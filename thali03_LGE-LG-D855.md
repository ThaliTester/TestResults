#### Test 506502783fcf234_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/AndroidRuntime( 7077): 
D/AndroidRuntime( 7077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7077): CheckJNI is OFF
D/AndroidRuntime( 7077): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1969): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{211899d0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{211899d0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7097 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7077): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1872): Display #0 changed.
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{29afa90e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{14216f2f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7097): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7097): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7097): Loading: webviewchromium
I/LibraryLoader( 7097): Time to load native libraries: 6 ms (timestamps 1648-1654)
,I/LibraryLoader( 7097): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7097): Binding Chromium to main looper Looper (main, tid 1) {3e8f7c3e}
,I/LibraryLoader( 7097): Expected native library version number "",actual native library version number ""
I/chromium( 7097): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7097): Initializing chromium process, renderers=0
W/art     ( 7097): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7097): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7097): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7097): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb54f5d60, uid 10311
,D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e1267da:true
I/Adreno-EGL( 7097): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7097): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7097): Build Date: 12/12/14 금
I/Adreno-EGL( 7097): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7097): Remote Branch: 
I/Adreno-EGL( 7097): Local Patches: 
I/Adreno-EGL( 7097): Reconstruct Branch: 
,W/chromium( 7097): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7097): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7097): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7097): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7097): CordovaWebView is running on device made by: LGE
,W/art     ( 7097): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7097): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{1d370dc9 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7097): Render dirty regions requested: true
I/OpenGLRenderer( 7097): Initialized EGL, version 1.4
D/OpenGLRenderer( 7097): Enabling debug mode 0
,D/Atlas   ( 7097): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{304f2bc4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@36933244,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/Timeline( 7097): Timeline: Activity_idle id: android.os.BinderProxy@32b170ee time:292113
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +670ms (total +750ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{1d370dc9 u0 com.test.thalitest/.MainActivity t4} time:292114
D/LgDataFeature( 7097): LgDataFeature() Constructor: none
D/LgDataFeature( 7097): LgDataFeature() Constructor Done, null
I/chromium( 7097): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7097): 
,D/JsMessageQueue( 7097): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7097): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435090688
,D/JX-Cordova( 7097): jxcore cordova android initializing
E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7097): Initializing JXcore engine
W/jxcore-log( 7097): JXcore engine is ready
,W/jxcore-log( 7097): Starting JXcore engine
,I/art     ( 7097): Background sticky concurrent mark sweep GC freed 120132(11MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 39MB/55MB, paused 953us total 100.243ms
,W/.test.thalitest( 7097): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8424]" dev="sockfs" ino=8424 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7097): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7097): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10442]" dev="sockfs" ino=10442 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7097): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7097): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34332]" dev="sockfs" ino=34332 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7097): Platform android
W/jxcore-log( 7097): 
W/jxcore-log( 7097): Process ARCH arm
W/jxcore-log( 7097): 
,I/jxcore-log( 7097): JXcore Cordova bridge is ready!
I/jxcore-log( 7097): 
W/jxcore-log( 7097): JXcore engine is started
,I/jxcore-log( 7097): Toggling radios to true
I/jxcore-log( 7097): 
,D/BluetoothAdapter( 7097): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7097, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7097, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1038): disconnect pid=7097, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [295,766,416 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7097, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7097): Radios toggled
I/jxcore-log( 7097): 
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7097): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7097): 
,I/jxcore-log( 7097): Perf Test app loaded loaded,
I/jxcore-log( 7097): 
,I/jxcore-log( 7097): check test folder
I/jxcore-log( 7097): 
I/jxcore-log( 7097): found test : ./testFindPeers.js
I/jxcore-log( 7097): 
I/jxcore-log( 7097): found test : ./testSendData.js
I/jxcore-log( 7097): 
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1038): InitialState.processMessage what=4
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  315): Clearing all IP addresses on wlan0
V/NativeCrypto( 2144): Read error: ssl=0xaf4d4600: I/O error during system call, Connection timed out
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 0
D/WifiHS20( 1038): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [295,929,932 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=295935
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=295945
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService( 1038): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
I/art     ( 2144): Explicit concurrent mark sweep GC freed 38131(2MB) AllocSpace objects, 8(1024KB) LOS objects, 51% free, 30MB/62MB, paused 1.209ms total 71.725ms
V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaf4d4600: I/O error during system call, Broken pipe
,D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=295977  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=295978  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=295993  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/chromium( 7097): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 7190): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296004  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 7190): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
I/chromium( 7097): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7097): 
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7097): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/DhcpStateMachine( 1038): StoppedState
,D/DhcpStateMachine( 1038): StoppedState{ when=-131ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7190): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7190): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7190): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7190): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7190): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7190): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6067:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6067/cgroup.procs: No such file or directory
,I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7190): LgDataFeature() Constructor: none
D/LgDataFeature( 7190): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7251 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6087:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6087/cgroup.procs: No such file or directory
W/ResourcesManager( 7251): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 7251): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 7251): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7251): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7251): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7251): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7251): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7251): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7251): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7251): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7251): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7251): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7251): LgDataFeature() Constructor: none
D/LgDataFeature( 7251): LgDataFeature() Constructor Done, null
V/SoundPool( 7251): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7251): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7251): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7251): doLoad: loading sample sampleID=1
V/SoundPool( 7251): Start decode
V/MediaPlayer[Native]( 7251): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
I/QRemote ( 7251): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6753): QS Service created
D/QRemote ( 7251): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  319): setAudioSource() 
V/MediaPlayerService(  319): prepare
V/AwesomePlayer(  319): prepareAsync_l() 
V/MediaPlayerService(  319): wait for prepare
V/AwesomePlayer(  319): onPrepareAsyncEvent() 
V/AwesomePlayer(  319): initAudioDecoder() 
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AwesomePlayer(  319): getUseOffload() = 0 
V/OMXCodec(  319): OMXCodec::Create
V/OMXCodec(  319): findMatchingCodecs()
V/OMXCodec(  319): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  319): matchingCodecs.size()=1
V/OMXCodec(  319): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  319): LG Codec Adapter start
V/OMXCodec(  319): OMXCodec Createtor
V/OMXCodec(  319): setComponentRole
V/OMXCodec(  319): configureCodec protected=0
V/LGCodecAdapter(  319): called getLGCodecSpecificData
V/LGCodecOSAL(  319): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMSG
V/LGCodecOSAL(  319): Not support LGCodec
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  319): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  319): Could not offload audio decode, try pcm offload
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcce0 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/LGMDMManager( 7251): Create singleton instance
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb5474740, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb5474740, 1, 0, 0)
V/AudioCache(  319): prepared
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): start
V/AwesomePlayer(  319): play_l() 
V/AwesomePlayer(  319): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  319): createAudioPlayer_l
V/AwesomePlayer(  319): seekAudioIfNecessary_l() 
V/AwesomePlayer(  319): startAudioPlayer_l() 
D/AudioPlayer(  319): start of Playback, useOffload 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796224
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797024
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb5474740, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab602000, 0xb57d2000, 4096)
I/UEI.SmartControl( 6753): Service initServices...
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab603000, 0xb57d2000, 4096)
D/UEI.SmartControl( 6753): QS start get config
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab604000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab605000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab606000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab607000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab608000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab609000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60a000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60b000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60c000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60d000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60e000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab60f000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab610000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab611000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab612000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab613000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab614000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab615000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab616000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab617000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab618000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab619000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61a000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61b000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61c000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61d000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61e000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab61f000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab620000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab621000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab622000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab623000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab624000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab625000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab626000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab627000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab628000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab629000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62a000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62b000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62c000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62d000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62e000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab62f000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab630000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab631000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab632000, 0xb57d2000, 4096)
V/AudioCache(  319): write(0xb57d2000, 4096)
V/AudioCache(  319): memcpy(0xab633000, 0xb57d2000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb57d2000, 280)
V/AudioCache(  319): memcpy(0xab634000, 0xb57d2000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb5474740, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb5474740, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  319): Pause Playback at 1068125
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 7251): close(31)
V/SoundPool( 7251): pointer = 0x9fe42000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1727
I/UEI.SmartControl( 6753): Supports setup maps: true
D/UEI.SmartControl( 6753): QS start statue = true Error code = 0
I/UEI.SmartControl( 6753): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6753): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6753): ### init IR Blaster...
D/serial_port( 6753): Configuring serial port
E/UEI.SmartControl( 6753): UEIBLaster setting for 616
I/UEI.SmartControl( 6753): Setting serial record hearder size = 2
I/UEI.SmartControl( 6753): configuring settings for MAXQ616
I/UEI.SmartControl( 6753): Get version...
D/UEI.SmartControl( 6753): serial port data available: 21
D/UEI.SmartControl( 6753): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6753): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6753): QS saving settings...
D/UEI.SmartControl( 6753): IR Blaster version: 25672567
D/UEI.SmartControl( 6753): serial port data available: 4
I/UEI.SmartControl( 6753): Device manager: loading config....
D/UEI.SmartControl( 6753): ----------- loading internal config...
W/ContextImpl( 6753): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6753): Services init done
D/UEI.SmartControl( 6753): QS Service init finished
D/UEI.SmartControl( 6753): QS Service version name: 2.1.91
D/UEI.SmartControl( 6753): QS Service version code: 201091
D/UEI.SmartControl( 6753): Service requested: Control
E/UEI.SmartControl( 6753): Loading SETTINGS...
D/UEI.SmartControl( 6753): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6753): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6753): Internal service binding...
I/QRemote ( 7251): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6753): ------ IControl API: 11
D/UEI.SmartControl( 6753): File observer start...
E/UEI.SmartControl( 6753): IR Port is disabled: false
D/UEI.SmartControl( 6753): Starting file observer...
I/UEI.SmartControl( 6753): Registering callback...
,I/UEI.SmartControl( 6753): ------ IControl API: 19
I/UEI.SmartControl( 6753): Registering Services Ready callback...
I/UEI.SmartControl( 6753): Notify client services are ready...
I/QRemote ( 7251): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7251): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7251): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7251): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7251): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6753): ------ IControl API: 8
D/QRemote ( 7251): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7251): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
I/UEI.SmartControl( 6753): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6753): -----service ready thread exits
I/QRemote ( 7251): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7251): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7251): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7251): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7251): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7251): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7251): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7251): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,D/QRemote ( 7251): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7251): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450238474212]
D/QRemote ( 7251): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6611:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 7251): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6611/cgroup.procs: No such file or directory
,V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 297933598326; DSPS: 9903886; Offset : -4324082302
,I/wpa_supplicant( 2661): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=298084  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=298117  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2661): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298197  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298226  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298227
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298229
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298229
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298230
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298230
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298230  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298233  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298234  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298234  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298250
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298250
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
,D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7190): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7190): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7190): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7190): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : availableList=[wlan0]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7190): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7190): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7190): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  315): Setting iface cfg
,E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298287  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@230ea4a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@230ea4a target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 1
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECT,IVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/dsqn    ( 7331): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7331): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 7331): DSQN ssw
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
,D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7251): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7251): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7251): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/PCSuite ( 7227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/dhcpcd  ( 7335): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7335): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/WiFiOffLoadBroadcast( 7190): MCCMNC not supported: null
I/dhcpcd  ( 7335): version 5.5.6 starting
,E/dhcpcd  ( 7335): get_duid: m
D/dhcpcd  ( 7335): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7251): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7251): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7251): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/dhcpcd  ( 7335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7335): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7335): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7335): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7335): wlan0: sending REQUEST (xid 0xfbc89f94), next in 3.35 seconds
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  315): argv[0]=dsqncommand
,D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 04:01:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450238475506], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450238475487]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{257fe38d type 2 when 298992 com.google.android.gms} when 298992
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7373 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  345): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 25.232ms
,I/art     (  345): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 18.539ms
I/art     (  345): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 295us total 16.085ms
,I/AppUp4:AppBoxCP( 7373): onCreate
W/AppUp4:DB( 7373):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7373):  setFingerPrint start
,I/AppUp4:DB( 7373):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7373):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7373):  SDK version = 21
,I/AppUp4:DB( 7373):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7373): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7373): onReceive
,D/LgDataFeature( 7373): LgDataFeature() Constructor: none
D/LgDataFeature( 7373): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7373): Context : android.app.ReceiverRestrictedContext@28af57ec
D/AppUp4:CustFacade( 7373): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7373): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7373): begin check event
I/AppUp4:CustModeStarterReceiver( 7373): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7373): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7373): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7373): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7373): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1038): Killing 6485:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6485/cgroup.procs: No such file or directory
,D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3372): DownloadService onCreate
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7403 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@2fa29549 on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
,I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3372): DownloadService onStartCommand
,V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@1f3e507c on behalf of 3372
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/ResourcesManager( 7403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@5f63d05 on behalf of 3372
W/ResourcesManager( 7403): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7403): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7403): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
,V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
V/DownloadManager( 3372): DownloadService onDestroy
I/LGEmail ( 7403): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7403): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7403): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7403): LgDataFeature() Constructor: none
D/LgDataFeature( 7403): LgDataFeature() Constructor Done, null
,D/eas_req ( 7403): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7447 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/HubEmail( 7403): JNI_OnLoad()
I/HubEmail( 7403): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7403): registerNatives()
I/HubEmail( 7403): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/dhcpcd  ( 7335): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/HubEmail( 7403): registerNativeMethods()
I/HubEmail( 7403): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7403): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524295
I/ActivityManager( 1038): Killing 6643:com.android.gallery3d/u0a27 (adj 15): empty #17
I/dhcpcd  ( 7335): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7335): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7335): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7335): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7335): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7335): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6643/cgroup.procs: No such file or directory
,W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7484 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
V/FormManager( 7447): There are no updated forms. The schedule will be deleted.
V/FormManager( 7447): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7512 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6669:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6669/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 6700:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/jxcore-log( 7097): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7097): 
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7529 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6791:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6700/cgroup.procs: No such file or directory
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6791/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/art     ( 7529): Almond Protected OAT
,D/WeatherApplication( 7529): removeAccount
,D/WeatherApplication( 7529): Account.length = 0
E/WeatherApplication( 7529): OPERATOR:OPEN
D/WeatherAncestor( 7529): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:17
D/Weather.Utils( 7529): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7529): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7529): 2 : This is isUpdating : false
,D/WeatherAncestor( 7529): connectivity changed - connection : true
D/WeatherService( 7529): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7529): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7529): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7529): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7529): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7529): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:17
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7547 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6721:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6721/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,W/ContextImpl( 7547): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7547): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7547): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=true
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7547): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7547): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7547): Loading: webviewchromium
I/LibraryLoader( 7547): Time to load native libraries: 7 ms (timestamps 1676-1683)
,I/LibraryLoader( 7547): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7547): Binding Chromium to main looper Looper (main, tid 1) {22675b87}
I/LibraryLoader( 7547): Expected native library version number "",actual native library version number ""
I/chromium( 7547): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7547): Initializing chromium process, renderers=0
,W/art     ( 7547): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7547): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7547): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7547): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb14fd100, uid 10093
W/AudioManagerAndroid( 7547): Requires BLUETOOTH permission
I/Adreno-EGL( 7547): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7547): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7547): Build Date: 12/12/14 금
I/Adreno-EGL( 7547): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7547): Remote Branch: 
I/Adreno-EGL( 7547): Local Patches: 
I/Adreno-EGL( 7547): Reconstruct Branch: 
,I/NSApplication( 7547): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7602 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6813:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6813/cgroup.procs: No such file or directory
,W/ResourcesManager( 7602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 7097): Connected to the server!
I/jxcore-log( 7097): 
,I/chromium( 7097): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 84186(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.371ms total 160.165ms
,D/UEI.SmartControl( 6753): Internal timer expired: 3
D/UEI.SmartControl( 6753): unbind internal service
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSActivity( 2144): [ac] getting account id
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2144): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] request level :IDLE....
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
I/AppUp4:CustModeStarterReceiver( 7373): onReceive
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
D/serial_port( 6753): close(fd = 24)
,D/AppUp4:CustFacade( 7373): Context : android.app.ReceiverRestrictedContext@28af57ec
D/AppUp4:CustFacade( 7373): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7373): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7373): begin check event
I/AppUp4:CustModeStarterReceiver( 7373): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/UEI.SmartControl( 6753): Serial port is closed.
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3372): DownloadService onCreate
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@dba1f8b on behalf of 3372
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3372): in trimDatabase
I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = false
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@3e5df868 on behalf of 3372
W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7529): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:19
D/Weather.Utils( 7529): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7529): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7529): 2 : This is isUpdating : false
D/WeatherAncestor( 7529): connectivity changed - connection : true
D/WeatherService( 7529): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a031e4a
D/ForecastDataCache( 7529): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7529): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7529): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7529): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7529): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:19
V/DownloadManager( 3372): DownloadService onStartCommand
,V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@ca92967 on behalf of 3372
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3372): processing inserted download 9
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3372): processing inserted download 10
,V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3372): processing inserted download 18
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
V/DownloadManager( 3372): processing inserted download 21
V/FormManager( 7447): There are no updated forms. The schedule will be deleted.
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
V/DownloadManager( 3372): DownloadService onDestroy
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,V/FormManager( 7447): Alarm would be updated, because LastCheckTime has been updated.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6558): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7373): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7373): onReceive
,D/AppUp4:CustFacade( 7373): Context : android.app.ReceiverRestrictedContext@28af57ec
D/AppUp4:CustFacade( 7373): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7373): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7373): begin check event
I/AppUp4:CustModeStarterReceiver( 7373): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3372): DownloadService onCreate
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@95407bd on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@1394f503 on behalf of 3372
V/DownloadManager( 3372): DownloadService onStartCommand
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@93e62b9 on behalf of 3372
V/DownloadManager( 3372): processing inserted download 1
W/Settings( 7403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3372): processing inserted download 4
,V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
,V/DownloadManager( 3372): processing inserted download 16
I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3372): processing inserted download 17
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = true
D/PhoneState( 3343): setPdpRejectCasuse : false
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7529): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:19
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Weather.Utils( 7529): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7529): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7529): 2 : This is isUpdating : false
D/WeatherAncestor( 7529): connectivity changed - connection : true
,D/WeatherService( 7529): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a031e4a
V/DownloadManager( 3372): DownloadService onDestroy
D/ForecastDataCache( 7529): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7529): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7529): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7529): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7529): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 5:1:19
D/LgeQuickCoverNLService( 1419): onNotificationPosted
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/GCM     ( 2144): Connected
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/GCM     ( 2144): Message class com.google.f.a.a.p
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7447): There are no updated forms. The schedule will be deleted.
V/FormManager( 7447): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GAV4    ( 7547): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{e8b7512 type 2 when 307373 android} when 307373
,V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1727
,I/BooksSync( 6927): Starting books sync
,D/BooksSync( 6927): started syncMyEbooks
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2526810517072679822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2526810517072679822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2526810517072679822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
E/BooksSync( 6927): Soft error: 
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2526810517072679822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
,E/BooksSync( 6927): Sync error
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2526810517072679822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
I/BooksSync( 6927): Finished books sync
I/ActivityManager( 1038): Killing 6839:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307373, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6839/cgroup.procs: No such file or directory
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 317935217902; DSPS: 10559299; Offset : -4324080262
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1ddd161f type 2 when 337443 android} when 337443
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 337937466644; DSPS: 11214733; Offset : -4324089820
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 25565(1182KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 3.158ms total 180.645ms
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 357939296168; DSPS: 11870153; Offset : -4324091352
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3789): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6197): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6197): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6197): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6197): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6197): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6197): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6197): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6197): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 377942192567; DSPS: 12525608; Offset : -4324094200
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 397944003913; DSPS: 13181027; Offset : -4324083444
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 417946031354; DSPS: 13836454; Offset : -4324100523
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 437948031867; DSPS: 14491879; Offset : -4324083601
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 457949849463; DSPS: 15147299; Offset : -4324097242
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 477952623362; DSPS: 15802750; Offset : -4324100312
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 497954126584; DSPS: 16458159; Offset : -4324092582
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 517956234597; DSPS: 17113588; Offset : -4324090360
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 537958042974; DSPS: 17769008; Offset : -4324112855
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 557960270728; DSPS: 18424440; Offset : -4324082471
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{6d35de9 type 2 when 573340 android} when 573340
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/BooksSync( 6927): Starting books sync
,D/BooksSync( 6927): started syncMyEbooks
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7766796842404424538&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7766796842404424538&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7766796842404424538&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
,E/BooksSync( 6927): Soft error: 
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7766796842404424538&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
,E/BooksSync( 6927): Sync error
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7766796842404424538&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
I/BooksSync( 6927): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 573340, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 577962751397; DSPS: 19079882; Offset : -4324104139
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 597964817327; DSPS: 19735309; Offset : -4324083069
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1f52130b type 2 when 603531 android} when 603531
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 617966723308; DSPS: 20390732; Offset : -4324099669
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 637968796374; DSPS: 21046160; Offset : -4324101800
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/ActivityManager( 1038): Killing 6197:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6197/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 657971118294; DSPS: 21701596; Offset : -4324099059
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 677973081410; DSPS: 22357020; Offset : -4324089172
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 697975124789; DSPS: 23012447; Offset : -4324090418
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 717976729520; DSPS: 23667860; Offset : -4324103172
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1038): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3789): Disconnected process message: 10, size: 0
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 737978525555; DSPS: 24323279; Offset : -4324107699
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 757980764089; DSPS: 24978712; Offset : -4324096844
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 777982987102; DSPS: 25634145; Offset : -4324101693
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 797984785324; DSPS: 26289564; Offset : -4324104008
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 817986810888; DSPS: 26944990; Offset : -4324092500
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 837988952182; DSPS: 27600420; Offset : -4324087696
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 857991034103; DSPS: 28255849; Offset : -4324111306
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 877992567480; DSPS: 28911259; Offset : -4324103912
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 897994704973; DSPS: 29566689; Offset : -4324102468
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 917996714757; DSPS: 30222115; Offset : -4324107026
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 937998840634; DSPS: 30877544; Offset : -4324086758
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,W/bt-smp  ( 3789): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3789): Plain text(LSB ~ MSB) = fd 93 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3789): Encrypted text(LSB ~ MSB) = b9 00 52 6b 81 57 54 ec 84 cf 35 d0 bc 8b 3f 20 
,W/bt-btm  ( 3789): Stopping oneshot timer
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1d41a5e8 type 2 when 943101 com.android.bluetooth} when 943101
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 958001159794; DSPS: 31532980; Offset : -4324087091
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 978003096661; DSPS: 32188404; Offset : -4324103166
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 998005088528; DSPS: 32843829; Offset : -4324094994
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1018007219823; DSPS: 33499259; Offset : -4324099982
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1038009102211; DSPS: 34154681; Offset : -4324109579
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1058022444131; DSPS: 34810478; Offset : -4324103919
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1078024544800; DSPS: 35465907; Offset : -4324109015
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1098026314011; DSPS: 36121325; Offset : -4324109771
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2ef08401 type 2 when 1101089 android} when 1101089
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/BooksSync( 6927): Starting books sync
D/BooksSync( 6927): started syncMyEbooks
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
W/ApiaryClient( 6927): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=226916831123757283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=226916831123757283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6927): Authentication error
E/BooksAccountManager( 6927): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6927): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6927): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6927): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6927): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b4e3314 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6927): Error response from books API: {
W/ApiaryClient( 6927):  "error": {
W/ApiaryClient( 6927):   "errors": [
W/ApiaryClient( 6927):    {
W/ApiaryClient( 6927):     "domain": "global",
W/ApiaryClient( 6927):     "reason": "required",
W/ApiaryClient( 6927):     "message": "Login Required",
W/ApiaryClient( 6927):     "locationType": "header",
W/ApiaryClient( 6927):     "location": "Authorization"
W/ApiaryClient( 6927):    }
W/ApiaryClient( 6927):   ],
W/ApiaryClient( 6927):   "code": 401,
W/ApiaryClient( 6927):   "message": "Login Required"
W/ApiaryClient( 6927):  }
W/ApiaryClient( 6927): }
,W/ApiaryClient( 6927): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=226916831123757283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6927): Headers:
W/ApiaryClient( 6927): accept-encoding: [gzip]
W/ApiaryClient( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6927): gdata-version: 2
E/BooksSync( 6927): Soft error: 
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=226916831123757283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
,E/BooksSync( 6927): Sync error
E/BooksSync( 6927): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6927): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=226916831123757283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6927): Headers:
E/BooksSync( 6927): accept-encoding: [gzip]
E/BooksSync( 6927): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6927): gdata-version: 2
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6927): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6927): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6927): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6927): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6927): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6927): {
E/BooksSync( 6927):  "error": {
E/BooksSync( 6927):   "errors": [
E/BooksSync( 6927):    {
E/BooksSync( 6927):     "domain": "global",
E/BooksSync( 6927):     "reason": "required",
E/BooksSync( 6927):     "message": "Login Required",
E/BooksSync( 6927):     "locationType": "header",
E/BooksSync( 6927):     "location": "Authorization"
E/BooksSync( 6927):    }
E/BooksSync( 6927):   ],
E/BooksSync( 6927):   "code": 401,
E/BooksSync( 6927):   "message": "Login Required"
E/BooksSync( 6927):  }
E/BooksSync( 6927): }
E/BooksSync( 6927): 
E/BooksSync( 6927): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6927): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6927): 	... 8 more
I/BooksSync( 6927): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1101089, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1118028713899; DSPS: 36776763; Offset : -4324090150
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/DigitalAppWidgetProvider( 7024): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7024): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@eee94f9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1853d463 type 2 when 1131911 android} when 1131911
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1138030997017; DSPS: 37432198; Offset : -4324095929
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1158032886123; DSPS: 38087620; Offset : -4324098912
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1178034928356; DSPS: 38743047; Offset : -4324101358
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1198036751629; DSPS: 39398467; Offset : -4324108800
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1218038534223; DSPS: 40053885; Offset : -4324096564
,I/UsageStatsService( 1038): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1238041530260; DSPS: 40709343; Offset : -4324091250
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1258043485512; DSPS: 41364767; Offset : -4324089018
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1278045517120; DSPS: 42020194; Offset : -4324102036
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1298047430028; DSPS: 42675617; Offset : -4324111814
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1318049578093; DSPS: 43331047; Offset : -4324099745
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1338051225482; DSPS: 43986461; Offset : -4324100592
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1358053379068; DSPS: 44641891; Offset : -4324083210
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1378055221143; DSPS: 45297312; Offset : -4324102837
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1398057174834; DSPS: 45952736; Offset : -4324102141
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1418058913472; DSPS: 46608153; Offset : -4324102900
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1438061137580; DSPS: 47263586; Offset : -4324106759
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1458063230957; DSPS: 47919014; Offset : -4324088576
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1478065290064; DSPS: 48574442; Offset : -4324104483
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1498067669171; DSPS: 49229880; Offset : -4324105851
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3789): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1518069999371; DSPS: 49885316; Offset : -4324095118
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1538072020718; DSPS: 50540742; Offset : -4324087775
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1558073871857; DSPS: 51196163; Offset : -4324098259
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1578075666953; DSPS: 51851582; Offset : -4324103779
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1598077753508; DSPS: 52507010; Offset : -4324092237
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1618079418239; DSPS: 53162425; Offset : -4324106103
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1638082221201; DSPS: 53817877; Offset : -4324110836
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1658084361871; DSPS: 54473307; Offset : -4324106162
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1678086348738; DSPS: 55128732; Offset : -4324103094
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1698088485813; DSPS: 55784162; Offset : -4324102328
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1718090646119; DSPS: 56439593; Offset : -4324108456
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1738092784704; DSPS: 57095023; Offset : -4324106233
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1758094909748; DSPS: 57750452; Offset : -4324086981
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1778096705627; DSPS: 58405871; Offset : -4324091508
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1798098804264; DSPS: 59061300; Offset : -4324098792
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1818101557122; DSPS: 59716750; Offset : -4324092595
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1838103682531; DSPS: 60372180; Offset : -4324103076
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{28a7c119 type 2 when 1843129 com.android.bluetooth} when 1843129
,W/bt-smp  ( 3789): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3789): Plain text(LSB ~ MSB) = 66 ce 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3789): Encrypted text(LSB ~ MSB) = 3a 92 d9 d9 ad 3b 47 61 86 eb 5c ad 8e ea 29 25 
W/bt-btm  ( 3789): Stopping oneshot timer
I/ProcessStatsService( 1038): Prepared write state in 9ms
,I/ProcessStatsService( 1038): Prepared write state in 18ms
,I/ProcessStatsService( 1038): Prepared write state in 15ms
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/ProcessStatsService( 1038): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-04-26.bin
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1858105993564; DSPS: 61027615; Offset : -4324080992
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1e9905de type 2 when 1202921 com.google.android.gms} when 1202921
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
,D/GCM     ( 2144): Message class com.google.f.a.a.i
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ProcessCpuTracker( 1038): Skipping unknown process pid 7968
W/ProcessCpuTracker( 1038): Skipping unknown process pid 7969
,W/ProcessCpuTracker( 1038): Skipping unknown process pid 7984
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1878108072411; DSPS: 61683044; Offset : -4324107832
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1898110360737; DSPS: 62338479; Offset : -4324108299
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1918112515208; DSPS: 62993909; Offset : -4324090084
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1938114099576; DSPS: 63649321; Offset : -4324092760
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1958116310714; DSPS: 64304754; Offset : -4324109301
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1978118516488; DSPS: 64960186; Offset : -4324100819
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1998121188460; DSPS: 65615634; Offset : -4324114421
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2018122562462; DSPS: 66271038; Offset : -4324081707
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=870668746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7024): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7024): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@eee94f9
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=870668746 [*alarm*], flags=0x0
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2038124745944; DSPS: 66926470; Offset : -4324097053
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2058127817030; DSPS: 67581931; Offset : -4324108113
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2078129768584; DSPS: 68237355; Offset : -4324109709
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2098131979255; DSPS: 68892787; Offset : -4324096408
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2118133751486; DSPS: 69548205; Offset : -4324094119
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2138135920384; DSPS: 70203636; Offset : -4324091944
,TIME-OUT KILL (timeout was 1800000ms)
```
