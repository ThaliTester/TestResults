#### Test 58135655c662d33_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1663): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1663): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3133): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3133):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3133):   adb logcat -s GAv4
W/GAv4    ( 3133): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3133): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3133): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3133): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2676): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2112:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3133): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3133): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3133): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2112/cgroup.procs: No such file or directory
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1663): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1663): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1663): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1663): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/Finsky  ( 2676): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1564): Explicit concurrent mark sweep GC freed 32159(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 21MB/35MB, paused 870us total 32.787ms
,D/AndroidRuntime( 3198): 
D/AndroidRuntime( 3198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3198): CheckJNI is OFF
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3198): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/qtaguid ( 2676): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2676): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2676): untagSocket(37) failed with errno -22
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3213 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 2676): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/AndroidRuntime( 3198): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  759): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3231 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/WebViewFactory( 3213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ResourcesManager( 3231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 3213): Time to load native libraries: 1 ms (timestamps 7877-7878)
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
I/MultiDex( 3231): VM with version 2.1.0 has multidex support
I/MultiDex( 3231): install
I/MultiDex( 3231): VM has multidex support, MultiDex support library is disabled.
,V/WebViewChromiumFactoryProvider( 3213): Binding Chromium to main looper Looper (main, tid 1) {2c399c52}
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
I/chromium( 3213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,V/JNIHelp ( 3231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/BrowserStartupController( 3213): Initializing chromium process, singleProcess=true
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3213): ApplicationContext is null in ApplicationStatus
,W/chromium( 3213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3213): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/ActivityThread( 3231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dfd9344: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3231): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1564): callingUid 10008, callindPid: 1564
,E/MDM     ( 1564): [222] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 3231): Reading stored module config
D/AuthorizationBluetoothService( 1564): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1663): Restart initialization of location
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2676): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2676): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2676): untagSocket(37) failed with errno -22
D/ChimeraCfgMgr( 3231): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1564): No location to return for getLastLocation()
W/FusedLocationProvider( 1564): location=null
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39454515:true
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3213): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3213): CordovaWebView is running on device made by: LGE
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3213): Render dirty regions requested: true
,D/CAR.SERVICE( 3231): Connecting to CarCallService...
,D/Atlas   ( 3213): Validating map...
,D/NativeLibraryUtils( 3231): Install completed successfully. count=14 extracted=0
,W/chromium( 3213): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     ( 3231): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3231): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/OpenGLRenderer( 3213): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3213): Enabling debug mode 0
,D/CAR.SERVICE( 3231): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3231): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3231): Creating a new PhoneAdapter instance
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3231): setListener: com.google.android.gms.car.dn@178bc2e3
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3231): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3231): Starting CarCallService with initial phone null
,W/BindingManager( 3213): Cannot call determinedVisibility() - never saw a connection for the pid: 3213
,W/IInputConnectionWrapper( 3213): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +451ms (total +46s471ms)
,D/JsMessageQueue( 3213): Set native->JS mode to OnlineEventsBridgeMode
,D/CAR.SERVICE( 3231): Package validated; name: com.android.vending
,V/Finsky  ( 2676): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/jxcore_app_log( 3213): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3213): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     (  759): Explicit concurrent mark sweep GC freed 15873(733KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.006ms total 76.124ms
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2676): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2676): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2676): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2676): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1564): client connected with version: 8296000
,D/Finsky  ( 2676): [271] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2676): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2676): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,W/jxcore-log( 3213): Initializing JXcore engine
W/jxcore-log( 3213): JXcore engine is ready
,I/ActivityManager(  759): Killing 2599:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/Thread-306( 3309): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8424]" dev="sockfs" ino=8424 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3309): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3309): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6677]" dev="sockfs" ino=6677 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3309): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20725]" dev="sockfs" ino=20725 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3213): Starting JXcore engine
,W/jxcore-log( 3213): Platform android
W/jxcore-log( 3213): 
W/jxcore-log( 3213): Process ARCH arm
W/jxcore-log( 3213): 
,I/ActivityManager(  759): Killing 2644:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2599/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2644/cgroup.procs: No such file or directory
,I/jxcore-log( 3213): JXcore Cordova bridge is ready!
I/jxcore-log( 3213): 
,W/jxcore-log( 3213): JXcore engine is started
,I/jxcore-log( 3213): Toggling radios to true
I/jxcore-log( 3213): 
,D/BluetoothAdapter( 3213): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3213, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3213): Radios toggled
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): My device name is: LGE-Nexus 5
I/jxcore-log( 3213): 
,I/wpa_supplicant( 1022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1564): Read error: ssl=0x9c141e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1564): SSL shutdown failed: ssl=0x9c141e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1022): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1663): CM callback handler got msg 524292
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1247): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1022): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1022): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1022): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1022): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3365): version 5.5.6 starting
E/dhcpcd  ( 3365): get_duid: Read-only file system
,I/dhcpcd  ( 3365): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3365): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3365): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2793): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1663): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1663): onCreate
,D/SystemUpdateService( 1663): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1663): active receiver: enabled
,I/iu.Environment( 1663): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1663): num queued entries: 0
I/iu.UploadsManager( 1663): num updated entries: 0
I/iu.SyncManager( 1663): NEXT; no task
,I/SystemUpdateService( 1663): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1663): retry (wakeup: false) in 3599949 ms
,I/Babel   ( 1942): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3406 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1663): onDestroy
,E/GpsLocationProvider(  759): No APN found to select.
,D/CAR.SERVICE( 3231): mConnectedToCar = false, abort
,E/GpsLocationProvider(  759): No APN found to select.
,E/ActivityThread( 3231): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2350916b that was originally bound here
E/ActivityThread( 3231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2350916b that was originally bound here
E/ActivityThread( 3231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3231): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3231): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3231): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3231): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3231): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3231): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3231): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3231): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3231): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3231): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3231): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3231): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3231): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@328ceb12 that was originally bound here
E/ActivityThread( 3231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@328ceb12 that was originally bound here
E/ActivityThread( 3231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3231): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3231): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3231): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3231): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3231): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3231): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3231): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3231): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3231): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3231): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3231): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3231): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3231): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@264cc38d
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  759):    accepting network in place of null
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1663): CM callback handler got msg 524290
,I/GAv4    ( 3406): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3406):   adb logcat -s GAv4
,W/GAv4    ( 3406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 18:12:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454523131414], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454523131394]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
,D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1247): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1663): CM callback handler got msg 524290
,I/WebViewFactory( 3406): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3406): Time to load native libraries: 2 ms (timestamps 3778-3780)
I/LibraryLoader( 3406): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3406): Binding Chromium to main looper Looper (main, tid 1) {e0e5574}
I/LibraryLoader( 3406): Expected native library version number "",actual native library version number ""
,I/chromium( 3406): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3406): Initializing chromium process, singleProcess=true
W/art     ( 3406): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3406): ApplicationContext is null in ApplicationStatus
,W/chromium( 3406): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3406): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3406): Starting up...
,W/AudioManagerAndroid( 3406): Requires BLUETOOTH permission
,I/ActivityManager(  759): Killing 2768:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2768/cgroup.procs: No such file or directory
,V/MusicLeanback( 2793): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1663): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1663): onCreate
D/SystemUpdateService( 1663): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1663): active receiver: enabled
,I/iu.Environment( 1663): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1663): num queued entries: 0
I/iu.UploadsManager( 1663): num updated entries: 0
,I/iu.SyncManager( 1663): NEXT; no task
,I/SystemUpdateService( 1663): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1663): retry (wakeup: false) in 3599928 ms
,D/SystemUpdateService( 1663): onDestroy
,I/Babel   ( 1942): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3213): 
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3213): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2793): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2793): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1663): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1663): onCreate
,D/SystemUpdateService( 1663): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1663): active receiver: enabled
I/SystemUpdateService( 1663): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1663): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1663): onDestroy
,I/jxcore-log( 3213): Test app app.js loaded
I/jxcore-log( 3213): 
,I/chromium( 3213): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@260b5c7f added. We now have 1 listener(s)
,I/jxcore-log( 3213): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3213): 
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2676): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2676): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1564): Vacuum at: now=1454523156236 tag=VacuumService
,I/PhenotypeConfigurator( 1564): Scheduling Phenotype for one-off execution 4042 seconds from now (1454523156611)
,D/GetConfigurationSnapshotOperation( 1564): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1564): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1564): disconnect managed GoogleApiClient
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3606 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3606): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3606):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3606):   adb logcat -s GAv4
,W/GAv4    ( 3606): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2750:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2750/cgroup.procs: No such file or directory
,I/jxcore-log( 3213): --= Surplus to requirements =--
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ****TEST TOOK:  ms ****
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3213): 
,D/AndroidRuntime( 3663): 
D/AndroidRuntime( 3663): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3663): CheckJNI is OFF
,D/AndroidRuntime( 3663): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  759): Killing 3213:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  759): WIN DEATH: Window{38bbf83d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{3ce585c6 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{2c168a40 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  759): Spurious death for ProcessRecord{6ccd38b 3213:com.test.thalitest/u0a270}, curProc for 3213: null
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1369): Explicit concurrent mark sweep GC freed 7658(636KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 343us total 20.183ms
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1564): Ignoring removeGeofence because network location is disabled.
,D/NetworkChangeNotifierAutoDetect(  945): Network connectivity changed, type is: 2
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 3910(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 471us total 52.689ms
,I/Keyboard.Facilitator( 1104): resetDictionaries() : en_US
,W/art     (  759): Suspending all threads took: 7.187ms
,I/art     (  759): Explicit concurrent mark sweep GC freed 56655(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 8.470ms total 75.792ms
,I/LibraryLoader( 1525): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/art     (  759): WaitForGcToComplete blocked for 80.025ms for cause Explicit
,I/Keyboard.Facilitator.DecoderInitializer( 1104): run()
D/VoicemailCleanupService( 2906): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1104): createOrResetDecoder
,W/Launcher( 1268): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b94bb23 new=com.google.android.velvet.VelvetApplication@1b94bb23
I/UpdateIcingCorporaServi( 1369): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/LibraryLoader( 1525): Time to load native libraries: 60 ms (timestamps 3516-3576)
I/LibraryLoader( 1525): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1525): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1525): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1525): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1663): Explicit concurrent mark sweep GC freed 4387(227KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/29MB, paused 467us total 185.082ms
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3701 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1564): onCreate
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  759): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  759): Explicit concurrent mark sweep GC freed 8457(474KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.756ms total 124.508ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1104): run()
,I/UpdateIcingCorporaServi( 1369): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
W/ContextImpl( 3701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1663): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1663): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1663): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1663): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1104): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/ChimeraCfgMgr( 1663): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1663): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = history
E/NetworkScheduler.SchedulerReceiver( 1564): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1564): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1104): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1104): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1104): run()
I/StatsUtilsManager( 1104): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1104): shouldRecordStats() = Too Soon
,I/LocationSettingsChecker( 1663): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1663): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/AndroidRuntime( 3663): Shutting down VM
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3743 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1268): Deferring update until onResume
,W/BaseAppContext( 1663): Using Auth Proxy for data requests.
,W/BaseAppContext( 1663): Using Auth Proxy for data requests.
,W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  759): Killing 2618:com.google.android.gm/u0a70 (adj 15): empty #17
W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1268): Deferring update until onResume
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2618/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1663): App measurement is starting up, version: 8489
I/GMPM-SVC( 1663): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3764 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/Icing   ( 1663): doRemovePackageData com.test.thalitest
,I/ActivityManager(  759): Killing 2045:com.google.android.calendar/u0a31 (adj 15): empty #17
,I/ActivityManager(  759): Killing 1471:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,D/ExternalStorage( 3764): After updating volumes, found 1 active roots
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2045/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1471/cgroup.procs: No such file or directory
,W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3743): Update found 7 roots in 233ms

```
