#### Test 543122982543be8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297838925282; DSPS: 9900254; Offset : -4306494539
,D/AndroidRuntime( 7088): 
D/AndroidRuntime( 7088): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7088): CheckJNI is OFF
D/AndroidRuntime( 7088): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1935): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{2db0397c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{2db0397c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  331): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7108 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7088): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1846): Display #0 changed.
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{304ee2d5 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{2071aaea co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7108): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7108): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7108): Loading: webviewchromium
I/LibraryLoader( 7108): Time to load native libraries: 5 ms (timestamps 1401-1406)
,I/LibraryLoader( 7108): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7108): Binding Chromium to main looper Looper (main, tid 1) {243477c5}
,I/LibraryLoader( 7108): Expected native library version number "",actual native library version number ""
,I/chromium( 7108): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7108): Initializing chromium process, renderers=0
W/art     ( 7108): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7108): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7108): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7108): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb1427ba0, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30a02a26:true
I/Adreno-EGL( 7108): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7108): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7108): Build Date: 12/12/14 금
I/Adreno-EGL( 7108): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7108): Remote Branch: 
I/Adreno-EGL( 7108): Local Patches: 
I/Adreno-EGL( 7108): Reconstruct Branch: 
,W/chromium( 7108): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7108): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7108): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7108): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7108): CordovaWebView is running on device made by: LGE
,W/art     ( 7108): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7108): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{17747205 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7108): Render dirty regions requested: true
I/OpenGLRenderer( 7108): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7108): Enabling debug mode 0
D/Atlas   ( 7108): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{2b82ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4f35b28,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7108): LgDataFeature() Constructor: none
,D/LgDataFeature( 7108): LgDataFeature() Constructor Done, null
I/Timeline( 7108): Timeline: Activity_idle id: android.os.BinderProxy@1b7bdc35 time:311780
,I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +628ms (total +745ms)
,I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{17747205 u0 com.test.thalitest/.MainActivity t4} time:311804
I/chromium( 7108): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7108): 
,D/JsMessageQueue( 7108): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7108): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434888448
D/JX-Cordova( 7108): jxcore cordova android initializing
,E/GBMv2   (  331): DFP En is all cleared set to be enabled
E/GBMv2   (  331): Set value is all cleared set the max
I/GBMv2   (  331): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7108): Initializing JXcore engine
W/jxcore-log( 7108): JXcore engine is ready
,W/jxcore-log( 7108): Starting JXcore engine
W/.test.thalitest( 7108): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8438]" dev="sockfs" ino=8438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7108): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7108): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9986]" dev="sockfs" ino=9986 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7108): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7108): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33571]" dev="sockfs" ino=33571 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 7108): Background sticky concurrent mark sweep GC freed 123266(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.606ms total 132.911ms
,W/jxcore-log( 7108): Platform android
W/jxcore-log( 7108): 
W/jxcore-log( 7108): Process ARCH arm
W/jxcore-log( 7108): 
,I/jxcore-log( 7108): JXcore Cordova bridge is ready!
I/jxcore-log( 7108): 
W/jxcore-log( 7108): JXcore engine is started
,I/jxcore-log( 7108): Toggling radios to true
I/jxcore-log( 7108): 
,D/BluetoothAdapter( 7108): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7108, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7108, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7108, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [315,634,222 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7108, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7108): Radios toggled
I/jxcore-log( 7108): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7108): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7108): 
I/jxcore-log( 7108): Perf Test app loaded loaded
I/jxcore-log( 7108): 
I/jxcore-log( 7108): check test folder
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): found test : ./testFindPeers.js
I/jxcore-log( 7108): 
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1037): InitialState.processMessage what=4
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
I/jxcore-log( 7108): found test : ./testSendData.js
I/jxcore-log( 7108): 
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1037): RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2096): Read error: ssl=0xaa6f3600: I/O error during system call, Connection timed out
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7204 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [315,737,760 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
,I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1037): ignoring duplicate network state non-change
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=315740
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=315741
D/WifiHS20( 1037): hidePasspointNotification off =false
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NativeCrypto( 2096): SSL shutdown failed: ssl=0xaa6f3600: I/O error during system call, Broken pipe
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/jxcore-log( 7108): found test : ./testSendData2.js
I/jxcore-log( 7108): 
,D/CommandListener(  312): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1037): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=315793  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=315794  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1846): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Connect,ivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=315813  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=315822  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7204): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/chromium( 7108): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7108): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7108): 
,I/chromium( 7108): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1037): StoppedState
,D/DhcpStateMachine( 1037): StoppedState{ when=-213ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7204): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7204): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7204): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7204): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7241 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6126:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6126/cgroup.procs: No such file or directory
,I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7241): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7204): LgDataFeature() Constructor: none
D/LgDataFeature( 7204): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7265 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6146:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6146/cgroup.procs: No such file or directory
,W/ResourcesManager( 7265): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7265): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7265): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7265): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7265): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7265): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7265): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7265): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7265): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7265): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7265): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7241): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7241): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
,D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7241): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
,D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7265): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7265): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7265): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7265): LgDataFeature() Constructor: none
,D/LgDataFeature( 7265): LgDataFeature() Constructor Done, null
V/SoundPool( 7265): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7265): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7265): create sampleID=1, fd=31, offset=17813 length=10857164
,V/SoundPool( 7265): doLoad: loading sample sampleID=1
V/SoundPool( 7265): Start decode
V/MediaPlayer[Native]( 7265): decode(31, 10857164, 17813)
I/QRemote ( 7265): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
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
V/AudioCache(  316): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/UEI.SmartControl( 6815): QS Service created
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
,E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/QRemote ( 7265): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7265): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7265): Create singleton instance
,V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
,V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
,V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
,V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec,
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
I/UEI.SmartControl( 6815): Service initServices...
D/UEI.SmartControl( 6815): QS start get config
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb1163840, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1163840, 1, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975824
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX,.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e70 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1163840, 6, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae700000, 0xb57ff000, 4096)
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae701000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae702000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae703000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae704000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae705000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae706000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae707000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae708000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae709000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70a000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70b000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70c000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70d000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70e000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae70f000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae710000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae711000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae712000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae713000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae714000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae715000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae716000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae717000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae718000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae719000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71a000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71b000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71c000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71d000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71e000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae71f000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae720000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae721000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae722000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae723000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae724000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae725000, 0xb57ff000, 4096)
,V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae726000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae727000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae728000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae729000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72a000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72b000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72c000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72d000, 0xb57ff000, 4096)
,V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72e000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae72f000, 0xb57ff000, 4096)
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae730000, 0xb57ff000, 4096)
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  316): write(0xb57ff000, 4096)
V/AudioCache(  316): memcpy(0xae731000, 0xb57ff000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57ff000, 280)
V/AudioCache(  316): memcpy(0xae732000, 0xb57ff000, 280)
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4340
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1163840, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): wait - success
V/AudioCache(  316): notify(0xb1163840, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434e70 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
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
V/AwesomePlayer(  316): cancelPl,ayerEvents
V/SoundPool( 7265): close(31)
V/SoundPool( 7265): pointer = 0x9fe68000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6815): Supports setup maps: true
,D/UEI.SmartControl( 6815): QS start statue = true Error code = 0
I/UEI.SmartControl( 6815): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6815): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6815): ### init IR Blaster...
D/serial_port( 6815): Configuring serial port
E/UEI.SmartControl( 6815): UEIBLaster setting for 616
I/UEI.SmartControl( 6815): Setting serial record hearder size = 2
I/UEI.SmartControl( 6815): configuring settings for MAXQ616
I/UEI.SmartControl( 6815): Get version...
D/UEI.SmartControl( 6815): serial port data available: 21
,D/UEI.SmartControl( 6815): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6815): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6815): QS saving settings...
,D/UEI.SmartControl( 6815): IR Blaster version: 25672567
D/UEI.SmartControl( 6815): serial port data available: 4
,W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6815): Device manager: loading config....
,D/UEI.SmartControl( 6815): ----------- loading internal config...
E/UEI.SmartControl( 6815): Services init done
D/UEI.SmartControl( 6815): QS Service init finished
D/UEI.SmartControl( 6815): QS Service version name: 2.1.91
D/UEI.SmartControl( 6815): QS Service version code: 201091
D/UEI.SmartControl( 6815): Service requested: Control
E/UEI.SmartControl( 6815): Loading SETTINGS...
D/UEI.SmartControl( 6815): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6815): Internal service binding...
I/QRemote ( 7265): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6815): ------ IControl API: 11
D/UEI.SmartControl( 6815): File observer start...
E/UEI.SmartControl( 6815): IR Port is disabled: false
D/UEI.SmartControl( 6815): Starting file observer...
I/UEI.SmartControl( 6815): Registering callback...
I/UEI.SmartControl( 6815): ------ IControl API: 19
I/UEI.SmartControl( 6815): Registering Services Ready callback...
,D/UEI.SmartControl( 6815): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6815): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6815): -----service ready thread exits
I/QRemote ( 7265): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7265): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7265): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7265): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7265): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6815): ------ IControl API: 8
D/QRemote ( 7265): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7265): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7265): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7265): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7265): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7265): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7265): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7265): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7265): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7265): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7265): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450745685821]
D/QRemote ( 7265): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6712:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7265): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6712/cgroup.procs: No such file or directory
,V/QRemote ( 7265): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7265): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317841035143; DSPS: 10555683; Offset : -4306490522
,I/wpa_supplicant( 2669): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=317905  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=317935  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2669): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2669): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=318014  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=318015  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=318020
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=318020
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=318029
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=318030
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=318030
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=318032  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=318045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=318061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=318062  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=318063
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=318063
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7204): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7204): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7204): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7204): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 7204): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  312): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=318116  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=318117  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=318117  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1037): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=318121  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=318121  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=318121  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ceddabe target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ceddabe target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/CommandListener(  312): Setting iface cfg
D/CommandListener(  312): Trying to bring up wlan0
I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 1
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  312): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
,D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
W/dsqn    ( 7343): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7343): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/DSQN    ( 7343): DSQN ssw
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
,V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7265): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/LGDataListener(  312): argv[0]=dsqncommand
D/LGDataListener(  312): argv[1]=wlan0
D/LGDataListener(  312): argv[2]=1
D/LGDataListener(  312): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7265): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7265): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7265): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Dec 2015 00:54:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450745686572], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450745686554]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
,D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/PCSuite ( 7241): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7241): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7204): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7204): MCCMNC not supported: null
D/QRemote ( 7265): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7265): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
D/QRemote ( 7265): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/QRemote ( 7265): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7265): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
W/dhcpcd  ( 7350): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7350): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7350): version 5.5.6 starting
E/dhcpcd  ( 7350): get_duid: m
D/dhcpcd  ( 7350): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7350): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7350): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7350): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7350): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7350): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7350): wlan0: sending REQUEST (xid 0xdc94e70f), next in 3.65 seconds
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/jxcore-log( 7108): Connected to the server!
I/jxcore-log( 7108): 
I/NetworkMonitor( 5494): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5494): type=WIFI subType= reason=null isConnected=true
I/chromium( 7108): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7394 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7394): onCreate
W/AppUp4:DB( 7394):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7394):  setFingerPrint start
I/AppUp4:DB( 7394):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7394):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7394):  SDK version = 21
I/AppUp4:DB( 7394):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7394): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7394): onReceive
,D/LgDataFeature( 7394): LgDataFeature() Constructor: none
D/LgDataFeature( 7394): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7394): Context : android.app.ReceiverRestrictedContext@1217b84b
D/AppUp4:CustFacade( 7394): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7394): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7394): begin check event
I/AppUp4:CustModeStarterReceiver( 7394): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7394): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7394): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7394): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7394): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6170:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6170/cgroup.procs: No such file or directory
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3362): DownloadService onCreate
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@227a841e on behalf of 3362
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@f9f94ff on behalf of 3362
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7423 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@24c6c42a on behalf of 3362
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 20.866ms
V/DownloadManager( 3362): processing inserted download 1
,V/DownloadManager( 3362): processing inserted download 4
V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
,V/DownloadManager( 3362): processing inserted download 17
V/DownloadManager( 3362): processing inserted download 18
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.135ms total 24.804ms
V/DownloadManager( 3362): processing inserted download 21
V/DownloadManager( 3362): DownloadService onDestroy
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 28.682ms
,W/ResourcesManager( 7423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7423): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7423): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7423): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7423): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7423): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7423): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7423): LgDataFeature() Constructor: none
,D/LgDataFeature( 7423): LgDataFeature() Constructor Done, null
,D/eas_req ( 7423): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7456 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7423): JNI_OnLoad()
,I/HubEmail( 7423): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7423): registerNatives()
I/HubEmail( 7423): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7423): registerNativeMethods()
I/HubEmail( 7423): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7423): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6603:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6603/cgroup.procs: No such file or directory
,W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3314): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3314): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3314): networkInfo.isConnected() = false
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7350): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524295
I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7484 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7350): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7350): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7350): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7350): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7350): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7350): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7350): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7350): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 80774(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.524ms total 227.573ms
,W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7456): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7456): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7532 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6749:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6749/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6777:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6777/cgroup.procs: No such file or directory
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7552 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6850:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6850/cgroup.procs: No such file or directory
I/art     ( 7552): Almond Protected OAT
D/WeatherApplication( 7552): removeAccount
D/WeatherApplication( 7552): Account.length = 0
E/WeatherApplication( 7552): OPERATOR:OPEN
D/WeatherAncestor( 7552): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:48
D/Weather.Utils( 7552): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7552): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7552): 2 : This is isUpdating : false
D/WeatherAncestor( 7552): connectivity changed - connection : true
D/WeatherService( 7552): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7552): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7552): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7552): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7552): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7552): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:48
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7108): BLE supported!!
I/jxcore-log( 7108): 
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7573 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6798:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6798/cgroup.procs: No such file or directory
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7573): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7573): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7573): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7573): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
I/WebViewFactory( 7573): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5494): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LibraryLoader( 7573): Loading: webviewchromium
,I/LibraryLoader( 7573): Time to load native libraries: 7 ms (timestamps 1235-1242)
I/LibraryLoader( 7573): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7573): Binding Chromium to main looper Looper (main, tid 1) {3d4df722}
,I/LibraryLoader( 7573): Expected native library version number "",actual native library version number ""
I/chromium( 7573): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7573): Initializing chromium process, renderers=0
,W/art     ( 7573): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7573): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7573): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7573): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb15242e0, uid 10093
W/AudioManagerAndroid( 7573): Requires BLUETOOTH permission
,I/Adreno-EGL( 7573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7573): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7573): Build Date: 12/12/14 금
I/Adreno-EGL( 7573): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7573): Remote Branch: 
I/Adreno-EGL( 7573): Local Patches: 
I/Adreno-EGL( 7573): Reconstruct Branch: 
,I/NSApplication( 7573): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7634 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6874:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6874/cgroup.procs: No such file or directory
,W/ResourcesManager( 7634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ContextImpl( 6665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSActivity( 2096): [ac] getting account id
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7394): onReceive
D/AppUp4:CustFacade( 7394): Context : android.app.ReceiverRestrictedContext@1217b84b
D/AppUp4:CustFacade( 7394): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7394): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7394): begin check event
I/AppUp4:CustModeStarterReceiver( 7394): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2096): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3362): DownloadService onCreate
I/DownloadManager( 3362): in removeSpuriousFiles
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@31f7cfb8 on behalf of 3362
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@7e4f8f6 on behalf of 3362
,V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@6362f64 on behalf of 3362
W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3362): processing inserted download 1
W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3362): processing inserted download 4
V/DownloadManager( 3362): processing inserted download 7
I/LgeMiscReceiver( 3314): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3314): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3314): networkInfo.isConnected() = false
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3362): processing inserted download 16
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
,V/DownloadManager( 3362): processing inserted download 17
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
V/DownloadManager( 3362): processing inserted download 18
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3362): processing inserted download 21
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/WeatherAncestor( 7552): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:50
V/DownloadManager( 3362): DownloadService onDestroy
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/Weather.Utils( 7552): 2 : the weather widgets(using time tick) are gone.
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/Weather.Utils( 7552): 2 : All the weather widget is gone.
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/UpdateThreadPoolManager( 7552): 2 : This is isUpdating : false
D/WeatherAncestor( 7552): connectivity changed - connection : true
D/WeatherService( 7552): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@39e9cb41
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/ForecastDataCache( 7552): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7552): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7552): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7552): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7552): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:50
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7394): [onReceive] request level :IDLE....
V/FormManager( 7456): There are no updated forms. The schedule will be deleted.
I/AppUp4:CustModeStarterReceiver( 7394): onReceive
D/AppUp4:CustFacade( 7394): Context : android.app.ReceiverRestrictedContext@1217b84b
D/AppUp4:CustFacade( 7394): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7394): isPhone : true
V/FormManager( 7456): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustModeStarterReceiver( 7394): begin check event
I/AppUp4:CustModeStarterReceiver( 7394): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3362): DownloadService onCreate
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@3ddfae82 on behalf of 3362
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@39f51993 on behalf of 3362
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@1cde30ce on behalf of 3362
V/DownloadManager( 3362): processing inserted download 1
V/DownloadManager( 3362): processing inserted download 4
,V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
V/DownloadManager( 3362): processing inserted download 18
V/DownloadManager( 3362): processing inserted download 21
I/LgeMiscReceiver( 3314): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3314): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3314): networkInfo.isConnected() = true
D/PhoneState( 3314): setPdpRejectCasuse : false
E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3362): DownloadService onDestroy
D/WeatherAncestor( 7552): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:50
D/Weather.Utils( 7552): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7552): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7552): 2 : This is isUpdating : false
D/WeatherAncestor( 7552): connectivity changed - connection : true
D/WeatherService( 7552): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@39e9cb41
D/ForecastDataCache( 7552): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7552): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7552): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7552): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7552): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:54:50
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7456): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7456): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = www.google.com succeed
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
D/UEI.SmartControl( 6815): Internal timer expired: 3
D/UEI.SmartControl( 6815): unbind internal service
,D/serial_port( 6815): close(fd = 24)
,I/UEI.SmartControl( 6815): Serial port is closed.
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1ebe5f92 type 2 when 323845 android} when 323845
,V/QRemote ( 7265): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7265): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4340
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{15195d63 type 2 when 324146 com.google.android.gms} when 324146
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2096): Connected
,D/GCM     ( 2096): Message class com.google.f.a.a.p
,I/GAV4    ( 7573): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1037): Killing 6899:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6899/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337843252479; DSPS: 11211116; Offset : -4306500942
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=694256919, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=694256919 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357844436638; DSPS: 11866515; Offset : -4306506968
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 25678(1220KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 3.111ms total 199.368ms
,I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2096): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2096): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2096): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2096): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/PlayEventLogger( 6262): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6262): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6262): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6262): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6262): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6262): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6262): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6262): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377846613662; DSPS: 12521946; Offset : -4306496771
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397848596987; DSPS: 13177371; Offset : -4306497011
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417851345053; DSPS: 13832821; Offset : -4306495501
,I/[SystemUI]LGPowerUI( 1478): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1478): On Skip Timer : true
,D/WifiController( 1037): battery changed pluggedType: 2
,D/LEDHandler( 1935): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1935): Battery Level Remaining: 100%
D/LEDHandler( 1935): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1478): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1478): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1478): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3786): Disconnected process message: 10, size: 0
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437853503639; DSPS: 14488252; Offset : -4306503792
,I/jxcore-log( 7108): --- start :testFindPeers.js---
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): testFindPeers created [object Object]
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): serverPort is 8876
I/jxcore-log( 7108): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3064
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7108): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3786): [BTUI] createSocketChannel FD=84 mFd=82
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): start: OK
I/io.jxcore.node.ConnectionHelper( 7108): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3064
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7108): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7108): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@719ee5fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@719ee5fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433303634222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433303634222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/LGWifiP2pService( 1037): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7108): start: OK
I/jxcore-log( 7108): StartBroadcasting started ok
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7108): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7108): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 63000101000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 63000101000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 63000101000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] is available
I/jxcore-log( 7108): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1947","peerAvailable":true}]
I/jxcore-log( 7108): 
I/jxcore-log( 7108): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): weAreDoneNow
I/jxcore-log( 7108): 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/jxcore-log( 7108): done, now sending data to server
I/jxcore-log( 7108): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] is available
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884] is available
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382] is available
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=55 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457855499567; DSPS: 15143677; Offset : -4306491222
,I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01],
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=61 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=64 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thalip,roject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477861176020; DSPS: 15799223; Offset : -4306491271
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=73 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] is available
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=80 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=87 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] is available
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497863343095; DSPS: 16454654; Offset : -4306491075
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=93 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=94 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=95 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=98 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
,I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] is available
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000106000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000106000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027],
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000106000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] already in the list, will not add again
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=104 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=106 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517865487254; DSPS: 17110084; Offset : -4306482835
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=110 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=111 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=114 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ whe,n=-13ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-26ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-26ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-28ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-29ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-29ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-30ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-30ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-30ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-30ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-30ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-31ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-33ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-33ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-33ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState receive service response,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792],
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001060a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001060a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=120 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=43 target=com.android.intern,al.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=122 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=124 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=127 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] already in the list, will not add again
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-25ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-25ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=128 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] is available
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=129 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382] already in the list, will not add again,
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027],
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=130 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] already in the list, will not add again
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=131 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001070a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=132 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.th,aliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537867518757; DSPS: 17765511; Offset : -4306495905
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=135 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDe,viceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=694256919, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{14852ac1 type 2 when 542005 android} when 542005
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=694256919 [*alarm*], flags=0x0
,I/BooksSync( 6963): Starting books sync
,D/BooksSync( 6963): started syncMyEbooks
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=139 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2096): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2096): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2096): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2096): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6963): Authentication error
E/BooksAccountManager( 6963): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6963): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6963): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6963): null auth token
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=140 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=141 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=142 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully,
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=144 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
,I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78,
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000109000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000109000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000109000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=146 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000109000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] is available
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000109000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000109000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=147 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000109000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
W/ApiaryClient( 6963): Error response from books API: {
W/ApiaryClient( 6963):  "error": {
W/ApiaryClient( 6963):   "errors": [
W/ApiaryClient( 6963):    {
W/ApiaryClient( 6963):     "domain": "global",
W/ApiaryClient( 6963):     "reason": "required",
W/ApiaryClient( 6963):     "message": "Login Required",
W/ApiaryClient( 6963):     "locationType": "header",
W/ApiaryClient( 6963):     "location": "Authorization"
W/ApiaryClient( 6963):    }
W/ApiaryClient( 6963):   ],
W/ApiaryClient( 6963):   "code": 401,
W/ApiaryClient( 6963):   "message": "Login Required"
W/ApiaryClient( 6963):  }
W/ApiaryClient( 6963): }
,W/ApiaryClient( 6963): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6963): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1470323364659177509&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6963): Headers:
W/ApiaryClient( 6963): accept-encoding: [gzip]
W/ApiaryClient( 6963): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6963): gdata-version: 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=148 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2096): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2096): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2096): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2096): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6963): Authentication error
E/BooksAccountManager( 6963): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6963): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6963): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6963): null auth token
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=149 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/ApiaryClient( 6963): Error response from books API: {
W/ApiaryClient( 6963):  "error": {
W/ApiaryClient( 6963):   "errors": [
W/ApiaryClient( 6963):    {
W/ApiaryClient( 6963):     "domain": "global",
W/ApiaryClient( 6963):     "reason": "required",
W/ApiaryClient( 6963):     "message": "Login Required",
W/ApiaryClient( 6963):     "locationType": "header",
W/ApiaryClient( 6963):     "location": "Authorization"
W/ApiaryClient( 6963):    }
W/ApiaryClient( 6963):   ],
W/ApiaryClient( 6963):   "code": 401,
W/ApiaryClient( 6963):   "message": "Login Required"
W/ApiaryClient( 6963):  }
W/ApiaryClient( 6963): }
,W/ApiaryClient( 6963): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6963): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1470323364659177509&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6963): Headers:
W/ApiaryClient( 6963): accept-encoding: [gzip]
W/ApiaryClient( 6963): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6963): gdata-version: 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=150 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/GLSUser ( 2096): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2096): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2096): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2096): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1416): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1416): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1416): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1416): handleNotificationPosted(true)
D/QuickCircle( 1416): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1416): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): post do just update job
D/LgeQuickCoverNotificationData( 1416): showAll3
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1416): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1416): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1416): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1416): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1416): updateNotificationData: count=3
W/GLSActivity( 2096): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2096): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2096): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2096): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2096): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6963): Authentication error
E/BooksAccountManager( 6963): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6963): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6963): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6963): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6963): null auth token
D/QuickStatusbarLayout( 1416): Notification difference=198
D/QuickStatusbarLayout( 1416): child = android.widget.LinearLayout{39f51993 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6963): Error response from books API: {
W/ApiaryClient( 6963):  "error": {
W/ApiaryClient( 6963):   "errors": [
W/ApiaryClient( 6963):    {
W/ApiaryClient( 6963):     "domain": "global",
W/ApiaryClient( 6963):     "reason": "required",
W/ApiaryClient( 6963):     "message": "Login Required",
W/ApiaryClient( 6963):     "locationType": "header",
W/ApiaryClient( 6963):     "location": "Authorization"
W/ApiaryClient( 6963):    }
W/ApiaryClient( 6963):   ],
W/ApiaryClient( 6963):   "code": 401,
W/ApiaryClient( 6963):   "message": "Login Required"
W/ApiaryClient( 6963):  }
W/ApiaryClient( 6963): }
,W/ApiaryClient( 6963): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6963): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1470323364659177509&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6963): Headers:
W/ApiaryClient( 6963): accept-encoding: [gzip]
W/ApiaryClient( 6963): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6963): gdata-version: 2
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=151 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01],
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01
E/BooksSync( 6963): Soft error: 
E/BooksSync( 6963): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6963): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1470323364659177509&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6963): Headers:
E/BooksSync( 6963): accept-encoding: [gzip]
E/BooksSync( 6963): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6963): gdata-version: 2
E/BooksSync( 6963): 
E/BooksSync( 6963): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6963): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6963): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6963): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6963): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6963): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6963): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6963): {
E/BooksSync( 6963):  "error": {
E/BooksSync( 6963):   "errors": [
E/BooksSync( 6963):    {
E/BooksSync( 6963):     "domain": "global",
E/BooksSync( 6963):     "reason": "required",
E/BooksSync( 6963):     "message": "Login Required",
E/BooksSync( 6963):     "locationType": "header",
E/BooksSync( 6963):     "location": "Authorization"
E/BooksSync( 6963):    }
E/BooksSync( 6963):   ],
E/BooksSync( 6963):   "code": 401,
E/BooksSync( 6963):   "message": "Login Required"
E/BooksSync( 6963):  }
E/BooksSync( 6963): }
E/BooksSync( 6963): 
E/BooksSync( 6963): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6963): 	... 8 more
,E/BooksSync( 6963): Sync error
E/BooksSync( 6963): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6963): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1470323364659177509&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6963): Headers:
E/BooksSync( 6963): accept-encoding: [gzip]
E/BooksSync( 6963): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6963): gdata-version: 2
E/BooksSync( 6963): 
E/BooksSync( 6963): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6963): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6963): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6963): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6963): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6963): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6963): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6963): {
E/BooksSync( 6963):  "error": {
E/BooksSync( 6963):   "errors": [
E/BooksSync( 6963):    {
E/BooksSync( 6963):     "domain": "global",
E/BooksSync( 6963):     "reason": "required",
E/BooksSync( 6963):     "message": "Login Required",
E/BooksSync( 6963):     "locationType": "header",
E/BooksSync( 6963):     "location": "Authorization"
E/BooksSync( 6963):    }
E/BooksSync( 6963):   ],
E/BooksSync( 6963):   "code": 401,
E/BooksSync( 6963):   "message": "Login Required"
E/BooksSync( 6963):  }
E/BooksSync( 6963): }
E/BooksSync( 6963): 
E/BooksSync( 6963): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6963): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6963): 	... 8 more
I/BooksSync( 6963): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 542005, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=153 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=154 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=155 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=156 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=157 dispatchEvent: P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557869460467; DSPS: 18420935; Offset : -4306507424
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 7 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 7 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 7 120001040a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=161 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=162 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 6300010a000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 6300010a000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=164 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 6300010a000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224c47452d4c472d443732325f505431393437222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1947","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] already in the list, will not add again
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=165 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=166 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=167 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=168 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ wh,en=0 what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=63 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=63 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=170 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=171 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001070a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=172 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139310 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=173 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/jxcore-log( 7108): teardown
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): testFindPeers stopped
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2669): P2P-FIND-STOPPED 
D/WfdsMonitor( 1935): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=174 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=694256919, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{379ca523 type 2 when 572199 android} when 572199
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7108): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setState: NOT_STARTED
I/jxcore-log( 7108): StopBroadcasting went ok
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7108): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7108): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=694256919 [*alarm*], flags=0x0
,I/jxcore-log( 7108): --- start :testSendData.js---
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 7108): 
I/jxcore-log( 7108): daya100000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): check server
I/jxcore-log( 7108): 
I/jxcore-log( 7108): serverPort is 58156
I/jxcore-log( 7108): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3064
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7108): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): start: OK
I/io.jxcore.node.ConnectionHelper( 7108): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3064
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7108): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7108): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@719ee5fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@719ee5fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433303634222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433303634222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=175 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7108): start: OK
I/jxcore-log( 7108): StartBroadcasting started ok
I/jxcore-log( 7108): 
I/jxcore-log( 7108): null
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:00.876Z SendDataTCPServer.js: TCP/IP server is bound to port: 58156
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2669): P2P-FIND-STOPPED 
D/WfdsMonitor( 1935): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=176 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7108): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/chromium( 7108): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=177 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.Dis,coveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=179 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=180 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=182 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=183 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=184 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505433373932222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] already in the list, will not add again
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577872064940; DSPS: 19076380; Offset : -4306497049
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=185 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=187 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=188 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=189 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=190 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=191 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=192 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=193 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=194 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=195 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=196 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=197 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=198 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=199 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=200 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=15 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=15 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=201 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=202 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=203 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505431333832222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382] already in the list, will not add again
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=204 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=205 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597874086859; DSPS: 19731806; Offset : -4306489134,
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=207 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=208 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=209 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=210 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=211 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=212 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true,
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState add service request,
,D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=214 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=215 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010e000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505433373834222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010e000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505433373834222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=216 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010e000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505433373834222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] is available
I/jxcore-log( 7108): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT3784","peerAvailable":true}]
I/jxcore-log( 7108): 
I/jxcore-log( 7108): Found peer : motorola-XT1072_PT3784, Available: true
I/jxcore-log( 7108): 
I/jxcore-log( 7108): startWithNextDevice
I/jxcore-log( 7108): 
I/jxcore-log( 7108): device[1]: 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:36.148Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:36.149Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:36.149Z SendDataConnector.js: do connect now
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7108): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 821)
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 6800010e000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 6800010e000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=217 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 6800010e000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] already in the list, will not add again
W/LGMDMUISystemServiceAdapter( 7108): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3786): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3786): [BTUI] connectSocket FD=85 mFd=84
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:e7:c4:e6:4c:f8 7 6600010e000a436f72646f7661703270c00c000c01507b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a224854432d485443204f6e65204d38735f5054333735222c227261223a2239303a45373a43343a46363a36393a3737227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:e7:c4:e6:4c:f8 7 6600010e000a436f72646f7661703270c00c000c01507b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a224854432d485443204f6e65204d38735f5054333735222c227261223a2239303a45373a43343a46363a36393a3737227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-SERV-DISC-RESP 92:e7:c4:e6:4c:f8 7 6600010e000a436f72646f7661703270c00c000c01507b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a224854432d485443204f6e65204d38735f5054333735222c227261223a2239303a45373a43343a46363a36393a3737227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] is available,
I/jxcore-log( 7108): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT375","peerAvailable":true}]
I/jxcore-log( 7108): 
I/jxcore-log( 7108): Found peer : HTC-HTC One M8s_PT375, Available: true,
,I/jxcore-log( 7108): 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 7 6300010e000a436f72646f7661703270c00c000c014d7b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224c47452d4e6578757320355f505431353130222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 7 6300010e000a436f72646f7661703270c00c000c014d7b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224c47452d4e6578757320355f505431353130222c227261223a2233343a46433a45463a31313a41453a3637227dc027],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=219 dispatchEvent: P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 7 6300010e000a436f72646f7661703270c00c000c014d7b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224c47452d4e6578757320355f505431353130222c227261223a2233343a46433a45463a31313a41453a3637227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 7108): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] is available
I/jxcore-log( 7108): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT1510","peerAvailable":true}]
I/jxcore-log( 7108): 
I/jxcore-log( 7108): Found peer : LGE-Nexus 5_PT1510, Available: true
I/jxcore-log( 7108): 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=220 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=221 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 1
W/bt-s,dp  ( 3786): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3786): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3786): invalid rfc slot id: 8,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 821)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Maximum number of allowed retries (0) reached, giving up... (thread ID: 821)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Exiting thread (thread ID: 821)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/jxcore-log( 7108): 2015-12-22T00:59:42.766Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] failed
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:42.766Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] failed
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:42.766Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7108): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): shutdown (thread ID: 821)
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=222 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01],
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=224 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=225 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617895816695; DSPS: 20387878; Offset : -4306488126
,I/jxcore-log( 7108): 2015-12-22T00:59:47.769Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T00:59:47.775Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=226 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=227 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=228 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=229 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=230 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 7108): 2015-12-22T00:59:52.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:52.785Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:52.786Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:52.787Z SendDataConnector.js: do connect now
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7108): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 823)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7108): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7108): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3786): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=231 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=232 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=233 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18,:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=234 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001100a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=235 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
,I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=236 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=237 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] already in the list, will not add again
,I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=238 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=239 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
W/bt-btm  ( 3786): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-btm  ( 3786): btm_acl_created hci_handle=2 link_role=0  transport=1
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3786): btm_read_remote_version_complete: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3786): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3786): btm_process_remote_ext_features_page 0: BDA: 44-80-eb-7b-5a-05
,W/bt-btm  ( 3786): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3786): btm_process_remote_ext_features_page 1: BDA: 44-80-eb-7b-5a-05
,W/bt-btif ( 3786): info:x10
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3786): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3786): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3786): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3786): process_service_search_attr_rsp
W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0041
W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 21
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b97f077:true
,D/LGBluetoothFeatureConfig( 7204): isPrivacyLogsEnabled : true
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL connected => AclLinkCount = 1
,I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3786): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3786): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3786): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3786): Entering PendingCommandState State
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7801 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35234d4d:true
,I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothRemoteDevices( 3786): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3786): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3786): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3786): StableState(): Entering Off State
,E/ActivityThread( 7801): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7801): No ProfileInfo entries
I/LG Account v2.2( 7801): isEnabled: false
I/Feature ( 7801): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7801): [Lifetracker]Country: EU
I/Feature ( 7801): [Lifetracker]Operator: OPEN
I/Feature ( 7801): [Lifetracker]Ranking support: false
I/Feature ( 7801): [Lifetracker]Comfort support: false
,I/Feature ( 7801): [Lifetracker]Accessory: true
I/Feature ( 7801): [Lifetracker]Health device: true
I/Feature ( 7801): [Lifetracker]Extra Pedometer: false
I/Feature ( 7801): [Lifetracker]Blood glucose device: false
I/Feature ( 7801): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 6262:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6262/cgroup.procs: No such file or directory
,W/bt-btm  ( 3786): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0043,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0043,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3786): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3786): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3786): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3786): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 823)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesWritten: 77 bytes successfully written (thread ID: 824)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Outgoing connection initialized (*handshake* thread ID: 824)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Exiting thread (thread ID: 823)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Entering thread (ID: 824)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesRead: Read 81 bytes successfully (thread ID: 824)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Exiting thread (ID: 824)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7108): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7108): Entering thread (ID: 825)
D/io.jxcore.node.OutgoingSocketThread( 7108): Server socket local port: 51388
I/io.jxcore.node.OutgoingSocketThread( 7108): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 7108): onListeningForIncomingConnections: Outgoing connection is using port 51388 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 7108): 2015-12-22T00:59:58.904Z SendDataConnector.js: CLIENT connected to 51388, error: null
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:58.904Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7108): 
,I/io.jxcore.node.OutgoingSocketThread( 7108): Incoming data from address: /127.0.0.1, port: 51388
D/io.jxcore.node.OutgoingSocketThread( 7108): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7108): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7108): Exiting thread (ID: 825)
I/jxcore-log( 7108): 2015-12-22T00:59:58.934Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7108): 
D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 827, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 826, name: Sender)
D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29928
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22998
,I/jxcore-log( 7108): 2015-12-22T00:59:59.664Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7108): 
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12108
I/jxcore-log( 7108): 2015-12-22T00:59:59.703Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T00:59:59.740Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T00:59:59.752Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7108): 
D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 7108): 2015-12-22T00:59:59.835Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T00:59:59.897Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T00:59:59.963Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:00.001Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7108): 
,I/[SystemUI]TimeTickManager( 1478): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1478): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1478): called onTimeUpdated()
I/[SystemUI]Clock( 1478): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
I/[SystemUI]DateView( 1478): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1478): handleTimeUpdate
I/jxcore-log( 7108): 2015-12-22T01:00:00.127Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:00.140Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:00.141Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): oneRoundDownNow
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:00.154Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:00.154Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7108): 
D/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 7108): close
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 827
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 826
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 826, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7108): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 827, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 826, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 827, name: Receiver)
I/jxcore-log( 7108): 2015-12-22T01:00:00.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7108): 
I/jxcore-log( 7108): ---- round done--------
I/jxcore-log( 7108): 
I/jxcore-log( 7108): startWithNextDevice
I/jxcore-log( 7108): 
I/jxcore-log( 7108): device[2]: 90:E7:C4:F6:69:77
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:00.171Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:00.171Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:00.171Z SendDataConnector.js: do connect now
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7108): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 828)
W/LGMDMUISystemServiceAdapter( 7108): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3786): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-rfcomm( 3786): rfc_port_closed
W/bt-btif ( 3786): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0042
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010d0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=240 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010d0a436f72646f7661703270c00c000c01
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=694256919, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7854 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7854): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7854): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2279be3c
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=694256919 [*alarm*], flags=0x0
I/ActivityManager( 1037): Killing 7241:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7241/cgroup.procs: No such file or directory
,W/bt-btm  ( 3786): btm_acl_created hci_handle=3 link_role=1  transport=1
W/bt-btm  ( 3786): btm_acl_created hci_handle=3 link_role=0  transport=1
,W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btm  ( 3786): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3786): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3786): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3786): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3786): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
,W/bt-btif ( 3786): info:x10
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3786): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3786): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3786): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL connected => AclLinkCount = 2
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3786): process_service_search_attr_rsp
W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0043
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 21
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=241 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 3786): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3786): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3786): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3786): Entering PendingCommandState State
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
D/BluetoothRemoteDevices( 3786): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3786): Failed to remove device: 90:E7:C4:F6:69:77
I/BluetoothBondStateMachine( 3786): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3786): StableState(): Entering Off State
W/bt-btm  ( 3786): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0041,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0041,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 828)
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3786): new conn_srvc id:26, app_id:1
W/bt-btif ( 3786): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3786): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3786): bta_dm_pm_ssr:2, lat:1200
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesWritten: 77 bytes successfully written (thread ID: 829)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Outgoing connection initialized (*handshake* thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Exiting thread (thread ID: 828)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Entering thread (ID: 829)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesRead: Read 80 bytes successfully (thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Exiting thread (ID: 829)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
,I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7108): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7108): Entering thread (ID: 830)
,D/io.jxcore.node.OutgoingSocketThread( 7108): Server socket local port: 37724
I/io.jxcore.node.OutgoingSocketThread( 7108): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7108): onListeningForIncomingConnections: Outgoing connection is using port 37724 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 7108): 2015-12-22T01:00:03.438Z SendDataConnector.js: CLIENT connected to 37724, error: null
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:03.438Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7108): 
,I/io.jxcore.node.OutgoingSocketThread( 7108): Incoming data from address: /127.0.0.1, port: 37724
D/io.jxcore.node.OutgoingSocketThread( 7108): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7108): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7108): Exiting thread (ID: 830)
I/jxcore-log( 7108): 2015-12-22T01:00:03.450Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7108): 
D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 832, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 831, name: Sender)
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=242 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=243 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:3,7:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=39 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=39 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706,
,I/jxcore-log( 7108): 2015-12-22T01:00:04.243Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7108): 
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
I/jxcore-log( 7108): 2015-12-22T01:00:04.282Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7108): 
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 7108): 2015-12-22T01:00:04.320Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:04.363Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:04.391Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:04.453Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7108): 
,E/bt-btm  ( 3786): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1037): Connected BT device : -1
I/BluetoothMapService( 3786): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3786): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3786): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3786): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3786): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3786): state: -2147483648
,I/jxcore-log( 7108): 2015-12-22T01:00:04.556Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.560Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7108): 
,D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL disconnected => AclLinkCount = 1
,I/jxcore-log( 7108): 2015-12-22T01:00:04.602Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.603Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7108): 
I/jxcore-log( 7108): oneRoundDownNow
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.603Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.603Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7108): 
D/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 7108): close
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 832
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 831
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 831, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7108): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 832, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 831, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 832, name: Receiver)
I/jxcore-log( 7108): 2015-12-22T01:00:04.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7108): 
I/jxcore-log( 7108): ---- round done--------
I/jxcore-log( 7108): 
I/jxcore-log( 7108): startWithNextDevice
I/jxcore-log( 7108): 
I/jxcore-log( 7108): device[3]: 34:FC:EF:11:AE:67
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.614Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.614Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:04.614Z SendDataConnector.js: do connect now
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnecting:, null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7108): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 833)
,W/LGMDMUISystemServiceAdapter( 7108): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7108): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3786): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20911d13:true
,I/BTConnectionReceiver( 4601): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4601): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=244 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-rfcomm( 3786): rfc_port_closed
W/bt-btif ( 3786): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0044
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-btm  ( 3786): btm_acl_created hci_handle=4 link_role=1  transport=1
,W/bt-btm  ( 3786): btm_acl_created hci_handle=4 link_role=0  transport=1
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3786): btm_read_remote_version_complete: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3786): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139310 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001110a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=245 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-btm  ( 3786): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3786): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3786): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-ae-67
W/bt-btif ( 3786): info:x10
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3786): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3786): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3786): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3786): process_service_search_attr_rsp
W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0045
,D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL connected => AclLinkCount = 2
W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3786): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 21
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000111000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000111000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=246 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000111000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431393033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3786): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3786): checkBluetoothPairing btPolicy: false
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1903","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] already in the list, will not add again
I/BluetoothBondStateMachine( 3786): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3786): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothRemoteDevices( 3786): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3786): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3786): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
W/bt-btm  ( 3786): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3786): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
I/BluetoothBondStateMachine( 3786): StableState(): Entering Off State
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0047,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0047,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3786): new conn_srvc id:26, app_id:1
W/bt-btif ( 3786): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3786): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3786): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesWritten: 77 bytes successfully written (thread ID: 834)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Outgoing connection initialized (*handshake* thread ID: 834)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Exiting thread (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Entering thread (ID: 834)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): onBytesRead: Read 77 bytes successfully (thread ID: 834)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7108): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Exiting thread (ID: 834)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7108): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7108): Entering thread (ID: 835)
D/io.jxcore.node.OutgoingSocketThread( 7108): Server socket local port: 36641
I/io.jxcore.node.OutgoingSocketThread( 7108): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7108): onListeningForIncomingConnections: Outgoing connection is using port 36641 (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 7108): 2015-12-22T01:00:05.962Z SendDataConnector.js: CLIENT connected to 36641, error: null
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:05.963Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7108): 
,I/io.jxcore.node.OutgoingSocketThread( 7108): Incoming data from address: /127.0.0.1, port: 36641
D/io.jxcore.node.OutgoingSocketThread( 7108): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7108): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7108): Exiting thread (ID: 835)
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=247 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 7 1200010b0a436f72646f7661703270c00c000c01
D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 837, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 836, name: Sender)
I/jxcore-log( 7108): 2015-12-22T01:00:06.001Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7108): 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637900354917; DSPS: 21043387; Offset : -4306494315
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29928
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:21018
,I/jxcore-log( 7108): 2015-12-22T01:00:06.716Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7108): 
W/bt-l2cap( 3786): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3786): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
,W/bt-btm  ( 3786): btm_acl_role_changed: New role: 0
,I/jxcore-log( 7108): 2015-12-22T01:00:07.007Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7108): 
,D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13098
,I/jxcore-log( 7108): 2015-12-22T01:00:07.082Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:07.087Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7108): 
D/        ( 3786): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 7108): 2015-12-22T01:00:07.141Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7108): 
,W/bt-btm  ( 3786): btm_acl_created hci_handle=1 link_role=1  transport=1
W/bt-btm  ( 3786): btm_acl_created hci_handle=1 link_role=0  transport=1
I/jxcore-log( 7108): 2015-12-22T01:00:07.183Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:07.193Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:07.234Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:07.291Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7108): 
,W/bt-btm  ( 3786): btm_read_remote_version_complete: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3786): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,I/jxcore-log( 7108): 2015-12-22T01:00:07.341Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:07.341Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7108): 
I/jxcore-log( 7108): oneRoundDownNow
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:07.342Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:07.343Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7108): 
D/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 7108): close
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 837
D/io.jxcore.node.OutgoingSocketThread( 7108): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 836
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 836, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7108): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7108): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 837, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7108): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 836, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 837, name: Receiver)
,I/jxcore-log( 7108): 2015-12-22T01:00:07.357Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7108): 
I/jxcore-log( 7108): ---- round done--------
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): startWithNextDevice
I/jxcore-log( 7108): 
W/bt-rfcomm( 3786): rfc_port_closed,
,W/bt-btif ( 3786): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-l2cap( 3786): L2CA_DisconnectReq()  CID: 0x0046
,W/bt-l2cap( 3786): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-btm  ( 3786): btm_process_remote_ext_features_page 0: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3786): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3786): btm_process_remote_ext_features_page 1: BDA: b0-c5-59-3f-75-69
W/bt-btif ( 3786): info:x10
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3786): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3786): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3786): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL connected => AclLinkCount = 3
,W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3786): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3786): L2CA_ErtmConnectRsp()  CID: 0x0047  Result: 0  Status: 0  BDA: b0c5593f7569  p_ertm_info:0x00000000
W/bt-l2cap( 3786): L2CAP - st: W4_L2CA_CON_RSP evt: 22
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3786): L2CA_DisconnectRsp()  CID: 0x0047
W/bt-l2cap( 3786): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 3786): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3786): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3786): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3786): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3786): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothRemoteDevices( 3786): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3786): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3786): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3786): StableState(): Entering Off State
W/bt-btm  ( 3786): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3786): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3786): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3786): L2CA_ErtmConnectRsp()  CID: 0x0048  Result: 0  Status: 0  BDA: b0c5593f7569  p_ertm_info:0x00000000
W/bt-l2cap( 3786): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3786): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3786): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3786): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Incoming connection initialized (thread ID: 838)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Waiting for incoming connections...
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3786): new conn_srvc id:26, app_id:255
W/bt-btif ( 3786): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3786): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3786): bta_dm_pm_ssr:2, lat:1200
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Entering thread (ID: 838)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): onBytesRead: Read 82 bytes successfully (thread ID: 838)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): onBytesWritten: 77 bytes successfully written (thread ID: 838)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): removeThreadFromList: Removing thread with ID 838
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Handshake thread disposed (thread ID: 838)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7108): Exiting thread (ID: 838)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/io.jxcore.node.ConnectionHelper( 7108): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7108): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], created successfully
D/io.jxcore.node.ConnectionHelper( 7108): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 7108): Entering thread (ID: 839)
I/io.jxcore.node.IncomingSocketThread( 7108): Local host address: localhost/127.0.0.1, port: 58156
D/io.jxcore.node.IncomingSocketThread( 7108): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7108): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7108): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7108): Exiting thread (ID: 839)
I/jxcore-log( 7108): 2015-12-22T01:00:08.344Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7108): 
,D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 841, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7108): Entering thread (ID: 840, name: Sender)
E/bt-btm  ( 3786): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -2
I/BluetoothMapService( 3786): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3786): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3786): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3786): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3786): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3786): state: -2147483648
I/jxcore-log( 7108): 2015-12-22T01:00:09.193Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.198Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.200Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.203Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7108): 
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL disconnected => AclLinkCount = 2
I/jxcore-log( 7108): 2015-12-22T01:00:09.208Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.212Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.216Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7108): 
I/BTConnectionReceiver( 4601): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4601): Bluetooth Device Name: HTC One M8s
I/jxcore-log( 7108): 2015-12-22T01:00:09.251Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.261Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.264Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.306Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.317Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.352Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.365Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.402Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.418Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.429Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:09.452Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): 2015-12-22T01:00:09.458Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7108): 
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 841, thread name: Receiver): bt socket closed, read return: -1
,W/bt-btif ( 3786): invalid rfc slot id: 7
,E/io.jxcore.node.IncomingSocketThread( 7108): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 839
D/io.jxcore.node.IncomingSocketThread( 7108): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 841
D/io.jxcore.node.IncomingSocketThread( 7108): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7108): doStop: Thread ID: 840
,D/io.jxcore.node.IncomingSocketThread( 7108): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-rfcomm( 3786): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-l2cap( 3786): L2CA_DisconnectRsp()  CID: 0x0048,
W/bt-l2cap( 3786): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-rfcomm( 3786): RFCOMM_DisconnectInd LCID:0x48
W/io.jxcore.node.StreamCopyingThread( 7108): Either failed to read from the output stream or write to the input stream (thread ID: 840, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7108): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7108): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7108): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7108): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7108): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7108): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 840, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7108): Exiting thread (ID: 841, name: Receiver)
I/jxcore-log( 7108): 2015-12-22T01:00:09.589Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7108): 
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/bt-btm  ( 3786): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -3
I/BluetoothMapService( 3786): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3786): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3786): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3786): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3786): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3786): state: -2147483648
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4601): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4601): Bluetooth Device Name: Nexus 5
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=248 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=249 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010e0a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=250 dispatchEvent: P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01
D/btif_config_util( 3786): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3786): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3786): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -4
I/BluetoothMapService( 3786): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3786): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3786): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3786): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3786): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3786): state: -2147483648
D/LGBluetoothPowerSaveListener( 7204): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4601): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4601): Bluetooth Device Name: Thali Test (Galaxy S5)
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=251 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=252 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=253 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=254 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=255 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=256 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=257 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=258 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=259 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001120a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=260 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=261 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000112000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027],
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000112000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=262 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000112000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] already in the list, will not add again
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010f0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=263 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 1200010f0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=264 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=265 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2669): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=266 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86]
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=267 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 657902581420; DSPS: 21698820; Offset : -4306498122
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=268 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=269 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=270 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=271 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=272 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services,
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001130a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=273 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=274 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000113000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672,d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000113000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=275 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000113000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505434333233222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=276 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505438373834222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] already in the list, will not add again
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2,
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001100a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001100a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=277 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 7 120001100a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=278 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=279 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=280 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 68000113000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f5054383834222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884] already in the list, will not add again
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=281 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=282 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=283 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=284 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=285 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=286 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=287 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPee,rs: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7108): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service request added successfully
I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=288 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001140a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2669): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1935): Event [P2P: Reject scan trigger since one is already pending],
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=289 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=290 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service discovery started successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 63000114000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 63000114000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=291 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 63000114000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505438313233222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] already in the list, will not add again
D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000114000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000114000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=292 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000114000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505432303836222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 7108): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7108): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] already in the list, will not add again
I/jxcore-log( 7108): timeout now
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 7108): 
I/jxcore-log( 7108): sendReportNow
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): done, now sending data to server
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:40.904Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7108): 
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2669): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1935): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=293 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2669): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=294 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1935): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1935): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300010b01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300010b01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=295 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300010b01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1935): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300011401]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300011401]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=296 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 9 0300011401
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 677904512662; DSPS: 22354243; Offset : -4306489226
,I/jxcore-log( 7108): teardown
I/jxcore-log( 7108): 
,I/jxcore-log( 7108): testSendData stopped
I/jxcore-log( 7108): 
I/io.jxcore.node.ConnectionHelper( 7108): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7108): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7108): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7108): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7108): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433303634222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2669): P2P-FIND-STOPPED 
D/WfdsMonitor( 1935): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=297 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7108): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7108): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7108): setState: NOT_STARTED
I/jxcore-log( 7108): StopBroadcasting went ok
I/jxcore-log( 7108): 
I/jxcore-log( 7108): 2015-12-22T01:00:46.713Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7108): 
,I/io.jxcore.node.ConnectionHelper( 7108): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7108): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7108): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7108): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7108): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7108): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7108): ****TEST TOOK:  ms ****
I/jxcore-log( 7108): 
I/jxcore-log( 7108): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7108): 
,D/AndroidRuntime( 7928): 
D/AndroidRuntime( 7928): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7928): CheckJNI is OFF
D/AndroidRuntime( 7928): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 7108:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1037): WIN DEATH: Window{2b82ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{2b82ceb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{18dca7a3 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{17747205 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  331): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{24575b50 7108:com.test.thalitest/u0a311}, curProc for 7108: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{17747205 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{17747205 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2027): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2027): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2027): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{d7541db co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{3f5ff478 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1899): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2027): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     ( 4601): Explicit concurrent mark sweep GC freed 33205(1603KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 519us total 59.502ms
I/[LGHome]EVENT( 2027): [Launcher.java:1056:onResume()]onResume end
,D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0,
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,D/LIA_MrGDBLogger_PackageInfoDetector( 3726): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 1990): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3786): [BTUI] [+] updateMediaPlayerInfo
W/System.err( 4539): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4539): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,I/[LGHome]EVENT( 2027): [Launcher.java:1114:onPause()]onPause
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/PostponalbeReceiver( 6665): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/System.err( 4539): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4539): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4539): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4539): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4539): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4539): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4539): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4539): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7959 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1899): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2027): , create_time: 1430558575574
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2027): , create_time: 1430558575600
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1450367114146
I/GBoardWebViewUtils( 2027): , create_time: 1450367114951
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
D/SplitUIManager( 1863): split_name #11 / not available #0
I/[SystemUI]QSlideListController( 1478): onReceive = android.intent.action.PACKAGE_REMOVED
D/SplitUIService( 1863): removed split : 
D/WallpaperManager( 2027): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4f35b28,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1478): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIManager( 1863): split_name #11 / not available #0
I/SplitUIService( 1863): split app #11
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 87652(5MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/67MB, paused 2.033ms total 242.632ms
I/art     ( 1037): WaitForGcToComplete blocked for 209.101ms for cause Explicit
,I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2027): [Launcher.java:5349:onStop()]onStop
D/AppUp4:PreloadHelper( 7394): added Exclude : com.test.thalitest
,I/LockScreenSettings( 7959): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/administrator( 1037): Handling package changes for user 0
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7981 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
,W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3177): Thermal-Lib-Client: Client request sent
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
,I/ActivityManager( 1037): Killing 7423:com.lge.email/u0a23 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/ResourcesManager( 7981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7981): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7981): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7981): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7981): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/[Concierge]WidgetView( 2027): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1478): handleShortcutListChanged...
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_7423/cgroup.procs: No such file or directory
D/[Concierge]Service( 2636): onStartCommand(). Type : 8
D/[Concierge]Service( 2636): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2636): Update widget ID : 11
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{26b60afb u0 com.lge.launcher2/.Launcher t3} time:679625
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]WidgetView( 2027): change position of spinner
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
,W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[Concierge]WidgetView( 2027): initWebView(). Time : 1450746047885
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
D/[Concierge]Service( 2636): onStartCommand(). Type : 0
D/KeyguardModel( 1478): handleShortcutListChanged...
I/[Concierge]WebView( 2027): Return exist ConciergeWebView. Reuse : 923927747
D/[Concierge]WidgetView( 2027): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2027): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@21d7730
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/SystemConfig( 7981): BUILD Country: EU
I/SystemConfig( 7981): BUILD Operator: OPEN
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2027): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2027): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2027): Widget kill message received. Destory myself. My : 1450745396645, New one : 1450746047885
D/[Concierge]WidgetView( 2027): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2027): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1037): Explicit concurrent mark sweep GC freed 15908(882KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.414ms total 243.284ms
I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1037): Killing 7456:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/Timeline( 2027): Timeline: Activity_idle id: android.os.BinderProxy@1339f8a time:679731
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/AndroidRuntime( 7928): Shutting down VM
,W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7456/cgroup.procs: No such file or directory
,I/SystemConfig( 7981): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7981): existFile = false
I/SystemConfig( 7981): canReadFile = false
I/SystemConfig( 7981): systemFeature RCS result false
D/SystemConfig( 7981): refreshRcsSupport() :false
I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/VoicemailCleanupService( 2351): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8004 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.724ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.965ms
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 180us total 9.048ms
,W/ResourcesManager( 8004): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8004): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8004): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8004): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2027): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/LGEmail ( 8004): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8004): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/GBoardtInterface( 2027): onReloaded()
,I/GBoardWebViewClient( 2027): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourceType( 8004): No package identifier when getting value for resource number 0x00000000
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3726): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3726): getSize() : size - 0
,D/LIA_Informant_Tips_SmartTipsActionManager( 3726): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3726): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LgDataFeature( 8004): LgDataFeature() Constructor: none
D/LgDataFeature( 8004): LgDataFeature() Constructor Done, null
,I/PackageChangeReceiver( 8004): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8028 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 7484:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10057/pid_7484/cgroup.procs: No such file or directory
,W/ResourcesManager( 8028): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8028): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8028): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8028): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.

```
