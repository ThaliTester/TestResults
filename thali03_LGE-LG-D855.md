#### Test 573480789efee08_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257746155151; DSPS: 8586934; Offset : -4319184047
,D/AndroidRuntime( 7149): 
D/AndroidRuntime( 7149): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7149): CheckJNI is OFF
D/AndroidRuntime( 7149): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1937): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{206fed55 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{206fed55 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7164 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7149): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1848): Display #0 changed.
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{2880c0d8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{38a41c31 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7164): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7164): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7164): Loading: webviewchromium
I/LibraryLoader( 7164): Time to load native libraries: 3 ms (timestamps 2557-2560)
,I/LibraryLoader( 7164): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7164): Binding Chromium to main looper Looper (main, tid 1) {38286688}
,I/LibraryLoader( 7164): Expected native library version number "",actual native library version number ""
,I/chromium( 7164): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7164): Initializing chromium process, renderers=0
W/art     ( 7164): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  314): registerClient() client 0xb14fd920, uid 10311
,D/BluetoothManagerService( 1039): Message: 20
W/chromium( 7164): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7164): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7164): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7164): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7164): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7164): Build Date: 12/12/14 금
I/Adreno-EGL( 7164): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
,I/Adreno-EGL( 7164): Remote Branch: 
I/Adreno-EGL( 7164): Local Patches: 
I/Adreno-EGL( 7164): Reconstruct Branch: 
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 26699(1181KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.689ms total 117.646ms
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30ceee6:true
,W/chromium( 7164): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7164): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7164): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7164): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7164): CordovaWebView is running on device made by: LGE
,W/art     ( 7164): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7164): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7164): Render dirty regions requested: true
I/OpenGLRenderer( 7164): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7164): Enabling debug mode 0
W/ActivityManager( 1039): Activity pause timeout for ActivityRecord{eb6236a u0 com.test.thalitest/.MainActivity t4}
,D/Atlas   ( 7164): Validating map...
D/SplitWindow( 1039): check instance of lgWin Window{37009f79 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7164): LgDataFeature() Constructor: none
,D/LgDataFeature( 7164): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7690072,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +638ms (total +718ms)
I/Timeline( 7164): Timeline: Activity_idle id: android.os.BinderProxy@190681b8 time:272999
,I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{eb6236a u0 com.test.thalitest/.MainActivity t4} time:273001
I/chromium( 7164): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7164): 
,D/JsMessageQueue( 7164): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7164): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7164): 
,D/jxcore_app_log( 7164): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434872064
,I/chromium( 7164): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7164): Initializing JXcore engine
W/jxcore-log( 7164): JXcore engine is ready
W/Thread-838( 7237): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6094]" dev="sockfs" ino=6094 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-838( 7237): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-838( 7237): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7823]" dev="sockfs" ino=7823 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-838( 7237): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-838( 7237): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33336]" dev="sockfs" ino=33336 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7164): Background sticky concurrent mark sweep GC freed 134297(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.749ms total 172.584ms
W/jxcore-log( 7164): Starting JXcore engine
W/jxcore-log( 7164): Platform android
W/jxcore-log( 7164): 
W/jxcore-log( 7164): Process ARCH arm
W/jxcore-log( 7164): 
I/jxcore-log( 7164): JXcore Cordova bridge is ready!
I/jxcore-log( 7164): 
W/jxcore-log( 7164): JXcore engine is started
I/jxcore-log( 7164): Toggling radios to true
I/jxcore-log( 7164): 
D/BluetoothAdapter( 7164): enable(): BT is already enabled..!
D/WifiService( 1039): New client listening to asynchronous messages
D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=7164, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=7164, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=7164, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1039): reconnect pid=7164, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1039): [276,361,726 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
I/jxcore-log( 7164): Radios toggled
I/jxcore-log( 7164): 
,I/jxcore-log( 7164): My device name is: LGE-LG-D855
I/jxcore-log( 7164): 
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1039): InitialState.processMessage what=4
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/DhcpStateMachine( 1039): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  310): Clearing all IP addresses on wlan0
V/NativeCrypto( 2067): Read error: ssl=0xaf499a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2067): SSL shutdown failed: ssl=0xaf499a00: I/O error during system call, Broken pipe
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7247 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): Dns fail occured do internet check.
,D/DSQN    ( 1039): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1039): try Internet connection check
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): Dns timeout INTERNET_CHECK already in progress ignore!
D/DSQN    ( 1039): ThreadTCPConnectionCheck DNS fail internet is not possible
,I/art     (  344): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 270us total 25.536ms
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/DSQN    ( 1039): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1039): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1039): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/WifiDataContinuityService( 1039): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceExtension( 1937): isInternetCheckAvailable return false
,I/art     (  344): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 257us total 13.528ms
E/WifiStateMachine( 1039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1039):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1039): [276,509,009 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1039): hidePasspointNotification off =false
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 221us total 10.676ms
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=276521
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=276521
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=276532  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=276533  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1039): hidePasspointNotification off =false
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=276537  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=276542  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_R,ESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524292
D/NetworkManagementService( 1039): Removing idletimer
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1039): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1848): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1848):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7247): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7247): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7247): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7247): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7247): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7247): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-150ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6586:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_6586/cgroup.procs: No such file or directory
,I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7247): LgDataFeature() Constructor: none
,D/LgDataFeature( 7247): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7311 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1039): Killing 6711:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10008/pid_6711/cgroup.procs: No such file or directory
,W/ResourcesManager( 7311): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7311): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7311): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7311): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7311): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7311): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7311): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7311): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7311): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7311): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7311): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7311): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7311): LgDataFeature() Constructor: none
D/LgDataFeature( 7311): LgDataFeature() Constructor Done, null
,V/SoundPool( 7311): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7311): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7311): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7311): doLoad: loading sample sampleID=1
I/QRemote ( 7311): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6919): QS Service created
D/QRemote ( 7311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7311): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/SoundPool( 7311): Start decode
V/MediaPlayer[Native]( 7311): decode(31, 10857164, 17813)
,V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
,V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6919): Service initServices...
,D/UEI.SmartControl( 6919): QS start get config
V/LGMDMManager( 7311): Create singleton instance
V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
V/AwesomePlayer(  314): initAudioDecoder() 
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AwesomePlayer(  314): getUseOffload() = 0 
V/OMXCodec(  314): OMXCodec::Create
V/OMXCodec(  314): findMatchingCodecs()
V/OMXCodec(  314): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  314): matchingCodecs.size()=1
V/OMXCodec(  314): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMSG
V/LGCodecOSAL(  314): Not support LGCodec
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  314): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  314): Could not offload audio decode, try pcm offload
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf60 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb5474740, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb5474740, 1, 0, 0)
V/AudioCache(  314): prepared
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): start
V/AwesomePlayer(  314): play_l() 
V/AwesomePlayer(  314): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  314): createAudioPlayer_l
V/AwesomePlayer(  314): seekAudioIfNecessary_l() 
V/AwesomePlayer(  314): startAudioPlayer_l() 
D/AudioPlayer(  314): start of Playback, useOffload 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTI,NGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797664
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb5474740, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab602000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab603000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab604000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab605000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab606000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab607000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab608000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab609000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60a000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60b000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60c000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60d000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60e000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab60f000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab610000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab611000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab612000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab613000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab614000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab615000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab616000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab617000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab618000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab619000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61a000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61b000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61c000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61d000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61e000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab61f000, 0xb57f1000, 4096)
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab620000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab621000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab622000, 0xb57f1000, 4096)
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab623000, 0xb57f1000, 4096)
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3334
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab624000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab625000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab626000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab627000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab628000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab629000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62a000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62b000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62c000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62d000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62e000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab62f000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab630000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab631000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab632000, 0xb57f1000, 4096)
V/AudioCache(  314): write(0xb57f1000, 4096)
V/AudioCache(  314): memcpy(0xab633000, 0xb57f1000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb57f1000, 280)
V/AudioCache(  314): memcpy(0xab634000, 0xb57f1000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb5474740, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb5474740, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
,D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  314): AudioPlayer releasing audio source
D/AudioPlayer(  314): AudioPlayer done releasing audio source
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): ~AwesomePlayer call
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/SoundPool( 7311): close(31)
V/SoundPool( 7311): pointer = 0x9ff26000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6919): Supports setup maps: true
D/UEI.SmartControl( 6919): QS start statue = true Error code = 0
I/UEI.SmartControl( 6919): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6919): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6919): ### init IR Blaster...
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277747595263; DSPS: 9242341; Offset : -4319177766
,D/serial_port( 6919): Configuring serial port
E/UEI.SmartControl( 6919): UEIBLaster setting for 616
,I/UEI.SmartControl( 6919): Setting serial record hearder size = 2
,I/UEI.SmartControl( 6919): configuring settings for MAXQ616
I/UEI.SmartControl( 6919): Get version...
D/UEI.SmartControl( 6919): serial port data available: 21
,D/UEI.SmartControl( 6919): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6919): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6919): QS saving settings...
D/UEI.SmartControl( 6919): IR Blaster version: 25672567
D/UEI.SmartControl( 6919): serial port data available: 4
,I/UEI.SmartControl( 6919): Device manager: loading config....
,D/UEI.SmartControl( 6919): ----------- loading internal config...
W/ContextImpl( 6919): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6919): Services init done
D/UEI.SmartControl( 6919): QS Service init finished
D/UEI.SmartControl( 6919): QS Service version name: 2.1.91
D/UEI.SmartControl( 6919): QS Service version code: 201091
D/UEI.SmartControl( 6919): Service requested: Control
E/UEI.SmartControl( 6919): Loading SETTINGS...
,D/UEI.SmartControl( 6919): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6919): Internal service binding...
I/QRemote ( 7311): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6919): ------ IControl API: 11
D/UEI.SmartControl( 6919): File observer start...
E/UEI.SmartControl( 6919): IR Port is disabled: false
D/UEI.SmartControl( 6919): Starting file observer...
I/UEI.SmartControl( 6919): Registering callback...
D/UEI.SmartControl( 6919): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6919): ------ IControl API: 19
I/UEI.SmartControl( 6919): Registering Services Ready callback...
I/UEI.SmartControl( 6919): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6919): -----service ready thread exits
I/QRemote ( 7311): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7311): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7311): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7311): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7311): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6919): ------ IControl API: 8
D/QRemote ( 7311): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7311): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7311): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7311): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7311): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7311): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7311): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7311): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7311): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453981793596]
,D/QRemote ( 7311): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1039): Killing 6737:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7311): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6737/cgroup.procs: No such file or directory
,V/QRemote ( 7311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2700): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=278580  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=278595  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2700): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=278690  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=278690  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=278691
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=278691
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7247): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7247): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7247): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=278692
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=278692
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=278692
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7247): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7247): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7247): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7247): [AUTORUN] setTetherStatus() : status=false
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5928): type=WIFI subType= reason=null isConnected=false
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1039): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5928): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7374 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7374): onCreate
W/AppUp4:DB( 7374):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7374):  setFingerPrint start
I/AppUp4:DB( 7374):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7374):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7374):  SDK version = 21
I/AppUp4:DB( 7374):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7374): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7374): onReceive
D/LgDataFeature( 7374): LgDataFeature() Constructor: none
D/LgDataFeature( 7374): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7374): Context : android.app.ReceiverRestrictedContext@1c2bf446
D/AppUp4:CustFacade( 7374): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7374): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7374): begin check event
I/AppUp4:CustModeStarterReceiver( 7374): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7374): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7374): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7374): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7374): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 6757:com.android.contacts/u0a19 (adj 15): empty #17
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_6757/cgroup.procs: No such file or directory
,W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 6781): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7409 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6781): JNI_OnLoad()
I/HubEmail( 6781): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6781): registerNatives()
I/HubEmail( 6781): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6781): registerNativeMethods()
I/HubEmail( 6781): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6781): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3369): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3369): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3369): networkInfo.isConnected() = false
I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7432 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7409): Network not available. Please check & try again.
V/FormManager( 7409): Network unavailable.
V/FormManager( 7409): Network unavailable.
,I/ActivityManager( 1039): Killing 6806:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_6806/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7456 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6827:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6827/cgroup.procs: No such file or directory
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{24f0cfa3 type 0 when 1453981792429 android} when 1453981792429
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{14de42a0 type 2 when 280479 com.google.android.gms} when 280479
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7474 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6873:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_6873/cgroup.procs: No such file or directory
,I/art     ( 7474): Almond Protected OAT
,I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7164): 
D/WeatherApplication( 7474): removeAccount
,D/WeatherApplication( 7474): Account.length = 0
E/WeatherApplication( 7474): OPERATOR:OPEN
D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:49:56
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
D/WeatherAncestor( 7474): connectivity changed - connection : true
,D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:49:56
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7495 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6939:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6939/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7495): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7495): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7495): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7495): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7164): 
,I/WebViewFactory( 7495): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7495): Loading: webviewchromium
I/LibraryLoader( 7495): Time to load native libraries: 4 ms (timestamps 1472-1476)
I/LibraryLoader( 7495): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7495): Binding Chromium to main looper Looper (main, tid 1) {1af49393}
,I/LibraryLoader( 7495): Expected native library version number "",actual native library version number ""
I/chromium( 7495): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7495): Initializing chromium process, renderers=0
,W/art     ( 7495): Attempt to remove local handle scope entry from IRT, ignoring
I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7164): 
V/AudioPolicyService(  314): registerClient() client 0xb14fd120, uid 10093
W/chromium( 7495): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 7495): Requires BLUETOOTH permission
I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7164): 
I/chromium( 7495): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7495): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,E/WifiStateMachine( 1039):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/Adreno-EGL( 7495): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7495): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7495): Build Date: 12/12/14 금
I/Adreno-EGL( 7495): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7495): Remote Branch: 
I/Adreno-EGL( 7495): Local Patches: 
I/Adreno-EGL( 7495): Reconstruct Branch: 
,I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7164): 
,I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7164): 
,I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7164): 
I/jxcore-log( 7164): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7164): 
I/NSApplication( 7495): Starting up...
,I/ActivityManager( 1039): Killing 6080:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281671  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2700): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_6080/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281725  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281728  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281728  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281729
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281729
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1039): Got NetworkAgent Messenger
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1039): NetworkAgent connected
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
,I/iu.Environment( 2350): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1039): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
,E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281785  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281785  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281786  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281788  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281788  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281788  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
I/iu.UploadsManager( 2350): num queued entries: 0
I/iu.UploadsManager( 2350): num updated entries: 0
I/iu.SyncManager( 2350): NEXT; no task
,D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7374): onReceive
,D/AppUp4:CustFacade( 7374): Context : android.app.ReceiverRestrictedContext@1c2bf446
D/AppUp4:CustFacade( 7374): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7374): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7374): begin check event
I/AppUp4:CustModeStarterReceiver( 7374): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@111eaa32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@111eaa32 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1039): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
,D/eas_req ( 6781): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): ignoring duplicate network state non-change
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1039): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings( 6781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 1
E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
E/Netd    (  310): netlink response contains error (File exists)
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1039): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1848): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1848):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
I/LgeMiscReceiver( 3369): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3369): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3369): networkInfo.isConnected() = false
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE,
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
W/dsqn    ( 7570): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7570): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7570): DSQN ssw
W/FormManager( 7409): Network not available. Please check & try again.
,D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:49:57
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
D/WeatherAncestor( 7474): connectivity changed - connection : true
D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@33216334
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:49:57
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
,D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.Environment( 2350): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2350): num queued entries: 0
I/iu.UploadsManager( 2350): num updated entries: 0
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 2350): NEXT; no task
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
E/WifiStateMachine( 1039):  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:217702] from screen [on:0 period:-2012115662]
E/WifiStateMachine( 1039):  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2012115662]
E/WifiStateMachine( 1039): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-127
D/WifiNative-wlan0( 1039): doBoolean: SCAN TYPE=ONLY
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1039): SCAN TYPE=ONLY: returned true
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7578): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7578): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7578): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7578): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/dhcpcd  ( 7578): version 5.5.6 starting
E/dhcpcd  ( 7578): get_duid: m
D/dhcpcd  ( 7578): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7578): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 1422): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1422): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1422): onNotificationPosted
D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/SmartCoverUpdateMonitor( 1422): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1422): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1422): handleNotificationPosted(true)
D/QuickCircle( 1422): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1422): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1422): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1422): post do just update job
D/LgeQuickCoverNotificationData( 1422): showAll3
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1422): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ResourcesManager( 1422): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1422): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  2
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1422): updateNotificationData: count=3
D/QuickStatusbarLayout( 1422): Notification difference=198
,D/QuickStatusbarLayout( 1422): child = android.widget.LinearLayout{20f8702e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dhcpcd  ( 7578): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7578): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7578): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7578): wlan0: rebinding lease of 192.168.1.141
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/dhcpcd  ( 7578): wlan0: sending REQUEST (xid 0xcd6c94c2), next in 4.32 seconds
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
,D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 11:49:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453981797866], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453981797848]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1848): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1848):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7247): MCCMNC not supported: null
D/QRemote ( 7311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/UEI.SmartControl( 6919): Internal timer expired: 4
D/UEI.SmartControl( 6919): unbind internal service
,D/serial_port( 6919): close(fd = 24)
,E/WifiStateMachine( 1039):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1039): identical MTU - not setting
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524295
I/UEI.SmartControl( 6919): Serial port is closed.
I/dhcpcd  ( 7578): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7578): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7578): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7578): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 7578): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 7578): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7578): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7578): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7578): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/GCM     ( 2067): Connected
,D/GCM     ( 2067): Message class com.google.f.a.a.p
D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1039): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=827207422, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
D/[Concierge]Service( 2614): onStartCommand(). Type : 9
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
V/QRemote ( 7311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7311): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3334
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=827207422 [*alarm*], flags=0x0
V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5928): type=WIFI subType= reason=null isConnected=true
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7374): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7374): onReceive
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7374): Context : android.app.ReceiverRestrictedContext@1c2bf446
D/AppUp4:CustFacade( 7374): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7374): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7374): begin check event
I/AppUp4:CustModeStarterReceiver( 7374): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 6781): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3422): DownloadService onCreate
I/LGDMClient( 4337): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@f5b818a on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
,I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@262a63fb on behalf of 3422
W/Settings( 6781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/LgeMiscReceiver( 3369): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3369): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3369): networkInfo.isConnected() = true
D/PhoneState( 3369): setPdpRejectCasuse : false
E/LGDMClient( 4337): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4337): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4337): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3422): DownloadService onStartCommand
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@15f82c56 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 1
V/DownloadManager( 3422): processing inserted download 4
,D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:50:0
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
D/WeatherAncestor( 7474): connectivity changed - connection : true
D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@33216334
V/DownloadManager( 3422): processing inserted download 7
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:50:0
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
,V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): processing inserted download 22
V/DownloadManager( 3422): DownloadService onDestroy
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1422): onNotificationPosted
D/SmartCoverUpdateMonitor( 1422): received broadcast com.lge.intent.action.NLDataPosted
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
E/SmartCoverUpdateMonitor( 1422): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1422): handleNotificationPosted(true)
D/QuickCircle( 1422): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1422): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1422): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1422): post do just update job
D/LgeQuickCoverNotificationData( 1422): showAll3
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1422): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1422): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1422): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1422): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1422): updateNotificationData: count=3
D/QuickStatusbarLayout( 1422): Notification difference=198
D/QuickStatusbarLayout( 1422): child = android.widget.LinearLayout{20f8702e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine( 1039):  ConnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 7247): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 7247): Not supported operator for automatic switch
,D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7409): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7409): Alarm would be updated, because LastCheckTime has been updated.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
,I/GAV4    ( 7495): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7164): Test app app.js loaded
I/jxcore-log( 7164): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7164): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7164): BLE advertisement is supported,
I/jxcore-log( 7164): 
I/chromium( 7164): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 7164): --= Surplus to requirements =--
I/jxcore-log( 7164): 
I/jxcore-log( 7164): ****TEST TOOK:  ms ****
I/jxcore-log( 7164): 
I/jxcore-log( 7164): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7164): 
,D/AndroidRuntime( 7678): 
D/AndroidRuntime( 7678): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7678): CheckJNI is OFF
D/AndroidRuntime( 7678): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 7164:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1039): WIN DEATH: Window{37009f79 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1039): Client connection lost with reason: 4
D/InputDispatcher( 1039): Window went away: Window{37009f79 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1039): Skipping PackageSetting{37369edf com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1039):   Force finishing activity ActivityRecord{eb6236a u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
,W/ActivityManager( 1039): Spurious death for ProcessRecord{2351daf 7164:com.test.thalitest/u0a311}, curProc for 7164: null
,I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{eb6236a u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Duplicate finish request for ActivityRecord{eb6236a u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2029): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{1d5d1f16 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2029): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2029): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{1232097 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3735): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4624): Explicit concurrent mark sweep GC freed 16130(901KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 666us total 99.783ms
,D/PostponalbeReceiver( 6682): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,D/SplitUIManager( 1865): split_name #11 / not available #0
D/SplitUIService( 1865): removed split : 
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/ActivityManager( 1039): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7711 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1902): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3735): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2029): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2029): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1473): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2029): [Launcher.java:1114:onPause()]onPause
,D/ActionManagerService( 1902): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3735): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3735): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2029): , create_time: 1430558575574
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2029): , create_time: 1430558575600
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2029): , create_time: 1453384801850
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7690072,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2029): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1473): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/System.err( 4569): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
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
,D/SplitUIManager( 1865): split_name #11 / not available #0
I/SplitUIService( 1865): split app #11
I/art     ( 1039): Explicit concurrent mark sweep GC freed 106268(5MB) AllocSpace objects, 6(352KB) LOS objects, 33% free, 44MB/66MB, paused 2.899ms total 222.835ms
,I/art     ( 1039): WaitForGcToComplete blocked for 210.758ms for cause Explicit
,D/AppUp4:PreloadHelper( 7374): added Exclude : com.test.thalitest
I/LockScreenSettings( 7711): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2029): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
D/administrator( 1039): Handling package changes for user 0
,W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ThermalEngine(  332): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3139): Thermal-Lib-Client: Client request sent
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/ActivityManager( 1039): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7731 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          displayName: Music
D/KeyguardModel( 1473): handleShortcutListChanged...
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
,W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
I/ActivityManager( 1039): Killing 6971:com.lge.bnr/1000 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2029): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/KeyguardModel( 1473): handleShortcutListChanged...
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6971/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2614): onStartCommand(). Type : 8
D/[Concierge]Service( 2614): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{165eb2cb u0 com.lge.launcher2/.Launcher t3} time:288666
D/[Concierge]Service( 2614): Update widget ID : 11
,D/[Concierge]WidgetView( 2029): change position of spinner
I/art     ( 1039): Explicit concurrent mark sweep GC freed 9008(495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.614ms total 196.168ms
,W/ResourcesManager( 7731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,I/[Concierge]WidgetView( 2029): initWebView(). Time : 1453981804361
D/[Concierge]Service( 2614): onStartCommand(). Type : 0
W/ResourcesManager( 7731): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2029): Return exist ConciergeWebView. Reuse : 34905889
D/[Concierge]WidgetView( 2029): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2029): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2b313f90
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2029): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2029): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/SystemConfig( 7731): BUILD Country: EU
W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SystemConfig( 7731): BUILD Operator: OPEN
W/[Concierge]WidgetView( 2029): Widget kill message received. Destory myself. My : 1453981543399, New one : 1453981804361
D/[Concierge]WidgetView( 2029): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2029): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7678): Shutting down VM
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/ActivityManager( 1039): Killing 7030:com.google.android.apps.books/u0a54 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2029): Timeline: Activity_idle id: android.os.BinderProxy@2f717bdb time:288816
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_7030/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 2333): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 6781): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/SystemConfig( 7731): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7731): existFile = false
I/SystemConfig( 7731): canReadFile = false
I/SystemConfig( 7731): systemFeature RCS result false
D/SystemConfig( 7731): refreshRcsSupport() :false
I/chromium( 2029): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1039): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7754 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 216us total 9.211ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 8.859ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.897ms
,W/ResourcesManager( 7754): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7754): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7754): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7754): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardtInterface( 2029): onReloaded()
I/GBoardWebViewClient( 2029): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3735): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3735): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1902): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3735): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3735): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1902): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3735): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3735): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3735): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3735): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3735): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 7754): Total System Memory = 2995761152
,D/SystemHelper( 7754): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1039): Killing 6295:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_6295/cgroup.procs: No such file or directory
,D/LIA_Service_NativeEventReceiver( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 1992): startLIAService() : Trying to start LIA service ...

```
