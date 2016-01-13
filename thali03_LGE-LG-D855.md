#### Test 5590220275263c8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 238026627674; DSPS: 7940841; Offset : -4324045758
,D/AndroidRuntime( 6387): 
D/AndroidRuntime( 6387): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6387): CheckJNI is OFF
D/AndroidRuntime( 6387): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1956): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{35a3bf0d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{35a3bf0d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  338): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6407 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6387): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1866): Display #0 changed.
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{11fcf6e2 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{10ba2a73 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6407): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6407): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6407): Loading: webviewchromium
I/LibraryLoader( 6407): Time to load native libraries: 3 ms (timestamps 6441-6444)
I/LibraryLoader( 6407): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6407): Binding Chromium to main looper Looper (main, tid 1) {245fff12}
I/LibraryLoader( 6407): Expected native library version number "",actual native library version number ""
I/chromium( 6407): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6407): Initializing chromium process, renderers=0
W/art     ( 6407): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6407): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  316): registerClient() client 0xb1427240, uid 10311
,W/chromium( 6407): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6407): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6407): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a7d5b2f:true
I/Adreno-EGL( 6407): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6407): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6407): Build Date: 12/12/14 금
I/Adreno-EGL( 6407): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6407): Remote Branch: 
I/Adreno-EGL( 6407): Local Patches: 
I/Adreno-EGL( 6407): Reconstruct Branch: 
,W/chromium( 6407): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6407): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6407): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6407): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6407): CordovaWebView is running on device made by: LGE
W/art     ( 6407): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6407): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6407): Render dirty regions requested: true
I/OpenGLRenderer( 6407): Initialized EGL, version 1.4
D/OpenGLRenderer( 6407): Enabling debug mode 0
D/Atlas   ( 6407): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{d13c1b1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6407): LgDataFeature() Constructor: none
D/LgDataFeature( 6407): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16fc68df,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 6407): Timeline: Activity_idle id: android.os.BinderProxy@232250c2 time:246852
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +568ms (total +667ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{bfc7ec2 u0 com.test.thalitest/.MainActivity t4} time:246856
D/JsMessageQueue( 6407): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6407): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
D/JX-Cordova( 6407): jxcore cordova android initializing
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=898027067, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{52a8622 type 0 when 1452695777857 com.android.vending} when 1452695777857
D/[Concierge]Service( 2628): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=898027067 [*alarm*], flags=0x0
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
E/GBMv2   (  338): DFP En is all cleared set to be enabled
E/GBMv2   (  338): Set value is all cleared set the max
I/GBMv2   (  338): DFP Enabled. Ignore VFP set
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5783): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5783): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5783): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
D/HeadsetStateMachine( 3723): Disconnected process message: 10, size: 0
D/LEDHandler( 1956): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1956): Battery Level Remaining: 100%
D/LEDHandler( 1956): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/jxcore-log( 6407): Initializing JXcore engine
W/jxcore-log( 6407): JXcore engine is ready
W/jxcore-log( 6407): Starting JXcore engine
I/art     ( 6407): Background sticky concurrent mark sweep GC freed 120949(11MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.205ms total 105.877ms
W/.test.thalitest( 6407): type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[8437]" dev="sockfs" ino=8437 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6407): type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6407): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[9789]" dev="sockfs" ino=9789 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6407): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6407): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[30616]" dev="sockfs" ino=30616 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6407): Platform android
W/jxcore-log( 6407): 
W/jxcore-log( 6407): Process ARCH arm
W/jxcore-log( 6407): 
,I/jxcore-log( 6407): JXcore Cordova bridge is ready!
I/jxcore-log( 6407): 
,W/jxcore-log( 6407): JXcore engine is started
I/jxcore-log( 6407): Toggling radios to true
I/jxcore-log( 6407): 
,D/BluetoothAdapter( 6407): enable(): BT is already enabled..!
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6407, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6407, uid=10311
,E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1030): disconnect pid=6407, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1030):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1030): setLastSelectedConfiguration -1
E/WifiNative: ( 1030): [249,840,560 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,D/WifiNative-wlan0( 1030): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1030): reconnect pid=6407, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6407): Radios toggled
I/jxcore-log( 6407): 
I/jxcore-log( 6407): My device name is: LGE-LG-D855
I/jxcore-log( 6407): 
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1030): DISCONNECT: returned true
D/Tethering( 1030): InitialState.processMessage what=4
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1030): [249,883,563 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=249891
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=249893  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6513 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=249918  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=249920  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=249920  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6513): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6513): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6513): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6513): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6513): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6513): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6541 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5657:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5657/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6513): LgDataFeature() Constructor: none
,D/LgDataFeature( 6513): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6567 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1030): Killing 5677:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5677/cgroup.procs: No such file or directory
,W/ResourcesManager( 6567): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6567): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6567): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6567): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6567): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6567): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6567): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6567): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6567): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/QRemote ( 6567): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6567): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6541): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6541): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6541): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6567): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6567): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6567): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6567): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6567): LgDataFeature() Constructor: none
D/LgDataFeature( 6567): LgDataFeature() Constructor Done, null
,V/SoundPool( 6567): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6567): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6567): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6567): doLoad: loading sample sampleID=1
I/QRemote ( 6567): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6567): Start decode
V/MediaPlayer[Native]( 6567): decode(31, 10857164, 17813)
,V/MediaPlayerService(  316): decode(24, 10857164, 17813)
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
V/AudioCache(  316): notify(0xb1432400, 8, 0, 0)
V/AudioCache(  316): ignored
D/QRemote ( 6567): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
E/QRemote ( 6567): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/UEI.SmartControl( 6104): QS Service created
V/LGMDMManager( 6567): Create singleton instance
I/UEI.SmartControl( 6104): Service initServices...
D/UEI.SmartControl( 6104): QS start get config
,V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
,V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
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
V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e20 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyn,cCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb1432400, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1432400, 1, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978144
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb119a100 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1432400, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae806000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae807000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae808000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae809000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80a000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80b000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80c000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80d000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80e000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae80f000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae810000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae811000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae812000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae813000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae814000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae815000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae816000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae817000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae818000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae819000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81a000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81b000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81c000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81d000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81e000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae81f000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae820000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae821000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae822000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae823000, 0xb57f0000, 4096)
,V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae824000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae825000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae826000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae827000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae828000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae829000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82a000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82b000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82c000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82d000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82e000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae82f000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae830000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae831000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae832000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae833000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae834000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae835000, 0xb57f0000, 4096)
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae836000, 0xb57f0000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  316): write(0xb57f0000, 4096)
V/AudioCache(  316): memcpy(0xae837000, 0xb57f0000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57f0000, 280)
V/AudioCache(  316): memcpy(0xae838000, 0xb57f0000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1432400, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb1432400, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1432400, 8, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb119a100 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434880 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
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
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 6567): close(31)
V/SoundPool( 6567): pointer = 0x9ffb8000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 6567): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6567): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6567): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3982
I/UEI.SmartControl( 6104): Supports setup maps: true
,D/UEI.SmartControl( 6104): QS start statue = true Error code = 0
I/UEI.SmartControl( 6104): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6104): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6104): ### init IR Blaster...
D/serial_port( 6104): Configuring serial port
E/UEI.SmartControl( 6104): UEIBLaster setting for 616
I/UEI.SmartControl( 6104): Setting serial record hearder size = 2
I/UEI.SmartControl( 6104): configuring settings for MAXQ616
I/UEI.SmartControl( 6104): Get version...
D/UEI.SmartControl( 6104): serial port data available: 21
,D/UEI.SmartControl( 6104): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6104): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6104): QS saving settings...
,D/UEI.SmartControl( 6104): IR Blaster version: 25672567
D/UEI.SmartControl( 6104): serial port data available: 4
,W/ContextImpl( 6104): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6104): Services init done
,D/UEI.SmartControl( 6104): QS Service init finished
D/UEI.SmartControl( 6104): QS Service version name: 2.1.91
D/UEI.SmartControl( 6104): QS Service version code: 201091
D/UEI.SmartControl( 6104): Service requested: Control
I/UEI.SmartControl( 6104): Device manager: loading config....
D/UEI.SmartControl( 6104): ----------- loading internal config...
I/QRemote ( 6567): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6104): Internal service binding...
I/UEI.SmartControl( 6104): ------ IControl API: 11
D/UEI.SmartControl( 6104): File observer start...
E/UEI.SmartControl( 6104): IR Port is disabled: false
D/UEI.SmartControl( 6104): Starting file observer...
I/UEI.SmartControl( 6104): Registering callback...
I/UEI.SmartControl( 6104): ------ IControl API: 19
,I/UEI.SmartControl( 6104): Registering Services Ready callback...
E/UEI.SmartControl( 6104): Loading SETTINGS...
D/UEI.SmartControl( 6104): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6104): Notify AllClients services are ready: 0
,I/QRemote ( 6567): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6567): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6567): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6567): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6567): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6104): ------ IControl API: 8
D/UEI.SmartControl( 6104): -----service ready thread exits
D/QRemote ( 6567): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6567): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6567): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6567): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6567): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6567): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6567): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6567): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6567): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6567): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6567): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452695792631]
D/QRemote ( 6567): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1030): Killing 6087:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 6567): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6087/cgroup.procs: No such file or directory
,V/QRemote ( 6567): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6567): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6567): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2720): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3311 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3311 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3311 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3311 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=251991  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=252011  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2720): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=252091  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=252092  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6513): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6513): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6513): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 2720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsControl( 6513): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : errorList=[]
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6513): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6513): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6513): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=252107
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=252108
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=252108
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=252108
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=252109
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=252109  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=252119  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=252119  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=252120  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=252121
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=252121
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
,D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true,
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=252190  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=252191  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=252191  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=252193  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=252194  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=252195  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2720): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2720): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@75e287e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@75e287e target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
,D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6650): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6650): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6650): version 5.5.6 starting
,E/dhcpcd  ( 6650): get_duid: m
D/dhcpcd  ( 6650): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6650): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6650): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6650): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6650): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6650): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6650): wlan0: sending REQUEST (xid 0x1e1297), next in 4.49 seconds
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6650): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6650): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6650): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6650): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6650): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6650): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6650): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6650): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6650): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2720): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2720): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/DhcpStateMachine( 1030): RunningState
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1956): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
,D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6697): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dsqn    ( 6697): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 6697): DSQN ssw
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org succeed
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
,D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6567): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6541): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/PCSuite ( 6541): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 6567): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6567): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6567): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDataListener(  311): argv[0]=dsqncommand
,D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
I/PCSuite ( 6541): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6541): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6513): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 14:36:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452695795567], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452695795551]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/ConnectivityService( 1030): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 6513): MCCMNC not supported: null
D/QRemote ( 6567): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6567): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6567): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6567): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6567): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1452695795289 (Wed Jan 13 15:36:35 GMT+01:00 2016) reference: 254370 certainty: 39 system time offset: -332
,D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
,I/rmt_storage(  309): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  309): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  309): wakelock acquired: 1, error no: 42
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  309): 
,I/rmt_storage(  309): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  897): [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/UEI.SmartControl( 6104): Internal timer expired: 4
D/UEI.SmartControl( 6104): unbind internal service
,D/serial_port( 6104): close(fd = 24)
,I/UEI.SmartControl( 6104): Serial port is closed.
,I/jxcore-log( 6407): Test app app.js loaded
I/jxcore-log( 6407): 
,I/chromium( 6407): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6407): 
,I/chromium( 6407): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 6407): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6407): --= Surplus to requirements =--
I/jxcore-log( 6407): 
I/jxcore-log( 6407): ****TEST TOOK:  ms ****
I/jxcore-log( 6407): 
I/jxcore-log( 6407): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6407): 
,I/chromium( 6407): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6407): 
,D/AndroidRuntime( 6718): 
D/AndroidRuntime( 6718): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6718): CheckJNI is OFF
D/AndroidRuntime( 6718): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 6407:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,W/PackageSettings( 1030): Skipping PackageSetting{19e05c58 com.example.hello/10319} due to missing metadata
,I/WindowState( 1030): WIN DEATH: Window{d13c1b1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{d13c1b1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{bfc7ec2 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
,W/ActivityManager( 1030): Spurious death for ProcessRecord{2bbbacfb 6407:com.test.thalitest/u0a311}, curProc for 6407: null
I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{bfc7ec2 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{bfc7ec2 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{20254d30 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{3086ada9 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2083): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2083): [Launcher.java:903:onResume()]onResume
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,D/LIA_MrGDBLogger_PackageInfoDetector( 2747): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/NetworkMonitor( 5363): type=WIFI subType= reason=null isConnected=true
,E/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2027): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 2083): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1917): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2083): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2083): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2083): [Launcher.java:1114:onPause()]onPause
W/System.err( 4372): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4372): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4372): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4372): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4372): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4372): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4372): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4372): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4372): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4372): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/PostponalbeReceiver( 6031): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/art     ( 4423): Explicit concurrent mark sweep GC freed 16864(941KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 441us total 152.526ms
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1c27a9ad type 2 when 256826 android} when 256826
,D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/ActionManagerService( 1917): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2083): , create_time: 1430558575574
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2083): , create_time: 1430558575600
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2083): , create_time: 1452175675684
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/SplitUIManager( 1883): split_name #11 / not available #0
D/SplitUIService( 1883): removed split : 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6750 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/KeyguardModel( 1461): handleShortcutListChanged...
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 58139(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 6.477ms total 231.606ms
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/WallpaperManager( 2083): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
E/GpsLocationProvider( 1030): No APN found to select.
D/AlarmManagerService( 1030): Setting time of day to sec=1452695798
W/AlarmManagerService( 1030): Unable to set rtc to 1452695798: Invalid argument
I/art     ( 1030): WaitForGcToComplete blocked for 250.518ms for cause Explicit
,D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
,I/[SystemUI]Clock( 1461): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2747): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2747): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-13 15:36:38...... Request
I/LIA_Informant_Tips_LogTracer( 2747): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 143, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2747): DateInfo : SmartTips Total Working Day Count = 143
D/LIA_Informant_Tips_DateChangeManager( 2747): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 2747): DateInfo : Last Date Check Time = 2016-01-13 15:36:38
I/LgeClockWidgetControlView( 1461): time changed, timezoneChanged : false
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
I/SecureClockService( 1956): Intent.ACTION_TIME_CHANGED 
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16fc68df,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/administrator( 1030): Handling package changes for user 0
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
,D/KeyguardModel( 1461): handleShortcutListChanged...
I/ThermalEngine(  332): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3112): Thermal-Lib-Client: Client request sent
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          displayName: Music
,D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3723): [BTUI] [-] updateMediaPlayerInfo
I/AppUp4:AppBoxCP( 6750): onCreate
W/AppUp4:DB( 6750):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6750):  setFingerPrint start
I/AppUp4:DB( 6750):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6750):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6750):  SDK version = 21
I/AppUp4:DB( 6750):  beforefinger == newfinger no write in DB
,I/[LGHome]EVENT( 2083): [Launcher.java:5349:onStop()]onStop
D/AppUp4:AppBoxApplication( 6750): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6750): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6750): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6750): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6750): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6750): onReceive
D/LgDataFeature( 6750): LgDataFeature() Constructor: none
D/LgDataFeature( 6750): LgDataFeature() Constructor Done, null
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AppUp4:CustFacade( 6750): Context : android.app.ReceiverRestrictedContext@c1088e0
D/AppUp4:CustFacade( 6750): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6750): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6750): begin check event
I/AppUp4:CustModeStarterReceiver( 6750): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6750): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6750): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6750): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6750): handleAsyncCustNotification do not startCustService
,D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3329): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2083): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=13 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 13
V/DownloadManager( 3329): DownloadService onCreate
I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 13
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/LGDMClient( 4142): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4142): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3329): in removeSpuriousFiles
V/DownloadManager( 3329): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3329): created cursor android.database.sqlite.SQLiteCursor@1e1f476c on behalf of 3329
I/LGDMClient( 4142): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3329): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3329): in trimDatabase
V/DownloadManager( 3329): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3329): created cursor android.database.sqlite.SQLiteCursor@49c8135 on behalf of 3329
D/LGDMClient( 4142): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6779 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{38a42b73 u0 com.lge.launcher2/.Launcher t3} time:257824
V/DownloadManager( 3329): DownloadService onStartCommand
V/DownloadManager( 3329): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/[Concierge]Service( 2628): onStartCommand(). Type : 9
,I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3329): created cursor android.database.sqlite.SQLiteCursor@b50f73b on behalf of 3329
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
E/LGDMClient( 4142): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4142): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
D/LGDMClient( 4142): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
V/DownloadManager( 3329): processing inserted download 1
,V/DownloadManager( 3329): processing inserted download 4
V/DownloadManager( 3329): processing inserted download 7
V/DownloadManager( 3329): processing inserted download 8
V/DownloadManager( 3329): processing inserted download 9
V/DownloadManager( 3329): processing inserted download 10
V/DownloadManager( 3329): processing inserted download 16
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/DownloadManager( 3329): processing inserted download 17
V/DownloadManager( 3329): processing inserted download 18
V/DownloadManager( 3329): processing inserted download 21
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
V/DownloadManager( 3329): DownloadService onDestroy
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 13974(708KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.664ms total 280.595ms
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/ResourcesManager( 6779): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6779): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 6779): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6779): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/[Concierge]WidgetView( 2083): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2628): onStartCommand(). Type : 8
D/[Concierge]Service( 2628): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2628): Update widget ID : 11
D/[Concierge]WidgetView( 2083): change position of spinner
,I/[Concierge]WidgetView( 2083): initWebView(). Time : 1452695798790
D/[Concierge]Service( 2628): onStartCommand(). Type : 0
I/ActivityManager( 1030): Killing 5705:com.android.gallery3d/u0a27 (adj 15): empty #17
D/AndroidRuntime( 6718): Shutting down VM
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5705/cgroup.procs: No such file or directory
I/LGEmail ( 6779): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[Concierge]WebView( 2083): Return exist ConciergeWebView. Reuse : 1056750098
D/[Concierge]WidgetView( 2083): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2083): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2fffd2e8
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/LGEmail ( 6779): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2083): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2083): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourceType( 6779): No package identifier when getting value for resource number 0x00000000
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6800 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/[Concierge]WidgetView( 2083): Widget kill message received. Destory myself. My : 1452695570142, New one : 1452695798790
D/[Concierge]WidgetView( 2083): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2083): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/LgDataFeature( 6779): LgDataFeature() Constructor: none
D/LgDataFeature( 6779): LgDataFeature() Constructor Done, null
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 258027502093; DSPS: 8596230; Offset : -4324059553
I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6819 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/VacuumService( 2127): Vacuum at: now=1452695798948 tag=VacuumService
I/GoogleURLConnFactory( 2127): Using platform SSLCertificateSocketFactory
,W/Uploader( 2127): No account for auth token provided
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
,I/Timeline( 2083): Timeline: Activity_idle id: android.os.BinderProxy@2de693 time:258120
,I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6842 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
I/AppConfig( 6819): Total System Memory = 2995761152
,D/SystemHelper( 6819): region [EU], country [EU], operator [OPEN], sub-operator []
I/ReaderUtils( 6800): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/DriveInitializer( 2325): Background init thread started
D/eas_req ( 6779): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6869 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,W/GAV2    ( 6800): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Auth.Api.Credentials( 2325): [CredentialSyncAdapter] Unknown sync event.
,I/HubEmail( 6779): JNI_OnLoad()
I/HubEmail( 6779): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6779): registerNatives()
I/HubEmail( 6779): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6779): registerNativeMethods()
I/HubEmail( 6779): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6779): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2325): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/chromium( 2083): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/art     ( 2127): Explicit concurrent mark sweep GC freed 23493(1335KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.074ms total 29.624ms
W/FileUtils( 2325): Failed to chmod(/data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 2325): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml
I/BooksApp( 6800): Created application version: 3.2.35 (30235)
E/SQLiteLog( 2325): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
W/DriveInitializer( 2325): Awaiting to be initialized
,I/ActivityManager( 1030): Killing 5988:com.android.defcontainer/u0a4 (adj 15): empty #17
E/DocListDatabase( 2325): Failed to delete from FileContent112
E/DocListDatabase( 2325): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 2325): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 2325): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/DocListDatabase( 2325): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 2325): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 2325): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/DocListDatabase( 2325): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 2325): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 2325): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 2325): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 2325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 2325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 2325): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 2325): FATAL EXCEPTION: pool-11-thread-1
E/AndroidRuntime( 2325): Process: com.google.android.gms, PID: 2325
E/AndroidRuntime( 2325): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2325): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2325): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2325): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2325): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2325): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2325): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 2325): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 2325): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 2325): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 2325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2325): 	at java.lang.Thread.run(Thread.java:818)
I/GBoardtInterface( 2083): onReloaded()
,I/GBoardWebViewClient( 2083): onPageFinished url:file:///android_asset/www/main.html
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,W/Settings( 6779): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/BoardContentProvider( 2747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/Process ( 2325): Sending signal. PID: 2325 SIG: 9
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5988/cgroup.procs: No such file or directory
W/Settings( 6779): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/BoardContentProvider( 2747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
E/lowmemorykiller(  276): Error writing /proc/2325/oom_score_adj; errno=22
,E/DropBoxManagerService( 1030): Can't write: system_app_crash
E/DropBoxManagerService( 1030): java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1030): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1030): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1030): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1030): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1030): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1030): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1030): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1030): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1030): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1030): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1030): 	... 5 more
E/JavaBinder( 1030): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1030): Scheduling restart of crashed service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService in 1000ms
I/LgeMiscReceiver( 3284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3284): networkInfo.isConnected() = true
,D/PhoneState( 3284): setPdpRejectCasuse : false
D/ActionManagerService( 1917): notifyUserLog: 1000001
I/BooksSync( 6800): Starting books sync
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2747): onEvent() : ACTION_BOARD_ENABLED
D/DelayedSyncController( 6842): Delaying sync.
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
W/GmsClient( 6800): service died
E/SQLiteDatabase( 6869): Failed to open database '/data/data/com.lge.formmanager/databases/form_manager.db'.
E/SQLiteDatabase( 6869): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.data.MyProvider.getSQLiteDatabase(MyProvider.java:94)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.data.MyProvider.insert(MyProvider.java:45)
E/SQLiteDatabase( 6869): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6869): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.reserveNewSchedule(FormUpdatedTimeChecker.java:161)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.onNetworkStateChanged(FormUpdatedTimeChecker.java:140)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.execute(FormUpdatedTimeChecker.java:67)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.formhandler.AbstractChainableTask.onHandle(AbstractChainableTask.java:14)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.formhandler.AbstractChainableTask.onHandle(AbstractChainableTask.java:17)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.FormService$FormHandlerThread.call(FormService.java:117)
E/SQLiteDatabase( 6869): 	at com.lge.formmanager.FormService$FormHandlerThread.call(FormService.java:92)
E/SQLiteDatabase( 6869): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6869): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6869): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6869): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6914 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/System.err( 6869): java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6869): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
W/System.err( 6869): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
W/System.err( 6869): 	at com.lge.formmanager.FormService.onHandleIntent(FormService.java:59)
W/System.err( 6869): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6869): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6869): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 6869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 6869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 6869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 6869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 6869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 6869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 6869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 6869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 6869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 6869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 6869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 6869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 6869): 	at com.lge.formmanager.data.MyProvider.getSQLiteDatabase(MyProvider.java:94)
W/System.err( 6869): 	at com.lge.formmanager.data.MyProvider.insert(MyProvider.java:45)
W/System.err( 6869): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
W/System.err( 6869): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
W/System.err( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.reserveNewSchedule(FormUpdatedTimeChecker.java:161)
W/System.err( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.onNetworkStateChanged(FormUpdatedTimeChecker.java:140)
W/System.err( 6869): 	at com.lge.formmanager.formhandler.FormUpdatedTimeChecker.execute(FormUpdatedTimeChecker.java:67)
W/System.err( 6869): 	at com.lge.formmanager.formhandler.AbstractChainableTask.onHandle(AbstractChainableTask.java:14)
W/System.err( 6869): 	at com.lge.formmanager.formhandler.AbstractChainableTask.onHandle(AbstractChainableTask.java:17)
W/System.err( 6869): 	at com.lge.formmanager.FormService$FormHandlerThread.call(FormService.java:117)
W/System.err( 6869): 	at com.lge.formmanager.FormService$FormHandlerThread.call(FormService.java:92)
W/System.err( 6869): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6869): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6869): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6869): 	at java.lang.Thread.run(Thread.java:818)
,V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
I/art     (  342): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 202us total 9.290ms
I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.896ms
,I/ActivityManager( 1030): Process com.google.android.gms (pid 2325) has died
W/ActivityManager( 1030): Scheduling restart of crashed service com.google.android.gms/.drive.metadata.sync.syncadapter.SyncAdapterService in 10935ms
W/ActivityManager( 1030): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20935ms
W/ActivityManager( 1030): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30935ms
D/ActionManagerService( 1917): notifyUserLog: 1000001
I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.085ms
V/BoardContentProvider( 2747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2747): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2747): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2747): onSettingEvent() : GBoard On - add scheduler - 0

```
