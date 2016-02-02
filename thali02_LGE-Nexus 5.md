#### Test 5797209499148df_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3022): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3022):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3022):   adb logcat -s GAv4
W/GAv4    ( 3022): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/qtaguid ( 2570): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2570): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2570): untagSocket(37) failed with errno -22
D/Finsky  ( 2570): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
W/GAv4    ( 3022): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3022): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3022): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
--------- beginning of system
I/ActivityManager(  759): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3059 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 185us total 8.027ms
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 172us total 7.473ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 7.571ms
W/ResourcesManager( 3059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3059): VM with version 2.1.0 has multidex support
I/MultiDex( 3059): install
I/MultiDex( 3059): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 2570): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ActivityThread( 3059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38d53ae6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3059): Installed default security provider GmsCore_OpenSSL
V/JNIHelp ( 3022): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ChimeraCfgMgr( 3059): Reading stored module config
I/qtaguid ( 2570): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2570): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2570): untagSocket(37) failed with errno -22
D/WearableService( 1606): callingUid 10008, callindPid: 1606
E/MDM     ( 1606): [221] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1606): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1625): Restart initialization of location
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 3059): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1606): No location to return for getLastLocation()
W/FusedLocationProvider( 1606): location=null
W/System  ( 3022): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3022): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NativeLibraryUtils( 3059): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 3059): Connecting to CarCallService...
I/art     ( 3059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 3059): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3059): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3059): Creating a new PhoneAdapter instance
W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3059): setListener: com.google.android.gms.car.dn@1b21b6ed
W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3059): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3059): Starting CarCallService with initial phone null
D/CAR.SERVICE( 3059): Package validated; name: com.android.vending
V/Finsky  ( 2570): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/Icing   ( 1625): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1625): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1625): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1625): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2570): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2570): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2570): untagSocket(37) failed with errno -22
W/ResourcesManager( 2570): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2570): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2570): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2570): [1] DailyHygiene.access$600: Logging device features
D/DeviceConnectionService( 1606): client connected with version: 8296000
D/Finsky  ( 2570): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2570): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2570): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3113): 
D/AndroidRuntime( 3113): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3113): CheckJNI is OFF
D/AndroidRuntime( 3113): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3144 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3113): Shutting down VM
I/ActivityManager(  759): Killing 2055:com.google.android.deskclock/u0a38 (adj 15): empty #17
I/ActivityManager(  759): Killing 2386:com.google.android.youtube/u0a80 (adj 15): empty #18
V/ActivityManager(  759): Display changed displayId=0
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2055/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2386/cgroup.procs: No such file or directory
,I/WebViewFactory( 3144): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3144): Time to load native libraries: 1 ms (timestamps 4568-4569)
,I/LibraryLoader( 3144): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3144): Binding Chromium to main looper Looper (main, tid 1) {1953d044}
I/LibraryLoader( 3144): Expected native library version number "",actual native library version number ""
I/chromium( 3144): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3144): Initializing chromium process, singleProcess=true
W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3144): ApplicationContext is null in ApplicationStatus
,W/chromium( 3144): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3144): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c5654c7:true
,I/art     (  759): Explicit concurrent mark sweep GC freed 19709(922KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 987us total 49.231ms
,W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3144): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3144): CordovaWebView is running on device made by: LGE
,W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3144): Render dirty regions requested: true
,D/Atlas   ( 3144): Validating map...
,W/chromium( 3144): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3144): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3144): Enabling debug mode 0
,I/Keyboard.Facilitator( 1087): onFinishInput()
,W/IInputConnectionWrapper( 3144): showStatusIcon on inactive InputConnection
,W/BindingManager( 3144): Cannot call determinedVisibility() - never saw a connection for the pid: 3144
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +490ms (total +52s572ms)
,D/JsMessageQueue( 3144): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3144): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3144): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  759): Killing 2538:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2538/cgroup.procs: No such file or directory
,W/jxcore-log( 3144): Initializing JXcore engine
W/jxcore-log( 3144): JXcore engine is ready
,W/Thread-301( 3209): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8732]" dev="sockfs" ino=8732 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3209): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-301( 3209): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6735]" dev="sockfs" ino=6735 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3209): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20668]" dev="sockfs" ino=20668 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3144): Starting JXcore engine
,W/jxcore-log( 3144): Platform android
W/jxcore-log( 3144): 
W/jxcore-log( 3144): Process ARCH arm
W/jxcore-log( 3144): 
,I/jxcore-log( 3144): JXcore Cordova bridge is ready!
I/jxcore-log( 3144): 
W/jxcore-log( 3144): JXcore engine is started
,I/jxcore-log( 3144): Toggling radios to true
I/jxcore-log( 3144): 
,D/BluetoothAdapter( 3144): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3144, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3144): Radios toggled
I/jxcore-log( 3144): 
I/jxcore-log( 3144): My device name is: LGE-Nexus 5
I/jxcore-log( 3144): 
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1606): Read error: ssl=0xb4028e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1606): SSL shutdown failed: ssl=0xb4028e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
E/native  (  759): do suspend true
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1226): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  759): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  759): Killing 2494:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2494/cgroup.procs: No such file or directory
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,D/CAR.SERVICE( 3059): mConnectedToCar = false, abort
,E/ActivityThread( 3059): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@324bf635 that was originally bound here
E/ActivityThread( 3059): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@324bf635 that was originally bound here
E/ActivityThread( 3059): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3059): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3059): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3059): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3059): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3059): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3059): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3059): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3059): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3059): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3059): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3059): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3059): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3059): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3059): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3059): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3059): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3059): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3059): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3059): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2af56104 that was originally bound here
E/ActivityThread( 3059): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2af56104 that was originally bound here
E/ActivityThread( 3059): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3059): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3059): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3059): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3059): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3059): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3059): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3059): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3059): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3059): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3059): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3059): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3059): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3059): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3059): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3059): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3059): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3059): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@34748390
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3256): version 5.5.6 starting
E/dhcpcd  ( 3256): get_duid: Read-only file system
,I/dhcpcd  ( 3256): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3256): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3256): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/Tethering(  759): MasterInitialState.processMessage what=3
,E/GpsLocationProvider(  759): No APN found to select.
,V/MusicLeanback( 2682): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1625): num queued entries: 0
I/iu.UploadsManager( 1625): num updated entries: 0
,I/iu.SyncManager( 1625): NEXT; no task
,I/SystemUpdateService( 1625): active receiver: enabled
,I/SystemUpdateService( 1625): showing system update notification
,I/Babel   ( 1923): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3298 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,E/native  (  759): do suspend true
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599910 ms
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  759): Adding iface wlan0 to network 101
E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/SystemUpdateService( 1625): onDestroy
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
,I/GAv4    ( 3298): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3298):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3298):   adb logcat -s GAv4
,W/GAv4    ( 3298): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:35:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454416540220], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454416540203]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1226): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3298): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3298): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3298): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3298): Time to load native libraries: 2 ms (timestamps 260-262)
I/LibraryLoader( 3298): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3298): Binding Chromium to main looper Looper (main, tid 1) {25582996}
,I/LibraryLoader( 3298): Expected native library version number "",actual native library version number ""
,I/chromium( 3298): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3298): Initializing chromium process, singleProcess=true
W/art     ( 3298): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3298): ApplicationContext is null in ApplicationStatus
,W/chromium( 3298): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3298): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3298): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3298): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3298): Requires BLUETOOTH permission
,I/NSApplication( 3298): Starting up...
,I/ActivityManager(  759): Killing 2658:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2658/cgroup.procs: No such file or directory
,V/MusicLeanback( 2682): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1625): num queued entries: 0
I/iu.UploadsManager( 1625): num updated entries: 0
,I/iu.SyncManager( 1625): NEXT; no task
I/SystemUpdateService( 1625): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599926 ms
,D/SystemUpdateService( 1625): onDestroy
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3144): 
,I/Babel   ( 1923): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3144): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2682): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2682): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     ( 1625): WaitForGcToComplete blocked for 28.173ms for cause DisableMovingGc
,I/art     ( 1625): WaitForGcToComplete blocked for 27.950ms for cause DisableMovingGc
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GpsLocationProvider(  759): No APN found to select.
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1625): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599964 ms
,D/SystemUpdateService( 1625): onDestroy
,I/jxcore-log( 3144): Test app app.js loaded
I/jxcore-log( 3144): 
,I/chromium( 3144): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b51dd29 added. We now have 1 listener(s)
,I/jxcore-log( 3144): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3144): 
,D/Finsky  ( 2570): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2570): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1606): Vacuum at: now=1454416563652 tag=VacuumService
,I/PhenotypeConfigurator( 1606): Scheduling Phenotype for one-off execution 11801 seconds from now (1454416564086)
,D/GetConfigurationSnapshotOperation( 1606): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1606): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1606): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1087): run()
I/Keyboard.Facilitator( 1087): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1606): disconnect managed GoogleApiClient
,D/HeadsetStateMachine( 2078): Disconnected process message: 10, size: 0
,I/jxcore-log( 3144): TAP version 13
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # multiplex can send data
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 1 String should be length:200
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # enqueue and run in order
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 2 firstPromise setTimeout
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 3 firstPromise result
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 4 firstPromise testValue
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 5 secondPromise setTimeout
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 6 secondPromise result
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 7 secondPromise testValue
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 8 thirdPromise in promise
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 9 thirdPromise result
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 10 thirdPromise testValue
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # basic
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 11 sane
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # another
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 12 sane
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 13 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 14 null
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 15 (unnamed assert)
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 16 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 17 should not throw
I/jxcore-log( 3144): 
I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 18 (unnamed assert)
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 19 (unnamed assert)
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 20 should not throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 21 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 22 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 23 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # failed to get mobile documents path
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 24 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 25 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 26 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 27 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #init should register the networkChanged event
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 28 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on null device name
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 29 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 30 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 31 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 32 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on negative port
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 33 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should throw on too large port
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 34 should throw
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 35 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 36 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 37 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 38 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 39 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 40 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 41 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 42 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 43 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 44 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 45 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 46 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 47 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 48 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 49 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 50 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 51 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): ok 52 should be equal
I/jxcore-log( 3144): 
I/jxcore-log( 3144): ok 53 should be equal
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # teardown
I/jxcore-log( 3144): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f3d8ae added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742814.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742814.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742814.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742814.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742814.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416742814.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742814.3144, mode: WIFI
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
,I/jxcore-log( 3144): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1028d1ba added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742879.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742879.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742879.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742879.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742879.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416742879.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742879.3144, mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
I/jxcore-log( 3144): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f824f86 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742930.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742930.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742930.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742930.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742930.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416742930.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742930.3144, mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/jxcore-log( 3144): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a3de12 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742984.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742984.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742984.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742984.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416742984.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416742984.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416742984.3144, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/jxcore-log( 3144): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddc95e added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743021.3144
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743021.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743021.3144, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743021.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743021.3144","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743021.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743021.3144, mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3144): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
,I/io.jxcore.node.ConnectionHelper( 3144): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8391d6a added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743058.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743058.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743058.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743058.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743058.3144","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743058.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743058.3144, mode: WIFI
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/jxcore-log( 3144): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,I/jxcore-log( 3144): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3443a636 added. We now have 8 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743096.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/art     (  759): Explicit concurrent mark sweep GC freed 54638(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 786us total 89.890ms
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743096.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743096.3144, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743096.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743096.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743096.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743096.3144, mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3144): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3144): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@379befc2 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743230.3144
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743230.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743230.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743230.3144","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743230.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743230.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743230.3144, mode: WIFI
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
I/jxcore-log( 3144): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e3d460e added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743264.3144
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743264.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743264.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743264.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743264.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743264.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743264.3144, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3144): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
,I/jxcore-log( 3144): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3144): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@268bb51a added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743295.3144
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743295.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): start: OK
I/io.jxcore.node.ConnectionHelper( 3144): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743295.3144, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Waiting for incoming connections...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3144): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743295.3144","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454416743295.3144","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454416743295.3144","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454416743295.3144, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3144): start: OK
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): startWifiPeerDiscovery: Wi-Fi Direct OK
I/jxcore-log( 3144): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3144): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3144): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): shutdown
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3144): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3144): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3144): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3144): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3144): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3144): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3144): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3144): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3144): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3144): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): # setup
I/jxcore-log( 3144): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3144): start: Cannot start, because not initialized
,W/bt-smp  ( 2078): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2078): Plain text(LSB ~ MSB) = d7 3c 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2078): Encrypted text(LSB ~ MSB) = 88 ea 06 df 3d 63 83 a3 fe 0b 68 50 12 8d 45 6a 
,W/bt-btm  ( 2078): Stopping oneshot timer
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3529 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3529): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3529):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3529):   adb logcat -s GAv4
,W/GAv4    ( 3529): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3529): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3529): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2637:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2637/cgroup.procs: No such file or directory
,I/PerfProfileCollectorService( 1625): Turn off PerfProfile Collection
,D/PerfProfileCollectorService( 1625): removeStateFiles() called
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3590): 
D/AndroidRuntime( 3590): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3590): CheckJNI is OFF
D/AndroidRuntime( 3590): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3144:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  759): Client connection lost with reason: 4
I/WindowState(  759): WIN DEATH: Window{1137fdb7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  759): Skipping PackageSetting{15569e98 com.example.hello/10278} due to missing metadata
I/ActivityManager(  759):   Force finishing activity ActivityRecord{1f190a73 u0 com.test.thalitest/.MainActivity t216}
W/ActivityManager(  759): Spurious death for ProcessRecord{2daae2fc 3144:com.test.thalitest/u0a270}, curProc for 3144: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1308): Explicit concurrent mark sweep GC freed 3988(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.391ms total 17.779ms
I/Keyboard.Facilitator( 1087): resetDictionaries() : en_US
W/GeofencerStateMachine( 1606): Ignoring removeGeofence because network location is disabled.
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1087): run()
I/Decoder ( 1087): createOrResetDecoder
I/art     ( 1399): Explicit concurrent mark sweep GC freed 9646(678KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 384us total 60.563ms
I/art     (  759): Explicit concurrent mark sweep GC freed 16664(1128KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.496ms total 82.103ms
D/VoicemailCleanupService( 1371): Cleaning up data for package: com.test.thalitest
I/art     (  759): WaitForGcToComplete blocked for 31.210ms for cause Explicit
I/art     ( 1625): Explicit concurrent mark sweep GC freed 9386(475KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 1.045ms total 94.291ms
I/UpdateIcingCorporaServi( 1399): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1308): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2abc952d new=com.google.android.velvet.VelvetApplication@2abc952d
I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  942): Initialized EGL, version 1.4
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3631 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/OpenGLRenderer(  942): Enabling debug mode 0
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  759): removeObsoleteFile: deleting file=216_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): run()
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3144 uid 10270
I/Keyboard.Facilitator( 1087): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1087): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1087): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1087): run()
I/StatsUtilsManager( 1087): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1087): shouldRecordStats() = Too Soon
I/art     (  759): Explicit concurrent mark sweep GC freed 4655(259KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.076ms total 158.801ms
I/UpdateIcingCorporaServi( 1399): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
W/ContextImpl( 3631): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1625): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1625): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1606): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1606): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator( 1087): onFinishInput()
W/IInputConnectionWrapper( 1308): showStatusIcon on inactive InputConnection
I/LocationSettingsChecker( 1625): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1625): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 3590): Shutting down VM
I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3664 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/BaseAppContext( 1625): Using Auth Proxy for data requests.
W/BaseAppContext( 1625): Using Auth Proxy for data requests.
I/GMPM-SVC( 1625): App measurement is starting up, version: 8489
I/GMPM-SVC( 1625): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 1625): doRemovePackageData com.test.thalitest
I/ActivityManager(  759): Killing 2514:com.google.android.gm/u0a70 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2514/cgroup.procs: No such file or directory
I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3692 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/Launcher( 1308): Deferring update until onResume
I/ActivityManager(  759): Killing 1992:com.google.android.calendar/u0a31 (adj 15): empty #17
W/ResourcesManager( 1308): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1308): Deferring update until onResume
W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_1992/cgroup.procs: No such file or directory
D/ExternalStorage( 3692): After updating volumes, found 1 active roots

```
