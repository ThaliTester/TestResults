#### Test 583805003a0697c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3092): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3092):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3092):   adb logcat -s GAv4
W/GAv4    ( 3092): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3092): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3092): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3092): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2644): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  757): Killing 2386:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3092): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/Sensors (  189): sns_acm_mr.c(432):Transport error -45
I/DisplayManagerService(  757): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  170): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  170): hwc_blank: Blanking display: 0
V/ActivityManager(  757): Display changed displayId=0
W/System  ( 3092): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3092): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2386/cgroup.procs: No such file or directory
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1651): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/qdhwcomposer(  170): hwc_blank: Done blanking display: 0
D/SurfaceControl(  757): Excessive delay in setPowerMode(): 283ms
I/Icing   ( 1651): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1651): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1651): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3153): 
D/AndroidRuntime( 3153): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3153): CheckJNI is OFF
D/AndroidRuntime( 3153): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3177 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3153): Shutting down VM
I/art     (  193): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 9.005ms
I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.575ms
I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 9.191ms
V/ActivityManager(  757): Display changed displayId=0
I/WebViewFactory( 3177): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3177): Time to load native libraries: 2 ms (timestamps 6062-6064)
I/LibraryLoader( 3177): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3177): Binding Chromium to main looper Looper (main, tid 1) {1d3528ae}
I/LibraryLoader( 3177): Expected native library version number "",actual native library version number ""
I/chromium( 3177): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3177): Initializing chromium process, singleProcess=true
W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3177): ApplicationContext is null in ApplicationStatus
W/chromium( 3177): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3177): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d53e921:true
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3177): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3177): CordovaWebView is running on device made by: LGE
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3177): Render dirty regions requested: true
,D/Atlas   ( 3177): Validating map...
,W/chromium( 3177): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3177): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3177): Enabling debug mode 0
,W/BindingManager( 3177): Cannot call determinedVisibility() - never saw a connection for the pid: 3177
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +441ms (total +44s150ms)
,W/IInputConnectionWrapper( 3177): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3177): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3177): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3177): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  757): Killing 2460:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2460/cgroup.procs: No such file or directory
,W/jxcore-log( 3177): Initializing JXcore engine
W/jxcore-log( 3177): JXcore engine is ready
,W/Thread-297( 3226): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8016]" dev="sockfs" ino=8016 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3226): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-297( 3226): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6630]" dev="sockfs" ino=6630 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-297( 3226): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19659]" dev="sockfs" ino=19659 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3177): Starting JXcore engine
,W/jxcore-log( 3177): Platform android
W/jxcore-log( 3177): 
W/jxcore-log( 3177): Process ARCH arm
W/jxcore-log( 3177): 
,I/jxcore-log( 3177): JXcore Cordova bridge is ready!
I/jxcore-log( 3177): 
,W/jxcore-log( 3177): JXcore engine is started
,I/jxcore-log( 3177): Toggling radios to true
I/jxcore-log( 3177): 
,D/BluetoothAdapter( 3177): enable(): BT is already enabled..!
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: true pid=3177, uid=10270
,E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3177): Radios toggled
I/jxcore-log( 3177): 
I/jxcore-log( 3177): My device name is: LGE-Nexus 5
I/jxcore-log( 3177): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  757): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1604): Read error: ssl=0x9d8f7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1604): SSL shutdown failed: ssl=0x9d8f7e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
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
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  757): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524292
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1273): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  757): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  757): Killing 2615:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2615/cgroup.procs: No such file or directory
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  757): Start Dhcp Watchdog 2
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/dhcpcd  ( 3259): version 5.5.6 starting
E/dhcpcd  ( 3259): get_duid: Read-only file system
,I/dhcpcd  ( 3259): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3259): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3259): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/Tethering(  757): MasterInitialState.processMessage what=3,
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1651): onCreate
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1651): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1651): num queued entries: 0
I/iu.UploadsManager( 1651): num updated entries: 0
I/iu.SyncManager( 1651): NEXT; no task
,I/SystemUpdateService( 1651): active receiver: enabled
,I/Babel   ( 1933): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1651): showing system update notification
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3286 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  757): No APN found to select.
,E/GpsLocationProvider(  757): No APN found to select.
I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3599907 ms
,D/SystemUpdateService( 1651): onDestroy
,I/GAv4    ( 3286): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3286):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3286):   adb logcat -s GAv4
,W/GAv4    ( 3286): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3286): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3286): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
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
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524290
,I/WebViewFactory( 3286): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3286): Time to load native libraries: 3 ms (timestamps 1849-1852)
,I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3286): Binding Chromium to main looper Looper (main, tid 1) {3af2c722}
I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
I/chromium( 3286): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3286): Initializing chromium process, singleProcess=true
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3286): ApplicationContext is null in ApplicationStatus
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:15:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455056134778], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455056134758]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,W/chromium( 3286): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1651): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1273): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/libEGL  ( 3286): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3286): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3286): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/Finsky  ( 2644): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 3286): Requires BLUETOOTH permission
,I/art     (  757): Explicit concurrent mark sweep GC freed 45596(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 920us total 79.504ms
,I/NSApplication( 3286): Starting up...
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1651): onCreate
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1651): active receiver: enabled
,I/SystemUpdateService( 1651): showing system update notification
,I/iu.Environment( 1651): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1651): num queued entries: 0
,I/iu.UploadsManager( 1651): num updated entries: 0
,I/iu.SyncManager( 1651): NEXT; no task
,I/ValidateNoPeople(  757): skipping global notification
,W/art     ( 2939): Suspending all threads took: 10.700ms
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1651): onDestroy
,I/Babel   ( 1933): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3177): 
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2644): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2644): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2644): untagSocket(37) failed with errno -22
,D/Finsky  ( 2644): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  757): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3384 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ConnectivityService(  757): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3384): VM with version 2.1.0 has multidex support
I/MultiDex( 3384): install
I/MultiDex( 3384): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3384): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@65ebe40: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3384): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1604): callingUid 10008, callindPid: 1604
,E/MDM     ( 1604): [226] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 3384): Reading stored module config
,I/qtaguid ( 2644): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2644): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2644): untagSocket(37) failed with errno -22
,D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1651): Restart initialization of location
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,D/ChimeraCfgMgr( 3384): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3177): 
,D/NativeLibraryUtils( 3384): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3384): Connecting to CarCallService...
,I/art     ( 3384): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3384): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3177): 
,D/CAR.SERVICE( 3384): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3384): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3384): Creating a new PhoneAdapter instance
,W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3384): setListener: com.google.android.gms.car.dn@13e79a0f
W/ActivityManager(  757): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3384): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3384): Starting CarCallService with initial phone null
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3177): 
,D/CAR.SERVICE( 3384): Package validated; name: com.android.vending
,V/Finsky  ( 2644): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3177): 
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2644): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2644): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2644): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2644): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2644): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2644): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2644): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1604): client connected with version: 8296000
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2644): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2644): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  757): Killing 2082:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  757): Killing 2565:com.google.android.apps.fitness/u0a45 (adj 15): empty #18
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2082/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_2565/cgroup.procs: No such file or directory
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2773): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1651): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1651): onCreate
,D/SystemUpdateService( 1651): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1651): active receiver: enabled
,I/SystemUpdateService( 1651): showing system update notification
E/GpsLocationProvider(  757): No APN found to select.
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1651): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1651): onDestroy
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test app app.js loaded
I/jxcore-log( 3177): 
,I/chromium( 3177): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2a001 added. We now have 1 listener(s)
,I/jxcore-log( 3177): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): TAP version 13
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 5 should be equal
I/jxcore-log( 3177): 
,D/CAR.SERVICE( 3384): mConnectedToCar = false, abort
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3177): 
,E/ActivityThread( 3384): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15dddf17 that was originally bound here
E/ActivityThread( 3384): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15dddf17 that was originally bound here
E/ActivityThread( 3384): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3384): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3384): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3384): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3384): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3384): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3384): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3384): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3384): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3384): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3384): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3384): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3384): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3384): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3384): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3384): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3384): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3384): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3384): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3384): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3384): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3384): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3384): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@381a336e that was originally bound here
E/ActivityThread( 3384): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@381a336e that was originally bound here
E/ActivityThread( 3384): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3384): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3384): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3384): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3384): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3384): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3384): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3384): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3384): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3384): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3384): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3384): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3384): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3384): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3384): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3384): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3384): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3384): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3384): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3384): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3384): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  757): Unbind failed: could not find connection for android.os.BinderProxy@46b95b9
,I/jxcore-log( 3177): ok 6 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 7 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 8 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 9 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 10 should throw
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons expiration out of range lower
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 12 Expiration out of range
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons expiration out of range lower
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 13 Expiration out of range
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons no beacons returns null
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 14 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 16 should be equal
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 17 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 18 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 19 should be equal
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ok 20 (unnamed assert)
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): # setup
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): ok 21 (unnamed assert)
I/jxcore-log( 3177): 
I/jxcore-log( 3177): # teardown
I/jxcore-log( 3177): 
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2644): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2644): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1604): Vacuum at: now=1455056166083 tag=VacuumService
,I/PhenotypeConfigurator( 1604): Scheduling Phenotype for one-off execution 4659 seconds from now (1455056166530)
,D/GetConfigurationSnapshotOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1604): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1604): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  757): Explicit concurrent mark sweep GC freed 32696(1426KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 811us total 77.268ms
,I/ClearcutLoggerApiImpl( 1604): disconnect managed GoogleApiClient
,I/jxcore-log( 3177): --= Surplus to requirements =--
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ****TEST TOOK:  ms ****
I/jxcore-log( 3177): 
I/jxcore-log( 3177): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3177): 
,D/AndroidRuntime( 3613): 
D/AndroidRuntime( 3613): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3613): CheckJNI is OFF
,D/AndroidRuntime( 3613): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 3177:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  757): WIN DEATH: Window{15b85c91 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  757): Client connection lost with reason: 4
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{23937ed u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  757): Skipping PackageSetting{1248462 com.example.hello/10278} due to missing metadata
,W/ActivityManager(  757): Spurious death for ProcessRecord{fe2c9e0 3177:com.test.thalitest/u0a270}, curProc for 3177: null
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1338): Explicit concurrent mark sweep GC freed 7380(552KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 503us total 29.189ms
I/art     ( 1651): Explicit concurrent mark sweep GC freed 3760(199KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 12.768ms total 58.811ms
,I/art     ( 1380): Explicit concurrent mark sweep GC freed 7787(555KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 319us total 23.818ms
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1604): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1110): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1110): run()
,D/VoicemailCleanupService( 1401): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1110): createOrResetDecoder
,I/art     (  757): Explicit concurrent mark sweep GC freed 9045(667KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.077ms total 76.792ms
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/UpdateIcingCorporaServi( 1380): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1338): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@69b864f new=com.google.android.velvet.VelvetApplication@69b864f
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3653 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): run()
,I/art     (  757): Explicit concurrent mark sweep GC freed 2584(131KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.918ms total 99.775ms
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/TaskPersister(  757): removeObsoleteFile: deleting file=216_task.xml
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = user
W/InputMethodManagerService(  757): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@9abd5d (uid=10034 pid=944)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1110): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1110): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1110): run()
I/StatsUtilsManager( 1110): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1110): shouldRecordStats() = Too Soon
,W/ContextImpl( 3653): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1651): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1651): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  757): Killing 2747:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/AndroidRuntime( 3613): Shutting down VM
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 125071(6MB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 24MB/40MB, paused 739us total 78.339ms
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c3ccfdb)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b9b6a78)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c6d1551)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3496f1b6)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@aae8eb7)
E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1458b624)
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2747/cgroup.procs: No such file or directory
,I/Launcher( 1338): Deferring update until onResume
,D/ChimeraCfgMgr( 1651): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1651): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1651): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1604): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1604): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1338): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1380): UpdateCorporaTask done [took 282 ms] updated apps [took 282 ms] 
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1651): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ResourcesManager( 1338): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1651): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1651): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1651): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1651): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1338): Deferring update until onResume
,I/ActivityManager(  757): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3687 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/GMPM-SVC( 1651): App measurement is starting up, version: 8489
I/GMPM-SVC( 1651): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1651): Using Auth Proxy for data requests.
,W/BaseAppContext( 1651): Using Auth Proxy for data requests.
,I/Icing   ( 1651): doRemovePackageData com.test.thalitest
,I/ActivityManager(  757): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3712 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,E/GMPM-SVC( 1651): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1775)
,I/ActivityManager(  757): Killing 2725:com.android.settings/1000 (adj 15): empty #17
,E/SharedPreferencesImpl( 1651): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,D/WifiService(  757): Client connection lost with reason: 4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2725/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2589:com.google.android.gm/u0a70 (adj 15): empty #17

```
