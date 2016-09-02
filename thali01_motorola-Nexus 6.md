#### Test 8326889394b7a14_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-02 12:25:00.556  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:25:00.559  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 12:25:00.613  1515  2453 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-02 12:25:00.613  1515  2453 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 12:25:00.613  1515  2453 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:00.614  1515  2453 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 12:25:00.647  3560  3874 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-02 12:25:00.647  3560  3874 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jdm.a(PG:82)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jcs.o(PG:406)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jcn.a(PG:1379)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jcs.i(PG:143)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at blb.a(PG:3937)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at czp.a(PG:18188)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at czp.a(PG:9087)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at czq.run(PG:1686)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:25:00.647  3560  3874 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jdj.a(PG:4091)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jdj.a(PG:1125)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jdm.a(PG:77)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	... 12 more
09-02 12:25:00.647  3560  3874 E HttpOperation: Caused by: faj: BadAuthentication
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at fal.a(PG:38)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	at jdj.a(PG:4089)
09-02 12:25:00.647  3560  3874 E HttpOperation: 	... 14 more
09-02 12:25:00.876  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-02 12:25:00.877  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 12:25:00.877  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:00.877  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 12:25:00.890  3560  3879 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-02 12:25:00.890  3560  3879 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jdm.a(PG:82)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jcs.o(PG:406)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jcn.a(PG:1379)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jcs.i(PG:143)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at blb.a(PG:3937)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at czp.a(PG:18188)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at czp.a(PG:9081)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at czq.run(PG:1686)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:25:00.890  3560  3879 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jdj.a(PG:4091)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jdj.a(PG:1125)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jdm.a(PG:77)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	... 12 more
09-02 12:25:00.890  3560  3879 E HttpOperation: Caused by: faj: BadAuthentication
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at fal.a(PG:38)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	at jdj.a(PG:4089)
09-02 12:25:00.890  3560  3879 E HttpOperation: 	... 14 more
09-02 12:25:00.927  1515  2199 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-02 12:25:00.927  1515  2199 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 12:25:00.927  1515  2199 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:00.927  1515  2199 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 12:25:00.946  3560  3879 E HttpOperation: [getmobileexperiments] Unexpected exception
09-02 12:25:00.946  3560  3879 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jdm.a(PG:82)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jcs.o(PG:406)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jcn.a(PG:1379)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jcs.i(PG:143)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at hec.a(PG:42)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at hee.a(PG:102)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at czr.a(PG:65)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at kka.a(PG:108)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at czp.a(PG:19176)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at czp.a(PG:9081)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at czq.run(PG:1686)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:25:00.946  3560  3879 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jdj.a(PG:4091)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jdj.a(PG:1125)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jdm.a(PG:77)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	... 15 more
09-02 12:25:00.946  3560  3879 E HttpOperation: Caused by: faj: BadAuthentication
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at fal.a(PG:38)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	at jdj.a(PG:4089)
09-02 12:25:00.946  3560  3879 E HttpOperation: 	... 17 more
09-02 12:25:00.947  3560  3879 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-02 12:25:00.947  3560  3879 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jdm.a(PG:82)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jcs.o(PG:406)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jcn.a(PG:1379)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jcs.i(PG:143)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at hec.a(PG:42)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at hee.a(PG:102)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at czr.a(PG:65)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at kka.a(PG:108)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at czp.a(PG:19176)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at czp.a(PG:9081)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at czq.run(PG:1686)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jdj.a(PG:4091)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jdj.a(PG:1125)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jdm.a(PG:77)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	... 15 more
09-02 12:25:00.947  3560  3879 E ExperimentLoader: Caused by: faj: BadAuthentication
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at fal.a(PG:38)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	at jdj.a(PG:4089)
09-02 12:25:00.947  3560  3879 E ExperimentLoader: 	... 17 more
09-02 12:25:01.061   874   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 96257, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
09-02 12:25:01.315  3875  3875 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-02 12:25:01.320  3875  3875 D AndroidRuntime: CheckJNI is OFF
09-02 12:25:01.355  3875  3875 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-02 12:25:01.397  3875  3875 I Radio-JNI: register_android_hardware_Radio DONE
09-02 12:25:01.416  3875  3875 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 12:25:01.421   874  2009 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 12:25:01.480   874  2009 I ActivityManager: Start proc 3888:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-02 12:25:01.492  3875  3875 D AndroidRuntime: Shutting down VM
09-02 12:25:01.593  3888  3888 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-02 12:25:01.614  3888  3888 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-02 12:25:01.626  3888  3888 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9946-9953)
09-02 12:25:01.626  3888  3888 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:25:01.639  3888  3888 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5d44a3a}
09-02 12:25:01.639  3888  3888 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:25:01.639  3888  3888 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 12:25:01.645  3888  3888 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 12:25:01.646  3888  3888 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 12:25:01.657  3888  3888 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-02 12:25:01.666  3888  3888 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 12:25:01.666  3888  3888 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 12:25:01.666  3888  3888 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 12:25:01.666  3888  3888 I Adreno  : Build Date                       : 10/20/15
09-02 12:25:01.666  3888  3888 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 12:25:01.666  3888  3888 I Adreno  : Local Branch                     : M14
09-02 12:25:01.666  3888  3888 I Adreno  : Remote Branch                    : 
09-02 12:25:01.666  3888  3888 I Adreno  : Remote Branch                    : 
09-02 12:25:01.666  3888  3888 I Adreno  : Reconstruct Branch               : 
,09-02 12:25:01.750   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d39c6a:true
,09-02 12:25:01.782  3888  3888 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 12:25:01.794  3888  3888 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-02 12:25:01.874  3888  3925 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-02 12:25:01.888  3888  3912 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-02 12:25:01.924  3888  3925 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 12:25:01.949  1909  1909 I Keyboard.Facilitator: onFinishInput()
,09-02 12:25:02.012   874   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms (total +553ms)
,09-02 12:25:02.065  3888  3888 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3888
,09-02 12:25:02.233  3888  3888 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 12:25:02.400  3888  3928 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684338384
,09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 12:25:02.409  3888  3928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96a52d9 added. We now have 1 listener(s)
,09-02 12:25:02.414  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-02 12:25:02.415  3888  3928 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:25:02.416  3888  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:25:02.416  3888  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 12:25:02.421  3888  3928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fd174c added. We now have 1 listener(s)
09-02 12:25:02.421  3888  3928 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:02.429   874  1317 D WifiService: New client listening to asynchronous messages
,09-02 12:25:02.429  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:25:02.430  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 12:25:02.430  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 12:25:02.430  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 12:25:02.430  3888  3928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 12:25:02.432  3888  3928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:02.432  3888  3928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-02 12:25:02.448  3888  3928 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:02.448  3888  3928 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:02.448  3888  3928 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-02 12:25:02.448  3888  3928 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:02.449  3888  3928 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:25:02.454  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:02.459  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:02.491  3888  3888 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 12:25:03.345  3888  3934 W jxcore-log: Initializing JXcore engine
09-02 12:25:03.345  3888  3934 W jxcore-log: JXcore engine is ready
,09-02 12:25:03.385  3934  3934 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-02 12:25:03.385  3934  3934 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10668]" dev="sockfs" ino=10668 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-02 12:25:03.385  3934  3934 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-02 12:25:03.385  3934  3934 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26994]" dev="sockfs" ino=26994 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-02 12:25:03.400  3888  3934 W jxcore-log: Starting JXcore engine
,09-02 12:25:03.487  3888  3934 W jxcore-log: Platform android
09-02 12:25:03.487  3888  3934 W jxcore-log: 
,09-02 12:25:03.487  3888  3934 W jxcore-log: Process ARCH arm
09-02 12:25:03.487  3888  3934 W jxcore-log: 
,09-02 12:25:03.688  3888  3934 I jxcore-log: JXcore Cordova bridge is ready!
09-02 12:25:03.688  3888  3934 I jxcore-log: 
,09-02 12:25:03.689  3888  3934 W jxcore-log: JXcore engine is started
,09-02 12:25:03.695  3888  3928 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 12:25:03.699  3888  3888 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 12:25:05.723   874  2020 I ActivityManager: Start proc 3935:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,09-02 12:25:05.761  3935  3935 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-02 12:25:05.795  3935  3935 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-02 12:25:05.839  3935  3958 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 12:25:05.870  1515  2453 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-02 12:25:05.870  1515  2453 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-02 12:25:05.870  1515  2453 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:05.870  1515  2453 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-02 12:25:05.892  3935  3958 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-02 12:25:05.973  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:25:05.997  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-02 12:25:05.997  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-02 12:25:05.997  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:05.997  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:25:06.028  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-02 12:25:06.028  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-02 12:25:06.028  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-02 12:25:06.037   874  2020 I ActivityManager: Killing 3499:android.process.acore/u0a5 (adj 15): empty #17
,09-02 12:25:13.117  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 12:25:13.117  3888  3934 I jxcore-log: 
,09-02 12:25:13.119  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 12:25:13.119  3888  3934 I jxcore-log: 
,09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:13.129  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:25:13.134  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:25:13.136  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 12:25:13.136  3888  3934 I jxcore-log: 
,09-02 12:25:13.138  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 12:25:13.138  3888  3934 I jxcore-log: 
,09-02 12:25:13.632  3888  3934 D executeNativeTests: Running unit tests
,09-02 12:25:13.690  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:13.690  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 added. We now have 2 listener(s)
,09-02 12:25:13.691  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:13.691  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:13.691  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:13.691  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:13.691  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee added. We now have 2 listener(s)
09-02 12:25:13.691  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:13.692  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:25:13.695  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:13.707  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:25:13.709  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:25:13.709  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:25:13.711  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:13.712  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:13.719  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 12:25:13.720  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 12:25:13.720  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 12:25:13.725  3888  3934 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 12:25:13.726  3888  3934 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:25:13.727  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:25:13.727  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:25:13.727  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:25:13.729  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:25:13.730  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.731  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.732  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.732  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.732  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.733  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:13.733  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 removed from the list
09-02 12:25:13.733  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.733  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee removed from the list
09-02 12:25:13.733  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.734  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.734  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.734  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.735  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.735  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.736  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.736  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.737  3888  3934 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 12:25:13.738  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.738  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.738  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.738  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.738  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.738  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.738  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.738  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.738  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.738  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.738  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.738  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.739  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.739  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.739  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.739  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.740  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.740  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:25:13.744  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:25:13.745  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:25:13.746  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:25:13.746  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-02 12:25:13.746  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:25:13.746  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:25:13.746  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.746  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.746  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.746  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.746  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.746  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.746  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.746  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.746  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.746  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.746  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.747  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.747  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.747  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.748  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.748  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.748  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.748  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.748  3888  3934 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:25:13.750  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:13.755  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:13.757  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.757  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:13.758  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:13.759  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:13.759  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:25:13.760  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:25:13.760  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:13.760  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:25:13.760  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:13.766  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:25:13.766  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:25:13.772  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:25:13.774  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:25:13.774  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:25:13.777  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 12:25:13.780  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 12:25:13.780  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:25:13.781  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:25:13.781  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:25:13.783  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:13.787  2681  2692 D BtGatt.GattService: registerClient() - UUID=0f3a30de-d405-43de-8c59-e0d1817c43f7
09-02 12:25:13.788  2681  2700 D BtGatt.GattService: onClientRegistered() - UUID=0f3a30de-d405-43de-8c59-e0d1817c43f7, clientIf=5
09-02 12:25:13.788  3888  3899 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 12:25:13.789  2681  2809 D BtGatt.GattService: start scan with filters
09-02 12:25:13.793  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:25:13.793  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:25:13.793  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:25:13.793  2681  2703 D BtGatt.ScanManager: handling starting scan
09-02 12:25:13.793  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:25:13.796  2681  2703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:13.799  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:13.800  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:25:13.800  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:13.803  2681  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 12:25:13.803  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.804  2681  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 12:25:13.805  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 12:25:13.809  3888  3934 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:25:13.809  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:25:13.809  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.810  2681  2703 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:25:13.810  2681  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:25:13.814  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.814  3888  3934 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:25:13.814  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.814  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:25:13.814  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.814  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:25:13.814  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:25:13.814  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:25:13.814  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:25:13.815  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:25:13.815  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:25:13.815  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:25:13.816  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:13.817  2681  2809 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:25:13.818  2681  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 12:25:13.818  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.818  2681  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:25:13.819  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:25:13.819  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:25:13.819  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:25:13.819  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:13.819  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:25:13.820  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:13.821  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:25:13.821  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:25:13.821  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:25:13.822  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:25:13.823  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:25:13.823  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.823  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:13.824  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:13.824  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:13.824  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:25:13.824  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.824  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.824  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
,09-02 12:25:13.824  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.824  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list,
,09-02 12:25:13.824  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:25:13.825  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.825  3888  3934 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 12:25:13.827  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:25:13.830  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:25:13.830  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.830  2681  2703 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:13.833  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:13.837  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:25:13.837  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.838  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:25:13.838  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:13.838  2681  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:25:13.838  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:25:13.838  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 12:25:13.838  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:25:13.838  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:13.838  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:25:13.843  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:13.843  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:25:13.843  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:25:13.844  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:13.846  2681  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:25:13.846  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:13.854  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:25:13.855  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:25:13.855  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:25:13.861  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:25:13.861  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:25:13.861  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:25:13.861  3888  3934 D BluetoothAdapter: STATE_ON
,09-02 12:25:13.864  2681  2809 D BtGatt.GattService: registerClient() - UUID=a9458e5e-846b-4f7f-bdba-8e4baf3fad3c
,09-02 12:25:13.865  2681  2700 D BtGatt.GattService: onClientRegistered() - UUID=a9458e5e-846b-4f7f-bdba-8e4baf3fad3c, clientIf=5
,09-02 12:25:13.866  3888  3898 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:25:13.866  2681  2693 D BtGatt.GattService: start scan with filters
,09-02 12:25:13.870  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:25:13.870  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:25:13.870  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:25:13.870  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:25:13.870  2681  2703 D BtGatt.ScanManager: handling starting scan
,09-02 12:25:13.872  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:25:13.872  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:13.872  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:25:13.873  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:25:13.875  3888  3934 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:25:13.878  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:25:13.879  3888  3934 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:25:13.879  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:25:13.879  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:25:13.879  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.879  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-02 12:25:13.879  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:25:13.879  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 12:25:13.879  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:25:13.879  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 12:25:13.879  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:25:13.879  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:25:13.879  2681  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 12:25:13.879  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:13.880  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:13.880  2681  2809 D BtGatt.GattService: stopScan() - queue size =1
,09-02 12:25:13.880  2681  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 12:25:13.880  2681  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:25:13.881  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:25:13.881  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 12:25:13.881  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:25:13.881  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:13.881  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:25:13.881  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:13.882  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:25:13.882  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 12:25:13.882  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:25:13.882  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.883  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:13.883  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:13.883  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:13.883  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.883  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.884  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.884  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.884  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.884  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.884  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:25:13.884  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.884  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.884  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.885  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.885  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.885  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.885  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.885  3888  3934 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:25:13.886  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:13.890  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:13.891  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:13.891  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 12:25:13.891  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:13.891  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:13.892  2681  2703 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 12:25:13.892  2681  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:25:13.893  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:13.893  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 12:25:13.893  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:25:13.893  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:13.893  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:13.893  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:25:13.895  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:13.897  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 12:25:13.897  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:25:13.900  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:25:13.900  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:25:13.900  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:25:13.903  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:25:13.903  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:25:13.903  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:25:13.903  3888  3934 D BluetoothAdapter: STATE_ON
,09-02 12:25:13.906  2681  2693 D BtGatt.GattService: registerClient() - UUID=0696984c-fd3e-4874-8c6b-9d56bd965150
,09-02 12:25:13.907  2681  2700 D BtGatt.GattService: onClientRegistered() - UUID=0696984c-fd3e-4874-8c6b-9d56bd965150, clientIf=5,
,09-02 12:25:13.907  2681  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:25:13.907  3888  3898 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:25:13.907  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:13.908  2681  2692 D BtGatt.GattService: start scan with filters
,09-02 12:25:13.917  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:25:13.917  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:25:13.917  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.918  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 12:25:13.918  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:25:13.919  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:25:13.920  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:25:13.921  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:13.921  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:25:13.922  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:25:13.926  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:25:13.926  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.926  2681  2703 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:25:13.927  3888  3934 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:25:13.927  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.927  3888  3934 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:25:13.927  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.927  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:25:13.927  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.927  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:25:13.927  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:25:13.927  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 12:25:13.927  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:25:13.928  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 12:25:13.928  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-02 12:25:13.928  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 12:25:13.930  3888  3934 D BluetoothAdapter: STATE_ON,
09-02 12:25:13.931  2681  2809 D BtGatt.GattService: stopScan() - queue size =0
,09-02 12:25:13.933  2681  2692 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 12:25:13.933  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:25:13.933  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.933  2681  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:25:13.934  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:25:13.934  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:25:13.934  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:25:13.934  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:13.935  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:25:13.937  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:13.937  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:25:13.938  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 12:25:13.938  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:25:13.938  2681  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 12:25:13.938  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.939  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.941  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:13.941  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:13.941  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:13.941  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.941  2681  2703 D BtGatt.ScanManager: handling starting scan
,09-02 12:25:13.941  3888  3934 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:25:13.941  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.942  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:25:13.942  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.942  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.942  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:13.942  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
,09-02 12:25:13.943  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.943  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.943  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.943  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.946  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.946  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.948  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:13.948  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.948  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.948  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.949  3888  3934 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-02 12:25:13.950  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.950  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:25:13.950  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.951  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.951  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.951  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.951  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.951  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.951  2681  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:25:13.951  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.951  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.951  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:25:13.951  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.951  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.951  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.952  2681  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:25:13.952  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.953  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:13.953  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:25:13.953  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.954  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.956  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-02 12:25:13.956  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.956  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.956  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:25:13.957  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.957  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.957  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.957  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.958  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.958  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.958  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.958  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.958  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.958  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.958  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.960  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:25:13.960  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.960  2681  2703 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:25:13.960  2681  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:25:13.961  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:13.961  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.961  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.961  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.963  3888  3934 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 12:25:13.963  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.963  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.963  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.964  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.964  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.964  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.964  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.964  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.964  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.964  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.964  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.964  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.965  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.965  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.966  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.966  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:13.966  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.966  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.967  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 12:25:13.967  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:13.967  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.967  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.967  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:13.967  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.967  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.967  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.967  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:13.967  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.968  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:25:13.968  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.968  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.968  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.968  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.969  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.969  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:25:13.969  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.969  2681  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 12:25:13.969  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.969  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.970  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:25:13.972  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:25:13.972  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 12:25:13.972  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:25:13.972  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:25:13.972  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:25:13.975  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:25:13.975  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:25:13.975  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.975  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:13.975  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:13.976  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:25:13.976  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.976  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:13.976  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:13.976  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.976  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
,09-02 12:25:13.976  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:13.976  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:13.976  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.976  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:13.976  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:13.978  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:13.978  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:25:13.978  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:13.978  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:13.980  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-02 12:25:13.981  3888  3934 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:25:13.981  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:25:13.985  2681  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:25:13.985  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.986  2681  2703 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:25:13.988  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:25:13.989  3888  3934 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:25:13.989  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:25:13.990  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-02 12:25:13.992  2681  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:25:13.992  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.992  2681  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:25:13.991  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:25:13.992  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:25:13.992  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:25:13.992  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:25:13.993  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:25:13.993  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:25:13.993  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 12:25:13.994  3888  3934 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:25:13.995  3888  3934 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 12:25:13.995  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:25:13.995  3888  3934 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:25:13.997  3888  3934 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 12:25:13.997  2681  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:25:13.997  2681  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:13.997  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:25:13.997  3888  3934 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:25:13.997  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 12:25:14.002  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 12:25:14.003  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 12:25:14.004  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 12:25:14.005  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 12:25:14.005  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 12:25:14.005  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 12:25:14.005  3888  3959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
09-02 12:25:14.005  3888  3934 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:25:14.005  3888  3934 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 12:25:14.006  3888  3959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:14.007  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.007  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.007  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.007  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.007  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.007  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.007  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 12:25:14.008  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.008  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.009  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.009  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.009  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.009  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.009  3888  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
09-02 12:25:14.009  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.009  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.009  3888  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
09-02 12:25:14.009  3888  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
09-02 12:25:14.009  3888  3959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
09-02 12:25:14.010  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.010  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.010  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.011  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.012  3888  3934 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 12:25:14.012  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.012  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.012  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.012  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.012  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.012  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.012  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.013  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.013  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.013  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.013  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.013  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.013  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.013  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.014  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.014  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.014  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.014  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.015  3888  3934 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 12:25:14.015  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.015  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.015  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.016  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.016  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.016  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.016  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.016  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.016  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.016  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.016  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.016  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.016  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.017  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.018  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.018  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.018  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.018  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 12:25:14.019  3888  3934 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:25:14.019  3888  3934 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:25:14.019  3888  3934 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:25:14.019  3888  3934 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:25:14.019  3888  3934 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:25:14.019  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:25:14.020  3888  3934 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 12:25:14.020  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.020  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.020  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.020  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.020  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.020  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.020  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.021  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.021  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.021  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.021  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.021  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.021  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:14.021  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.022  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.022  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.022  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.022  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.023  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.023  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.023  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.023  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.023  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.023  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.023  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.023  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.023  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.024  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.024  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.024  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.024  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.024  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.024  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.024  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.024  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.024  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.024  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.024  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.024  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.025  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.025  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.025  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.025  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.025  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.025  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.025  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.025  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.026  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.026  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.026  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.026  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.028  3888  3934 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 12:25:14.028  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:14.029  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 12:25:14.029  3888  3934 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 12:25:14.029  3888  3934 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 12:25:14.030  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 12:25:14.030  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:25:14.030  3888  3888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 12:25:14.030  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.030  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 12:25:14.030  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 12:25:14.030  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 12:25:14.030  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.031  3888  3934 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 12:25:14.031  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.031  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.031  3888  3888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 12:25:14.031  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:25:14.031  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:25:14.031  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:25:14.031  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.031  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.031  3888  3961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:14.032  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:14.032  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.032  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.032  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:14.032  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:14.032  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.032  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:14.032  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.033  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.033  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.033  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.033  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.033  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.033  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.033  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.033  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.033  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.033  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.033  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.034  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.034  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.034  3888  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 12:25:14.034  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.034  3888  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 12:25:14.034  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.034  3888  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 12:25:14.035  3888  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 12:25:14.036  3888  3934 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 12:25:14.036  3888  3934 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:25:14.036  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:25:14.036  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:25:14.036  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.036  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.036  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.036  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.036  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.037  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.037  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.037  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.037  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.037  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.037  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.037  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.037  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.037  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.038  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.038  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.038  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.038  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.042  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.042  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.042  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.042  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.042  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.042  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.043  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.043  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.043  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.043  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.043  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.043  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.043  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.043  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.044  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.044  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.044  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.044  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.045  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:14.045  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:14.045  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:14.045  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:14.045  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.045  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.045  3888  3934 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f954169 not in the list
09-02 12:25:14.045  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.046  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.046  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:14.046  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.046  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.046  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:14.046  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:14.047  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:14.047  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:14.047  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:14.047  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb107ee not in the list
09-02 12:25:14.048  3888  3934 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 12:25:14.048  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:25:14.048  3888  3934 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 12:25:14.048  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:25:14.048  3888  3934 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 12:25:14.048  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:25:14.050  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:25:14.050  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 12:25:14.051  3888  3934 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 12:25:14.051  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:25:14.051  3888  3934 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 12:25:14.051  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:25:14.051  3888  3934 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 12:25:14.051  3888  3934 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 12:25:14.052  3888  3934 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 12:25:14.052  3888  3934 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 12:25:14.052  3888  3934 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 12:25:14.053  3888  3934 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 12:25:14.053  3888  3934 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 12:25:14.053  3888  3934 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 12:25:14.054  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:14.054  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1781d20 added. We now have 2 listener(s)
09-02 12:25:14.054  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:14.056  3888  3934 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 12:25:14.056   874  2022 D WifiService: setWifiEnabled: true pid=3888, uid=10000
09-02 12:25:14.056   874  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:25:14.057  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:14.057  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc456d9 added. We now have 3 listener(s)
09-02 12:25:14.057  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:14.062  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:14.062  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de5489e added. We now have 4 listener(s)
09-02 12:25:14.062  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:14.064  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:14.064  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef43f7f added. We now have 5 listener(s)
09-02 12:25:14.064  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:14.065   874  2027 D WifiService: setWifiEnabled: false pid=3888, uid=10000
09-02 12:25:14.065   874  2027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:25:14.070  2681  2696 D BluetoothAdapterState: Current state: ON, message: 23
09-02 12:25:14.070  2681  2696 D BluetoothAdapterProperties: Setting state to 13
09-02 12:25:14.070  2681  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:25:14.071  2681  2696 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:25:14.073  2681  2681 D BluetoothMapService: onReceive
09-02 12:25:14.073  2681  2681 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:25:14.074  2681  2696 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:14.074  2681  2681 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:25:14.074  2681  2681 D BluetoothMapService: MAP Service closeService in
09-02 12:25:14.074  2681  2681 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 12:25:14.074  2681  2681 D ObexServerSockets0: shutdown(block = true)
09-02 12:25:14.075  2681  2681 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 12:25:14.075  2681  2830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 12:25:14.075  2681  2681 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 12:25:14.075  2681  2805 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 12:25:14.075  2681  2831 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 12:25:14.076  2681  2681 I BtOppRfcommListener: stopping Accept Thread
09-02 12:25:14.076  2681  3416 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:25:14.076  2681  3416 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:25:14.077  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:14.077  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:14.078  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.078  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:14.078  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:25:14.079   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 12:25:14.080   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 12:25:14.080   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:25:14.080   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:25:14.087   874  1316 E native  : do suspend true
09-02 12:25:14.092   874   888 I ActivityManager: Start proc 3964:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-02 12:25:14.093  2681  2700 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:25:14.093  2681  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 12:25:14.094  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:14.096  2681  2681 D HeadsetService: Received stop request...Stopping profile...
09-02 12:25:14.097   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:14.097   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:14.098  1989  2131 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:14.098   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:14.098  1374  1392 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:14.101   874  1855 D DhcpClient: Clearing IP address
09-02 12:25:14.101  2681  2681 D A2dpService: Received stop request...Stopping profile...
09-02 12:25:14.101  2681  2811 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:25:14.101   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:25:14.103  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:14.103  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:25:14.103   874   874 D BluetoothA2dp: Proxy object disconnected
,09-02 12:25:14.103  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:14.104   372   872 D CommandListener: Setting iface cfg
09-02 12:25:14.105  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:14.105  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:25:14.105  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:25:14.105  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:14.105  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.105  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:14.105  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:14.107   874  1862 D DhcpClient: Receive thread stopped
09-02 12:25:14.108  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:14.109  1374  1374 D HeadsetProfile: Bluetooth service disconnected
09-02 12:25:14.109  2681  2681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 12:25:14.109  2681  2681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 12:25:14.109  2681  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-02 12:25:14.109  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:14.109  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:25:14.109  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:25:14.110  2681  2700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-02 12:25:14.110  1374  1374 D BluetoothA2dp: Proxy object disconnected
,09-02 12:25:14.110  2681  2681 D HidService: Received stop request...Stopping profile...
09-02 12:25:14.110  2681  2681 D HidService: Stopping Bluetooth HidService
,09-02 12:25:14.111  1374  1374 D BluetoothInputDevice: Proxy object disconnected
,09-02 12:25:14.111  1374  1374 D HidProfile: Bluetooth service disconnected
,09-02 12:25:14.112  2681  2681 D HealthService: Received stop request...Stopping profile...
,09-02 12:25:14.112   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:25:14.112   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-02 12:25:14.112   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-02 12:25:14.115   403   403 E Parcel  : Reading a NULL string not supported here.
,09-02 12:25:14.116  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:14.117   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:25:14.117   874  1316 E native  : do suspend true
,09-02 12:25:14.119  2681  2681 D PanService: Received stop request...Stopping profile...
,09-02 12:25:14.120  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:14.120  2681  2681 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:25:14.120  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:14.120  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:14.121  2681  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 12:25:14.121  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:14.121  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:14.121  2681  2774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 12:25:14.121  2681  2774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 12:25:14.122  2681  2774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:25:14.122  2681  2774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:25:14.122  2681  2681 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:25:14.122  2681  2681 D BluetoothMapService: stop()
,09-02 12:25:14.123  2681  2681 D BluetoothMapAppObserver: deinitObservers()
09-02 12:25:14.123  2681  2681 D BluetoothMapAppObserver: removeReceiver()
,09-02 12:25:14.123   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 12:25:14.125  2681  2681 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:25:14.125  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.125  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:14.125  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:14.125  2681  2681 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:25:14.125  2681  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 12:25:14.125  2681  2681 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:25:14.126  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:14.126  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.126  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:14.126  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:14.126  2681  2681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:25:14.127  2681  2700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 12:25:14.127  2681  2681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:25:14.128  2681  2681 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:25:14.128  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.128  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:14.128  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:14.128  2681  2681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:25:14.129  2681  2681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 12:25:14.129  2681  2681 D BluetoothMapService: MAP Service closeService in
,09-02 12:25:14.129  2681  2681 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:25:14.130  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.130  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:14.130  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:14.130  2681  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-02 12:25:14.130  2681  2696 D BluetoothAdapterProperties: Setting state to 15
09-02 12:25:14.130  2681  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 12:25:14.130   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:14.130   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:14.131  1374  2129 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:25:14.131  2681  2696 I BluetoothAdapterState: Entering BleOnState
09-02 12:25:14.131  1374  1392 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:14.131  1374  1386 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:25:14.132  2681  2681 D BluetoothMapService: cleanup()
,09-02 12:25:14.132  2681  2681 D BluetoothMapService: MAP Service closeService in
09-02 12:25:14.132  1374  3887 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:25:14.132   874   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:25:14.133  1989  2131 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:14.133  1374  2129 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:25:14.133  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:25:14.137  1515  2436 V NativeCrypto: Read error: ssl=0x9a802600: I/O error during system call, Connection timed out
09-02 12:25:14.137   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:14.138  2681  2696 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 12:25:14.138  2681  2696 D BluetoothAdapterProperties: Setting state to 16
09-02 12:25:14.138  2681  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-02 12:25:14.139  2681  2696 D BluetoothAdapterProperties: onBleDisable
09-02 12:25:14.139  2681  2696 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:14.139  2681  2697 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 12:25:14.140  2681  2700 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:25:14.141  2681  2774 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 12:25:14.141  2681  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:14.142  1515  2436 V NativeCrypto: SSL shutdown failed: ssl=0x9a802600: I/O error during system call, Broken pipe
09-02 12:25:14.143  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:14.143  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:14.144  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.144  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:14.145  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:14.146  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:14.146  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.147  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:14.148  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:14.149  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:14.160   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 12:25:14.171  3964  3964 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-02 12:25:14.183   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 12:25:14.184   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:25:14.184   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 12:25:14.184   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:25:14.187   874   892 D Tethering: MasterInitialState.processMessage what=3
09-02 12:25:14.187   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-02 12:25:14.190  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:14.191  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:14.196  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:25:14.204   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:25:14.205  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:25:14.206  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:14.206  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:14.207  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:14.207  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:14.207   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:25:14.209  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:14.209  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:14.210  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:14.210  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:14.211   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff7ffce:true
,09-02 12:25:14.216  1871  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:25:14.218   874  2047 I ActivityManager: Start proc 3986:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-02 12:25:14.226  3964  3964 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 12:25:14.227   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-02 12:25:14.230  3964  3964 D BluetoothMap: Create BluetoothMap proxy object
,09-02 12:25:14.235  3964  3964 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 12:25:14.247  3964  3964 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:25:14.251   874  2009 I ActivityManager: Killing 3656:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-02 12:25:14.260  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-02 12:25:14.343  2681  2700 I bt_hci  : shut_down
,09-02 12:25:14.353  2681  2704 I bt_vendor: low_power_mode_cb
,09-02 12:25:14.358  2681  2704 D bt_hwcfg: hw_epilog_process
,09-02 12:25:14.374  2681  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 12:25:14.374  2681  2704 I bt_vendor: epilog_cb
,09-02 12:25:14.374  2681  2704 I bt_hci  : epilog_finished_callback
,09-02 12:25:14.380  2681  2700 I bt_hci_h4: hal_close
,09-02 12:25:14.381  2681  2700 I bt_userial_vendor: device fd = 51 close
,09-02 12:25:14.424  3986  3986 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.424  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:583)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:25:14.425  3986  3986 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:14.425  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:25:14.433  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:25:14.446  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:25:14.456  3964  3964 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:25:14.465   874  1696 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,09-02 12:25:14.534  3888  3888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:25:14.559   874  1696 I ActivityManager: Start proc 4017:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-02 12:25:14.564  2681  2697 D bt_stack_manager: event_shut_down_stack finished.
,09-02 12:25:14.564  2681  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 12:25:14.568  2681  2696 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 12:25:14.568  2681  2681 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:25:14.569  2681  2681 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 12:25:14.569  2681  2681 D BtGatt.GattService: stop()
09-02 12:25:14.570  2681  2681 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 12:25:14.571  2681  2681 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:14.571  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:14.571  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:14.571  2681  2681 V BluetoothAdapterState: isBleTurningOff()=true
09-02 12:25:14.571  2681  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-02 12:25:14.571  2681  2696 D BluetoothAdapterProperties: Setting state to 10
,09-02 12:25:14.571  2681  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 12:25:14.572  2681  2696 I BluetoothAdapterState: Entering OffState
,09-02 12:25:14.572   874   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-02 12:25:14.581  2681  2681 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 12:25:14.581  2681  2681 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-02 12:25:14.581  2681  2681 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 12:25:14.582  2681  2697 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-02 12:25:14.583  2681  2697 D bt_stack_manager: event_clean_up_stack finished.
,09-02 12:25:14.587  2681  2681 I art     : System.exit called, status: 0
,09-02 12:25:14.587  2681  2681 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:25:14.636   874   886 I ActivityManager: Process com.android.bluetooth (pid 2681) has died
,09-02 12:25:14.649  4017  4017 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-02 12:25:14.748  3986  4003 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 12:25:14.816  4017  4037 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-02 12:25:14.816  4017  4037 I Babel_SMS: MmsConfig.loadMmsSettings
09-02 12:25:14.823  4017  4037 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
09-02 12:25:14.823  4017  4037 I Babel_SMS: MmsConfig.loadFromDatabase
,09-02 12:25:14.857  4017  4037 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-02 12:25:14.857  4017  4037 I Babel_SMS: MmsConfig.loadFromResources
,09-02 12:25:14.858  4017  4037 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 12:25:14.860  4017  4037 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-02 12:25:14.940  4017  4017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:25:14.944  4017  4017 I Babel_Crash: startup - clean
,09-02 12:25:14.956   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@369bac7:true
,09-02 12:25:14.981  4017  4017 I Babel_telephony: TeleModule.launchCompleted
,09-02 12:25:14.995   874  2028 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-02 12:25:15.001  4017  4017 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-02 12:25:15.008  4017  4017 W Babel   : BAM#gBA: invalid account id: -1
09-02 12:25:15.008  4017  4017 W Babel   : BAM#gBA: invalid account id: -1
,09-02 12:25:15.008  4017  4017 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-02 12:25:15.020  4017  4042 I Babel   : deleted: false for 0
,09-02 12:25:15.022   874  2027 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-02 12:25:15.065  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:25:15.071  1715  1715 D SystemUpdateService: onCreate
,09-02 12:25:15.079  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:25:15.104  1715  4044 I SystemUpdateService: active receiver: enabled
,09-02 12:25:15.109  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 12:25:15.113  1715  4044 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-02 12:25:15.113  1715  2410 I iu.UploadsManager: num queued entries: 0
09-02 12:25:15.114  1715  2410 I iu.UploadsManager: num updated entries: 0
09-02 12:25:15.115  1715  2410 I iu.SyncManager: NEXT; no task
,09-02 12:25:15.120  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:25:15.130  1715  4044 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-02 12:25:15.130  1715  4044 I SystemUpdateService: now status is 0 (complete)
09-02 12:25:15.130  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:25:15.130  1715  4044 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 12:25:15.131  1715  4044 I SystemUpdateService: file has been verified
,09-02 12:25:15.132  1715  4044 I SystemUpdateService: OTA package size = 12249756
,09-02 12:25:15.138  1715  4044 I SystemUpdateService: showing system update notification
,09-02 12:25:15.145   874  2009 I ActivityManager: Start proc 4046:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-02 12:25:15.158  1715  1715 D SystemUpdateService: onDestroy
,09-02 12:25:15.177  4017  4017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:25:15.199  4046  4046 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-02 12:25:15.209  4046  4046 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:25:15.236  4046  4046 D SprintDMHelper: simOperator: 
09-02 12:25:15.236  4046  4046 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:25:15.251  4017  4017 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 12:25:15.262  4017  4017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-02 12:25:15.267  4017  4017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:25:15.274  4017  4017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:25:15.278  4017  4017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:25:15.283   874  2020 I ActivityManager: Start proc 4058:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-02 12:25:15.285   874  2020 I ActivityManager: Killing 2067:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-02 12:25:15.329  4017  4017 I vclib   : onServiceConnected
,09-02 12:25:15.449   874  2020 I ActivityManager: Start proc 4073:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-02 12:25:15.454  4017  4072 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-02 12:25:15.458   874  1611 I ActivityManager: Killing 3695:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-02 12:25:15.507  4073  4073 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-02 12:25:15.555  4073  4073 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 12:25:15.555  4073  4073 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 12:25:15.555  4073  4073 I GAv4    :   adb logcat -s GAv4
,09-02 12:25:15.567  4073  4073 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:25:15.571  4073  4073 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:25:15.600  4073  4090 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:25:15.707  4073  4073 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-02 12:25:15.745  4073  4073 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-02 12:25:15.755  4073  4073 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4078-4082)
,09-02 12:25:15.755  4073  4073 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 12:25:15.768  4073  4073 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6e2614e}
,09-02 12:25:15.768  4073  4073 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 12:25:15.768  4073  4073 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:25:15.777  4073  4073 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 12:25:15.778  4073  4073 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 12:25:15.796  4073  4073 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-02 12:25:15.808  4073  4073 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
09-02 12:25:15.808  4073  4073 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 12:25:15.808  4073  4073 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 12:25:15.808  4073  4073 I Adreno  : Build Date                       : 10/20/15
09-02 12:25:15.808  4073  4073 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 12:25:15.808  4073  4073 I Adreno  : Local Branch                     : M14
09-02 12:25:15.808  4073  4073 I Adreno  : Remote Branch                    : 
09-02 12:25:15.808  4073  4073 I Adreno  : Remote Branch                    : 
09-02 12:25:15.808  4073  4073 I Adreno  : Reconstruct Branch               : 
,09-02 12:25:15.870  4073  4073 I NSApplication: Starting up...
,09-02 12:25:15.880  4073  4119 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 12:25:15.916   874  2032 I ActivityManager: Start proc 4124:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-02 12:25:15.921   874  2032 I ActivityManager: Killing 3621:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-02 12:25:16.024  4124  4124 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-02 12:25:16.209   874  1381 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-02 12:25:17.110   874  1611 D WifiService: setWifiEnabled: true pid=3888, uid=10000
,09-02 12:25:17.111   874  1611 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:25:17.132   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:25:17.134  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:17.134  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:17.134  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:17.134  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:17.137  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:17.137  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:17.137  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:17.138  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:17.148   874  1316 D WifiConfigStore: loaded 0 passpoint configs
09-02 12:25:17.149   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-02 12:25:17.150   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-02 12:25:17.151   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:25:17.152   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-02 12:25:17.152   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-02 12:25:17.152   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 12:25:17.177   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-02 12:25:17.177   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 12:25:17.179   372   872 D CommandListener: Setting iface cfg
,09-02 12:25:17.186   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-02 12:25:17.187   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:25:17.187   874  1316 E native  : do suspend true
,09-02 12:25:17.198   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:25:17.218   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 12:25:17.219   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 12:25:18.572   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-02 12:25:18.626   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.81 rxSuccessRate=9.69 delta 1000 -> 994
,09-02 12:25:18.629   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-02 12:25:18.629   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:18.642   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 12:25:18.685   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 12:25:18.687  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 12:25:19.115  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:25:19.155  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 12:25:19.155  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 12:25:19.160   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:25:19.181   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-02 12:25:19.182   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 12:25:19.182   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:19.209   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:19.224   372   872 D CommandListener: Setting iface cfg
,09-02 12:25:19.225   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-02 12:25:19.234   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 12:25:19.259   874  4150 D DhcpClient: Receive thread started
,09-02 12:25:19.342   874  1316 E native  : do suspend false
,09-02 12:25:19.353   874  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 12:25:19.370   874  4150 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172615, domain null
,09-02 12:25:19.371   874  1855 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172615 seconds
09-02 12:25:19.372   874  1855 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 12:25:19.384   874  4150 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 12:25:19.385   874  1855 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 12:25:19.389   372   872 D CommandListener: Setting iface cfg
,09-02 12:25:19.401   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 12:25:19.401   874  1855 D DhcpClient: Scheduling renewal in 86399s
09-02 12:25:19.404   874  1316 E native  : do suspend true
,09-02 12:25:19.429   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 12:25:19.433   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 12:25:19.434   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 12:25:19.437   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 12:25:19.447   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 12:25:19.503   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 12:25:19.503   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 12:25:19.504   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-02 12:25:19.506   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-02 12:25:19.507   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 12:25:19.518   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 12:25:19.524   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-02 12:25:19.525   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-02 12:25:19.525   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-02 12:25:19.525   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-02 12:25:19.525   874  1318 D ConnectivityService:    accepting network in place of null
09-02 12:25:19.526   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 12:25:19.527   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:25:19.538   874  4149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207865, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 12:25:19.567   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:25:19.603   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:25:19.613   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 12:25:19.614   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:25:19.623   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-02 12:25:19.631  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:19.632  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:19.633  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:19.633  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:19.633   874   892 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:25:19.640  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:25:19.641  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:25:19.641  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:19.641  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:25:19.644   874  4148 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:804::200e
,09-02 12:25:19.652  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:25:19.654  1715  1715 D SystemUpdateService: onCreate
,09-02 12:25:19.658  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:25:19.661  1715  4159 I SystemUpdateService: active receiver: enabled
,09-02 12:25:19.664  1715  4159 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:25:19.665  1715  4159 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 12:25:19.665  1715  4159 I SystemUpdateService: now status is 0 (complete)
,09-02 12:25:19.666  1715  4159 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 12:25:19.666  1715  4159 I SystemUpdateService: file has been verified
,09-02 12:25:19.666  1715  4159 I SystemUpdateService: OTA package size = 12249756
,09-02 12:25:19.671  1715  4159 I SystemUpdateService: showing system update notification
,09-02 12:25:19.690  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 12:25:19.691  1715  1715 D SystemUpdateService: onDestroy
,09-02 12:25:19.698  1715  2410 I iu.UploadsManager: num queued entries: 0
,09-02 12:25:19.699  1715  2410 I iu.UploadsManager: num updated entries: 0
,09-02 12:25:19.701  1715  2410 I iu.SyncManager: NEXT; no task
,09-02 12:25:19.707  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:25:19.709  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:25:19.711  4046  4046 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:25:19.714  1715  4162 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 12:25:19.714  1715  4162 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 12:25:19.715  4046  4046 D SprintDMHelper: simOperator: 
09-02 12:25:19.715  4046  4046 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:25:19.715  1715  4162 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 12:25:19.723  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 12:25:19.725  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:25:19.733   874  4148 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:25:19 GMT], X-Android-Received-Millis=[1472811919732], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472811919702]}
09-02 12:25:19.733   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-02 12:25:19.733   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-02 12:25:19.734   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 12:25:19.735   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 12:25:19.738  4017  4017 I art     : Waiting for a blocking GC DisableMovingGc
,09-02 12:25:19.741  4017  4017 I art     : Starting a blocking GC DisableMovingGc
,09-02 12:25:19.762  1515  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 12:25:19.762  1515  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 12:25:19.762  1515  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:25:19.762  1515  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:25:19.796  1715  4162 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-02 12:25:19.887  4017  4165 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 12:25:19.901   874  2020 I ActivityManager: Killing 3785:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-02 12:25:20.121   874  2047 D WifiService: setWifiEnabled: false pid=3888, uid=10000
09-02 12:25:20.121   874  2047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:25:20.153  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 12:25:20.162   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 12:25:20.162   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 12:25:20.163   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:25:20.163   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:20.189   874  1316 E native  : do suspend true
,09-02 12:25:20.203   874  1855 D DhcpClient: Clearing IP address
,09-02 12:25:20.203   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:25:20.208   372   872 D CommandListener: Setting iface cfg
,09-02 12:25:20.214  1515  4169 V NativeCrypto: Read error: ssl=0x9a802600: I/O error during system call, Connection timed out
,09-02 12:25:20.225   874  4150 D DhcpClient: Receive thread stopped
,09-02 12:25:20.235   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-02 12:25:20.235   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-02 12:25:20.237   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-02 12:25:20.237  1515  4169 V NativeCrypto: SSL shutdown failed: ssl=0x9a802600: I/O error during system call, Broken pipe
09-02 12:25:20.238   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 12:25:20.238   874  1316 E native  : do suspend true
09-02 12:25:20.240   403   403 E Parcel  : Reading a NULL string not supported here.
,09-02 12:25:20.247   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-02 12:25:20.280   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:25:20.306   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:25:20.307   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 12:25:20.307   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:25:20.307   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:25:20.310   874   892 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:25:20.312  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:20.312  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:20.312  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:20.312  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:20.313  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:20.314  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:20.314  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:20.314  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:20.324  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:25:20.330  1715  1715 D SystemUpdateService: onCreate
,09-02 12:25:20.333  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:25:20.348  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 12:25:20.351  1715  2410 I iu.UploadsManager: num queued entries: 0
,09-02 12:25:20.354  1715  4179 I SystemUpdateService: active receiver: enabled
,09-02 12:25:20.355  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:25:20.356  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:25:20.358  4046  4046 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:25:20.351  1715  2410 I iu.UploadsManager: num updated entries: 0
,09-02 12:25:20.362  4046  4046 D SprintDMHelper: simOperator: 
09-02 12:25:20.362  4046  4046 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:25:20.369  1715  4179 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:25:20.399  4017  4182 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-02 12:25:20.401  1715  2410 I iu.SyncManager: NEXT; no task
,09-02 12:25:20.407  1715  4179 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 12:25:20.407  1715  4179 I SystemUpdateService: now status is 0 (complete)
09-02 12:25:20.407  1715  4179 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 12:25:20.407  1715  4179 I SystemUpdateService: file has been verified
09-02 12:25:20.407  1715  4179 I SystemUpdateService: OTA package size = 12249756
,09-02 12:25:20.411   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-02 12:25:20.413   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-02 12:25:20.415   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-02 12:25:20.429  1715  4179 I SystemUpdateService: showing system update notification
,09-02 12:25:20.437   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-02 12:25:20.439  1715  1715 D SystemUpdateService: onDestroy
,09-02 12:25:20.441  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:20.441  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:20.441  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:20.441  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:20.442  1871  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:25:20.442  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:20.442  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:20.442  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:20.442  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:20.451   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-02 12:25:20.612   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 12:25:23.162   874   892 I ActivityManager: Start proc 4189:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 12:25:23.309  4189  4189 D AdapterServiceConfig: Adding HeadsetService
,09-02 12:25:23.310  4189  4189 D AdapterServiceConfig: Adding A2dpService,
09-02 12:25:23.310  4189  4189 D AdapterServiceConfig: Adding HidService
09-02 12:25:23.311  4189  4189 D AdapterServiceConfig: Adding HealthService
,09-02 12:25:23.311  4189  4189 D AdapterServiceConfig: Adding PanService
09-02 12:25:23.311  4189  4189 D AdapterServiceConfig: Adding GattService,
09-02 12:25:23.312  4189  4189 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 12:25:23.333   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bae5467:true
,09-02 12:25:23.334  4189  4189 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 12:25:23.339  4189  4189 I bt_bluedroid: init
,09-02 12:25:23.339  4189  4201 I BluetoothAdapterState: Entering OffState
,09-02 12:25:23.345  4189  4202 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 12:25:23.345  4189  4202 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:25:23.345  4189  4202 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 12:25:23.346  4189  4202 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:25:23.348  4189  4189 I bt_bluedroid: get_profile_interface socket
,09-02 12:25:23.350  4189  4189 I bt_bluedroid: get_profile_interface sdp
,09-02 12:25:23.354  4189  4200 I bt_bluedroid: config_hci_snoop_log
,09-02 12:25:23.355   874   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 12:25:23.356  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:25:23.362  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:25:23.362  4189  4201 D BluetoothAdapterState: Current state: OFF, message: 0
09-02 12:25:23.362  4189  4201 D BluetoothAdapterProperties: Setting state to 14
09-02 12:25:23.363  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 12:25:23.364  4189  4201 D BluetoothBondStateMachine: make
,09-02 12:25:23.368  4189  4206 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 12:25:23.374  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:25:23.374  4189  4189 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 12:25:23.378  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:23.378  4189  4189 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:25:23.379  4189  4189 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:25:23.379  4189  4189 D BtGatt.GattService: start()
09-02 12:25:23.379  4189  4189 I bt_bluedroid: get_profile_interface gatt
,09-02 12:25:23.380  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:23.380  4189  4189 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:25:23.390  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:23.390  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:23.390  4189  4189 V BluetoothAdapterState: isBleTurningOn()=true
09-02 12:25:23.390  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:23.391  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-02 12:25:23.392  4189  4201 I bt_bluedroid: enable
09-02 12:25:23.392  4189  4202 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-02 12:25:23.394  4189  4202 I bt_hci  : start_up
,09-02 12:25:23.410  4189  4202 I bt_vendor: alloc value 0xb39d7189
,09-02 12:25:23.410  4189  4202 I bt_vendor: init
09-02 12:25:23.411  4189  4202 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-02 12:25:23.411  4189  4202 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 12:25:23.522  4189  4202 D bt_hci  : start_up starting async portion
,09-02 12:25:23.522  4189  4209 I bt_hci  : event_finish_startup
09-02 12:25:23.523  4189  4209 I bt_hci_h4: hal_open
09-02 12:25:23.523  4189  4209 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 12:25:23.533  4189  4209 I bt_userial_vendor: device fd = 51 open
,09-02 12:25:23.560  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:25:23.592  4189  4209 D bt_hwcfg: Chipset BCM4354A2
,09-02 12:25:23.592  4189  4209 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 12:25:23.593  4189  4209 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 12:25:24.251  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 12:25:24.252  4189  4209 D bt_hwcfg: Settlement delay -- 100 ms
09-02 12:25:24.253  4189  4209 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 12:25:24.369  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:25:24.371  4189  4209 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 12:25:24.400  4189  4209 I bt_hwcfg: vendor lib fwcfg completed
,09-02 12:25:24.401  4189  4209 I bt_vendor: firmware callback
,09-02 12:25:24.401  4189  4209 I bt_hci  : firmware_config_callback
,09-02 12:25:24.413  4189  4211 I bt_btu  : btu_task pending for preload complete event
,09-02 12:25:24.413  4189  4211 I bt_btu_task: Bluetooth chip preload is complete
09-02 12:25:24.413  4189  4211 I bt_btu  : btu_task received preload complete event
,09-02 12:25:24.424  4189  4211 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 12:25:24.424  4189  4211 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 12:25:24.425  4189  4211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:25:24.425  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 12:25:24.425  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:25:24.425  4189  4211 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 12:25:24.426  4189  4211 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:25:24.426  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:25:24.427  4189  4211 I         : BTE_InitTraceLevels -- TRC_GAP
,09-02 12:25:24.427  4189  4211 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:25:24.428  4189  4211 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:25:24.428  4189  4211 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:25:24.429  4189  4211 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 12:25:24.429  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:25:24.430  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 12:25:24.564  4189  4211 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,09-02 12:25:24.564  4189  4211 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,09-02 12:25:24.571  4189  4205 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-02 12:25:24.572  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 12:25:24.573  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:25:24.576  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:25:24.581  4189  4205 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:25:24.585  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:25:24.586  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:24.586  4189  4205 D bt_hci  : do_postload posting postload work item
09-02 12:25:24.588  4189  4209 I bt_hci  : event_postload
09-02 12:25:24.588  4189  4209 I bt_vendor: sco_config_cb
,09-02 12:25:24.588  4189  4209 I bt_hci  : sco_config_callback postload finished.
09-02 12:25:24.590  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:24.591  4189  4205 D bt_bte_conf: Device ID record 1 : primary
09-02 12:25:24.591  4189  4205 D bt_bte_conf:   vendorId            = 000f
09-02 12:25:24.591  4189  4205 D bt_bte_conf:   vendorIdSource      = 0001
09-02 12:25:24.592  4189  4205 D bt_bte_conf:   product             = 1200
,09-02 12:25:24.592  4189  4205 D bt_bte_conf:   version             = 1436
09-02 12:25:24.592  4189  4205 D bt_bte_conf:   clientExecutableURL = 
09-02 12:25:24.592  4189  4205 D bt_bte_conf:   serviceDescription  = 
09-02 12:25:24.592  4189  4205 D bt_bte_conf:   documentationURL    = 
09-02 12:25:24.593  4189  4205 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-02 12:25:24.593  4189  4202 D bt_stack_manager: event_start_up_stack finished
09-02 12:25:24.594  4189  4209 I bt_vendor: low_power_mode_cb
09-02 12:25:24.595  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-02 12:25:24.596  4189  4201 D BluetoothAdapterProperties: Setting state to 15
09-02 12:25:24.596  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 12:25:24.597  4189  4201 I BluetoothAdapterState: Entering BleOnState
,09-02 12:25:24.602  4189  4201 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-02 12:25:24.602  4189  4201 D BluetoothAdapterProperties: Setting state to 11
09-02 12:25:24.602  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 12:25:24.608  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:24.614  4189  4189 D HeadsetService: Received start request. Starting profile...
,09-02 12:25:24.616  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:24.619  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:24.621  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:24.625  4189  4189 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 12:25:24.627  4189  4189 D HeadsetStateMachine: make
,09-02 12:25:24.640  4189  4189 D HeadsetStateMachine: max_hf_connections = 1
,09-02 12:25:24.640  4189  4189 I bt_bluedroid: get_profile_interface handsfree
,09-02 12:25:24.641  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 12:25:24.641  4189  4205 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-02 12:25:24.647  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:24.649  4189  4189 D A2dpService: Received start request. Starting profile...
,09-02 12:25:24.650  4189  4189 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 12:25:24.651  4189  4189 I bt_bluedroid: get_profile_interface avrcp
,09-02 12:25:24.665  4189  4189 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 12:25:24.665  4189  4189 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:25:24.666  4189  4189 D A2dpStateMachine: make
,09-02 12:25:24.668  4189  4189 I bt_bluedroid: get_profile_interface a2dp
,09-02 12:25:24.668  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-02 12:25:24.671  4189  4189 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 12:25:24.671  4189  4220 D A2dpStateMachine: Enter Disconnected: -2
09-02 12:25:24.672  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:24.673  4189  4189 D HidService: Received start request. Starting profile...
,09-02 12:25:24.673  3964  3964 D BluetoothInputDevice: Proxy object connected
09-02 12:25:24.673  4189  4189 I bt_bluedroid: get_profile_interface hidhost
09-02 12:25:24.673  4189  4189 D HidService: setHidService(): set to: null
09-02 12:25:24.673  4189  4205 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
09-02 12:25:24.674  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-02 12:25:24.674  4189  4189 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 12:25:24.674  3964  3964 D HidProfile: Bluetooth service connected
09-02 12:25:24.675  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:24.676  4189  4189 D HealthService: Received start request. Starting profile...
09-02 12:25:24.679  4189  4189 I bt_bluedroid: get_profile_interface health
,09-02 12:25:24.680  4189  4189 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 12:25:24.681  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:24.683  4189  4189 D PanService: Received start request. Starting profile...
,09-02 12:25:24.683  3964  3964 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:25:24.683  4189  4189 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:25:24.683  4189  4189 I bt_bluedroid: get_profile_interface pan
09-02 12:25:24.683  3964  3964 D PanProfile: Bluetooth service connected
,09-02 12:25:24.684  4189  4205 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 12:25:24.687  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:24.688  3964  3964 D BluetoothMap: Proxy object connected
,09-02 12:25:24.688  4189  4189 D BluetoothMapService: Received start request. Starting profile...
09-02 12:25:24.688  4189  4189 D BluetoothMapService: start()
09-02 12:25:24.689  3964  3964 D MapProfile: Bluetooth service connected
09-02 12:25:24.689  3964  3964 D BluetoothMap: getConnectedDevices()
09-02 12:25:24.690  3964  3964 D BluetoothMap: Bluetooth is Not enabled
09-02 12:25:24.691  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 12:25:24.692  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-02 12:25:24.692  4189  4189 D BluetoothMapAppObserver: createReceiver()
09-02 12:25:24.693  4189  4189 D BluetoothMapAppObserver: initObservers()
09-02 12:25:24.693  4189  4189 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 12:25:24.704  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:24.704  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:25:24.705  4189  4189 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:24.705  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.705  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:24.708  4189  4218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.709  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.710  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:24.711  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:24.711  4189  4189 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:24.711  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:24.711  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:24.711  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-02 12:25:24.711  4189  4201 D BluetoothAdapterProperties: ScanMode =  20
09-02 12:25:24.712  4189  4201 D BluetoothAdapterProperties: State =  11
09-02 12:25:24.712  4189  4201 D BluetoothAdapterProperties: Setting state to 12
09-02 12:25:24.712  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:25:24.713  4189  4201 I BluetoothAdapterState: Entering OnState
09-02 12:25:24.713   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:24.713   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:24.714  4189  4205 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:25:24.714  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:25:24.714  3964  3975 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:25:24.715  3964  3974 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:25:24.720  1374  2129 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:25:24.721  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:24.721  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:24.722  4189  4189 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 12:25:24.724  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:24.725  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:24.726  1374  1374 D BluetoothInputDevice: Proxy object connected
09-02 12:25:24.726  1374  1374 D HidProfile: Bluetooth service connected
09-02 12:25:24.727  1374  1392 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:24.728  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:24.729  4189  4189 D ObexServerSockets: Succeed to create listening sockets 
09-02 12:25:24.729  1374  3887 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:25:24.729  4189  4189 D ObexServerSockets0: startAccept()
09-02 12:25:24.729  4189  4189 D ObexServerSockets0: prepareForNewConnect()
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:24.729  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:24.732  4189  4189 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 12:25:24.733  4189  4225 D ObexServerSockets0: Accepting socket connection...
09-02 12:25:24.733  4189  4189 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 12:25:24.734  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:25:24.734  4189  4226 D ObexServerSockets0: Accepting socket connection...
09-02 12:25:24.734  1374  1374 D PanProfile: Bluetooth service connected
,09-02 12:25:24.735  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:24.736  1374  2129 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:25:24.738   874   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:25:24.738  1374  1374 D BluetoothMap: Proxy object connected
09-02 12:25:24.738  1374  1374 D MapProfile: Bluetooth service connected
09-02 12:25:24.738  1374  1374 D BluetoothMap: getConnectedDevices()
09-02 12:25:24.738  3964  3975 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:25:24.739  1989  2131 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:24.739   874   874 D BluetoothA2dp: Proxy object connected
09-02 12:25:24.740  1374  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:25:24.744  1374  1374 D BluetoothA2dp: Proxy object connected
,09-02 12:25:24.745  1374  2129 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 12:25:24.748   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:25:24.748  3964  3974 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:25:24.752   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 12:25:24.752  4189  4189 D BluetoothMapService: onReceive
,09-02 12:25:24.752  4189  4189 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:25:24.752  4189  4189 D BluetoothMapService: STATE_ON
09-02 12:25:24.754  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:24.755  3964  3964 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-02 12:25:24.757  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:24.760  3964  3964 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-02 12:25:24.767  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:25:24.773  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 12:25:24.773  4189  4189 D ObexServerSockets0: prepareForNewConnect()
,09-02 12:25:24.773  3964  3964 D BluetoothA2dp: Proxy object connected
,09-02 12:25:24.794  3964  3964 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:25:24.798  3964  3964 D BluetoothPbap: Proxy object connected
09-02 12:25:24.799  3964  3964 D PbapServerProfile: Bluetooth service connected
,09-02 12:25:24.799  1374  1374 D BluetoothPbap: Proxy object connected
09-02 12:25:24.799  1374  1374 D PbapServerProfile: Bluetooth service connected
,09-02 12:25:24.804  4189  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:25:24.815   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:25:24.815   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.816  1989  2240 D BluetoothHeadset: Proxy object connected
09-02 12:25:24.817   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.817  1374  2129 D BluetoothHeadset: Proxy object connected
09-02 12:25:24.818  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:24.829  1374  1392 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.830  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:24.835  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:25:24.835  1515  1515 I art     : Waiting for a blocking GC DisableMovingGc
,09-02 12:25:24.838  1515  1515 I art     : Starting a blocking GC DisableMovingGc
,09-02 12:25:24.839  1989  2000 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.848   874   892 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.864  3964  3975 D BluetoothHeadset: Proxy object connected
,09-02 12:25:24.865  3964  3964 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:24.883  4189  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:25:24.885  4189  4235 I BtOppRfcommListener: Accept thread started.
,09-02 12:25:26.142  4189  4201 D BluetoothAdapterState: Current state: ON, message: 23
,09-02 12:25:26.143  4189  4201 D BluetoothAdapterProperties: Setting state to 13
09-02 12:25:26.143  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 12:25:26.145  4189  4201 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 12:25:26.147  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:26.159  4189  4189 D BluetoothMapService: onReceive
09-02 12:25:26.160  4189  4189 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:25:26.160  4189  4189 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:25:26.161  4189  4189 D BluetoothMapService: MAP Service closeService in
09-02 12:25:26.161  4189  4189 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 12:25:26.162  4189  4189 D ObexServerSockets0: shutdown(block = true)
,09-02 12:25:26.163  4189  4225 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-02 12:25:26.165  4189  4205 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:25:26.166  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 12:25:26.166  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:26.167  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:26.168  4189  4189 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 12:25:26.169  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:26.169  4189  4226 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 12:25:26.169  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:26.171  4189  4214 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 12:25:26.171  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 12:25:26.171  4189  4189 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 12:25:26.176  4189  4189 I BtOppRfcommListener: stopping Accept Thread
09-02 12:25:26.177  4189  4235 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:25:26.177  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:26.177  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:26.178  4189  4235 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:25:26.178  3888  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:25:26.178  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:26.181  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:26.182  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:26.183  4189  4189 D HeadsetService: Received stop request...Stopping profile...
09-02 12:25:26.185   874   874 D BluetoothHeadset: Proxy object disconnected
,09-02 12:25:26.185   874   874 D BluetoothHeadset: Proxy object disconnected
,09-02 12:25:26.185  4189  4189 D A2dpService: Received stop request...Stopping profile...
09-02 12:25:26.185  1989  2001 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:26.186   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:26.186  4189  4220 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:25:26.186  3964  3975 D BluetoothHeadset: Proxy object disconnected
,09-02 12:25:26.187  1374  1392 D BluetoothHeadset: Proxy object disconnected
09-02 12:25:26.187  1374  1374 D HeadsetProfile: Bluetooth service disconnected
09-02 12:25:26.187   874   874 D BluetoothA2dp: Proxy object disconnected
09-02 12:25:26.187  1374  1374 D BluetoothA2dp: Proxy object disconnected
,09-02 12:25:26.188  3964  3964 D DockEventReceiver: finishStartingService: stopping service
09-02 12:25:26.188  4189  4189 D HidService: Received stop request...Stopping profile...
09-02 12:25:26.188  4189  4189 D HidService: Stopping Bluetooth HidService
09-02 12:25:26.189  1374  1374 D BluetoothInputDevice: Proxy object disconnected
09-02 12:25:26.189  1374  1374 D HidProfile: Bluetooth service disconnected
09-02 12:25:26.190  3964  3964 D HeadsetProfile: Bluetooth service disconnected
,09-02 12:25:26.190  4189  4189 D HealthService: Received stop request...Stopping profile...
,09-02 12:25:26.190  3964  3964 D BluetoothA2dp: Proxy object disconnected
09-02 12:25:26.190  3964  3964 D BluetoothInputDevice: Proxy object disconnected
09-02 12:25:26.190  3964  3964 D HidProfile: Bluetooth service disconnected
09-02 12:25:26.192  4189  4189 D PanService: Received stop request...Stopping profile...
09-02 12:25:26.193  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:25:26.193  1374  1374 D PanProfile: Bluetooth service disconnected
09-02 12:25:26.195  3964  3964 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:25:26.195  3964  3964 D PanProfile: Bluetooth service disconnected
09-02 12:25:26.197  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:25:26.198  4189  4189 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:25:26.198  4189  4189 D BluetoothMapService: stop()
,09-02 12:25:26.199  4189  4189 D BluetoothMapAppObserver: deinitObservers()
09-02 12:25:26.199  4189  4189 D BluetoothMapAppObserver: removeReceiver()
09-02 12:25:26.200  3964  3964 D BluetoothMap: Proxy object disconnected
,09-02 12:25:26.200  3964  3964 D MapProfile: Bluetooth service disconnected
09-02 12:25:26.200  1374  1374 D BluetoothMap: Proxy object disconnected
09-02 12:25:26.201  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.201  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.201  1374  1374 D MapProfile: Bluetooth service disconnected
09-02 12:25:26.201  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.201  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:26.202  4189  4189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:25:26.203  4189  4189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 12:25:26.203  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.203  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.203  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.203  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:26.204  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:26.204  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:26.204  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:26.204  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 12:25:26.204  4189  4205 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-02 12:25:26.205  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:26.205  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:25:26.206  4189  4211 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:25:26.206  4189  4211 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:25:26.206  4189  4211 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:25:26.206  4189  4211 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:25:26.206  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 12:25:26.206  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.206  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.206  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.207  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:26.207  4189  4189 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:25:26.207  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 12:25:26.207  4189  4189 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:25:26.208  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.208  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.208  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.208  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:26.208  4189  4189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:25:26.208  4189  4205 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 12:25:26.209  4189  4189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:25:26.209  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.209  4189  4189 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:25:26.209  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.209  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:26.210  4189  4189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:25:26.210  4189  4189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 12:25:26.213  4189  4189 D BluetoothMapService: MAP Service closeService in
09-02 12:25:26.213  4189  4189 V BluetoothAdapterState: isTurningOff()=true
09-02 12:25:26.213  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.213  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.213  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:26.213  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 12:25:26.213  4189  4201 D BluetoothAdapterProperties: Setting state to 15
09-02 12:25:26.213  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 12:25:26.213  1374  1374 D BluetoothPbap: Proxy object disconnected
09-02 12:25:26.214  4189  4189 D BluetoothMapService: cleanup()
09-02 12:25:26.214  4189  4201 I BluetoothAdapterState: Entering BleOnState
09-02 12:25:26.214  4189  4189 D BluetoothMapService: MAP Service closeService in
09-02 12:25:26.214  1374  1374 D PbapServerProfile: Bluetooth service disconnected
09-02 12:25:26.216   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.216   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.216  3964  3974 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:25:26.217  3964  3975 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.218  3964  3974 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:25:26.219  3964  3964 D BluetoothPbap: Proxy object disconnected
09-02 12:25:26.219  3964  3964 D PbapServerProfile: Bluetooth service disconnected
09-02 12:25:26.220  1374  2129 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 12:25:26.221  1374  2129 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.222  1374  1392 D BluetoothPan: onBluetoothStateChange on: false
,09-02 12:25:26.222  1374  1386 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:25:26.223   874   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:25:26.223  3964  3975 D BluetoothPan: onBluetoothStateChange on: false
,09-02 12:25:26.224  1989  2131 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.224  1374  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 12:25:26.224  1374  2129 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:25:26.225   874   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:25:26.225  3964  4239 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 12:25:26.225  3964  3974 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:25:26.226  4189  4201 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-02 12:25:26.226  4189  4201 D BluetoothAdapterProperties: Setting state to 16
09-02 12:25:26.226  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 12:25:26.227  4189  4201 D BluetoothAdapterProperties: onBleDisable
09-02 12:25:26.228  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:26.229  4189  4202 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 12:25:26.230  4189  4211 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 12:25:26.230  4189  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:25:26.232  4189  4205 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:25:26.234  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 12:25:26.234  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:26.235  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:26.236  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:26.240  3964  3964 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:25:26.247  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:26.248  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:25:26.431  4189  4205 I bt_hci  : shut_down
,09-02 12:25:26.448  4189  4209 D bt_hwcfg: hw_epilog_process
,09-02 12:25:26.449  4189  4209 I bt_vendor: low_power_mode_cb
,09-02 12:25:26.469  4189  4209 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 12:25:26.469  4189  4209 I bt_vendor: epilog_cb
09-02 12:25:26.469  4189  4209 I bt_hci  : epilog_finished_callback
,09-02 12:25:26.476  4189  4205 I bt_hci_h4: hal_close
,09-02 12:25:26.478  4189  4205 I bt_userial_vendor: device fd = 51 close
,09-02 12:25:26.598  4189  4202 D bt_stack_manager: event_shut_down_stack finished.
,09-02 12:25:26.600  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 12:25:26.607  4189  4201 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 12:25:26.607  4189  4189 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:25:26.609  4189  4189 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 12:25:26.609  4189  4189 D BtGatt.GattService: stop()
,09-02 12:25:26.610  4189  4189 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 12:25:26.615  4189  4189 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:26.615  4189  4189 V BluetoothAdapterState: isTurningOn()=false
09-02 12:25:26.615  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:26.616  4189  4189 V BluetoothAdapterState: isBleTurningOff()=true
,09-02 12:25:26.616  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-02 12:25:26.617  4189  4201 D BluetoothAdapterProperties: Setting state to 10
09-02 12:25:26.617  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 12:25:26.619  4189  4201 I BluetoothAdapterState: Entering OffState
,09-02 12:25:26.621   874   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 12:25:26.642  4189  4189 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-02 12:25:26.642  4189  4189 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 12:25:26.642  4189  4202 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-02 12:25:26.646  4189  4189 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 12:25:26.652  4189  4202 D bt_stack_manager: event_clean_up_stack finished.
,09-02 12:25:26.659  4189  4189 I art     : System.exit called, status: 0
09-02 12:25:26.659  4189  4189 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:25:26.705   874  2030 I ActivityManager: Process com.android.bluetooth (pid 4189) has died
,09-02 12:25:27.533   874  1318 D ConnectivityService: handlePromptUnvalidated 101
,09-02 12:25:29.139  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:29.140  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:32.147  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:25:32.148  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a8795 added. We now have 6 listener(s)
09-02 12:25:32.148  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:32.152  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:25:32.153  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95950aa added. We now have 7 listener(s)
09-02 12:25:32.153  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:32.155  3888  3934 I System.out: IsBluetoothEnabled
,09-02 12:25:32.167  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:32.218   874   892 I ActivityManager: Start proc 4247:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 12:25:32.350  4247  4247 D AdapterServiceConfig: Adding HeadsetService
09-02 12:25:32.350  4247  4247 D AdapterServiceConfig: Adding A2dpService
,09-02 12:25:32.350  4247  4247 D AdapterServiceConfig: Adding HidService
09-02 12:25:32.350  4247  4247 D AdapterServiceConfig: Adding HealthService
09-02 12:25:32.350  4247  4247 D AdapterServiceConfig: Adding PanService
09-02 12:25:32.351  4247  4247 D AdapterServiceConfig: Adding GattService
09-02 12:25:32.351  4247  4247 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 12:25:32.365  4247  4247 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 12:25:32.365   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a33ac28:true
,09-02 12:25:32.370  4247  4247 I bt_bluedroid: init
,09-02 12:25:32.371  4247  4259 I BluetoothAdapterState: Entering OffState
,09-02 12:25:32.379  4247  4260 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 12:25:32.380  4247  4260 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:25:32.380  4247  4260 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 12:25:32.383  4247  4260 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 12:25:32.386  4247  4247 I bt_bluedroid: get_profile_interface socket
,09-02 12:25:32.388  4247  4247 I bt_bluedroid: get_profile_interface sdp
09-02 12:25:32.391  4247  4263 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:25:32.393  4247  4258 I bt_bluedroid: config_hci_snoop_log
09-02 12:25:32.394  4247  4263 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:25:32.396   874   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 12:25:32.407  4247  4259 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 12:25:32.407  4247  4259 D BluetoothAdapterProperties: Setting state to 14
09-02 12:25:32.408  4247  4259 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 12:25:32.413  4247  4259 D BluetoothBondStateMachine: make
,09-02 12:25:32.418  4247  4264 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 12:25:32.427  4247  4259 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:25:32.429  4247  4247 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 12:25:32.435  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:32.436  4247  4247 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:25:32.438  4247  4247 D BtGatt.GattService: Received start request. Starting profile...
,09-02 12:25:32.438  4247  4247 D BtGatt.GattService: start()
09-02 12:25:32.438  4247  4247 I bt_bluedroid: get_profile_interface gatt
,09-02 12:25:32.440  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:32.440  4247  4247 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:25:32.454  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:32.455  4247  4247 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:25:32.455  4247  4247 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 12:25:32.456  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:32.458  4247  4259 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-02 12:25:32.459  4247  4259 I bt_bluedroid: enable
09-02 12:25:32.460  4247  4260 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-02 12:25:32.461  4247  4260 I bt_hci  : start_up
,09-02 12:25:32.484  4247  4260 I bt_vendor: alloc value 0xb39d7189
09-02 12:25:32.484  4247  4260 I bt_vendor: init
09-02 12:25:32.484  4247  4260 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-02 12:25:32.485  4247  4260 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 12:25:32.591  4247  4260 D bt_hci  : start_up starting async portion
,09-02 12:25:32.592  4247  4267 I bt_hci  : event_finish_startup
,09-02 12:25:32.593  4247  4267 I bt_hci_h4: hal_open
,09-02 12:25:32.595  4247  4267 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 12:25:32.607  4247  4267 I bt_userial_vendor: device fd = 51 open
,09-02 12:25:32.633  4247  4267 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:25:32.666  4247  4267 D bt_hwcfg: Chipset BCM4354A2
,09-02 12:25:32.666  4247  4267 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 12:25:32.668  4247  4267 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 12:25:33.328  4247  4267 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 12:25:33.329  4247  4267 D bt_hwcfg: Settlement delay -- 100 ms
,09-02 12:25:33.330  4247  4267 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 12:25:33.447  4247  4267 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:25:33.448  4247  4267 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 12:25:33.477  4247  4267 I bt_hwcfg: vendor lib fwcfg completed
,09-02 12:25:33.478  4247  4267 I bt_vendor: firmware callback
,09-02 12:25:33.478  4247  4267 I bt_hci  : firmware_config_callback
,09-02 12:25:33.491  4247  4269 I bt_btu  : btu_task pending for preload complete event,
09-02 12:25:33.492  4247  4269 I bt_btu_task: Bluetooth chip preload is complete
09-02 12:25:33.492  4247  4269 I bt_btu  : btu_task received preload complete event
,09-02 12:25:33.502  4247  4269 I         : BTE_InitTraceLevels -- TRC_HCI,
09-02 12:25:33.502  4247  4269 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:25:33.503  4247  4269 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 12:25:33.503  4247  4269 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 12:25:33.503  4247  4269 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:25:33.503  4247  4269 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:25:33.504  4247  4269 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 12:25:33.504  4247  4269 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 12:25:33.505  4247  4269 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:25:33.505  4247  4269 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:25:33.506  4247  4269 I         : BTE_InitTraceLevels -- TRC_SDP
,09-02 12:25:33.507  4247  4269 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:25:33.507  4247  4269 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:25:33.507  4247  4269 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:25:33.508  4247  4269 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 12:25:33.642  4247  4269 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,09-02 12:25:33.643  4247  4269 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,09-02 12:25:33.655  4247  4263 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 12:25:33.658  4247  4263 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 12:25:33.660  4247  4263 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:25:33.664  4247  4263 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:25:33.667  4247  4263 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:25:33.668  4247  4263 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:25:33.668  4247  4263 D bt_hci  : do_postload posting postload work item
,09-02 12:25:33.668  4247  4267 I bt_hci  : event_postload
,09-02 12:25:33.668  4247  4267 I bt_vendor: sco_config_cb
,09-02 12:25:33.669  4247  4267 I bt_hci  : sco_config_callback postload finished.
,09-02 12:25:33.671  4247  4263 D bt_bte_conf: Device ID record 1 : primary
,09-02 12:25:33.671  4247  4263 D bt_bte_conf:   vendorId            = 000f
,09-02 12:25:33.671  4247  4263 D bt_bte_conf:   vendorIdSource      = 0001
,09-02 12:25:33.672  4247  4263 D bt_bte_conf:   product             = 1200
09-02 12:25:33.672  4247  4263 D bt_bte_conf:   version             = 1436
,09-02 12:25:33.672  4247  4263 D bt_bte_conf:   clientExecutableURL = 
09-02 12:25:33.672  4247  4263 D bt_bte_conf:   serviceDescription  = 
09-02 12:25:33.672  4247  4263 D bt_bte_conf:   documentationURL    = ,
09-02 12:25:33.673  4247  4263 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-02 12:25:33.673  4247  4260 D bt_stack_manager: event_start_up_stack finished
09-02 12:25:33.675  4247  4259 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 12:25:33.675  4247  4259 D BluetoothAdapterProperties: Setting state to 15
,09-02 12:25:33.675  4247  4259 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 12:25:33.677  4247  4259 I BluetoothAdapterState: Entering BleOnState
09-02 12:25:33.679  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:33.682  4247  4267 I bt_vendor: low_power_mode_cb
09-02 12:25:33.683  4247  4259 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-02 12:25:33.687  4247  4259 D BluetoothAdapterProperties: Setting state to 11
,09-02 12:25:33.687  4247  4259 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 12:25:33.693  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:33.697  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:33.698  4247  4247 D HeadsetService: Received start request. Starting profile...
09-02 12:25:33.702  4247  4247 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:25:33.702  4247  4247 D HeadsetStateMachine: make
,09-02 12:25:33.709  4247  4259 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:25:33.710  4247  4247 D HeadsetStateMachine: max_hf_connections = 1
,09-02 12:25:33.710  4247  4247 I bt_bluedroid: get_profile_interface handsfree
09-02 12:25:33.710  4247  4263 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 12:25:33.711  4247  4263 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-02 12:25:33.714  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:25:33.715  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:33.715  4247  4247 D A2dpService: Received start request. Starting profile...
09-02 12:25:33.716  4247  4247 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:25:33.716  4247  4247 I bt_bluedroid: get_profile_interface avrcp
,09-02 12:25:33.723  4247  4247 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 12:25:33.723  4247  4247 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-02 12:25:33.723  4247  4247 D A2dpStateMachine: make
,09-02 12:25:33.724  4247  4247 I bt_bluedroid: get_profile_interface a2dp
,09-02 12:25:33.725  4247  4263 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 12:25:33.726  4247  4278 D A2dpStateMachine: Enter Disconnected: -2
,09-02 12:25:33.727  4247  4247 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 12:25:33.728  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:33.728  4247  4247 D HidService: Received start request. Starting profile...
,09-02 12:25:33.728  4247  4247 I bt_bluedroid: get_profile_interface hidhost
09-02 12:25:33.728  4247  4247 D HidService: setHidService(): set to: null
09-02 12:25:33.728  4247  4263 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
09-02 12:25:33.729  4247  4263 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-02 12:25:33.729  4247  4247 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:25:33.730  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
09-02 12:25:33.730  4247  4247 D HealthService: Received start request. Starting profile...
,09-02 12:25:33.731  4247  4247 I bt_bluedroid: get_profile_interface health
,09-02 12:25:33.732  4247  4247 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 12:25:33.733  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:33.733  4247  4247 D PanService: Received start request. Starting profile...
,09-02 12:25:33.733  4247  4247 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:25:33.733  4247  4247 I bt_bluedroid: get_profile_interface pan
,09-02 12:25:33.734  4247  4263 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 12:25:33.740  4247  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:33.741  4247  4247 D BluetoothMapService: Received start request. Starting profile...
,09-02 12:25:33.741  4247  4247 D BluetoothMapService: start()
,09-02 12:25:33.743  4247  4247 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 12:25:33.744  4247  4247 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-02 12:25:33.744  4247  4247 D BluetoothMapAppObserver: createReceiver()
09-02 12:25:33.745  4247  4247 D BluetoothMapAppObserver: initObservers()
,09-02 12:25:33.745  4247  4247 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 12:25:33.751  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:33.751  4247  4247 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:33.751  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:25:33.751  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:33.753  4247  4276 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 12:25:33.754  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:33.755  4247  4247 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:25:33.755  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:33.755  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:25:33.755  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:33.755  4247  4247 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false,
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isTurningOff()=false
09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:33.756  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:33.757  4247  4247 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:25:33.757  4247  4247 V BluetoothAdapterState: isTurningOn()=true
09-02 12:25:33.757  4247  4247 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:25:33.757  4247  4247 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:25:33.757  4247  4259 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 12:25:33.757  4247  4259 D BluetoothAdapterProperties: ScanMode =  20
,09-02 12:25:33.757  4247  4259 D BluetoothAdapterProperties: State =  11
,09-02 12:25:33.757  4247  4259 D BluetoothAdapterProperties: Setting state to 12
,09-02 12:25:33.758  4247  4259 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:25:33.758   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:25:33.758   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:33.758  4247  4263 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:25:33.758  4247  4263 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:25:33.759  4247  4259 I BluetoothAdapterState: Entering OnState
,09-02 12:25:33.759  3964  3975 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:25:33.761  3964  4239 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:25:33.762  3964  3975 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:33.762  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:33.763  3964  3964 D BluetoothInputDevice: Proxy object connected
,09-02 12:25:33.763  3964  3964 D HidProfile: Bluetooth service connected
09-02 12:25:33.763  1374  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:25:33.764  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:33.765  1374  1374 D BluetoothInputDevice: Proxy object connected
,09-02 12:25:33.765  1374  1374 D HidProfile: Bluetooth service connected
,09-02 12:25:33.765  1374  2129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:33.766  1374  1392 D BluetoothPan: onBluetoothStateChange on: true,
09-02 12:25:33.767  1374  1386 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:25:33.768  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:25:33.768  1374  1374 D PanProfile: Bluetooth service connected
,09-02 12:25:33.768   874   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:25:33.769  3964  3974 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:25:33.769  1374  1374 D BluetoothMap: Proxy object connected,
09-02 12:25:33.769   874   874 D BluetoothA2dp: Proxy object connected
09-02 12:25:33.770  4247  4247 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 12:25:33.769  1374  1374 D MapProfile: Bluetooth service connected
09-02 12:25:33.770  1374  1374 D BluetoothMap: getConnectedDevices()
09-02 12:25:33.770  4247  4247 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-02 12:25:33.772  1989  2131 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:33.772  4247  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:33.773  1374  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:25:33.774  4247  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:25:33.774  1374  1374 D BluetoothA2dp: Proxy object connected
,09-02 12:25:33.774  1374  1386 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:25:33.776  4247  4247 D ObexServerSockets: Succeed to create listening sockets 
09-02 12:25:33.776  4247  4247 D ObexServerSockets0: startAccept(),
09-02 12:25:33.776   874   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:25:33.776  4247  4247 D ObexServerSockets0: prepareForNewConnect()
09-02 12:25:33.776  3964  3975 D BluetoothMap: onBluetoothStateChange: up=true,
09-02 12:25:33.777  3964  3964 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:25:33.777  3964  3964 D PanProfile: Bluetooth service connected
09-02 12:25:33.777  4247  4247 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-02 12:25:33.777  4247  4247 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 12:25:33.778  4247  4283 D ObexServerSockets0: Accepting socket connection...
,09-02 12:25:33.778  4247  4284 D ObexServerSockets0: Accepting socket connection...
09-02 12:25:33.779  3964  3974 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:25:33.782   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 12:25:33.783  4247  4247 D BluetoothMapService: onReceive
09-02 12:25:33.783  4247  4247 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:25:33.783  4247  4247 D BluetoothMapService: STATE_ON
09-02 12:25:33.784  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:33.785  3964  3964 D BluetoothMap: Proxy object connected
09-02 12:25:33.785  3964  3964 D MapProfile: Bluetooth service connected
,09-02 12:25:33.785  3964  3964 D BluetoothMap: getConnectedDevices()
09-02 12:25:33.786  3964  3964 D BluetoothA2dp: Proxy object connected
09-02 12:25:33.792  3964  3964 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:25:33.798  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:25:33.799  3964  3964 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:25:33.807  3964  3964 D BluetoothPbap: Proxy object connected
,09-02 12:25:33.807  1374  1374 D BluetoothPbap: Proxy object connected
09-02 12:25:33.807  3964  3964 D PbapServerProfile: Bluetooth service connected
,09-02 12:25:33.807  1374  1374 D PbapServerProfile: Bluetooth service connected
09-02 12:25:33.808  4247  4247 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 12:25:33.808  4247  4247 D ObexServerSockets0: prepareForNewConnect()
,09-02 12:25:33.814  4247  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:25:33.829  4247  4293 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:25:33.830  4247  4293 I BtOppRfcommListener: Accept thread started.
,09-02 12:25:33.859   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:25:33.859   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:25:33.860  1989  2240 D BluetoothHeadset: Proxy object connected
,09-02 12:25:33.860   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:25:33.860  3964  4239 D BluetoothHeadset: Proxy object connected
09-02 12:25:33.861  3964  3964 D HeadsetProfile: Bluetooth service connected
09-02 12:25:33.861  1374  1392 D BluetoothHeadset: Proxy object connected
09-02 12:25:33.861  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:33.861  3964  3974 D BluetoothHeadset: Proxy object connected
09-02 12:25:33.863  3964  3964 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:33.865  1374  3887 D BluetoothHeadset: Proxy object connected
09-02 12:25:33.866  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-02 12:25:33.872  1989  2000 D BluetoothHeadset: Proxy object connected
,09-02 12:25:33.876   874   892 D BluetoothHeadset: Proxy object connected
,09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:34.190  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:34.197  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:34.200  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:25:34.200  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f17549b added. We now have 8 listener(s)
09-02 12:25:34.201  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:34.208   874  2029 D WifiService: setWifiEnabled: false pid=3888, uid=10000
,09-02 12:25:34.208   874  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:25:34.220  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:34.221   874  2032 D WifiService: setWifiEnabled: true pid=3888, uid=10000
09-02 12:25:34.222   874  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:25:34.239   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:34.255  3888  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:34.262  3888  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:34.274   874  1316 D WifiConfigStore: loaded 0 passpoint configs
09-02 12:25:34.275   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 12:25:34.276   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-02 12:25:34.277   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:25:34.277   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 12:25:34.278   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 12:25:34.278   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 12:25:34.291   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 12:25:34.292   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-02 12:25:34.293   372   872 D CommandListener: Setting iface cfg
,09-02 12:25:34.294   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-02 12:25:34.294   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 12:25:34.351   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 12:25:34.351   874  1316 E native  : do suspend true
,09-02 12:25:34.353   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 12:25:34.388   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:35.249  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:35.256  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:35.268  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 12:25:35.271  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 12:25:35.277  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@70f7c60 Bundle[{}]
,09-02 12:25:35.278  3888  3934 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 12:25:35.278  3888  3934 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 12:25:35.279  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 12:25:35.280  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 12:25:35.280  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 12:25:35.281  3888  3934 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-02 12:25:35.286  3888  3934 I System.out: Running OutgoingSocketThread
,09-02 12:25:35.289  3888  4299 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 431)
,09-02 12:25:35.291  3888  4299 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44916
,09-02 12:25:35.291  3888  4299 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 12:25:35.765   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-02 12:25:36.289  3888  3934 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 432)
,09-02 12:25:36.290  3888  3934 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 432)
,09-02 12:25:36.301  3888  3934 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,09-02 12:25:36.304  3888  3934 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 12:25:36.304  3888  3934 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,09-02 12:25:36.309  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.310  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3987038 added. We now have 2 listener(s)
,09-02 12:25:36.311  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.312  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.312  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.312  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.312  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d690811 added. We now have 9 listener(s)
09-02 12:25:36.312  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:36.313  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:25:36.317  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:36.323  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:36.327  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:36.327  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:36.327  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:25:36.327  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8c9f77 added. We now have 3 listener(s)
09-02 12:25:36.329  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:25:36.329  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.329  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.329  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.330  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48057e4 added. We now have 10 listener(s)
09-02 12:25:36.330  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:36.330  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:36.330  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:36.330  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:36.330  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.330  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.330  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:36.330  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.331  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:36.331  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3987038 removed from the list
09-02 12:25:36.331  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.331  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d690811 removed from the list
09-02 12:25:36.334  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:36.334  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:36.334  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.335  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.335  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.337  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.337  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.337  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.337  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d690811 not in the list
09-02 12:25:36.337  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.337  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.339  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.340  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.340  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.340  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48057e4 removed from the list
09-02 12:25:36.341  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:25:36.341  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.341  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.341  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.342  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8c9f77 removed from the list
,09-02 12:25:36.344  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.344  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5144d added. We now have 2 listener(s)
,09-02 12:25:36.350  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.350  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.350  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.351  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.351  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a74b02 added. We now have 9 listener(s)
09-02 12:25:36.351  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.353  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:25:36.358  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:36.365  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:36.369  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:36.369  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:25:36.369  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:25:36.370  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dd0e50 added. We now have 3 listener(s)
,09-02 12:25:36.371  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:25:36.371  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.371  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.372  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.372  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5ba849 added. We now have 10 listener(s)
09-02 12:25:36.372  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:36.372  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:36.372  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:25:36.372  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:25:36.372  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:36.373  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:25:36.373  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:36.376  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:25:36.376  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:25:36.377  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:36.383  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:25:36.384  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:25:36.385  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:25:36.393  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:25:36.393  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:25:36.393  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:25:36.395  3888  3934 D BluetoothAdapter: STATE_ON
,09-02 12:25:36.402  4247  4257 D BtGatt.GattService: registerClient() - UUID=d4548e9a-3d03-4373-b7d3-2acd6461edef
,09-02 12:25:36.404  4247  4263 D BtGatt.GattService: onClientRegistered() - UUID=d4548e9a-3d03-4373-b7d3-2acd6461edef, clientIf=5
,09-02 12:25:36.405  3888  3899 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 12:25:36.407  4247  4274 D BtGatt.GattService: start scan with filters
,09-02 12:25:36.413  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:25:36.414  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:25:36.414  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:25:36.414  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:25:36.414  4247  4266 D BtGatt.ScanManager: handling starting scan
,09-02 12:25:36.418  4247  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aad04f4
,09-02 12:25:36.423  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:36.423  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:25:36.423  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:25:36.425  4247  4263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:25:36.425  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.425  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:25:36.427  4247  4266 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 12:25:36.429  3888  3934 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:25:36.429  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:36.429  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:25:36.429  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:36.429  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:25:36.429  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:25:36.429  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:25:36.429  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:25:36.430  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:25:36.430  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:25:36.430  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:25:36.431  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:36.431  4247  4274 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:25:36.433  4247  4258 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 12:25:36.433  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:25:36.433  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:25:36.433  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:25:36.433  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:36.434  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:25:36.435  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:36.435  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:25:36.435  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:25:36.435  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:25:36.437  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:36.438  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:25:36.438  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:36.439  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:36.439  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:36.438  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.442  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:36.442  4247  4266 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:25:36.443  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:36.443  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:36.443  4247  4266 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:25:36.443  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.443  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.443  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:36.444  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:25:36.446  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5144d removed from the list
09-02 12:25:36.446  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.446  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a74b02 removed from the list
,09-02 12:25:36.446  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:36.446  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.447  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.447  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.449  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:36.450  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.450  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.450  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a74b02 not in the list
09-02 12:25:36.450  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.451  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.452  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.452  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.453  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:36.453  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5ba849 removed from the list
09-02 12:25:36.453  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.453  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.453  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.453  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:25:36.454  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dd0e50 removed from the list
09-02 12:25:36.455  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:25:36.455  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fad8005 added. We now have 2 listener(s)
,09-02 12:25:36.458  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.458  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.459  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.459  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.459  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf385a added. We now have 9 listener(s)
09-02 12:25:36.459  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.460  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:25:36.464  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:36.468  4247  4263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 12:25:36.468  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:36.469  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:36.473  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:25:36.473  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:36.473  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:25:36.473  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9245768 added. We now have 3 listener(s)
09-02 12:25:36.476  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:25:36.476  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.477  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.477  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:36.477  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.477  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b1781 added. We now have 10 listener(s)
09-02 12:25:36.477  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:25:36.477  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:36.479  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:25:36.479  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:25:36.479  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.480  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:36.480  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:25:36.480  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:25:36.480  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:36.480  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:25:36.484  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:25:36.485  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:25:36.490  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:25:36.491  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:25:36.491  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:25:36.493  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:25:36.493  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.494  4247  4266 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:25:36.496  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:25:36.496  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:25:36.496  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:25:36.497  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:36.499  4247  4285 D BtGatt.GattService: registerClient() - UUID=73ea30a1-9239-44d1-9b3f-d70f667e2488
09-02 12:25:36.500  4247  4263 D BtGatt.GattService: onClientRegistered() - UUID=73ea30a1-9239-44d1-9b3f-d70f667e2488, clientIf=5
09-02 12:25:36.500  3888  3898 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:25:36.500  4247  4274 D BtGatt.GattService: start scan with filters
09-02 12:25:36.503  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:25:36.503  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.503  4247  4266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:25:36.505  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:25:36.505  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:25:36.505  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:25:36.505  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:25:36.508  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:36.509  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:25:36.509  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:25:36.510  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 12:25:36.513  4247  4263 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:25:36.513  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.514  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:36.514  3888  3934 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 12:25:36.514  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:36.515  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:36.515  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:36.515  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.515  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.515  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:25:36.515  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.515  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fad8005 removed from the list
09-02 12:25:36.515  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.515  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf385a removed from the list
09-02 12:25:36.515  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:36.515  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:36.516  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.516  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 12:25:36.516  4247  4266 D BtGatt.ScanManager: handling starting scan
09-02 12:25:36.516  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.516  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:25:36.517  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.518  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.518  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.518  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf385a not in the list
09-02 12:25:36.518  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:25:36.518  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:25:36.518  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:25:36.518  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:25:36.518  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:25:36.519  3888  3934 D BluetoothAdapter: STATE_ON
09-02 12:25:36.520  4247  4258 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:25:36.520  4247  4257 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:25:36.521  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:25:36.521  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:25:36.521  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:25:36.521  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:36.521  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:25:36.522  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:36.523  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:25:36.523  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:25:36.523  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:25:36.523  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.524  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:36.525  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:25:36.525  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:36.525  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.525  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:36.525  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.525  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b1781 removed from the list
,09-02 12:25:36.525  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.525  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:36.525  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.525  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:25:36.526  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9245768 removed from the list
,09-02 12:25:36.527  4247  4263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 12:25:36.527  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.527  4247  4266 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:25:36.527  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.528  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@450aabd added. We now have 2 listener(s)
,09-02 12:25:36.529  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.529  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:25:36.530  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.530  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.530  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58c78b2 added. We now have 9 listener(s)
,09-02 12:25:36.530  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.530  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:25:36.533  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:36.535  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:25:36.535  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.536  4247  4266 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:25:36.536  4247  4266 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:36.538  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:25:36.540  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:36.540  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:25:36.542  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:36.542  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.542  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb8ab80 added. We now have 3 listener(s)
,09-02 12:25:36.543  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:36.545  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.545  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:25:36.545  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:25:36.545  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:25:36.545  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae235b9 added. We now have 10 listener(s)
,09-02 12:25:36.545  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.545  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:25:36.545  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 12:25:36.546  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:25:36.546  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:25:36.546  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:25:36.550  3888  3934 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 12:25:36.550  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:25:36.552  4247  4263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:25:36.553  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.558  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:25:36.558  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 12:25:36.559  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:25:36.560  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:25:36.560  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.562  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:25:36.562  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 12:25:36.563  3888  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:25:36.563  3888  3934 D BluetoothAdapter: STATE_ON
,09-02 12:25:36.566  4247  4285 D BtGatt.GattService: registerClient() - UUID=f38e9ac1-142c-429f-a8ab-279d48022b1e
,09-02 12:25:36.566  4247  4263 D BtGatt.GattService: onClientRegistered() - UUID=f38e9ac1-142c-429f-a8ab-279d48022b1e, clientIf=5
,09-02 12:25:36.567  3888  3898 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 12:25:36.567  4247  4274 D BtGatt.GattService: start scan with filters
,09-02 12:25:36.569  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
09-02 12:25:36.569  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.569  4247  4266 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:25:36.572  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:25:36.572  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-02 12:25:36.572  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 12:25:36.572  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:25:36.575  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:25:36.576  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:25:36.576  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:25:36.578  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:25:36.578  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 12:25:36.578  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.579  4247  4266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:25:36.584  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:25:36.584  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:25:36.584  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:36.585  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:25:36.585  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.585  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 12:25:36.585  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.585  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@450aabd removed from the list
,09-02 12:25:36.585  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.585  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58c78b2 removed from the list
,09-02 12:25:36.585  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:36.585  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:25:36.586  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.586  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 12:25:36.586  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.586  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:25:36.587  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.587  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 12:25:36.587  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:36.588  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58c78b2 not in the list
09-02 12:25:36.588  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:25:36.588  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:25:36.588  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:25:36.588  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:25:36.588  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:25:36.589  3888  3934 D BluetoothAdapter: STATE_ON,
09-02 12:25:36.590  4247  4263 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 12:25:36.590  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.590  4247  4274 D BtGatt.GattService: stopScan() - queue size =0
,09-02 12:25:36.591  4247  4257 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:25:36.592  4247  4266 D BtGatt.ScanManager: handling starting scan
,09-02 12:25:36.592  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:25:36.592  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
09-02 12:25:36.592  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 12:25:36.592  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:25:36.593  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:25:36.594  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:25:36.594  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 12:25:36.594  3888  3934 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:25:36.594  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:25:36.595  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.596  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 12:25:36.596  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:25:36.596  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.596  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:36.596  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae235b9 removed from the list
09-02 12:25:36.596  3888  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:25:36.596  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.596  3888  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:25:36.596  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.597  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.597  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.597  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb8ab80 removed from the list
09-02 12:25:36.598  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.598  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8677475 added. We now have 2 listener(s)
,09-02 12:25:36.600  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:25:36.600  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:25:36.600  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.601  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:25:36.601  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1066c0a added. We now have 9 listener(s)
09-02 12:25:36.601  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.601  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:25:36.605  4247  4263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:25:36.605  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.605  4247  4266 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 12:25:36.606  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:25:36.612  3888  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:25:36.614  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 12:25:36.614  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.614  4247  4266 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:25:36.614  4247  4266 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:25:36.616  3888  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:25:36.616  3888  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:25:36.617  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:25:36.618  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed06a98 added. We now have 3 listener(s)
09-02 12:25:36.619  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:36.621  3888  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:25:36.622  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:25:36.622  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:25:36.622  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:25:36.622  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:25:36.622  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c7e2f1 added. We now have 10 listener(s)
09-02 12:25:36.622  3888  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:25:36.623  3888  3934 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:25:36.623  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:25:36.623  3888  3934 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:25:36.623  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:25:36.623  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:36.623  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:25:36.623  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.623  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8677475 removed from the list
,09-02 12:25:36.623  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.623  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1066c0a removed from the list
,09-02 12:25:36.623  3888  3934 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:25:36.624  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.624  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:25:36.625  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:25:36.626  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.626  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:25:36.626  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:25:36.626  3888  3934 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1066c0a not in the list
09-02 12:25:36.626  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.626  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.627  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:25:36.627  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:25:36.627  3888  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:25:36.627  3888  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c7e2f1 removed from the list
09-02 12:25:36.628  3888  3934 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:25:36.628  3888  3934 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:25:36.628  3888  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:25:36.628  3888  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:25:36.628  3888  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed06a98 removed from the list
09-02 12:25:36.629  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 12:25:36.629  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 12:25:36.629  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 12:25:36.629  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:25:36.630  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 12:25:36.630  3888  3934 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:25:36.633  4247  4263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 12:25:36.633  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.637  3888  4300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
,09-02 12:25:36.637  3888  4300 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
09-02 12:25:36.637  3888  4300 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:25:36.640  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:25:36.640  3888  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
09-02 12:25:36.640  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.640  3888  4301 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
,09-02 12:25:36.641  3888  4301 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:25:36.645  3888  3934 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-02 12:25:36.645  3888  3934 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 12:25:36.646  3888  3934 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 12:25:36.646  3888  3934 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 12:25:36.646  3888  3934 D com.test.thalitest.ThaliTestRunner: Total duration: 22957 ms
,09-02 12:25:36.649  4247  4263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 12:25:36.649  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.649  3888  3934 I jxcore-log: *Native tests were executed*
09-02 12:25:36.649  3888  3934 I jxcore-log: 
09-02 12:25:36.649  4247  4266 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:25:36.649  3888  3934 I jxcore-log: Total number of executed tests:  80
09-02 12:25:36.649  3888  3934 I jxcore-log: 
,09-02 12:25:36.650  3888  3934 I jxcore-log: Number of passed tests:  80
09-02 12:25:36.650  3888  3934 I jxcore-log: 
09-02 12:25:36.651  3888  3934 I jxcore-log: Number of failed tests:  0
09-02 12:25:36.651  3888  3934 I jxcore-log: 
,09-02 12:25:36.652  3888  3934 I jxcore-log: Number of ignored tests:  0
09-02 12:25:36.652  3888  3934 I jxcore-log: 
,09-02 12:25:36.653  3888  3934 I jxcore-log: Total duration:  22957
09-02 12:25:36.653  3888  3934 I jxcore-log: 
,09-02 12:25:36.653  3888  3934 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 12:25:36.653  3888  3934 I jxcore-log: 
,09-02 12:25:36.656  4247  4263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:25:36.657  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:25:36.656  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.656  3888  3934 I jxcore-log: 
09-02 12:25:36.657  4247  4266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:25:36.660  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.660  3888  3934 I jxcore-log: 
,09-02 12:25:36.661  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.661  3888  3934 I jxcore-log: 
,09-02 12:25:36.663  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.663  3888  3934 I jxcore-log: 
09-02 12:25:36.664  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.664  3888  3934 I jxcore-log: 
09-02 12:25:36.664  4247  4263 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 12:25:36.664  4247  4263 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:25:36.666  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.666  3888  3934 I jxcore-log: 
09-02 12:25:36.666  3888  3888 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-02 12:25:36.668  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.668  3888  3934 I jxcore-log: 
09-02 12:25:36.670  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.670  3888  3934 I jxcore-log: 
09-02 12:25:36.671  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
09-02 12:25:36.671  3888  3934 I jxcore-log: 
09-02 12:25:36.671  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.671  3888  3934 I jxcore-log: 
09-02 12:25:36.672  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.672  3888  3934 I jxcore-log: 
,09-02 12:25:36.673  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:25:36.673  3888  3934 I jxcore-log: 
09-02 12:25:36.675  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.675  3888  3934 I jxcore-log: 
,09-02 12:25:36.675  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.675  3888  3934 I jxcore-log: 
09-02 12:25:36.676  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.676  3888  3934 I jxcore-log: 
09-02 12:25:36.677  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:25:36.677  3888  3934 I jxcore-log: 
,09-02 12:25:36.678  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.678  3888  3934 I jxcore-log: 
,09-02 12:25:36.678  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.678  3888  3934 I jxcore-log: 
09-02 12:25:36.679  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.679  3888  3934 I jxcore-log: 
,09-02 12:25:36.680  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.680  3888  3934 I jxcore-log: 
,09-02 12:25:36.681  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.681  3888  3934 I jxcore-log: 
09-02 12:25:36.681  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.681  3888  3934 I jxcore-log: 
,09-02 12:25:36.682  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.682  3888  3934 I jxcore-log: 
09-02 12:25:36.683  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.683  3888  3934 I jxcore-log: 
,09-02 12:25:36.684  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.684  3888  3934 I jxcore-log: 
,09-02 12:25:36.684  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:25:36.684  3888  3934 I jxcore-log: 
,09-02 12:25:36.685  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.685  3888  3934 I jxcore-log: 
,09-02 12:25:36.686  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.686  3888  3934 I jxcore-log: 
,09-02 12:25:36.687  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.687  3888  3934 I jxcore-log: 
,09-02 12:25:36.688  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.688  3888  3934 I jxcore-log: 
09-02 12:25:36.689  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.689  3888  3934 I jxcore-log: 
09-02 12:25:36.690  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.690  3888  3934 I jxcore-log: 
09-02 12:25:36.690  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:25:36.690  3888  3934 I jxcore-log: 
,09-02 12:25:36.941  3888  3888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:25:36.944  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:25:36.944  3888  3934 I jxcore-log: 
,09-02 12:25:37.025  3888  3888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:25:37.028  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:25:37.028  3888  3934 I jxcore-log: 
,09-02 12:25:37.097  3888  3888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:25:37.100  3888  3934 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:25:37.100  3888  3934 I jxcore-log: 
,09-02 12:25:37.297  4302  4302 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-02 12:25:37.302  4302  4302 D AndroidRuntime: CheckJNI is OFF
,09-02 12:25:37.345  4302  4302 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-02 12:25:37.393  4302  4302 I Radio-JNI: register_android_hardware_Radio DONE
,09-02 12:25:37.417  4302  4302 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 12:25:37.427   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.78 rxSuccessRate=5.59 delta 1000 -> 1000
,09-02 12:25:37.431   874   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-02 12:25:37.432   874   888 I ActivityManager: Killing 3888:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-02 12:25:37.434   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 12:25:37.434   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:37.454   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 12:25:37.524   874  2022 I WindowState: WIN DEATH: Window{c43f41a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:25:37.524   874  2047 D GraphicsStats: Buffer count: 2
,09-02 12:25:37.525   874  1317 D WifiService: Client connection lost with reason: 4
,09-02 12:25:37.575   874   898 W PackageSettings: Skipping PackageSetting{d2f09f1 com.example.hello/10273} due to missing metadata
,09-02 12:25:37.602   874   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-02 12:25:37.602   874   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-02 12:25:37.603   874   888 E ActivityManager: Failure starting process com.test.thalitest
09-02 12:25:37.603   874   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-02 12:25:37.603   874   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:37.603   874   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:37.603   874   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 12:25:37.603   874   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-02 12:25:37.604   874   888 I ActivityManager:   Force finishing activity ActivityRecord{afc6347 u0 com.test.thalitest/.MainActivity t2}
09-02 12:25:37.605   874   898 I art     : Starting a blocking GC Explicit
,09-02 12:25:37.610   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 12:25:37.611   874   886 W ActivityManager: Spurious death for ProcessRecord{c5f79c4 0:com.test.thalitest/u0a0}, curProc for 3888: null
,09-02 12:25:37.612  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 12:25:37.660   874   898 I art     : Explicit concurrent mark sweep GC freed 37284(2MB) AllocSpace objects, 12(296KB) LOS objects, 33% free, 29MB/43MB, paused 843us total 53.098ms
,09-02 12:25:37.696   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-02 12:25:37.699  4302  4302 I art     : System.exit called, status: 0
09-02 12:25:37.699  4302  4302 I AndroidRuntime: VM exiting with result code 0.
,09-02 12:25:37.729   874   898 I ActivityManager: Start proc 4312:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-02 12:25:37.730   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-02 12:25:37.756   874   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-02 12:25:37.759  1909  1909 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-02 12:25:37.761  1871  2287 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 12:25:37.763  4247  4247 D BluetoothMapAppObserver: onReceive
,09-02 12:25:37.764  4247  4247 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-02 12:25:37.764   874  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 12:25:37.770  3642  3642 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-02 12:25:37.788  1989  1989 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-02 12:25:37.789  1909  4325 I Keyboard.Facilitator.DecoderInitializer: run()
,09-02 12:25:37.799  1909  4325 I Decoder : createOrResetDecoder
,09-02 12:25:37.803   874   886 I ActivityManager: Start proc 4327:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-02 12:25:37.824   874  1314 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,09-02 12:25:37.833  1515  1515 I ConfigService: onCreate
,09-02 12:25:37.835   874  2028 I ActivityManager: Killing 3804:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-02 12:25:37.849   874  1381 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3888 uid 10000
,09-02 12:25:37.850  1909  1909 I Keyboard.Facilitator: onFinishInput()
,09-02 12:25:37.870  1515  4340 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 12:25:37.870  1515  4340 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 12:25:37.870  1515  4340 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-02 12:25:37.877   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 12:25:37.878  4327  4327 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-02 12:25:37.879  1515  4340 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-02 12:25:37.889  2003  2133 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-02 12:25:37.892   874   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-02 12:25:37.893   874   887 E PackageManager: Failed to write settings, restoring backup
09-02 12:25:37.893   874   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-02 12:25:37.893   874   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-02 12:25:37.893   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-02 12:25:37.893   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-02 12:25:37.893   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-02 12:25:37.893   874   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:37.893   874   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:37.893   874   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:25:37.897   874   888 E DropBoxManagerService: Can't write: system_server_wtf
09-02 12:25:37.897   874   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-02 12:25:37.897   874   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:37.897   874   888 E DropBoxManagerService: 	... 13 more
,09-02 12:25:37.902   874   886 I ActivityManager: Start proc 4341:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-02 12:25:37.903  2003  2133 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-02 12:25:37.903  2003  2133 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2003
09-02 12:25:37.903  2003  2133 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:37.903  2003  2133 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:25:37.905   874  1611 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 12:25:37.905   874  4349 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:25:37.905   874  4349 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:37.905   874  4349 E DropBoxManagerService: 	... 5 more
09-02 12:25:37.909  2003  2133 I Process : Sending signal. PID: 2003 SIG: 9
,09-02 12:25:37.936  1909  4325 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-02 12:25:37.972  1909  4325 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-02 12:25:37.974  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-02 12:25:37.974  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-02 12:25:37.976  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-02 12:25:37.977  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-02 12:25:37.977  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-02 12:25:37.977  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-02 12:25:37.978  1909  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-02 12:25:37.978  1909  4325 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-02 12:25:37.978  1909  4325 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-02 12:25:37.978  1909  4325 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-02 12:25:37.978  1909  4325 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-02 12:25:37.978  1909  4325 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-02 12:25:37.981   874  1696 D GraphicsStats: Buffer count: 1
,09-02 12:25:37.981   874   885 I WindowState: WIN DEATH: Window{21e31ab u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-02 12:25:37.992   874  2028 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2003) has died
,09-02 12:25:37.993   874  2028 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-02 12:25:37.996   874  2028 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 12:25:38.011   874   888 I ActivityManager: Start proc 4359:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 12:25:38.032  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:25:38.045  4327  4327 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-02 12:25:38.055  4359  4359 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:38.055  4359  4359 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:25:38.056  4359  4359 D AndroidRuntime: Shutting down VM
,09-02 12:25:38.055  1715  4371 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-02 12:25:38.056  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 12:25:38.056  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-02 12:25:38.058   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:25:38.061  1715  4371 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-02 12:25:38.064   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:25:38.064   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:38.064   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 12:25:38.067  4327  4373 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 12:25:38.075   874  2165 I ActivityManager: Start proc 4378:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-02 12:25:38.076   383   383 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_alloc_service_client failed! service_id = 42, conn_id = 29, rc=-1 error = 0
,09-02 12:25:38.076   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:25:38.078  4359  4359 E AndroidRuntime: FATAL EXCEPTION: main
09-02 12:25:38.078  4359  4359 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4359
09-02 12:25:38.078  4359  4359 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	,at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 12:25:38.078  4359  4359 E AndroidRuntime: 	... 10 more
,09-02 12:25:38.080   372   872 D CommandListener: Setting iface cfg
09-02 12:25:38.081   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
09-02 12:25:38.087   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-02 12:25:38.087   874  4389 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:25:38.087   874  4389 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:38.087   874  4389 E DropBoxManagerService: 	... 5 more
,09-02 12:25:38.088   874   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-02 12:25:38.089  4359  4359 I Process : Sending signal. PID: 4359 SIG: 9
09-02 12:25:38.093   874  4391 D DhcpClient: Receive thread started
,09-02 12:25:38.108  1715  4371 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-02 12:25:38.110  1715  4371 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-02 12:25:38.112  4327  4373 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.112  4327  4373 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:25:38.112  4327  4373 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 12:25:38.112  4327  4373 E AndroidRuntime: Process: android.process.acore, PID: 4327
09-02 12:25:38.112  4327  4373 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.112  4327  4373 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:25:38.114   874  4392 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:25:38.114   874  4392 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	,at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:38.114   874  4392 E DropBoxManagerService: 	... 5 more
09-02 12:25:38.115  4327  4373 I Process : Sending signal. PID: 4327 SIG: 9
,09-02 12:25:38.120   874  2028 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4359) has died
,09-02 12:25:38.121  4378  4378 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-02 12:25:38.121   874  2028 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 12:25:38.135   874   888 I ActivityManager: Start proc 4393:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 12:25:38.152   874  2029 I ActivityManager: Process android.process.acore (pid 4327) has died
,09-02 12:25:38.152   874  2029 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-02 12:25:38.156  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-02 12:25:38.158  1515  1515 D AndroidRuntime: Shutting down VM
,09-02 12:25:38.159  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
09-02 12:25:38.159  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
09-02 12:25:38.159  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-02 12:25:38.159  1515  1515 E AndroidRuntime: 	... 8 more
,09-02 12:25:38.163  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
,09-02 12:25:38.164   874  4408 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:25:38.164   874  4408 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:25:38.164   874  4408 E DropBoxManagerService: 	... 5 more
,09-02 12:25:38.171   874  1381 I ActivityManager: Killing 3449:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-02 12:25:38.175   874  1316 E native  : do suspend false
,09-02 12:25:38.179  4393  4393 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:25:38.179  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:25:38.179  4393  4393 D AndroidRuntime: Shutting down VM
09-02 12:25:38.184   874  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 12:25:38.195   874  4391 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172781, domain null
,09-02 12:25:38.198   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
