#### Test 50650278923ff9f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 157545366182; DSPS: 5303606; Offset : -4322693743
,D/AndroidRuntime( 7014): 
D/AndroidRuntime( 7014): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7014): CheckJNI is OFF
D/AndroidRuntime( 7014): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1945): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{1c8999fd #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{1c8999fd #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7033 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7014): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1852): Display #0 changed.
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{2fba46 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{3737d407 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7033): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7033): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7033): Loading: webviewchromium
I/LibraryLoader( 7033): Time to load native libraries: 13 ms (timestamps 8506-8519)
I/LibraryLoader( 7033): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7033): Binding Chromium to main looper Looper (main, tid 1) {3d7e6a9b}
I/LibraryLoader( 7033): Expected native library version number "",actual native library version number ""
I/chromium( 7033): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7033): Initializing chromium process, renderers=0
W/art     ( 7033): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  320): registerClient() client 0xb1427080, uid 10311
W/chromium( 7033): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7033): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7033): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23b6de9f:true
I/Adreno-EGL( 7033): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7033): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7033): Build Date: 12/12/14 금
I/Adreno-EGL( 7033): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7033): Remote Branch: 
I/Adreno-EGL( 7033): Local Patches: 
I/Adreno-EGL( 7033): Reconstruct Branch: 
W/chromium( 7033): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7033): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7033): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7033): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7033): CordovaWebView is running on device made by: LGE
W/art     ( 7033): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7033): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7033): Render dirty regions requested: true
I/OpenGLRenderer( 7033): Initialized EGL, version 1.4
D/OpenGLRenderer( 7033): Enabling debug mode 0
D/Atlas   ( 7033): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{17185a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7033): LgDataFeature() Constructor: none
D/LgDataFeature( 7033): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1446): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1446): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1446):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1446): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2a27e198,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 7033): Timeline: Activity_idle id: android.os.BinderProxy@78b308b time:158972
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +608ms (total +705ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{2a2fd6f2 u0 com.test.thalitest/.MainActivity t4} time:158973
D/JsMessageQueue( 7033): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7033): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434941696
,D/JX-Cordova( 7033): jxcore cordova android initializing
E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7033): Initializing JXcore engine
W/jxcore-log( 7033): JXcore engine is ready
,W/jxcore-log( 7033): Starting JXcore engine
W/.test.thalitest( 7033): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7594]" dev="sockfs" ino=7594 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7033): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7033): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7749]" dev="sockfs" ino=7749 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7033): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7033): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[35097]" dev="sockfs" ino=35097 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7033): Background sticky concurrent mark sweep GC freed 123779(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.600ms total 123.155ms
,W/jxcore-log( 7033): Platform android
W/jxcore-log( 7033): 
W/jxcore-log( 7033): Process ARCH arm
W/jxcore-log( 7033): 
,I/jxcore-log( 7033): JXcore Cordova bridge is ready!
I/jxcore-log( 7033): 
W/jxcore-log( 7033): JXcore engine is started
,I/jxcore-log( 7033): Toggling radios to true
I/jxcore-log( 7033): 
,D/BluetoothAdapter( 7033): enable(): BT is already enabled..!
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=7033, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=7033, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1030): disconnect pid=7033, uid=10311, packageName=com.test.thalitest
,D/WifiServiceImplEx( 1030): reconnect pid=7033, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1030):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7033): Radios toggled
I/jxcore-log( 7033): 
E/WifiNative: ( 1030): [162,347,346 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1030): doBoolean: DISCONNECT
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7033): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7033): 
I/jxcore-log( 7033): Perf Test app loaded loaded
I/jxcore-log( 7033): 
I/jxcore-log( 7033): check test folder
I/jxcore-log( 7033): 
,I/jxcore-log( 7033): found test : ./testFindPeers.js
I/jxcore-log( 7033): 
I/jxcore-log( 7033): found test : ./testSendData.js
I/jxcore-log( 7033): 
,I/wpa_supplicant( 2643): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1030): DISCONNECT: returned true
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7122 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2121): Read error: ssl=0xaf4d1e00: I/O error during system call, Connection timed out
V/NativeCrypto( 2121): SSL shutdown failed: ssl=0xaf4d1e00: I/O error during system call, Broken pipe
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine( 1030): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1030):  DisconnectingState CMD_RECONNECT 0 0
I/chromium( 7033): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine( 1030):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1030): [162,517,291 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
I/art     (  346): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 46.090ms
I/wpa_supplicant( 2643): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1030): RECONNECT: returned true
E/WifiStateMachine( 1030):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=162524
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=162524
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/WifiHS20( 1030): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1945): handleWifiStateChangedEvent: 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/chromium( 7033): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7033): 
D/WifiHS20( 1030): hidePasspointNotification off =false
,I/art     (  346): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 22.188ms
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  315): Clearing all IP addresses on wlan0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 180us total 10.267ms
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162557  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1030): hidePasspointNotification off =false
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162558  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524292
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162566  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1030): Removing idletimer
D/TelephonyNetworkFactory-1( 1852): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1030): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162578  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
W/ResourcesManager( 7122): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7122): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7033): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7122): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7122): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7122): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7122): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7122): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7122): [AUTORUN] setTetherStatus() : status=false
I/chromium( 7033): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7033): 
,D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-239ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 2191:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  320): 2191 died, releasing its sessions
V/AudioFlinger(  320):  pid 1852 @ 0
V/AudioFlinger(  320):  pid 3324 @ 1
V/AudioFlinger(  320):  pid 3324 @ 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10034/pid_2191/cgroup.procs: No such file or directory
,I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7158): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7122): LgDataFeature() Constructor: none
D/LgDataFeature( 7122): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
,I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7182 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1030): Killing 6820:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_6820/cgroup.procs: No such file or directory
,W/ResourcesManager( 7182): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7182): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7182): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7182): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7182): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7182): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7182): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7182): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7182): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7158): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7182): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/QRemote ( 7182): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7158): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7158): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
,D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7182): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7182): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7182): LgDataFeature() Constructor: none
D/LgDataFeature( 7182): LgDataFeature() Constructor Done, null
,V/SoundPool( 7182): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7182): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7182): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7182): doLoad: loading sample sampleID=1
V/SoundPool( 7182): Start decode
V/MediaPlayer[Native]( 7182): decode(31, 10857164, 17813)
V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
I/QRemote ( 7182): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
V/AwesomePlayer(  320): AwesomePlayer create()
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474d00, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6866): QS Service created
D/QRemote ( 7182): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7182): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7182): Create singleton instance
I/UEI.SmartControl( 6866): Service initServices...
D/UEI.SmartControl( 6866): QS start get config
,V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
,V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
,V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
,V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
,V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb5474d00, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb5474d00, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795664
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb5474d00, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab700000, 0xb57c0000, 4096)
,D/QRemote ( 7182): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab701000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab702000, 0xb57c0000, 4096)
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab703000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab704000, 0xb57c0000, 4096)
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8968
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab705000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab706000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab707000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab708000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab709000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70a000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70b000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70c000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70d000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70e000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab70f000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab710000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab711000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab712000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab713000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab714000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab715000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab716000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab717000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab718000, 0xb57c0000, 4096)
,V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab719000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
,V/AudioCache(  320): memcpy(0xab71a000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab71b000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab71c000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab71d000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab71e000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab71f000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab720000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
,V/AudioCache(  320): memcpy(0xab721000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab722000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab723000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab724000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab725000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab726000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab727000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab728000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab729000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72a000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72b000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72c000, 0xb57c0000, 4096)
,V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72d000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72e000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab72f000, 0xb57c0000, 4096)
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab730000, 0xb57c0000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  320): write(0xb57c0000, 4096)
V/AudioCache(  320): memcpy(0xab731000, 0xb57c0000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb57c0000, 280)
V/AudioCache(  320): memcpy(0xab732000, 0xb57c0000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb5474d00, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): notify(0xb5474d00, 7, 0, 0)
V/AudioCache(  320): wait - success
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
,D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474d00, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 7182): close(31)
V/SoundPool( 7182): pointer = 0x9fe61000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6866): Supports setup maps: true
D/UEI.SmartControl( 6866): QS start statue = true Error code = 0
I/UEI.SmartControl( 6866): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6866): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6866): ### init IR Blaster...
,D/serial_port( 6866): Configuring serial port
E/UEI.SmartControl( 6866): UEIBLaster setting for 616
I/UEI.SmartControl( 6866): Setting serial record hearder size = 2
I/UEI.SmartControl( 6866): configuring settings for MAXQ616
I/UEI.SmartControl( 6866): Get version...
D/UEI.SmartControl( 6866): serial port data available: 21
,D/UEI.SmartControl( 6866): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6866): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6866): QS saving settings...
,D/UEI.SmartControl( 6866): IR Blaster version: 25672567
D/UEI.SmartControl( 6866): serial port data available: 4
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6866): Device manager: loading config....
D/UEI.SmartControl( 6866): ----------- loading internal config...
E/UEI.SmartControl( 6866): Services init done
,D/UEI.SmartControl( 6866): QS Service init finished
D/UEI.SmartControl( 6866): QS Service version name: 2.1.91
D/UEI.SmartControl( 6866): QS Service version code: 201091
D/UEI.SmartControl( 6866): Service requested: Control
,E/UEI.SmartControl( 6866): Loading SETTINGS...
D/UEI.SmartControl( 6866): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6866): Internal service binding...
,I/QRemote ( 7182): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6866): ------ IControl API: 11
D/UEI.SmartControl( 6866): File observer start...
D/UEI.SmartControl( 6866): -- Open brand translation xml: brands_translations_ko
E/UEI.SmartControl( 6866): IR Port is disabled: false
D/UEI.SmartControl( 6866): Starting file observer...
I/UEI.SmartControl( 6866): Registering callback...
I/UEI.SmartControl( 6866): ------ IControl API: 19
I/UEI.SmartControl( 6866): Registering Services Ready callback...
I/UEI.SmartControl( 6866): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6866): -----service ready thread exits
,I/QRemote ( 7182): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7182): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7182): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7182): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7182): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6866): ------ IControl API: 8
D/QRemote ( 7182): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7182): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7182): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7182): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7182): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7182): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7182): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7182): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7182): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7182): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7182): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450280819054]
,D/QRemote ( 7182): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1030): Killing 6254:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7182): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6254/cgroup.procs: No such file or directory
,V/QRemote ( 7182): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7182): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 7182): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 7182): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2643): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164781  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164816  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7182): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
I/wpa_supplicant( 2643): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2643): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2643): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164903  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164904  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164915
,E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164916
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164918
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164919
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164920
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164921  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7122): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7122): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7122): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164938  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164938  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164939  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164940
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164941
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 7122): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7122): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7122): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/UsbSettingsControl( 7122): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1030): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164999  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=165000  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=165000  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=165006  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=165006  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=165006  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28f21a26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28f21a26 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1030): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2643): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Adding iface wlan0 to network 101
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WfdStateTracker( 1945): handleWifiStateChangedEvent: 1
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 0
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1030): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/TelephonyNetworkFactory-1( 1852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{2e8ec5b2 type 0 when 1450280820133 com.android.vending} when 1450280820133
W/dsqn    ( 7260): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7260): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/DSQN    ( 7260): DSQN ssw
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7182): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 15:47:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450280820240], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450280820216]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/ConnectivityService( 1030): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7267): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7267): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7267): version 5.5.6 starting
E/dhcpcd  ( 7267): get_duid: m
D/dhcpcd  ( 7267): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7267): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dhcpcd  ( 7267): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7267): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7267): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7267): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7267): wlan0: sending REQUEST (xid 0x9010ff82), next in 3.47 seconds
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/art     ( 1030): Explicit concurrent mark sweep GC freed 82511(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.690ms total 163.600ms
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/Finsky  ( 6365): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6365): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6365): [1] 5.onFinished: Scheduling replication attempt 4.
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7182): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7182): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7182): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7158): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7158): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7122): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7122): MCCMNC not supported: null
D/QRemote ( 7182): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7182): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7182): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7182): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7182): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5216): type=WIFI subType= reason=null isConnected=true
D/Tethering( 1030): MasterInitialState.processMessage what=3
W/ContextImpl( 6782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5216): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7281 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7281): onCreate
W/AppUp4:DB( 7281):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7281):  setFingerPrint start
I/AppUp4:DB( 7281):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7281):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7281):  SDK version = 21
I/AppUp4:DB( 7281):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7281): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7281): onReceive
D/LgDataFeature( 7281): LgDataFeature() Constructor: none
D/LgDataFeature( 7281): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7281): Context : android.app.ReceiverRestrictedContext@4ed0e11
D/AppUp4:CustFacade( 7281): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7281): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7281): begin check event
I/AppUp4:CustModeStarterReceiver( 7281): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7281): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7281): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7281): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7281): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 6698:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_6698/cgroup.procs: No such file or directory
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3352): DownloadService onCreate
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3352): in removeSpuriousFiles
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@116f8ae5 on behalf of 3352
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
I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3aee19ba on behalf of 3352
V/DownloadManager( 3352): DownloadService onStartCommand
V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3c12f061 on behalf of 3352
V/DownloadManager( 3352): processing inserted download 1
D/eas_req ( 6849): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3352): processing inserted download 4
V/DownloadManager( 3352): processing inserted download 7
V/DownloadManager( 3352): processing inserted download 8
V/DownloadManager( 3352): processing inserted download 9
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
V/DownloadManager( 3352): processing inserted download 17
V/DownloadManager( 3352): processing inserted download 18
V/DownloadManager( 3352): processing inserted download 21
V/DownloadManager( 3352): DownloadService onDestroy
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7305 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6849): JNI_OnLoad()
I/HubEmail( 6849): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6849): registerNatives()
I/HubEmail( 6849): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6849): registerNativeMethods()
I/HubEmail( 6849): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6849): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3324): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3324): networkInfo.isConnected() = false
I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7328 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{26750686 type 2 when 166148 com.google.android.gms} when 166148
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7305): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7305): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7349 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6273:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_6273/cgroup.procs: No such file or directory
I/ActivityManager( 1030): Killing 6298:com.android.gallery3d/u0a27 (adj 15): empty #17
I/dhcpcd  ( 7267): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6298/cgroup.procs: No such file or directory
I/dhcpcd  ( 7267): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7267): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7267): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7267): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7267): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7267): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7267): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7267): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7370 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6647:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_6647/cgroup.procs: No such file or directory
,I/art     ( 7370): Almond Protected OAT
,D/WeatherApplication( 7370): removeAccount
D/WeatherApplication( 7370): Account.length = 0
E/WeatherApplication( 7370): OPERATOR:OPEN
,D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:1
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:null
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is not up-to-date, count: 0
E/WifiStateMachine( 1030):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1030): identical MTU - not setting
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524295
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:1
I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7404 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6318:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_6318/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7033): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7033): 
,I/WebViewFactory( 7404): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7404): Loading: webviewchromium
I/LibraryLoader( 7404): Time to load native libraries: 4 ms (timestamps 7487-7491)
,I/LibraryLoader( 7404): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7404): Binding Chromium to main looper Looper (main, tid 1) {6024980}
I/LibraryLoader( 7404): Expected native library version number "",actual native library version number ""
I/chromium( 7404): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7404): Initializing chromium process, renderers=0
,W/art     ( 7404): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiStateMachine( 1030):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1030):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/chromium( 7404): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7404): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7404): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  320): registerClient() client 0xb54ecfa0, uid 10093
W/AudioManagerAndroid( 7404): Requires BLUETOOTH permission
,I/Adreno-EGL( 7404): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7404): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7404): Build Date: 12/12/14 금
I/Adreno-EGL( 7404): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7404): Remote Branch: 
I/Adreno-EGL( 7404): Local Patches: 
I/Adreno-EGL( 7404): Reconstruct Branch: 
,I/NSApplication( 7404): Starting up...
,I/ActivityManager( 1030): Killing 6908:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6908/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2341): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2341): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7281): onReceive
D/AppUp4:CustFacade( 7281): Context : android.app.ReceiverRestrictedContext@4ed0e11
D/AppUp4:CustFacade( 7281): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7281): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7281): begin check event
I/AppUp4:CustModeStarterReceiver( 7281): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3352): DownloadService onCreate
I/DownloadManager( 3352): in removeSpuriousFiles
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3b9d0847 on behalf of 3352
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
I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@284c5874 on behalf of 3352
V/DownloadManager( 3352): DownloadService onStartCommand
,D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@2697e1e3 on behalf of 3352
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3352): processing inserted download 1
V/DownloadManager( 3352): processing inserted download 4
,V/DownloadManager( 3352): processing inserted download 7
V/DownloadManager( 3352): processing inserted download 8
V/DownloadManager( 3352): processing inserted download 9
,D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
V/DownloadManager( 3352): processing inserted download 17
V/DownloadManager( 3352): processing inserted download 18
V/DownloadManager( 3352): processing inserted download 21
V/DownloadManager( 3352): DownloadService onDestroy
,I/LgeMiscReceiver( 3324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3324): networkInfo.isConnected() = false
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:2
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2341): [AccountUtils] Account not ready
W/Kids    ( 2341): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2341): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2341): 	at java.lang.Thread.run(Thread.java:818)
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c4f1577
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:2
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2341): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,V/FormManager( 7305): There are no updated forms. The schedule will be deleted.
D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
V/FormManager( 7305): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2341): [AccountUtils] Account not ready
W/Kids    ( 2341): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2341): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2341): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5216): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6782): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7281): [onReceive] request level :IDLE....
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:CustModeStarterReceiver( 7281): onReceive
D/AppUp4:CustFacade( 7281): Context : android.app.ReceiverRestrictedContext@4ed0e11
,D/AppUp4:CustFacade( 7281): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7281): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7281): begin check event
I/AppUp4:CustModeStarterReceiver( 7281): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3352): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3352): DownloadService onCreate
D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3352): in removeSpuriousFiles
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3352): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@3db04a99 on behalf of 3352
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3352): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3352): in trimDatabase
V/DownloadManager( 3352): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@14dcb93f on behalf of 3352
V/DownloadManager( 3352): DownloadService onStartCommand
V/DownloadManager( 3352): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3352): created cursor android.database.sqlite.SQLiteCursor@21b1f755 on behalf of 3352
,V/DownloadManager( 3352): processing inserted download 1
W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3352): processing inserted download 4
V/DownloadManager( 3352): processing inserted download 7
V/DownloadManager( 3352): processing inserted download 8
V/DownloadManager( 3352): processing inserted download 9
V/DownloadManager( 3352): processing inserted download 10
V/DownloadManager( 3352): processing inserted download 16
W/Settings( 6849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3352): processing inserted download 17
I/LgeMiscReceiver( 3324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3324): networkInfo.isConnected() = true
D/PhoneState( 3324): setPdpRejectCasuse : false
V/DownloadManager( 3352): processing inserted download 18
,V/DownloadManager( 3352): processing inserted download 21
D/WeatherAncestor( 7370): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:3
V/DownloadManager( 3352): DownloadService onDestroy
D/Weather.Utils( 7370): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7370): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7370): 2 : This is isUpdating : false
D/WeatherAncestor( 7370): connectivity changed - connection : true
D/WeatherService( 7370): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c4f1577
,D/ForecastDataCache( 7370): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7370): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7370): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7370): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7370): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:47:3
I/GoogleURLConnFactory( 2121): Using platform SSLCertificateSocketFactory
,V/FormManager( 7305): There are no updated forms. The schedule will be deleted.
V/FormManager( 7305): Alarm would be updated, because LastCheckTime has been updated.
,W/Uploader( 2121): No account for auth token provided
,D/ChimeraCfgMgr( 2341): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/GCM     ( 2121): Connected
I/GCM     ( 2341): Message from null null
E/GCM     ( 2341): Dropping message from null
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 2121): Message class com.google.f.a.a.p
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/Kids    ( 2341): [AccountUtils] Account not ready
W/Kids    ( 2341): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2341): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2341): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2341): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2341): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2341): 	at java.lang.Thread.run(Thread.java:818)
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/Uploader( 2121): No account for auth token provided
,W/Uploader( 2121): No account for auth token provided
,W/Uploader( 2121):  no longer exists, so no auth token.
,W/Uploader( 2121): No account for auth token provided
D/UEI.SmartControl( 6866): Internal timer expired: 4
D/UEI.SmartControl( 6866): unbind internal service
,W/Uploader( 2121): No account for auth token provided
D/serial_port( 6866): close(fd = 24)
,I/UEI.SmartControl( 6866): Serial port is closed.
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,E/Uploader( 2121): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 2121): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 2121): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 2121): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 2121): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{d90f493 type 2 when 169734 android} when 169734
,V/QRemote ( 7182): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7182): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8968
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7526 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7526): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 33335(1588KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 2.034ms total 103.048ms
,W/GAV2    ( 7526): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7526): Created application version: 3.2.35 (30235)
,I/BooksSync( 7526): Starting books sync
,D/BooksSync( 7526): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8566235583715145261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
,D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GAV4    ( 7404): Thread[GAThread,5,main]: No campaign data found.
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8566235583715145261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8566235583715145261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
E/BooksSync( 7526): Soft error: 
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8566235583715145261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
,E/BooksSync( 7526): Sync error
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8566235583715145261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
I/BooksSync( 7526): Finished books sync
I/ActivityManager( 1030): Killing 6925:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6925/cgroup.procs: No such file or directory
,I/GAV2    ( 7526): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 177546817071; DSPS: 5959015; Offset : -4322738189
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{daaa3bf type 0 when 1450280840391 com.android.vending} when 1450280840391
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/art     ( 2121): Explicit concurrent mark sweep GC freed 46533(2MB) AllocSpace objects, 22(2MB) LOS objects, 50% free, 30MB/62MB, paused 2.449ms total 63.238ms
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6365): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6365): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6365): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 197548701959; DSPS: 6614437; Offset : -4322745496
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3ef2f289 type 2 when 199879 android} when 199879
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 217551386483; DSPS: 7269884; Offset : -4322716052
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1819faaf type 0 when 1450280866027 com.android.vending} when 1450280866027
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6365): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6365): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6365): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 237553301266; DSPS: 7925307; Offset : -4322723878
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3d008ff9 type 2 when 237509 android} when 237509
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257555549488; DSPS: 8580741; Offset : -4322733981
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 277557716147; DSPS: 9236172; Offset : -4322733940
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 297559608536; DSPS: 9891594; Offset : -4322733536
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{38b15b3e type 2 when 300103 android} when 300103
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/BooksSync( 7526): Starting books sync
,D/BooksSync( 7526): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7526): null auth token
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
W/ApiaryClient( 7526): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2043140364873874778&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
,D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2043140364873874778&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
,D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2043140364873874778&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
E/BooksSync( 7526): Soft error: 
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2043140364873874778&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
,E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
,E/BooksSync( 7526): Sync error
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2043140364873874778&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
I/BooksSync( 7526): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 300103, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 7033): Connected to the server!
I/jxcore-log( 7033): 
,I/chromium( 7033): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 317561754882; DSPS: 10547024; Offset : -4322723605
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{28f23838 type 2 when 330291 android} when 330291
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 337563610343; DSPS: 11202445; Offset : -4322729690
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 26699(1125KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.661ms total 67.584ms
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 357565335857; DSPS: 11857862; Offset : -4322743808
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6365): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6365): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6365): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6365): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6365): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6365): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6365): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6365): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 377567627619; DSPS: 12513297; Offset : -4322740889
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 397569525007; DSPS: 13168719; Offset : -4322735409
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 417572337292; DSPS: 13824171; Offset : -4322730898
,I/[SystemUI]LGPowerUI( 1446): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1446): On Skip Timer : true
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1030): battery changed pluggedType: 2
D/HeadsetStateMachine( 3819): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1446): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1446): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1446): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 437574592649; DSPS: 14479605; Offset : -4322733842
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 457576814256; DSPS: 15135038; Offset : -4322740018
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 477578501696; DSPS: 15790453; Offset : -4322730940
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 497580943668; DSPS: 16445893; Offset : -4322730453
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 517583087098; DSPS: 17101323; Offset : -4322723202
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 537585300996; DSPS: 17756756; Offset : -4322737217
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{16f3c05a type 2 when 555278 android} when 555278
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/BooksSync( 7526): Starting books sync
,D/BooksSync( 7526): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9196285309206267293&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9196285309206267293&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 557587194894; DSPS: 18412178; Offset : -4322735409
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
,E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9196285309206267293&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
E/BooksSync( 7526): Soft error: 
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9196285309206267293&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
,E/BooksSync( 7526): Sync error
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9196285309206267293&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
I/BooksSync( 7526): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 555278, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 577589491449; DSPS: 19067613; Offset : -4322727594
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{185de274 type 2 when 585472 android} when 585472
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 597591510765; DSPS: 19723039; Offset : -4322722333
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 617593334247; DSPS: 20378459; Offset : -4322730089
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 637595599708; DSPS: 21033893; Offset : -4322722851
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/ActivityManager( 1030): Killing 6951:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6951/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 657597403294; DSPS: 21689312; Offset : -4322719854
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 677599559693; DSPS: 22344743; Offset : -4322729942
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 697601744738; DSPS: 23000175; Offset : -4322742345
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 717603642281; DSPS: 23655597; Offset : -4322736736
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 737605615503; DSPS: 24311021; Offset : -4322716692
,I/[SystemUI]LGPowerUI( 1446): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1446): On Skip Timer : true
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1446): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1446): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1446): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3819): Disconnected process message: 10, size: 0
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 757607812318; DSPS: 24966454; Offset : -4322747763
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated(),
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 777610606112; DSPS: 25621905; Offset : -4322730808
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 797612519335; DSPS: 26277328; Offset : -4322740350
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 817614369691; DSPS: 26932748; Offset : -4322721125
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 837616354580; DSPS: 27588173; Offset : -4322719698
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 857618234676; DSPS: 28243595; Offset : -4322731717
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 877620405189; DSPS: 28899026; Offset : -4322727848
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 897625579088; DSPS: 29554556; Offset : -4322742172
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 917627711736; DSPS: 30209986; Offset : -4322745963
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 937629899333; DSPS: 30865417; Offset : -4322724957
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{14b0f39d type 2 when 943051 com.android.bluetooth} when 943051
,W/bt-smp  ( 3819): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3819): Plain text(LSB ~ MSB) = 10 c2 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3819): Encrypted text(LSB ~ MSB) = 95 af 6f 38 79 89 6e 6b 46 f1 8f cb 52 6d c1 cc 
W/bt-btm  ( 3819): Stopping oneshot timer
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7761 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7761): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7761): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2f36feaa
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/ActivityManager( 1030): Killing 7158:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7158/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 957632611878; DSPS: 31520866; Offset : -4322728580
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 977634803380; DSPS: 32176298; Offset : -4322734241
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 997636722071; DSPS: 32831721; Offset : -4322738104
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1017638834511; DSPS: 33487150; Offset : -4322731455
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1037640837733; DSPS: 34142576; Offset : -4322742471
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1057643026111; DSPS: 34798007; Offset : -4322720868
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1ffc012 type 2 when 1061711 android} when 1061711
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/BooksSync( 7526): Starting books sync
D/BooksSync( 7526): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-577124807345731066&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
W/ApiaryClient( 7526): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-577124807345731066&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7526): Authentication error
E/BooksAccountManager( 7526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7526): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7526): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{3db04a99 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7526): Error response from books API: {
W/ApiaryClient( 7526):  "error": {
W/ApiaryClient( 7526):   "errors": [
W/ApiaryClient( 7526):    {
W/ApiaryClient( 7526):     "domain": "global",
W/ApiaryClient( 7526):     "reason": "required",
W/ApiaryClient( 7526):     "message": "Login Required",
W/ApiaryClient( 7526):     "locationType": "header",
W/ApiaryClient( 7526):     "location": "Authorization"
W/ApiaryClient( 7526):    }
W/ApiaryClient( 7526):   ],
W/ApiaryClient( 7526):   "code": 401,
W/ApiaryClient( 7526):   "message": "Login Required"
W/ApiaryClient( 7526):  }
W/ApiaryClient( 7526): }
,W/ApiaryClient( 7526): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-577124807345731066&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7526): Headers:
W/ApiaryClient( 7526): accept-encoding: [gzip]
W/ApiaryClient( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7526): gdata-version: 2
E/BooksSync( 7526): Soft error: 
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-577124807345731066&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
,E/BooksSync( 7526): Sync error
E/BooksSync( 7526): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7526): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-577124807345731066&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7526): Headers:
E/BooksSync( 7526): accept-encoding: [gzip]
E/BooksSync( 7526): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7526): gdata-version: 2
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7526): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7526): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7526): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7526): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7526): {
E/BooksSync( 7526):  "error": {
E/BooksSync( 7526):   "errors": [
E/BooksSync( 7526):    {
E/BooksSync( 7526):     "domain": "global",
E/BooksSync( 7526):     "reason": "required",
E/BooksSync( 7526):     "message": "Login Required",
E/BooksSync( 7526):     "locationType": "header",
E/BooksSync( 7526):     "location": "Authorization"
E/BooksSync( 7526):    }
E/BooksSync( 7526):   ],
E/BooksSync( 7526):   "code": 401,
E/BooksSync( 7526):   "message": "Login Required"
E/BooksSync( 7526):  }
E/BooksSync( 7526): }
E/BooksSync( 7526): 
E/BooksSync( 7526): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7526): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7526): 	... 8 more
I/BooksSync( 7526): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1061711, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1077645277561; DSPS: 35453441; Offset : -4322727588
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1269806c type 2 when 1092459 android} when 1092459
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1097647524636; DSPS: 36108875; Offset : -4322738711
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1117649313275; DSPS: 36764293; Offset : -4322720324
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
,I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1137652235194; DSPS: 37419749; Offset : -4322728068
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1157654534092; DSPS: 38075184; Offset : -4322717987
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1177656516794; DSPS: 38730609; Offset : -4322718720
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1197658703556; DSPS: 39386041; Offset : -4322729223
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1217660868394; DSPS: 40041472; Offset : -4322731316
,I/UsageStatsService( 1030): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1237662737761; DSPS: 40696893; Offset : -4322723600
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1257664897961; DSPS: 41352324; Offset : -4322730121
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1277666741235; DSPS: 42007745; Offset : -4322748133
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1297668583518; DSPS: 42663165; Offset : -4322737140
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1317670279657; DSPS: 43318580; Offset : -4322719519
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1337672371889; DSPS: 43974009; Offset : -4322732973
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1357674286308; DSPS: 44629432; Offset : -4322741006
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1377676349582; DSPS: 45284859; Offset : -4322722644
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1397678522803; DSPS: 45940290; Offset : -4322715963
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3b94c635 type 2 when 1068312 com.google.android.gms} when 1068312
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{34babaca type 0 when 1450281883221 com.google.android.gms} when 1450281883221
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/GCM     ( 2121): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/EventLogService( 2341): Aggregate from 1450280083153 (log), 1450280083153 (data)
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 34036(1539KB) AllocSpace objects, 13(1104KB) LOS objects, 33% free, 44MB/66MB, paused 1.272ms total 110.589ms
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1417681941754; DSPS: 46595762; Offset : -4322714980
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1437683827476; DSPS: 47251184; Offset : -4322721374
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1457685464708; DSPS: 47906598; Offset : -4322732118
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1477687899179; DSPS: 48562038; Offset : -4322738949
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1497689748286; DSPS: 49217458; Offset : -4322721026
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1517691976352; DSPS: 49872891; Offset : -4322720666
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1537694058792; DSPS: 50528320; Offset : -4322743991
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1557696180815; DSPS: 51183749; Offset : -4322727471
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1577698278932; DSPS: 51839178; Offset : -4322735199
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1597701100072; DSPS: 52494630; Offset : -4322721598
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1617703187563; DSPS: 53150059; Offset : -4322739897
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1637705361774; DSPS: 53805490; Offset : -4322732382
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1657709839579; DSPS: 54460997; Offset : -4322740896
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
,I/[SystemUI]Clock( 1446): called onTimeUpdated()
I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1677712125978; DSPS: 55116432; Offset : -4322743107
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1697714041750; DSPS: 55771854; Offset : -4322719504
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1717716240234; DSPS: 56427286; Offset : -4322718129
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1737718275955; DSPS: 57082713; Offset : -4322727319
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1757720234802; DSPS: 57738137; Offset : -4322721442
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1777723125315; DSPS: 58393592; Offset : -4322730176
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1797725290203; DSPS: 59049023; Offset : -4322731984
,I/[SystemUI]LGPowerUI( 1446): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1446): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1446): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1446): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1446): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3819): Disconnected process message: 10, size: 0
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1817727525456; DSPS: 59704456; Offset : -4322724697
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1837729119146; DSPS: 60359868; Offset : -4322717868
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,W/bt-smp  ( 3819): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3819): Plain text(LSB ~ MSB) = 55 d9 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3819): Encrypted text(LSB ~ MSB) = 54 26 53 b1 51 fe d6 0d 21 74 54 e5 c9 99 6e ee 
,W/bt-btm  ( 3819): Stopping oneshot timer
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{ab486ed type 2 when 1843080 com.android.bluetooth} when 1843080
I/ProcessStatsService( 1030): Prepared write state in 19ms
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,I/ProcessStatsService( 1030): Prepared write state in 16ms
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
,I/ProcessStatsService( 1030): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-49.bin
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=809451237, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/DigitalAppWidgetProvider( 7761): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7761): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2f36feaa
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=809451237 [*alarm*], flags=0x0
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1857731659972; DSPS: 61015312; Offset : -4322740338
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1877733545589; DSPS: 61670733; Offset : -4322716397
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1897735163706; DSPS: 62326147; Offset : -4322746151
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1917737074793; DSPS: 62981569; Offset : -4322727075
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1937738623743; DSPS: 63636980; Offset : -4322734470
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1957740094100; DSPS: 64292388; Offset : -4322729295
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,TIME-OUT KILL (timeout was 1800000ms)
```
