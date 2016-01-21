#### Test 56672827039a409_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257998008166; DSPS: 8594929; Offset : -4312921516
,D/AndroidRuntime( 6977): 
D/AndroidRuntime( 6977): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6977): CheckJNI is OFF
D/AndroidRuntime( 6977): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1972): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{18b3a8c8 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{18b3a8c8 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6996 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6977): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1874): Display #0 changed.
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{230d58f1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{392e7cd6 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6996): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6996): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6996): Loading: webviewchromium
I/LibraryLoader( 6996): Time to load native libraries: 4 ms (timestamps 2247-2251)
I/LibraryLoader( 6996): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6996): Binding Chromium to main looper Looper (main, tid 1) {3db4e1}
I/LibraryLoader( 6996): Expected native library version number "",actual native library version number ""
I/chromium( 6996): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6996): Initializing chromium process, renderers=0
W/art     ( 6996): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  327): registerClient() client 0xb1450120, uid 10311
W/chromium( 6996): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6996): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b1a3f12:true
I/chromium( 6996): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6996): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6996): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6996): Build Date: 12/12/14 금
I/Adreno-EGL( 6996): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6996): Remote Branch: 
I/Adreno-EGL( 6996): Local Patches: 
I/Adreno-EGL( 6996): Reconstruct Branch: 
W/chromium( 6996): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6996): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6996): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6996): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6996): CordovaWebView is running on device made by: LGE
W/art     ( 6996): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6996): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{149bfd61 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6996): Render dirty regions requested: true
I/OpenGLRenderer( 6996): Initialized EGL, version 1.4
D/OpenGLRenderer( 6996): Enabling debug mode 0
D/Atlas   ( 6996): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{3621d73c u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@280f27b2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6996): LgDataFeature() Constructor: none
D/LgDataFeature( 6996): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +668ms (total +757ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{149bfd61 u0 com.test.thalitest/.MainActivity t4} time:272699
I/Timeline( 6996): Timeline: Activity_idle id: android.os.BinderProxy@3f8c9851 time:272701
I/chromium( 6996): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6996): 
D/JsMessageQueue( 6996): Set native->JS mode to OnlineEventsBridgeMode
E/GBMv2   (  349): DFP En is all cleared set to be enabled
E/GBMv2   (  349): Set value is all cleared set the max
I/GBMv2   (  349): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6996): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435075840
I/chromium( 6996): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6996): 
I/chromium( 6996): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/jxcore-log( 6996): Initializing JXcore engine
W/jxcore-log( 6996): JXcore engine is ready
W/Thread-804( 7064): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9777]" dev="sockfs" ino=9777 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-804( 7064): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-804( 7064): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10413]" dev="sockfs" ino=10413 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-804( 7064): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-804( 7064): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33542]" dev="sockfs" ino=33542 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6996): Starting JXcore engine
,I/art     ( 6996): Background sticky concurrent mark sweep GC freed 136390(13MB) AllocSpace objects, 21(7MB) LOS objects, 28% free, 40MB/56MB, paused 2.310ms total 161.244ms
,W/jxcore-log( 6996): Platform android
W/jxcore-log( 6996): 
,W/jxcore-log( 6996): Process ARCH arm
W/jxcore-log( 6996): 
,I/jxcore-log( 6996): JXcore Cordova bridge is ready!
I/jxcore-log( 6996): 
W/jxcore-log( 6996): JXcore engine is started
,I/jxcore-log( 6996): Toggling radios to true
I/jxcore-log( 6996): 
,D/BluetoothAdapter( 6996): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6996, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1037): setWifiEnabled: true pid=6996, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6996, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=6996, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6996): Radios toggled
I/jxcore-log( 6996): 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6996): My device name is: LGE-LG-D855
I/jxcore-log( 6996): 
,E/WifiNative: ( 1037): [275,216,583 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/wpa_supplicant( 2689): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1037): InitialState.processMessage what=4
,E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true,
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
V/NativeCrypto( 2146): Read error: ssl=0xaa716000: I/O error during system call, Connection timed out
D/DhcpStateMachine( 1037): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2146): SSL shutdown failed: ssl=0xaa716000: I/O error during system call, Broken pipe
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7087 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1972): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [275,379,915 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2689): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=275388
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=275389
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  321): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=275434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=275435  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=275442  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI ,Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=275457  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,W/ResourcesManager( 7087): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7087): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7087): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7087): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7087): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7087): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7087): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7087): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7087): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7115 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6582:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6582/cgroup.procs: No such file or directory
,I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7115): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7087): LgDataFeature() Constructor: none
D/LgDataFeature( 7087): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7139 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6088:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6088/cgroup.procs: No such file or directory
,W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7139): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7139): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7139): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7139): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7139): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7139): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7139): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7139): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7139): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7139): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7115): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7115): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.,
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7115): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7139): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7139): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7139): LgDataFeature() Constructor: none
D/LgDataFeature( 7139): LgDataFeature() Constructor Done, null
,V/SoundPool( 7139): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7139): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7139): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7139): doLoad: loading sample sampleID=1
I/QRemote ( 7139): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7139): Start decode
V/MediaPlayer[Native]( 7139): decode(31, 10857164, 17813)
V/MediaPlayerService(  327): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  327): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  327): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  327): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  327): player type = 3
V/AwesomePlayer(  327): AwesomePlayer create()
V/AwesomePlayer(  327): reset_l() 
,V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): setAudioSink() 
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb1163ac0, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/Utils   (  327): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  327): setDataSource_l dataSource
V/LGParserOSAL(  327): SniffLGParser start
V/LGParserOSAL(  327): MainType:5, SubType=0
V/LGParserOSAL(  327): #### check Mime : application/ogg
V/LGParserOSAL(  327): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  327): Use LGExtractor :application/ogg 
V/LGParserOSAL(  327): supported mime: application/ogg
V/AwesomePlayer(  327): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  327): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  327): mBitrate = -1 bits/sec
V/AwesomePlayer(  327): AudioTrack Setting
V/AwesomePlayer(  327): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  327): setAudioSource() 
V/MediaPlayerService(  327): prepare
V/AwesomePlayer(  327): prepareAsync_l() 
V/MediaPlayerService(  327): wait for prepare
V/AwesomePlayer(  327): onPrepareAsyncEvent() 
V/AwesomePlayer(  327): initAudioDecoder() 
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  327): isAudioPlaybackHookOn() false
V/AwesomePlayer(  327): getUseOffload() = 0 
V/OMXCodec(  327): OMXCodec::Create
V/OMXCodec(  327): findMatchingCodecs()
V/OMXCodec(  327): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  327): matchingCodecs.size()=1
V/OMXCodec(  327): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  327): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  327): LG Codec Adapter start
,V/OMXCodec(  327): OMXCodec Createtor
V/OMXCodec(  327): setComponentRole
V/OMXCodec(  327): configureCodec protected=0
V/LGCodecAdapter(  327): called getLGCodecSpecificData
V/LGCodecOSAL(  327): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMSG
V/LGCodecOSAL(  327): Not support LGCodec
,V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  327): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  327): Could not offload audio decode, try pcm offload
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  327): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  327): init()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  327): allocateBuffers
V/OMXCodec(  327): allocateBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14348d0 on output port
V/OMXCodec(  327): init() mAsyncCompletion wait!!! 
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  327): init() mAsyncCompletion wait!!! 
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  327): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  327): finishAsyncPrepare_l() 
V/AudioCache(  327): notify(0xb1163ac0, 5, 0, 0)
V/AudioCache(  327): ignored
V/AudioCache(  327): notify(0xb1163ac0, 1, 0, 0)
V/AudioCache(  327): prepared
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): start
V/AwesomePlayer(  327): play_l() 
V/AwesomePlayer(  327): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  327): createAudioPlayer_l
V/AwesomePlayer(  327): seekAudioIfNecessary_l() 
V/AwesomePlayer(  327): startAudioPlayer_l() 
D/AudioPlayer(  327): start of Playback, useOffload 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  327): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
V/OMXCodec(  327): [OMX.google.v,orbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976784
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  327): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1451060 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  327): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  327): notify(0xb1163ac0, 6, 0, 0)
V/AudioCache(  327): ignored
V/MediaPlayerService(  327): wait for playback complete
I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7165 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 7139): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac700000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac701000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac702000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac703000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac704000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac705000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac706000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac707000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac708000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac709000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70a000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70b000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70c000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70d000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70e000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac70f000, 0xb124d000, 4096)
E/QRemote ( 7139): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac710000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac711000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac712000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac713000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac714000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac715000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac716000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac717000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac718000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac719000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71a000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71b000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71c000, 0xb124d000, 4096)
,V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71d000, 0xb124d000, 4096)
V/LGMDMManager( 7139): Create singleton instance
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71e000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac71f000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac720000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac721000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac722000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac723000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac724000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac725000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac726000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac727000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac728000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac729000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72a000, 0xb124d000, 4096)
,V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72b000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72c000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72d000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72e000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac72f000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac730000, 0xb124d000, 4096)
V/AudioCache(  327): write(0xb124d000, 4096)
V/AudioCache(  327): memcpy(0xac731000, 0xb124d000, 4096)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  327): postAudioEOS() 
V/AudioCache(  327): write(0xb124d000, 280)
V/AudioCache(  327): memcpy(0xac732000, 0xb124d000, 280)
V/AwesomePlayer(  327): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  327): onStreamDone
V/AwesomePlayer(  327): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  327): notify(0xb1163ac0, 2, 0, 0)
V/AudioCache(  327): playback complete
V/AwesomePlayer(  327): pause_l() 
V/AudioCache(  327): notify(0xb1163ac0, 7, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/AudioPlayer(  327): Pause Playback at 1068125
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb1163ac0, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/AudioPlayer(  327): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1451060 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  327): [OMX.google.vorb,is.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  327): AudioPlayer releasing audio source
D/AudioPlayer(  327): AudioPlayer done releasing audio source
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): ~AwesomePlayer call
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/SoundPool( 7139): close(31)
V/SoundPool( 7139): pointer = 0x9ffc6000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3451
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 49958(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.573ms total 118.487ms,
,D/UEI.SmartControl( 7165): Quickset Services start...
,I/UEI.SmartControl( 7165): Manufacture = LGE
D/UEI.SmartControl( 7165): Id = LGNevo
D/UEI.SmartControl( 7165): File observer start...
E/UEI.SmartControl( 7165): IR Port is disabled: false
D/UEI.SmartControl( 7165): Starting file observer...
D/UEI.SmartControl( 7165): Extracting JNI libs...
D/UEI.SmartControl( 7165): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7165): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7165): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7165): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7165): --- Selecting new region: 6
,I/UEI.SmartControl( 7165): Model = LG-D855
D/UEI.SmartControl( 7165): QS Service created
I/UEI.SmartControl( 7165): Service initServices...
D/UEI.SmartControl( 7165): QS start get config
,D/UEI.SmartControl( 7165): Loading JNI Libs...
,I/UEI.SmartControl( 7165): Supports setup maps: true
,D/UEI.SmartControl( 7165): QS start statue = true Error code = 0
I/UEI.SmartControl( 7165): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7165): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 7165): ### init IR Blaster...
D/serial_port( 7165): Configuring serial port
E/UEI.SmartControl( 7165): UEIBLaster setting for 616
I/UEI.SmartControl( 7165): Setting serial record hearder size = 2
I/UEI.SmartControl( 7165): configuring settings for MAXQ616
I/UEI.SmartControl( 7165): Get version...
D/UEI.SmartControl( 7165): serial port data available: 21
,D/UEI.SmartControl( 7165): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7165): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7165): QS saving settings...
D/UEI.SmartControl( 7165): IR Blaster version: 25672567
,D/UEI.SmartControl( 7165): serial port data available: 4
,W/ContextImpl( 7165): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 7165): Device manager: loading config....
D/UEI.SmartControl( 7165): ----------- loading internal config...
E/UEI.SmartControl( 7165): Services init done
D/UEI.SmartControl( 7165): QS Service init finished
D/UEI.SmartControl( 7165): QS Service version name: 2.1.91
D/UEI.SmartControl( 7165): QS Service version code: 201091
D/UEI.SmartControl( 7165): Service requested: Control
E/UEI.SmartControl( 7165): Loading SETTINGS...
,D/UEI.SmartControl( 7165): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7165): Internal service binding...
I/QRemote ( 7139): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 7165): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7165): ------ IControl API: 11
I/UEI.SmartControl( 7165): Registering callback...
,I/UEI.SmartControl( 7165): ------ IControl API: 19
I/UEI.SmartControl( 7165): Registering Services Ready callback...
I/UEI.SmartControl( 7165): Notify client services are ready...
I/QRemote ( 7139): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/UEI.SmartControl( 7165): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7165): -----service ready thread exits
I/QRemote ( 7139): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7139): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7139): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 7139): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7139): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7165): ------ IControl API: 8
D/QRemote ( 7139): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7139): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7139): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7139): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 7139): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7139): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7139): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7139): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7139): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7139): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453396745227]
D/QRemote ( 7139): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6618:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7139): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1037): Killing 6107:com.android.contacts/u0a19 (adj 15): empty #18
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6618/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6107/cgroup.procs: No such file or directory
V/QRemote ( 7139): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7139): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7139): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7139): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2689): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=277510  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=277519  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7139): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2689): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=277616  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=277617  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2689): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2689): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=277626
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=277627
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=277631
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=277631
,D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7087): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7087): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7087): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=277632
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=277633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=277641  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsControl( 7087): [AUTORUN] getUsbConnected() : connected=true
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=277646  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=277647  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7087): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7087): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 7087): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=277650
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=277650
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  321): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=277702  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=277704  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=277705  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=277708  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=277708  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=277708  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b8d73c1 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b8d73c1 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  321): Setting iface cfg
D/CommandListener(  321): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2689): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1037): Adding iface wlan0 to network 101
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1972): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  321): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/,LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
W/dsqn    ( 7227): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/DSQN    ( 7227): DSQN ssw
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/dsqn    ( 7227): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7139): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7139): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7139): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7139): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7115): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7115): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7087): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7087): MCCMNC not supported: null
D/QRemote ( 7139): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7139): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7139): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7139): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7139): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  321): argv[0]=dsqncommand
D/LGDataListener(  321): argv[1]=wlan0
D/LGDataListener(  321): argv[2]=1
D/LGDataListener(  321): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 17:19:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453396746046], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453396746020]}
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
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,W/dhcpcd  ( 7233): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7233): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 278002484376; DSPS: 9250434; Offset : -4312870381
,I/dhcpcd  ( 7233): version 5.5.6 starting
E/dhcpcd  ( 7233): get_duid: m
D/dhcpcd  ( 7233): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7233): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7233): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7233): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7233): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7233): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7233): wlan0: sending REQUEST (xid 0x500702dd), next in 4.13 seconds
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5442): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5442): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7261 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7261): onCreate
,W/AppUp4:DB( 7261):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7261):  setFingerPrint start
,I/AppUp4:DB( 7261):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7261):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7261):  SDK version = 21
I/AppUp4:DB( 7261):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7261): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7261): onReceive
D/LgDataFeature( 7261): LgDataFeature() Constructor: none
D/LgDataFeature( 7261): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7261): Context : android.app.ReceiverRestrictedContext@45ca0c7
,D/AppUp4:CustFacade( 7261): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7261): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7261): begin check event
I/AppUp4:CustModeStarterReceiver( 7261): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7261): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7261): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7261): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7261): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6484:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6484/cgroup.procs: No such file or directory
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3371): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3371): DownloadService onCreate
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3371): in removeSpuriousFiles
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@3bbde2bb on behalf of 3371
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,I/DownloadManager( 3371): in trimDatabase
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@3f789331 on behalf of 3371
,I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7290 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3371): DownloadService onStartCommand
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3371): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@2bddef97 on behalf of 3371
V/DownloadManager( 3371): processing inserted download 1
V/DownloadManager( 3371): processing inserted download 4
,V/DownloadManager( 3371): processing inserted download 7
V/DownloadManager( 3371): processing inserted download 8
V/DownloadManager( 3371): processing inserted download 9
V/DownloadManager( 3371): processing inserted download 10
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3371): processing inserted download 16
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3371): processing inserted download 17
V/DownloadManager( 3371): processing inserted download 18
V/DownloadManager( 3371): processing inserted download 21
V/DownloadManager( 3371): processing inserted download 22
V/DownloadManager( 3371): DownloadService onDestroy
,W/ResourcesManager( 7290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7290): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7290): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7290): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7290): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7290): LgDataFeature() Constructor: none
D/LgDataFeature( 7290): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/eas_req ( 7290): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/dhcpcd  ( 7233): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524295
,I/dhcpcd  ( 7233): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7233): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7233): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7233): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7233): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 7233): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7233): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7233): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7321 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7290): JNI_OnLoad()
I/HubEmail( 7290): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7290): registerNatives()
I/HubEmail( 7290): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7290): registerNativeMethods()
I/HubEmail( 7290): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7290): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6644:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6644/cgroup.procs: No such file or directory
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/LgeMiscReceiver( 3345): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3345): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3345): networkInfo.isConnected() = false
I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7367 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/art     (  354): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.977ms
,I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 19.495ms
,I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 17.741ms
,D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7321): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7321): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7388 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6671:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6996): 
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6671/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6729:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6729/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7410 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6787:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6787/cgroup.procs: No such file or directory
,I/art     ( 7410): Almond Protected OAT
,D/WeatherApplication( 7410): removeAccount
,D/WeatherApplication( 7410): Account.length = 0
E/WeatherApplication( 7410): OPERATOR:OPEN
D/WeatherAncestor( 7410): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:8
,D/Weather.Utils( 7410): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7410): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7410): 2 : This is isUpdating : false
D/WeatherAncestor( 7410): connectivity changed - connection : true
D/WeatherService( 7410): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7410): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7410): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7410): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7410): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7410): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:8
I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6996): 
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7428 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6016:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6996): 
I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6996): 
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6016/cgroup.procs: No such file or directory
,I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6996): 
,I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6996): 
,I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6996): 
I/jxcore-log( 6996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6996): 
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7428): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,I/WebViewFactory( 7428): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7428): Loading: webviewchromium
I/LibraryLoader( 7428): Time to load native libraries: 4 ms (timestamps 837-841)
,I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5442): type=WIFI subType= reason=null isConnected=true
,V/WebViewChromiumFactoryProvider( 7428): Binding Chromium to main looper Looper (main, tid 1) {2485288e}
I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
I/chromium( 7428): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/BrowserStartupController( 7428): Initializing chromium process, renderers=0
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7428): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7428): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 7428): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:229536 len:643667
V/AudioPolicyService(  327): registerClient() client 0xb1427040, uid 10093
W/AudioManagerAndroid( 7428): Requires BLUETOOTH permission
,I/Adreno-EGL( 7428): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7428): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7428): Build Date: 12/12/14 금
I/Adreno-EGL( 7428): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7428): Remote Branch: 
I/Adreno-EGL( 7428): Local Patches: 
I/Adreno-EGL( 7428): Reconstruct Branch: 
,I/NSApplication( 7428): Starting up...
,I/ActivityManager( 1037): Killing 6825:com.lge.bnr/1000 (adj 15): empty #17
,I/jxcore-log( 6996): Test app app.js loaded
I/jxcore-log( 6996): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6996): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6996): BLE advertisement is supported
I/jxcore-log( 6996): 
I/chromium( 6996): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6825/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2351): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2351): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7261): onReceive
,D/AppUp4:CustFacade( 7261): Context : android.app.ReceiverRestrictedContext@45ca0c7
D/AppUp4:CustFacade( 7261): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7261): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7261): begin check event
I/AppUp4:CustModeStarterReceiver( 7261): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3371): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3371): DownloadService onCreate
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3371): in removeSpuriousFiles
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@1f92316d on behalf of 3371
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,I/DownloadManager( 3371): in trimDatabase
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@239c71a2 on behalf of 3371
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/jxcore-log( 6996): --= Surplus to requirements =--
I/jxcore-log( 6996): 
I/jxcore-log( 6996): ****TEST TOOK:  ms ****
I/jxcore-log( 6996): 
I/jxcore-log( 6996): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6996): 
V/DownloadManager( 3371): DownloadService onStartCommand
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3371): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@342d7769 on behalf of 3371
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3371): processing inserted download 1
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3371): processing inserted download 4
V/DownloadManager( 3371): processing inserted download 7
V/DownloadManager( 3371): processing inserted download 8
V/DownloadManager( 3371): processing inserted download 9
V/DownloadManager( 3371): processing inserted download 10
V/DownloadManager( 3371): processing inserted download 16
,V/DownloadManager( 3371): processing inserted download 17
V/DownloadManager( 3371): processing inserted download 18
V/DownloadManager( 3371): processing inserted download 21
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,I/LgeMiscReceiver( 3345): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3345): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3345): networkInfo.isConnected() = false
W/Kids    ( 2351): [AccountUtils] Account not ready
W/Kids    ( 2351): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2351): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2351): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3371): processing inserted download 22
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3371): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7410): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:9
D/Weather.Utils( 7410): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7410): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7410): 2 : This is isUpdating : false
D/WeatherAncestor( 7410): connectivity changed - connection : true
D/WeatherService( 7410): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@227fbe1d
D/ForecastDataCache( 7410): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7410): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7410): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7410): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7410): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:9
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{36c93a8f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2351): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7321): There are no updated forms. The schedule will be deleted.
,D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/FormManager( 7321): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7261): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7261): onReceive
,D/AppUp4:CustFacade( 7261): Context : android.app.ReceiverRestrictedContext@45ca0c7
D/AppUp4:CustFacade( 7261): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7261): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7261): begin check event
I/AppUp4:CustModeStarterReceiver( 7261): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3371): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3371): DownloadService onCreate
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3371): in removeSpuriousFiles
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Kids    ( 2351): [AccountUtils] Account not ready
W/Kids    ( 2351): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2351): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2351): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@3d1fb11c on behalf of 3371
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3371): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3371): in trimDatabase
V/DownloadManager( 3371): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@61d2125 on behalf of 3371
V/DownloadManager( 3371): DownloadService onStartCommand
V/DownloadManager( 3371): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1417): onNotificationPosted
V/DownloadManager( 3371): created cursor android.database.sqlite.SQLiteCursor@1f28f0ab on behalf of 3371
I/LgeMiscReceiver( 3345): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3345): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3345): networkInfo.isConnected() = true
D/PhoneState( 3345): setPdpRejectCasuse : false
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
V/DownloadManager( 3371): processing inserted download 1
V/DownloadManager( 3371): processing inserted download 4
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3371): processing inserted download 7
V/DownloadManager( 3371): processing inserted download 8
V/DownloadManager( 3371): processing inserted download 9
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/WeatherAncestor( 7410): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:9
V/DownloadManager( 3371): processing inserted download 10
D/Weather.Utils( 7410): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7410): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7410): 2 : This is isUpdating : false
D/WeatherAncestor( 7410): connectivity changed - connection : true
D/WeatherService( 7410): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@227fbe1d
V/DownloadManager( 3371): processing inserted download 16
D/ForecastDataCache( 7410): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7410): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7410): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 7410): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7410): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:19:9
V/DownloadManager( 3371): processing inserted download 17
V/DownloadManager( 3371): processing inserted download 18
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/DownloadManager( 3371): processing inserted download 21
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{36c93a8f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3371): processing inserted download 22
V/DownloadManager( 3371): DownloadService onDestroy
D/AndroidRuntime( 7510): 
D/AndroidRuntime( 7510): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ChimeraCfgMgr( 2351): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/AndroidRuntime( 7510): CheckJNI is OFF
V/FormManager( 7321): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7321): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2351): [AccountUtils] Account not ready
W/Kids    ( 2351): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2351): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2351): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2351): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2351): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{36c93a8f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/AndroidRuntime( 7510): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6996:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1037): Skipping PackageSetting{24e942ec com.example.hello/10319} due to missing metadata
,D/WifiService( 1037): Client connection lost with reason: 4
,I/WindowState( 1037): WIN DEATH: Window{3621d73c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher( 1037): Window went away: Window{3621d73c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{149bfd61 u0 com.test.thalitest/.MainActivity t4}
,D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{26588b57 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{2a720644 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ActivityManager( 1037): Spurious death for ProcessRecord{31f04243 6996:com.test.thalitest/u0a311}, curProc for 6996: null
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/[LGHome]EVENT( 2091): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2091): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,E/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3744): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2048): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.google.com, class = 1, type = 1
,I/art     ( 4576): Explicit concurrent mark sweep GC freed 16907(943KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 522us total 92.899ms
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/UEI.SmartControl( 7165): Internal timer expired: 1
D/UEI.SmartControl( 7165): unbind internal service
D/libc-netbsd(  321): res_queryN name = www.google.com succeed
,I/[LGHome]EVENT( 2091): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
W/System.err( 4531): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 4531): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4531): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4531): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4531): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4531): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4531): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4531): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4531): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4531): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4531): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/PostponalbeReceiver( 6552): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4531): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7555 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1926): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3744): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1467): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2091): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2091): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2091): [Launcher.java:1114:onPause()]onPause
D/serial_port( 7165): close(fd = 25)
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
I/art     ( 1037): Explicit concurrent mark sweep GC freed 74090(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.980ms total 173.295ms
I/art     ( 1037): WaitForGcToComplete blocked for 10.234ms for cause Explicit
,I/UEI.SmartControl( 7165): Serial port is closed.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1467): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1891): split_name #11 / not available #0
D/SplitUIService( 1891): removed split : 
,D/SplitUIManager( 1891): split_name #11 / not available #0
I/SplitUIService( 1891): split app #11
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/administrator( 1037): Handling package changes for user 0
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 5283(296KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.799ms total 89.393ms
,I/art     ( 1037): WaitForGcToComplete blocked for 113.552ms for cause Explicit
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/ActionManagerService( 1926): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,V/BoardContentProvider( 3744): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 3744): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2091): , create_time: 1430558575574
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2091): , create_time: 1430558575600
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2091): , create_time: 1453384801850
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3815): [BTUI] [-] updateMediaPlayerInfo
D/AppUp4:PreloadHelper( 7261): added Exclude : com.test.thalitest
D/WallpaperManager( 2091): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@280f27b2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/LockScreenSettings( 7555): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]EVENT( 2091): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7577 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): handleShortcutListChanged...
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 7577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 7577): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7577): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7577): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7577): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
I/ActivityManager( 1037): Killing 6861:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/art     ( 2091): Background sticky concurrent mark sweep GC freed 1823(107KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 6.794ms total 11.065ms
I/art     ( 1037): Explicit concurrent mark sweep GC freed 7575(447KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.640ms total 172.434ms
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/KeyguardModel( 1467): handleShortcutListChanged...
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6861/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2091): [Launcher.java:5349:onStop()]onStop
,D/AndroidRuntime( 7510): Shutting down VM
I/SystemConfig( 7577): BUILD Country: EU
I/SystemConfig( 7577): BUILD Operator: OPEN
,I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager( 1037): Killing 6198:com.android.vending/u0a44 (adj 15): empty #17
I/[LGHome]EVENT( 2091): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2091): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6198/cgroup.procs: No such file or directory
D/[Concierge]Service( 2636): onStartCommand(). Type : 8
,D/[Concierge]Service( 2636): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2091): change position of spinner
D/[Concierge]Service( 2636): Update widget ID : 11
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{24767c57 u0 com.lge.launcher2/.Launcher t3} time:282594
I/SystemConfig( 7577): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7577): existFile = false
I/SystemConfig( 7577): canReadFile = false
I/SystemConfig( 7577): systemFeature RCS result false
D/SystemConfig( 7577): refreshRcsSupport() :false
I/[Concierge]WidgetView( 2091): initWebView(). Time : 1453396750665
,D/[Concierge]Service( 2636): onStartCommand(). Type : 0
I/PackageChangeReceiver( 7290): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2168): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7600 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[Concierge]WebView( 2091): Return exist ConciergeWebView. Reuse : 380546897
D/[Concierge]WidgetView( 2091): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2091): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f93ac80
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2091): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2091): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 7600): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7600): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7600): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7600): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/[Concierge]WidgetView( 2091): Widget kill message received. Destory myself. My : 1453396496896, New one : 1453396750665
D/[Concierge]WidgetView( 2091): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2091): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppConfig( 7600): Total System Memory = 2995761152
D/SystemHelper( 7600): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/SharedPreferencesImpl( 7600): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1037): Killing 7115:com.lge.sync/1000 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2091): Timeline: Activity_idle id: android.os.BinderProxy@30e40b76 time:282846
,E/SharedPreferencesImpl( 2091): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
D/LIA_Service_NativeEventReceiver( 2048): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2048): startLIAService() : Trying to start LIA service ...

```
