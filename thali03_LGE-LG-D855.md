#### Test 564496607226f84_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 277984838081; DSPS: 9249990; Offset : -4315671636
,D/AndroidRuntime( 7182): 
D/AndroidRuntime( 7182): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7182): CheckJNI is OFF
D/AndroidRuntime( 7182): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1971): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{2d345bb #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{2d345bb #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7197 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7182): Shutting down VM
V/ActivityManager( 1040): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{27ace001 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{12a1dea6 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7197): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7197): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7197): Loading: webviewchromium
I/LibraryLoader( 7197): Time to load native libraries: 4 ms (timestamps 9648-9652)
I/LibraryLoader( 7197): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7197): Binding Chromium to main looper Looper (main, tid 1) {f1fff1}
,I/LibraryLoader( 7197): Expected native library version number "",actual native library version number ""
I/chromium( 7197): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7197): Initializing chromium process, renderers=0
,W/art     ( 7197): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7197): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7197): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7197): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  315): registerClient() client 0xb14272a0, uid 10311
D/BluetoothManagerService( 1040): Message: 20
,D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c047c6d:true
,I/Adreno-EGL( 7197): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7197): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7197): Build Date: 12/12/14 금
I/Adreno-EGL( 7197): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7197): Remote Branch: 
I/Adreno-EGL( 7197): Local Patches: 
I/Adreno-EGL( 7197): Reconstruct Branch: 
W/chromium( 7197): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7197): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7197): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7197): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7197): CordovaWebView is running on device made by: LGE
,W/art     ( 7197): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7197): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7197): Render dirty regions requested: true
I/OpenGLRenderer( 7197): Initialized EGL, version 1.4
D/OpenGLRenderer( 7197): Enabling debug mode 0
,D/Atlas   ( 7197): Validating map...
,D/SplitWindow( 1040): check instance of lgWin Window{3dbe987f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1040): Activity pause timeout for ActivityRecord{3cd5dad8 u0 com.test.thalitest/.MainActivity t4}
,I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1caaae0c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/LgDataFeature( 7197): LgDataFeature() Constructor: none
,D/LgDataFeature( 7197): LgDataFeature() Constructor Done, null
,I/Timeline( 7197): Timeline: Activity_idle id: android.os.BinderProxy@2eb1c761 time:280064
,I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +617ms (total +730ms)
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{3cd5dad8 u0 com.test.thalitest/.MainActivity t4} time:280088
D/JsMessageQueue( 7197): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7197): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435083520
,I/chromium( 7197): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7197): 
,I/chromium( 7197): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7197): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7197): 
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7197): Initializing JXcore engine
W/jxcore-log( 7197): JXcore engine is ready
W/Thread-829( 7272): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7578]" dev="sockfs" ino=7578 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-829( 7272): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-829( 7272): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8461]" dev="sockfs" ino=8461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-829( 7272): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-829( 7272): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34574]" dev="sockfs" ino=34574 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7197): Starting JXcore engine
I/art     ( 7197): Background sticky concurrent mark sweep GC freed 133251(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 763us total 100.522ms
W/jxcore-log( 7197): Platform android
W/jxcore-log( 7197): 
W/jxcore-log( 7197): Process ARCH arm
W/jxcore-log( 7197): 
,I/jxcore-log( 7197): JXcore Cordova bridge is ready!
I/jxcore-log( 7197): 
W/jxcore-log( 7197): JXcore engine is started
,I/jxcore-log( 7197): Toggling radios to true
I/jxcore-log( 7197): 
,D/BluetoothAdapter( 7197): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=7197, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1040): setWifiEnabled: true pid=7197, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=7197, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1040): reconnect pid=7197, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1040): [283,313,505 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
I/jxcore-log( 7197): Radios toggled
I/jxcore-log( 7197): 
I/jxcore-log( 7197): My device name is: LGE-LG-D855
I/jxcore-log( 7197): 
I/wpa_supplicant( 2631): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1040): InitialState.processMessage what=4
D/WifiNative-wlan0( 1040): DISCONNECT: returned true
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/DhcpStateMachine( 1040): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2136): Read error: ssl=0xaf458e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2136): SSL shutdown failed: ssl=0xaf458e00: I/O error during system call, Broken pipe
I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7292 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1040): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1971): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiNative: ( 1040): [283,476,056 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
D/WifiNative-wlan0( 1040): RECONNECT: returned true
I/wpa_supplicant( 2631): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=283480
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=283481
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1040): SET ps 1: returned true
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/WifiHS20( 1040): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=283517  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=283517  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1040): Removing idletimer
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1040): Setting airplane_mode_on has moved from, android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=283539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=283544  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 7292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1040): StoppedState
D/DhcpStateMachine( 1040): StoppedState{ when=-124ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7292): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7292): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7292): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7292): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7292): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7292): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6682:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10008/pid_6682/cgroup.procs: No such file or directory
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 51836(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.533ms total 130.933ms
,I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7292): LgDataFeature() Constructor: none
D/LgDataFeature( 7292): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7344 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1040): Killing 6705:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 20.040ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 19.224ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 19.337ms
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6705/cgroup.procs: No such file or directory
W/ResourcesManager( 7344): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7344): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7344): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7344): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7344): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7344): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7344): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7344): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7344): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7344): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7344): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7344): LgDataFeature() Constructor: none
D/LgDataFeature( 7344): LgDataFeature() Constructor Done, null
,V/SoundPool( 7344): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7344): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7344): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7344): doLoad: loading sample sampleID=1
I/QRemote ( 7344): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7344): Start decode
V/MediaPlayer[Native]( 7344): decode(31, 10857164, 17813)
D/UEI.SmartControl( 6908): QS Service created
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
,V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb14ce400, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
,V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6908): Service initServices...
D/UEI.SmartControl( 6908): QS start get config
D/QRemote ( 7344): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
,V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/LGMDMManager( 7344): Create singleton instance
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcba0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcbf0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mSta,te=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb14ce400, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb14ce400, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796464
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796704
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796784
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797504
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcbf0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcba0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb14ce400, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab602000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab603000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab604000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab605000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab606000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab607000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab608000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab609000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60a000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60b000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60c000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60d000, 0xb57c7000, 4096)
,V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60e000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab60f000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab610000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab611000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab612000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab613000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab614000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab615000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab616000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab617000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab618000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab619000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61a000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61b000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61c000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61d000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61e000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab61f000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab620000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab621000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab622000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab623000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab624000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab625000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab626000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab627000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab628000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab629000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62a000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62b000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62c000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62d000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62e000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab62f000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab630000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab631000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab632000, 0xb57c7000, 4096)
V/AudioCache(  315): write(0xb57c7000, 4096)
V/AudioCache(  315): memcpy(0xab633000, 0xb57c7000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb57c7000, 280)
V/AudioCache(  315): memcpy(0xab634000, 0xb57c7000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb14ce400, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb14ce400, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb14ce400, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcab0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcba0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcbf0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 7344): close(31)
V/SoundPool( 7344): pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9716
,I/UEI.SmartControl( 6908): Supports setup maps: true
D/UEI.SmartControl( 6908): QS start statue = true Error code = 0
I/UEI.SmartControl( 6908): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6908): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6908): ### init IR Blaster...
,D/serial_port( 6908): Configuring serial port
E/UEI.SmartControl( 6908): UEIBLaster setting for 616
I/UEI.SmartControl( 6908): Setting serial record hearder size = 2
I/UEI.SmartControl( 6908): configuring settings for MAXQ616
I/UEI.SmartControl( 6908): Get version...
D/UEI.SmartControl( 6908): serial port data available: 21
,D/UEI.SmartControl( 6908): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6908): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6908): QS saving settings...
D/UEI.SmartControl( 6908): IR Blaster version: 25672567
,D/UEI.SmartControl( 6908): serial port data available: 4
,I/UEI.SmartControl( 6908): Device manager: loading config....
D/UEI.SmartControl( 6908): ----------- loading internal config...
W/ContextImpl( 6908): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6908): Services init done
D/UEI.SmartControl( 6908): QS Service init finished
D/UEI.SmartControl( 6908): QS Service version name: 2.1.91
D/UEI.SmartControl( 6908): QS Service version code: 201091
D/UEI.SmartControl( 6908): Service requested: Control
E/UEI.SmartControl( 6908): Loading SETTINGS...
D/UEI.SmartControl( 6908): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6908): Internal service binding...
I/QRemote ( 7344): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6908): ------ IControl API: 11
D/UEI.SmartControl( 6908): File observer start...
E/UEI.SmartControl( 6908): IR Port is disabled: false
D/UEI.SmartControl( 6908): Starting file observer...
I/UEI.SmartControl( 6908): Registering callback...
I/UEI.SmartControl( 6908): ------ IControl API: 19
D/UEI.SmartControl( 6908): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6908): Registering Services Ready callback...
I/UEI.SmartControl( 6908): Notify AllClients services are ready: 0
,I/QRemote ( 7344): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6908): -----service ready thread exits
D/QRemote ( 7344): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7344): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7344): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7344): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6908): ------ IControl API: 8
D/QRemote ( 7344): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7344): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7344): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7344): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7344): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7344): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7344): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7344): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7344): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453202210003]
D/QRemote ( 7344): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1040): Killing 6728:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7344): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6728/cgroup.procs: No such file or directory
,V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7344): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2631): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=285651  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=285652  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
,D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2631): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=285758  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=285758  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=285759
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=285760
I/wpa_supplicant( 2631): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2631): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=285761
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=285762
E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=285763
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=285763  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=285766  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=285781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=285781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=285782
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=285782
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7292): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7292): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7292): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 7292): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7292): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7292): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
D/UsbSettingsControl( 7292): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1040): Got NetworkAgent Messenger
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1040): NetworkAgent connected
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/DhcpStateMachine( 1040): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285840  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1040):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateFOUR_WAY_HANDSHAKE
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285849  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285850  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285850  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
,I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@128586d1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@128586d1 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
,I/wpa_supplicant( 2631): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1040): Adding iface wlan0 to network 101
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1971): handleWifiStateChangedEvent: 1
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
W/dsqn    ( 7406): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7406): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/DSQN    ( 7406): DSQN ssw
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
,I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7344): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7344): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7344): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7292): MCCMNC not supported: null
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7344): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7344): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7344): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1040): start to monitor internet connection
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1040): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7412): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7412): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 11:16:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453202211003], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453202210982]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
I/dhcpcd  ( 7412): version 5.5.6 starting
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/dhcpcd  ( 7412): get_duid: m
D/dhcpcd  ( 7412): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7412): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7412): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7412): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7412): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7412): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7412): wlan0: sending REQUEST (xid 0x320ba69d), next in 3.56 seconds
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3,
I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7438 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7438): onCreate
,W/AppUp4:DB( 7438):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7438):  setFingerPrint start
I/AppUp4:DB( 7438):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7438):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7438):  SDK version = 21
I/AppUp4:DB( 7438):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7438): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7438): onReceive
D/LgDataFeature( 7438): LgDataFeature() Constructor: none
,D/LgDataFeature( 7438): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7438): Context : android.app.ReceiverRestrictedContext@23970a57
D/AppUp4:CustFacade( 7438): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7438): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7438): begin check event
I/AppUp4:CustModeStarterReceiver( 7438): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7438): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7438): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7438): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7438): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6752:com.lge.email/u0a23 (adj 15): empty #17
,D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6752/cgroup.procs: No such file or directory
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3375): DownloadService onCreate
D/LGDMClient( 4291): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4291): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@1ffc9f4b on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@dc28a41 on behalf of 3375
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7468 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3375): DownloadService onStartCommand
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4291): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4291): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4291): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@3ef3e527 on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): processing inserted download 22
,V/DownloadManager( 3375): DownloadService onDestroy
,W/ResourcesManager( 7468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7468): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7468): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7468): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7468): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7468): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7468): LgDataFeature() Constructor: none
D/LgDataFeature( 7468): LgDataFeature() Constructor Done, null
,D/eas_req ( 7468): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7490 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7468): JNI_OnLoad()
I/HubEmail( 7468): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7468): registerNatives()
I/HubEmail( 7468): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7468): registerNativeMethods()
I/HubEmail( 7468): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7468): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1040): Killing 6779:com.android.gallery3d/u0a27 (adj 15): empty #17
W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6779/cgroup.procs: No such file or directory
W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524295
I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
I/dhcpcd  ( 7412): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7514 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7412): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7412): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7412): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7412): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7412): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7412): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7412): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7412): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7490): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7490): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7558 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6824:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
,W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6824/cgroup.procs: No such file or directory
I/ActivityManager( 1040): Killing 6865:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7197): 
W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6865/cgroup.procs: No such file or directory
I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7579 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6977:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6977/cgroup.procs: No such file or directory
I/art     ( 7579): Almond Protected OAT
D/WeatherApplication( 7579): removeAccount
D/WeatherApplication( 7579): Account.length = 0
E/WeatherApplication( 7579): OPERATOR:OPEN
D/WeatherAncestor( 7579): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:53
D/Weather.Utils( 7579): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7579): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7579): 2 : This is isUpdating : false
D/WeatherAncestor( 7579): connectivity changed - connection : true
D/WeatherService( 7579): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7579): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7579): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7579): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7579): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7579): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:53
I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7597 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6947:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1040): failed to open /acct/uid_10097/pid_6947/cgroup.procs: No such file or directory
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7597): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7597): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7597): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7597): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7197): 
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7197): 
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7197): 
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7197): 
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7197): 
I/jxcore-log( 7197): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7197): 
V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
I/WebViewFactory( 7597): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering( 1040): MasterInitialState.processMessage what=3
I/LibraryLoader( 7597): Loading: webviewchromium
I/LibraryLoader( 7597): Time to load native libraries: 3 ms (timestamps 8976-8979)
I/LibraryLoader( 7597): Expected native library version number "",actual native library version number ""
I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
V/WebViewChromiumFactoryProvider( 7597): Binding Chromium to main looper Looper (main, tid 1) {1cca7c5e}
I/LibraryLoader( 7597): Expected native library version number "",actual native library version number ""
I/chromium( 7597): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7597): Initializing chromium process, renderers=0
W/art     ( 7597): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7597): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7597): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7597): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb14fd760, uid 10093
W/AudioManagerAndroid( 7597): Requires BLUETOOTH permission
I/Adreno-EGL( 7597): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7597): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7597): Build Date: 12/12/14 금
I/Adreno-EGL( 7597): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7597): Remote Branch: 
I/Adreno-EGL( 7597): Local Patches: 
I/Adreno-EGL( 7597): Reconstruct Branch: 
,I/NSApplication( 7597): Starting up...
,I/ActivityManager( 1040): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7659 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6023:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_6023/cgroup.procs: No such file or directory
,W/ResourcesManager( 7659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7438): onReceive
,D/AppUp4:CustFacade( 7438): Context : android.app.ReceiverRestrictedContext@23970a57
D/AppUp4:CustFacade( 7438): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7438): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7438): begin check event
I/AppUp4:CustModeStarterReceiver( 7438): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSActivity( 2136): [ac] getting account id
I/GLSUser ( 2136): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4291): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4291): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3375): DownloadService onCreate
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@2e6c897d on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
E/LGDMClient( 4291): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4291): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4291): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@29c8d072 on behalf of 3375
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2371): [AccountUtils] Account not ready
W/Kids    ( 2371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2371): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2371): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3375): DownloadService onStartCommand
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@32bd4079 on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
V/DownloadManager( 3375): processing inserted download 9
,V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): processing inserted download 22
W/ResourcesManager( 1423): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1423): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
,D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
V/DownloadManager( 3375): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/WeatherAncestor( 7579): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:54
D/Weather.Utils( 7579): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7579): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7579): 2 : This is isUpdating : false
D/WeatherAncestor( 7579): connectivity changed - connection : true
D/WeatherService( 7579): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@215aa2d
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/ForecastDataCache( 7579): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7579): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7579): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7579): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7579): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:54
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,W/ResourcesManager( 1423): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1423): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{3ad6521f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,V/FormManager( 7490): There are no updated forms. The schedule will be deleted.
V/FormManager( 7490): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2136): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1040): Explicit concurrent mark sweep GC freed 64080(2MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 1.572ms total 90.730ms
,V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7438): [onReceive] request level :IDLE....
D/UEI.SmartControl( 6908): Internal timer expired: 4
,D/UEI.SmartControl( 6908): unbind internal service
I/AppUp4:CustModeStarterReceiver( 7438): onReceive
,D/AppUp4:CustFacade( 7438): Context : android.app.ReceiverRestrictedContext@23970a57
D/AppUp4:CustFacade( 7438): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7438): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7438): begin check event
I/AppUp4:CustModeStarterReceiver( 7438): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3375): DownloadService onCreate
,I/LGDMClient( 4291): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4291): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@3ad6521f on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
E/LGDMClient( 4291): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3375): DownloadService onStartCommand
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 4291): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/serial_port( 6908): close(fd = 24)
D/LGDMClient( 4291): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@3dfdfbca on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
I/UEI.SmartControl( 6908): Serial port is closed.
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): processing inserted download 8
V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@1017f13b on behalf of 3375
V/DownloadManager( 3375): processing inserted download 18
,V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): processing inserted download 22
W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 2136): Explicit concurrent mark sweep GC freed 49998(2MB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.769ms total 57.724ms
I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = true
D/PhoneState( 3344): setPdpRejectCasuse : false
,W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): DownloadService onDestroy
,D/WeatherAncestor( 7579): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:55
D/Weather.Utils( 7579): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7579): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7579): 2 : This is isUpdating : false
D/WeatherAncestor( 7579): connectivity changed - connection : true
D/WeatherService( 7579): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@215aa2d
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 7579): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7579): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7579): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7579): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7579): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:16:55
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,W/Kids    ( 2371): [AccountUtils] Account not ready
W/Kids    ( 2371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2371): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2371): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{3ad6521f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
V/FormManager( 7490): There are no updated forms. The schedule will be deleted.
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/FormManager( 7490): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
W/Kids    ( 2371): [AccountUtils] Account not ready
W/Kids    ( 2371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2371): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2371): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
,D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{3ad6521f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 7197): Test app app.js loaded
I/jxcore-log( 7197): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7197): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7197): BLE advertisement is supported
I/jxcore-log( 7197): 
I/chromium( 7197): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7197): --= Surplus to requirements =--
I/jxcore-log( 7197): 
I/jxcore-log( 7197): ****TEST TOOK:  ms ****
I/jxcore-log( 7197): 
I/jxcore-log( 7197): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7197): 
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{13c97485 type 2 when 292315 com.google.android.gms} when 292315
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9716
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2136): Connected
,D/GCM     ( 2136): Message class com.google.f.a.a.p
D/AndroidRuntime( 7742): 
D/AndroidRuntime( 7742): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7742): CheckJNI is OFF
D/AndroidRuntime( 7742): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1040): Killing 7197:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1040): Skipping PackageSetting{4a0f73c com.example.hello/10319} due to missing metadata
,I/WindowState( 1040): WIN DEATH: Window{3dbe987f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1040): Client connection lost with reason: 4
D/InputDispatcher( 1040): Window went away: Window{3dbe987f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1040):   Force finishing activity ActivityRecord{3cd5dad8 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
,W/ActivityManager( 1040): Spurious death for ProcessRecord{322552da 7197:com.test.thalitest/u0a311}, curProc for 7197: null
I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1040):   Force finishing activity ActivityRecord{3cd5dad8 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1040): Duplicate finish request for ActivityRecord{3cd5dad8 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2090): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{1b2690e7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{93c4494 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
,E/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2036): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3739): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1040): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4489): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4489): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4489): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4489): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4489): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4489): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4489): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4489): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4489): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4489): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4489): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4489): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4536): Explicit concurrent mark sweep GC freed 16108(914KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 601us total 77.462ms
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,D/administrator( 1040): Handling package changes for user 0
,D/PostponalbeReceiver( 6655): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
,I/ActivityManager( 1040): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7768 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1934): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3739): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1478): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2090): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2090): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2090): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1934): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3739): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,V/BoardContentProvider( 3739): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1478): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2090): , create_time: 1430558575574
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2090): , create_time: 1430558575600
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2090): , create_time: 1452774039338
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
D/WallpaperManager( 2090): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1caaae0c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/AppUp4:PreloadHelper( 7438): added Exclude : com.test.thalitest
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/ActivityManager( 1040): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7789 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,W/ActivityManager( 1040): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
I/LockScreenSettings( 7768): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/NotificationService( 1040): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1040): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1040): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2090): [Launcher.java:5349:onStop()]onStop
D/TaskPersister( 1040): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
,W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
,W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
I/ActivityManager( 1040): Killing 7015:com.lge.bnr/1000 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     ( 1040): Explicit concurrent mark sweep GC freed 24717(1557KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 3.223ms total 382.587ms
D/KeyguardModel( 1478): handleShortcutListChanged...
D/AndroidRuntime( 7742): Shutting down VM
,I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2090): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_7015/cgroup.procs: No such file or directory
,I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{9cc41e7 u0 com.lge.launcher2/.Launcher t3} time:293573
D/[Concierge]Service( 2632): onStartCommand(). Type : 8
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/[Concierge]Service( 2632): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/KeyguardModel( 1478): createShortcutInfo...
D/[Concierge]Service( 2632): Update widget ID : 11
D/[Concierge]WidgetView( 2090): change position of spinner
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
I/[Concierge]WidgetView( 2090): initWebView(). Time : 1453202218490
D/[Concierge]Service( 2632): onStartCommand(). Type : 0
W/ResourcesManager( 1040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardModel( 1478): handleShortcutListChanged...
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{39c77197 type 2 when 293583 android} when 293583
W/ResourceType( 1040): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/SystemConfig( 7789): BUILD Country: EU
I/SystemConfig( 7789): BUILD Operator: OPEN
,I/[Concierge]WebView( 2090): Return exist ConciergeWebView. Reuse : 741533813
D/[Concierge]WidgetView( 2090): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2090): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@42b1f34
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2090): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2090): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2090): Widget kill message received. Destory myself. My : 1453201952677, New one : 1453202218490
D/[Concierge]WidgetView( 2090): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2090): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1040): Killing 6433:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2090): Timeline: Activity_idle id: android.os.BinderProxy@162c0f88 time:293710
,W/libprocessgroup( 1040): failed to open /acct/uid_10054/pid_6433/cgroup.procs: No such file or directory
,I/GAV4    ( 7597): Thread[GAThread,5,main]: No campaign data found.
I/PackageChangeReceiver( 7468): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/VoicemailCleanupService( 2200): Cleaning up data for package: com.test.thalitest
,I/SystemConfig( 7789): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7789): existFile = false
I/SystemConfig( 7789): canReadFile = false
I/SystemConfig( 7789): systemFeature RCS result false
D/SystemConfig( 7789): refreshRcsSupport() :false
I/chromium( 2090): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1040): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7814 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.115ms,
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 219us total 9.111ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.947ms
W/ResourcesManager( 7814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7814): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7814): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7814): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardtInterface( 2090): onReloaded()
,I/GBoardWebViewClient( 2090): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3739): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3739): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1934): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3739): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3739): onEvent() : ACTION_BOARD_ENABLED

```
