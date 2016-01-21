#### Test 568182548138a64_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1053): tsOffsetIs: Apps: 277520922677; DSPS: 9235003; Offset : -4322735904
,D/AndroidRuntime( 7134): 
D/AndroidRuntime( 7134): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7134): CheckJNI is OFF
D/AndroidRuntime( 7134): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1053): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1936): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1053): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1053): setTaskToReturnTo : TaskRecord{1b7068f8 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1053): setTaskToReturnTo : TaskRecord{1b7068f8 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1053): AppWindowTokenEx init.. 
E/GBMv2   (  334): DFP En is all cleared set to be enabled
I/ActivityManager( 1053): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7154 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7134): Shutting down VM
V/ActivityManager( 1053): Display changed displayId=0
D/DSDPConnection( 1846): Display #0 changed.
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{3c710587 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{3938acb4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7154): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7154): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7154): Loading: webviewchromium
I/LibraryLoader( 7154): Time to load native libraries: 3 ms (timestamps 3482-3485)
I/LibraryLoader( 7154): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7154): Binding Chromium to main looper Looper (main, tid 1) {3e1ca6f7}
,I/LibraryLoader( 7154): Expected native library version number "",actual native library version number ""
I/chromium( 7154): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7154): Initializing chromium process, renderers=0
,W/art     ( 7154): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  317): registerClient() client 0xb57d0ba0, uid 10311
,D/BluetoothManagerService( 1053): Message: 20
D/BluetoothManagerService( 1053): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3417dc2:true
W/chromium( 7154): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7154): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7154): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7154): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7154): Build Date: 12/12/14 금
I/Adreno-EGL( 7154): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7154): Remote Branch: 
I/Adreno-EGL( 7154): Local Patches: 
I/Adreno-EGL( 7154): Reconstruct Branch: 
,W/chromium( 7154): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7154): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7154): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7154): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7154): CordovaWebView is running on device made by: LGE
,W/art     ( 7154): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7154): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7154): Render dirty regions requested: true
I/OpenGLRenderer( 7154): Initialized EGL, version 1.4
D/OpenGLRenderer( 7154): Enabling debug mode 0
D/Atlas   ( 7154): Validating map...
,D/SplitWindow( 1053): check instance of lgWin Window{2a384c6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7154): LgDataFeature() Constructor: none
D/LgDataFeature( 7154): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1053): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1053): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1053): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1053): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1053): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ecedb09,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1053): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1053): Displayed com.test.thalitest/.MainActivity: +496ms (total +584ms)
I/Timeline( 1053): Timeline: Activity_windows_visible id: ActivityRecord{16a871d1 u0 com.test.thalitest/.MainActivity t4} time:283863
,I/Timeline( 7154): Timeline: Activity_idle id: android.os.BinderProxy@80f3be7 time:283878
,D/JsMessageQueue( 7154): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7154): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7154): 
,D/jxcore_app_log( 7154): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435073280
I/chromium( 7154): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7154): 
,I/chromium( 7154): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
I/GBMv2   (  334): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7154): Initializing JXcore engine
W/jxcore-log( 7154): JXcore engine is ready
,W/Thread-828( 7205): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10406]" dev="sockfs" ino=10406 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-828( 7205): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-828( 7205): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7668]" dev="sockfs" ino=7668 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-828( 7205): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-828( 7205): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33602]" dev="sockfs" ino=33602 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7154): Starting JXcore engine
,I/art     ( 7154): Background sticky concurrent mark sweep GC freed 133366(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.200ms total 137.098ms
,W/jxcore-log( 7154): Platform android
W/jxcore-log( 7154): 
W/jxcore-log( 7154): Process ARCH arm
W/jxcore-log( 7154): 
,I/jxcore-log( 7154): JXcore Cordova bridge is ready!
I/jxcore-log( 7154): 
,W/jxcore-log( 7154): JXcore engine is started
I/jxcore-log( 7154): Toggling radios to true
I/jxcore-log( 7154): 
,D/BluetoothAdapter( 7154): enable(): BT is already enabled..!
D/WifiService( 1053): New client listening to asynchronous messages
D/WifiServiceImplEx( 1053): setWifiEnabled: true pid=7154, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1053): setWifiEnabled: true pid=7154, uid=10311
E/WifiService( 1053): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1053): disconnect pid=7154, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1053): reconnect pid=7154, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1053):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7154): Radios toggled
I/jxcore-log( 7154): 
E/WifiStateMachine( 1053):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7154): My device name is: LGE-LG-D855
I/jxcore-log( 7154): 
E/WifiNative: ( 1053): [286,794,558 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1053): doBoolean: DISCONNECT
I/wpa_supplicant( 2624): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1053): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1053): InitialState.processMessage what=4
D/Tethering( 1053): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1053): DISCONNECT: returned true
E/WifiStateMachine( 1053): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1053): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1053): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1053): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1053): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1053): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1053): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1053): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1053): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1053): doBoolean: SET ps 1
D/LGWifiP2pService( 1053): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1053): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1053): SET ps 1: returned true
D/DhcpStateMachine( 1053): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Clearing all IP addresses on wlan0
V/NativeCrypto( 2066): Read error: ssl=0xaf4d6600: I/O error during system call, Connection timed out
,I/ActivityManager( 1053): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7216 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/ConnectivityService( 1053): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1053): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1053): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1936): handleWifiStateChangedEvent: 0
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1053): hidePasspointNotification off =false
E/WifiStateMachine( 1053): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1053):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1053):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1053): [286,936,842 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1053): doBoolean: RECONNECT
I/wpa_supplicant( 2624): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1053): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1053): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1053): RECONNECT: returned true
E/WifiStateMachine( 1053):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1053):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1053):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1053):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1053):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286941
E/WifiStateMachine( 1053):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286941
D/LGWifiP2pService( 1053): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1053): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1053): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1053): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1053): doBoolean: SET ps 1
D/WifiNative-wlan0( 1053): SET ps 1: returned true
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/ConnectivityService( 1053): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1053): disableDataServiceNotify
D/DSQN    ( 1053): stop dsqn bin
,D/WifiHS20( 1053): hidePasspointNotification off =false
E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286959  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286960  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1053):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1053):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1053):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1053): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286965  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1053): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1053): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1053): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1053): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1053): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1053): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1053): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1053): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): Disconnected - quitting
V/NetworkPolicy( 1053): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiHS20( 1053): hidePasspointNotification off =false
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/TelephonyNetworkFactory-1( 1846): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
V/NetworkPolicy( 1053): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1053): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1053): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1053): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1053): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1053): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1053): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1053): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1053): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1053): Removing idletimer
W/Settings( 1053): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1053): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1053): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286986  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1053): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1053):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateSCANNING
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 1053): Explicit concurrent mark sweep GC freed 49684(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.250ms total 149.219ms
,V/NativeCrypto( 2066): SSL shutdown failed: ssl=0xaf4d6600: I/O error during system call, Broken pipe
W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/DhcpStateMachine( 1053): StoppedState
,D/DhcpStateMachine( 1053): StoppedState{ when=-157ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7216): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7216): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7216): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1053): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7255 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1053): Killing 6658:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1053): failed to open /acct/uid_10004/pid_6658/cgroup.procs: No such file or directory
,I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7255): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7216): LgDataFeature() Constructor: none
,D/LgDataFeature( 7216): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
I/ActivityManager( 1053): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7277 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1053): Killing 6762:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/art     (  338): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 21.475ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.139ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 19.007ms
,W/libprocessgroup( 1053): failed to open /acct/uid_10008/pid_6762/cgroup.procs: No such file or directory
W/ResourcesManager( 7277): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7277): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7277): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7277): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7277): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7277): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7277): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7277): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7277): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 7277): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 7277): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7255): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7255): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7255): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7277): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7277): LgDataFeature() Constructor: none
D/LgDataFeature( 7277): LgDataFeature() Constructor Done, null
,V/SoundPool( 7277): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7277): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7277): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7277): doLoad: loading sample sampleID=1
I/QRemote ( 7277): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7277): Start decode
V/MediaPlayer[Native]( 7277): decode(31, 10857164, 17813)
,D/UEI.SmartControl( 6940): QS Service created
V/MediaPlayerService(  317): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  317): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  317): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  317): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  317): player type = 3
V/AwesomePlayer(  317): AwesomePlayer create()
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): setAudioSink() 
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb5474d00, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/Utils   (  317): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  317): setDataSource_l dataSource
V/LGParserOSAL(  317): SniffLGParser start
V/LGParserOSAL(  317): MainType:5, SubType=0
V/LGParserOSAL(  317): #### check Mime : application/ogg
V/LGParserOSAL(  317): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  317): Use LGExtractor :application/ogg 
D/QRemote ( 7277): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7277): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  317): supported mime: application/ogg
V/AwesomePlayer(  317): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  317): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  317): mBitrate = -1 bits/sec
V/AwesomePlayer(  317): AudioTrack Setting
V/AwesomePlayer(  317): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  317): setAudioSource() 
V/MediaPlayerService(  317): prepare
V/AwesomePlayer(  317): prepareAsync_l() 
V/MediaPlayerService(  317): wait for prepare
V/AwesomePlayer(  317): onPrepareAsyncEvent() 
V/AwesomePlayer(  317): initAudioDecoder() 
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AwesomePlayer(  317): getUseOffload() = 0 
V/OMXCodec(  317): OMXCodec::Create
V/OMXCodec(  317): findMatchingCodecs()
V/OMXCodec(  317): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  317): matchingCodecs.size()=1
V/OMXCodec(  317): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  317): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  317): LG Codec Adapter start
V/OMXCodec(  317): OMXCodec Createtor
V/OMXCodec(  317): setComponentRole
V/OMXCodec(  317): configureCodec protected=0
V/LGCodecAdapter(  317): called getLGCodecSpecificData
V/LGCodecOSAL(  317): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMSG
V/LGCodecOSAL(  317): Not support LGCodec
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  317): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  317): Could not offload audio decode, try pcm offload
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  317): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  317): init()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  317): allocateBuffers
V/OMXCodec(  317): allocateBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] a,llocated buffer 0xb14fcb00 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1750330 on output port
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  317): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  317): finishAsyncPrepare_l() 
V/AudioCache(  317): notify(0xb5474d00, 5, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): notify(0xb5474d00, 1, 0, 0)
V/AudioCache(  317): prepared
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): start
V/AwesomePlayer(  317): play_l() 
V/AwesomePlayer(  317): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  317): createAudioPlayer_l
V/AwesomePlayer(  317): seekAudioIfNecessary_l() 
V/AwesomePlayer(  317): startAudioPlayer_l() 
D/AudioPlayer(  317): start of Playback, useOffload 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  317): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796224
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796464
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796544
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977235760
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  317): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcb00 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb17fb380 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  317): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  317): notify(0xb5474d00, 6, 0, 0)
V/AudioCache(  317): ignored
V/MediaPlayerService(  317): wait for playback complete
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab602000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab603000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab604000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab605000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab606000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab607000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab608000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab609000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60a000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60b000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60c000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60d000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60e000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab60f000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab610000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab611000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab612000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab613000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab614000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab615000, 0xb57c8000, 4096)
I/UEI.SmartControl( 6940): Service initServices...
D/UEI.SmartControl( 6940): QS start get config
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab616000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab617000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab618000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab619000, 0xb57c8000, 4096)
V/LGMDMManager( 7277): Create singleton instance
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61a000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61b000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61c000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61d000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61e000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab61f000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab620000, 0xb57c8000, 4096)
,V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab621000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab622000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab623000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab624000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab625000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab626000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab627000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab628000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab629000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62a000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62b000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62c000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62d000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62e000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab62f000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab630000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab631000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab632000, 0xb57c8000, 4096)
V/AudioCache(  317): write(0xb57c8000, 4096)
V/AudioCache(  317): memcpy(0xab633000, 0xb57c8000, 4096)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  317): postAudioEOS() 
V/AudioCache(  317): write(0xb57c8000, 280)
V/AudioCache(  317): memcpy(0xab634000, 0xb57c8000, 280)
V/AwesomePlayer(  317): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  317): onStreamDone
V/AwesomePlayer(  317): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  317): notify(0xb5474d00, 2, 0, 0)
V/AudioCache(  317): playback complete
V/AwesomePlayer(  317): pause_l() 
V/AudioCache(  317): notify(0xb5474d00, 7, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  317): Pause Playback at 1068125
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb5474d00, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/AudioPlayer(  317): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb17fb380 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcab0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcb00 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  317): AudioPlayer releasing audio source
D/AudioPlayer(  317): AudioPlayer done releasing audio source
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): ~AwesomePlayer call
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/SoundPool( 7277): close(31)
V/SoundPool( 7277): pointer = 0x9fe42000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7277): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7423
I/UEI.SmartControl( 6940): Supports setup maps: true
,D/UEI.SmartControl( 6940): QS start statue = true Error code = 0
I/UEI.SmartControl( 6940): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6940): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6940): ### init IR Blaster...
D/serial_port( 6940): Configuring serial port
E/UEI.SmartControl( 6940): UEIBLaster setting for 616
I/UEI.SmartControl( 6940): Setting serial record hearder size = 2
I/UEI.SmartControl( 6940): configuring settings for MAXQ616
I/UEI.SmartControl( 6940): Get version...
D/UEI.SmartControl( 6940): serial port data available: 21
,D/UEI.SmartControl( 6940): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6940): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6940): QS saving settings...
D/UEI.SmartControl( 6940): IR Blaster version: 25672567
,D/UEI.SmartControl( 6940): serial port data available: 4
,W/ContextImpl( 6940): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6940): Services init done
D/UEI.SmartControl( 6940): QS Service init finished
D/UEI.SmartControl( 6940): QS Service version name: 2.1.91
D/UEI.SmartControl( 6940): QS Service version code: 201091
D/UEI.SmartControl( 6940): Service requested: Control
I/QRemote ( 7277): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6940): Internal service binding...
I/UEI.SmartControl( 6940): Device manager: loading config....
D/UEI.SmartControl( 6940): ----------- loading internal config...
I/UEI.SmartControl( 6940): ------ IControl API: 11
D/UEI.SmartControl( 6940): File observer start...
E/UEI.SmartControl( 6940): IR Port is disabled: false
D/UEI.SmartControl( 6940): Starting file observer...
I/UEI.SmartControl( 6940): Registering callback...
I/UEI.SmartControl( 6940): ------ IControl API: 19
,I/UEI.SmartControl( 6940): Registering Services Ready callback...
E/UEI.SmartControl( 6940): Loading SETTINGS...
,D/UEI.SmartControl( 6940): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6940): Notify AllClients services are ready: 0
,I/QRemote ( 7277): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6940): -----service ready thread exits
D/QRemote ( 7277): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7277): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7277): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7277): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6940): ------ IControl API: 8
D/QRemote ( 7277): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7277): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7277): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7277): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7277): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7277): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7277): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7277): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453416203427]
D/QRemote ( 7277): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1053): Killing 6219:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7277): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1053): failed to open /acct/uid_10011/pid_6219/cgroup.procs: No such file or directory
,V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 7277): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/wpa_supplicant( 2624): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1053): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1053): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1053): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1053):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1053):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1053):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1053):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1053): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289046  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2624): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1053): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289127  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289127  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1053):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289128
E/WifiStateMachine( 1053):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289128
E/WifiStateMachine( 1053):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289128
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289128
D/Tethering( 1053): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1053):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289129
E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289129  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289132  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1053):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1053):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 2624): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2624): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1053):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiMonitor( 1053): Event [IFNAME=wlan0 WPA: Key negot,iation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
W/WifiMonitor( 1053): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1053):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1053): setSupplicantStateASSOCIATED
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1053): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1053):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289136  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289136  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1053):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289136
E/WifiStateMachine( 1053):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289137
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1053): doString: [STATUS]
D/WifiMonitor( 1053): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1053): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1053):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 7216): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7216): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/WifiServiceExtension( 1053): setVHTCapabilityType  : false
D/UsbSettingsControl( 7216): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1053): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1053): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1053): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1053): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1053): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1053): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1053): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1053): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1053): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1053): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1053): SAVE_CONFIG: returned true
E/WifiConfigStore( 1053): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1053): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1053): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1053): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1053): SAVE_CONFIG: returned true
D/CommandListener(  313): Setting iface cfg
E/WifiStateMachine( 1053): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1053): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1053): WaitBeforeStartState
,E/WifiStateMachine( 1053):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289171  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1053):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289171  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289171  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1053):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1053):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1053):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
E/WifiStateMachine( 1053):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1053):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1053):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService( 1053): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1053):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1053): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1053): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1053): doBoolean: SET ps 0
D/WifiNative-wlan0( 1053): SET ps 0: returned true
D/WifiNative-wlan0( 1053): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1053): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1053): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1053): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1053): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1053): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b90791f target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1053): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b90791f target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1053): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1053): DHCP Start wake lock is acquired.
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1053): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1053): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1053): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1053):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1053):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1053): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1053): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1053): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1053): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1053): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2624): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1053): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1053): doBoolean: SET ps 1
D/WifiNative-wlan0( 1053): SET ps 1: returned true
D/ConnectivityService( 1053): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1053):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1053): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1053):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1053):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1053): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1053): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1053): Setti,ng stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1053): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1053): Adding iface wlan0 to network 101
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1053): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WfdStateTracker( 1936): handleWifiStateChangedEvent: 1
D/WifiHS20( 1053): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1053): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1053): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1053): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1053): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1053): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1053): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1053): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/Netd    (  313): netlink response contains error (File exists)
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1053): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1053): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1053): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1053): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1053): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1053): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1053):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): Connected
D/ConnectivityService( 1053):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1053):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1053):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1053): currentScore = 0, newScore = 20
D/ConnectivityService( 1053):    accepting network in place of null
,D/ConnectivityService( 1053): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1053): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1053):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1053): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1053): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1053): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1053): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1053): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1053): validation of new default Network = false
D/ConnectivityService( 1053): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1053): enableDataServiceNotify 
D/DSQN    ( 1053): start dsqn bin
D/LocSvc_java( 1053): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1053): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1053): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1053): ignore wifi update if we are not in OPENING or CLOSING
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1053): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7341): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7341): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1053): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7341): DSQN ssw
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7277): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7277): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7277): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7255): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7255): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7277): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7277): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7277): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1053): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1053): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 22:43:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453416204337], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453416204315]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1053): Validated
D/ConnectivityService( 1053): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1053):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1053): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1053): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1053): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1053):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
,D/TelephonyNetworkFactory-1( 1846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1053): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1053): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1053): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7348): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7348): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7348): version 5.5.6 starting
,E/dhcpcd  ( 7348): get_duid: m
D/dhcpcd  ( 7348): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7348): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7348): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7348): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7348): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7348): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 7348): wlan0: sending REQUEST (xid 0x7580ea52), next in 3.90 seconds
D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1053): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1053): MasterInitialState.processMessage what=3
D/Tethering( 1053): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 6000): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6000): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1053): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1053): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7372 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1053): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1053): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7372): onCreate
,W/AppUp4:DB( 7372):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7372):  setFingerPrint start
I/AppUp4:DB( 7372):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7372):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7372):  SDK version = 21
I/AppUp4:DB( 7372):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7372): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7372): onReceive
D/LgDataFeature( 7372): LgDataFeature() Constructor: none
D/LgDataFeature( 7372): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7372): Context : android.app.ReceiverRestrictedContext@205b27cd
D/AppUp4:CustFacade( 7372): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7372): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7372): begin check event
I/AppUp4:CustModeStarterReceiver( 7372): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7372): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7372): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7372): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7372): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1053): Killing 6239:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1053): failed to open /acct/uid_10019/pid_6239/cgroup.procs: No such file or directory
D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3333): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3333): DownloadService onCreate
D/LGDMClient( 4376): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4376): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3333): in removeSpuriousFiles
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@18abe5e1 on behalf of 3333
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3333): in trimDatabase
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@e419f06 on behalf of 3333
,V/DownloadManager( 3333): DownloadService onStartCommand
D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3333): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4376): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4376): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4376): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@121fff1d on behalf of 3333
V/DownloadManager( 3333): processing inserted download 1
V/DownloadManager( 3333): processing inserted download 4
V/DownloadManager( 3333): processing inserted download 7
V/DownloadManager( 3333): processing inserted download 8
V/DownloadManager( 3333): processing inserted download 9
V/DownloadManager( 3333): processing inserted download 10
,D/eas_req ( 6787): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3333): processing inserted download 16
V/DownloadManager( 3333): processing inserted download 17
V/DownloadManager( 3333): processing inserted download 18
V/DownloadManager( 3333): processing inserted download 21
V/DownloadManager( 3333): processing inserted download 22
,V/DownloadManager( 3333): DownloadService onDestroy
I/ActivityManager( 1053): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7404 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6787): JNI_OnLoad()
I/HubEmail( 6787): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6787): registerNatives()
I/HubEmail( 6787): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6787): registerNativeMethods()
I/HubEmail( 6787): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6787): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3266): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3266): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3266): networkInfo.isConnected() = false
,E/WifiStateMachine( 1053):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1053):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1053): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1053): identical MTU - not setting
D/Nat464Xlat( 1053): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1053): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1053):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1053): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524295
I/ActivityManager( 1053): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7427 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7348): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7348): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7348): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7348): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7348): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 7348): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7348): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7348): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7348): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1053): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7461 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1053): Killing 6816:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1053): failed to open /acct/uid_10027/pid_6816/cgroup.procs: No such file or directory
,I/ActivityManager( 1053): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7490 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1053): Killing 6840:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/DhcpStateMachine( 1053): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1053): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1053): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1053): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1053): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1053): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1053): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1053): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1053): RunningState
W/libprocessgroup( 1053): failed to open /acct/uid_10061/pid_6840/cgroup.procs: No such file or directory
,D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
,I/art     ( 7490): Almond Protected OAT
,I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7154): 
,D/WeatherApplication( 7490): removeAccount
D/WeatherApplication( 7490): Account.length = 0
E/WeatherApplication( 7490): OPERATOR:OPEN
D/WeatherAncestor( 7490): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:26
D/Weather.Utils( 7490): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7490): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7490): 2 : This is isUpdating : false
,D/WeatherAncestor( 7490): connectivity changed - connection : true
D/WeatherService( 7490): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7490): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7490): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7490): 2 : Cache is not up-to-date, count: 0
V/FormManager( 7404): There are no updated forms. The schedule will be deleted.
V/FormManager( 7404): Alarm would be updated, because LastCheckTime has been updated.
D/Weather_cast( 7490): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7490): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:26
,I/ActivityManager( 1053): Killing 6864:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1053): failed to open /acct/uid_10080/pid_6864/cgroup.procs: No such file or directory
,I/ActivityManager( 1053): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7509 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1053): Killing 6909:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1053): failed to open /acct/uid_1000/pid_6909/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7509): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7509): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7509): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7509): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/art     ( 2066): Explicit concurrent mark sweep GC freed 37133(2MB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.222ms total 61.889ms
,I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7154): 
,I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7154): 
I/WebViewFactory( 7509): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7509): Loading: webviewchromium
I/LibraryLoader( 7509): Time to load native libraries: 2 ms (timestamps 1887-1889)
I/LibraryLoader( 7509): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7509): Binding Chromium to main looper Looper (main, tid 1) {539412c}
I/LibraryLoader( 7509): Expected native library version number "",actual native library version number ""
I/chromium( 7509): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7509): Initializing chromium process, renderers=0
,W/art     ( 7509): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7509): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7509): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7509): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  317): registerClient() client 0xb14fda00, uid 10093
W/AudioManagerAndroid( 7509): Requires BLUETOOTH permission
I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7154): 
I/Adreno-EGL( 7509): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7509): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7509): Build Date: 12/12/14 금
I/Adreno-EGL( 7509): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7509): Remote Branch: 
I/Adreno-EGL( 7509): Local Patches: 
I/Adreno-EGL( 7509): Reconstruct Branch: 
,E/WifiStateMachine( 1053):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1053):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1053):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1053):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1053):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1053):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7154): 
,I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7154): 
I/jxcore-log( 7154): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7154): 
,I/NSApplication( 7509): Starting up...
,I/ActivityManager( 1053): Killing 6157:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1053): failed to open /acct/uid_10005/pid_6157/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1053): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1053): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1053): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1053): MasterInitialState.processMessage what=3
I/NetworkMonitor( 6000): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1053): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7372): onReceive
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7372): Context : android.app.ReceiverRestrictedContext@205b27cd
D/AppUp4:CustFacade( 7372): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7372): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7372): begin check event
I/AppUp4:CustModeStarterReceiver( 7372): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3333): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3333): DownloadService onCreate
I/DownloadManager( 3333): in removeSpuriousFiles
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@2ccd2b63 on behalf of 3333
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3333): in trimDatabase
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4376): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@825d360 on behalf of 3333
V/DownloadManager( 3333): DownloadService onStartCommand
V/DownloadManager( 3333): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4376): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@26dd1abf on behalf of 3333
V/NotificationService( 1053): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1053): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1053): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1053): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1053): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Kids    ( 2349): [AccountUtils] Account not ready
W/Kids    ( 2349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2349): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2349): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
V/DownloadManager( 3333): processing inserted download 1
V/DownloadManager( 3333): processing inserted download 4
V/DownloadManager( 3333): processing inserted download 7
V/DownloadManager( 3333): processing inserted download 8
V/DownloadManager( 3333): processing inserted download 9
V/DownloadManager( 3333): processing inserted download 10
V/DownloadManager( 3333): processing inserted download 16
,V/DownloadManager( 3333): processing inserted download 17
V/DownloadManager( 3333): processing inserted download 18
V/DownloadManager( 3333): processing inserted download 21
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3333): processing inserted download 22
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LGDMClient( 4376): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4376): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4376): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
I/LgeMiscReceiver( 3266): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3266): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3266): networkInfo.isConnected() = false
V/DownloadManager( 3333): DownloadService onDestroy
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{3180f4d5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/WeatherAncestor( 7490): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:27
,D/Weather.Utils( 7490): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7490): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7490): 2 : This is isUpdating : false
D/WeatherAncestor( 7490): connectivity changed - connection : true
D/WeatherService( 7490): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38eabb93
D/ForecastDataCache( 7490): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7490): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7490): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7490): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7490): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:27
D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
V/FormManager( 7404): There are no updated forms. The schedule will be deleted.
,W/ContextImpl( 6734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/FormManager( 7404): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7372): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7372): onReceive
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/AppUp4:CustFacade( 7372): Context : android.app.ReceiverRestrictedContext@205b27cd
D/AppUp4:CustFacade( 7372): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7372): isPhone : true
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AppUp4:CustModeStarterReceiver( 7372): begin check event
I/AppUp4:CustModeStarterReceiver( 7372): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3333): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4376): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4376): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3333): DownloadService onCreate
I/DownloadManager( 3333): in removeSpuriousFiles
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@3180f4d5 on behalf of 3333
V/NotificationService( 1053): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1053): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1053): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1053): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1053): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3333): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Kids    ( 2349): [AccountUtils] Account not ready
W/Kids    ( 2349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2349): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2349): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
I/DownloadManager( 3333): in trimDatabase
V/DownloadManager( 3333): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@103f54ea on behalf of 3333
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
E/LGDMClient( 4376): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4376): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4376): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
I/LgeMiscReceiver( 3266): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3266): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3266): networkInfo.isConnected() = true
D/PhoneState( 3266): setPdpRejectCasuse : false
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{3180f4d5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3333): DownloadService onStartCommand
V/DownloadManager( 3333): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WeatherAncestor( 7490): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:27
D/Weather.Utils( 7490): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7490): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7490): 2 : This is isUpdating : false
D/WeatherAncestor( 7490): connectivity changed - connection : true
D/WeatherService( 7490): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38eabb93
V/DownloadManager( 3333): created cursor android.database.sqlite.SQLiteCursor@1c690951 on behalf of 3333
D/ForecastDataCache( 7490): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7490): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7490): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7490): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7490): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:43:27
V/DownloadManager( 3333): processing inserted download 1
V/DownloadManager( 3333): processing inserted download 4
V/DownloadManager( 3333): processing inserted download 7
,V/DownloadManager( 3333): processing inserted download 8
V/DownloadManager( 3333): processing inserted download 9
V/DownloadManager( 3333): processing inserted download 10
V/DownloadManager( 3333): processing inserted download 16
V/DownloadManager( 3333): processing inserted download 17
V/DownloadManager( 3333): processing inserted download 18
V/DownloadManager( 3333): processing inserted download 21
V/DownloadManager( 3333): processing inserted download 22
,V/DownloadManager( 3333): DownloadService onDestroy
D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7404): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7404): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1053): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1053): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1053): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1053): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1053): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2349): [AccountUtils] Account not ready
W/Kids    ( 2349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2349): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2349): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{3180f4d5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/jxcore-log( 7154): Test app app.js loaded
I/jxcore-log( 7154): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7154): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7154): BLE advertisement is supported
I/jxcore-log( 7154): 
I/chromium( 7154): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/UEI.SmartControl( 6940): Internal timer expired: 2
D/UEI.SmartControl( 6940): unbind internal service
,D/serial_port( 6940): close(fd = 24)
,I/UEI.SmartControl( 6940): Serial port is closed.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = www.google.com succeed
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1053): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7154): --= Surplus to requirements =--
I/jxcore-log( 7154): 
I/jxcore-log( 7154): ****TEST TOOK:  ms ****
I/jxcore-log( 7154): 
I/jxcore-log( 7154): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7154): 
,D/AndroidRuntime( 7618): 
D/AndroidRuntime( 7618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7618): CheckJNI is OFF
V/AlarmManager( 1053): ELAPSED_WAKEUP set : Alarm{6b383fd type 2 when 240069 android} when 240069
,D/[Concierge]Service( 2625): onStartCommand(). Type : 9
,D/AndroidRuntime( 7618): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1053): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
I/ActivityManager( 1053): Killing 7154:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7423
W/PackageSettings( 1053): Skipping PackageSetting{1f6b673a com.example.hello/10319} due to missing metadata
I/WindowState( 1053): WIN DEATH: Window{2a384c6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1053): Client connection lost with reason: 4
D/InputDispatcher( 1053): Window went away: Window{2a384c6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1053):   Force finishing activity ActivityRecord{16a871d1 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
,W/ActivityManager( 1053): Spurious death for ProcessRecord{1f5478f2 7154:com.test.thalitest/u0a311}, curProc for 7154: null
,I/ActivityManager( 1053): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1053):   Force finishing activity ActivityRecord{16a871d1 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1053): Duplicate finish request for ActivityRecord{16a871d1 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2026): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2026): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{28f890dd co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{15e73452 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2026): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 1989): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3726): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/art     ( 4676): Explicit concurrent mark sweep GC freed 15848(890KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 573us total 80.460ms
,I/InputReader( 1053): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,D/ActionManagerService( 1899): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2026): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/PostponalbeReceiver( 6734): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4624): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4624): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4624): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4624): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4624): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4624): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4624): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4624): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4624): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4624): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/ActivityManager( 1053): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7649 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2026): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1478): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2026): [Launcher.java:1114:onPause()]onPause
V/SIM_STK ( 1053): Menu title from STK is T-Mobile
,D/ActionManagerService( 1899): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2026): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2026): , create_time: 1430558575574
I/GBoardWebViewUtils( 2026): , expire_time: 0
I/GBoardWebViewUtils( 2026): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2026): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2026): , display: false
I/GBoardWebViewUtils( 2026): , animation: false }
I/GBoardWebViewUtils( 2026): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2026): , create_time: 1430558575600
I/GBoardWebViewUtils( 2026): , expire_time: 0
I/GBoardWebViewUtils( 2026): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2026): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2026): , display: false
I/GBoardWebViewUtils( 2026): , animation: false }
I/GBoardWebViewUtils( 2026): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2026): , create_time: 1453384801850
I/GBoardWebViewUtils( 2026): , expire_time: 0
I/GBoardWebViewUtils( 2026): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2026): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2026): , display: false
I/GBoardWebViewUtils( 2026): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1478): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/WallpaperManager( 2026): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/SplitUIManager( 1863): split_name #11 / not available #0
D/SplitUIService( 1863): removed split : 
I/SystemUI[Framework]( 1053): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1053): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1053): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1053): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1053): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ecedb09,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1053): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1053): Explicit concurrent mark sweep GC freed 75921(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.822ms total 180.439ms
,I/[LGHome]EVENT( 2026): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 1053): WaitForGcToComplete blocked for 202.772ms for cause Explicit
,I/LockScreenSettings( 7649): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,V/SIM_STK ( 1053): Menu title from STK is T-Mobile
V/SIM_STK ( 1053): Menu title from STK is T-Mobile
D/SplitUIManager( 1863): split_name #11 / not available #0
I/SplitUIService( 1863): split app #11
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
,I/[LGHome]EVENT( 2026): [Launcher.java:5349:onStop()]onStop
D/AppUp4:PreloadHelper( 7372): added Exclude : com.test.thalitest
D/administrator( 1053): Handling package changes for user 0
,I/ActivityManager( 1053): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7670 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityManager( 1053): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [-] updateMediaPlayerInfo
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
D/KeyguardModel( 1478): handleShortcutListChanged...
,D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
I/ActivityManager( 1053): Killing 6967:com.lge.bnr/1000 (adj 15): empty #17
,I/NotificationService( 1053): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1053): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1053): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 7670): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7670): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7670): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,V/SIM_STK ( 1053): Menu title from STK is T-Mobile
W/ResourcesManager( 7670): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7670): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/art     ( 1053): Explicit concurrent mark sweep GC freed 9873(531KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.564ms total 183.383ms
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2026): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2026): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2026): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1478): handleShortcutListChanged...
,W/libprocessgroup( 1053): failed to open /acct/uid_1000/pid_6967/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1053): Timeline: Activity_windows_visible id: ActivityRecord{275b0cbb u0 com.lge.launcher2/.Launcher t3} time:294925
D/TaskPersister( 1053): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2625): onStartCommand(). Type : 8
D/[Concierge]Service( 2625): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2026): change position of spinner
D/[Concierge]Service( 2625): Update widget ID : 11
I/[Concierge]WidgetView( 2026): initWebView(). Time : 1453416209877
D/[Concierge]Service( 2625): onStartCommand(). Type : 0
,D/AndroidRuntime( 7618): Shutting down VM
W/ResourcesManager( 1053): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[Concierge]WebView( 2026): Return exist ConciergeWebView. Reuse : 929764855
D/[Concierge]WidgetView( 2026): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/SystemConfig( 7670): BUILD Country: EU
I/SystemConfig( 7670): BUILD Operator: OPEN
W/ResourceType( 1053): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]ExtViewHost( 2026): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1b305cec
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2026): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2026): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2026): Widget kill message received. Destory myself. My : 1453415942649, New one : 1453416209877
D/[Concierge]WidgetView( 2026): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2026): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2026): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1053): Killing 7044:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2026): Timeline: Activity_idle id: android.os.BinderProxy@8bd1866 time:295064
,W/libprocessgroup( 1053): failed to open /acct/uid_10054/pid_7044/cgroup.procs: No such file or directory
,I/PackageChangeReceiver( 6787): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2395): Cleaning up data for package: com.test.thalitest
,I/SystemConfig( 7670): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7670): existFile = false
I/SystemConfig( 7670): canReadFile = false
I/SystemConfig( 7670): systemFeature RCS result false
D/SystemConfig( 7670): refreshRcsSupport() :false
I/ActivityManager( 1053): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7692 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/chromium( 2026): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,V/AlarmManager( 1053): ELAPSED_WAKEUP set : Alarm{3f5b169d type 2 when 295209 android} when 295209
I/GBoardtInterface( 2026): onReloaded()
,I/GBoardWebViewClient( 2026): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3726): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 7692): Total System Memory = 2995761152
,D/SystemHelper( 7692): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7692): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
