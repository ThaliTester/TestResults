#### Test 57659382b63fd0b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,D/AndroidRuntime( 6783): 
D/AndroidRuntime( 6783): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6783): CheckJNI is OFF
--------- beginning of system
V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{2d82a245 type 0 when 1454082659255 com.android.vending} when 1454082659255
W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/SIM_STK ( 1041): Menu title from STK is T-Mobile
D/AndroidRuntime( 6783): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1041): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1949): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1041): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1041): setTaskToReturnTo : TaskRecord{346e4d9a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1041): setTaskToReturnTo : TaskRecord{346e4d9a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1041): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1041): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6821 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6783): Shutting down VM
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DSDPConnection( 1858): Display #0 changed.
V/ActivityManager( 1041): Display changed displayId=0
D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{2ed5314b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{10cd0728 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/Finsky  ( 6185): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6185): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6185): [1] 5.onFinished: Scheduling replication attempt 2.
D/ContextHelper( 6821): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6821): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6821): Loading: webviewchromium
I/LibraryLoader( 6821): Time to load native libraries: 4 ms (timestamps 6992-6996)
I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6821): Binding Chromium to main looper Looper (main, tid 1) {187883bb}
I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
I/chromium( 6821): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6821): Initializing chromium process, renderers=0
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  318): registerClient() client 0xb14275c0, uid 10311
D/BluetoothManagerService( 1041): Message: 20
D/BluetoothManagerService( 1041): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18daf931:true
W/chromium( 6821): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6821): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6821): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6821): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6821): Build Date: 12/12/14 금
I/Adreno-EGL( 6821): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6821): Remote Branch: 
I/Adreno-EGL( 6821): Local Patches: 
I/Adreno-EGL( 6821): Reconstruct Branch: 
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
W/chromium( 6821): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6821): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6821): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6821): CordovaWebView is running on device made by: LGE
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6821): Render dirty regions requested: true
I/OpenGLRenderer( 6821): Initialized EGL, version 1.4
D/OpenGLRenderer( 6821): Enabling debug mode 0
D/Atlas   ( 6821): Validating map...
D/SplitWindow( 1041): check instance of lgWin Window{36418023 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6821): LgDataFeature() Constructor: none
D/LgDataFeature( 6821): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1041): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1041): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1041): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1041): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3e2116e6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1041): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1041): Displayed com.test.thalitest/.MainActivity: +606ms (total +691ms)
I/Timeline( 6821): Timeline: Activity_idle id: android.os.BinderProxy@244dd1ab time:117418
I/Timeline( 1041): Timeline: Activity_windows_visible id: ActivityRecord{db826cb u0 com.test.thalitest/.MainActivity t4} time:117423
D/JsMessageQueue( 6821): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6821): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6821): 
D/jxcore_app_log( 6821): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435206912
I/chromium( 6821): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6821): 
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 117772962718; DSPS: 4000056; Offset : -4313482799
I/chromium( 6821): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6821): Initializing JXcore engine
W/jxcore-log( 6821): JXcore engine is ready
,W/Thread-794( 6880): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9913]" dev="sockfs" ino=9913 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-794( 6880): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-794( 6880): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10106]" dev="sockfs" ino=10106 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-794( 6880): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-794( 6880): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33228]" dev="sockfs" ino=33228 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6821): Starting JXcore engine
W/jxcore-log( 6821): Platform android
W/jxcore-log( 6821): 
W/jxcore-log( 6821): Process ARCH arm
W/jxcore-log( 6821): 
,I/jxcore-log( 6821): JXcore Cordova bridge is ready!
I/jxcore-log( 6821): 
,W/jxcore-log( 6821): JXcore engine is started
,I/jxcore-log( 6821): Toggling radios to true
I/jxcore-log( 6821): 
,D/BluetoothAdapter( 6821): enable(): BT is already enabled..!
D/WifiService( 1041): New client listening to asynchronous messages
D/WifiServiceImplEx( 1041): setWifiEnabled: true pid=6821, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1041): setWifiEnabled: true pid=6821, uid=10311
E/WifiService( 1041): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1041): disconnect pid=6821, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1041): reconnect pid=6821, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1041):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6821): Radios toggled
I/jxcore-log( 6821): 
E/WifiStateMachine( 1041):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6821): My device name is: LGE-LG-D855
I/jxcore-log( 6821): 
E/WifiNative: ( 1041): [119,872,803 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1041): doBoolean: DISCONNECT
I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1041): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1041): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1041): InitialState.processMessage what=4
,D/Tethering( 1041): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1041): DISCONNECT: returned true
E/WifiStateMachine( 1041): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/DhcpStateMachine( 1041): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  314): Clearing all IP addresses on wlan0
V/NativeCrypto( 2132): Read error: ssl=0xaf4d5600: I/O error during system call, Connection timed out
I/ActivityManager( 1041): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6892 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2132): SSL shutdown failed: ssl=0xaf4d5600: I/O error during system call, Broken pipe
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1041): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiHS20( 1041): hidePasspointNotification off =false
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1041): hidePasspointNotification off =false
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1041): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1041):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1041): [120,014,460 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1041): doBoolean: RECONNECT
I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/WfdStateTracker( 1949): handleWifiStateChangedEvent: 0
D/WifiNative-wlan0( 1041): RECONNECT: returned true
E/WifiStateMachine( 1041):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=120016
E/WifiStateMachine( 1041):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=120017
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1041): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1041): disableDataServiceNotify
D/DSQN    ( 1041): stop dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/DSQN    ( 1041): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120079  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120079  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1041): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120083  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1041): hidePasspointNotification off =false
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1041): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 6892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6892): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6892): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  ,ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 6892): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateSCANNING
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6892): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6892): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1041): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1041): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Disconnected - quitting
D/CSLegacyTypeTracker( 1041): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1041): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1041): Removing idletimer
W/Settings( 1041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1041): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1041): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1041): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getTyp,e():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1041): StoppedState
,D/DhcpStateMachine( 1041): StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6892): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6892): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6892): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1041): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6918 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6069:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10011/pid_6069/cgroup.procs: No such file or directory
,I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6918): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6892): LgDataFeature() Constructor: none
,D/LgDataFeature( 6892): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
I/ActivityManager( 1041): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6939 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1041): Killing 6094:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10019/pid_6094/cgroup.procs: No such file or directory
,W/ResourcesManager( 6939): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6939): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6939): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6939): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6939): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6939): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6939): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6939): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6939): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6939): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6918): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6918): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6918): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6939): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6939): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6939): LgDataFeature() Constructor: none
D/LgDataFeature( 6939): LgDataFeature() Constructor Done, null
,V/SoundPool( 6939): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6939): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6939): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6939): doLoad: loading sample sampleID=1
I/QRemote ( 6939): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6939): Start decode
V/MediaPlayer[Native]( 6939): decode(31, 10857164, 17813)
V/MediaPlayerService(  318): decode(23, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1163240, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
,V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
,E/MediaExtractor(  318): Use LGExtractor :application/ogg 
,D/UEI.SmartControl( 6648): QS Service created
D/QRemote ( 6939): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6939): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  318): supported mime: application/ogg
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
,V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
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
,V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
,V/LGCodecOSAL(  318): Not support LGCodec
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14347e0 on output port
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
V/AudioCache(  318): notify(0xb1163240, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb1163240, 1, 0, 0)
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
V/LGMDMManager( 6939): Create singleton instance
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.,vorbis.decoder] Port is disabled, freeing buffer 2973975824
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976544
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb1163240, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae904000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae905000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae906000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae907000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae908000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae909000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae90a000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae90b000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae90c000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae90d000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae90e000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
I/UEI.SmartControl( 6648): Service initServices...
V/AudioCache(  318): memcpy(0xae90f000, 0xb57bf000, 4096)
D/UEI.SmartControl( 6648): QS start get config
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae910000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae911000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae912000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae913000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae914000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae915000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae916000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae917000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae918000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae919000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91a000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91b000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91c000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91d000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91e000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae91f000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae920000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae921000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae922000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae923000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae924000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae925000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae926000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae927000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae928000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae929000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92a000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92b000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92c000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92d000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92e000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae92f000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae930000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae931000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae932000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae933000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae934000, 0xb57bf000, 4096)
V/AudioCache(  318): write(0xb57bf000, 4096)
V/AudioCache(  318): memcpy(0xae935000, 0xb57bf000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
,V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb57bf000, 280)
V/AudioCache(  318): memcpy(0xae936000, 0xb57bf000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb1163240, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AudioCache(  318): wait - success
V/AwesomePlayer(  318): pause_l() 
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  318): notify(0xb1163240, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): Pause Playback at 1068125
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1163240, 8, 0, 0)
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
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
V/SoundPool( 6939): close(31)
V/SoundPool( 6939): pointer = 0xa000d,000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6939): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:91,
I/UEI.SmartControl( 6648): Supports setup maps: true
,D/UEI.SmartControl( 6648): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6648): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6648): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6648): ### init IR Blaster...
D/serial_port( 6648): Configuring serial port
E/UEI.SmartControl( 6648): UEIBLaster setting for 616
I/UEI.SmartControl( 6648): Setting serial record hearder size = 2
I/UEI.SmartControl( 6648): configuring settings for MAXQ616
I/UEI.SmartControl( 6648): Get version...
D/UEI.SmartControl( 6648): serial port data available: 21
,D/UEI.SmartControl( 6648): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6648): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6648): QS saving settings...
D/UEI.SmartControl( 6648): IR Blaster version: 25672567
,D/UEI.SmartControl( 6648): serial port data available: 4
,I/UEI.SmartControl( 6648): Device manager: loading config....
D/UEI.SmartControl( 6648): ----------- loading internal config...
,W/ContextImpl( 6648): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6648): Services init done
D/UEI.SmartControl( 6648): QS Service init finished
D/UEI.SmartControl( 6648): QS Service version name: 2.1.91
D/UEI.SmartControl( 6648): QS Service version code: 201091
E/UEI.SmartControl( 6648): Loading SETTINGS...
D/UEI.SmartControl( 6648): Service requested: Control
,I/QRemote ( 6939): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6648): ------ IControl API: 11
D/UEI.SmartControl( 6648): File observer start...
E/UEI.SmartControl( 6648): IR Port is disabled: false
D/UEI.SmartControl( 6648): Starting file observer...
I/UEI.SmartControl( 6648): Registering callback...
I/UEI.SmartControl( 6648): ------ IControl API: 19
I/UEI.SmartControl( 6648): Registering Services Ready callback...
D/UEI.SmartControl( 6648): Internal service binding...
D/UEI.SmartControl( 6648): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6648): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6648): -----service ready thread exits
I/QRemote ( 6939): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6939): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6939): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 6939): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6939): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6648): ------ IControl API: 8
D/QRemote ( 6939): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6939): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6939): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6939): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6939): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6939): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6939): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6939): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6939): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6939): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6939): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454082664628]
D/QRemote ( 6939): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1041): Killing 6516:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 6939): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1041): failed to open /acct/uid_10023/pid_6516/cgroup.procs: No such file or directory
,V/QRemote ( 6939): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6939): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1041): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine( 1041):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
W/WifiMonitor( 1041): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2609): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1041):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1041):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1041):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1041): doString: [BSS RANGE=0- MASK=0x21987]
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122119  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122133  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
,D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2609): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1041): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1041):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1041): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122237  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122237  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1041):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122238
E/WifiStateMachine( 1041):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122238
E/WifiStateMachine( 1041):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122238
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122239
E/WifiStateMachine( 1041):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122239
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=122240  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/wpa_supplicant( 2609): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1041): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1041): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=122258  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1041):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122260
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1041):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122261
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1041): doString: [STATUS]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1041):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1041): setVHTCapabilityType  : false
,D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6892): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6892): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6892): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1041): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1041): setKeepAlivePacketInterval msec : 60
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1041): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1041): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1041): NetworkAgent connected
,D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1041): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1041): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1041): WaitBeforeStartState
E/WifiStateMachine( 1041):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122313  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122313  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122314  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1041):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122315  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1041):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122316  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122316  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1041):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,E/WifiStateMachine( 1041):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1041): doBoolean: DRIVER SETSUSPENDMODE 0
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1041): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 0
,D/WifiNative-wlan0( 1041): SET ps 0: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1041): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1041): Current State is mWaitBeforeStartState.
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
V/LgDhcpStateMachineHelper( 1041): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15263c65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15263c65 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1041): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1041): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1041): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1041): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1041):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1041):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 1041):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1041): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/ConnectivityService( 1041): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1041):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1041):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1041): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1041): ignoring duplicate network state non-change
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1041): Adding iface wlan0 to network 101
E/WifiStateMachine( 1041): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1041): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1041): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/WifiHS20( 1041): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1041): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
V/WfdStateTracker( 1949): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1041): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1041): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1041): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1041): Setting Dns servers for network 101 to [/192.168.1.1]
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1041): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1041): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1041):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Connected
D/ConnectivityService( 1041):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1041): currentScore = 0, newScore = 20
D/ConnectivityService( 1041):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1041): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1041): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1858): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1041): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1041): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1041): sendStick,yBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1041): [e] list.add(nai) empty : false size: 1
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1041): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1041): validation of new default Network = false
D/ConnectivityService( 1041): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1041): enableDataServiceNotify 
D/DSQN    ( 1041): start dsqn bin
D/LocSvc_java( 1041): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1041): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7003): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7003): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1041): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
,E/DSQN    ( 7003): DSQN ssw
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6939): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6939): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6939): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6918): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6918): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/DhcpStateMachine( 1041): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1041): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1041): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7007): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7007): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6939): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6939): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6939): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/dhcpcd  ( 7007): version 5.5.6 starting
E/dhcpcd  ( 7007): get_duid: m
D/dhcpcd  ( 7007): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7007): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7007): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7007): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7007): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7007): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7007): wlan0: sending REQUEST (xid 0xf679724a), next in 4.52 seconds
,D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1041): MasterInitialState.processMessage what=3
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/DSQN    ( 1041): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1041): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 15:51:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454082666051], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454082666033]}
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
D/Tethering( 1041): MasterInitialState.processMessage what=3
D/ConnectivityService( 1041): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/ConnectivityService( 1041): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1858): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5436): type=WIFI subType= reason=null isConnected=true
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/NetworkMonitor( 5436): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1041): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7035 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7035): onCreate
,W/AppUp4:DB( 7035):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7035):  setFingerPrint start
I/AppUp4:DB( 7035):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7035):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7035):  SDK version = 21
I/AppUp4:DB( 7035):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7035): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7035): onReceive
D/LgDataFeature( 7035): LgDataFeature() Constructor: none
,D/LgDataFeature( 7035): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7035): Context : android.app.ReceiverRestrictedContext@2ede9c31
D/AppUp4:CustFacade( 7035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7035): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7035): begin check event
I/AppUp4:CustModeStarterReceiver( 7035): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7035): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7035): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7035): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7035): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1041): Killing 6114:com.android.gallery3d/u0a27 (adj 15): empty #17
,E/WifiStateMachine( 1041):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1041):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524295
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1041): failed to open /acct/uid_10027/pid_6114/cgroup.procs: No such file or directory
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3300): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3300): DownloadService onCreate
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3300): in removeSpuriousFiles
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@4136a7c on behalf of 3300
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3300): in trimDatabase
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@8595b5a on behalf of 3300
I/ActivityManager( 1041): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7060 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3300): DownloadService onStartCommand
V/DownloadManager( 3300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@46ab268 on behalf of 3300
E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4317): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3300): processing inserted download 1
,V/DownloadManager( 3300): processing inserted download 4
V/DownloadManager( 3300): processing inserted download 7
V/DownloadManager( 3300): processing inserted download 8
V/DownloadManager( 3300): processing inserted download 9
V/DownloadManager( 3300): processing inserted download 10
V/DownloadManager( 3300): processing inserted download 16
V/DownloadManager( 3300): processing inserted download 17
V/DownloadManager( 3300): processing inserted download 18
V/DownloadManager( 3300): processing inserted download 21
,V/DownloadManager( 3300): processing inserted download 22
V/DownloadManager( 3300): DownloadService onDestroy
,W/ResourcesManager( 7060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 1041): Explicit concurrent mark sweep GC freed 84035(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.641ms total 156.988ms
,I/LGEmail ( 7060): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7060): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7060): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7060): LgDataFeature() Constructor: none
D/LgDataFeature( 7060): LgDataFeature() Constructor Done, null
,D/eas_req ( 7060): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 7007): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7007): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7007): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7007): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7007): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7007): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7007): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7007): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7007): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1041): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7086 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7060): JNI_OnLoad()
I/HubEmail( 7060): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7060): registerNatives()
I/HubEmail( 7060): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7060): registerNativeMethods()
I/HubEmail( 7060): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7060): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1041): Killing 6549:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1041): failed to open /acct/uid_10061/pid_6549/cgroup.procs: No such file or directory
,W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3128): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3128): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3128): networkInfo.isConnected() = false
D/DhcpStateMachine( 1041): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1041): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1041): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1041): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1041): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1041): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1041): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1041): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1041): RunningState
I/ActivityManager( 1041): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7134 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6821): 
,I/ActivityManager( 1041): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7154 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6138:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1041): failed to open /acct/uid_10080/pid_6138/cgroup.procs: No such file or directory
,I/ActivityManager( 1041): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7174 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 6160:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1041): failed to open /acct/uid_10097/pid_6160/cgroup.procs: No such file or directory
,V/FormManager( 7086): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7086): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1041): Killing 6601:com.lge.eula/1000 (adj 15): empty #17
,E/WifiStateMachine( 1041):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1041):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/art     ( 7174): Almond Protected OAT
W/libprocessgroup( 1041): failed to open /acct/uid_1000/pid_6601/cgroup.procs: No such file or directory
,D/WeatherApplication( 7174): removeAccount
,D/WeatherApplication( 7174): Account.length = 0
E/WeatherApplication( 7174): OPERATOR:OPEN
D/WeatherAncestor( 7174): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:8
D/Weather.Utils( 7174): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7174): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7174): 2 : This is isUpdating : false
,D/WeatherAncestor( 7174): connectivity changed - connection : true
,D/WeatherService( 7174): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7174): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7174): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7174): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7174): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7174): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:8
I/ActivityManager( 1041): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7193 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 5996:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  351): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 19.980ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 9.638ms
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.436ms
,W/libprocessgroup( 1041): failed to open /acct/uid_10005/pid_5996/cgroup.procs: No such file or directory
V/WifiInternetCheck( 1041): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7193): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7193): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6821): 
D/Tethering( 1041): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5436): type=WIFI subType= reason=null isConnected=true
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7193): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7193): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6821): 
I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6821): 
I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6821): 
I/WebViewFactory( 7193): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7193): Loading: webviewchromium
I/LibraryLoader( 7193): Time to load native libraries: 3 ms (timestamps 5640-5643)
I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7193): Binding Chromium to main looper Looper (main, tid 1) {1c955820}
I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
I/chromium( 7193): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7193): Initializing chromium process, renderers=0
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7193): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7193): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7193): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  318): registerClient() client 0xb1427da0, uid 10093
W/AudioManagerAndroid( 7193): Requires BLUETOOTH permission
,I/Adreno-EGL( 7193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7193): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7193): Build Date: 12/12/14 금
I/Adreno-EGL( 7193): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7193): Remote Branch: 
I/Adreno-EGL( 7193): Local Patches: 
I/Adreno-EGL( 7193): Reconstruct Branch: 
,I/NSApplication( 7193): Starting up...
,I/ActivityManager( 1041): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7254 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6622:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_1000/pid_6622/cgroup.procs: No such file or directory
W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSActivity( 2132): [ac] getting account id
,D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2132): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7035): onReceive
D/AppUp4:CustFacade( 7035): Context : android.app.ReceiverRestrictedContext@2ede9c31
D/AppUp4:CustFacade( 7035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7035): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7035): begin check event
I/AppUp4:CustModeStarterReceiver( 7035): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3300): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3300): DownloadService onCreate
I/DownloadManager( 3300): in removeSpuriousFiles
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@8c1d326 on behalf of 3300
,W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3300): DownloadService onStartCommand
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
V/DownloadManager( 3300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3300): in trimDatabase
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@8ac59bd on behalf of 3300
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4317): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3300): processing inserted download 1
V/DownloadManager( 3300): processing inserted download 4
V/DownloadManager( 3300): processing inserted download 7
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@19e7fbb2 on behalf of 3300
V/DownloadManager( 3300): processing inserted download 8
V/DownloadManager( 3300): processing inserted download 9
,V/DownloadManager( 3300): processing inserted download 10
V/DownloadManager( 3300): processing inserted download 16
V/DownloadManager( 3300): processing inserted download 17
V/DownloadManager( 3300): processing inserted download 18
V/DownloadManager( 3300): processing inserted download 21
V/DownloadManager( 3300): processing inserted download 22
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3300): DownloadService onDestroy
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
I/LgeMiscReceiver( 3128): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3128): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3128): networkInfo.isConnected() = false
D/WeatherAncestor( 7174): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:9
,D/Weather.Utils( 7174): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7174): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7174): 2 : This is isUpdating : false
D/WeatherAncestor( 7174): connectivity changed - connection : true
D/WeatherService( 7174): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3021a097
D/ForecastDataCache( 7174): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7174): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7174): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7174): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7174): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:9
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7035): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7035): onReceive
,V/FormManager( 7086): There are no updated forms. The schedule will be deleted.
D/AppUp4:CustFacade( 7035): Context : android.app.ReceiverRestrictedContext@2ede9c31
D/AppUp4:CustFacade( 7035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7035): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7035): begin check event
I/AppUp4:CustModeStarterReceiver( 7035): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/FormManager( 7086): Alarm would be updated, because LastCheckTime has been updated.
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3300): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3300): DownloadService onCreate
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
,D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
I/DownloadManager( 3300): in removeSpuriousFiles
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@2c0f6680 on behalf of 3300
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3300): in trimDatabase
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@6d620fe on behalf of 3300
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 43,17): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3300): DownloadService onStartCommand
V/DownloadManager( 3300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@e446aac on behalf of 3300
I/LgeMiscReceiver( 3128): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3128): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3128): networkInfo.isConnected() = true
D/PhoneState( 3128): setPdpRejectCasuse : false
V/DownloadManager( 3300): processing inserted download 1
W/Settings( 7060): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3300): processing inserted download 4
V/DownloadManager( 3300): processing inserted download 7
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3300): processing inserted download 8
V/DownloadManager( 3300): processing inserted download 9
V/DownloadManager( 3300): processing inserted download 10
V/DownloadManager( 3300): processing inserted download 16
V/DownloadManager( 3300): processing inserted download 17
V/DownloadManager( 3300): processing inserted download 18
,V/DownloadManager( 3300): processing inserted download 21
,D/WeatherAncestor( 7174): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:9
V/DownloadManager( 3300): processing inserted download 22
D/Weather.Utils( 7174): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7174): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7174): 2 : This is isUpdating : false
V/DownloadManager( 3300): DownloadService onDestroy
D/WeatherAncestor( 7174): connectivity changed - connection : true
D/WeatherService( 7174): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3021a097
D/ForecastDataCache( 7174): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7174): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7174): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7174): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7174): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:9
V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{2612ca2a type 2 when 126595 com.google.android.gms} when 126595
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
V/QRemote ( 6939): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6939): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:91
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/FormManager( 7086): There are no updated forms. The schedule will be deleted.
D/UEI.SmartControl( 6648): Internal timer expired: 2
D/UEI.SmartControl( 6648): unbind internal service
V/FormManager( 7086): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
,D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/WifiInternetCheck( 1041): isHttpConnectionAvailable - We got a valid response : 204
D/serial_port( 6648): close(fd = 24)
,I/UEI.SmartControl( 6648): Serial port is closed.
,D/GCM     ( 2132): Connected
,D/GCM     ( 2132): Message class com.google.f.a.a.p
W/ProcessCpuTracker( 1041): Skipping unknown process pid 7022
W/ProcessCpuTracker( 1041): Skipping unknown process pid 7025
,W/ProcessCpuTracker( 1041): Skipping unknown process pid 7213
W/ProcessCpuTracker( 1041): Skipping unknown process pid 7215
W/ProcessCpuTracker( 1041): Skipping unknown process pid 7263
W/ProcessCpuTracker( 1041): Skipping unknown process pid 7316
I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
,I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1041): battery changed pluggedType: 2
D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3761): Disconnected process message: 10, size: 0
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/art     ( 1041): Explicit concurrent mark sweep GC freed 34050(1602KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 2.272ms total 145.240ms
,I/GAV4    ( 7193): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{10969cfc type 2 when 130966 android} when 130966
,I/jxcore-log( 6821): Test app app.js loaded
I/jxcore-log( 6821): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1045329f added. We now have 1 listener(s)
I/jxcore-log( 6821): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6821): 
I/chromium( 6821): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 1041): Killing 6026:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10014/pid_6026/cgroup.procs: No such file or directory
,I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{b8a11da type 0 when 1454082679746 com.android.vending} when 1454082679746
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6185): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6185): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6185): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 137774857034; DSPS: 4655478; Offset : -4313482137
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{3e0aa3f5 type 0 when 1454082700129 com.android.vending} when 1454082700129
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 157776392807; DSPS: 5310888; Offset : -4313472424
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6185): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6185): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6185): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1041):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1041):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1041):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{1df40bcf type 2 when 168904 android} when 168904
,I/BooksSync( 6683): Starting books sync
,D/BooksSync( 6683): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6683): null auth token
W/ResourcesManager( 1406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
W/ResourcesManager( 1406): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1406): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3961140120002382072&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3961140120002382072&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3961140120002382072&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,E/BooksSync( 6683): Soft error: 
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3961140120002382072&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  }
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
,E/BooksSync( 6683): Sync error
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3961140120002382072&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  }
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
I/BooksSync( 6683): Finished books sync
D/SyncManager( 1041): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168904, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 177778506653; DSPS: 5966318; Offset : -4313494756
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{70bc343 type 0 when 1454082720874 com.android.vending} when 1454082720874
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6185): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6185): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6185): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 197781032272; DSPS: 6621760; Offset : -4313471397
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{408fe6d type 2 when 198943 android} when 198943
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 217783193774; DSPS: 7277191; Offset : -4313476617
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{3f940333 type 0 when 1454082754064 com.android.vending} when 1454082754064
,V/SIM_STK ( 1041): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6185): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6185): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6185): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager( 1041): RTC_WAKEUP set : Alarm{38f35cdd type 0 when 1454082701171 com.google.android.gms} when 1454082701171
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{15d81052 type 2 when 184716 com.google.android.gms} when 184716
V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{13641f23 type 2 when 214047 android} when 214047
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2352): Aggregate from 1454080901075 (log), 1454080901075 (data)
,I/VacuumService( 2132): Vacuum at: now=1454082770878 tag=VacuumService
,I/GoogleURLConnFactory( 2132): Using platform SSLCertificateSocketFactory
,W/Uploader( 2132): No account for auth token provided
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,I/art     ( 2132): Explicit concurrent mark sweep GC freed 41125(2MB) AllocSpace objects, 17(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.954ms total 67.177ms
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2132): No account for auth token provided
,W/Uploader( 2132): No account for auth token provided
,W/Uploader( 2132):  no longer exists, so no auth token.
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 237787989964; DSPS: 7932708; Offset : -4313471894
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 257790684020; DSPS: 8588157; Offset : -4313493722
,I/jxcore-log( 6821): TAP version 13
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # multiplex can send data
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 1 String should be length:200
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # enqueue and run in order
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 2 firstPromise setTimeout
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 3 firstPromise result
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 4 firstPromise testValue
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 5 secondPromise setTimeout
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 6 secondPromise result
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 7 secondPromise testValue
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 8 thirdPromise in promise
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 9 thirdPromise result
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 10 thirdPromise testValue
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # basic
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 11 sane
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # another
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 12 sane
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 13 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 14 null
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 15 (unnamed assert)
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 16 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 17 should not throw
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 18 (unnamed assert)
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 19 (unnamed assert)
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 20 should not throw
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 21 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 22 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 23 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # failed to get mobile documents path
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 24 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 25 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 26 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 27 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #init should register the networkChanged event
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 28 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #startBroadcasting should throw on null device name
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 29 should throw
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 30 should throw
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 31 should throw
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 32 should throw
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #startBroadcasting should throw on negative port
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 33 should throw
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #startBroadcasting should throw on too large port
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 34 should throw
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 35 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 36 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 37 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 38 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 39 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 40 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 41 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 42 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 43 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 44 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 45 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 46 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 47 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 48 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 49 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 50 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 51 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ok 52 should be equal
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ok 53 should be equal
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
I/jxcore-log( 6821): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): # teardown
I/jxcore-log( 6821): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd2fec added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: BLE -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (BLE)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: BLE -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setBluetoothMacAddress: 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808548.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808548.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808548.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3761): [BTUI] createSocketChannel FD=84 mFd=82
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808548.6821","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082808548.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082808548.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae7af8f2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae7af8f2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383534382e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383534382e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383534381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383534381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2609): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1949): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808548.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/jxcore-log( 6821): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383534381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383534381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED,
I/jxcore-log( 6821): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27456231 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808681.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808681.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808681.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808681.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082808681.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082808681.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@878a3976 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@878a3976 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383638312e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383638312e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383638311f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383638311f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808681.6821, mode: WIFI
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
I/jxcore-log( 6821): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
,D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383638311f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383638311f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
I/jxcore-log( 6821): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-5ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dcf06d added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808733.6821
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808733.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808733.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808733.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082808733.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082808733.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a9f18d7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a9f18d7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383733332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383733332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383733331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383733331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808733.6821, mode: WIFI
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
I/jxcore-log( 6821): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383733331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383733331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6821): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e52669 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808783.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
I/art     ( 1041): Explicit concurrent mark sweep GC freed 29285(1367KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 3.721ms total 150.598ms
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808783.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808783.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
,W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808783.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082808783.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082808783.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f3ac4630 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f3ac4630 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383738332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808783.6821, mode: WIFI
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383738332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383738331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383738331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6821): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
D/LGWifiP2pService( 1041): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=147493 target=com.a,ndroid.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6821): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383738331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820c025 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383738331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
D/LGWifiP2pService( 1041): InactiveState{ when=0 ,what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808998.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808998.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808998.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082808998.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082808998.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082808998.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@635b9aa0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@635b9aa0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383939382e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830383939382e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383939381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082808998.6821, mode: WIFI
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383939381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2609): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
D/WfdsMonitor( 1949): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1041): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/jxcore-log( 6821): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6821): stop
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383939381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830383939381f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Cannot restart, because not initialized
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6821): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c239a1 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809056.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809056.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809056.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809056.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082809056.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082809056.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b445d7bc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b445d7bc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393035362e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393035362e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393035361f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393035361f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809056.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6821): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1041): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6821): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393035361f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393035361f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba7cedd added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809103.6821
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809103.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809103.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809103.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082809103.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082809103.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4fbd8a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4fbd8a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393130332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393130332e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393130331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393130331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809103.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6821): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393130331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393130331f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6821): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b577bd9 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809170.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809170.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809170.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809170.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082809170.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082809170.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8837e02 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8837e02 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393137302e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393137302e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393137301f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393137301f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809170.6821, mode: WIFI
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
D/BluetoothManagerService( 1041): checkIfCallerIsForegro,undUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6821): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
,I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative,-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393137301f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393137301f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6821): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bafc95 added. We now have 10 listener(,s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809229.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809229.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809229.6821, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809229.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082809229.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082809229.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d7a0d2b8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d7a0d2b8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393232392e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393232392e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393232391f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393232391f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809229.6821, mode: WIFI
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6821): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
I/io.jxcore.node.ConnectionHelper( 6821): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting t,hread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393232391f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393232391f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1041): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
I/jxcore-log( 6821): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 6821): 
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6821): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199bcd11 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6821): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809307.6821
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809307.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): start: OK
I/io.jxcore.node.ConnectionHelper( 6821): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809307.6821, mode: WIFI
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): bind: Binding a new listener
W/BluetoothAdapter( 6821): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6821): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454082809307.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: {"pi":"58:3F:54:73:64:C0","pn":"1454082809307.6821","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454082809307.6821","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@393d6fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@393d6fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState add service
D/LGWifiP2pService( 1041): add a new client
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393330372e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343038323830393330372e36383231222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393330371f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1041): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393330371f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
I/wpa_supplicant( 2609): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454082809307.6821, mode: WIFI
D/WfdsMonitor( 1949): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1041): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1041): P2P_FIND 120: returned true
D/LGWifiP2pService( 1041): discovery change broadcast true
D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6821): start: OK
I/jxcore-log( 6821): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 6821): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6821): stop
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): stopListeningForIncomingConnections: Stopping...
I/wpa_supplicant( 2609): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): shutdown
D/WfdsMonitor( 1949): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6821): Exiting thread
D/WifiMonitor( 1041): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6821): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6821): onServerStopped
E/WifiMonitor( 1041): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6821): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6821): stopProvideBluetoothMacAddressMode
D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6821): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6821): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6821): clear
D/LGWifiP2pService( 1041): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6821): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6821): ok 73 Should be able to call stopBroadcasting without error,
I/jxcore-log( 6821): 
,D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1041): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393330371f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1041): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343038323830393330371f36383231222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
,D/LGWifiP2pService( 1041): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6821): Local services cleared successfully
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1041): doBoolean: P2P_STOP_FIND
,D/WifiNative-p2p0( 1041): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6821): P2P device discovery stopped successfully,
D/LGWifiP2pService( 1041): InactiveState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1041): P2pEnabledState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState clear service request
I/jxcore-log( 6821): # setup
I/jxcore-log( 6821): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6821): Service requests cleared successfully
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 277792092866; DSPS: 9243563; Offset : -4313488736
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 297794012598; DSPS: 9898986; Offset : -4313491689
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{2dde346e type 2 when 299399 android} when 299399
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/BooksSync( 6683): Starting books sync
,D/BooksSync( 6683): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7467794291531686333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
W/ApiaryClient( 6683): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7467794291531686333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1406): Notification difference=198
,D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6683): null auth token
W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7467794291531686333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,E/BooksSync( 6683): Soft error: 
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7467794291531686333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  }
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
,E/BooksSync( 6683): Sync error
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7467794291531686333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  }
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
I/BooksSync( 6683): Finished books sync
D/SyncManager( 1041): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 299399, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1041): battery changed pluggedType: 2
D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3761): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 317796159413; DSPS: 10554416; Offset : -4313481079
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{30519294 type 2 when 329664 android} when 329664
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 337798274613; DSPS: 11209845; Offset : -4313471539
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 357800334971; DSPS: 11865273; Offset : -4313484684
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6185): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6185): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6185): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6185): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6185): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6185): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6185): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6185): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 377802348088; DSPS: 12520699; Offset : -4313487368
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 397804072872; DSPS: 13176115; Offset : -4313471698
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 417805852552; DSPS: 13831534; Offset : -4313492451
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 437807382075; DSPS: 14486944; Offset : -4313488990
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 457809152587; DSPS: 15142362; Offset : -4313488342
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 477811877529; DSPS: 15797811; Offset : -4313479437
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 497813952625; DSPS: 16453239; Offset : -4313479588
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 517815784805; DSPS: 17108659; Offset : -4313478463
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 537817849277; DSPS: 17764087; Offset : -4313489186
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{2e6ddb56 type 2 when 556452 android} when 556452
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/BooksSync( 6683): Starting books sync
,D/BooksSync( 6683): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1406): Notification difference=198
,D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7292596888855483401&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 557820128540; DSPS: 18419521; Offset : -4313468121
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7292596888855483401&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1041): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1041): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1041): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1041): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1041): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6683): Authentication error
E/BooksAccountManager( 6683): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6683): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6683): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6683): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6683): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3ac9d4b9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6683): Error response from books API: {
W/ApiaryClient( 6683):  "error": {
W/ApiaryClient( 6683):   "errors": [
W/ApiaryClient( 6683):    {
W/ApiaryClient( 6683):     "domain": "global",
W/ApiaryClient( 6683):     "reason": "required",
W/ApiaryClient( 6683):     "message": "Login Required",
W/ApiaryClient( 6683):     "locationType": "header",
W/ApiaryClient( 6683):     "location": "Authorization"
W/ApiaryClient( 6683):    }
W/ApiaryClient( 6683):   ],
W/ApiaryClient( 6683):   "code": 401,
W/ApiaryClient( 6683):   "message": "Login Required"
W/ApiaryClient( 6683):  }
W/ApiaryClient( 6683): }
,W/ApiaryClient( 6683): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7292596888855483401&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6683): Headers:
W/ApiaryClient( 6683): accept-encoding: [gzip]
W/ApiaryClient( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6683): gdata-version: 2
,E/BooksSync( 6683): Soft error: 
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7292596888855483401&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
,E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  },
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
,E/BooksSync( 6683): Sync error
E/BooksSync( 6683): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6683): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7292596888855483401&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6683): Headers:
E/BooksSync( 6683): accept-encoding: [gzip]
E/BooksSync( 6683): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6683): gdata-version: 2
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6683): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6683): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6683): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6683): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6683): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6683): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6683): {
E/BooksSync( 6683):  "error": {
E/BooksSync( 6683):   "errors": [
E/BooksSync( 6683):    {
E/BooksSync( 6683):     "domain": "global",
E/BooksSync( 6683):     "reason": "required",
E/BooksSync( 6683):     "message": "Login Required",
E/BooksSync( 6683):     "locationType": "header",
E/BooksSync( 6683):     "location": "Authorization"
E/BooksSync( 6683):    }
E/BooksSync( 6683):   ],
E/BooksSync( 6683):   "code": 401,
E/BooksSync( 6683):   "message": "Login Required"
E/BooksSync( 6683):  }
E/BooksSync( 6683): }
E/BooksSync( 6683): 
E/BooksSync( 6683): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6683): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6683): 	... 8 more
I/BooksSync( 6683): Finished books sync
D/SyncManager( 1041): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 556452, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 577822102960; DSPS: 19074946; Offset : -4313477448
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{12958390 type 2 when 586664 android} when 586664
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 597824061181; DSPS: 19730370; Offset : -4313472325
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 617825766590; DSPS: 20385786; Offset : -4313476004
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 3761): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1041): battery changed pluggedType: 2
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 637827528353; DSPS: 21041204; Offset : -4313484314
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/ActivityManager( 1041): Killing 2206:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  318): 2206 died, releasing its sessions
,V/AudioFlinger(  318):  pid 1858 @ 0
V/AudioFlinger(  318):  pid 3128 @ 1
V/AudioFlinger(  318):  pid 3128 @ 2
,W/libprocessgroup( 1041): failed to open /acct/uid_10034/pid_2206/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 657829633762; DSPS: 21696633; Offset : -4313484512
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,I/ActivityManager( 1041): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7585 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,I/art     ( 1041): Explicit concurrent mark sweep GC freed 34070(1707KB) AllocSpace objects, 10(1056KB) LOS objects, 33% free, 44MB/66MB, paused 3.744ms total 165.437ms
,I/DigitalAppWidgetProvider( 7585): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7585): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1113484a
D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
I/ActivityManager( 1041): Killing 6918:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1041): failed to open /acct/uid_1000/pid_6918/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 677831730318; DSPS: 22352062; Offset : -4313493566
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 697833835622; DSPS: 23007491; Offset : -4313494000
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 717835695041; DSPS: 23662912; Offset : -4313496154
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 737837737221; DSPS: 24318338; Offset : -4313468160
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 757839698776; DSPS: 24973763; Offset : -4313490117
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 777841614341; DSPS: 25629186; Offset : -4313497290
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 797843667772; DSPS: 26284613; Offset : -4313488667
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 817845677816; DSPS: 26940039; Offset : -4313492653
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 837847340829; DSPS: 27595453; Offset : -4313477667
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 857849115352; DSPS: 28250871; Offset : -4313473007
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 877851551022; DSPS: 28906311; Offset : -4313478823
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 897853641588; DSPS: 29561740; Offset : -4313493969
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 917855725226; DSPS: 30217168; Offset : -4313485552
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 937857475113; DSPS: 30872585; Offset : -4313475193
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{91f1489 type 2 when 942456 com.android.bluetooth} when 942456
,W/bt-smp  ( 3761): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3761): Plain text(LSB ~ MSB) = 6e 29 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3761): Encrypted text(LSB ~ MSB) = 6d 79 7e 69 98 5a a8 65 2c f2 2b 76 82 75 0a 11 
W/bt-btm  ( 3761): Stopping oneshot timer
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 957860569013; DSPS: 31528047; Offset : -4313493904
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 977862645724; DSPS: 32183475; Offset : -4313492492
,I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1041): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1041): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1041): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1041): InitialState.processMessage what=4
,E/WifiStateMachine( 1041):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=981382
E/WifiStateMachine( 1041):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=981382
E/WifiStateMachine( 1041):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=981383
E/WifiConfigStore( 1041): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1041): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1041): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1041): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1041): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6892): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiNative-wlan0( 1041): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1041): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1041): RunningState{ when=-14ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2132): Read error: ssl=0xaf4d3600: I/O error during system call, Connection timed out
I/jxcore-log( 6821): Toggling radios to false
I/jxcore-log( 6821): 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/BluetoothManagerService( 1041): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1041): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@573ac8e mBinding = false
,I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1041): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2132): SSL shutdown failed: ssl=0xaf4d3600: I/O error during system call, Broken pipe
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1041): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/ConnectivityService( 1041): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiHS20( 1041): hidePasspointNotification off =false
,V/WfdStateTracker( 1949): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1041): hidePasspointNotification off =false
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1041): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=981594  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=981594  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1041):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/LocationManagerService( 1041): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1041):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/Ulp_jni ( 1041): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/BluetoothManagerService( 1041): Message: 2
D/Ulp_jni ( 1041): JNI:system_update. Event-4
,D/BluetoothManagerService( 1041): Sending off request.
D/LGBluetoothServiceAdapter( 3761): [BTUI] Precleanup
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterState( 3761): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3761): Setting state to 13
I/BluetoothAdapterState( 3761): Bluetooth adapter state changed: 12-> 13
D/WifiServiceImplEx( 1041): setWifiEnabled: false pid=6821, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1041): setWifiEnabled: false pid=6821, uid=10311
E/WifiService( 1041): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties( 3761): onBluetoothDisable()
D/BluetoothManagerService( 1041): Message: 60
D/BluetoothManagerService( 1041): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1041): Bluetooth State Change Intent: 12 -> 13
D/ConnectivityService( 1041): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1041): disableDataServiceNotify
D/DSQN    ( 1041): stop dsqn bin
I/BluetoothAdapterState( 3761): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1041):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1041): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1041):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=981628  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1041):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=981633  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1041): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1041): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1041): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1041): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1041): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1041): Disconnected - quitting
D/LocationManagerService( 1041): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1041): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1041): JNI:system_update. Event-4
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGBluetoothAPIService( 1949): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
D/WifiNetworkAgent( 1041): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1041):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1041):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/BluetoothMapService( 3761): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine( 1041):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/BluetoothMapService( 3761): STATE_TURNING_OFF
V/BluetoothMapService( 3761): Handler(): got msg=4
D/BluetoothMapService( 3761): MAP Service closeService in
I/jxcore-log( 6821): Radios toggled
I/jxcore-log( 6821): 
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/BluetoothMapMasInstance( 3761): MAP Service shutdown
E/WifiStateMachine( 1041):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/BluetoothMapMasInstance( 3761): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3761): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3761): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3761): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3761): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3761): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3761): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3761): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 3761): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3761): MAP Service closeService out
V/BtOppService( 3761): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3761): stopping Accept Thread
V/BtOppRfcommListener( 3761): close mBtServerSocket
V/BtOppRfcommListener( 3761): waiting for thread to terminate
E/BtOppRfcommListener( 3761): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/WifiHS20( 1041): hidePasspointNotification off =false
I/BtOppRfcommListener( 3761): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3761): done wait,ing for thread to terminate
,W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [SCANNING]
V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/BluetoothAdapterProperties( 3761): Scan Mode:20
D/UsbSettingsControl( 6892): [AUTORUN] getUsbConnected() : connected=true
D/BluetoothAdapterState( 3761): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6892): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6892): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6892): [AUTORUN] setTetherStatus() : status=false
D/btif_config_util( 3761): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
V/BluetoothPbapService( 3761): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3761): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3761): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3761): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3761): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0011
,W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3761): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothFtpService:RfcommSocketAcceptThread( 3761): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3761): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiStateMachine( 1041):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
V/BluetoothPbapReceiver( 3761): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3761): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3761): ***********state = 13
V/BluetoothPbapReceiver( 3761): ***********Calling start service!!!! with action = null
D/ConnectivityService( 1041): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1041): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1041): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1041): Removing idletimer
W/Settings( 1041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1041): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1041): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt( 1041): SUPPLICANT_STATE_CHANGED_ACTION
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiServerServiceExt( 1041): setSupplicantStateSCANNING
,V/NetworkPolicy( 1041): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1041): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1041): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1041): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1041): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1041):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1041):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1041):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
V/BtOppService( 3761): onDestroy
,D/LGBluetoothOppAdapter( 3761): [BTUI] LGBluetoothOppAdapter cleanup
V/BluetoothPbapService( 3761): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3761): state: 13
V/BluetoothPbapService( 3761): Pbap Service closeService in
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 6892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1041): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7674 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/WIFI    ( 1041): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1041):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGWifiP2pService( 1041): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1041): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a1e9b7c
,V/BluetoothPbapService( 3761): successfully stopped pbap service
V/BluetoothPbapService( 3761): Pbap Service closeService out
V/BluetoothPbapService( 3761): Pbap Service onDestroy
V/BluetoothPbapService( 3761): Pbap Service closeService in
V/BluetoothPbapService( 3761): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3761): [BTUI] cleanup
D/WifiScanningService( 1041): SCAN_AVAILABLE : 1
D/RttService( 1041): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1041): P2pDisablingState
D/LGWifiP2pService( 1041): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): p2p socket connection lost
D/LGWifiP2pService( 1041): P2pDisabledState
D/WifiScanningService( 1041): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1041): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1041):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1041): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1041): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2609): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1041): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1041): doBoolean: SET ps 1
D/WifiNative-wlan0( 1041): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
V/WfdStateTracker( 1949): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1949): WifiP2pState is changed : false
D/WfdsService( 1949): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1949): Set the WFDS Monitor: false
D/WifiNative-p2p0( 1041): doBoolean: TERMINATE
D/WifiHS20( 1041): hidePasspointNotification off =false
D/WifiNative-p2p0( 1041): TERMINATE: returned true
E/WifiStateMachine( 1041): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1041): useWiFiOffloading() : false
E/WifiStateMachine( 1041): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1041): hidePasspointNotification off =false
W/Settings( 1041): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1041): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1041): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothManagerService( 1041): Message: 20
D/BluetoothManagerService( 1041): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2502039a:true
,V/WfdStateTracker( 1949): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1041): WIFI_STATE_CHANGED_ACTION [0]
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WfdsMonitor( 1949): WFDS Monitor is stopped
D/WfdsService( 1949): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1949): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1949): Received on exit socket, terminate
E/CtrlSupplicant( 1949): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1949): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1949): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1949): DefaultState - msg [9445378] is not handled
,I/ActivityManager( 1041): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7692 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1041): StoppedState
D/DhcpStateMachine( 1041): StoppedState{ when=-71ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1041):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1041):  DefaultState CMD_ON_QUIT 0 0
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothManagerService( 1041): Message: 30
D/BluetoothManagerService( 1041): Message: 30
D/LocalBluetoothProfileManager( 6892): Adding local MAP profile
D/BluetoothMap( 6892): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1041): Message: 30
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothManagerService( 1041): Message: 30
D/LocalBluetoothProfileManager( 6892): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6892):  get() - isFeatureLoaded : false
E/ActivityThread( 7674): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7674): No ProfileInfo entries
I/LG Account v2.2( 7674): isEnabled: false
I/Feature ( 7674): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7674): [Lifetracker]Country: EU
I/Feature ( 7674): [Lifetracker]Operator: OPEN
I/Feature ( 7674): [Lifetracker]Ranking support: false
I/Feature ( 7674): [Lifetracker]Comfort support: false
I/Feature ( 7674): [Lifetracker]Accessory: true
I/Feature ( 7674): [Lifetracker]Health device: true
I/Feature ( 7674): [Lifetracker]Extra Pedometer: false
I/Feature ( 7674): [Lifetracker]Blood glucose device: false
I/Feature ( 7674): [Lifetracker]Device Number: 3
D/LGBluetoothUserBindClient( 6892): [BTUI] initUserBindClient
,W/ContextImpl( 6892): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6892): finishStartingService: stopping service
D/BluetoothInputDevice( 6892): Proxy object connected
D/HidProfile( 6892): Bluetooth service connected
D/BluetoothPan( 6892): BluetoothPAN Proxy object connected
D/PanProfile( 6892): Bluetooth service connected
D/BluetoothMap( 6892): Proxy object connected
D/MapProfile( 6892): Bluetooth service connected
D/BluetoothMap( 6892): getConnectedDevices()
D/BluetoothMap( 6892): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6892): [BTUI] onServiceConnected
I/PCSuite ( 7692): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGBluetoothAuthorization( 6892): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 6892): onReceive
D/LGBluetoothAuthorization( 6892): [BTUI] cancel All Notification
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1041): Killing 7035:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6892): return without doing reset settings.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/libprocessgroup( 1041): failed to open /acct/uid_10011/pid_7035/cgroup.procs: No such file or directory
,I/ActivityManager( 1041): Killing 7060:com.lge.email/u0a23 (adj 15): empty #17
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
V/BluetoothOppReceiver( 3761): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 3761): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3761): [BTUI] cancel opp active transfer file notification
W/libprocessgroup( 1041): failed to open /acct/uid_10023/pid_7060/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 3761): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3761): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3761): Ftp Service onStartCommand
V/BluetoothFtpService( 3761): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3761): Ftp Service closeService
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/BluetoothFtpService:RfcommSocketAcceptThread( 3761): Shutdown
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3761): successfully stopped ftp service
V/BluetoothSapReceiver( 3761): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3761): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3761): SapReceiver onReceive 
V/BluetoothSapReceiver( 3761): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3761):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3761): Calling SAP service start service with action = null
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothFtpService( 3761): Ftp Service onDestroy
V/BluetoothFtpService( 3761): Ftp Service closeService
V/BluetoothSapService( 3761): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3761): state: 13
V/BluetoothSapService( 3761): Stopping SAP server process
V/BluetoothSapService( 3761): Sap Service closeSapService in
V/BluetoothSapService( 3761): Close listen Socket : 
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothSapService( 3761): Close rfcomm Socket : 
V/BluetoothSapService( 3761): Close sapd  Socket : 
,V/BluetoothSapService( 3761): Sap Service closeSapService out
,V/BluetoothSapService( 3761): Sap Service onDestroy
V/BluetoothSapService( 3761): Sap Service closeSapService in
V/BluetoothSapService( 3761): Close listen Socket : 
V/BluetoothSapService( 3761): Close rfcomm Socket : 
V/BluetoothSapService( 3761): Close sapd  Socket : 
I/ActivityManager( 1041): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7721 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3761): Sap Service closeSapService out
I/PCSuite ( 7692): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7692): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ResourcesManager( 7721): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2132): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7692): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7692): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/QRemote ( 6939): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6939): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6939): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7086): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
V/FormManager( 7086): Network unavailable.
,V/FormManager( 7086): Network unavailable.
I/ActivityManager( 1041): Killing 7134:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10057/pid_7134/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3761): cleanup
,I/bt_lpm  ( 3761): LPM is already off!!!
I/bt_userial_mct( 3761): exiting userial_read_thread
D/bt_userial_mct( 3761): Leaving userial_evt_read_thread()
W/bt-btif ( 3761): ag scb idx 1 not allocated
E/bt-btif ( 3761): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3761): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3761): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3761): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3761): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3761): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3761): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3761): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3761): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3761): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3761): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3761): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3761): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3761): hw_epilog_process
D/bt_hci_bdroid( 3761): cleanup Finalizing cleanup
D/bt_userial_mct( 3761): userial_close
E/bt_userial_mct( 3761): pthread_join() FAILED result:3
I/bt_vendor( 3761): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3761): set_power 0
I/bt_vendor( 3761): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3761): bluetooth satus is on
I/bt_vendor( 3761): bt-vendor : resetting BT status
I/bt_vendor( 3761): Starting hciattach daemon
I/bt_vendor( 3761): try to set false
,I/bt_vendor( 3761): Starting hciattach daemon
I/bt_vendor( 3761): try to set false
I/bt_vendor( 3761): cleanup
I/GKI_LINUX( 3761): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3761): GKI_exit_task 0 done
I/GKI_LINUX( 3761): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3761): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3761): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3761): Stopping profile services that were post enabled
I/LGBluetoothHfpAdapter( 3761): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3761): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
D/HeadsetStateMachine( 3761): Exit Disconnected: -1
D/BluetoothHeadset( 1041): Proxy object disconnected
D/AudioService( 1041): onServiceDisconnected: Bluetooth profile: 1
,D/BluetoothHeadset( 1858): Proxy object disconnected
D/BluetoothHeadset( 1858): Proxy object disconnected
D/BluetoothHeadset( 1858): Proxy object disconnected
D/A2dpService( 3761): Received stop request...Stopping profile...
D/A2dpStateMachine( 3761): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3761): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3761): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3761): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
D/HidService( 3761): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
,D/HealthService( 3761): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
D/BluetoothA2dp( 1041): Proxy object disconnected
D/AudioService( 1041): onServiceDisconnected: Bluetooth profile: 2
D/PanService( 3761): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
D/BtGatt.DebugUtils( 3761): handleDebugAction() action=null
D/BtGatt.GattService( 3761): Received stop request...Stopping profile...
D/BtGatt.GattService( 3761): stop()
D/BtGatt.AdvertiseManager( 3761): advertise clients cleared
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
D/BluetoothMapService( 3761): Received stop request...Stopping profile...
D/BluetoothMapService( 3761): stop()
,D/BluetoothMapEmailAppObserver( 3761): deinitObservers()
D/BluetoothMapEmailAppObserver( 3761): removeReceiver()
D/BluetoothAdapterService( 3761): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7459f16
V/BluetoothMapService( 3761): Handler(): got msg=4
D/BluetoothMapService( 3761): MAP Service closeService in
D/LGBluetoothMapAdapter( 3761): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3761): MAP Service closeService out
D/BluetoothAdapterState( 3761): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3761): Setting state to 10
I/BluetoothAdapterState( 3761): Bluetooth adapter state changed: 13-> 10
D/HeadsetStateMachine( 3761): Unbinding service...
D/BluetoothManagerService( 1041): Message: 60
D/BluetoothManagerService( 1041): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1041): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1041): onBluetoothStateChange: up=false
D/HeadsetPhoneState( 3761): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3761): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3761): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3761): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3761): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3761): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3761): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothAdapterState( 3761): Entering OffState
,D/BluetoothInputDevice( 6892): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1858): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1041): onBluetoothStateChange: up=false
D/BluetoothPbap( 6892): onBluetoothStateChange: up=false
I/BluetoothA2dpServiceJni( 3761): cleanupNative
I/GKI_LINUX( 3761): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3761): GKI_exit_task 2 done
I/GKI_LINUX( 3761): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3761): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3761): Cleaning up Bluetooth GID callback object
,D/BluetoothMap( 6892): onBluetoothStateChange: up=false
W/BluetoothHealthServiceJni( 3761): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3761): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3761): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3761): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3761): Cleaning up Bluetooth PAN callback object
D/BluetoothHeadset( 1858): onBluetoothStateChange: up=false
D/BluetoothMapService( 3761): cleanup()
D/BluetoothMapService( 3761): MAP Service closeService in
D/LGBluetoothMapAdapter( 3761): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3761): MAP Service closeService out
D/BluetoothPan( 6892): onBluetoothStateChange on: false
D/BluetoothHeadset( 1858): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1041): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1041): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1041): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1041): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1041): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@573ac8e mBinding = false
D/BluetoothManagerService( 1041): Sending unbind request.
I/GKI_LINUX( 3761): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3761): GKI_exit_task 1 done
I/GKI_LINUX( 3761): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3761): cleanupNative: return from cleanup
I/art     ( 3761): --- WEIRD: removing null entry 246
W/art     ( 3761): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3761): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3761): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1041): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3761): System.exit called, status: 0
I/AndroidRuntime( 3761): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  318): 3761 died, releasing its sessions
V/AudioFlinger(  318):  pid 1858 @ 0
V/AudioFlinger(  318):  pid 3128 @ 1
V/AudioFlinger(  318):  pid 3128 @ 2
,D/LGBluetoothAPIService( 1949): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1949): Message: 101
E/LGBluetoothAPIService( 1949): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1949): Calling onBluetoothServiceDown callbacks
D/LGBluetoothUserBindClient( 6892): [BTUI] onServiceDisconnected
D/LGBluetoothAPIService( 1949): Broadcasting onBluetoothServiceDown() to 0 receivers.
I/ActivityManager( 1041): Process com.android.bluetooth (pid 3761) has died
W/ActivityManager( 1041): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1041): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 10999ms
,I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothFeatureConfig( 6892): isPrivacyLogsEnabled : true
D/LGBluetoothAPIService( 1949): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1949): Message: 2
E/LGBluetoothEventManager( 6892): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6892): [BTUI] clear device connection state
D/LGBluetoothAPIService( 1949): unbindAndFinish(): null mBinding = false
W/ContextImpl( 6892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothAdapter( 1468): 437075824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1468): 437075824: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager( 1041): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7770 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 6892): finishStartingService: stopping service
,W/ResourcesManager( 7770): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7770): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7770): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7770): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7770): Loading JNI Library
,D/BluetoothAdapterApp( 7770): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f1abc9f Instance Count = 1
,D/BluetoothAdapterApp( 7770): onCreate
D/ProfileConfigQcom( 7770): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7770): Adding HeadsetService
,D/ProfileConfigQcom( 7770): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7770): Adding A2dpService
D/ProfileConfigQcom( 7770): [BTUI] HidService is supported
D/ProfileConfigQcom( 7770): Adding HidService
D/ProfileConfigQcom( 7770): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7770): Adding HealthService
D/LGBluetoothFeatureConfig( 7770): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7770): [BTUI] PanService is supported
D/ProfileConfigQcom( 7770): Adding PanService
D/ProfileConfigQcom( 7770): [BTUI] GattService is supported
D/ProfileConfigQcom( 7770): Adding GattService
,D/ProfileConfigQcom( 7770): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7770): Adding BluetoothMapService
D/ProfileConfigQcom( 7770): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7770): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7770): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7770): ***********state = 10
V/LGMDMManagerInternal( 7770): Create singleton instance
D/LGBluetoothUserBindClient( 6892): [BTUI] onServiceConnected
D/LGBluetoothAPIServer( 7770): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7770): [BTUI] onBind()
,D/LGBluetoothAPIService( 1949): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1949): Message: 100
D/LGBluetoothAPIService( 1949): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothPermissionRequest( 6892): onReceive
D/LGBluetoothUtils( 6892): [BTUI] FileNotFound: readProperty
,D/BluetoothDiscoverableTimeoutReceiver( 6892): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 6892): return without doing reset settings.
D/LGBluetoothOppAdapter( 7770): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 7770): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7770): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7770): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7770): SapReceiver onReceive 
V/BluetoothSapReceiver( 7770): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7770):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7721): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2132): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2609): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2609): monitor socket send errors count : 1
,I/wpa_supplicant( 2609): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1949-2\x00 that cannot receive messages
,W/wpa_supplicant( 2609): USIM:  scard_deinit function
D/WifiMonitor( 1041): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1041): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1041):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=983566  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1041):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=983566  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2609): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1041): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1041): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1041): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1041):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 60 0
D/WfdsService( 1949): Supplicant Connection state is changed : false
D/WfdsService( 1949): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1949): Set the WFDS Monitor: false
D/WfdsMonitor( 1949): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1041): stopMonitoring
E/WifiStateMachine( 1041): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1041): useWiFiOffloading() : false
E/WifiStateMachine( 1041): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1949): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1823): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1041): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1041): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1041): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/PCSuite ( 7692): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7692): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7692): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6892): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6892): MCCMNC not supported: null
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7086): Network unavailable.
,W/FormManager( 7086): Network not available. Please check & try again.
,V/FormManager( 7086): Network unavailable.
,D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1041): MasterInitialState.processMessage what=3
D/ConnectivityService( 1041): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1041): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5436): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5436): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1041): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1041): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7827 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1041): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7827): onCreate
,W/AppUp4:DB( 7827):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7827):  setFingerPrint start
,I/AppUp4:DB( 7827):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7827):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7827):  SDK version = 21
I/AppUp4:DB( 7827):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7827): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7827): onReceive
,D/LgDataFeature( 7827): LgDataFeature() Constructor: none
D/LgDataFeature( 7827): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7827): Context : android.app.ReceiverRestrictedContext@2ede9c31
D/AppUp4:CustFacade( 7827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7827): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7827): begin check event
I/AppUp4:CustModeStarterReceiver( 7827): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7827): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7827): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7827): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7827): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1041): Killing 7154:com.lge.drmservice/u0a62 (adj 15): empty #17
,D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1041): failed to open /acct/uid_10062/pid_7154/cgroup.procs: No such file or directory
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1041): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7860 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7860): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7860): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7860): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7860): LgDataFeature() Constructor: none
D/LgDataFeature( 7860): LgDataFeature() Constructor Done, null
,D/eas_req ( 7860): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3128): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3128): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3128): networkInfo.isConnected() = false
,I/HubEmail( 7860): JNI_OnLoad()
I/HubEmail( 7860): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7860): registerNatives()
I/HubEmail( 7860): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7860): registerNativeMethods()
I/HubEmail( 7860): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7860): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1041): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7898 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7086): Network not available. Please check & try again.
V/FormManager( 7086): Network unavailable.
,W/Settings( 7860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7086): Network unavailable.
I/ActivityManager( 1041): Killing 7174:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10085/pid_7174/cgroup.procs: No such file or directory
,I/ActivityManager( 1041): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7922 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 7193:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10093/pid_7193/cgroup.procs: No such file or directory
,I/ActivityManager( 1041): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7939 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 7254:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/art     (  351): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 24.365ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 21.713ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 19.238ms
,W/libprocessgroup( 1041): failed to open /acct/uid_10097/pid_7254/cgroup.procs: No such file or directory
,I/art     ( 7939): Almond Protected OAT
,D/WeatherApplication( 7939): removeAccount
D/WeatherApplication( 7939): Account.length = 0
E/WeatherApplication( 7939): OPERATOR:OPEN
,D/WeatherAncestor( 7939): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:5:29
,D/Weather.Utils( 7939): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7939): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7939): 2 : This is isUpdating : false
,D/WeatherAncestor( 7939): connectivity changed - connection : true
D/WeatherService( 7939): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7939): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7939): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7939): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7939): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7939): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:5:29
,I/ActivityManager( 1041): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7957 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1041): Killing 6185:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1041): failed to open /acct/uid_10044/pid_6185/cgroup.procs: No such file or directory
,D/LGWifiP2pService( 1041): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1041): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1041):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1041):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7957): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7957): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7957): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7957): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7957): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7957): Loading: webviewchromium
,I/LibraryLoader( 7957): Time to load native libraries: 7 ms (timestamps 7092-7099)
,I/LibraryLoader( 7957): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7957): Binding Chromium to main looper Looper (main, tid 1) {2093ec52}
I/LibraryLoader( 7957): Expected native library version number "",actual native library version number ""
I/chromium( 7957): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7957): Initializing chromium process, renderers=0
,W/art     ( 7957): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7957): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7957): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7957): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  318): registerClient() client 0xb151f160, uid 10093
W/AudioManagerAndroid( 7957): Requires BLUETOOTH permission
I/Adreno-EGL( 7957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7957): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7957): Build Date: 12/12/14 금
I/Adreno-EGL( 7957): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7957): Remote Branch: 
I/Adreno-EGL( 7957): Local Patches: 
I/Adreno-EGL( 7957): Reconstruct Branch: 
,I/NSApplication( 7957): Starting up...
,I/ActivityManager( 1041): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8013 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1041): Killing 6683:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10054/pid_6683/cgroup.procs: No such file or directory
,W/ResourcesManager( 8013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2352): num queued entries: 0
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
D/PostponalbeReceiver( 6454): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7827): [onReceive] request level :IDLE....
W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/AppUp4:CustModeStarterReceiver( 7827): onReceive
,D/AppUp4:CustFacade( 7827): Context : android.app.ReceiverRestrictedContext@2ede9c31
D/AppUp4:CustFacade( 7827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7827): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7827): begin check event
I/AppUp4:CustModeStarterReceiver( 7827): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/GLSActivity( 2132): [ac] getting account id
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7860): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/GLSUser ( 2132): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3128): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) },
I/LgeMiscReceiver( 3128): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3128): networkInfo.isConnected() = false
,W/Settings( 7860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7086): Network not available. Please check & try again.
,D/WeatherAncestor( 7939): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:5:30
,D/Weather.Utils( 7939): 2 : the weather widgets(using time tick) are gone.
V/FormManager( 7086): Network unavailable.
D/Weather.Utils( 7939): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7939): 2 : This is isUpdating : false
D/WeatherAncestor( 7939): connectivity changed - connection : true
D/WeatherService( 7939): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3021a097
D/ForecastDataCache( 7939): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7939): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7939): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7939): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7939): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:5:30
V/FormManager( 7086): Network unavailable.
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1041): Explicit concurrent mark sweep GC freed 68783(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.730ms total 140.850ms
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{223cd4ae type 2 when 989162 com.google.android.gms} when 989162
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1041): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/GAV4    ( 7957): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1041): Killing 7585:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1041): failed to open /acct/uid_10010/pid_7585/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 997864058891; DSPS: 32838881; Offset : -4313483187
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1017866031542; DSPS: 33494306; Offset : -4313494073
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1037868084659; DSPS: 34149733; Offset : -4313485790
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1057870857621; DSPS: 34805184; Offset : -4313489902
,D/PowerManagerServiceEx( 1041): acquireWakeLockInternal: lock=34612288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
,V/AlarmManager( 1041): ELAPSED_WAKEUP set : Alarm{a058dba type 2 when 1066248 android} when 1066248
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1041): releaseWakeLockInternal: lock=34612288 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1077872914748; DSPS: 35460611; Offset : -4313477400
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1097874947292; DSPS: 36116038; Offset : -4313489482
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1117877004681; DSPS: 36771465; Offset : -4313476745
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1137878975558; DSPS: 37426890; Offset : -4313489667
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1157881478988; DSPS: 38082332; Offset : -4313488652
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1177883587054; DSPS: 38737761; Offset : -4313486247
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1197885634806; DSPS: 39393188; Offset : -4313483303
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/WifiController( 1041): battery changed pluggedType: 2
,D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1949): Battery Level Remaining: 100%
,D/LEDHandler( 1949): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
,I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1217887451674; DSPS: 40048608; Offset : -4313497334
,I/UsageStatsService( 1041): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1237889304530; DSPS: 40704028; Offset : -4313475636
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1257892049627; DSPS: 41359478; Offset : -4313477017
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1277893998109; DSPS: 42014902; Offset : -4313481660
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1297896148205; DSPS: 42670332; Offset : -4313467847
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1041): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1041): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1041): tsOffsetIs: Apps: 1317898273458; DSPS: 43325762; Offset : -4313478694
,TIME-OUT KILL (timeout was 1200000ms)
```
