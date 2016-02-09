#### Test 58135655e9e7eb8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1619): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1619): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3025): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3025):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3025):   adb logcat -s GAv4
W/GAv4    ( 3025): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3025): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3025): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3025): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2595): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  755): Killing 2327:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  755): failed to open /acct/uid_1000/pid_2327/cgroup.procs: No such file or directory
V/JNIHelp ( 3025): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3025): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3025): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1619): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1619): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1619): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1619): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3086): 
D/AndroidRuntime( 3086): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3086): CheckJNI is OFF
D/AndroidRuntime( 3086): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3086): Shutting down VM
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3106 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 220us total 9.981ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 238us total 10.403ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 210us total 9.728ms
I/MicrophoneInputStream( 1401): mic_close gfk@f6c9b5b
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1401): Hotword detection finished
I/HotwordRecognitionRnr( 1401): Stopping hotword detection.
I/WebViewFactory( 3106): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3106): Time to load native libraries: 1 ms (timestamps 4908-4909)
I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3106): Binding Chromium to main looper Looper (main, tid 1) {2d41618a}
,I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
,I/chromium( 3106): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3106): Initializing chromium process, singleProcess=true
,W/art     ( 3106): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3106): ApplicationContext is null in ApplicationStatus
,W/chromium( 3106): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3106): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3106): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3106): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  755): Message: 20
,D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17ee374a:true
,W/art     ( 3106): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3106): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3106): CordovaWebView is running on device made by: LGE
,W/art     ( 3106): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3106): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3106): Render dirty regions requested: true
,D/Atlas   ( 3106): Validating map...
,W/chromium( 3106): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3106): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3106): Enabling debug mode 0
,I/Keyboard.Facilitator( 1072): onFinishInput()
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +607ms (total +43s128ms)
,W/BindingManager( 3106): Cannot call determinedVisibility() - never saw a connection for the pid: 3106
,D/JsMessageQueue( 3106): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3106): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3106): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/PowerManagerService(  755): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  755): Sleeping (uid 1000)...
,I/Adreno-EGL(  755): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
,D/PermissionCache(  171): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (124 us)
,E/native  (  755): do suspend false
,D/audio_hw_primary(  183): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  183): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1072): onFinishInput()
,E/native  (  755): do suspend true
,I/ActivityManager(  755): Killing 2410:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10080/pid_2410/cgroup.procs: No such file or directory
,E/Sensors (  191): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  755): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  171): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  171): hwc_blank: Blanking display: 0
V/ActivityManager(  755): Display changed displayId=0
,W/jxcore-log( 3106): Initializing JXcore engine
W/jxcore-log( 3106): JXcore engine is ready
,W/Thread-296( 3181): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8036]" dev="sockfs" ino=8036 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3181): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3181): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8579]" dev="sockfs" ino=8579 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3181): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18849]" dev="sockfs" ino=18849 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3106): Starting JXcore engine
,D/qdhwcomposer(  171): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  755): Excessive delay in setPowerMode(): 292ms
,W/jxcore-log( 3106): Platform android
W/jxcore-log( 3106): 
,W/jxcore-log( 3106): Process ARCH arm
W/jxcore-log( 3106): 
,I/jxcore-log( 3106): JXcore Cordova bridge is ready!
I/jxcore-log( 3106): 
W/jxcore-log( 3106): JXcore engine is started
,I/jxcore-log( 3106): Toggling radios to true
I/jxcore-log( 3106): 
,D/BluetoothAdapter( 3106): enable(): BT is already enabled..!
,D/WifiService(  755): New client listening to asynchronous messages
,D/WifiService(  755): setWifiEnabled: true pid=3106, uid=10270
E/WifiService(  755): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3106): Radios toggled
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): My device name is: LGE-Nexus 5
I/jxcore-log( 3106): 
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  755): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  755): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1594): Read error: ssl=0xaf25be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1594): SSL shutdown failed: ssl=0xaf25be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  755): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  755): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  755): do suspend true
,D/ConnectivityService(  755): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/Nat464Xlat(  755): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  755): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  755): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1234): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/ConnectivityService(  755): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Disconnected - quitting
,D/WifiNetworkAgent(  755): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  982): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  982): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  982): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  982): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  755): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  755): Start Dhcp Watchdog 2
,E/native  (  755): do suspend false
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/ActivityManager(  755): Killing 2066:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10038/pid_2066/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3239): version 5.5.6 starting
E/dhcpcd  ( 3239): get_duid: Read-only file system
,I/dhcpcd  ( 3239): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3239): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3239): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  755): do suspend true
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  755): Adding iface wlan0 to network 101
E/WifiStateMachine(  755): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  755): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  755): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  755): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  755): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  755): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  755): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:37:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455021456541], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455021456518]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Validated
D/ConnectivityService(  755): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1234): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2712): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 2712): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2712): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ActivityManager(  755): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3302 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  755): No APN found to select.
,E/GpsLocationProvider(  755): No APN found to select.
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599907 ms
,D/SystemUpdateService( 1619): onDestroy
,I/GAv4    ( 3302): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3302):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3302):   adb logcat -s GAv4
,W/GAv4    ( 3302): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3302): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524295
,W/GAv4    ( 3302): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3302): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3302): Time to load native libraries: 2 ms (timestamps 882-884)
I/LibraryLoader( 3302): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3302): Binding Chromium to main looper Looper (main, tid 1) {3ea351ec}
,I/LibraryLoader( 3302): Expected native library version number "",actual native library version number ""
I/chromium( 3302): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3302): Initializing chromium process, singleProcess=true
,W/art     ( 3302): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3302): ApplicationContext is null in ApplicationStatus
,W/chromium( 3302): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3302): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3302): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3302): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3302): Requires BLUETOOTH permission
,D/ConnectivityService(  755): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     (  755): Explicit concurrent mark sweep GC freed 50723(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.268ms total 56.764ms
I/NSApplication( 3302): Starting up...
,I/ActivityManager(  755): Killing 2563:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10069/pid_2563/cgroup.procs: No such file or directory
,V/MusicLeanback( 2712): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1619): onDestroy
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3106): 
,D/Finsky  ( 2595): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1594): Explicit concurrent mark sweep GC freed 33522(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 21MB/35MB, paused 766us total 31.261ms
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2595): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2595): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2595): untagSocket(37) failed with errno -22
,D/Finsky  ( 2595): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  755): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3383 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3383): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3383): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3383): VM with version 2.1.0 has multidex support
I/MultiDex( 3383): install
I/MultiDex( 3383): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3383): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3383): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3383): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ffe01bc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3383): Installed default security provider GmsCore_OpenSSL
D/WearableService( 1594): callingUid 10008, callindPid: 1594
E/MDM     ( 1594): [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 3383): Reading stored module config
I/qtaguid ( 2595): Failed write_ctrl(u 37) res=-1 errno=22
,I/qtaguid ( 2595): Untagging socket 37 failed errno=-22
D/AuthorizationBluetoothService( 1594): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/NetworkManagementSocketTagger( 2595): untagSocket(37) failed with errno -22
,D/LocationInitializer( 1619): Restart initialization of location
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1594): No location to return for getLastLocation()
W/FusedLocationProvider( 1594): location=null
D/ChimeraCfgMgr( 3383): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2712): type=WIFI subType= reason=null isConnected=true
,D/NativeLibraryUtils( 3383): Install completed successfully. count=14 extracted=0
,V/MusicLeanback( 2712): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  755): No APN found to select.
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599963 ms
,D/SystemUpdateService( 1619): onDestroy
,D/CAR.SERVICE( 3383): Connecting to CarCallService...
,I/art     ( 3383): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3383): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3383): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3383): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3383): Creating a new PhoneAdapter instance
W/ActivityManager(  755): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3383): setListener: com.google.android.gms.car.dn@20e263bb
W/ActivityManager(  755): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3383): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3383): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3383): Package validated; name: com.android.vending
,V/Finsky  ( 2595): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2595): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2595): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2595): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2595): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2595): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2595): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2595): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1594): client connected with version: 8296000
,D/Finsky  ( 2595): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2595): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2595): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  755): Killing 2509:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_2509/cgroup.procs: No such file or directory
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3106): 
,I/jxcore-log( 3106): Test app app.js loaded
I/jxcore-log( 3106): 
,I/chromium( 3106): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3106): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad7f79a added. We now have 1 listener(s)
,I/jxcore-log( 3106): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3106): 
,D/CAR.SERVICE( 3383): mConnectedToCar = false, abort
,E/ActivityThread( 3383): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@121259c0 that was originally bound here
E/ActivityThread( 3383): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@121259c0 that was originally bound here
E/ActivityThread( 3383): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3383): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3383): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3383): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3383): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3383): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3383): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3383): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3383): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3383): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3383): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3383): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3383): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3383): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3383): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3383): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3383): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3378a84a that was originally bound here
E/ActivityThread( 3383): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3378a84a that was originally bound here
E/ActivityThread( 3383): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3383): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3383): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3383): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3383): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3383): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3383): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3383): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3383): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3383): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3383): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3383): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3383): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3383): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3383): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3383): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3383): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  755): Unbind failed: could not find connection for android.os.BinderProxy@3eb6a40b
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2595): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2595): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1594): Vacuum at: now=1455021490145 tag=VacuumService
,I/art     (  755): Explicit concurrent mark sweep GC freed 31203(1374KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.669ms total 74.536ms
,I/PhenotypeConfigurator( 1594): Scheduling Phenotype for one-off execution 12452 seconds from now (1455021490594)
,D/GetConfigurationSnapshotOperation( 1594): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1594): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1594): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1594): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1072): run()
I/Keyboard.Facilitator( 1072): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1594): disconnect managed GoogleApiClient
,I/jxcore-log( 3106): --= Surplus to requirements =--
I/jxcore-log( 3106): 
I/jxcore-log( 3106): ****TEST TOOK:  ms ****
I/jxcore-log( 3106): 
I/jxcore-log( 3106): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3106): 
,D/AndroidRuntime( 3542): 
D/AndroidRuntime( 3542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3542): CheckJNI is OFF
,D/AndroidRuntime( 3542): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 3106:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  755): WIN DEATH: Window{342b06fa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  755): Client connection lost with reason: 4
,W/PackageSettings(  755): Skipping PackageSetting{f52677e com.example.hello/10278} due to missing metadata
,I/ActivityManager(  755):   Force finishing activity ActivityRecord{11485c8e u0 com.test.thalitest/.MainActivity t216}
,V/ActivityManager(  755): Display changed displayId=0
,W/ActivityManager(  755): Spurious death for ProcessRecord{317feb3a 3106:com.test.thalitest/u0a270}, curProc for 3106: null
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 7293(548KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 585us total 26.283ms
,W/GeofencerStateMachine( 1594): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1072): resetDictionaries() : en_US
,I/art     (  755): Explicit concurrent mark sweep GC freed 11804(781KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.613ms total 57.705ms
,I/Keyboard.Facilitator.DecoderInitializer( 1072): run()
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 9974(690KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 19MB/25MB, paused 381us total 76.568ms
,I/art     ( 1619): Explicit concurrent mark sweep GC freed 4288(220KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 548us total 88.548ms
,I/Decoder ( 1072): createOrResetDecoder
,D/VoicemailCleanupService( 1378): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): run()
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,I/UpdateIcingCorporaServi( 1401): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1259): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b4ac3fb new=com.google.android.velvet.VelvetApplication@2b4ac3fb
,D/OpenGLRenderer(  943): Enabling debug mode 0
,I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3581 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = contacts
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1072): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1072): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1072): run()
I/StatsUtilsManager( 1072): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1072): shouldRecordStats() = Too Soon
W/InputMethodManagerService(  755): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1736e4ee (uid=10034 pid=943)
,D/TaskPersister(  755): removeObsoleteFile: deleting file=216_task.xml
,W/ContextImpl( 3581): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1619): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1619): Clearing selected account for com.test.thalitest
,I/UpdateIcingCorporaServi( 1401): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
,D/ChimeraCfgMgr( 1619): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1619): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  755): Killing 2685:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/ChimeraCfgMgr( 1619): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1619): Module APK com.google.android.play.games already loaded
,W/InputMethodManagerService(  755): Got RemoteException sending setActive(false) notification to pid 3106 uid 10270
,I/Keyboard.Facilitator( 1072): onFinishInput()
,I/art     (  755): Explicit concurrent mark sweep GC freed 6873(355KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.306ms total 241.514ms
,D/AndroidRuntime( 3542): Shutting down VM
,E/NetworkScheduler.SchedulerReceiver( 1594): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1594): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2685/cgroup.procs: No such file or directory
,I/Launcher( 1259): Deferring update until onResume
,I/LocationSettingsChecker( 1619): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3623 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/FileUtils( 1619): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1619): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1619): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1619): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1619): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,--------- beginning of crash
E/AndroidRuntime( 1619): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1619): Process: com.google.android.gms, PID: 1619
E/AndroidRuntime( 1619): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1619): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1619): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1619): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1619): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1619): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1619): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1619): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1619): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1619): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1619): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1619): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Launcher( 1259): Deferring update until onResume
,I/Process ( 1619): Sending signal. PID: 1619 SIG: 9
,E/DropBoxManagerService(  755): Can't write: system_app_crash
E/DropBoxManagerService(  755): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  755): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  755): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  755): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  755): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  755): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  755): 	... 5 more
,D/ConnectivityService(  755): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@263fc080)
D/ConnectivityService(  755): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  755): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  755): Process com.google.android.gms (pid 1619) has died
,W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 31000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30999ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30999ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30999ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30999ms

```
