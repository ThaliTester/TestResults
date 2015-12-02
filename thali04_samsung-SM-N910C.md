#### Test 50388019193a02f_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 269, CUR = 48
--------- beginning of main
D/AndroidRuntime(11822): 
D/AndroidRuntime(11822): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11822): CheckJNI is OFF
D/AndroidRuntime(11822): readGMSProperty: start
D/AndroidRuntime(11822): readGMSProperty: already setted!!
D/AndroidRuntime(11822): readGMSProperty: end
D/AndroidRuntime(11822): addProductProperty: start
E/AffinityControl(11822): AffinityControl: registerfunction enter
D/AndroidRuntime(11822): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3523): mDVFSHelper.acquire()
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (11840): MountEmulatedStorage()
I/libpersona(11840): KNOX_SDCARD checking this for 10446
E/Zygote  (11840): v2
I/libpersona(11840): KNOX_SDCARD not a persona
I/SELinux (11840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11840 uid=10446 gids={50446, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (11840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11840): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11822): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11840): TimaSignature is unavailable
D/ActivityThread(11840): Added TimaKeyStore provider
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6272): updateVisibility : ActivityRecord{38f0d05d token=android.os.BinderProxy@3d0eadc6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(11840): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/WebViewFactory(11840): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11840): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11840): Loading: webviewchromium
I/LibraryLoader(11840): Time to load native libraries: 4 ms (timestamps 5106-5110)
I/LibraryLoader(11840): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11840): Binding Chromium to main looper Looper (main, tid 1) {1bc755c4}
I/LibraryLoader(11840): Expected native library version number "",actual native library version number ""
I/chromium(11840): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11840): Initializing chromium process, renderers=0
W/art     (11840): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11840): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11840): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11840): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5702): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5702): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium(11840): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11840): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11840): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11840): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11840): CordovaWebView is running on device made by: samsung
,W/art     (11840): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11840): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11840): performCreate Call secproduct feature valuefalse
D/Activity(11840): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11840): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2853): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11840): Initialized EGL, version 1.4
,I/OpenGLRenderer(11840): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278893808 
,D/OpenGLRenderer(11840): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11840): Enabling debug mode 0
,D/mali_winsys(11840): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11840): updateVisibility : ActivityRecord{50db7f4 token=android.os.BinderProxy@28da47fb {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{1cc6b5f5 u0 com.example.hello/.MainActivity t26} time:235592
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 33788(2MB) AllocSpace objects, 24(384KB) LOS objects, 24% free, 49MB/65MB, paused 3.785ms total 180.114ms
,W/IInputConnectionWrapper(11840): showStatusIcon on inactive InputConnection
I/Timeline(11840): Timeline: Activity_idle id: android.os.BinderProxy@28da47fb time:235782
,I/chromium(11840): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(11840): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium(11840): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11840): 
,D/JsMessageQueue(11840): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11840): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360016128
D/JX-Cordova(11840): jxcore cordova android initializing
,W/jxcore-log(11840): Initializing JXcore engine
W/jxcore-log(11840): JXcore engine is ready
,W/jxcore-log(11840): Starting JXcore engine
,E/auditd  ( 4613): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11840): Platform android
W/jxcore-log(11840): 
W/jxcore-log(11840): Process ARCH arm
W/jxcore-log(11840): 
,I/jxcore-log(11840): JXcore Cordova bridge is ready!
I/jxcore-log(11840): 
W/jxcore-log(11840): JXcore engine is started
,E/jxcore-log(11840): >> samsung-SM-N910C
E/jxcore-log(11840): 
,I/jxcore-log(11840): Total memory 2970812416
I/jxcore-log(11840): 
,I/jxcore-log(11840): Free memory 198152192
I/jxcore-log(11840): 
I/jxcore-log(11840): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11840): 
I/jxcore-log(11840): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11840): 
,I/jxcore-log(11840): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11840): 
,I/jxcore-log(11840): Size 1440 2560
I/jxcore-log(11840): 
,I/jxcore-log(11840): Screen Brightness 134
I/jxcore-log(11840): 
,E/jxcore-log(11840): Dummy Error Log.
E/jxcore-log(11840): 
,I/jxcore-log(11840): getBuffer is called!!!!
I/jxcore-log(11840): 
,D/BluetoothAdapter(11840): disable()
,D/SettingsProvider( 3523): name = bluetooth_on
,D/BluetoothAdapterState( 5702): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5702): Setting state to 13
I/BluetoothAdapterState( 5702): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5702): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5702): updateAdapterState state is 13
,D/BluetoothAdapterService( 5702): Autoconnection is available 
,D/BluetoothAdapterService( 5702): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 5702): terminating service from this receiver
,D/BluetoothAdapterProperties( 5702): onBluetoothDisable()
,D/SecContentProvider( 3523): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothPbapService( 5702): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 5702): close() in, this: android.bluetooth.BluetoothSocket@47d5316, channel: 19, state: LISTENING
,D/BluetoothSocket( 5702): close() this: android.bluetooth.BluetoothSocket@47d5316, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ec18af9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31b14497mSocket: android.net.LocalSocket@f2a6684 impl:android.net.LocalSocketImpl@2e620e6d fd:FileDescriptor[72]
,D/BluetoothSocket( 5702): Closing mSocket: android.net.LocalSocket@f2a6684 impl:android.net.LocalSocketImpl@2e620e6d fd:FileDescriptor[72]
,I/BluetoothAdapterState( 5702): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5702): Scan Mode:20
,D/BluetoothAdapterState( 5702): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 5702): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5702): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 5702): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 5702): cmd socket is not created
,D/btif_config_util( 5702): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 5702): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 5702): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5702): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x001b not found for deregistration
,D/BluetoothPbap( 8823): Proxy object disconnected
,D/PbapServerProfile( 8823): Bluetooth service disconnected
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 3523): [BT Setting State] State =13
,D/BluetoothTile( 3694):  onBluetoothStateChange:
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService( 3523): New client listening to asynchronous messages
,I/SamsungIME( 4465): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,I/WifiManager(11840): packageName : com.example.hello
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,V/BluetoothEventManager( 8823): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService( 3523): setWifiEnabled: false pid=11840, uid=10446
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3523): name = wifi_on
D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
,W/ContextImpl( 8823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
,I/jxcore-log(11840): ****TEST TOOK:  5162  ms ****
I/jxcore-log(11840): 
,I/jxcore-log(11840): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11840): 
I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,V/[CarModeFW](11306): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/BluetoothSocket( 5702): close() in, this: android.bluetooth.BluetoothSocket@11bb9333, channel: 5, state: LISTENING
D/DockEventReceiver( 8823): finishStartingService: stopping service
D/BluetoothSocket( 5702): close() this: android.bluetooth.BluetoothSocket@11bb9333, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2269e09f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2966f0mSocket: android.net.LocalSocket@3c9e2469 impl:android.net.LocalSocketImpl@10a3aeee fd:FileDescriptor[74]
D/BluetoothSocket( 5702): Closing mSocket: android.net.LocalSocket@3c9e2469 impl:android.net.LocalSocketImpl@10a3aeee fd:FileDescriptor[74]
,I/BtOppRfcommListener( 5702): stopping Accept Thread
D/BluetoothSocket( 5702): close() in, this: android.bluetooth.BluetoothSocket@2f122f8f, channel: 12, state: LISTENING
D/BluetoothSocket( 5702): close() this: android.bluetooth.BluetoothSocket@2f122f8f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c14a031, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cd6021cmSocket: android.net.LocalSocket@96b9e25 impl:android.net.LocalSocketImpl@29fcbfa fd:FileDescriptor[79]
D/BluetoothSocket( 5702): Closing mSocket: android.net.LocalSocket@96b9e25 impl:android.net.LocalSocketImpl@29fcbfa fd:FileDescriptor[79]
I/BtOppRfcommListener( 5702): BluetoothSocket listen thread finished
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2849): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2849): ifc_reset_connections failed on iface wlan0 for address 192.168.1.113/24 (Unknown error -1)
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine( 3523): scanCount==0 - aborting
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,E/WifiStateMachine( 3523): [1,449,078,613,704 ms] noteScanEnd no scan source
,D/WifiP2pService( 3523): InactiveState{ what=131204 }
D/BluetoothNotiBroadcastReceiver( 8823): onReceive
D/WifiP2pService( 3523): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 3523): sending p2p connection changed broadcast: FAILED
,D/WifiScanningService( 3523): SCAN_AVAILABLE : 1
,D/WifiScanningService( 3523): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3523): SCAN_AVAILABLE : 1
,D/RttService( 3523): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3523): onP2pDisconnected
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
,D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService( 3523): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 3523): P2pDisablingState
,D/WifiP2pService( 3523): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 3523): p2p socket connection lost
,D/WifiP2pService( 3523): P2pDisabledState
,E/WifiStateMachine( 3523): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3523): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3523): disconnect
D/WifiDisplayController( 3523): updateConnection
,D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3523): onP2pDisconnected
D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  ( 3523): do suspend true
,D/AllShareCastTile( 3694): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 3523): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3523): DefaultState{ what=143375 }
,D/AllShareCastTile( 3694): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/CommandListener( 2849): Clearing all IP addresses on wlan0
,D/AuthorizationBluetoothService( 5558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
,E/WifiStateMachine( 3523): stopping supplicant
,D/ConnectivityManager.CallbackHandler( 6892): CM callback handler got msg 524292
I/wpa_supplicant( 3833): p2p0: State: DISCONNECTED -> DISCONNECTED
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/WifiStateMachine( 3523): setWifiState: disabling
,D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 3985): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,W/bt-l2cap( 5702): HC lib lpm enable=0 return 0
W/bt-l2cap( 5702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5702): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5702): ag scb idx 1 not allocated
W/bt-btif ( 5702): ag scb idx 2 not allocated
E/bt-btif ( 5702): BTA AG is already disabled, ignoring ...
D/bt_userial( 5702): RX termination
W/bt_userial( 5702): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5702): Leaving userial_read_thread()
D/bt_userial( 5702): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 5702): hw_epilog_process
I/bt_userial_vendor( 5702): device fd = 65 close
I/GKI_LINUX( 5702): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 5702): GKI_exit_task 0 done
I/GKI_LINUX( 5702): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5702): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5702): isSecureModeOn:false
D/BluetoothAdapterService( 5702): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.gatt.GattService
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/BtGatt.DebugUtils( 5702): handleDebugAction() action=null
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 5702): Received stop request...Stopping profile...
D/BtGatt.GattService( 5702): stop()
,D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
E/ConnectivityService( 3523): updateNetworkInfo()
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/BtGatt.AdvertiseManager( 5702): advertise clients cleared
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(0)
D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/HotspotTile( 3694): onReceive : 0, 0
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
D/StatusBar.NetworkController( 3694): updateDataNetType()
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 5702): Received stop request...Stopping profile...
,V/NetworkStats( 3523): performPollLocked() took 12ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,I/Hs20UtilService( 4111): Starting #8
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.hdp.HealthService
,I/Hs20UtilService( 4111): Message received 5007
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 1
,D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/HeadsetProfile( 8823): Bluetooth service disconnected
W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.pan.PanService
,D/NearbySettings( 8823): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8823): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8823): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8823): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5702): Not skipping com.android.bluetooth.map.BluetoothMapService
,V/NearbySettings( 8823): DMSUtil.isNetworkConnected - flag-null, state-null
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5702): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5702): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5702): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5702): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5702): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/BluetoothAdapterService( 5702): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 5702): Received stop request...Stopping profile...
V/Avrcp   ( 5702): doQuit
D/A2dpStateMachine( 5702): Exit Disconnected: -1
I/wpa_supplicant( 3833): Blacklist: Clear (all) 
,D/BluetoothAdapterState( 5702): Stopping profile services that were post enabled
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8823): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8823): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8823): MountReceiver.mPrefHandler - 7002
D/Avrcp   ( 5702): Unregistering previous receiver
,D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,D/BluetoothA2dp( 3523): Proxy object disconnected
D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothA2dp( 8823): Proxy object disconnected
D/A2dpProfile( 8823): Bluetooth service disconnected
,D/BluetoothA2dp( 5025): Proxy object disconnected
D/HidService( 5702): Received stop request...Stopping profile...
D/HidService( 5702): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5702): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5702): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5702): Cleaning up Bluetooth GID callback object
,D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,D/BluetoothInputDevice( 8823): Proxy object disconnected
D/HidProfile( 8823): Bluetooth service disconnected
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5702): Profile still running: com.android.bluetooth.hid.HidService
I/SignOutReceiver(11460): NETWORK_STATE_CHANGED_ACTION
,D/HealthService( 5702): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,W/BluetoothHeadsetServiceJni( 5702): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5702): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 5702): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,D/NearbySettings( 8823): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/wpa_supplicant( 3833): p2p0: CTRL-EVENT-TERMINATING 
,V/NearbySettings( 8823): DMSUtil.isNetworkConnected - flag-null, state-null
,D/BluetoothPan( 3523): BluetoothPAN Proxy object disconnected
,I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothMapService( 5702): Received stop request...Stopping profile...
,I/NearbySettings( 8823): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8823): MountReceiver.onReceive - Set preference state off
I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
V/NearbySettings( 8823): MountReceiver.mPrefHandler - 7002
D/BluetoothPan( 8823): BluetoothPAN Proxy object disconnected
D/PanProfile( 8823): Bluetooth service disconnected
I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11939): MountEmulatedStorage()
E/Zygote  (11939): v2
I/libpersona(11939): KNOX_SDCARD checking this for 10079
I/libpersona(11939): KNOX_SDCARD not a persona
,I/SELinux (11939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11939 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothMap( 8823): Proxy object disconnected
D/MapProfile( 8823): Bluetooth service disconnected
,D/SapService( 5702): Received stop request...Stopping profile...
D/SapService( 5702): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5702): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bc755c4
,D/Bluetoothsap( 8823): BluetoothSAP Proxy object disconnected
,D/SapProfile( 8823): Bluetooth service disconnected
E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5702): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5702): Proxy object disconnected
D/BluetoothAdapterService( 5702): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 5702): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5702): GKI_exit_task 2 done
I/GKI_LINUX( 5702): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5702): cleanup
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5702): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5702): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5702): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5702): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5702): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5702): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5702): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5702): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5702): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(466048452)( 5702): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 5702): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5702): Setting state to 10
I/BluetoothAdapterState( 5702): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5702): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5702): updateAdapterState state is 10
W/BluetoothSAPServiceJni( 5702): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,D/BluetoothAdapterService( 5702): Autoconnection is available 
D/BluetoothAdapterService( 5702): updateAdapterState prevState = 13newState = 10
D/BluetoothA2dp( 8823): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 5702): Entering OffState
W/BluetoothSAPServiceJni( 5702): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothA2dp( 5025): onBluetoothStateChange: up=false
,D/AndroidRuntime(11923): 
D/AndroidRuntime(11923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothPbap( 8823): onBluetoothStateChange: up=false
,D/AndroidRuntime(11923): CheckJNI is OFF
,D/AndroidRuntime(11923): readGMSProperty: start
D/AndroidRuntime(11923): readGMSProperty: already setted!!
,D/AndroidRuntime(11923): readGMSProperty: end
D/AndroidRuntime(11923): addProductProperty: start
,D/Bluetoothsap( 8823): onBluetoothStateChange: up=false
D/Bluetoothsap( 8823): Unbinding service...
,D/BluetoothMap( 8823): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5702): onBluetoothStateChange: up=false
,D/TimaKeyStoreProvider(11939): TimaSignature is unavailable
,D/ActivityThread(11939): Added TimaKeyStore provider
,D/BluetoothInputDevice( 8823): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 3523): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceDown() to 14 receivers.
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,I/wpa_supplicant( 3833): Blacklist: Clear (all) 
,D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/ResourcesManager(11939): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3523): [BT Setting State] State =10
I/InputMethodManagerService( 3523): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/GKI_LINUX( 5702): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 3694): 902069390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3694): 902069390: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3694): 902069390: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
I/GKI_LINUX( 5702): GKI_exit_task 1 done
I/GKI_LINUX( 5702): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5702): cleanupNative: return from cleanup
,D/BluetoothAdapter( 3694): 902069390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3694): 902069390: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
I/SamsungIME( 4465): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/art     ( 5702): System.exit called, status: 0
I/AndroidRuntime( 5702): VM exiting with result code 0, cleanup skipped.
,D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/FileShare-Server(11939): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,V/BluetoothEventManager( 8823): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 4666): 1050226823: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4666): 1050226823: getState() :  mService = null. Returning STATE_OFF
,V/[CarModeFW](11306): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](11306): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,I/Hs20UtilService( 4111): Starting #9
,I/Hs20UtilService( 4111): Message received 5007
I/ActivityManager( 3523): Killing 9645:com.sec.android.gallery3d/u0a50 (adj 15): bgCount ##31
,D/NearbySettings( 8823): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8823): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8823): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8823): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8823): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8823): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11460): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4111): Starting #10
,I/Hs20UtilService( 4111): Message received 5011
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/AffinityControl(11923): AffinityControl: registerfunction enter
,D/AndroidRuntime(11923): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3523): START PACKAGE DELETE: observer{842412507}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3523): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3523): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3523): !@killApplicatoin: 10446, uninstall pkg
,E/Zygote  (11980): MountEmulatedStorage()
E/Zygote  (11980): v2
I/libpersona(11980): KNOX_SDCARD checking this for 10127
I/libpersona(11980): KNOX_SDCARD not a persona
,I/SELinux (11980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11980 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Force stopping com.example.hello appid=10446 user=-1: uninstall pkg
I/ActivityManager( 3523): Killing 11840:com.example.hello/u0a446 (adj 0): stop com.example.hello
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{1cc6b5f5 u0 com.example.hello/.MainActivity t26}
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,D/TimaKeyStoreProvider(11980): TimaSignature is unavailable
,D/ActivityThread(11980): Added TimaKeyStore provider
,W/PackageSettings( 3523): Skipping PackageSetting{db3d2e1 com.test.thalitest/10445} due to missing metadata
,D/WifiService( 3523): Client connection lost with reason: 4
,I/WindowState( 3523): WIN DEATH: Window{3fc4f963 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3523): Force stopping com.example.hello appid=10446 user=0: pkg removed
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{1cc6b5f5 u0 com.example.hello/.MainActivity t26 f}
W/ActivityManager( 3523): Duplicate finish request for ActivityRecord{1cc6b5f5 u0 com.example.hello/.MainActivity t26 f}
,D/ResourcesManager(11980): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3523): Process com.android.bluetooth (pid 5702)(adj 0) has died(242,1190)
,D/KeyguardWallpaperUpdator(11980): cancelUpdateWallpaper
,I/DBG_DM  ( 6272): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/KeyguardWallpaperUpdator(11980): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11980): stopCheckCategoryVersion
,I/art     ( 4050): Explicit concurrent mark sweep GC freed 33082(2031KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.491ms total 42.897ms
,I/art     ( 9017): Explicit concurrent mark sweep GC freed 29713(1655KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.085ms total 51.129ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/SamsungIME( 4465): mOCRHelper is null
,W/GeofencerStateMachine( 4666): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6272): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
,D/LWLocationManager(11614): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11614): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6272): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/SignOutReceiver(11460): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourceType( 5415): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
I/libpersona(11998): KNOX_SDCARD checking this for 1000
W/ResourceType( 5415): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/libpersona(11998): KNOX_SDCARD not a persona
E/Zygote  (11998): MountEmulatedStorage()
E/Zygote  (11998): v2
,I/SELinux (11998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SELinux (11998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/wpa_supplicant( 3833): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 3523): InitialState.processMessage what=4
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
E/WifiStateMachine( 3523): Supplicant connection lost
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 39351(2MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 49MB/65MB, paused 4.698ms total 180.300ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     ( 3523): WaitForGcToComplete blocked for 168.293ms for cause Explicit
,D/TimaKeyStoreProvider(11998): TimaSignature is unavailable
,D/ActivityThread(11998): Added TimaKeyStore provider
,E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [21]
,E/Tethering( 3523): No numeric data
,E/WifiStateMachine( 3523): setWifiState: disabled
D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/ActivityManager( 3523): Killing 11173:com.android.mms/u0a52 (adj 13): bgCount ##31
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,D/Tethering( 3523): sendTetherStateChangedBroadcast 0, 0, 0
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/DBG_DM  ( 6272): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6272): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6272): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6272): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6272): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/DBG_DM  ( 6272): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/HotspotTile( 3694): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/HotspotTile( 3694): updateTetherState():false, false
,D/ResourcesManager(11998): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/CountryDetector( 3523): No listener is left
,D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(1)
,D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/HotspotTile( 3694): onReceive : 1, 0
,I/SurfaceFlinger( 2853): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/NetworkStats( 3523): performPollLocked() took 16ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6272): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6272): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,W/Settings( 4666): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/RegisteredServicesCache( 3970): empty dynamic service
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/SecContentProvider2( 3523): mCursor = null
,I/ActivityManager( 3523): Killing 11197:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ContextImpl( 8823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/InputMethodManagerService( 3523): Got RemoteException sending setActive(false) notification to pid 11840 uid 10446
W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,V/ActivityThread( 6272): updateVisibility : ActivityRecord{38f0d05d token=android.os.BinderProxy@3d0eadc6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/Timeline( 6272): Timeline: Activity_idle id: android.os.BinderProxy@3d0eadc6 time:242420
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/DockEventReceiver( 8823): finishStartingService: stopping service
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 8099(421KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.136ms total 154.514ms
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11614): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{20457244 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:242454
,D/PackageManager( 3523): delete codoeFile: 
,I/AASAUninstall( 3523):  com.example.hello not target!
,D/PackageManager( 3523): result of delete: 1{842412507}
,D/BluetoothNotiBroadcastReceiver( 8823): onReceive
,D/AndroidRuntime(11923): Shutting down VM
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (12020): MountEmulatedStorage()
E/Zygote  (12020): v2
I/libpersona(12020): KNOX_SDCARD checking this for 1002
I/libpersona(12020): KNOX_SDCARD not a persona
,I/SELinux (12020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12020 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux (12020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/SELinux (12020): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11614): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11614): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11614): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11614): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/TimaKeyStoreProvider(12020): TimaSignature is unavailable
,D/ActivityThread(12020): Added TimaKeyStore provider
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(12020): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager(12020): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(12020): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/BluetoothA2dpSinkServiceJni(12020): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BtSettings.ProfileConfig(12020): Adding GattService
D/BtSettings.ProfileConfig(12020): Adding HeadsetService
D/BtSettings.ProfileConfig(12020): Adding A2dpService
D/BtSettings.ProfileConfig(12020): Adding HidService
,D/BtSettings.ProfileConfig(12020): Adding HealthService
D/BtSettings.ProfileConfig(12020): Adding PanService
D/BtSettings.ProfileConfig(12020): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12020): Adding SapService
D/BtSettings.ProfileConfig(12020): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12020): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12020): Adding SapClientService
,D/BtSettings.ProfileConfig(12020): Adding HidDevService
I/BtSettings.ProfileConfig(12020): *********Initializing Bluetooth Profile Settings*******
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
,D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002,
,D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(11614): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/ActivityManager( 3523): Killing 11215:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/RCPManagerService( 3523): PackageReceiver onReceive()
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/AuthorizationBluetoothService( 5558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10446
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
D/UsbSettingsManager( 3523): clearDefaults: com.example.hello
I/CrashAnrDetector( 3523): onPackageRemoved : com.example.hello
,D/ResourcesManager(11614): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11614): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,E/Zygote  (12036): MountEmulatedStorage()
E/Zygote  (12036): v2
I/libpersona(12036): KNOX_SDCARD checking this for 10063
I/libpersona(12036): KNOX_SDCARD not a persona
,I/SELinux (12036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12036 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,W/SLocation( 3523): No Active Data Connection
D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TimaKeyStoreProvider(12036): TimaSignature is unavailable
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ActivityThread(12036): Added TimaKeyStore provider
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12036): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
I/ApplicationPolicy( 3523): updateDataUsageMap
I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
,D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,D/PanelView( 3694): There is/are notification(s) 
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
,D/PanelView( 3694): There is/are notification(s) 
,D/VRSetupWizardStub/PackageIntentReceiver(12036): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12036): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12036): packagename:com.example.hello
,D/ResourcesManager(11614): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  (12051): MountEmulatedStorage()
E/Zygote  (12051): v2
I/libpersona(12051): KNOX_SDCARD checking this for 10021
I/libpersona(12051): KNOX_SDCARD not a persona
,I/SELinux (12051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12051 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 11231:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider(12051): TimaSignature is unavailable
,D/ActivityThread(12051): Added TimaKeyStore provider
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12051): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,I/KLMS-2.4.521: (12051): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 18:50:14 GMT+01:00 2015
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/KLMS-2.4.521: (12051): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12051): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12051): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(11614): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/KLMS-2.4.521: (12051): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12051): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12051): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12051): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/KLMS-2.4.521: (12051): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,E/Zygote  (12069): MountEmulatedStorage()
E/Zygote  (12069): v2
I/libpersona(12069): KNOX_SDCARD checking this for 10106
I/libpersona(12069): KNOX_SDCARD not a persona
,I/SELinux (12069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12069 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TimaKeyStoreProvider(12069): TimaSignature is unavailable
,D/ActivityThread(12069): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 860us total 23.603ms
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 489us total 18.833ms
,D/ResourcesManager(11614): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 489us total 13.296ms
,I/KLMS-2.4.521: (12051): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11614): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  (12090): MountEmulatedStorage()
E/Zygote  (12090): v2
I/libpersona(12090): KNOX_SDCARD checking this for 1000
I/libpersona(12090): KNOX_SDCARD not a persona
,I/SELinux (12090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12090): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/KLMS-2.4.521: (12051): KLMSIntentService(): onDestroy()
,D/ResourcesManager(12069): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
D/TimaKeyStoreProvider(12090): TimaSignature is unavailable
,D/ActivityThread(12090): Added TimaKeyStore provider
,E/Zygote  (12106): MountEmulatedStorage()
E/Zygote  (12106): v2
I/libpersona(12106): KNOX_SDCARD checking this for 10050
I/libpersona(12106): KNOX_SDCARD not a persona
,I/SELinux (12106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12106 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/elm:14491(12069): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
E/SELinux (12106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12069): ELMEngine.ELMEngine( context ).
,D/elm:14491(12069): MDMBridge.setEnterpriseBridge()
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(11614): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/elm:14491(12069): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TimaKeyStoreProvider(12106): TimaSignature is unavailable
,D/ActivityThread(12106): Added TimaKeyStore provider
,D/ResourcesManager(12090): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/elm:14491(12069): ElmAgentService : onCreate()
,W/ResourcesManager(12090): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:14491(12069): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
D/ResourcesManager(11614): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/elm:14491(12069): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12069): MDMBridge.getInstance()
D/elm:14491(12069): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12069): MDMBridge.getAllLicenseInfoFromSDK()
,D/RCPManager(12090):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12106): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(12106): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12106): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12124): MountEmulatedStorage()
E/Zygote  (12124): v2
I/libpersona(12124): KNOX_SDCARD checking this for 10019
I/libpersona(12124): KNOX_SDCARD not a persona
,I/SELinux (12124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12124 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12124): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12069): ElmAgentService : onDestroy().
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11513): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11513): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(11513): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11513): Widget is not attached.
,D/TimaKeyStoreProvider(12124): TimaSignature is unavailable
,I/ActivityManager( 3523): Killing 11247:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
D/ActivityThread(12124): Added TimaKeyStore provider
,I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,W/ContextImpl(11376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager(12124): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(12106): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12106): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12106): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12106): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12106): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12106): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12106): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12106): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12106): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12106): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/Zygote  (12143): MountEmulatedStorage()
E/Zygote  (12143): v2
I/libpersona(12143): KNOX_SDCARD checking this for 10116
I/libpersona(12143): KNOX_SDCARD not a persona
,I/SELinux (12143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27

```
