#### Test 5753124305d96c2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1627): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1627): Module APK com.google.android.play.games already loaded
I/GAv4    ( 2993): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2993):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2993):   adb logcat -s GAv4
W/GAv4    ( 2993): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2993): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2993): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2993): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 2993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2604): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  757): Killing 2322:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2993): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/PowerManagerService(  757): Going to sleep due to screen timeout (uid 1000)...
W/System  ( 2993): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2993): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2322/cgroup.procs: No such file or directory
I/PowerManagerService(  757): Sleeping (uid 1000)...
I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MicrophoneInputStream( 1420): mic_close gfk@2b245b5d
D/PermissionCache(  171): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (121 us)
E/native  (  757): do suspend false
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
I/HotwordRecognitionRnr( 1420): Hotword detection finished
I/HotwordRecognitionRnr( 1420): Stopping hotword detection.
D/SurfaceFlinger(  171): shader cache generated - 24 shaders in 136.062866 ms
D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1107): onFinishInput()
E/native  (  757): do suspend true
I/Icing   ( 1627): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1627): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1627): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1627): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
E/Sensors (  191): sns_acm_mr.c(432):Transport error -45
D/SurfaceFlinger(  171): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  171): hwc_blank: Blanking display: 0
I/DisplayManagerService(  757): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  757): Display changed displayId=0
,D/qdhwcomposer(  171): hwc_blank: Done blanking display: 0
D/SurfaceControl(  757): Excessive delay in setPowerMode(): 303ms
D/AndroidRuntime( 3067): 
D/AndroidRuntime( 3067): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3067): CheckJNI is OFF
D/AndroidRuntime( 3067): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3088 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3067): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.759ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.855ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.360ms
V/ActivityManager(  757): Display changed displayId=0
I/WebViewFactory( 3088): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3088): Time to load native libraries: 1 ms (timestamps 7112-7113)
I/LibraryLoader( 3088): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3088): Binding Chromium to main looper Looper (main, tid 1) {1e51cabb}
I/LibraryLoader( 3088): Expected native library version number "",actual native library version number ""
I/chromium( 3088): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3088): Initializing chromium process, singleProcess=true
W/art     ( 3088): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3088): ApplicationContext is null in ApplicationStatus
W/chromium( 3088): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3088): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3088): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3088): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1950ceb9:true
,W/art     ( 3088): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3088): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3088): CordovaWebView is running on device made by: LGE
,W/art     ( 3088): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3088): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3088): Render dirty regions requested: true
,D/Atlas   ( 3088): Validating map...
,W/chromium( 3088): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3088): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3088): Enabling debug mode 0
,I/Keyboard.Facilitator( 1107): onFinishInput()
,W/IInputConnectionWrapper( 3088): showStatusIcon on inactive InputConnection
,W/BindingManager( 3088): Cannot call determinedVisibility() - never saw a connection for the pid: 3088
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +487ms (total +45s440ms)
,D/JsMessageQueue( 3088): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3088): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3088): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  757): Killing 2409:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2409/cgroup.procs: No such file or directory
,W/jxcore-log( 3088): Initializing JXcore engine
W/jxcore-log( 3088): JXcore engine is ready
,W/Thread-297( 3156): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7991]" dev="sockfs" ino=7991 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3156): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-297( 3156): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8028]" dev="sockfs" ino=8028 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3156): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19699]" dev="sockfs" ino=19699 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3088): Starting JXcore engine
,W/jxcore-log( 3088): Platform android
W/jxcore-log( 3088): 
W/jxcore-log( 3088): Process ARCH arm
W/jxcore-log( 3088): 
,I/jxcore-log( 3088): JXcore Cordova bridge is ready!
I/jxcore-log( 3088): 
,W/jxcore-log( 3088): JXcore engine is started
,I/jxcore-log( 3088): Toggling radios to true
I/jxcore-log( 3088): 
,D/BluetoothAdapter( 3088): enable(): BT is already enabled..!
,D/WifiService(  757): New client listening to asynchronous messages
D/WifiService(  757): setWifiEnabled: true pid=3088, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3088): Radios toggled
I/jxcore-log( 3088): 
,I/jxcore-log( 3088): My device name is: LGE-Nexus 5
I/jxcore-log( 3088): 
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  757): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1601): Read error: ssl=0x9c070e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1601): SSL shutdown failed: ssl=0x9c070e00: I/O error during system call, Broken pipe
D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  757): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  894): CM callback handler got msg 524292
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524292
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1281): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  757): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  757): Killing 2554:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2554/cgroup.procs: No such file or directory
,I/wpa_supplicant(  983): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  983): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  983): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  757): Start Dhcp Watchdog 2
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/ActivityManager(  757): Killing 2510:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_2510/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3187): version 5.5.6 starting
E/dhcpcd  ( 3187): get_duid: Read-only file system
,I/dhcpcd  ( 3187): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3187): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3187): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/Tethering(  757): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2711): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1627): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1627): num queued entries: 0
,I/iu.UploadsManager( 1627): num updated entries: 0
I/iu.SyncManager( 1627): NEXT; no task
,E/GpsLocationProvider(  757): No APN found to select.
,I/Babel   ( 1905): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3227 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  757): do suspend true
,E/WifiStateMachine(  757): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 101
,I/SystemUpdateService( 1627): active receiver: enabled
,E/GpsLocationProvider(  757): No APN found to select.
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  757): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SystemUpdateService( 1627): showing system update notification
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  894): CM callback handler got msg 524290
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1627): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 14:15:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454422519937], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454422519921]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
,D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  894): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1281): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524290
,I/GAv4    ( 3227): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3227):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3227):   adb logcat -s GAv4
,W/GAv4    ( 3227): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3227): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3227): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3227): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3227): Time to load native libraries: 1 ms (timestamps 2824-2825)
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3227): Binding Chromium to main looper Looper (main, tid 1) {b713275}
,I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
I/chromium( 3227): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3227): Initializing chromium process, singleProcess=true
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3227): ApplicationContext is null in ApplicationStatus
,W/chromium( 3227): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3227): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3227): Requires BLUETOOTH permission
,I/NSApplication( 3227): Starting up...
,I/ActivityManager(  757): Killing 2688:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2688/cgroup.procs: No such file or directory
,D/Finsky  ( 2604): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3088): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3088): 
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 32887(2046KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 21MB/35MB, paused 844us total 36.696ms
,I/art     (  757): Explicit concurrent mark sweep GC freed 46384(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 892us total 70.485ms
,V/MusicLeanback( 2711): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  757): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1627): active receiver: enabled
,I/SystemUpdateService( 1627): showing system update notification
,I/iu.Environment( 1627): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1627): num queued entries: 0
,I/iu.UploadsManager( 1627): num updated entries: 0
,I/iu.SyncManager( 1627): NEXT; no task
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1627): onDestroy
,I/Babel   ( 1905): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2604): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2604): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2604): untagSocket(37) failed with errno -22
,D/Finsky  ( 2604): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3088): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3088): 
,I/ActivityManager(  757): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3332 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/jxcore-log( 3088): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3088): 
,I/jxcore-log( 3088): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3088): 
,I/jxcore-log( 3088): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3088): 
,W/ResourcesManager( 3332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3332): VM with version 2.1.0 has multidex support
I/MultiDex( 3332): install
I/MultiDex( 3332): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3332): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3332): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fabbe05: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3332): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3332): Reading stored module config
D/WearableService( 1601): callingUid 10008, callindPid: 1601
,E/MDM     ( 1601): [222] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3332): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/AuthorizationBluetoothService( 1601): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1627): Restart initialization of location
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2604): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2604): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2604): untagSocket(37) failed with errno -22
,W/GCoreFlp( 1601): No location to return for getLastLocation()
W/FusedLocationProvider( 1601): location=null
,D/CAR.SERVICE( 3332): Connecting to CarCallService...
,D/NativeLibraryUtils( 3332): Install completed successfully. count=14 extracted=0
,I/art     ( 3332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3332): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3332): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3332): Creating a new PhoneAdapter instance
,W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3332): setListener: com.google.android.gms.car.dn@23bc098
,W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3332): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3332): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3332): Package validated; name: com.android.vending
,V/Finsky  ( 2604): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2604): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2604): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2604): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2604): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2604): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2604): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2604): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1601): client connected with version: 8296000
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2604): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2604): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2711): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2711): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  757): No APN found to select.
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1627): active receiver: enabled
,I/SystemUpdateService( 1627): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1627): onDestroy
,I/jxcore-log( 3088): Test app app.js loaded
I/jxcore-log( 3088): 
,I/chromium( 3088): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3088): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a496c33 added. We now have 1 listener(s)
,I/jxcore-log( 3088): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3088): 
,I/ActivityManager(  757): Killing 2667:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  757): Client connection lost with reason: 4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2667/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 3332): mConnectedToCar = false, abort
,E/ActivityThread( 3332): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22a74180 that was originally bound here
E/ActivityThread( 3332): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22a74180 that was originally bound here
E/ActivityThread( 3332): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3332): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3332): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3332): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3332): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3332): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3332): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3332): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3332): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3332): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3332): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3332): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3332): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3332): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35ae2a7b that was originally bound here
E/ActivityThread( 3332): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35ae2a7b that was originally bound here
E/ActivityThread( 3332): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3332): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3332): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3332): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3332): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3332): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3332): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3332): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3332): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3332): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3332): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3332): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3332): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3332): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  757): Unbind failed: could not find connection for android.os.BinderProxy@1c8c8ab6
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2604): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2604): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1601): Vacuum at: now=1454422551803 tag=VacuumService
,I/PhenotypeConfigurator( 1601): Scheduling Phenotype for one-off execution 11201 seconds from now (1454422552205)
,D/GetConfigurationSnapshotOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1601): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1601): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1107): run()
I/Keyboard.Facilitator( 1107): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1601): disconnect managed GoogleApiClient
,I/art     (  757): Explicit concurrent mark sweep GC freed 36554(1625KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 982us total 122.490ms
,W/bt-smp  ( 2084): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2084): Plain text(LSB ~ MSB) = 7c e7 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2084): Encrypted text(LSB ~ MSB) = 29 d3 99 c1 20 81 27 83 45 a3 ce cb 18 9a 6a 30 
W/bt-btm  ( 2084): Stopping oneshot timer
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
