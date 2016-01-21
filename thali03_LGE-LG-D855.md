#### Test 56449660bb41d23_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1443): called onTimeUpdated()
I/LgeClockWidgetControlView( 1443): called onTimeUpdated()
I/[SystemUI]DateView( 1443): called onTimeUpdated()
I/[SystemUI]DateView( 1443): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1443): handleTimeUpdate
,D/AndroidRuntime( 7154): 
D/AndroidRuntime( 7154): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7154): CheckJNI is OFF
D/AndroidRuntime( 7154): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1034): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1034): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{28f0a4a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{28f0a4a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1034): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1034): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7174 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7154): Shutting down VM
V/ActivityManager( 1034): Display changed displayId=0
D/DSDPConnection( 1855): Display #0 changed.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{169c2639 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{3d37d47e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7174): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7174): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7174): Loading: webviewchromium
I/LibraryLoader( 7174): Time to load native libraries: 4 ms (timestamps 5522-5526)
I/LibraryLoader( 7174): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7174): Binding Chromium to main looper Looper (main, tid 1) {3bed5429}
I/LibraryLoader( 7174): Expected native library version number "",actual native library version number ""
I/chromium( 7174): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7174): Initializing chromium process, renderers=0
W/art     ( 7174): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb144b060, uid 10311
D/BluetoothManagerService( 1034): Message: 20
W/chromium( 7174): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7174): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7174): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7174): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7174): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7174): Build Date: 12/12/14 금
I/Adreno-EGL( 7174): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7174): Remote Branch: 
I/Adreno-EGL( 7174): Local Patches: 
I/Adreno-EGL( 7174): Reconstruct Branch: 
W/chromium( 7174): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7174): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7174): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7174): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7174): CordovaWebView is running on device made by: LGE
I/art     ( 1034): Explicit concurrent mark sweep GC freed 25641(1109KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.978ms total 150.453ms
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c659787:true
W/art     ( 7174): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7174): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7174): Render dirty regions requested: true
I/OpenGLRenderer( 7174): Initialized EGL, version 1.4
D/OpenGLRenderer( 7174): Enabling debug mode 0
W/ActivityManager( 1034): Activity pause timeout for ActivityRecord{2b461dbb u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 7174): Validating map...
D/SplitWindow( 1034): check instance of lgWin Window{18bd1d9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7174): LgDataFeature() Constructor: none
D/LgDataFeature( 7174): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1443): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@abd84d4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1443): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1443):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1443): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1034): Displayed com.test.thalitest/.MainActivity: +640ms (total +720ms)
I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{2b461dbb u0 com.test.thalitest/.MainActivity t4} time:275945
I/Timeline( 7174): Timeline: Activity_idle id: android.os.BinderProxy@3aa69999 time:275950
I/chromium( 7174): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7174): 
D/JsMessageQueue( 7174): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7174): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435100416
I/chromium( 7174): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7174): 
I/chromium( 7174): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
,I/GBMv2   (  345): DFP Enabled. Ignore VFP set
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 276895771826; DSPS: 9214098; Offset : -4308303894
,W/jxcore-log( 7174): Initializing JXcore engine
W/jxcore-log( 7174): JXcore engine is ready
I/art     ( 7174): Background sticky concurrent mark sweep GC freed 133295(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.726ms total 130.842ms
W/Thread-819( 7244): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9258]" dev="sockfs" ino=9258 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-819( 7244): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-819( 7244): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9052]" dev="sockfs" ino=9052 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-819( 7244): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-819( 7244): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[35043]" dev="sockfs" ino=35043 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7174): Starting JXcore engine
W/jxcore-log( 7174): Platform android
W/jxcore-log( 7174): 
W/jxcore-log( 7174): Process ARCH arm
W/jxcore-log( 7174): 
,I/jxcore-log( 7174): JXcore Cordova bridge is ready!
I/jxcore-log( 7174): 
W/jxcore-log( 7174): JXcore engine is started
,I/jxcore-log( 7174): Toggling radios to true
I/jxcore-log( 7174): 
,D/BluetoothAdapter( 7174): enable(): BT is already enabled..!
D/WifiService( 1034): New client listening to asynchronous messages
D/WifiServiceImplEx( 1034): setWifiEnabled: true pid=7174, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1034): setWifiEnabled: true pid=7174, uid=10311
E/WifiService( 1034): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1034): disconnect pid=7174, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1034): reconnect pid=7174, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1034):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1034): [278,860,716 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
I/jxcore-log( 7174): Radios toggled
I/jxcore-log( 7174): 
D/WifiNative-wlan0( 1034): doBoolean: DISCONNECT
I/jxcore-log( 7174): My device name is: LGE-LG-D855
I/jxcore-log( 7174): 
,I/wpa_supplicant( 2608): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1034): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1034): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1034): InitialState.processMessage what=4
D/Tethering( 1034): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1034): DISCONNECT: returned true
E/WifiStateMachine( 1034): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
D/CommandListener(  312): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1034): RunningState{ when=-19ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1034): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7267 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2116): Read error: ssl=0xaa6ea800: I/O error during system call, Connection timed out
,V/NativeCrypto( 2116): SSL shutdown failed: ssl=0xaa6ea800: I/O error during system call, Broken pipe
E/WifiStateMachine( 1034): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1034):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1034): [279,035,982 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1034): doBoolean: RECONNECT
,I/wpa_supplicant( 2608): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1034): ignoring duplicate network state non-change
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1034): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1034): RECONNECT: returned true
E/WifiStateMachine( 1034):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279049
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279050
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1034): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/CommandListener(  312): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1034): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1034): disableDataServiceNotify
D/DSQN    ( 1034): stop dsqn bin
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1034): hidePasspointNotification off =false
E/WifiStateMachine( 1034):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279092  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1034): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Disconnected - quitting
D/CSLegacyTypeTracker( 1034): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1034): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandle,r( 1443): CM callback handler got msg 524292
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
,E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279100  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
,D/NetworkManagementService( 1034): Removing idletimer
W/Settings( 1034): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1034): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279104  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNetworkAgent( 1034): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1034): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateSCANNING
,D/TelephonyIcons( 1443): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7267): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TelephonyIcons( 1443): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7267): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1034): StoppedState
D/DhcpStateMachine( 1034): StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7267): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7267): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7267): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7267): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7267): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7267): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1034): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7301 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 6602:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10004/pid_6602/cgroup.procs: No such file or directory
,I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7267): LgDataFeature() Constructor: none
,D/LgDataFeature( 7267): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
,I/ActivityManager( 1034): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7322 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1034): Killing 6725:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=220158153, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
W/libprocessgroup( 1034): failed to open /acct/uid_10008/pid_6725/cgroup.procs: No such file or directory
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{d6d159b type 0 when 1453391059748 android} when 1453391059748
V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{4e99d38 type 2 when 279644 com.google.android.gms} when 279644
,D/[Concierge]Service( 2610): onStartCommand(). Type : 9
,W/ResourcesManager( 7322): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 7322): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7322): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7322): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7322): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7322): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7322): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7322): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7322): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7322): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7322): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,E/WifiStateMachine( 1034):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:216013] from screen [on:0 period:1692114532]
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=220158153 [*alarm*], flags=0x0
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/QRemote ( 7322): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7322): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7322): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7322): LgDataFeature() Constructor: none
D/LgDataFeature( 7322): LgDataFeature() Constructor Done, null
,V/SoundPool( 7322): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7322): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7322): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7322): doLoad: loading sample sampleID=1
I/QRemote ( 7322): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6869): QS Service created
,V/SoundPool( 7322): Start decode
V/MediaPlayer[Native]( 7322): decode(31, 10857164, 17813)
D/QRemote ( 7322): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb11639c0, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6869): Service initServices...
D/UEI.SmartControl( 6869): QS start get config
E/QRemote ( 7322): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7322): Create singleton instance
,V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
V/OMXCodec(  316): setComponentRole
,V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb11639c0, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb11639c0, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vo,rbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb119a060 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb11639c0, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae904000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae905000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae906000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae907000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae908000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae909000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90a000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90b000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90c000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90d000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90e000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae90f000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae910000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae911000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae912000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae913000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae914000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae915000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae916000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae917000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae918000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae919000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91a000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91b000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91c000, 0xb12c1000, 4096)
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91d000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91e000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae91f000, 0xb12c1000, 4096)
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae920000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae921000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae922000, 0xb12c1000, 4096)
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3741
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae923000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae924000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae925000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae926000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae927000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae928000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae929000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92a000, 0xb12c1000, 4096)
,V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92b000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92c000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92d000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92e000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae92f000, 0xb12c1000, 4096)
,V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae930000, 0xb12c1000, 4096)
,V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae931000, 0xb12c1000, 4096)
V/AudioCache(  316): write(0xb12c1000, 4096)
,V/AudioCache(  316): memcpy(0xae932000, 0xb12c1000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae933000, 0xb12c1000, 4096)
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae934000, 0xb12c1000, 4096)
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  316): write(0xb12c1000, 4096)
V/AudioCache(  316): memcpy(0xae935000, 0xb12c1000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb12c1000, 280)
V/AudioCache(  316): memcpy(0xae936000, 0xb12c1000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb11639c0, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb11639c0, 7, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): wait - success
V/AwesomePlayer(  316): cancelPlayerEvents
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb11639c0, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb119a060 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7322): close(31)
V/SoundPool( 7322): pointer = 0x9fe7a000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6869): Supports setup maps: true
D/UEI.SmartControl( 6869): QS start statue = true Error code = 0
I/UEI.SmartControl( 6869): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6869): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6869): ### init IR Blaster...
,D/serial_port( 6869): Configuring serial port
,E/UEI.SmartControl( 6869): UEIBLaster setting for 616
I/UEI.SmartControl( 6869): Setting serial record hearder size = 2
I/UEI.SmartControl( 6869): configuring settings for MAXQ616
I/UEI.SmartControl( 6869): Get version...
D/UEI.SmartControl( 6869): serial port data available: 21
,D/UEI.SmartControl( 6869): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6869): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6869): QS saving settings...
D/UEI.SmartControl( 6869): IR Blaster version: 25672567
,D/UEI.SmartControl( 6869): serial port data available: 4
,I/UEI.SmartControl( 6869): Device manager: loading config....
,W/ContextImpl( 6869): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 6869): ----------- loading internal config...
E/UEI.SmartControl( 6869): Services init done
D/UEI.SmartControl( 6869): QS Service init finished
D/UEI.SmartControl( 6869): QS Service version name: 2.1.91
D/UEI.SmartControl( 6869): QS Service version code: 201091
D/UEI.SmartControl( 6869): Service requested: Control
E/UEI.SmartControl( 6869): Loading SETTINGS...
D/UEI.SmartControl( 6869): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6869): Internal service binding...
I/QRemote ( 7322): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6869): ------ IControl API: 11
D/UEI.SmartControl( 6869): File observer start...
E/UEI.SmartControl( 6869): IR Port is disabled: false
D/UEI.SmartControl( 6869): Starting file observer...
I/UEI.SmartControl( 6869): Registering callback...
I/UEI.SmartControl( 6869): ------ IControl API: 19
D/UEI.SmartControl( 6869): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6869): Registering Services Ready callback...
I/UEI.SmartControl( 6869): Notify AllClients services are ready: 0
,I/QRemote ( 7322): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7322): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7322): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6869): -----service ready thread exits
D/QRemote ( 7322): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7322): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6869): ------ IControl API: 8
D/QRemote ( 7322): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7322): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7322): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7322): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7322): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7322): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7322): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,D/QRemote ( 7322): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1034): Killing 6132:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10011/pid_6132/cgroup.procs: No such file or directory
,V/QRemote ( 7322): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7322): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7322): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453391061214]
,D/QRemote ( 7322): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 7322): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7322): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7322): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1034): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1034): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2608): Trying to associate with SSID 'NG700'
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1034):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1034):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1034):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1034):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1034): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281107  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281129  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
,D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2608): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1034): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1034): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281217  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281217  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1034):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281217
E/WifiStateMachine( 1034):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281218
E/WifiStateMachine( 1034):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281218
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281218
E/WifiStateMachine( 1034):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281218
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281218  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 7267): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7267): [AUTORUN] sys.usb.state = ptp_only,adb
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbSettingsReceiver( 7267): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281227  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1034):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 2608): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2608): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1034): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1034): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281236  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281236  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1034):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281237
D/WifiServerServiceExt( 1034): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281237
D/WifiNative-wlan0( 1034): doString: [STATUS]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1034):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServiceExtension( 1034): setVHTCapabilityType  : false
D/UsbSettingsControl( 7267): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7267): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsReceiver( 7267): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7267): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1034): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1034): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1034): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1034): Got NetworkAgent Messenger
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1034): NetworkAgent connected
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
,D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{7d7dcac type 2 when 281279 com.google.android.gms} when 281279
D/CommandListener(  312): Setting iface cfg
E/WifiStateMachine( 1034): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1034): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): WaitBeforeStartState
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281282  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281282  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281282  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1034):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 0
D/WifiNative-wlan0( 1034): SET ps 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1034): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c1887d4 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c1887d4 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): DHCP Start wake lock is acquired.
D/CommandListener(  312): Setting iface cfg
D/CommandListener(  312): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1034): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
E/WifiStateMachine( 1034):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2608): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/WifiNative-wlan0( 1034): SET ps 1: returned true
E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1034):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1034): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1034): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1034): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1443): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1034): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1443): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1443): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1034): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1034): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1034): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  312): netlink response contains error (File exists)
D/ConnectivityService( 1034): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/ConnectivityService( 1034): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1034): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1034): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1034): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1034): currentScore = 0, newScore = 20
D/ConnectivityService( 1034):    accepting network in place of null
D/ConnectivityService( 1034): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1034): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1034): Sending connecte,d broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1034): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1034): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1034): validation of new default Network = false
D/ConnectivityService( 1034): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1034): enableDataServiceNotify 
D/DSQN    ( 1034): start dsqn bin
D/LocSvc_java( 1034): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1443): CM callback handler got msg 524290
W/dsqn    ( 7382): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7382): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/NetworkPolicy( 1034): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7382): DSQN ssw
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
,D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7322): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1443): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7322): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7322): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7322): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7267): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7267): MCCMNC not supported: null
D/QRemote ( 7322): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7322): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7322): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7322): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7322): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  312): argv[0]=dsqncommand
D/LGDataListener(  312): argv[1]=wlan0
,D/LGDataListener(  312): argv[2]=1
D/LGDataListener(  312): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1034): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1034): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 15:44:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453391061960], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453391061938]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Validated
D/ConnectivityService( 1034): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1443): CM callback handler got msg 524290
D/ConnectivityService( 1034): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1034): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DhcpStateMachine( 1034): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1034): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1034): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7388): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7388): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7388): version 5.5.6 starting
,E/dhcpcd  ( 7388): get_duid: m
D/dhcpcd  ( 7388): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7388): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1443): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1443): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7388): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7388): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7388): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7388): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7388): wlan0: sending REQUEST (xid 0xde112f16), next in 3.83 seconds
,D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5479): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5479): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1034): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7419 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7419): onCreate
,W/AppUp4:DB( 7419):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7419):  setFingerPrint start
I/AppUp4:DB( 7419):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7419):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7419):  SDK version = 21
I/AppUp4:DB( 7419):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7419): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7419): onReceive
D/LgDataFeature( 7419): LgDataFeature() Constructor: none
D/LgDataFeature( 7419): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7419): Context : android.app.ReceiverRestrictedContext@c6454f
D/AppUp4:CustFacade( 7419): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7419): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7419): begin check event
I/AppUp4:CustModeStarterReceiver( 7419): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7419): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7419): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7419): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7419): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1034): Killing 6154:com.android.contacts/u0a19 (adj 15): empty #17
D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1034): failed to open /acct/uid_10019/pid_6154/cgroup.procs: No such file or directory
,D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4303): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3352): DownloadService onCreate
I/LGDMClient( 4303): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3352): in removeSpuriousFiles
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3c2f84c3 on behalf of 3352
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
E/LGDMClient( 4303): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4303): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4303): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@c812140 on behalf of 3352
V/DownloadManager( 3352): DownloadService onStartCommand
V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@efbaa1f on behalf of 3352
,D/eas_req ( 6750): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3352): processing inserted download 1
V/DownloadManager( 3352): processing inserted download 4
V/DownloadManager( 3352): processing inserted download 7
V/DownloadManager( 3352): processing inserted download 8
V/DownloadManager( 3352): processing inserted download 9
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
V/DownloadManager( 3352): processing inserted download 17
V/DownloadManager( 3352): processing inserted download 18
,V/DownloadManager( 3352): processing inserted download 21
V/DownloadManager( 3352): processing inserted download 22
V/DownloadManager( 3352): DownloadService onDestroy
I/ActivityManager( 1034): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7449 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6750): JNI_OnLoad()
I/HubEmail( 6750): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6750): registerNatives()
I/HubEmail( 6750): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6750): registerNativeMethods()
I/HubEmail( 6750): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6750): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 33.387ms
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.242ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 18.259ms
,I/LgeMiscReceiver( 3313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3313): networkInfo.isConnected() = false
I/ActivityManager( 1034): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7472 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7388): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7388): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7388): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7388): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7388): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7388): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7388): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7388): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7388): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7449): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7449): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1034): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7505 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 6785:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10027/pid_6785/cgroup.procs: No such file or directory
,I/ActivityManager( 1034): Killing 6807:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7174): 
,E/WifiStateMachine( 1034):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1034): identical MTU - not setting
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1034): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1443): CM callback handler got msg 524295
D/DhcpStateMachine( 1034): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1034): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1034): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1034): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1034): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1034): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1034): RunningState
,I/ActivityManager( 1034): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7530 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6843:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10061/pid_6807/cgroup.procs: No such file or directory
,W/libprocessgroup( 1034): failed to open /acct/uid_10080/pid_6843/cgroup.procs: No such file or directory
,I/art     ( 7530): Almond Protected OAT
,D/WeatherApplication( 7530): removeAccount
,D/WeatherApplication( 7530): Account.length = 0
E/WeatherApplication( 7530): OPERATOR:OPEN
D/WeatherAncestor( 7530): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:24
D/Weather.Utils( 7530): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7530): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7530): 2 : This is isUpdating : false
D/WeatherAncestor( 7530): connectivity changed - connection : true
D/WeatherService( 7530): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7530): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7530): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7530): 2 : Cache is not up-to-date, count: 0
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{12e1c8dc type 2 when 283640 com.google.android.gms} when 283640
D/Weather_cast( 7530): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7530): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:24
I/ActivityManager( 1034): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7551 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6928:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6928/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7174): 
,I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7174): 
E/WifiStateMachine( 1034):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7174): 
,I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7174): 
,I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7174): 
,I/WebViewFactory( 7551): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7551): Loading: webviewchromium
I/LibraryLoader( 7551): Time to load native libraries: 2 ms (timestamps 4106-4108)
I/LibraryLoader( 7551): Expected native library version number "",actual native library version number ""
I/jxcore-log( 7174): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7174): 
,V/WebViewChromiumFactoryProvider( 7551): Binding Chromium to main looper Looper (main, tid 1) {233a7136}
I/LibraryLoader( 7551): Expected native library version number "",actual native library version number ""
I/chromium( 7551): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7551): Initializing chromium process, renderers=0
W/art     ( 7551): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7551): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7551): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7551): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  316): registerClient() client 0xb1004da0, uid 10093
I/Adreno-EGL( 7551): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7551): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7551): Build Date: 12/12/14 금
I/Adreno-EGL( 7551): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7551): Remote Branch: 
I/Adreno-EGL( 7551): Local Patches: 
I/Adreno-EGL( 7551): Reconstruct Branch: 
W/AudioManagerAndroid( 7551): Requires BLUETOOTH permission
,I/NSApplication( 7551): Starting up...
,I/ActivityManager( 1034): Killing 6037:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,V/WifiInternetCheck( 1034): Single check msg out of sync, ignoring.
,W/libprocessgroup( 1034): failed to open /acct/uid_10005/pid_6037/cgroup.procs: No such file or directory
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1034): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5479): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7419): onReceive
,D/AppUp4:CustFacade( 7419): Context : android.app.ReceiverRestrictedContext@c6454f
D/AppUp4:CustFacade( 7419): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7419): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7419): begin check event
I/AppUp4:CustModeStarterReceiver( 7419): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3352): DownloadService onCreate
I/DownloadManager( 3352): in removeSpuriousFiles
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3098335 on behalf of 3352
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,D/LGDMClient( 4303): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@210533ca on behalf of 3352
I/LGDMClient( 4303): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3313): networkInfo.isConnected() = false
W/Settings( 6750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7530): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:24
D/Weather.Utils( 7530): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7530): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7530): 2 : This is isUpdating : false
D/WeatherAncestor( 7530): connectivity changed - connection : true
D/WeatherService( 7530): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@24de09e5
D/ForecastDataCache( 7530): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7530): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7530): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 7530): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7530): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:24
V/DownloadManager( 3352): DownloadService onStartCommand
,V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@1b5c1db1 on behalf of 3352
E/LGDMClient( 4303): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4303): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4303): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3352): processing inserted download 1
V/DownloadManager( 3352): processing inserted download 4
V/DownloadManager( 3352): processing inserted download 7
,V/DownloadManager( 3352): processing inserted download 8
V/DownloadManager( 3352): processing inserted download 9
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
V/DownloadManager( 3352): processing inserted download 17
V/DownloadManager( 3352): processing inserted download 18
I/art     ( 2116): Explicit concurrent mark sweep GC freed 41524(2MB) AllocSpace objects, 12(1472KB) LOS objects, 51% free, 30MB/62MB, paused 1.280ms total 75.809ms
,V/DownloadManager( 3352): processing inserted download 21
V/DownloadManager( 3352): processing inserted download 22
V/DownloadManager( 3352): DownloadService onDestroy
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/ResourcesManager( 1403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7419): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7419): onReceive
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/AppUp4:CustFacade( 7419): Context : android.app.ReceiverRestrictedContext@c6454f
D/AppUp4:CustFacade( 7419): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7419): isPhone : true
V/FormManager( 7449): There are no updated forms. The schedule will be deleted.
D/AppUp4:CustModeStarterReceiver( 7419): begin check event
I/AppUp4:CustModeStarterReceiver( 7419): Event For GoodConnectivity, noConnectivity : false, but skip! 
,W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4303): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{2282be17 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7449): Alarm would be updated, because LastCheckTime has been updated.
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3352): DownloadService onCreate
D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4303): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4303): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3352): DownloadService onStartCommand
V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  312): res_queryN name = mtalk.google.com succeed
I/LgeMiscReceiver( 3313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3313): networkInfo.isConnected() = true
D/PhoneState( 3313): setPdpRejectCasuse : false
I/DownloadManager( 3352): in removeSpuriousFiles
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4303): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@1a63e3ed on behalf of 3352
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LgeQuickCoverNLService( 1403): onNotificationPosted
W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@22487222 on behalf of 3352
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@13eb24b3 on behalf of 3352
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
W/Settings( 6750,): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
V/DownloadManager( 3352): processing inserted download 1
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
,V/DownloadManager( 3352): processing inserted download 4
W/Settings( 6750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7530): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:25
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LGDMClient( 4303): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3352): processing inserted download 7
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/LGDMClient( 4303): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4303): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3352): processing inserted download 8
D/Weather.Utils( 7530): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7530): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7530): 2 : This is isUpdating : false
D/WeatherAncestor( 7530): connectivity changed - connection : true
D/WeatherService( 7530): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@24de09e5
V/DownloadManager( 3352): processing inserted download 9
D/ForecastDataCache( 7530): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7530): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7530): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7530): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7530): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:44:25
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
V/DownloadManager( 3352): processing inserted download 17
V/DownloadManager( 3352): processing inserted download 18
,V/DownloadManager( 3352): processing inserted download 21
V/DownloadManager( 3352): processing inserted download 22
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{2282be17 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3352): DownloadService onDestroy
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7449): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7449): Alarm would be updated, because LastCheckTime has been updated.
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 94574(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 6.742ms total 117.373ms
,D/GCM     ( 2116): Connected
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 2116): Message class com.google.f.a.a.p
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{2282be17 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.google.com, class = 1, type = 1
,D/UEI.SmartControl( 6869): Internal timer expired: 4
D/UEI.SmartControl( 6869): unbind internal service
,D/libc-netbsd(  312): res_queryN name = www.google.com succeed
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
D/serial_port( 6869): close(fd = 24)
,I/UEI.SmartControl( 6869): Serial port is closed.
V/WifiInternetCheck( 1034): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7551): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7174): Test app app.js loaded
I/jxcore-log( 7174): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7174): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7174): BLE advertisement is supported
I/jxcore-log( 7174): 
I/chromium( 7174): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7174): --= Surplus to requirements =--
I/jxcore-log( 7174): 
I/jxcore-log( 7174): ****TEST TOOK:  ms ****
I/jxcore-log( 7174): 
I/jxcore-log( 7174): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7174): 
,D/AndroidRuntime( 7671): 
D/AndroidRuntime( 7671): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7671): CheckJNI is OFF
D/AndroidRuntime( 7671): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1034): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1034): Killing 7174:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1034): WIN DEATH: Window{18bd1d9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1034): Client connection lost with reason: 4
D/InputDispatcher( 1034): Window went away: Window{18bd1d9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1034): Skipping PackageSetting{20669d4 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1034):   Force finishing activity ActivityRecord{2b461dbb u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
W/ActivityManager( 1034): Spurious death for ProcessRecord{9c17b59 7174:com.test.thalitest/u0a311}, curProc for 7174: null
I/ActivityManager( 1034): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1034):   Force finishing activity ActivityRecord{2b461dbb u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1034): Duplicate finish request for ActivityRecord{2b461dbb u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2070): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{2af80ddf co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{39520a2c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2070): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2070): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2070): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/ActionManagerService( 1916): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3719): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2070): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1443): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2018): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3719): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,W/System.err( 4552): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4552): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4552): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4552): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4552): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4552): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4552): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4552): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4602): Explicit concurrent mark sweep GC freed 16275(921KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 933us total 62.192ms
I/InputReader( 1034): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGActivityUtil( 2070): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/SplitUIManager( 1872): split_name #11 / not available #0
D/SplitUIService( 1872): removed split : 
,D/PostponalbeReceiver( 6689): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1034): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7703 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2070): [Launcher.java:1056:onResume()]onResume end
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
I/[SystemUI]QSlideListController( 1443): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2070): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1916): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2070): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3719): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3719): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2070): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2070): , create_time: 1430558575574
I/GBoardWebViewUtils( 2070): , expire_time: 0
I/GBoardWebViewUtils( 2070): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2070): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2070): , display: false
I/GBoardWebViewUtils( 2070): , animation: false }
I/GBoardWebViewUtils( 2070): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2070): , create_time: 1430558575600
I/GBoardWebViewUtils( 2070): , expire_time: 0
I/GBoardWebViewUtils( 2070): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2070): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2070): , display: false
I/GBoardWebViewUtils( 2070): , animation: false }
I/GBoardWebViewUtils( 2070): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2070): , create_time: 1453384801850
I/GBoardWebViewUtils( 2070): , expire_time: 0
I/GBoardWebViewUtils( 2070): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2070): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2070): , display: false
I/GBoardWebViewUtils( 2070): , animation: false }
,D/WallpaperManager( 2070): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@abd84d4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1443): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1443): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1872): split_name #11 / not available #0
I/SplitUIService( 1872): split app #11
I/[LGHome]GBoardWebView( 2070): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 15894(1158KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.105ms total 225.765ms
I/art     ( 1034): WaitForGcToComplete blocked for 207.239ms for cause Explicit
I/LockScreenSettings( 7703): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1443): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1443): createShortcutInfo...
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
D/administrator( 1034): Handling package changes for user 0
D/KeyguardModel( 1443): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1443): createShortcutInfo...
,W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1443): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1443): createShortcutInfo...
,W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1443): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1443): createShortcutInfo...
W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2070): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/AppUp4:PreloadHelper( 7419): added Exclude : com.test.thalitest
W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1443): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1443): createShortcutInfo...
,I/ActivityManager( 1034): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7723 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityManager( 1034): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] [-] updateMediaPlayerInfo
I/ActivityManager( 1034): Killing 6962:com.lge.bnr/1000 (adj 15): empty #17
I/[LGHome]EVENT( 2070): [Launcher.java:5349:onStop()]onStop
I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3121): Thermal-Lib-Client: Client request sent
I/NotificationService( 1034): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService( 1034): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1034): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 1034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LGHome]Launcher.Model( 2070): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
W/ResourceType( 1034): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1443): handleShortcutListChanged...
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 5849(313KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.005ms total 211.838ms
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6962/cgroup.procs: No such file or directory
I/[LGHome]Launcher.Model( 2070): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2070): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2070): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/TaskPersister( 1034): removeObsoleteFile: deleting file=4_task.xml
,D/PhoneStatusBar( 1443): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1443): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1443):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1443): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{2822dedf u0 com.lge.launcher2/.Launcher t3} time:291414
D/KeyguardModel( 1443): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1443): createShortcutInfo...
D/KeyguardModel( 1443): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1443): createShortcutInfo...
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1443): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1443): createShortcutInfo...
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1443): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1443): createShortcutInfo...
W/ResourceType( 1443): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1443): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1443): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1443): createShortcutInfo...
,I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]EVENT( 2070): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/KeyguardModel( 1443): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2070): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7723): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2070): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2610): onStartCommand(). Type : 8
D/[Concierge]Service( 2610): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2610): Update widget ID : 11
D/[Concierge]WidgetView( 2070): change position of spinner
D/[Concierge]Service( 2610): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2070): initWebView(). Time : 1453391071899
,I/[Concierge]WebView( 2070): Return exist ConciergeWebView. Reuse : 671140141
D/[Concierge]WidgetView( 2070): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2070): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2070): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2d346715
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2070): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/SystemConfig( 7723): BUILD Country: EU
I/SystemConfig( 7723): BUILD Operator: OPEN
D/[Concierge]WidgetView( 2070): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2070): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2070): Widget kill message received. Destory myself. My : 1453390807902, New one : 1453391071899
D/[Concierge]WidgetView( 2070): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2070): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
D/AndroidRuntime( 7671): Shutting down VM
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2070): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2070): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2070): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1034): Killing 7020:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/Timeline( 2070): Timeline: Activity_idle id: android.os.BinderProxy@1563fa0 time:291552
I/chromium( 2070): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/libprocessgroup( 1034): failed to open /acct/uid_10054/pid_7020/cgroup.procs: No such file or directory
I/SystemConfig( 7723): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7723): existFile = false
I/SystemConfig( 7723): canReadFile = false
I/SystemConfig( 7723): systemFeature RCS result false
D/SystemConfig( 7723): refreshRcsSupport() :false
I/PackageChangeReceiver( 6750): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2178): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1034): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7746 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/GBoardtInterface( 2070): onReloaded()
,I/GBoardWebViewClient( 2070): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3719): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3719): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1916): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3719): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3719): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1916): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3719): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3719): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3719): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3719): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3719): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2070): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2070): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2070): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2070): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2070): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2070): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ResourcesManager( 7746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7746): Total System Memory = 2995761152
,D/SystemHelper( 7746): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7746): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1034): Killing 6265:com.android.vending/u0a44 (adj 15): empty #17

```
