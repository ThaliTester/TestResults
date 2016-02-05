#### Test 58497659c9ea290_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3071): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3071):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3071):   adb logcat -s GAv4
W/GAv4    ( 3071): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3071): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3071): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
--------- beginning of system
I/PowerManagerService(  759): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  759): Sleeping (uid 1000)...
W/AnalyticsTrackerProxyImpl( 3071): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
I/MicrophoneInputStream( 1412): mic_close gfk@56b3b7f
D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
E/native  (  759): do suspend false
D/PermissionCache(  172): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (135 us)
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1412): Hotword detection finished
I/HotwordRecognitionRnr( 1412): Stopping hotword detection.
D/Finsky  ( 2664): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2413:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
D/SurfaceFlinger(  172): shader cache generated - 24 shaders in 141.716263 ms
V/JNIHelp ( 3071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3071): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3071): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2413/cgroup.procs: No such file or directory
V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1105): onFinishInput()
E/native  (  759): do suspend true
I/Icing   ( 1690): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1690): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1690): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1690): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
E/Sensors (  190): sns_acm_mr.c(432):Transport error -45
I/DisplayManagerService(  759): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  759): Display changed displayId=0
D/SurfaceFlinger(  172): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  172): hwc_blank: Blanking display: 0
D/qdhwcomposer(  172): hwc_blank: Done blanking display: 0
D/SurfaceControl(  759): Excessive delay in setPowerMode(): 298ms
,D/AndroidRuntime( 3155): 
D/AndroidRuntime( 3155): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3155): CheckJNI is OFF
D/AndroidRuntime( 3155): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3175 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3155): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 418us total 21.762ms
V/ActivityManager(  759): Display changed displayId=0
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.450ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.262ms
I/WebViewFactory( 3175): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3175): Time to load native libraries: 2 ms (timestamps 7621-7623)
I/LibraryLoader( 3175): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3175): Binding Chromium to main looper Looper (main, tid 1) {92cb3ed}
I/LibraryLoader( 3175): Expected native library version number "",actual native library version number ""
I/chromium( 3175): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3175): Initializing chromium process, singleProcess=true
W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3175): ApplicationContext is null in ApplicationStatus
W/chromium( 3175): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3175): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16d06743:true
,W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3175): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3175): CordovaWebView is running on device made by: LGE
,W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3175): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3175): Render dirty regions requested: true
,D/Atlas   ( 3175): Validating map...
,W/chromium( 3175): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3175): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3175): Enabling debug mode 0
,I/Keyboard.Facilitator( 1105): onFinishInput()
,W/BindingManager( 3175): Cannot call determinedVisibility() - never saw a connection for the pid: 3175
,W/IInputConnectionWrapper( 3175): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +375ms (total +45s825ms)
,D/JsMessageQueue( 3175): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3175): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3175): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  759): Killing 2490:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2490/cgroup.procs: No such file or directory
,W/jxcore-log( 3175): Initializing JXcore engine
W/jxcore-log( 3175): JXcore engine is ready
,W/Thread-297( 3225): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9449]" dev="sockfs" ino=9449 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3225): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-297( 3225): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6665]" dev="sockfs" ino=6665 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-297( 3225): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19184]" dev="sockfs" ino=19184 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3175): Starting JXcore engine
,W/jxcore-log( 3175): Platform android
W/jxcore-log( 3175): 
,W/jxcore-log( 3175): Process ARCH arm
W/jxcore-log( 3175): 
,I/ActivityManager(  759): Killing 2090:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/jxcore-log( 3175): JXcore Cordova bridge is ready!
I/jxcore-log( 3175): 
,W/jxcore-log( 3175): JXcore engine is started
,W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2090/cgroup.procs: No such file or directory
,I/jxcore-log( 3175): Toggling radios to true
I/jxcore-log( 3175): 
,D/BluetoothAdapter( 3175): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3175, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3175): Radios toggled
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): My device name is: LGE-Nexus 5
I/jxcore-log( 3175): 
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1660): Read error: ssl=0xb3ca3200: I/O error during system call, Connection timed out
V/NativeCrypto( 1660): SSL shutdown failed: ssl=0xb3ca3200: I/O error during system call, Broken pipe
D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityManager.CallbackHandler( 1690): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
,D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1281): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3272): version 5.5.6 starting
E/dhcpcd  ( 3272): get_duid: Read-only file system
,I/dhcpcd  ( 3272): wlan0: rebinding lease of 192.168.1.114
,D/Finsky  ( 2664): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2664): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3272): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/ActivityManager(  759): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3282 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/dhcpcd  ( 3272): wlan0: leased 192.168.1.114 for 86400 seconds
,W/ResourcesManager( 3282): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3282): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Finsky  ( 2664): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 3282): VM with version 2.1.0 has multidex support
I/MultiDex( 3282): install
I/MultiDex( 3282): VM has multidex support, MultiDex support library is disabled.
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/JNIHelp ( 3282): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2783): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1690): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1690): onCreate
,D/SystemUpdateService( 1690): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1690): active receiver: enabled
,I/SystemUpdateService( 1690): showing system update notification
,I/iu.Environment( 1690): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
E/GpsLocationProvider(  759): No APN found to select.
,I/iu.UploadsManager( 1690): num queued entries: 0
I/iu.UploadsManager( 1690): num updated entries: 0
I/iu.SyncManager( 1690): NEXT; no task
,I/Babel   ( 1934): connection state changed from CONNECTED to DISCONNECTED
,W/ActivityThread( 3282): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3282): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4d538e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3282): Installed default security provider GmsCore_OpenSSL
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1690): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3339 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,D/SystemUpdateService( 1690): onDestroy
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1690): CM callback handler got msg 524290
,D/ChimeraCfgMgr( 3282): Reading stored module config
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 3282): Install completed successfully. count=14 extracted=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 23:27:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454714835437], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454714835411]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1690): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1281): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CAR.SERVICE( 3282): Connecting to CarCallService...
,I/art     (  759): Explicit concurrent mark sweep GC freed 44486(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.115ms total 60.519ms
,I/art     ( 3282): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3282): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3282): com.google.android.projection.gearhead isn't installed.
,I/GAv4    ( 3339): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3339):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3339):   adb logcat -s GAv4
D/CAR.TEL.Service( 3282): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3282): Creating a new PhoneAdapter instance
W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3282): setListener: com.google.android.gms.car.dn@343ea0e2
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3282): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3282): Starting CarCallService with initial phone null
,W/GAv4    ( 3339): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3339): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3339): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/CAR.SERVICE( 3282): Package validated; name: com.android.vending
,V/Finsky  ( 2664): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3339): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3339): Time to load native libraries: 1 ms (timestamps 3343-3344)
I/LibraryLoader( 3339): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3339): Binding Chromium to main looper Looper (main, tid 1) {27c829d7}
I/LibraryLoader( 3339): Expected native library version number "",actual native library version number ""
I/chromium( 3339): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3339): Initializing chromium process, singleProcess=true
W/art     ( 3339): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3339): ApplicationContext is null in ApplicationStatus
,W/chromium( 3339): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3339): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3339): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3339): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3339): Requires BLUETOOTH permission
,I/NSApplication( 3339): Starting up...
,V/MusicLeanback( 2783): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1690): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1690): onCreate
,D/SystemUpdateService( 1690): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1690): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1690): num queued entries: 0
I/iu.UploadsManager( 1690): num updated entries: 0
,I/iu.SyncManager( 1690): NEXT; no task
I/SystemUpdateService( 1690): active receiver: enabled
,I/SystemUpdateService( 1690): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1690): retry (wakeup: false) in 3599973 ms
,D/WearableService( 1660): callingUid 10008, callindPid: 1660
,E/MDM     ( 1660): [234] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1690): Restart initialization of location
,D/SystemUpdateService( 1690): onDestroy
,I/Babel   ( 1934): connection state changed from DISCONNECTED to CONNECTED
,D/AuthorizationBluetoothService( 1660): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1660): No location to return for getLastLocation()
W/FusedLocationProvider( 1660): location=null
,W/ResourcesManager( 2664): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2664): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3175): 
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 2664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2664): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1660): client connected with version: 8296000
,D/Finsky  ( 2664): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2664): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2664): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  759): Killing 2592:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  759): Killing 2636:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3175): 
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2592/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2636/cgroup.procs: No such file or directory
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3175): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2783): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2783): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1690): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1690): onCreate
,D/SystemUpdateService( 1690): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1690): active receiver: enabled
,I/SystemUpdateService( 1690): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1690): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1690): onDestroy
,D/CAR.SERVICE( 3282): mConnectedToCar = false, abort
,E/ActivityThread( 3282): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@19274a8a that was originally bound here
E/ActivityThread( 3282): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@19274a8a that was originally bound here
E/ActivityThread( 3282): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3282): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3282): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3282): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3282): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3282): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3282): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3282): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3282): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3282): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3282): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3282): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3282): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3282): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3282): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3282): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3282): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3282): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3282): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3282): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3282): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3282): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3282): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3282): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@362e95ad that was originally bound here
E/ActivityThread( 3282): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@362e95ad that was originally bound here
E/ActivityThread( 3282): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3282): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3282): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3282): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3282): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3282): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3282): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3282): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3282): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3282): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3282): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3282): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3282): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3282): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3282): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3282): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3282): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3282): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3282): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3282): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3282): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3282): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@28dd2215
,I/jxcore-log( 3175): Test app app.js loaded
I/jxcore-log( 3175): 
,I/chromium( 3175): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3175): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3736948d added. We now have 1 listener(s)
,I/jxcore-log( 3175): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): TAP version 13
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 1 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 2 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 3 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 4 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 5 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 6 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 7 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 8 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 9 should throw
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 10 should throw
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons no beacons returns null
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 11 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 12 should throw
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 13 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 14 (unnamed assert)
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 15 should be equal
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 16 (unnamed assert)
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 17 (unnamed assert)
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # setup
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): ok 18 (unnamed assert)
I/jxcore-log( 3175): 
,I/jxcore-log( 3175): # teardown
I/jxcore-log( 3175): 
,D/Finsky  ( 2664): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2664): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1660): Vacuum at: now=1454714866163 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1105): run()
I/Keyboard.Facilitator( 1105): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1660): disconnect managed GoogleApiClient
,I/EventLogService( 1690): Aggregate from 1454713140076 (log), 1454713140076 (data)
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3521 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3521): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3521):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3521):   adb logcat -s GAv4
,W/GAv4    ( 3521): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3521): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3521): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2763:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2763/cgroup.procs: No such file or directory
,I/jxcore-log( 3175): --= Surplus to requirements =--
I/jxcore-log( 3175): 
I/jxcore-log( 3175): ****TEST TOOK:  ms ****
I/jxcore-log( 3175): 
I/jxcore-log( 3175): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3175): 
,D/AndroidRuntime( 3560): 
D/AndroidRuntime( 3560): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3560): CheckJNI is OFF
,D/AndroidRuntime( 3560): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3175:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  759): WIN DEATH: Window{1a3feaf0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{6c7b9b1 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{27db9bc u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  759): Spurious death for ProcessRecord{166d53fc 3175:com.test.thalitest/u0a270}, curProc for 3175: null
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1315): Explicit concurrent mark sweep GC freed 7291(548KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 410us total 16.656ms
,I/art     ( 1412): Explicit concurrent mark sweep GC freed 6133(484KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 442us total 40.384ms
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 5454(335KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 453us total 52.765ms
,W/GeofencerStateMachine( 1660): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1105): resetDictionaries() : en_US
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,D/VoicemailCleanupService( 1384): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1105): run()
,I/art     (  759): Explicit concurrent mark sweep GC freed 33735(1773KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.829ms total 81.795ms
,I/art     (  759): WaitForGcToComplete blocked for 15.016ms for cause Explicit
,I/Decoder ( 1105): createOrResetDecoder
,I/LibraryLoader( 1446): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,W/Launcher( 1315): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1d290222 new=com.google.android.velvet.VelvetApplication@1d290222
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3601 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1412): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/LibraryLoader( 1446): Time to load native libraries: 80 ms (timestamps 4886-4966)
I/LibraryLoader( 1446): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1446): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1446): Attempt to remove local handle scope entry from IRT, ignoring
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
W/art     ( 1446): Attempt to remove local handle scope entry from IRT, ignoring
,D/TaskPersister(  759): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1105): run()
,I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,D/OpenGLRenderer(  942): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1105): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/art     (  759): Explicit concurrent mark sweep GC freed 6262(356KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.769ms total 147.037ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Loading LM = user
W/art     (  942): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1105): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1105): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1105): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1105): run()
I/StatsUtilsManager( 1105): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1105): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@115875f9 (uid=10034 pid=942)
,W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1690): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1690): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1690): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1690): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1412): UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
D/ChimeraCfgMgr( 1690): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1690): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1660): Invalid parameter app
I/ActivityManager(  759): Killing 2742:com.android.settings/1000 (adj 15): empty #17
,E/NetworkScheduler.SchedulerReceiver( 1660): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3175 uid 10270
I/Keyboard.Facilitator( 1105): onFinishInput()
,D/WifiService(  759): Client connection lost with reason: 4
,D/AndroidRuntime( 3560): Shutting down VM
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2742/cgroup.procs: No such file or directory
,I/Launcher( 1315): Deferring update until onResume
,I/LocationSettingsChecker( 1690): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1315): Deferring update until onResume
,D/gH_CompatibleDatabase( 1690): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1690): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1690): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1690): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1690): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1690): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1690): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1690): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1690): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3641 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1690): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1690): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1690): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1690): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1690): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1690): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1690): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1690): Using Auth Proxy for data requests.
,I/Icing   ( 1690): doRemovePackageData com.test.thalitest
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3665 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2610:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2610/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 2026:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2026/cgroup.procs: No such file or directory
,D/ExternalStorage( 3665): After updating volumes, found 1 active roots
,W/ResourcesManager( 3071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3641): Update found 7 roots in 260ms

```
