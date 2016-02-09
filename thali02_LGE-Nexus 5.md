#### Test 58380500306a2c5_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1696): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1696): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3088): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3088):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3088):   adb logcat -s GAv4
W/GAv4    ( 3088): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3088): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3088): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3088): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2654): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3088): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  764): Killing 2383:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/System  ( 3088): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3088): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2383/cgroup.procs: No such file or directory
V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1696): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1696): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1696): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1696): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3153): 
D/AndroidRuntime( 3153): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3153): CheckJNI is OFF
D/AndroidRuntime( 3153): Calling main entry com.android.commands.am.Am
I/ActivityManager(  764): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3153): Shutting down VM
I/ActivityManager(  764): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3174 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MicrophoneInputStream( 1376): mic_close gfk@c3813df
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1376): Hotword detection finished
I/HotwordRecognitionRnr( 1376): Stopping hotword detection.
I/WebViewFactory( 3174): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3174): Time to load native libraries: 2 ms (timestamps 4468-4470)
I/LibraryLoader( 3174): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3174): Binding Chromium to main looper Looper (main, tid 1) {31506e68}
I/LibraryLoader( 3174): Expected native library version number "",actual native library version number ""
,I/chromium( 3174): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3174): Initializing chromium process, singleProcess=true
W/art     ( 3174): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3174): ApplicationContext is null in ApplicationStatus
,W/chromium( 3174): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3174): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  764): Message: 20
D/BluetoothManagerService(  764): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@332c0f70:true
,W/art     ( 3174): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3174): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3174): CordovaWebView is running on device made by: LGE
,W/art     ( 3174): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3174): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3174): Render dirty regions requested: true
,D/Atlas   ( 3174): Validating map...
,W/chromium( 3174): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3174): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3174): Enabling debug mode 0
,I/ActivityManager(  764): Displayed com.test.thalitest/.MainActivity: +466ms (total +42s686ms)
,I/Keyboard.Facilitator( 1114): onFinishInput()
,W/BindingManager( 3174): Cannot call determinedVisibility() - never saw a connection for the pid: 3174
,D/JsMessageQueue( 3174): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3174): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3174): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/PowerManagerService(  764): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  764): Sleeping (uid 1000)...
,I/Adreno-EGL(  764): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  172): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (192 us)
,D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  764): do suspend false
,D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
,I/Keyboard.Facilitator( 1114): onFinishInput()
,E/native  (  764): do suspend true
,I/ActivityManager(  764): Killing 2478:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10080/pid_2478/cgroup.procs: No such file or directory
,W/jxcore-log( 3174): Initializing JXcore engine
W/jxcore-log( 3174): JXcore engine is ready
,W/Thread-301( 3229): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8456]" dev="sockfs" ino=8456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3229): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3229): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9511]" dev="sockfs" ino=9511 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3229): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19836]" dev="sockfs" ino=19836 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3174): Starting JXcore engine
,E/Sensors (  190): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  764): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  172): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  172): hwc_blank: Blanking display: 0
V/ActivityManager(  764): Display changed displayId=0
,W/jxcore-log( 3174): Platform android
W/jxcore-log( 3174): 
,W/jxcore-log( 3174): Process ARCH arm
W/jxcore-log( 3174): 
,D/qdhwcomposer(  172): hwc_blank: Done blanking display: 0
D/SurfaceControl(  764): Excessive delay in setPowerMode(): 281ms
,I/jxcore-log( 3174): JXcore Cordova bridge is ready!
I/jxcore-log( 3174): 
W/jxcore-log( 3174): JXcore engine is started
,I/jxcore-log( 3174): Toggling radios to true
I/jxcore-log( 3174): 
,D/BluetoothAdapter( 3174): enable(): BT is already enabled..!
,D/WifiService(  764): New client listening to asynchronous messages
D/WifiService(  764): setWifiEnabled: true pid=3174, uid=10270
E/WifiService(  764): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3174): Radios toggled
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): My device name is: LGE-Nexus 5
I/jxcore-log( 3174): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  764): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  764): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1662): Read error: ssl=0xb3e28e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1662): SSL shutdown failed: ssl=0xb3e28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  764): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  764): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  764): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  764): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  764): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  764): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Disconnected - quitting
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1696): CM callback handler got msg 524292
,D/ConnectivityService(  764): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1285): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  764): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  764): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  764): Start Dhcp Watchdog 2
,E/native  (  764): do suspend false
,E/WifiStateMachine(  764): scanCount==0 - aborting
,I/dhcpcd  ( 3300): version 5.5.6 starting
E/dhcpcd  ( 3300): get_duid: Read-only file system
,I/dhcpcd  ( 3300): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3300): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3300): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  764): do suspend true
,E/WifiStateMachine(  764): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  764): Adding iface wlan0 to network 101
,E/ConnectivityService(  764): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  764): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  764): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  764): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1696): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:49:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455058182054], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455058182035]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Validated
D/ConnectivityService(  764): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1696): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1285): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  764): MasterInitialState.processMessage what=3
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2773): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2773): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  764): No APN found to select.
,I/SystemUpdateService( 1696): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1696): onCreate
,D/SystemUpdateService( 1696): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1696): active receiver: enabled
,I/SystemUpdateService( 1696): showing system update notification
,E/GpsLocationProvider(  764): No APN found to select.
,I/ValidateNoPeople(  764): skipping global notification
V/SystemUpdateService( 1696): retry (wakeup: false) in 3599971 ms
,I/ActivityManager(  764): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3361 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1696): onDestroy
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1696): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,I/GAv4    ( 3361): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3361):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3361):   adb logcat -s GAv4
,I/ActivityManager(  764): Killing 2624:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/ActivityManager(  764): Killing 2113:com.google.android.deskclock/u0a38 (adj 15): empty #18
,W/libprocessgroup(  764): failed to open /acct/uid_10069/pid_2624/cgroup.procs: No such file or directory
,W/libprocessgroup(  764): failed to open /acct/uid_10038/pid_2113/cgroup.procs: No such file or directory
,W/GAv4    ( 3361): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3361): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3361): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  764): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3361): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3361): Time to load native libraries: 2 ms (timestamps 648-650)
I/LibraryLoader( 3361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3361): Binding Chromium to main looper Looper (main, tid 1) {26eb4e1a}
,I/LibraryLoader( 3361): Expected native library version number "",actual native library version number ""
I/chromium( 3361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3361): Initializing chromium process, singleProcess=true
W/art     ( 3361): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3361): ApplicationContext is null in ApplicationStatus
,W/chromium( 3361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3361): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3361): Starting up...
,W/AudioManagerAndroid( 3361): Requires BLUETOOTH permission
,I/ActivityManager(  764): Killing 2578:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3174): 
,W/libprocessgroup(  764): failed to open /acct/uid_10045/pid_2578/cgroup.procs: No such file or directory
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1696): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1696): onCreate
,D/SystemUpdateService( 1696): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1696): active receiver: enabled
I/SystemUpdateService( 1696): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1696): retry (wakeup: false) in 3599951 ms
D/SystemUpdateService( 1696): onDestroy
,I/art     (  764): Explicit concurrent mark sweep GC freed 52698(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 936us total 60.590ms
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3174): 
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2773): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1696): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1696): onCreate
,D/SystemUpdateService( 1696): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1696): active receiver: enabled
I/SystemUpdateService( 1696): showing system update notification
,E/GpsLocationProvider(  764): No APN found to select.
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1696): retry (wakeup: false) in 3599986 ms
D/SystemUpdateService( 1696): onDestroy
,D/Finsky  ( 2654): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1662): Explicit concurrent mark sweep GC freed 33367(2MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 21MB/35MB, paused 609us total 33.950ms
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2654): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2654): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2654): untagSocket(37) failed with errno -22
,D/Finsky  ( 2654): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ProcessCpuTracker(  764): Skipping unknown process pid 3494
W/ProcessCpuTracker(  764): Skipping unknown process pid 3503
W/ProcessCpuTracker(  764): Skipping unknown process pid 3504
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  764): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3506 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3506): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3506): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3506): VM with version 2.1.0 has multidex support
I/MultiDex( 3506): install
I/MultiDex( 3506): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3506): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3506): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3506): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@390766a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3506): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 2654): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2654): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2654): untagSocket(37) failed with errno -22
,D/WearableService( 1662): callingUid 10008, callindPid: 1662
,E/MDM     ( 1662): [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1696): Restart initialization of location
,D/AuthorizationBluetoothService( 1662): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3506): Reading stored module config
,D/ChimeraCfgMgr( 3506): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1662): No location to return for getLastLocation()
W/FusedLocationProvider( 1662): location=null
,D/CAR.SERVICE( 3506): Connecting to CarCallService...
,D/NativeLibraryUtils( 3506): Install completed successfully. count=14 extracted=0
,I/art     ( 3506): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3506): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3506): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3506): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3506): Creating a new PhoneAdapter instance
,W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3506): setListener: com.google.android.gms.car.dn@1b6f7841
W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3506): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3506): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3506): Package validated; name: com.android.vending
,V/Finsky  ( 2654): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2654): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2654): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2654): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2654): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2654): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2654): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1662): client connected with version: 8296000
,D/Finsky  ( 2654): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2654): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2654): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3174): 
,I/jxcore-log( 3174): Test app app.js loaded
I/jxcore-log( 3174): 
,I/chromium( 3174): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3174): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10d698a0 added. We now have 1 listener(s)
,I/jxcore-log( 3174): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3174): 
,I/ActivityManager(  764): Killing 2752:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10003/pid_2752/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 3506): mConnectedToCar = false, abort
,E/ActivityThread( 3506): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2b5fb109 that was originally bound here
E/ActivityThread( 3506): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2b5fb109 that was originally bound here
E/ActivityThread( 3506): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3506): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3506): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3506): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3506): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3506): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3506): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3506): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3506): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3506): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3506): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3506): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3506): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3506): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3506): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3506): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3506): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3506): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3506): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3506): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37cec328 that was originally bound here
E/ActivityThread( 3506): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37cec328 that was originally bound here
E/ActivityThread( 3506): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3506): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3506): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3506): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3506): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3506): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3506): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3506): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3506): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3506): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3506): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3506): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3506): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3506): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3506): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3506): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3506): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3506): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  764): Unbind failed: could not find connection for android.os.BinderProxy@36f8ce5f
,D/Finsky  ( 2654): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2654): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1662): Vacuum at: now=1455058217759 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1114): run()
I/Keyboard.Facilitator( 1114): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1662): disconnect managed GoogleApiClient
,I/jxcore-log( 3174): --= Surplus to requirements =--
I/jxcore-log( 3174): 
I/jxcore-log( 3174): ****TEST TOOK:  ms ****
I/jxcore-log( 3174): 
I/jxcore-log( 3174): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3174): 
,D/AndroidRuntime( 3651): 
D/AndroidRuntime( 3651): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3651): CheckJNI is OFF
,D/AndroidRuntime( 3651): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  764): Killing 3174:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  764): WIN DEATH: Window{11da34a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  764): Client connection lost with reason: 4
,W/PackageSettings(  764): Skipping PackageSetting{3132227c com.example.hello/10278} due to missing metadata
,I/ActivityManager(  764):   Force finishing activity ActivityRecord{1dc40d4 u0 com.test.thalitest/.MainActivity t216}
,V/ActivityManager(  764): Display changed displayId=0
,W/ActivityManager(  764): Spurious death for ProcessRecord{2b2bca2d 3174:com.test.thalitest/u0a270}, curProc for 3174: null
,I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  764):   Force finishing activity ActivityRecord{1dc40d4 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  764): Duplicate finish request for ActivityRecord{1dc40d4 u0 com.test.thalitest/.MainActivity t216 f}
,W/GeofencerStateMachine( 1662): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  764): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 10103(693KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 350us total 70.457ms
,I/art     ( 1306): Explicit concurrent mark sweep GC freed 7260(546KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 223us total 42.349ms
,I/Keyboard.Facilitator( 1114): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1114): run()
,I/art     (  764): Explicit concurrent mark sweep GC freed 32703(1706KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.160ms total 91.637ms
,I/art     (  764): WaitForGcToComplete blocked for 10.758ms for cause Explicit
,I/art     ( 1696): Explicit concurrent mark sweep GC freed 4319(222KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 479us total 107.441ms
,I/Decoder ( 1114): createOrResetDecoder
I/LibraryLoader( 1456): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,D/VoicemailCleanupService( 1386): Cleaning up data for package: com.test.thalitest
,W/Launcher( 1306): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d52e281 new=com.google.android.velvet.VelvetApplication@d52e281
,I/UpdateIcingCorporaServi( 1376): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/OpenGLRenderer(  950): Initialized EGL, version 1.4
D/OpenGLRenderer(  950): Enabling debug mode 0
,D/BackupManagerService(  764): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  764): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): run()
,I/ActivityManager(  764): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3691 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1456): Time to load native libraries: 85 ms (timestamps 5611-5696)
I/LibraryLoader( 1456): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1456): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1456): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1456): Attempt to remove local handle scope entry from IRT, ignoring
,D/TaskPersister(  764): removeObsoleteFile: deleting file=216_task.xml
,W/art     (  950): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,W/InputMethodManagerService(  764): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@17c3210f (uid=10034 pid=950)
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1114): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1114): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1114): run()
I/StatsUtilsManager( 1114): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1114): shouldRecordStats() = Too Soon
,W/ContextImpl( 3691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1376): UpdateCorporaTask done [took 135 ms] updated apps [took 134 ms] 
,I/art     (  764): Explicit concurrent mark sweep GC freed 8207(456KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.807ms total 199.616ms
,D/ChimeraCfgMgr( 1696): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1696): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1696): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1696): Module APK com.google.android.play.games already loaded
,W/InputMethodManagerService(  764): Got RemoteException sending setActive(false) notification to pid 3174 uid 10270
D/PackageBroadcastService( 1696): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1696): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator( 1114): onFinishInput()
,E/NetworkScheduler.SchedulerReceiver( 1662): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1662): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  764): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3727 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1306): Deferring update until onResume
,D/AndroidRuntime( 3651): Shutting down VM
,I/LocationSettingsChecker( 1696): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1696): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1696): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
W/ResourcesManager( 1306): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/gH_MetricsDatabase( 1696): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1696): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1696): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1696): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1696): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1696): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1696): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/ResourcesManager( 1306): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1696): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1696): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1696): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1696): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 1696): App measurement is starting up, version: 8489
I/GMPM-SVC( 1696): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Launcher( 1306): Deferring update until onResume
,W/BaseAppContext( 1696): Using Auth Proxy for data requests.
,W/BaseAppContext( 1696): Using Auth Proxy for data requests.
,I/Icing   ( 1696): doRemovePackageData com.test.thalitest
,I/ActivityManager(  764): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3756 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  764): Killing 2731:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  764): Client connection lost with reason: 4
,W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2731/cgroup.procs: No such file or directory
,I/ActivityManager(  764): Killing 2598:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10070/pid_2598/cgroup.procs: No such file or directory
,D/ExternalStorage( 3756): After updating volumes, found 1 active roots
,W/ResourcesManager( 3088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3727): Update found 7 roots in 191ms
,D/Documents( 3727): Update found 7 roots in 95ms

```
