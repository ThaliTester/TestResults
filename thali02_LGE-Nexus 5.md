#### Test 506502785b2d2b2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1647): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1647): Module APK com.google.android.play.games already loaded
D/Finsky  ( 2660): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/GAv4    ( 3091): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3091):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3091):   adb logcat -s GAv4
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAv4    ( 3091): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3091): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3091): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3091): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2660): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3091): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3091): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2660): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2660): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2660): untagSocket(37) failed with errno -22
D/Finsky  ( 2660): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1647): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  757): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3157 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 3157): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3157): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 1647): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1647): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1647): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/MultiDex( 3157): VM with version 2.1.0 has multidex support
I/MultiDex( 3157): install
I/MultiDex( 3157): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3157): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/qtaguid ( 2660): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2660): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2660): untagSocket(37) failed with errno -22
W/ActivityThread( 3157): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3157): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1373108c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3157): Installed default security provider GmsCore_OpenSSL
D/WearableService( 1579): callingUid 10008, callindPid: 1579
E/MDM     ( 1579): [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1579): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1647): Restart initialization of location
D/ChimeraCfgMgr( 3157): Reading stored module config
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1579): No location to return for getLastLocation()
W/FusedLocationProvider( 1579): location=null
D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.car from APK com.google.android.gms
D/NativeLibraryUtils( 3157): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 3157): Connecting to CarCallService...
I/art     ( 3157): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3157): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 3157): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3157): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3157): Creating a new PhoneAdapter instance
W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3157): setListener: com.google.android.gms.car.dn@225f00cb
W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3157): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3157): Starting CarCallService with initial phone null
D/CAR.SERVICE( 3157): Package validated; name: com.android.vending
V/Finsky  ( 2660): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2660): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2660): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2660): untagSocket(37) failed with errno -22
W/ResourcesManager( 2660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3195): 
D/AndroidRuntime( 3195): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3195): CheckJNI is OFF
D/AndroidRuntime( 3195): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ResourcesManager( 2660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3218 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3195): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 181us total 8.608ms
D/Finsky  ( 2660): [1] DailyHygiene.access$600: Logging device features
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 8.773ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 198us total 8.311ms
V/ActivityManager(  757): Display changed displayId=0
D/DeviceConnectionService( 1579): client connected with version: 8296000
D/Finsky  ( 2660): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2660): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2660): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/art     (  757): Explicit concurrent mark sweep GC freed 21434(996KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 883us total 62.835ms
,I/WebViewFactory( 3218): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3218): Time to load native libraries: 2 ms (timestamps 5477-5479)
,I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  757): Killing 2483:com.google.android.youtube/u0a80 (adj 15): empty #17
,V/WebViewChromiumFactoryProvider( 3218): Binding Chromium to main looper Looper (main, tid 1) {20d938da}
,I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
I/chromium( 3218): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3218): Initializing chromium process, singleProcess=true
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3218): ApplicationContext is null in ApplicationStatus
,W/chromium( 3218): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3218): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/ActivityManager(  757): Killing 2392:com.lge.SprintHiddenMenu/1000 (adj 15): empty #18
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26663670:true
,W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2483/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2392/cgroup.procs: No such file or directory
,W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3218): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3218): CordovaWebView is running on device made by: LGE
,W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3218): Render dirty regions requested: true
,D/Atlas   ( 3218): Validating map...
,W/chromium( 3218): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  757): Killing 2109:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2109/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 3218): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3218): Enabling debug mode 0
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +741ms (total +53s887ms)
,W/IInputConnectionWrapper( 3218): showStatusIcon on inactive InputConnection
,W/BindingManager( 3218): Cannot call determinedVisibility() - never saw a connection for the pid: 3218
,D/JsMessageQueue( 3218): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3218): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3218): jxcore cordova android initializing
,W/jxcore-log( 3218): Initializing JXcore engine
W/jxcore-log( 3218): JXcore engine is ready
,W/jxcore-log( 3218): Starting JXcore engine
,W/.test.thalitest( 3218): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10259]" dev="sockfs" ino=10259 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3218): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8432]" dev="sockfs" ino=8432 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19536]" dev="sockfs" ino=19536 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3218): Platform android
W/jxcore-log( 3218): 
W/jxcore-log( 3218): Process ARCH arm
W/jxcore-log( 3218): 
,I/jxcore-log( 3218): JXcore Cordova bridge is ready!
I/jxcore-log( 3218): 
W/jxcore-log( 3218): JXcore engine is started
I/Choreographer( 3218): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3218): Toggling radios to true
I/jxcore-log( 3218): 
,D/BluetoothAdapter( 3218): enable(): BT is already enabled..!
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: true pid=3218, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3218): Radios toggled
I/jxcore-log( 3218): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3218): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Perf Test app loaded loaded
I/jxcore-log( 3218): 
I/jxcore-log( 3218): check test folder
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): found test : ./testFindPeers.js
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  757): do suspend true
,I/jxcore-log( 3218): found test : ./testSendData.js
I/jxcore-log( 3218): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1579): Read error: ssl=0x9aff5e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1579): SSL shutdown failed: ssl=0x9aff5e00: I/O error during system call, Broken pipe
D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  757): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  987): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  757): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1647): CM callback handler got msg 524292
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,I/Choreographer( 3218): Skipped 65 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CAR.SERVICE( 3157): mConnectedToCar = false, abort
,E/ActivityThread( 3157): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d189a53 that was originally bound here
E/ActivityThread( 3157): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d189a53 that was originally bound here
E/ActivityThread( 3157): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3157): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3157): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3157): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3157): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3157): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3157): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3157): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3157): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3157): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3157): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3157): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3157): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3157): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3157): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3157): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3157): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3157): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3157): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3157): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@e604f9a that was originally bound here
E/ActivityThread( 3157): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@e604f9a that was originally bound here
E/ActivityThread( 3157): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3157): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3157): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3157): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3157): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3157): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3157): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3157): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3157): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3157): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3157): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3157): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3157): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3157): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3157): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3157): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3157): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3157): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  757): Unbind failed: could not find connection for android.os.BinderProxy@1d931ff7
,I/wpa_supplicant(  987): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  987): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  987): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  987): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  757): Start Dhcp Watchdog 2
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/dhcpcd  ( 3330): version 5.5.6 starting
,E/dhcpcd  ( 3330): get_duid: Read-only file system
,I/dhcpcd  ( 3330): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3330): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3330): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 101
,E/WifiStateMachine(  757): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  757): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757):    accepting network in place of null
D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1647): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 02:40:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450579244320], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450579244303]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1239): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1647): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2776): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2776): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2776): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1647): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1647): onCreate
,D/SystemUpdateService( 1647): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1647): active receiver: enabled
,I/SystemUpdateService( 1647): showing system update notification
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3415 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  757): No APN found to select.
,E/GpsLocationProvider(  757): No APN found to select.
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1647): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1647): onDestroy
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1647): CM callback handler got msg 524295
,I/GAv4    ( 3415): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3415):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3415):   adb logcat -s GAv4
,W/GAv4    ( 3415): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3415): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3415): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  757): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3415): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3415): Time to load native libraries: 3 ms (timestamps 2687-2690)
,I/LibraryLoader( 3415): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3415): Binding Chromium to main looper Looper (main, tid 1) {3721b4bc}
I/LibraryLoader( 3415): Expected native library version number "",actual native library version number ""
I/chromium( 3415): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3415): Initializing chromium process, singleProcess=true
,W/art     ( 3415): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3415): ApplicationContext is null in ApplicationStatus
,W/chromium( 3415): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3415): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3415): Requires BLUETOOTH permission
,I/NSApplication( 3415): Starting up...
,I/ActivityManager(  757): Killing 2585:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_2585/cgroup.procs: No such file or directory
,V/MusicLeanback( 2776): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1647): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1647): onCreate
,D/SystemUpdateService( 1647): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1647): active receiver: enabled
,I/SystemUpdateService( 1647): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1647): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1647): onDestroy
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3218): BLE supported!!
I/jxcore-log( 3218): 
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2776): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2776): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1647): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1647): onCreate
,D/SystemUpdateService( 1647): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1647): active receiver: enabled
,I/SystemUpdateService( 1647): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1647): retry (wakeup: false) in 3599982 ms
D/SystemUpdateService( 1647): onDestroy
E/GpsLocationProvider(  757): No APN found to select.
,D/Finsky  ( 2660): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2660): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1579): Vacuum at: now=1450579267673 tag=VacuumService
,I/PhenotypeConfigurator( 1579): Scheduling Phenotype for one-off execution 3208 seconds from now (1450579267932)
,D/GetConfigurationSnapshotOperation( 1579): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1579): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1579): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1579): disconnect managed GoogleApiClient
,I/jxcore-log( 3218): Connected to the server!
I/jxcore-log( 3218): 
,I/chromium( 3218): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3584 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3584): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3584):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3584):   adb logcat -s GAv4
,W/GAv4    ( 3584): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3584): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3584): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Killing 2753:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2753/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2731:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  757): Client connection lost with reason: 4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2731/cgroup.procs: No such file or directory
,I/jxcore-log( 3218): --- start :testSendData.js---
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): daya100000
I/jxcore-log( 3218): 
I/jxcore-log( 3218): check server
I/jxcore-log( 3218): 
I/jxcore-log( 3218): serverPort is 33159
I/jxcore-log( 3218): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT3882
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): bind: Binding a new listener
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3218): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): start: OK
I/io.jxcore.node.ConnectionHelper( 3218): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT3882
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3218): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3218): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3218): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Waiting for incoming connections...
,I/art     (  757): Explicit concurrent mark sweep GC freed 53805(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.127ms total 54.947ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3218): start: OK
I/jxcore-log( 3218): StartBroadcasting started ok
I/jxcore-log( 3218): 
I/jxcore-log( 3218): null
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:46:39.567Z SendDataTCPServer.js: TCP/IP server is bound to port: 33159
I/jxcore-log( 3218): 
I/chromium( 3218): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3218): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3218): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3218): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6125","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-G900F_PT6125, Available: true
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[1]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:30.278Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:30.280Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:30.280Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 298)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3640 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a7a9f84:true
,I/ActivityManager(  757): Killing 2603:com.google.android.gm/u0a70 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2603/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 299)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Outgoing connection initialized (*handshake* thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 299)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesRead: Read 82 bytes successfully (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 299)
,D/io.jxcore.node.OutgoingSocketThread( 3218): Entering thread (ID: 300)
,D/io.jxcore.node.OutgoingSocketThread( 3218): Server socket local port: 33058
I/io.jxcore.node.OutgoingSocketThread( 3218): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3218): onListeningForIncomingConnections: Outgoing connection is using port 33058 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 3218): 2015-12-20T02:47:32.745Z SendDataConnector.js: CLIENT connected to 33058, error: null
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:32.748Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3218): 
,I/io.jxcore.node.OutgoingSocketThread( 3218): Incoming data from address: /127.0.0.1, port: 33058
,D/io.jxcore.node.OutgoingSocketThread( 3218): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3218): Exiting thread (ID: 300)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 301, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 302, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:32.812Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.399Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.456Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.487Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.625Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.668Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.683Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.726Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.745Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.841Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3218): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1380","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1380","peerAvailable":true}]
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Found peer : samsung-SM-A300FU_PT1380, Available: true
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.890Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:33.891Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:33.900Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:33.900Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3218): close
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 302
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 301
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 301, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3218): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 302, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 301, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 302, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:33.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[2]: 08:EC:A9:50:75:41
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:33.942Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:33.942Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:33.942Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 303)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 304)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Outgoing connection initialized (*handshake* thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 304)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesRead: Read 83 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3218): Entering thread (ID: 305)
,D/io.jxcore.node.OutgoingSocketThread( 3218): Server socket local port: 44786
I/io.jxcore.node.OutgoingSocketThread( 3218): Now accepting connections...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/io.jxcore.node.ConnectionHelper( 3218): onListeningForIncomingConnections: Outgoing connection is using port 44786 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 3218): 2015-12-20T02:47:36.485Z SendDataConnector.js: CLIENT connected to 44786, error: null
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:36.486Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3218): 
,I/io.jxcore.node.OutgoingSocketThread( 3218): Incoming data from address: /127.0.0.1, port: 44786
D/io.jxcore.node.OutgoingSocketThread( 3218): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3218): Exiting thread (ID: 305)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 306, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 307, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:36.526Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,E/bt-btm  ( 2137): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2137): bta_dm_check_av:0
,W/bt-btif ( 2137): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2da4eba2:true
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: S5-1
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3218): 2015-12-20T02:47:38.315Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:38.431Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3218): 2015-12-20T02:47:38.489Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:47:38.541Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3218): 2015-12-20T02:47:38.572Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:38.691Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:38.767Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:47:38.928Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:39.095Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:47:39.548Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:39.549Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:39.551Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:39.554Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3218): close
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 307
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 306
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 306, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3218): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 306, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
,D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 307, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:39.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5335","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT5335","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : HTC-HTC One M8s_PT5335, Available: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): device[3]: 90:E7:C4:F6:69:77
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:44.072Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:44.073Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:44.074Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 308)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Outgoing connection initialized (*handshake* thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesRead: Read 81 bytes successfully (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3218): Entering thread (ID: 310)
,D/io.jxcore.node.OutgoingSocketThread( 3218): Server socket local port: 52905
I/io.jxcore.node.OutgoingSocketThread( 3218): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3218): onListeningForIncomingConnections: Outgoing connection is using port 52905 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3218): 2015-12-20T02:47:47.734Z SendDataConnector.js: CLIENT connected to 52905, error: null
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:47.735Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3218): 
,I/io.jxcore.node.OutgoingSocketThread( 3218): Incoming data from address: /127.0.0.1, port: 52905
D/io.jxcore.node.OutgoingSocketThread( 3218): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3218): Exiting thread (ID: 310)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 312, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:47.768Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3218): 
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 311, name: Sender)
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3218): 2015-12-20T02:47:48.501Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:48.591Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3218): 2015-12-20T02:47:48.726Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:48.757Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3218): 2015-12-20T02:47:48.866Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] already in the list, will not add again
,I/jxcore-log( 3218): 2015-12-20T02:47:49.388Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:49.405Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:49.671Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:49.672Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:49.673Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:49.674Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3218): 
D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 3218): close
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 311
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3218): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 312, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 311, name: Sender)
,I/jxcore-log( 3218): 2015-12-20T02:47:49.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:255
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Incoming connection initialized (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 313)
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2137): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2137): bta_dm_check_av:0
,W/bt-btif ( 2137): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): onBytesRead: Read 81 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): removeThreadFromList: Removing thread with ID 313
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], created successfully
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3218): Entering thread (ID: 314)
,I/jxcore-log( 3218): 2015-12-20T02:47:52.586Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3218): 
,I/io.jxcore.node.IncomingSocketThread( 3218): Local host address: localhost/127.0.0.1, port: 33159
D/io.jxcore.node.IncomingSocketThread( 3218): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3218): Exiting thread (ID: 314)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 316, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 315, name: Sender)
,I/jxcore-log( 3218): 2015-12-20T02:47:53.621Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:53.714Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:53.805Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:54.360Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:54.608Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3218): 
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:255
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 317)
,I/jxcore-log( 3218): 2015-12-20T02:47:54.692Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): onBytesRead: Read 83 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): removeThreadFromList: Removing thread with ID 317
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 317)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], created successfully
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3218): Entering thread (ID: 318)
,I/io.jxcore.node.IncomingSocketThread( 3218): Local host address: localhost/127.0.0.1, port: 33159
D/io.jxcore.node.IncomingSocketThread( 3218): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3218): 2015-12-20T02:47:54.723Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3218): 
,I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3218): Exiting thread (ID: 318)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 320, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 319, name: Sender)
,I/jxcore-log( 3218): 2015-12-20T02:47:54.857Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3218): 
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3218): 2015-12-20T02:47:55.101Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.118Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.201Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.269Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.282Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.288Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.360Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.446Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.454Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.545Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.607Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.858Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.864Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.890Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:55.946Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.015Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.079Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.088Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.094Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.098Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.106Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.172Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.226Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.234Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.254Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:56.256Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.286Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:47:56.287Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.293Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.314Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.336Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.347Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.358Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.366Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.385Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.422Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.425Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.440Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.462Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.464Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.469Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.502Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.528Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.541Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.560Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.585Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.591Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.625Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.646Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.666Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.676Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.685Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.698Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.749Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.760Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.827Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.834Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.910Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.920Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:56.930Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.025Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.031Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.103Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.147Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.169Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.175Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.189Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.197Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.208Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.211Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.249Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.257Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.270Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.303Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.348Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3218): 
,W/bt-btif ( 2137): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3218): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 314
D/io.jxcore.node.IncomingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 316
D/io.jxcore.node.IncomingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 315
D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3218): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 315, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:57.566Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3218): 
,W/bt-rfcomm( 2137): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2137): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3218): 2015-12-20T02:47:57.714Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.752Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.878Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:47:57.885Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3218): 
,W/bt-btif ( 2137): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3218): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 318
D/io.jxcore.node.IncomingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 320
D/io.jxcore.node.IncomingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3218): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 319, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 320, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:47:58.400Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3218): 
,W/bt-rfcomm( 2137): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2137): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2137): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2137): bta_dm_check_av:0
,W/bt-btif ( 2137): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: HTC One M8s
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1450","peerAvailable":true}]
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Found peer : LGE-LG-D722_PT1450, Available: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[4]: F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:22.838Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:22.838Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:22.838Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT9057","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-A500FU_PT9057, Available: true
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 321)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 321)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 321)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/jxcore-log( 3218): 2015-12-20T02:49:27.979Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:27.979Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:27.980Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] removed
,D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] not available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1380","peerAvailable":false}]
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT5335","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT8343","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : LGE-LG-H815_PT8343, Available: true
I/jxcore-log( 3218): 
D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/jxcore-log( 3218): 2015-12-20T02:49:32.980Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:32.980Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6052","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-A300FU_PT6052, Available: true
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:49:37.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:37.987Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:37.987Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:37.988Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/jxcore-log( 3218): 2015-12-20T02:49:53.010Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:53.010Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:49:53.011Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:49:58.022Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:49:58.022Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6125","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:50:03.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:03.028Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:03.029Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:03.030Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":true}]
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Found peer : samsung-SM-G900F_PT1824, Available: true
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/jxcore-log( 3218): 2015-12-20T02:50:18.054Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:18.059Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:18.060Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:50:23.061Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:23.062Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:50:28.066Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:28.067Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:28.067Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:28.068Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null F8:95:C7:87:85:54
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x4b
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 11
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/jxcore-log( 3218): 2015-12-20T02:50:43.083Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:43.084Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:43.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:50:48.086Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:48.087Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
,I/jxcore-log( 3218): 2015-12-20T02:50:53.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:53.098Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:53.098Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:50:53.099Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/jxcore-log( 3218): 2015-12-20T02:51:08.114Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:08.115Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:08.116Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:51:08.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[5]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:08.137Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:08.138Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:08.139Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x4c
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 12
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/jxcore-log( 3218): 2015-12-20T02:51:23.159Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:23.160Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:23.160Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/jxcore-log( 3218): 2015-12-20T02:51:28.169Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:28.170Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Found peer : samsung-SM-G900F_PT1824, Available: false
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] not available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6052","peerAvailable":false}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-A300FU_PT6052, Available: false
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:51:33.174Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:33.175Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:33.176Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:33.176Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/jxcore-log( 3218): 2015-12-20T02:51:48.195Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:48.196Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:48.197Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:51:53.198Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:53.199Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:51:58.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:58.205Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:58.207Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:51:58.207Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:37:96:AB
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/jxcore-log( 3218): 2015-12-20T02:52:13.228Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:13.229Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:13.230Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x4d
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 327)
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 15
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 337)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 323)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 337)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 337)
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3218): 2015-12-20T02:52:18.231Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:18.232Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 16
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:52:23.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:23.237Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:23.237Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:23.238Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 338)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/jxcore-log( 3218): 2015-12-20T02:52:38.258Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:38.259Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:38.259Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/jxcore-log( 3218): 2015-12-20T02:52:43.259Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:43.260Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:52:48.267Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:48.267Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:48.268Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:52:48.269Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 340)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,E/bt-btm  ( 2137): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2137): bta_dm_check_av:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 325)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 325)
,W/bt-btif ( 2137): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 325)
,W/bt-btif ( 2137): btif_dm_cback : unhandl
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: G3s-1
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 18
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] removed
,D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] not available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT8343","peerAvailable":false}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : LGE-LG-H815_PT8343, Available: false
I/jxcore-log( 3218): 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 19
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6125","peerAvailable":true}]
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6052","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-A300FU_PT6052, Available: true
I/jxcore-log( 3218): 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 21
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 331)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 331)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/jxcore-log( 3218): 2015-12-20T02:54:01.683Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:01.683Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:01.685Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:54:01.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[6]: 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:01.691Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:54:01.700Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:01.701Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 342)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0xd  CID 0x48
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 22
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 338)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 338)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 24
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 333)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 333)
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 335)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 335)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 340)
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 26
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: A5-1
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 342)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 342)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 342)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/jxcore-log( 3218): 2015-12-20T02:54:13.789Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:13.790Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] failed
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:54:13.795Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] already in the list, will not add again
,I/jxcore-log( 3218): 2015-12-20T02:54:18.797Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:54:18.798Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 3218): 2015-12-20T02:54:23.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:23.808Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:23.808Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:23.809Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/jxcore-log( 3218): 2015-12-20T02:54:38.824Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:38.824Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:38.825Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:54:43.826Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:43.827Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 3218): 2015-12-20T02:54:48.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:48.838Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:48.838Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:54:48.839Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 28
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/jxcore-log( 3218): 2015-12-20T02:55:03.856Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:03.857Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:03.858Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:55:08.859Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:55:08.865Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:55:13.879Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:13.880Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:13.880Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:55:13.881Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 29
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/jxcore-log( 3218): 2015-12-20T02:55:28.906Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:28.910Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:28.911Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:55:33.912Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:33.913Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:55:38.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:38.917Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:38.918Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:38.918Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6052","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/art     ( 1579): Explicit concurrent mark sweep GC freed 92688(5MB) AllocSpace objects, 30(503KB) LOS objects, 40% free, 23MB/38MB, paused 907us total 54.803ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/jxcore-log( 3218): 2015-12-20T02:55:53.935Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:53.936Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:55:53.938Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 3218): 2015-12-20T02:55:53.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x8  CID 0x4f
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 30
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 344)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 344)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 32
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 346)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 346)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 346)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 33
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,E/bt-rfcomm( 2137): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2137): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2137): invalid rfc slot id: 34
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 350)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 350)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2137): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 352)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Outgoing connection initialized (*handshake* thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 352)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 352)
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT2008","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT2008","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-A500FU_PT2008, Available: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[7]: 7C:F9:0E:51:18:22
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:32.590Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:32.591Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:32.598Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 353)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2137): info:x10
,D/        ( 2137): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2137): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2137): process_service_search_attr_rsp
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2137): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2137): Entering PendingCommandState State
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/BluetoothBondStateMachine( 2137): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
D/BluetoothAdapterProperties( 2137): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2137): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2137): StableState(): Entering Off State
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2137): new conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2137): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesWritten: 77 bytes successfully written (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Outgoing connection initialized (*handshake* thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Entering thread (ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): onBytesRead: Read 83 bytes successfully (thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3218): Exiting thread (ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3218): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3218): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3218): Entering thread (ID: 355)
D/io.jxcore.node.OutgoingSocketThread( 3218): Server socket local port: 33528
I/io.jxcore.node.OutgoingSocketThread( 3218): Now accepting connections...
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3218): onListeningForIncomingConnections: Outgoing connection is using port 33528 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3218): 2015-12-20T02:56:34.610Z SendDataConnector.js: CLIENT connected to 33528, error: null
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:34.610Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3218): 
,I/io.jxcore.node.OutgoingSocketThread( 3218): Incoming data from address: /127.0.0.1, port: 33528
D/io.jxcore.node.OutgoingSocketThread( 3218): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3218): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3218): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3218): Exiting thread (ID: 355)
,I/jxcore-log( 3218): 2015-12-20T02:56:34.635Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3218): 
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 357, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3218): Entering thread (ID: 356, name: Sender)
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3218): 2015-12-20T02:56:35.283Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : samsung-SM-G900F_PT1824, Available: true
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:35.445Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3218): 2015-12-20T02:56:35.546Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:35.749Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3218): 
,D/        ( 2137): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3218): 2015-12-20T02:56:35.936Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:35.987Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:36.054Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:36.078Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:36.616Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:36.687Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:36.687Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:36.689Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:36.689Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3218): close
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 357
D/io.jxcore.node.OutgoingSocketThread( 3218): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3218): doStop: Thread ID: 356
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 356, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3218): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3218): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3218): Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3218): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3218): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 356, name: Sender)
,W/bt-btif ( 2137): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3218): Exiting thread (ID: 357, name: Receiver)
,I/jxcore-log( 3218): 2015-12-20T02:56:36.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/jxcore-log( 3218): device[8]: B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:36.750Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:36.755Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:36.756Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 358)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2137): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2137): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2137): onReceive
,I/BTConnectionReceiver( 1387): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1387): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/jxcore-log( 3218): 2015-12-20T02:56:51.769Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:51.770Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:51.770Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:56:56.781Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:56:56.781Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:57:01.786Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:01.787Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:01.787Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:01.788Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null B0:C5:59:3F:75:69
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 360)
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 358)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 358)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 358)
,W/bt-btif ( 2137): invalid rfc slot id: 36
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 358)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/jxcore-log( 3218): 2015-12-20T02:57:08.706Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:08.706Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] failed
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:08.707Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2137): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): 2015-12-20T02:57:13.708Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:13.709Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:57:18.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:18.714Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:18.715Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:18.715Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/jxcore-log( 3218): 2015-12-20T02:57:33.733Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:33.734Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:33.735Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/jxcore-log( 3218): 2015-12-20T02:57:38.737Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:38.737Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:57:43.748Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:43.748Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:43.749Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:43.749Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] not available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/jxcore-log( 3218): 2015-12-20T02:57:58.766Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:58.767Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:57:58.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T02:58:03.769Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:03.770Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 37
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 360)
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:58:08.775Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:08.776Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:08.777Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:08.777Z SendDataConnector.js: do connect now
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3218): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): connect: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3218): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3218): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionTimeout: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/jxcore-log( 3218): 2015-12-20T02:58:23.797Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:23.798Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69] timed out
I/jxcore-log( 3218): 
I/jxcore-log( 3218): oneRoundDownNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): 2015-12-20T02:58:23.800Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
,D/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3218): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3218): 2015-12-20T02:58:23.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ---- round done--------
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5335","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT5335","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 38
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2137): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 39
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 40
,W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2137): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2137): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1450","peerAvailable":false}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 362)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 362)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1450","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT2008","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,W/bt-sdp  ( 2137): SDP - Rcvd conn cnf with error: 0x22  CID 0x4e
E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 42
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 364)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 364)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 364)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2137): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,E/bt-btif ( 2137): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2137): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Maximum number of allowed retries (0) reached, giving up... (thread ID: 366)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): Exiting thread (thread ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3218): shutdown (thread ID: 366)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6052","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1380","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1380","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/jxcore-log( 3218): timeout now
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): weAreDoneNow, resultArray.length: 8
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): sendReportNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): done, now sending data to server
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T03:03:19.629Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
,I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8208","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] is available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT8208","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : LGE-LG-D855_PT8208, Available: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT8343","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : LGE-LG-H815_PT8343, Available: true
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5335","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1380","peerAvailable":false}]
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,W/bt-smp  ( 2137): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2137): Plain text(LSB ~ MSB) = d4 b7 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2137): Encrypted text(LSB ~ MSB) = 1c ab 67 35 cd d3 67 42 f2 51 75 28 91 14 34 80 
,W/bt-btm  ( 2137): Stopping oneshot timer
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/EventLogService( 1647): Aggregate from 1450578780584 (log), 1450578780584 (data)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":false}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] not available
I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT8208","peerAvailable":false}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : LGE-LG-D855_PT8208, Available: false
I/jxcore-log( 3218): 
I/jxcore-log( 3218): startWithNextDevice
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3218): teardown
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): testSendData stopped
I/jxcore-log( 3218): 
I/io.jxcore.node.ConnectionHelper( 3218): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): shutdown,
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3218): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setState: NOT_STARTED
I/jxcore-log( 3218): StopBroadcasting went ok
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): 2015-12-20T03:06:39.008Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3218): 
,I/chromium( 3218): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3218): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3218): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3218): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3218): --- start :testFindPeers.js---
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): testFindPeers created [object Object]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): serverPort is 8876
I/jxcore-log( 3218): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT3882
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): bind: Binding a new listener
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3218): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3218): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3218): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3218): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3218): start: OK
I/io.jxcore.node.ConnectionHelper( 3218): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT3882
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3218): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3218): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3218): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3882","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3218): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3218): start: OK
I/jxcore-log( 3218): StartBroadcasting started ok
I/jxcore-log( 3218): 
I/chromium( 3218): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3218): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3218): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3218): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Failed to start the service discovery, got error code: 3
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] is available
,I/jxcore-log( 3218): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1824","peerAvailable":true}]
I/jxcore-log( 3218): 
I/jxcore-log( 3218): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): weAreDoneNow
I/jxcore-log( 3218): 
I/jxcore-log( 3218): done, now sending data to server
I/jxcore-log( 3218): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1824","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5335","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1380","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8208","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] is available
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT2008","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8208","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] not available
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1380] not available
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] not available
I/io.jxcore.node.ConnectionHelper( 3218): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT8208]
D/io.jxcore.node.ConnectionHelper( 3218): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] removed
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6052","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  987): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6125","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8343","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1450","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5335","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT2008","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3218): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT2008] is available
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1450], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3218): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT5335]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Start timer timeout, starting now...
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): restart: Restarting...
,D/WifiP2pManager( 3218): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service request added successfully
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): Service discovery started successfully
,I/wpa_supplicant(  987): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  987): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9057","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3218): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057]
I/io.jxcore.node.ConnectionHelper( 3218): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3218): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] already in the list, will not add again
,TIME-OUT KILL (timeout was 1800000ms),I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): setState: RESTARTING
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  987): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3218): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3218): onP2pDeviceListChanged: 0 device(s) discovered
I/ActivityManager(  757): Killing 2997:com.android.defcontainer/u0a5 (adj 13): empty for 1812s
I/ActivityManager(  757): Killing 2059:com.android.providers.calendar/u0a2 (adj 13): empty for 1812s
I/ActivityManager(  757): Killing 3157:com.google.android.gms:car/u0a8 (adj 13): empty for 1812s
I/ActivityManager(  757): Killing 3091:com.google.android.apps.docs/u0a40 (adj 13): empty for 1814s
I/ActivityManager(  757): Killing 3056:com.android.musicfx/u0a15 (adj 15): empty for 1815s
I/ActivityManager(  757): Killing 1465:com.google.android.partnersetup/u0a13 (adj 15): empty for 1815s
I/ActivityManager(  757): Killing 2037:com.google.android.calendar/u0a31 (adj 15): empty for 1843s
I/ProcessStatsService(  757): Prepared write state in 4ms
W/libprocessgroup(  757): failed to open /acct/uid_10002/pid_2059/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10013/pid_1465/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10031/pid_2037/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10005/pid_2997/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10008/pid_3157/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10040/pid_3091/cgroup.procs: No such file or directory
W/libprocessgroup(  757): failed to open /acct/uid_10015/pid_3056/cgroup.procs: No such file or directory
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ProcessStatsService(  757): Pruning old procstats: /data/system/procstats/state-2015-12-19-03-01-27.bin
D/AndroidRuntime( 3864): 
D/AndroidRuntime( 3864): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3864): CheckJNI is OFF
D/AndroidRuntime( 3864): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 3218:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
W/PackageSettings(  757): Skipping PackageSetting{3e2569ce com.example.hello/10278} due to missing metadata
D/WifiService(  757): Client connection lost with reason: 4
I/WindowState(  757): WIN DEATH: Window{15295b2a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  757):   Force finishing activity ActivityRecord{14ed50c3 u0 com.test.thalitest/.MainActivity t214}
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  757):   Force finishing activity ActivityRecord{14ed50c3 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  757): Duplicate finish request for ActivityRecord{14ed50c3 u0 com.test.thalitest/.MainActivity t214 f}
I/art     ( 1647): Explicit concurrent mark sweep GC freed 10447(568KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 853us total 62.727ms
W/ActivityManager(  757): Spurious death for ProcessRecord{1478d777 3218:com.test.thalitest/u0a270}, curProc for 3218: null
I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1579): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1092): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1092): run()
I/art     ( 1283): Explicit concurrent mark sweep GC freed 3969(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 225us total 56.457ms
I/art     ( 1387): Explicit concurrent mark sweep GC freed 40493(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 19MB/26MB, paused 396us total 93.856ms
D/VoicemailCleanupService( 1362): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1092): createOrResetDecoder
I/art     (  757): Explicit concurrent mark sweep GC freed 90526(4MB) AllocSpace objects, 11(254KB) LOS objects, 33% free, 28MB/43MB, paused 1.185ms total 106.726ms
I/art     (  757): WaitForGcToComplete blocked for 32.618ms for cause Explicit
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3895 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
D/OpenGLRenderer(  946): Enabling debug mode 0
W/InputMethodManagerService(  757): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3080a15f (uid=10034 pid=946)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1092): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1092): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1092): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1092): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1092): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1092): run()
I/StatsUtilsManager( 1092): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1092): shouldRecordStats() = Too Soon
I/UpdateIcingCorporaServi( 1387): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  757): Killing 2776:com.google.android.music:main/u0a60 (adj 15): empty for 1804s
W/Launcher( 1283): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e6bd10b new=com.google.android.velvet.VelvetApplication@3e6bd10b
D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  757): Explicit concurrent mark sweep GC freed 9770(489KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.522ms total 170.062ms
I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3921 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/libprocessgroup(  757): failed to open /acct/uid_10060/pid_2776/cgroup.procs: No such file or directory
I/Launcher( 1283): Deferring update until onResume
D/AndroidRuntime( 3864): Shutting down VM
D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
W/ResourcesManager( 1283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 3921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1387): UpdateCorporaTask done [took 176 ms] updated apps [took 176 ms] 
D/PackageBroadcastService( 1647): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1647): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1647): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1647): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1647): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1647): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 1283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/LocationSettingsChecker( 1647): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1579): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1579): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Launcher( 1283): Deferring update until onResume
I/ActivityManager(  757): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3943 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1647): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1647): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1647): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1647): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1647): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1647): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1647): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1647): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1647): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1647): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1647): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1647): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1647): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1647): Using Auth Proxy for data requests.
I/GMPM-SVC( 1647): App measurement is starting up, version: 8489
I/GMPM-SVC( 1647): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1647): Using Auth Proxy for data requests.
I/Icing   ( 1647): doRemovePackageData com.test.thalitest
I/GAv4    ( 3943): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3943):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3943):   adb logcat -s GAv4

```
