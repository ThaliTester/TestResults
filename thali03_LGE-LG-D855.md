#### Test 56672827b6f75d5_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=106685529 [*alarm*], flags=0x0
,--------- beginning of main
D/AndroidRuntime( 7206): 
D/AndroidRuntime( 7206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7206): CheckJNI is OFF
D/AndroidRuntime( 7206): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1041): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1985): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1041): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1041): setTaskToReturnTo : TaskRecord{2476e048 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1041): setTaskToReturnTo : TaskRecord{2476e048 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1041): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1041): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7224 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7206): Shutting down VM
V/ActivityManager( 1041): Display changed displayId=0
D/DSDPConnection( 1880): Display #0 changed.
D/SplitWindowPolicy( 1985): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1985): topRunningActivity=ActivityInfo{2926e737 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1985): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1985): topRunningActivity=ActivityInfo{2b8d64a4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7224): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7224): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7224): Loading: webviewchromium
I/LibraryLoader( 7224): Time to load native libraries: 3 ms (timestamps 4014-4017)
I/LibraryLoader( 7224): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7224): Binding Chromium to main looper Looper (main, tid 1) {223bf4a7}
,I/LibraryLoader( 7224): Expected native library version number "",actual native library version number ""
,I/chromium( 7224): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7224): Initializing chromium process, renderers=0
W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  320): registerClient() client 0xb152dc40, uid 10311
,W/chromium( 7224): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7224): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7224): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1041): Message: 20
D/BluetoothManagerService( 1041): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35d7ba92:true
I/Adreno-EGL( 7224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7224): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7224): Build Date: 12/12/14 금
I/Adreno-EGL( 7224): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7224): Remote Branch: 
I/Adreno-EGL( 7224): Local Patches: 
I/Adreno-EGL( 7224): Reconstruct Branch: 
,W/chromium( 7224): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7224): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7224): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7224): CordovaWebView is running on device made by: LGE
,W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7224): Render dirty regions requested: true
I/OpenGLRenderer( 7224): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7224): Enabling debug mode 0
,D/Atlas   ( 7224): Validating map...
,D/SplitWindow( 1041): check instance of lgWin Window{11ce56bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1041): Activity pause timeout for ActivityRecord{3ea39ee1 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7224): LgDataFeature() Constructor: none
,D/LgDataFeature( 7224): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1041): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1041): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1041): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1041): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b195030,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1041): Displayed com.test.thalitest/.MainActivity: +660ms (total +743ms)
I/Timeline( 1041): Timeline: Activity_windows_visible id: ActivityRecord{3ea39ee1 u0 com.test.thalitest/.MainActivity t4} time:284552
,I/Timeline( 7224): Timeline: Activity_idle id: android.os.BinderProxy@1d355597 time:284554
I/chromium( 7224): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7224): 
,D/JsMessageQueue( 7224): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7224): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7224): 
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 7224): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435052800
,I/chromium( 7224): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 7224): Initializing JXcore engine
W/jxcore-log( 7224): JXcore engine is ready
,W/Thread-849( 7299): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10364]" dev="sockfs" ino=10364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-849( 7299): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-849( 7299): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9809]" dev="sockfs" ino=9809 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-849( 7299): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-849( 7299): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34238]" dev="sockfs" ino=34238 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 7224): Starting JXcore engine
I/art     ( 7224): Background sticky concurrent mark sweep GC freed 136945(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.146ms total 147.331ms
,W/jxcore-log( 7224): Platform android
W/jxcore-log( 7224): 
W/jxcore-log( 7224): Process ARCH arm
W/jxcore-log( 7224): 
,I/jxcore-log( 7224): JXcore Cordova bridge is ready!
I/jxcore-log( 7224): 
W/jxcore-log( 7224): JXcore engine is started
,I/jxcore-log( 7224): Toggling radios to true
I/jxcore-log( 7224): 
,D/BluetoothAdapter( 7224): enable(): BT is already enabled..!
D/WifiService( 1041): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1041): setWifiEnabled: true pid=7224, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1041): setWifiEnabled: true pid=7224, uid=10311
E/WifiService( 1041): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1041): disconnect pid=7224, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1041):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1041): [287,442,916 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1041): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1041): reconnect pid=7224, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7224): Radios toggled
I/jxcore-log( 7224): 
I/jxcore-log( 7224): My device name is: LGE-LG-D855
I/jxcore-log( 7224): 
,I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1041): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1041): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1041): DISCONNECT: returned true
E/WifiStateMachine( 1041): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
D/Tethering( 1041): InitialState.processMessage what=4
D/Tethering( 1041): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1041): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1041): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7310 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1041): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1041):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1041): [287,559,178 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1041): doBoolean: RECONNECT
,I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1041): ignoring duplicate network state non-change
,E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2130): Read error: ssl=0xaa6d9a00: I/O error during system call, Connection timed out
D/WifiHS20( 1041): hidePasspointNotification off =false
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 2130): SSL shutdown failed: ssl=0xaa6d9a00: I/O error during system call, Broken pipe
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1985): handleWifiStateChangedEvent: 0
D/WifiNative-wlan0( 1041): RECONNECT: returned true
E/WifiStateMachine( 1041):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=287569
E/WifiStateMachine( 1041):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=287569
D/WifiHS20( 1041): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1041): InactiveState{ when=-16ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-16ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/ConnectivityService( 1041): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  316): Clearing all IP addresses on wlan0
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1041): Default network via Wi-Fi disconnect. stop DSQN
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1041): disableDataServiceNotify
D/DSQN    ( 1041): stop dsqn bin
D/DSQN    ( 1041): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=287629  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=287629  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1041):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1041): hidePasspointNotification off =false
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1041):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1041): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=287634  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1041): hidePasspointNotification off =false
D/ConnectivityService( 1041): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Disconnected - quitting
D/CSLegacyTypeTracker( 1041): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1041): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1449): CM callback handler got msg 524292
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1,, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1041): Removing idletimer
W/Settings( 1041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1880): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=287649  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WIFI    ( 1041): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateSCANNING
D/TelephonyIcons( 1449): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1449): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1041): StoppedState
D/DhcpStateMachine( 1041): StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7310): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7310): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7310): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7310): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7310): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7310): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1041): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6724:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10011/pid_6724/cgroup.procs: No such file or directory
,I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7348): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7310): LgDataFeature() Constructor: none
D/LgDataFeature( 7310): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7348): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7348): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7348): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1041): Killing 6745:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1041): failed to open /acct/uid_10019/pid_6745/cgroup.procs: No such file or directory
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{347621c1 type 0 when 1453394874453 android} when 1453394874453
V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{30db5d66 type 2 when 288520 com.google.android.gms} when 288520
,E/WifiStateMachine( 1041):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:223768] from screen [on:0 period:1695929102]
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1041): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/wpa_supplicant( 2719): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1041): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1041): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1041):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1041):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1041):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1041):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1041): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289606  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2719): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1041): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289711  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289711  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1041):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289712
E/WifiStateMachine( 1041):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289712
E/WifiStateMachine( 1041):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289712
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289712
E/WifiStateMachine( 1041):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289713
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289713  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1041): sendTetherStateChangedBroadcast 1, 0, 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 2719): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1041): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
W/WifiMonitor( 1041): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1041): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289723  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289724  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289724  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1041):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289725
E/WifiStateMachine( 1041):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289725
D/WifiNative-wlan0( 1041): doString: [STATUS]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1041):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1041): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7310): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7310): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7310): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/WifiServerServiceExt( 1041): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1041): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7310): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7310): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7310): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/ConnectivityService( 1041): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/UsbSettingsControl( 7310): [AUTORUN] setTetherStatus() : status=false
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1041): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1041): NetworkAgent connected
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
D/CommandListener(  316): Setting iface cfg
E/WifiStateMachine( 1041): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1041): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1041): WaitBeforeStartState
E/WifiStateMachine( 1041):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289774  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289774  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289775  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateFOUR_WAY_HANDSHAKE
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1041):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289776  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289776  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289776  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1041):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1041): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1041): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 0
D/WifiNative-wlan0( 1041): SET ps 0: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1041): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e7c9261 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1041): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e7c9261 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1041): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1041): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1041): DHCP Start wake lock is acquired.
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1041): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1041):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateCOMPLETED
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1041):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1041):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1041): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1041):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1041): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1041): ignoring duplicate network state non-change
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1041): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1041): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1041): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1041): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1041): Adding Route [fe80::/64 -> :: wlan0] to network 101
V/WfdStateTracker( 1985): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1041): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Netd    (  316): netlink response contains error (File exists)
D/ConnectivityService( 1041): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1041): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1041): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1041): Setting Dns servers for network 101 to [/192.168.1.1]
D/WifiHS20( 1041): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1041): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1041):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Connected
D/ConnectivityService( 1041):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1041):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1041):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1041): currentScore = 0, newScore = 20
D/ConnectivityService( 1041):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1041): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1041): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1041): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1880): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1449): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1449): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1041): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1041): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1041): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1041): validation of new default Network = false
D/ConnectivityService( 1041): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1041): enableDataServiceNotify 
D/DSQN    ( 1041): start dsqn bin
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1041): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1449): CM callback handler got msg 524290
W/dsqn    ( 7398): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7398): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1041): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7398): DSQN ssw
D/TelephonyIcons( 1449): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7009): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7009): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7009): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7009): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7348): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7348): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7310): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7310): MCCMNC not supported: null
D/QRemote ( 7009): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7009): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QRemote ( 7009): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/DSQN    ( 1041): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1041): start to monitor internet connection
I/QRemote ( 7009): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7009): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 16:47:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453394876596], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453394876576]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Validated
D/ConnectivityService( 1041): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1041):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1041): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1041): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1449): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1880): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1041): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1449): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1449): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1041): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1041): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1041): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7404): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7404): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7404): version 5.5.6 starting
E/dhcpcd  ( 7404): get_duid: m
D/dhcpcd  ( 7404): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7404): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7404): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7404): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7404): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7404): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7404): wlan0: sending REQUEST (xid 0xa44b7082), next in 3.07 seconds
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{31703b6d type 2 when 290398 com.google.android.gms} when 290398
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = mtalk.google.com succeed
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1041): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1041): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5927): type=WIFI subType= reason=null isConnected=true
,D/GCM     ( 2130): Connected
,D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GCM     ( 2130): Message class com.google.f.a.a.p
,I/NetworkMonitor( 5927): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1041): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7433 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7433): onCreate
,W/AppUp4:DB( 7433):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7433):  setFingerPrint start
,I/AppUp4:DB( 7433):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7433):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7433):  SDK version = 21
I/AppUp4:DB( 7433):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7433): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7433): onReceive
,D/LgDataFeature( 7433): LgDataFeature() Constructor: none
D/LgDataFeature( 7433): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7433): Context : android.app.ReceiverRestrictedContext@f4de4fd
,D/AppUp4:CustFacade( 7433): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7433): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7433): begin check event
I/AppUp4:CustModeStarterReceiver( 7433): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7433): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7433): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7433): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7433): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1041): Killing 6768:com.lge.email/u0a23 (adj 15): empty #17
,E/WifiStateMachine( 1041):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1041): identical MTU - not setting
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1041): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1449): CM callback handler got msg 524295
D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/libprocessgroup( 1041): failed to open /acct/uid_10023/pid_6768/cgroup.procs: No such file or directory
,W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4343): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4343): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3421): DownloadService onCreate
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@5a1f411 on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@14784976 on behalf of 3421
E/LGDMClient( 4343): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4343): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4343): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager( 1041): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7463 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3421): DownloadService onStartCommand
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@14a0c04d on behalf of 3421
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
V/DownloadManager( 3421): processing inserted download 21
V/DownloadManager( 3421): processing inserted download 22
,V/DownloadManager( 3421): DownloadService onDestroy
W/ResourcesManager( 7463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7404): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/LGEmail ( 7463): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/dhcpcd  ( 7404): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7404): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7404): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7404): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7404): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7404): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7404): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7404): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/LGEmail ( 7463): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7463): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7463): LgDataFeature() Constructor: none
D/LgDataFeature( 7463): LgDataFeature() Constructor Done, null
,D/eas_req ( 7463): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1041): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7510 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7463): JNI_OnLoad()
I/HubEmail( 7463): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7463): registerNatives()
I/HubEmail( 7463): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7463): registerNativeMethods()
I/HubEmail( 7463): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7463): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1041): Killing 6789:com.android.gallery3d/u0a27 (adj 15): empty #17
D/DhcpStateMachine( 1041): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1041): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1041): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1041): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1041): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1041): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1041): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1041): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1041): RunningState
W/libprocessgroup( 1041): failed to open /acct/uid_10027/pid_6789/cgroup.procs: No such file or directory
,W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
I/ActivityManager( 1041): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7533 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1041): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7553 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6844:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7224): 
,W/libprocessgroup( 1041): failed to open /acct/uid_10061/pid_6844/cgroup.procs: No such file or directory
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1041): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7573 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6886:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
V/FormManager( 7510): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7510): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1041): failed to open /acct/uid_10080/pid_6886/cgroup.procs: No such file or directory
,I/ActivityManager( 1041): Killing 6932:com.lge.eula/1000 (adj 15): empty #17
,I/art     ( 7573): Almond Protected OAT
W/libprocessgroup( 1041): failed to open /acct/uid_1000/pid_6932/cgroup.procs: No such file or directory
,D/WeatherApplication( 7573): removeAccount
D/WeatherApplication( 7573): Account.length = 0
E/WeatherApplication( 7573): OPERATOR:OPEN
D/WeatherAncestor( 7573): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:47:59
,D/Weather.Utils( 7573): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7573): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7573): 2 : This is isUpdating : false
,D/WeatherAncestor( 7573): connectivity changed - connection : true
,D/WeatherService( 7573): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7573): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7573): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7573): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7573): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7573): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:47:59
,I/ActivityManager( 1041): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7592 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 6907:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1041):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7224): 
I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7224): 
,W/libprocessgroup( 1041): failed to open /acct/uid_10097/pid_6907/cgroup.procs: No such file or directory
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7224): 
I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7224): 
V/WifiInternetCheck( 1041): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1041): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5927): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  282): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  282): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  282): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  282): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  282): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  282): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  282): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  282): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  282): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  282): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  282): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  282): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7592): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7592): Loading: webviewchromium
I/LibraryLoader( 7592): Time to load native libraries: 3 ms (timestamps 3145-3148)
I/LibraryLoader( 7592): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7592): Binding Chromium to main looper Looper (main, tid 1) {3989df1c}
,I/LibraryLoader( 7592): Expected native library version number "",actual native library version number ""
I/chromium( 7592): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7592): Initializing chromium process, renderers=0
W/art     ( 7592): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  320): registerClient() client 0xb558a4a0, uid 10093
,W/chromium( 7592): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7592): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7592): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 7592): Requires BLUETOOTH permission
I/Adreno-EGL( 7592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7592): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7592): Build Date: 12/12/14 금
I/Adreno-EGL( 7592): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7592): Remote Branch: 
I/Adreno-EGL( 7592): Local Patches: 
I/Adreno-EGL( 7592): Reconstruct Branch: 
,I/NSApplication( 7592): Starting up...
,I/ActivityManager( 1041): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7662 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 6986:com.lge.bnr/1000 (adj 15): empty #17
I/art     (  344): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 775us total 19.942ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.937ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.653ms total 17.383ms
I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
W/libprocessgroup( 1041): failed to open /acct/uid_1000/pid_6986/cgroup.procs: No such file or directory
W/ResourcesManager( 7662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/jxcore-log( 7224): Test app app.js loaded
I/jxcore-log( 7224): 
I/chromium( 7224): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7224): BLE advertisement is supported
I/jxcore-log( 7224): 
I/jxcore-log( 7224): --= Surplus to requirements =--
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ****TEST TOOK:  ms ****
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7224): 
I/art     ( 1041): Explicit concurrent mark sweep GC freed 86816(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.976ms total 173.133ms
D/ChimeraCfgMgr( 2338): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2338): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] request level :IDLE....
W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/AppUp4:CustModeStarterReceiver( 7433): onReceive
D/AppUp4:CustFacade( 7433): Context : android.app.ReceiverRestrictedContext@f4de4fd
D/AppUp4:CustFacade( 7433): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7433): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7433): begin check event
I/AppUp4:CustModeStarterReceiver( 7433): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSActivity( 2130): [ac] getting account id
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3421): DownloadService onCreate
I/LGDMClient( 4343): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/GLSUser ( 2130): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@8334813 on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4343): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4343): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4343): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@2f7daa50 on behalf of 3421
W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3421): DownloadService onStartCommand
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@2d00526f on behalf of 3421
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
D/LgeQuickCoverNLService( 1407): onNotificationPosted
V/DownloadManager( 3421): processing inserted download 9
D/SmartCoverUpdateMonitor( 1407): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1407): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1407): handleNotificationPosted(true)
D/QuickCircle( 1407): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1407): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post do just update job
D/LgeQuickCoverNotificationData( 1407): showAll3
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1407): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  0
V/DownloadManager( 3421): processing inserted download 10
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
W/Kids    ( 2338): [AccountUtils] Account not ready
W/Kids    ( 2338): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2338): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2338): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3421): processing inserted download 18
V/DownloadManager( 3421): processing inserted download 21
D/WeatherAncestor( 7573): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:0
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  1
V/DownloadManager( 3421): processing inserted download 22
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
D/Weather.Utils( 7573): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7573): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7573): 2 : This is isUpdating : false
D/WeatherAncestor( 7573): connectivity changed - connection : true
D/WeatherService( 7573): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@18a93443
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1407): updateNotificationData: count=3
D/ForecastDataCache( 7573): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7573): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7573): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7573): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7573): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:0
V/DownloadManager( 3421): DownloadService onDestroy
D/QuickStatusbarLayout( 1407): Notification difference=198
D/QuickStatusbarLayout( 1407): child = android.widget.LinearLayout{2d2ac05 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.google.com, class = 1, type = 1
D/ChimeraCfgMgr( 2338): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  316): res_queryN name = www.google.com succeed
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
V/FormManager( 7510): There are no updated forms. The schedule will be deleted.
V/FormManager( 7510): Alarm would be updated, because LastCheckTime has been updated.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7433): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7433): onReceive
D/AppUp4:CustFacade( 7433): Context : android.app.ReceiverRestrictedContext@f4de4fd
D/AppUp4:CustFacade( 7433): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7433): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7433): begin check event
I/AppUp4:CustModeStarterReceiver( 7433): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3421): DownloadService onCreate
I/LGDMClient( 4343): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4343): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3421): in removeSpuriousFiles
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@2d2ac05 on behalf of 3421
W/Kids    ( 2338): [AccountUtils] Account not ready
W/Kids    ( 2338): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2338): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2338): 	at java.lang.Thread.run(Thread.java:818)
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4343): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4343): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4343): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): DownloadService onStartCommand
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ResourcesManager( 1407): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1407): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@37d70381 on behalf of 3421
D/LgeQuickCoverNLService( 1407): onNotificationPosted
D/SmartCoverUpdateMonitor( 1407): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1407): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1407): handleNotificationPosted(true)
D/QuickCircle( 1407): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1407): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post do just update job
D/LgeQuickCoverNotificationData( 1407): showAll3
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1407): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  0
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = true
D/PhoneState( 3355): setPdpRejectCasuse : false
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  1
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1abc7368 on behalf of 3421
V/DownloadManager( 3421): processing inserted download 1
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
W/Settings( 7463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
W/ResourcesManager( 1407): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1407): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/DownloadManager( 3421): processing inserted download 16
E/LgeQuickCoverOverlayWindow( 1407): updateNotificationData: count=3
D/QuickStatusbarLayout( 1407): Notification difference=198
D/QuickStatusbarLayout( 1407): child = android.widget.LinearLayout{2d2ac05 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
D/WeatherAncestor( 7573): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:0
V/DownloadManager( 3421): processing inserted download 21
V/DownloadManager( 3421): processing inserted download 22
D/Weather.Utils( 7573): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7573): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7573): 2 : This is isUpdating : false
D/WeatherAncestor( 7573): connectivity changed - connection : true
D/WeatherService( 7573): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@18a93443
V/WifiInternetCheck( 1041): isHttpConnectionAvailable - We got a valid response : 204
D/ForecastDataCache( 7573): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7573): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7573): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7573): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7573): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:0
V/DownloadManager( 3421): DownloadService onDestroy
D/ChimeraCfgMgr( 2338): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7510): There are no updated forms. The schedule will be deleted.
V/FormManager( 7510): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1407): onNotificationPosted
D/SmartCoverUpdateMonitor( 1407): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1407): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1407): handleNotificationPosted(true)
D/QuickCircle( 1407): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1407): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1407): post do just update job
D/LgeQuickCoverNotificationData( 1407): showAll3
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 1,0|com.google.android.gms|1|null|10005
W/Kids    ( 2338): [AccountUtils] Account not ready
W/Kids    ( 2338): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2338): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2338): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2338): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2338): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2338): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1407): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1407): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1407): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1407): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1407): updateNotificationData: count=3
D/QuickStatusbarLayout( 1407): Notification difference=198
D/QuickStatusbarLayout( 1407): child = android.widget.LinearLayout{2d2ac05 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/AndroidRuntime( 7743): 
D/AndroidRuntime( 7743): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7743): CheckJNI is OFF
,D/AndroidRuntime( 7743): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1041): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1041): Killing 7224:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1041): Skipping PackageSetting{7d0caaa com.example.hello/10319} due to missing metadata
,I/WindowState( 1041): WIN DEATH: Window{11ce56bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1041): Client connection lost with reason: 4
D/InputDispatcher( 1041): Window went away: Window{11ce56bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1041):   Force finishing activity ActivityRecord{3ea39ee1 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
,W/ActivityManager( 1041): Spurious death for ProcessRecord{1201c2d4 7224:com.test.thalitest/u0a311}, curProc for 7224: null
,D/SplitWindowPolicy( 1985): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1985): topRunningActivity=ActivityInfo{1ab6020d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1985): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1985): topRunningActivity=ActivityInfo{372d05c2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1041): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1041):   Force finishing activity ActivityRecord{3ea39ee1 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1041): Duplicate finish request for ActivityRecord{3ea39ee1 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2093): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2093): [Launcher.java:903:onResume()]onResume
,I/[LGHome]EVENT( 2093): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
E/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_MrGDBLogger_PackageInfoDetector( 2700): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2056): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/KeyguardModel( 1449): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/InputReader( 1041): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4569): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4569): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4569): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4569): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4569): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4569): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4569): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4569): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4569): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4569): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4569): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4569): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[SystemUI]QSlideListController( 1449): onReceive = android.intent.action.PACKAGE_REMOVED
,D/administrator( 1041): Handling package changes for user 0
,W/GeofencerStateMachine( 1826): Ignoring removeGeofence because network location is disabled.
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,I/[LGHome]LGActivityUtil( 2093): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/ActionManagerService( 1949): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2093): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2093): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1449): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1449): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/ActionManagerService( 1949): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000004)
D/SplitUIManager( 1909): split_name #11 / not available #0
D/SplitUIService( 1909): removed split : 
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
V/SIM_STK ( 1041): Menu title from STK is T-Mobile
V/SIM_STK ( 1041): Menu title from STK is T-Mobile
,D/SplitUIManager( 1909): split_name #11 / not available #0
I/SplitUIService( 1909): split app #11
I/ActivityManager( 1041): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7776 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/BoardContentProvider( 2700): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2093): , create_time: 1430558575574
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2093): , create_time: 1430558575600
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2093): , create_time: 1453384801850
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
D/WallpaperManager( 2093): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1041): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1041): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1041): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1041): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b195030,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/art     ( 4621): Explicit concurrent mark sweep GC freed 16110(915KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 397us total 220.572ms
W/ActivityManager( 1041): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3817): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]EVENT( 2093): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/AppUp4:PreloadHelper( 7433): added Exclude : com.test.thalitest
,I/LockScreenSettings( 7776): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/ActivityManager( 1041): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7795 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1449): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1449): createShortcutInfo...
,D/KeyguardModel( 1449): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.mms: Resource ID #0x0
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
D/KeyguardModel( 1449): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1449): createShortcutInfo...
I/[LGHome]EVENT( 2093): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1449): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1449): createShortcutInfo...
D/KeyguardModel( 1449): handleShortcutListChanged...
I/NotificationService( 1041): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1041): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1041): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1041): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/KeyguardModel( 1449): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1449): createShortcutInfo...
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1449): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1449): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1449): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourcesManager( 7795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7795): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 1041): Explicit concurrent mark sweep GC freed 33139(1907KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.726ms total 322.533ms
I/ActivityManager( 1041): Killing 7052:com.lge.clock/u0a10 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2093): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2093): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,D/AndroidRuntime( 7743): Shutting down VM
,D/KeyguardModel( 1449): handleShortcutListChanged...
W/libprocessgroup( 1041): failed to open /acct/uid_10010/pid_7052/cgroup.procs: No such file or directory
I/Timeline( 1041): Timeline: Activity_windows_visible id: ActivityRecord{29c05b0d u0 com.lge.launcher2/.Launcher t3} time:295635
,I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2093): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2602): onStartCommand(). Type : 8
D/[Concierge]Service( 2602): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2602): Update widget ID : 11
D/[Concierge]WidgetView( 2093): change position of spinner
I/[Concierge]WidgetView( 2093): initWebView(). Time : 1453394882285
D/[Concierge]Service( 2602): onStartCommand(). Type : 0
,I/SystemConfig( 7795): BUILD Country: EU
I/SystemConfig( 7795): BUILD Operator: OPEN
I/[Concierge]WebView( 2093): Return exist ConciergeWebView. Reuse : 225131070
D/[Concierge]WidgetView( 2093): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2093): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@24c62adc
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1041): Killing 6965:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2093): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2093): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 1041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1041): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1041): failed to open /acct/uid_10005/pid_6965/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 2175): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 7463): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/[Concierge]WidgetView( 2093): Widget kill message received. Destory myself. My : 1453394614169, New one : 1453394882285
,D/[Concierge]WidgetView( 2093): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2093): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/SystemConfig( 7795): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7795): existFile = false
I/SystemConfig( 7795): canReadFile = false
,I/SystemConfig( 7795): systemFeature RCS result false
,D/SystemConfig( 7795): refreshRcsSupport() :false
,I/ActivityManager( 1041): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7817 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2093): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2093): Timeline: Activity_idle id: android.os.BinderProxy@1fb9bad6 time:295904
,I/AppConfig( 7817): Total System Memory = 2995761152
,D/SystemHelper( 7817): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1041): Killing 7092:com.google.android.apps.books/u0a54 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 2056): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2056): startLIAService() : Trying to start LIA service ...

```
