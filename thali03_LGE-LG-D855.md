#### Test 50650278e989a4f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 277726519418; DSPS: 9241767; Offset : -4321985895
,D/AndroidRuntime( 7004): 
D/AndroidRuntime( 7004): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7004): CheckJNI is OFF
D/AndroidRuntime( 7004): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1046): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1951): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1046): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1046): setTaskToReturnTo : TaskRecord{118c845b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1046): setTaskToReturnTo : TaskRecord{118c845b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1046): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1046): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7023 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7004): Shutting down VM
I/art     ( 1046): Explicit concurrent mark sweep GC freed 25943(1143KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.718ms total 71.362ms
V/ActivityManager( 1046): Display changed displayId=0
D/DSDPConnection( 1854): Display #0 changed.
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{314c6a81 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{26c2d726 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,D/ContextHelper( 7023): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7023): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7023): Loading: webviewchromium
,I/LibraryLoader( 7023): Time to load native libraries: 3 ms (timestamps 5524-5527)
,I/LibraryLoader( 7023): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7023): Binding Chromium to main looper Looper (main, tid 1) {2f6c2a71}
,I/LibraryLoader( 7023): Expected native library version number "",actual native library version number ""
I/chromium( 7023): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7023): Initializing chromium process, renderers=0
,W/art     ( 7023): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  329): registerClient() client 0xb152da40, uid 10311
,D/BluetoothManagerService( 1046): Message: 20
,D/BluetoothManagerService( 1046): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13fac60d:true
W/chromium( 7023): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7023): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7023): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7023): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7023): Build Date: 12/12/14 금
I/Adreno-EGL( 7023): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7023): Remote Branch: 
I/Adreno-EGL( 7023): Local Patches: 
I/Adreno-EGL( 7023): Reconstruct Branch: 
,W/chromium( 7023): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7023): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7023): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7023): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7023): CordovaWebView is running on device made by: LGE
,W/art     ( 7023): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7023): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7023): Render dirty regions requested: true
I/OpenGLRenderer( 7023): Initialized EGL, version 1.4
D/OpenGLRenderer( 7023): Enabling debug mode 0
,D/Atlas   ( 7023): Validating map...
D/SplitWindow( 1046): check instance of lgWin Window{659fd1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7023): LgDataFeature() Constructor: none
,D/LgDataFeature( 7023): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1046): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1046): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1046): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1046): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@51770f4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1445): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1046): Displayed com.test.thalitest/.MainActivity: +611ms (total +772ms)
I/Timeline( 1046): Timeline: Activity_windows_visible id: ActivityRecord{28a44f8 u0 com.test.thalitest/.MainActivity t4} time:285960
,I/Timeline( 7023): Timeline: Activity_idle id: android.os.BinderProxy@74b91e1 time:285966
D/JsMessageQueue( 7023): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7023): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7023): 
,D/jxcore_app_log( 7023): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435100416
,D/JX-Cordova( 7023): jxcore cordova android initializing
E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7023): Initializing JXcore engine
W/jxcore-log( 7023): JXcore engine is ready
,W/jxcore-log( 7023): Starting JXcore engine
,W/.test.thalitest( 7023): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7569]" dev="sockfs" ino=7569 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7023): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7023): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9905]" dev="sockfs" ino=9905 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7023): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7023): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33942]" dev="sockfs" ino=33942 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7023): Platform android
W/jxcore-log( 7023): 
W/jxcore-log( 7023): Process ARCH arm
W/jxcore-log( 7023): 
I/jxcore-log( 7023): JXcore Cordova bridge is ready!
I/jxcore-log( 7023): 
W/jxcore-log( 7023): JXcore engine is started
,I/chromium( 7023): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7023): 
I/jxcore-log( 7023): Toggling radios to true
I/jxcore-log( 7023): 
,D/BluetoothAdapter( 7023): enable(): BT is already enabled..!
D/WifiService( 1046): New client listening to asynchronous messages
D/WifiServiceImplEx( 1046): setWifiEnabled: true pid=7023, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1046): setWifiEnabled: true pid=7023, uid=10311
E/WifiService( 1046): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1046): disconnect pid=7023, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1046):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1046):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1046): [289,596,836 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1046): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1046): reconnect pid=7023, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7023): Radios toggled
I/jxcore-log( 7023): 
D/BluetoothManagerService( 1046): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7023): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7023): 
I/jxcore-log( 7023): Perf Test app loaded loaded
I/jxcore-log( 7023): 
I/jxcore-log( 7023): check test folder
I/jxcore-log( 7023): 
I/jxcore-log( 7023): found test : ./testFindPeers.js
I/jxcore-log( 7023): 
,I/jxcore-log( 7023): found test : ./testSendData.js
I/jxcore-log( 7023): 
I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1046): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1046): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1046): DISCONNECT: returned true
,E/WifiStateMachine( 1046): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
,D/Tethering( 1046): InitialState.processMessage what=4
D/Tethering( 1046): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1046): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1046): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/CommandListener(  325): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1046): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2118): Read error: ssl=0xaf499600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2118): SSL shutdown failed: ssl=0xaf499600: I/O error during system call, Broken pipe
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1046): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager( 1046): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7101 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1046): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1046):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1046): [289,740,546 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1046): doBoolean: RECONNECT
I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1046): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1046): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1046): hidePasspointNotification off =false
D/DSQN    ( 1046): Dns fail occured do internet check.
D/ConnectivityService( 1046): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1046): disableDataServiceNotify
D/DSQN    ( 1046): stop dsqn bin
D/WifiNative-wlan0( 1046): RECONNECT: returned true
D/DSQN    ( 1046): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1046): try Internet connection check
E/WifiStateMachine( 1046):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289749
E/WifiStateMachine( 1046):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289750
D/LGWifiP2pService( 1046): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,V/WfdStateTracker( 1951): handleWifiStateChangedEvent: 0
D/LGWifiP2pService( 1046): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/CommandListener(  325): Clearing all IP addresses on wlan0
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1046): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1046): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1046): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1046): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1046): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/WifiHS20( 1046): hidePasspointNotification off =false
D/ConnectivityService( 1046): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1046): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1046): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1046): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524292
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1046): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1046): Removing idletimer
W/Settings( 1046): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1046): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1046): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiDataContinuityService( 1046): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/TelephonyNetworkFactory-1( 1854): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capa,bilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1854):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1046): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1046): [LG_RESTRICTED] !!!isConnected  type  :1
,D/WifiServiceExtension( 1951): isInternetCheckAvailable return false
D/LocSvc_java( 1046): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1046): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=289783  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=289783  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1046):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1046):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1046):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1046): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1046):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1046):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=289791  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=289795  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1046): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateSCANNING
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7101): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Choreographer( 7023): Skipped 79 frames!  The application may be doing too much work on its main thread.
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
I/chromium( 7023): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7023): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1046): StoppedState
,D/DhcpStateMachine( 1046): StoppedState{ when=-98ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7101): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7101): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7101): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7101): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7101): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7101): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1046): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7127 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6593:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_10008/pid_6593/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{5cb9f58 type 0 when 1450233255036 android} when 1450233255036
V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{184fd8b1 type 2 when 290097 com.google.android.gms} when 290097
D/PCSuite ( 7127): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7101): LgDataFeature() Constructor: none
D/LgDataFeature( 7101): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,I/ActivityManager( 1046): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7149 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1046): Killing 6070:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1046): failed to open /acct/uid_10011/pid_6070/cgroup.procs: No such file or directory
,W/ResourcesManager( 7149): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7149): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7149): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7149): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7149): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7149): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7149): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7149): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7149): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7149): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7127): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7149): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7127): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7127): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiStateMachine( 1046):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:226302] from screen [on:0 period:-1465690330]
D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1046): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/QRemote ( 7149): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7149): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7149): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7149): LgDataFeature() Constructor: none
D/LgDataFeature( 7149): LgDataFeature() Constructor Done, null
,V/SoundPool( 7149): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7149): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7149): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7149): doLoad: loading sample sampleID=1
V/SoundPool( 7149): Start decode
V/MediaPlayer[Native]( 7149): decode(31, 10857164, 17813)
V/MediaPlayerService(  329): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  329): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  329): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  329): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  329): player type = 3
V/AwesomePlayer(  329): AwesomePlayer create()
I/QRemote ( 7149): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): setAudioSink() 
V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/Utils   (  329): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  329): setDataSource_l dataSource
V/LGParserOSAL(  329): SniffLGParser start
V/LGParserOSAL(  329): MainType:5, SubType=0
V/LGParserOSAL(  329): #### check Mime : application/ogg
V/LGParserOSAL(  329): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  329): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6753): QS Service created
D/QRemote ( 7149): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7149): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/DSQN    ( 1046): EVENT_INTERNET_CHECK_ENABLE received
I/UEI.SmartControl( 6753): Service initServices...
D/UEI.SmartControl( 6753): QS start get config
,V/LGMDMManager( 7149): Create singleton instance
,V/LGParserOSAL(  329): supported mime: application/ogg
V/AwesomePlayer(  329): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  329): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  329): mBitrate = -1 bits/sec
V/AwesomePlayer(  329): AudioTrack Setting
V/AwesomePlayer(  329): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  329): setAudioSource() 
V/MediaPlayerService(  329): prepare
V/AwesomePlayer(  329): prepareAsync_l() 
V/MediaPlayerService(  329): wait for prepare
V/AwesomePlayer(  329): onPrepareAsyncEvent() 
V/AwesomePlayer(  329): initAudioDecoder() 
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  329): isAudioPlaybackHookOn() false
V/AwesomePlayer(  329): getUseOffload() = 0 
V/OMXCodec(  329): OMXCodec::Create
V/OMXCodec(  329): findMatchingCodecs()
,V/OMXCodec(  329): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  329): matchingCodecs.size()=1
V/OMXCodec(  329): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  329): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  329): LG Codec Adapter start
V/OMXCodec(  329): OMXCodec Createtor
V/OMXCodec(  329): setComponentRole
V/OMXCodec(  329): configureCodec protected=0
V/LGCodecAdapter(  329): called getLGCodecSpecificData
V/LGCodecOSAL(  329): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMSG
,V/LGCodecOSAL(  329): Not support LGCodec
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  329): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  329): Could not offload audio decode, try pcm offload
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  329): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  329): init()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  329): allocateBuffers
V/OMXCodec(  329): allocateBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544380 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544a10 on input port
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544a60 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b00 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b50 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544bf0 on output port
V/OMXCodec(  329): init() mAsyncCompletion wait!!! 
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  329): init() mAsyncCompletion wait!!! 
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  329): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  329): finishAsyncPrepare_l() 
V/AudioCache(  329): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  329): ignored
V/AudioCache(  329): notify(0xb54749c0, 1, 0, 0)
V/AudioCache(  329): prepared
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): start
V/AwesomePlayer(  329): play_l() 
V/AwesomePlayer(  329): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  329): createAudioPlayer_l
V/AwesomePlayer(  329): seekAudioIfNecessary_l() 
V/AwesomePlayer(  329): startAudioPlayer_l() 
D/AudioPlayer(  329): start of Playback, useOffload 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  329): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  329): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2,975091296
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091456
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091536
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091696
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  329): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b50 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b00 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1544a60 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  329): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  329): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  329): ignored
V/MediaPlayerService(  329): wait for playback complete
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae404000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae405000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae406000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae407000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae408000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae409000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40a000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40b000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40c000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40d000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40e000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae40f000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae410000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae411000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae412000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae413000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae414000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae415000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae416000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae417000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae418000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae419000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41a000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41b000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41c000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41d000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41e000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae41f000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae420000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae421000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae422000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae423000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae424000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae425000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae426000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae427000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae428000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae429000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42a000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42b000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42c000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42d000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42e000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae42f000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae430000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae431000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae432000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae433000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae434000, 0xb57f5000, 4096)
V/AudioCache(  329): write(0xb57f5000, 4096)
V/AudioCache(  329): memcpy(0xae435000, 0xb57f5000, 4096)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  329): postAudioEOS() 
V/AudioCache(  329): write(0xb57f5000, 280)
V/AudioCache(  329): memcpy(0xae436000, 0xb57f5000, 280)
V/AwesomePlayer(  329): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  329): onStreamDone
V/AwesomePlayer(  329): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  329): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  329): playback complete
V/AwesomePlayer(  329): pause_l() 
V/AudioCache(  329): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/AudioPlayer(  329): Pause Playback at 1068125
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/AudioPlayer(  329): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1544a10 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1544380 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1544a60 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1544b00 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1544b50 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  329): AudioPlayer releasing audio source
D/AudioPlayer(  329): AudioPlayer done releasing audio source
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): ~AwesomePlayer call
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/SoundPool( 7149): close(31)
V/SoundPool( 7149): pointer = 0x9fe62000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7149): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:341
I/UEI.SmartControl( 6753): Supports setup maps: true
,D/UEI.SmartControl( 6753): QS start statue = true Error code = 0
I/UEI.SmartControl( 6753): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6753): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6753): ### init IR Blaster...
D/serial_port( 6753): Configuring serial port
E/UEI.SmartControl( 6753): UEIBLaster setting for 616
I/UEI.SmartControl( 6753): Setting serial record hearder size = 2
I/UEI.SmartControl( 6753): configuring settings for MAXQ616
I/UEI.SmartControl( 6753): Get version...
D/UEI.SmartControl( 6753): serial port data available: 21
,D/UEI.SmartControl( 6753): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6753): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6753): QS saving settings...
D/UEI.SmartControl( 6753): IR Blaster version: 25672567
,D/UEI.SmartControl( 6753): serial port data available: 4
,I/UEI.SmartControl( 6753): Device manager: loading config....
D/UEI.SmartControl( 6753): ----------- loading internal config...
W/ContextImpl( 6753): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6753): Services init done
D/UEI.SmartControl( 6753): QS Service init finished
D/UEI.SmartControl( 6753): QS Service version name: 2.1.91
D/UEI.SmartControl( 6753): QS Service version code: 201091
D/UEI.SmartControl( 6753): Service requested: Control
,E/UEI.SmartControl( 6753): Loading SETTINGS...
D/UEI.SmartControl( 6753): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6753): Internal service binding...
I/QRemote ( 7149): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6753): ------ IControl API: 11
D/UEI.SmartControl( 6753): File observer start...
E/UEI.SmartControl( 6753): IR Port is disabled: false
D/UEI.SmartControl( 6753): Starting file observer...
I/UEI.SmartControl( 6753): Registering callback...
D/UEI.SmartControl( 6753): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6753): ------ IControl API: 19
I/UEI.SmartControl( 6753): Registering Services Ready callback...
,I/UEI.SmartControl( 6753): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6753): -----service ready thread exits
,I/QRemote ( 7149): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7149): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7149): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7149): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7149): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6753): ------ IControl API: 8
D/QRemote ( 7149): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7149): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7149): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7149): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7149): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7149): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7149): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7149): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7149): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7149): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450233256368]
,D/QRemote ( 7149): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1046): Killing 6094:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7149): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1046): failed to open /acct/uid_10019/pid_6094/cgroup.procs: No such file or directory
,V/QRemote ( 7149): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7149): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{320ec49c type 2 when 291404 com.google.android.gms} when 291404
,D/QRemote ( 7149): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2677): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1046): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1046): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1046):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1046):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1046):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1046):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1046): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=291966  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=291998  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7149): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2677): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1046): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292069  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2677): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292078  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1046):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292079
D/WifiMonitor( 1046): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1046): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1046): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1046):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292083
D/Tethering( 1046): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1046):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292094
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292094
E/WifiStateMachine( 1046):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292095
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292095  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292125  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292127  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292135  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1046):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292138
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
E/WifiStateMachine( 1046):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292139
D/WifiNative-wlan0( 1046): doString: [STATUS]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1046):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1046): setVHTCapabilityType  : false
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1046): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1046): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7101): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7101): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7101): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7101): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7101): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7101): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7101): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1046): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1046): Got NetworkAgent Messenger
,E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1046): NetworkAgent connected
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
D/CommandListener(  325): Setting iface cfg
E/WifiStateMachine( 1046): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1046): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1046): WaitBeforeStartState
E/WifiStateMachine( 1046):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292184  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,E/WifiStateMachine( 1046):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292185  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292185  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateFOUR_WAY_HANDSHAKE
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1046):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292194  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292194  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292195  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1046):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1046):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
E/WifiStateMachine( 1046):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1046): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1046): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 0
D/WifiNative-wlan0( 1046): SET ps 0: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1046): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1046): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService( 1046): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3407cde1 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1046): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1046): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3407cde1 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1046): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1046): DHCP Start wake lock is acquired.
D/CommandListener(  325): Setting iface cfg
D/CommandListener(  325): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1046): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1046):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1046):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1046):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1046): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1046): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1046): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1046):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1046): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1046): ignoring duplicate network state non-change
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1046): Adding iface wlan0 to network 101
E/WifiStateMachine( 1046): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1046): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1951): handleWifiStateChangedEvent: 1
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1046): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/ConnectivityService( 1046): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1046): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1046): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  325): netlink response contains error (File exists)
D/ConnectivityService( 1046): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1046): addLocalRoutetoDefaultNetwork
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1046): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1046): Setting Dns servers for network 101 to [/192.168.1.1]
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1046): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1046): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Connected
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1046): currentScore = 0, newScore = 20
D/ConnectivityService( 1046):    accepting network in place of null
D/ConnectivityService( 1046): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1046): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }, for legacy network type 1
D/CSLegacyTypeTracker( 1046): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1854): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1854):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1046): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1046): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1046): validation of new default Network = false
D/ConnectivityService( 1046): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1046): enableDataServiceNotify 
D/DSQN    ( 1046): start dsqn bin
D/LocSvc_java( 1046): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1046): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7228): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7228): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 7228): DSQN ssw
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1046): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
,D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7149): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/LGDataListener(  325): argv[0]=dsqncommand
D/LGDataListener(  325): argv[1]=wlan0
D/LGDataListener(  325): argv[2]=1
D/LGDataListener(  325): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1046): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1046): start to monitor internet connection
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:34:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233257466], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233257449]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Validated
D/ConnectivityService( 1046): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1046): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1046): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1046): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1854): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1854):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,D/DhcpStateMachine( 1046): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1046): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1046): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7149): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
W/dhcpcd  ( 7234): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7149): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7149): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
W/dhcpcd  ( 7234): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/dhcpcd  ( 7234): version 5.5.6 starting
E/dhcpcd  ( 7234): get_duid: m
D/dhcpcd  ( 7234): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7234): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/PCSuite ( 7127): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7127): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7101): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 7101): MCCMNC not supported: null
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 7149): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7149): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7149): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7149): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7149): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/dhcpcd  ( 7234): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7234): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7234): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7234): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7234): wlan0: sending REQUEST (xid 0x15a9c6c5), next in 3.12 seconds
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1046): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1046): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5429): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5429): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1046): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7251 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{2209a9b8 type 2 when 292860 com.google.android.gms} when 292860
D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7251): onCreate
W/AppUp4:DB( 7251):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7251):  setFingerPrint start
,I/AppUp4:DB( 7251):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7251):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7251):  SDK version = 21
I/AppUp4:DB( 7251):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7251): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7251): onReceive
,D/LgDataFeature( 7251): LgDataFeature() Constructor: none
D/LgDataFeature( 7251): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7251): Context : android.app.ReceiverRestrictedContext@164378d7
D/AppUp4:CustFacade( 7251): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7251): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7251): begin check event
I/AppUp4:CustModeStarterReceiver( 7251): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7251): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7251): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7251): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7251): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1046): Killing 6494:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1046): failed to open /acct/uid_10004/pid_6494/cgroup.procs: No such file or directory
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3361): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3361): DownloadService onCreate
D/LGDMClient( 4266): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/DownloadManager( 3361): in removeSpuriousFiles
V/DownloadManager( 3361): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@195489a on behalf of 3361
,I/LGDMClient( 4266): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3361): DownloadService onStartCommand
I/DownloadManager( 3361): in trimDatabase
V/DownloadManager( 3361): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@1a1394c1 on behalf of 3361
,D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3361): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.,
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@1fef5466 on behalf of 3361
E/LGDMClient( 4266): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4266): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4266): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3361): processing inserted download 1
,D/eas_req ( 6615): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3361): processing inserted download 4
V/DownloadManager( 3361): processing inserted download 7
V/DownloadManager( 3361): processing inserted download 8
V/DownloadManager( 3361): processing inserted download 9
V/DownloadManager( 3361): processing inserted download 10
V/DownloadManager( 3361): processing inserted download 16
V/DownloadManager( 3361): processing inserted download 17
V/DownloadManager( 3361): processing inserted download 18
,V/DownloadManager( 3361): processing inserted download 21
V/DownloadManager( 3361): DownloadService onDestroy
I/ActivityManager( 1046): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7294 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6615): JNI_OnLoad()
I/HubEmail( 6615): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6615): registerNatives()
I/HubEmail( 6615): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6615): registerNativeMethods()
,I/HubEmail( 6615): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6615): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 22.366ms
W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 20.189ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 17.897ms
,I/LgeMiscReceiver( 3332): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3332): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3332): networkInfo.isConnected() = false
,I/ActivityManager( 1046): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7318 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1046):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1046): identical MTU - not setting
D/Nat464Xlat( 1046): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1046): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524295
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 7234): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7234): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7234): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7234): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7234): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7234): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7234): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7234): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7234): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1046): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7342 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1046): Killing 6645:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1046): failed to open /acct/uid_10027/pid_6645/cgroup.procs: No such file or directory
,I/ActivityManager( 1046): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7370 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6676:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1046): failed to open /acct/uid_10061/pid_6676/cgroup.procs: No such file or directory
,I/jxcore-log( 7023): Connected to the server!
I/jxcore-log( 7023): 
,V/FormManager( 7294): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7294): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 7370): Almond Protected OAT
I/ActivityManager( 1046): Killing 6708:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/chromium( 7023): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/libprocessgroup( 1046): failed to open /acct/uid_10080/pid_6708/cgroup.procs: No such file or directory
,D/WeatherApplication( 7370): removeAccount
,D/WeatherApplication( 7370): Account.length = 0
E/WeatherApplication( 7370): OPERATOR:OPEN
D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:19
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
,D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is not up-to-date, count: 0
,D/DhcpStateMachine( 1046): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1046): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1046): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1046): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1046): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1046): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1046): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1046): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1046): RunningState
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:19
,I/ActivityManager( 1046): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7403 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6775:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6775/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7403): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/jxcore-log( 7023): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7023): 
I/LibraryLoader( 7403): Loading: webviewchromium
I/LibraryLoader( 7403): Time to load native libraries: 4 ms (timestamps 4624-4628)
,I/LibraryLoader( 7403): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7403): Binding Chromium to main looper Looper (main, tid 1) {207744de}
I/LibraryLoader( 7403): Expected native library version number "",actual native library version number ""
,I/chromium( 7403): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7403): Initializing chromium process, renderers=0
W/art     ( 7403): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  329): registerClient() client 0xb152dc60, uid 10093
W/AudioManagerAndroid( 7403): Requires BLUETOOTH permission
,W/chromium( 7403): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7403): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7403): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7403): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7403): Build Date: 12/12/14 금
I/Adreno-EGL( 7403): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7403): Remote Branch: 
I/Adreno-EGL( 7403): Local Patches: 
I/Adreno-EGL( 7403): Reconstruct Branch: 
,E/WifiStateMachine( 1046):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1046):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/NSApplication( 7403): Starting up...
,I/ActivityManager( 1046): Killing 6797:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6797/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7251): onReceive
,D/AppUp4:CustFacade( 7251): Context : android.app.ReceiverRestrictedContext@164378d7
,D/AppUp4:CustFacade( 7251): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7251): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7251): begin check event
I/AppUp4:CustModeStarterReceiver( 7251): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3361): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3361): DownloadService onCreate
I/DownloadManager( 3361): in removeSpuriousFiles
,V/DownloadManager( 3361): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@3e8c50f2 on behalf of 3361
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3361): DownloadService onStartCommand
V/DownloadManager( 3361): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3361): in trimDatabase
V/DownloadManager( 3361): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4266): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@2f946343 on behalf of 3361
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@13eddc0 on behalf of 3361
,I/LGDMClient( 4266): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/LgeMiscReceiver( 3332): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3332): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3332): networkInfo.isConnected() = false
W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3361): processing inserted download 1
,V/DownloadManager( 3361): processing inserted download 4
V/DownloadManager( 3361): processing inserted download 7
V/DownloadManager( 3361): processing inserted download 8
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3361): processing inserted download 9
V/DownloadManager( 3361): processing inserted download 10
V/DownloadManager( 3361): processing inserted download 16
V/DownloadManager( 3361): processing inserted download 17
V/DownloadManager( 3361): processing inserted download 18
V/DownloadManager( 3361): processing inserted download 21
,E/LGDMClient( 4266): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4266): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4266): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:20
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3247fcad
D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:20
,V/DownloadManager( 3361): DownloadService onDestroy
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2346): [AccountUtils] Account not ready
W/Kids    ( 2346): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2346): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2346): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1405): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1405): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
V/FormManager( 7294): There are no updated forms. The schedule will be deleted.
V/FormManager( 7294): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  325): res_queryN name = mtalk.google.com succeed
I/art     ( 2118): Explicit concurrent mark sweep GC freed 43224(2MB) AllocSpace objects, 11(1479KB) LOS objects, 51% free, 30MB/62MB, paused 1.401ms total 60.417ms
,V/WifiInternetCheck( 1046): Single check msg out of sync, ignoring.
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
W/Kids    ( 2346): [AccountUtils] Account not ready
W/Kids    ( 2346): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2346): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2346): 	at java.lang.Thread.run(Thread.java:818)
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
D/Tethering( 1046): MasterInitialState.processMessage what=3
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/PostponalbeReceiver( 6563): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
I/NetworkMonitor( 5429): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7251): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7251): onReceive
,D/AppUp4:CustFacade( 7251): Context : android.app.ReceiverRestrictedContext@164378d7
,D/AppUp4:CustFacade( 7251): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7251): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7251): begin check event
I/AppUp4:CustModeStarterReceiver( 7251): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/GCM     ( 2118): Connected
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 84046(3MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 5.710ms total 159.269ms
,V/DownloadManager( 3361): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4266): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3361): DownloadService onCreate
D/GCM     ( 2118): Message class com.google.f.a.a.p
I/LGDMClient( 4266): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3361): in removeSpuriousFiles
V/DownloadManager( 3361): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@3b8a8a3e on behalf of 3361
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3361): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3361): in trimDatabase
V/DownloadManager( 3361): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@3a0ff09f on behalf of 3361
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4266): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LgeMiscReceiver( 3332): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3332): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3332): networkInfo.isConnected() = true
D/PhoneState( 3332): setPdpRejectCasuse : false
V/DownloadManager( 3361): DownloadService onStartCommand
V/DownloadManager( 3361): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4266): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4266): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4266): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3361): created cursor android.database.sqlite.SQLiteCursor@26a10c4a on behalf of 3361
W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3361): processing inserted download 1
V/DownloadManager( 3361): processing inserted download 4
D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:20
V/DownloadManager( 3361): processing inserted download 7
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3247fcad
V/DownloadManager( 3361): processing inserted download 8
D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:34:20
V/DownloadManager( 3361): processing inserted download 9
V/DownloadManager( 3361): processing inserted download 10
V/DownloadManager( 3361): processing inserted download 16
V/DownloadManager( 3361): processing inserted download 17
V/DownloadManager( 3361): processing inserted download 18
,V/DownloadManager( 3361): processing inserted download 21
V/DownloadManager( 3361): DownloadService onDestroy
V/FormManager( 7294): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7294): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2346): [AccountUtils] Account not ready
W/Kids    ( 2346): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2346): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2346): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6753): Internal timer expired: 4
D/UEI.SmartControl( 6753): unbind internal service
,D/serial_port( 6753): close(fd = 24)
,I/UEI.SmartControl( 6753): Serial port is closed.
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  325): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = www.google.com succeed
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1046): isHttpConnectionAvailable - We got a valid response : 204
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 297728367233; DSPS: 9897188; Offset : -4321999705
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{26688ef9 type 2 when 297840 android} when 297840
,V/QRemote ( 7149): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7149): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:341
,I/BooksSync( 6904): Starting books sync
,D/BooksSync( 6904): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4506555827683697220&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GAV4    ( 7403): Thread[GAThread,5,main]: No campaign data found.
W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
W/ApiaryClient( 6904): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4506555827683697220&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4506555827683697220&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
E/BooksSync( 6904): Soft error: 
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4506555827683697220&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
,E/BooksSync( 6904): Sync error
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4506555827683697220&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
I/BooksSync( 6904): Finished books sync
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297840, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 317729979049; DSPS: 10552601; Offset : -4322005398
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{12c0b338 type 2 when 327914 android} when 327914
,E/WifiStateMachine( 1046):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 337731435969; DSPS: 11208008; Offset : -4321982753
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 357733644919; DSPS: 11863441; Offset : -4322001481
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6196): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6196): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6196): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6196): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6196): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6196): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6196): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6196): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 377735632985; DSPS: 12518866; Offset : -4321997032
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 397737352299; DSPS: 13174282; Offset : -4321986780
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 417738775989; DSPS: 13829689; Offset : -4321997417
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1046): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3775): Disconnected process message: 10, size: 0
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 437740783483; DSPS: 14485115; Offset : -4322004135
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1046): battery changed pluggedType: 2
D/HeadsetStateMachine( 3775): Disconnected process message: 10, size: 0
D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 457742513058; DSPS: 15140531; Offset : -4321983545
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 477744490290; DSPS: 15795956; Offset : -4321989929
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 497746406272; DSPS: 16451379; Offset : -4321996606
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 517748427097; DSPS: 17106805; Offset : -4321989889
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 537751102403; DSPS: 17762253; Offset : -4322000182
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{37e7c35a type 2 when 550936 android} when 550936
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,I/BooksSync( 6904): Starting books sync
,D/BooksSync( 6904): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
W/ApiaryClient( 6904): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198843628005597856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198843628005597856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 30798(1430KB) AllocSpace objects, 11(1072KB) LOS objects, 33% free, 44MB/66MB, paused 3.314ms total 164.460ms
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198843628005597856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
E/BooksSync( 6904): Soft error: 
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198843628005597856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
,E/BooksSync( 6904): Sync error
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198843628005597856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
I/BooksSync( 6904): Finished books sync
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 557752895312; DSPS: 18417672; Offset : -4322007784
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 577754883689; DSPS: 19073097; Offset : -4322003024
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{2d2ed70c type 2 when 581150 android} when 581150
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 597756501493; DSPS: 19728510; Offset : -4322002677
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 617758122632; DSPS: 20383923; Offset : -4321998996
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 637760242261; DSPS: 21039352; Offset : -4321985159
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,I/ActivityManager( 1046): Killing 6824:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_10005/pid_6824/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 657761991367; DSPS: 21694770; Offset : -4322006019
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 677763895839; DSPS: 22350192; Offset : -4321993455
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 697765559373; DSPS: 23005607; Offset : -4322008518
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 717767507542; DSPS: 23661030; Offset : -4321983008
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 737769174878; DSPS: 24316445; Offset : -4321994088
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 757771549767; DSPS: 24971883; Offset : -4321999647
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 777773532415; DSPS: 25627308; Offset : -4322000564
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 797775180637; DSPS: 26282722; Offset : -4322000343
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 817776559275; DSPS: 26938127; Offset : -4321994996
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 837778464163; DSPS: 27593549; Offset : -4321982121
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 857780835406; DSPS: 28248987; Offset : -4321991275
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 877782783835; DSPS: 28904411; Offset : -4321996023
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 897784180442; DSPS: 29559817; Offset : -4322003172
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 917785766581; DSPS: 30215229; Offset : -4322003947
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,I/ActivityManager( 1046): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7693 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7693): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7693): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@36c32018
D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
I/ActivityManager( 1046): Killing 6196:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1046): failed to open /acct/uid_10044/pid_6196/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 937788340323; DSPS: 30870673; Offset : -4321993655
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{21bf6855 type 2 when 942340 com.android.bluetooth} when 942340
,W/bt-smp  ( 3775): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3775): Plain text(LSB ~ MSB) = 02 a4 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3775): Encrypted text(LSB ~ MSB) = 15 9e 84 d4 d2 c5 3f d4 a0 70 4f 9d 22 da 5b 50 
W/bt-btm  ( 3775): Stopping oneshot timer
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 957790931409; DSPS: 31526118; Offset : -4321996590
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 977792739370; DSPS: 32181537; Offset : -4321989089
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 997794144310; DSPS: 32836943; Offset : -4321988113
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1017795144042; DSPS: 33492336; Offset : -4321995435
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1037797307263; DSPS: 34147767; Offset : -4321998910
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{3707826a type 2 when 1053346 android} when 1053346
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,I/BooksSync( 6904): Starting books sync
,D/BooksSync( 6904): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7825074475002826633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
W/ApiaryClient( 6904): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7825074475002826633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7825074475002826633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
E/BooksSync( 6904): Soft error: 
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7825074475002826633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
,E/BooksSync( 6904): Sync error
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7825074475002826633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
I/BooksSync( 6904): Finished books sync
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1053346, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1057798680485; DSPS: 34803172; Offset : -4321997207
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1077800582666; DSPS: 35458594; Offset : -4321988888
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{38cbed7a type 2 when 1083725 android} when 1083725
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1097802552137; DSPS: 36114019; Offset : -4322003138
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1117804248535; DSPS: 36769434; Offset : -4321985207
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1137808251705; DSPS: 37424925; Offset : -4321979708
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1157810923312; DSPS: 38080373; Offset : -4321993701
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1046): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3775): Disconnected process message: 10, size: 0
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1177812816377; DSPS: 38735795; Offset : -4321992752
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1197814200588; DSPS: 39391200; Offset : -4321981779
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1217815752091; DSPS: 40046611; Offset : -4321986725
,I/UsageStatsService( 1046): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1237817666927; DSPS: 40702034; Offset : -4321994497
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1257819454888; DSPS: 41357453; Offset : -4322007125
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1277821805922; DSPS: 42012890; Offset : -4322005840
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1297823743780; DSPS: 42668313; Offset : -4321990589
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1317825479084; DSPS: 43323730; Offset : -4321994761
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1337827255743; DSPS: 43979148; Offset : -4321988174
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1357828990996; DSPS: 44634565; Offset : -4321992449
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1377830954634; DSPS: 45289989; Offset : -4321981987
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1397832627907; DSPS: 45945404; Offset : -4321987182
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1417834034098; DSPS: 46600810; Offset : -4321984748
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1437835991382; DSPS: 47256234; Offset : -4321980536
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1457837608510; DSPS: 47911648; Offset : -4322011357
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1477839593501; DSPS: 48567072; Offset : -4321979491
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1497841583858; DSPS: 49222498; Offset : -4322003398
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1517842884529; DSPS: 49877900; Offset : -4321984361
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1537844795146; DSPS: 50533323; Offset : -4321996457
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1557846649618; DSPS: 51188744; Offset : -4322003426
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1577848039766; DSPS: 51844149; Offset : -4321986595
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1597849908925; DSPS: 52499570; Offset : -4321979164
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1617851871417; DSPS: 53154995; Offset : -4322000159
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1637853704848; DSPS: 53810415; Offset : -4321997731
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1657855681142; DSPS: 54465840; Offset : -4322005236
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{378b792b type 0 when 1450233889438 com.google.android.gms} when 1450233889438
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{78fe188 type 2 when 1140566 com.google.android.gms} when 1140566
V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{62aa721 type 2 when 1195531 com.google.android.gms} when 1195531
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 2118): Message class com.google.f.a.a.i
I/EventLogService( 2346): Aggregate from 1450232089363 (log), 1450232089363 (data)
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Ads     ( 2346): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/art     ( 2118): Explicit concurrent mark sweep GC freed 38974(2MB) AllocSpace objects, 27(3MB) LOS objects, 51% free, 30MB/62MB, paused 802us total 34.132ms
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1677857379936; DSPS: 55121255; Offset : -4321984804
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1697859198262; DSPS: 55776675; Offset : -4321997585
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1717861540755; DSPS: 56432112; Offset : -4322004919
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1737863208560; DSPS: 57087526; Offset : -4321985012
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1757865085895; DSPS: 57742948; Offset : -4321999845
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1046): battery changed pluggedType: 2
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3775): Disconnected process message: 10, size: 0
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4266): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1777866630471; DSPS: 58398359; Offset : -4322011717
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1797868266974; DSPS: 59053772; Offset : -4321992567
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1817869792122; DSPS: 59709182; Offset : -4321993299
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,I/ProcessStatsService( 1046): Prepared write state in 33ms
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7693): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7693): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@36c32018
D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
I/ProcessStatsService( 1046): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-17-12.bin
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1837871884928; DSPS: 60364611; Offset : -4322006283
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{3add4ecd type 2 when 1842367 com.android.bluetooth} when 1842367
,W/bt-smp  ( 3775): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3775): Plain text(LSB ~ MSB) = 46 18 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3775): Encrypted text(LSB ~ MSB) = 99 32 75 c7 58 f3 fb 46 f2 d8 a6 f7 41 ec a5 fb 
W/bt-btm  ( 3775): Stopping oneshot timer
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1857873588305; DSPS: 61020026; Offset : -4321981270
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1877875444340; DSPS: 61675447; Offset : -4321986884
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/LocationManagerService( 1046): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1897877129071; DSPS: 62330862; Offset : -4321980412
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1917879090938; DSPS: 62986287; Offset : -4322002293
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1937881094734; DSPS: 63641712; Offset : -4321982139
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1957882811340; DSPS: 64297129; Offset : -4322005087
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1977884478206; DSPS: 64952543; Offset : -4321986118
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 1997886156742; DSPS: 65607958; Offset : -4321986048
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2017887519077; DSPS: 66263363; Offset : -4321997135
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2037889393547; DSPS: 66918784; Offset : -4321984107
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{21df6e83 type 2 when 2054129 android} when 2054129
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,I/BooksSync( 6904): Starting books sync
D/BooksSync( 6904): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8939336460874016835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 42537(2021KB) AllocSpace objects, 17(1025KB) LOS objects, 33% free, 44MB/66MB, paused 3.112ms total 191.152ms
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8939336460874016835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2057893698541; DSPS: 67574285; Offset : -4321980060
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6904): Authentication error
E/BooksAccountManager( 6904): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6904): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6904): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6904): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6904): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{3a0ff09f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6904): Error response from books API: {
W/ApiaryClient( 6904):  "error": {
W/ApiaryClient( 6904):   "errors": [
W/ApiaryClient( 6904):    {
W/ApiaryClient( 6904):     "domain": "global",
W/ApiaryClient( 6904):     "reason": "required",
W/ApiaryClient( 6904):     "message": "Login Required",
W/ApiaryClient( 6904):     "locationType": "header",
W/ApiaryClient( 6904):     "location": "Authorization"
W/ApiaryClient( 6904):    }
W/ApiaryClient( 6904):   ],
W/ApiaryClient( 6904):   "code": 401,
W/ApiaryClient( 6904):   "message": "Login Required"
W/ApiaryClient( 6904):  }
W/ApiaryClient( 6904): }
,W/ApiaryClient( 6904): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8939336460874016835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6904): Headers:
W/ApiaryClient( 6904): accept-encoding: [gzip]
W/ApiaryClient( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6904): gdata-version: 2
E/BooksSync( 6904): Soft error: 
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8939336460874016835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
,E/BooksSync( 6904): Sync error
E/BooksSync( 6904): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6904): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8939336460874016835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6904): Headers:
E/BooksSync( 6904): accept-encoding: [gzip]
E/BooksSync( 6904): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6904): gdata-version: 2
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6904): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6904): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6904): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6904): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6904): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6904): {
E/BooksSync( 6904):  "error": {
E/BooksSync( 6904):   "errors": [
E/BooksSync( 6904):    {
E/BooksSync( 6904):     "domain": "global",
E/BooksSync( 6904):     "reason": "required",
E/BooksSync( 6904):     "message": "Login Required",
E/BooksSync( 6904):     "locationType": "header",
E/BooksSync( 6904):     "location": "Authorization"
E/BooksSync( 6904):    }
E/BooksSync( 6904):   ],
E/BooksSync( 6904):   "code": 401,
E/BooksSync( 6904):   "message": "Login Required"
E/BooksSync( 6904):  }
E/BooksSync( 6904): }
E/BooksSync( 6904): 
E/BooksSync( 6904): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6904): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6904): 	... 8 more
I/BooksSync( 6904): Finished books sync
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2054129, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2077895442909; DSPS: 68229703; Offset : -4322007770
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=1022309295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{2c403bd5 type 2 when 2084977 android} when 2084977
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=1022309295 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2097897759828; DSPS: 68885139; Offset : -4322010055
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 2117899108206; DSPS: 69540543; Offset : -4322004504
,TIME-OUT KILL (timeout was 1800000ms)
```
