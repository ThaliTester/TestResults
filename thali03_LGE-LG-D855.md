#### Test 5497026179923a9_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297794774375; DSPS: 9899129; Offset : -4318038874
,D/AndroidRuntime( 7390): 
D/AndroidRuntime( 7390): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7390): CheckJNI is OFF
D/AndroidRuntime( 7390): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1934): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1ff614e7 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1ff614e7 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7410 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7390): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1845): Display #0 changed.
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{31e87e39 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{2f894c7e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7410): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7410): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7410): Loading: webviewchromium
I/LibraryLoader( 7410): Time to load native libraries: 3 ms (timestamps 120-123)
I/LibraryLoader( 7410): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7410): Binding Chromium to main looper Looper (main, tid 1) {32ba64f3}
,I/LibraryLoader( 7410): Expected native library version number "",actual native library version number ""
I/chromium( 7410): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7410): Initializing chromium process, renderers=0
W/art     ( 7410): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  318): registerClient() client 0xb1427060, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1517f239:true
,W/chromium( 7410): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7410): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7410): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7410): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7410): Build Date: 12/12/14 금
I/Adreno-EGL( 7410): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7410): Remote Branch: 
I/Adreno-EGL( 7410): Local Patches: 
I/Adreno-EGL( 7410): Reconstruct Branch: 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 31002(1827KB) AllocSpace objects, 7(240KB) LOS objects, 33% free, 44MB/66MB, paused 2.311ms total 165.910ms
,W/chromium( 7410): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7410): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7410): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7410): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7410): CordovaWebView is running on device made by: LGE
,W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{27cf7894 u0 com.test.thalitest/.MainActivity t4}
W/art     ( 7410): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7410): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7410): Render dirty regions requested: true
I/OpenGLRenderer( 7410): Initialized EGL, version 1.4
D/OpenGLRenderer( 7410): Enabling debug mode 0
,D/Atlas   ( 7410): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{3ff332eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7410): LgDataFeature() Constructor: none
,D/LgDataFeature( 7410): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2d5338c0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 7410): Timeline: Activity_idle id: android.os.BinderProxy@18c670e3 time:300624
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +703ms (total +797ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{27cf7894 u0 com.test.thalitest/.MainActivity t4} time:300626
,D/JsMessageQueue( 7410): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7410): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7410): 
,I/chromium( 7410): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7410): 
,D/jxcore_app_log( 7410): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435081600
D/JX-Cordova( 7410): jxcore cordova android initializing
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7410): Initializing JXcore engine
W/jxcore-log( 7410): JXcore engine is ready
,W/jxcore-log( 7410): Starting JXcore engine
,W/.test.thalitest( 7410): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8572]" dev="sockfs" ino=8572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7410): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7410): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9575]" dev="sockfs" ino=9575 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7410): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7410): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[35927]" dev="sockfs" ino=35927 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7410): Background sticky concurrent mark sweep GC freed 124655(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.613ms total 111.578ms
,W/jxcore-log( 7410): Platform android
W/jxcore-log( 7410): 
,W/jxcore-log( 7410): Process ARCH arm
W/jxcore-log( 7410): 
I/jxcore-log( 7410): JXcore Cordova bridge is ready!
I/jxcore-log( 7410): 
W/jxcore-log( 7410): JXcore engine is started
,I/Choreographer( 7410): Skipped 130 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 7410): Toggling radios to true
I/jxcore-log( 7410): 
,D/BluetoothAdapter( 7410): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7410, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7410, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1037): disconnect pid=7410, uid=10311, packageName=com.test.thalitest,
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [303,247,001 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7410, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7410): Radios toggled
I/jxcore-log( 7410): 
I/jxcore-log( 7410): My device name is: LGE-LG-D855
I/jxcore-log( 7410): 
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1037): DISCONNECT: returned true
D/Tethering( 1037): InitialState.processMessage what=4
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  314): Clearing all IP addresses on wlan0
V/NativeCrypto( 2141): Read error: ssl=0xaa714800: I/O error during system call, Connection timed out
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7479 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaa714800: I/O error during system call, Broken pipe
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [303,382,165 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1934): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1037): RECONNECT: returned true
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=303406
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=303407
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): Dns fail occured do internet check.
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1037): stop dsqn bin
D/DSQN    ( 1037): try Internet connection check
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=303449  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=303450  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=303456  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/DSQN    ( 1037): ThreadTCPConnectionCheck DNS fail internet is not possible
D/WifiHS20( 1037): hidePasspointNotification off =false
D/DSQN    ( 1037): ThreadInternetCheck internet check NOK 
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1037): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1037): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiDataContinuityService( 1037): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=303462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceExtension( 1934): isInternetCheckAvailable return false
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 7479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7479): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/TelephonyNetworkFactory-1( 1845): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/ResourcesManager( 7479): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7479): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
,W/ResourcesManager( 7479): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7479): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService( 1037): Removing idletimer
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7479): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7479): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7479): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7479): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7479): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7479): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7518 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6819:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6819/cgroup.procs: No such file or directory
I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7518): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7479): LgDataFeature() Constructor: none
D/LgDataFeature( 7479): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7543 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6841:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6841/cgroup.procs: No such file or directory
W/ResourcesManager( 7543): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 7543): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 7543): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7543): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7543): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7543): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7543): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7543): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7543): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 7543): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7543): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7518): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7518): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7518): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7543): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7543): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7543): LgDataFeature() Constructor: none
D/LgDataFeature( 7543): LgDataFeature() Constructor Done, null
V/SoundPool( 7543): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7543): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7543): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7543): doLoad: loading sample sampleID=1
I/QRemote ( 7543): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7543): Start decode
V/MediaPlayer[Native]( 7543): decode(31, 10857164, 17813)
V/MediaPlayerService(  318): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
D/UEI.SmartControl( 6796): QS Service created
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474780, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
D/QRemote ( 7543): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7543): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6796): Service initServices...
D/UEI.SmartControl( 6796): QS start get config
V/LGMDMManager( 7543): Create singleton instance
V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
V/AwesomePlayer(  318): prepareAsync_l() 
V/MediaPlayerService(  318): wait for prepare
V/AwesomePlayer(  318): onPrepareAsyncEvent() 
V/AwesomePlayer(  318): initAudioDecoder() 
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AwesomePlayer(  318): getUseOffload() = 0 
V/OMXCodec(  318): OMXCodec::Create
V/OMXCodec(  318): findMatchingCodecs()
V/OMXCodec(  318): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  318): matchingCodecs.size()=1
V/OMXCodec(  318): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  318): LG Codec Adapter start
V/OMXCodec(  318): OMXCodec Createtor
V/OMXCodec(  318): setComponentRole
V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
V/LGCodecOSAL(  318): Not support LGCodec
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  318): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  318): Could not offload audio decode, try pcm offload
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  318): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  318): init()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  318): allocateBuffers
V/OMXCodec(  318): allocateBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf290 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf470 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb5474780, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb5474780, 1, 0, 0)
V/AudioCache(  318): prepared
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): start
V/AwesomePlayer(  318): play_l() 
V/AwesomePlayer(  318): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  318): createAudioPlayer_l
V/AwesomePlayer(  318): seekAudioIfNecessary_l() 
V/AwesomePlayer(  318): startAudioPlayer_l() 
D/AudioPlayer(  318): start of Playback, useOffload 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799120
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799200
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799600
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf290 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf6a0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb5474780, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab502000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab503000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab504000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab505000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab506000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab507000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab508000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab509000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50a000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50b000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50c000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50d000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50e000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab50f000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab510000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab511000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab512000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab513000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab514000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab515000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab516000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab517000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab518000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab519000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51a000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51b000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51c000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51d000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51e000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab51f000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab520000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab521000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab522000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab523000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab524000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab525000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab526000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab527000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab528000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab529000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52a000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52b000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52c000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52d000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52e000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab52f000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab530000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab531000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab532000, 0xb1006000, 4096)
V/AudioCache(  318): write(0xb1006000, 4096)
V/AudioCache(  318): memcpy(0xab533000, 0xb1006000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb1006000, 280)
V/AudioCache(  318): memcpy(0xab534000, 0xb1006000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb5474780, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb5474780, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  318): Pause Playback at 1068125
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474780, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf6a0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf290 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf2e0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 7543): close(31)
V/SoundPool( 7543): pointer = 0x9ff3e000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9199
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_ENABLE received
I/UEI.SmartControl( 6796): Supports setup maps: true
D/UEI.SmartControl( 6796): QS start statue = true Error code = 0
I/UEI.SmartControl( 6796): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6796): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6796): ### init IR Blaster...
D/serial_port( 6796): Configuring serial port
E/UEI.SmartControl( 6796): UEIBLaster setting for 616
I/UEI.SmartControl( 6796): Setting serial record hearder size = 2
I/UEI.SmartControl( 6796): configuring settings for MAXQ616
I/UEI.SmartControl( 6796): Get version...
D/UEI.SmartControl( 6796): serial port data available: 21
D/UEI.SmartControl( 6796): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6796): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6796): QS saving settings...
D/UEI.SmartControl( 6796): IR Blaster version: 25672567
D/UEI.SmartControl( 6796): serial port data available: 4
W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6796): Services init done
D/UEI.SmartControl( 6796): QS Service init finished
I/UEI.SmartControl( 6796): Device manager: loading config....
D/UEI.SmartControl( 6796): ----------- loading internal config...
D/UEI.SmartControl( 6796): QS Service version name: 2.1.91
D/UEI.SmartControl( 6796): QS Service version code: 201091
D/UEI.SmartControl( 6796): Service requested: Control
E/UEI.SmartControl( 6796): Loading SETTINGS...
D/UEI.SmartControl( 6796): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6796): Internal service binding...
I/QRemote ( 7543): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6796): ------ IControl API: 11
D/UEI.SmartControl( 6796): File observer start...
E/UEI.SmartControl( 6796): IR Port is disabled: false
D/UEI.SmartControl( 6796): Starting file observer...
D/UEI.SmartControl( 6796): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6796): Registering callback...
I/UEI.SmartControl( 6796): ------ IControl API: 19
I/UEI.SmartControl( 6796): Registering Services Ready callback...
I/UEI.SmartControl( 6796): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6796): -----service ready thread exits
I/QRemote ( 7543): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7543): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7543): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7543): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7543): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6796): ------ IControl API: 8
D/QRemote ( 7543): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7543): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7543): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7543): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7543): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7543): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7543): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7543): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7543): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7543): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452509655839]
D/QRemote ( 7543): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6949:com.google.android.apps.books/u0a54 (adj 15): empty #17
D/QRemote ( 7543): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6949/cgroup.procs: No such file or directory
V/QRemote ( 7543): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7543): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7543): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2700): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=305515  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=305530  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
,D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
,D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2700): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=305615  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=305615  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=305616
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=305616
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=305616
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=305616
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=305616
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=305617  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=305620  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 2700): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=305629  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=305629  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=305630
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=305630
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305671  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305671  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305672  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305672  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305673  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305673  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
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
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7479): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7479): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7479): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7479): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7479): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7479): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7479): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a6c5e86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a6c5e86 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1934): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{,20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7605): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7605): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7605): DSQN ssw
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7543): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7543): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7543): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7543): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7518): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7518): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7479): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 7479): MCCMNC not supported: null
D/QRemote ( 7543): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7543): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7543): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7543): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7543): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 10:54:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452509656913], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452509656895]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
,D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7611): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7611): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7611): version 5.5.6 starting
,E/dhcpcd  ( 7611): get_duid: m
D/dhcpcd  ( 7611): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7611): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7611): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7611): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7611): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7611): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7611): wlan0: sending REQUEST (xid 0x324911e1), next in 4.10 seconds
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=743697833, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{148fbaa8 type 2 when 306264 com.google.android.gms} when 306264
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=743697833 [*alarm*], flags=0x0
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/Tethering( 1037): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5470): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5470): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7277): onReceive
,D/AppUp4:CustFacade( 7277): Context : android.app.ReceiverRestrictedContext@38478b62
D/AppUp4:CustFacade( 7277): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7277): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7277): begin check event
I/AppUp4:CustModeStarterReceiver( 7277): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7277): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7277): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7277): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7277): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3402): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3402): DownloadService onCreate
D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3402): in removeSpuriousFiles
I/LGDMClient( 4310): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@48753d4 on behalf of 3402
,I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3402): in trimDatabase
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@bf30072 on behalf of 3402
D/GCM     ( 2141): Connected
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7644 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3402): DownloadService onStartCommand
V/DownloadManager( 3402): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@14efd940 on behalf of 3402
V/DownloadManager( 3402): processing inserted download 1
V/DownloadManager( 3402): processing inserted download 4
E/LGDMClient( 4310): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3402): processing inserted download 7
D/LGDMClient( 4310): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4310): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3402): processing inserted download 8
,V/DownloadManager( 3402): processing inserted download 9
D/GCM     ( 2141): Message class com.google.f.a.a.p
V/DownloadManager( 3402): processing inserted download 10
,V/DownloadManager( 3402): processing inserted download 16
V/DownloadManager( 3402): processing inserted download 17
V/DownloadManager( 3402): processing inserted download 18
V/DownloadManager( 3402): processing inserted download 21
V/DownloadManager( 3402): DownloadService onDestroy
,W/ResourcesManager( 7644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7644): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7644): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7644): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7644): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{6a6fff9 type 2 when 306717 android} when 306717
D/LGEmail ( 7644): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7644): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7644): LgDataFeature() Constructor: none
D/LgDataFeature( 7644): LgDataFeature() Constructor Done, null
,D/eas_req ( 7644): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7668 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7644): JNI_OnLoad()
I/HubEmail( 7644): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7644): registerNatives()
I/HubEmail( 7644): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7644): registerNativeMethods()
I/HubEmail( 7644): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7644): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6620:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
,D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524295
W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6620/cgroup.procs: No such file or directory
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3358): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3358): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7697 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7611): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,I/dhcpcd  ( 7611): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7611): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7611): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7611): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7611): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7611): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7611): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7611): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/FormManager( 7668): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7668): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7730 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 7132:com.google.android.configupdater/u0a59 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10059/pid_7132/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 7071:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_7071/cgroup.procs: No such file or directory
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7759 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 7244:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10072/pid_7244/cgroup.procs: No such file or directory
,I/art     ( 7759): Almond Protected OAT
,D/WeatherApplication( 7759): removeAccount
D/WeatherApplication( 7759): Account.length = 0
E/WeatherApplication( 7759): OPERATOR:OPEN
D/WeatherAncestor( 7759): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:18
,D/Weather.Utils( 7759): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7759): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7759): 2 : This is isUpdating : false
D/WeatherAncestor( 7759): connectivity changed - connection : true
D/WeatherService( 7759): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7759): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7759): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7759): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7759): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7759): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:18
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7778 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 7301:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_7301/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7778): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7778): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7778): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7778): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7778): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7778): Loading: webviewchromium
I/LibraryLoader( 7778): Time to load native libraries: 4 ms (timestamps 8346-8350)
I/LibraryLoader( 7778): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7778): Binding Chromium to main looper Looper (main, tid 1) {1cb9b5f8}
I/LibraryLoader( 7778): Expected native library version number "",actual native library version number ""
I/chromium( 7778): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7778): Initializing chromium process, renderers=0
W/art     ( 7778): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7778): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7778): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7778): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667,
V/AudioPolicyService(  318): registerClient() client 0xb1427180, uid 10093
W/AudioManagerAndroid( 7778): Requires BLUETOOTH permission
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/Adreno-EGL( 7778): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7778): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7778): Build Date: 12/12/14 금
I/Adreno-EGL( 7778): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7778): Remote Branch: 
I/Adreno-EGL( 7778): Local Patches: 
I/Adreno-EGL( 7778): Reconstruct Branch: 
I/NSApplication( 7778): Starting up...
,I/ActivityManager( 1037): Killing 7329:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_7329/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2378): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2378): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3810): Disconnected process message: 10, size: 0
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1934): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1934): Battery Level Remaining: 100%
D/LEDHandler( 1934): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
,I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7277): onReceive
,D/AppUp4:CustFacade( 7277): Context : android.app.ReceiverRestrictedContext@38478b62
D/AppUp4:CustFacade( 7277): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7277): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7277): begin check event
I/AppUp4:CustModeStarterReceiver( 7277): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4310): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3402): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4310): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3402): DownloadService onCreate
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,I/DownloadManager( 3402): in removeSpuriousFiles
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@2d6cb1be on behalf of 3402
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3402): in trimDatabase
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@2c63c21f on behalf of 3402
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3402): DownloadService onStartCommand
V/DownloadManager( 3402): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@153e2bca on behalf of 3402
V/DownloadManager( 3402): processing inserted download 1
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3402): processing inserted download 4
E/LGDMClient( 4310): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3402): processing inserted download 7
V/DownloadManager( 3402): processing inserted download 8
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3402): processing inserted download 9
V/DownloadManager( 3402): processing inserted download 10
V/DownloadManager( 3402): processing inserted download 16
D/Tethering( 1037): MasterInitialState.processMessage what=3
V/DownloadManager( 3402): processing inserted download 17
,V/DownloadManager( 3402): processing inserted download 18
V/DownloadManager( 3402): processing inserted download 21
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/NetworkMonitor( 5470): type=WIFI subType= reason=null isConnected=true
D/LGDMClient( 4310): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3358): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3358): networkInfo.isConnected() = false
V/DownloadManager( 3402): DownloadService onDestroy
D/WeatherAncestor( 7759): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:19
D/Weather.Utils( 7759): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7759): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7759): 2 : This is isUpdating : false
D/WeatherAncestor( 7759): connectivity changed - connection : true
D/WeatherService( 7759): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@348c5d4f
D/ForecastDataCache( 7759): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7759): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7759): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7759): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7759): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:19
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/Kids    ( 2378): [AccountUtils] Account not ready
W/Kids    ( 2378): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2378): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2378): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7851 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,I/art     (  341): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 15.464ms
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
V/FormManager( 7668): There are no updated forms. The schedule will be deleted.
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 274us total 13.019ms
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.157ms
V/FormManager( 7668): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2378): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GCM     ( 2378): Message from null null
,E/GCM     ( 2378): Dropping message from null
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7277): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7277): onReceive
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AppUp4:CustFacade( 7277): Context : android.app.ReceiverRestrictedContext@38478b62
D/AppUp4:CustFacade( 7277): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7277): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7277): begin check event
I/AppUp4:CustModeStarterReceiver( 7277): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3402): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4310): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/ReaderUtils( 7851): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2378): [AccountUtils] Account not ready
W/Kids    ( 2378): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2378): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2378): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
,D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3402): DownloadService onCreate
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
I/LGDMClient( 4310): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4310): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3402): in removeSpuriousFiles
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@3a879058 on behalf of 3402
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3402): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/LGDMClient( 4310): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4310): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4310): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3402): in trimDatabase
V/DownloadManager( 3402): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@29fb3a96 on behalf of 3402
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3402): DownloadService onStartCommand
V/DownloadManager( 3402): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3402): created cursor android.database.sqlite.SQLiteCursor@2c115a04 on behalf of 3402
V/DownloadManager( 3402): processing inserted download 1
V/DownloadManager( 3402): processing inserted download 4
V/DownloadManager( 3402): processing inserted download 7
V/DownloadManager( 3402): processing inserted download 8
V/DownloadManager( 3402): processing inserted download 9
V/DownloadManager( 3402): processing inserted download 10
V/DownloadManager( 3402): processing inserted download 16
V/DownloadManager( 3402): processing inserted download 17
V/DownloadManager( 3402): processing inserted download 18
V/DownloadManager( 3402): processing inserted download 21
,V/DownloadManager( 3402): DownloadService onDestroy
W/GAV2    ( 7851): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7851): Created application version: 3.2.35 (30235)
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 89705(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.532ms total 115.464ms
I/LgeMiscReceiver( 3358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3358): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3358): networkInfo.isConnected() = true
D/PhoneState( 3358): setPdpRejectCasuse : false
,V/FormManager( 7668): There are no updated forms. The schedule will be deleted.
D/WeatherAncestor( 7759): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:20
D/Weather.Utils( 7759): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7759): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7759): 2 : This is isUpdating : false
D/WeatherAncestor( 7759): connectivity changed - connection : true
D/WeatherService( 7759): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@348c5d4f
D/ForecastDataCache( 7759): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7759): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7759): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 7759): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7759): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:54:20
,V/FormManager( 7668): Alarm would be updated, because LastCheckTime has been updated.
,I/ThermalEngine(  331): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3175): Thermal-Lib-Client: Client request sent
I/BooksSync( 7851): Starting books sync
,D/ChimeraCfgMgr( 2378): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2378): [AccountUtils] Account not ready
W/Kids    ( 2378): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2378): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2378): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2378): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2378): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2378): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/BooksSync( 7851): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,E/BooksAccountManager( 7851): Authentication error
E/BooksAccountManager( 7851): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7851): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7851): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7851): null auth token
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7851): Error response from books API: {
W/ApiaryClient( 7851):  "error": {
W/ApiaryClient( 7851):   "errors": [
W/ApiaryClient( 7851):    {
W/ApiaryClient( 7851):     "domain": "global",
W/ApiaryClient( 7851):     "reason": "required",
W/ApiaryClient( 7851):     "message": "Login Required",
W/ApiaryClient( 7851):     "locationType": "header",
W/ApiaryClient( 7851):     "location": "Authorization"
W/ApiaryClient( 7851):    }
W/ApiaryClient( 7851):   ],
W/ApiaryClient( 7851):   "code": 401,
W/ApiaryClient( 7851):   "message": "Login Required"
W/ApiaryClient( 7851):  }
W/ApiaryClient( 7851): }
W/ApiaryClient( 7851): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7851): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7199982582363175842&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7851): Headers:
W/ApiaryClient( 7851): accept-encoding: [gzip]
W/ApiaryClient( 7851): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7851): gdata-version: 2
,D/UEI.SmartControl( 6796): Internal timer expired: 4
D/UEI.SmartControl( 6796): unbind internal service
,D/serial_port( 6796): close(fd = 24)
,I/UEI.SmartControl( 6796): Serial port is closed.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7410): Test app app.js loaded
I/jxcore-log( 7410): 
,I/chromium( 7410): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 7410): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ThermalEngine(  331): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3175): Thermal-Lib-Client: Client request sent
I/jxcore-log( 7410): --= Surplus to requirements =--
I/jxcore-log( 7410): 
I/jxcore-log( 7410): ****TEST TOOK:  ms ****
I/jxcore-log( 7410): 
I/jxcore-log( 7410): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7410): 
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7851): Authentication error
E/BooksAccountManager( 7851): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7851): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7851): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7851): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7851): Error response from books API: {
W/ApiaryClient( 7851):  "error": {
W/ApiaryClient( 7851):   "errors": [
W/ApiaryClient( 7851):    {
W/ApiaryClient( 7851):     "domain": "global",
W/ApiaryClient( 7851):     "reason": "required",
W/ApiaryClient( 7851):     "message": "Login Required",
W/ApiaryClient( 7851):     "locationType": "header",
W/ApiaryClient( 7851):     "location": "Authorization"
W/ApiaryClient( 7851):    }
W/ApiaryClient( 7851):   ],
W/ApiaryClient( 7851):   "code": 401,
W/ApiaryClient( 7851):   "message": "Login Required"
W/ApiaryClient( 7851):  }
W/ApiaryClient( 7851): }
W/ApiaryClient( 7851): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7851): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7199982582363175842&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7851): Headers:
W/ApiaryClient( 7851): accept-encoding: [gzip]
W/ApiaryClient( 7851): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7851): gdata-version: 2
,D/AndroidRuntime( 7920): 
D/AndroidRuntime( 7920): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7920): CheckJNI is OFF
,D/AndroidRuntime( 7920): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 7410:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1037): Skipping PackageSetting{32105041 com.example.hello/10319} due to missing metadata
,I/WindowState( 1037): WIN DEATH: Window{3ff332eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{3ff332eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{27cf7894 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
W/ActivityManager( 1037): Spurious death for ProcessRecord{67a343b 7410:com.test.thalitest/u0a311}, curProc for 7410: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{27cf7894 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{27cf7894 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2026): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{3a3825df co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{eec422c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2026): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2026): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 1989): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3734): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1810): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4535): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4535): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4535): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4535): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4535): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4535): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4535): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4535): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4535): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4535): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4535): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4535): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4580): Explicit concurrent mark sweep GC freed 25434(1466KB) AllocSpace objects, 4(76KB) LOS objects, 34% free, 30MB/46MB, paused 618us total 72.197ms
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,I/[LGHome]LGActivityUtil( 2026): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/PostponalbeReceiver( 6586): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/ActionManagerService( 1898): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000003)
D/administrator( 1037): Handling package changes for user 0
,I/[LGHome]EVENT( 2026): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2026): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1467): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1898): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
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
I/GBoardWebViewUtils( 2026): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2026): , create_time: 1452175675684
I/GBoardWebViewUtils( 2026): , expire_time: 0
I/GBoardWebViewUtils( 2026): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2026): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2026): , display: false
I/GBoardWebViewUtils( 2026): , animation: false }
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/WallpaperManager( 2026): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1467): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2d5338c0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1862): split_name #11 / not available #0
,D/SplitUIService( 1862): removed split : 
I/[LGHome]EVENT( 2026): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2026): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/SplitUIManager( 1862): split_name #11 / not available #0
I/SplitUIService( 1862): split app #11
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
I/[LGHome]EVENT( 2026): [Launcher.java:5349:onStop()]onStop
I/art     ( 1037): Explicit concurrent mark sweep GC freed 22134(1447KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.184ms total 244.512ms
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
D/AppUp4:PreloadHelper( 7277): added Exclude : com.test.thalitest
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7961 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/PhoneStatusBar( 1467): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1467): handleShortcutListChanged...
,D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/KeyguardModel( 1467): handleShortcutListChanged...
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{4a40859 u0 com.lge.launcher2/.Launcher t3} time:311908
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2026): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2026): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LgeQuickCoverNLService( 1417): onNotificationPosted
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
,E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 7961): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2026): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2611): onStartCommand(). Type : 8
D/[Concierge]Service( 2611): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
E/BooksAccountManager( 7851): Authentication error
E/BooksAccountManager( 7851): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7851): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7851): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7851): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7851): null auth token
D/[Concierge]Service( 2611): Update widget ID : 11
D/[Concierge]WidgetView( 2026): change position of spinner
W/ResourcesManager( 7961): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7961): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/[Concierge]Service( 2611): onStartCommand(). Type : 0
W/ResourcesManager( 7961): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7961): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2026): initWebView(). Time : 1452509662987
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35c375b1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 7920): Shutting down VM
,I/[Concierge]WebView( 2026): Return exist ConciergeWebView. Reuse : 364383841
D/[Concierge]WidgetView( 2026): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2026): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3ca686f6
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2026): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2026): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2026): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/[Concierge]WidgetView( 2026): Widget kill message received. Destory myself. My : 1452509378607, New one : 1452509662987
D/[Concierge]WidgetView( 2026): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2026): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/SystemConfig( 7961): BUILD Country: EU
,I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7961): BUILD Operator: OPEN
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2026): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ApiaryClient( 7851): Error response from books API: {
W/ApiaryClient( 7851):  "error": {
W/ApiaryClient( 7851):   "errors": [
W/ApiaryClient( 7851):    {
W/ApiaryClient( 7851):     "domain": "global",
W/ApiaryClient( 7851):     "reason": "required",
W/ApiaryClient( 7851):     "message": "Login Required",
W/ApiaryClient( 7851):     "locationType": "header",
W/ApiaryClient( 7851):     "location": "Authorization"
W/ApiaryClient( 7851):    }
W/ApiaryClient( 7851):   ],
W/ApiaryClient( 7851):   "code": 401,
W/ApiaryClient( 7851):   "message": "Login Required"
W/ApiaryClient( 7851):  }
W/ApiaryClient( 7851): }
W/ApiaryClient( 7851): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7851): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7199982582363175842&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7851): Headers:
W/ApiaryClient( 7851): accept-encoding: [gzip]
W/ApiaryClient( 7851): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7851): gdata-version: 2
I/ThermalEngine(  331): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3175): Thermal-Lib-Client: Client request sent
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1037): Killing 6241:com.android.vending/u0a44 (adj 15): empty #17
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2026): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2026): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2026): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2026): Timeline: Activity_idle id: android.os.BinderProxy@3780f7a0 time:312064
,W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6241/cgroup.procs: No such file or directory
,I/SystemConfig( 7961): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7961): existFile = false
I/SystemConfig( 7961): canReadFile = false
I/SystemConfig( 7961): systemFeature RCS result false
D/SystemConfig( 7961): refreshRcsSupport() :false
I/PackageChangeReceiver( 7644): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2325): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7984 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7984): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/chromium( 2026): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/AppConfig( 7984): Total System Memory = 2995761152
,D/SystemHelper( 7984): region [EU], country [EU], operator [OPEN], sub-operator []
I/GBoardtInterface( 2026): onReloaded()
,I/GBoardWebViewClient( 2026): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1898): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1898): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3734): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onSettingEvent() : GBoard On - add scheduler - 0
,V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2026): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,D/GBoardWebViewUtils( 2026): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/ActivityManager( 1037): Killing 6867:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 1989): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 1989): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6867/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 1989): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6586): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8009 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
