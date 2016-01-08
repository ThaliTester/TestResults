#### Test 5024228542a63d7_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 260, CUR = 67
D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 233, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
D/BatteryService( 3516): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5619): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(12007): 
D/AndroidRuntime(12007): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12007): CheckJNI is OFF
D/AndroidRuntime(12007): readGMSProperty: start
D/AndroidRuntime(12007): readGMSProperty: already setted!!
D/AndroidRuntime(12007): readGMSProperty: end
D/AndroidRuntime(12007): addProductProperty: start
E/AffinityControl(12007): AffinityControl: registerfunction enter
D/AndroidRuntime(12007): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3516): inState():  stateMachine is null !!
I/PersonaManagerService( 3516): PersonaId don't exist
I/ActivityManager( 3516): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3516): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3516): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3516): mDVFSHelper.acquire()
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/Zygote  (12030): MountEmulatedStorage()
E/Zygote  (12030): v2
I/libpersona(12030): KNOX_SDCARD checking this for 10549
I/libpersona(12030): KNOX_SDCARD not a persona
I/SELinux (12030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3516): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=12030 uid=10549 gids={50549, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (12030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
E/SELinux (12030): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(12007): Shutting down VM
D/TimaKeyStoreProvider(12030): TimaSignature is unavailable
D/ActivityThread(12030): Added TimaKeyStore provider
I/SurfaceFlinger( 2847): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2847): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(12030): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/ActivityThread( 6279): updateVisibility : ActivityRecord{29f9a8ff token=android.os.BinderProxy@190cf720 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(12030): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12030): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12030): Loading: webviewchromium
I/LibraryLoader(12030): Time to load native libraries: 5 ms (timestamps 5144-5149)
I/LibraryLoader(12030): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12030): Binding Chromium to main looper Looper (main, tid 1) {18cc672e}
,I/LibraryLoader(12030): Expected native library version number "",actual native library version number ""
,I/chromium(12030): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12030): Initializing chromium process, renderers=0
,W/art     (12030): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12030): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12030): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(12030): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(12030): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(12030): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (12030): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(12030): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(12030): CordovaWebView is running on device made by: samsung
,W/art     (12030): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (12030): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(12030): performCreate Call secproduct feature valuefalse
D/Activity(12030): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(12030): Render dirty regions requested: true
,D/ActivityManager( 3516): post active user change for 0
D/KnoxTimeoutHandler( 3516): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3516): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2847): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(12030): Initialized EGL, version 1.4
,I/OpenGLRenderer(12030): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278897904 
,D/OpenGLRenderer(12030): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(12030): Enabling debug mode 0
,D/mali_winsys(12030): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(12030): updateVisibility : ActivityRecord{1036f7de token=android.os.BinderProxy@1264ebad {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3516): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3516): mDVFSHelper.release()
I/Timeline( 3516): Timeline: Activity_windows_visible id: ActivityRecord{24a560c9 u0 com.example.hello/.MainActivity t26} time:135582
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 53802(3MB) AllocSpace objects, 29(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.709ms total 167.366ms
,W/IInputConnectionWrapper(12030): showStatusIcon on inactive InputConnection
,I/Timeline(12030): Timeline: Activity_idle id: android.os.BinderProxy@1264ebad time:135758
,I/chromium(12030): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(12030): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium(12030): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(12030): 
,D/JsMessageQueue(12030): Set native->JS mode to OnlineEventsBridgeMode
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/jxcore_app_log(12030): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360570624
D/JX-Cordova(12030): jxcore cordova android initializing
,W/jxcore-log(12030): Initializing JXcore engine
W/jxcore-log(12030): JXcore engine is ready
,E/auditd  ( 4609): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3516): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3516): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(12030): Starting JXcore engine
,W/jxcore-log(12030): Platform android
W/jxcore-log(12030): 
W/jxcore-log(12030): Process ARCH arm
W/jxcore-log(12030): 
,I/jxcore-log(12030): JXcore Cordova bridge is ready!
I/jxcore-log(12030): 
W/jxcore-log(12030): JXcore engine is started
,E/jxcore-log(12030): >> samsung-SM-N910C
E/jxcore-log(12030): 
,I/jxcore-log(12030): Total memory 2970812416
I/jxcore-log(12030): 
I/jxcore-log(12030): Free memory 74731520
I/jxcore-log(12030): 
I/jxcore-log(12030): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12030): 
I/jxcore-log(12030): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12030): 
,I/jxcore-log(12030): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log(12030): 
,I/jxcore-log(12030): Size 1440 2560
I/jxcore-log(12030): 
,I/jxcore-log(12030): Screen Brightness 134
I/jxcore-log(12030): 
E/jxcore-log(12030): Dummy Error Log.
E/jxcore-log(12030): 
,I/jxcore-log(12030): getBuffer is called!!!!
I/jxcore-log(12030): 
,D/BluetoothAdapter(12030): disable()
,D/SettingsProvider( 3516): name = bluetooth_on
,D/BluetoothAdapterState( 5619): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5619): Setting state to 13
,I/BluetoothAdapterState( 5619): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5619): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5619): updateAdapterState state is 13
,I/BluetoothPbapService( 5619): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 5619): Autoconnection is available 
,D/BluetoothAdapterService( 5619): updateAdapterState prevState = 12newState = 13
,D/BluetoothSocket( 5619): close() in, this: android.bluetooth.BluetoothSocket@239131f0, channel: 19, state: LISTENING
,D/BluetoothSocket( 5619): close() this: android.bluetooth.BluetoothSocket@239131f0, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c7d2f31, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31a99369mSocket: android.net.LocalSocket@3c53f1ee impl:android.net.LocalSocketImpl@f88b68f fd:FileDescriptor[74]
D/BluetoothAdapterService( 5619): terminating service from this receiver
D/BluetoothSocket( 5619): Closing mSocket: android.net.LocalSocket@3c53f1ee impl:android.net.LocalSocketImpl@f88b68f fd:FileDescriptor[74]
,D/BluetoothAdapterProperties( 5619): onBluetoothDisable()
,D/SecContentProvider( 3516): uri = 3 selection = isDiscoverableEnabled
,W/InputMethodManagerService( 3516): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothAdapterState( 5619): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/InputMethodManagerService( 3516): [BT Setting State] State =13
,D/WifiService( 3516): New client listening to asynchronous messages
,D/BluetoothTile( 3694):  onBluetoothStateChange:
I/WifiManager(12030): packageName : com.example.hello
,D/SecContentProvider( 3516): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3516): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3516): mCursor = null
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService( 3516): setWifiEnabled: false pid=12030, uid=10549
I/SamsungIME( 4504): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
E/WifiService( 3516): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3516): name = wifi_on
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 3516): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3516): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(12030): ****TEST TOOK:  5101  ms ****
I/jxcore-log(12030): 
,E/WifiStateMachine( 3516): WifiStateMachine: Leaving Connected state
I/jxcore-log(12030): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12030): 
,I/wpa_supplicant( 3827): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3827): P2P: Current p2p state = IDLE
E/WifiStateMachine( 3516): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3516): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3516): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 3827): Scan requested (ret=0) - scan timeout 30 seconds
E/Zygote  (12139): MountEmulatedStorage()
E/Zygote  (12139): v2
I/libpersona(12139): KNOX_SDCARD checking this for 1000
I/libpersona(12139): KNOX_SDCARD not a persona
,I/SELinux (12139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/ActivityManager( 3516): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=12139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/WifiStateMachine( 3516): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3516): do suspend true
,E/SELinux (12139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapterProperties( 5619): Scan Mode:20
D/BluetoothAdapterState( 5619): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5619): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5619): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 5619): cmd socket is not created
,E/BtOppRfcommListener( 5619): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 5619): btm_ble_start_auto_conn start : 0, 0
D/btif_config_util( 5619): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 5619): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 5619): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x001b not found for deregistration
,D/WifiP2pService( 3516): InactiveState{ what=143375 }
,D/WifiP2pService( 3516): P2pEnabledState{ what=143375 }
,D/BluetoothSocket( 5619): close() in, this: android.bluetooth.BluetoothSocket@153efd25, channel: 5, state: LISTENING
,D/BluetoothSocket( 5619): close() this: android.bluetooth.BluetoothSocket@153efd25, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c963fd8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c913efamSocket: android.net.LocalSocket@2a642cab impl:android.net.LocalSocketImpl@9854f08 fd:FileDescriptor[72]
D/BluetoothSocket( 5619): Closing mSocket: android.net.LocalSocket@2a642cab impl:android.net.LocalSocketImpl@9854f08 fd:FileDescriptor[72]
I/BtOppRfcommListener( 5619): stopping Accept Thread
,D/BluetoothSocket( 5619): close() in, this: android.bluetooth.BluetoothSocket@140746a1, channel: 12, state: LISTENING
D/BluetoothSocket( 5619): close() this: android.bluetooth.BluetoothSocket@140746a1, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@407aa33, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2450c6mSocket: android.net.LocalSocket@1f36e887 impl:android.net.LocalSocketImpl@24a453b4 fd:FileDescriptor[77]
D/BluetoothSocket( 5619): Closing mSocket: android.net.LocalSocket@1f36e887 impl:android.net.LocalSocketImpl@24a453b4 fd:FileDescriptor[77]
,I/BtOppRfcommListener( 5619): BluetoothSocket listen thread finished
,D/CommandListener( 2843): Clearing all IP addresses on wlan0
,V/NativeCrypto( 4634): Read error: ssl=0x9ca3ce00: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3516): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3516): updateNetworkInfo()
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 4634): SSL shutdown failed: ssl=0x9ca3ce00: I/O error during system call, Broken pipe
,I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen,
D/ConnectivityService( 3516): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): ValidatedState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): DefaultState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Forcing reevaluation,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine( 3516): scanCount==0 - aborting
,D/TimaKeyStoreProvider(12139): TimaSignature is unavailable
,D/ActivityThread(12139): Added TimaKeyStore provider
,E/WifiStateMachine( 3516): [1,452,276,758,179 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService( 3516): InactiveState{ what=131204 }
,I/System.out( 3516): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiP2pService( 3516): P2pEnabledState{ what=131204 }
E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/qtaguid ( 3516): Tagging socket 389 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3516, getuid(): 1000
,E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService( 3516): sending p2p connection changed broadcast: FAILED
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3516): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService( 3516): SCAN_AVAILABLE : 1
D/WifiScanningService( 3516): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 3516): SCAN_AVAILABLE : 1
,D/RttService( 3516): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/System.out( 3516): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiDisplayController( 3516): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3516): onP2pDisconnected
,D/IpRemoteDisplayController( 3516): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3516): WfdBridgeServer is already null
,D/WifiP2pService( 3516): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 3516): P2pDisablingState
,D/WifiP2pService( 3516): P2pDisablingState{ what=147458 }
,E/WifiStateMachine( 3516): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 3516): p2p socket connection lost
,D/WifiP2pService( 3516): P2pDisabledState
D/WifiDisplayController( 3516): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3516): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3516): disconnect
D/WifiDisplayController( 3516): updateConnection
D/WifiDisplayController( 3516): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
E/WifiStateMachine( 3516): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
D/WifiDisplayAdapter( 3516): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3516): do suspend true
D/WifiDisplayController( 3516): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3516): onP2pDisconnected
D/IpRemoteDisplayController( 3516): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3516): WfdBridgeServer is already null
,D/AllShareCastTile( 3694): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3516): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(12139): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/AllShareCastTile( 3694): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiP2pService( 3516): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 3516): DefaultState{ what=143375 }
D/EnterpriseController( 2843): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2843): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 3516): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3516): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Validated
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/CommandListener( 2843): Clearing all IP addresses on wlan0
,W/ResourcesManager(12139): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3516): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager(12139): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12139): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3516): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3516): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3516): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3516): stopping supplicant
D/ConnectivityManager.CallbackHandler( 6673): CM callback handler got msg 524292
I/wpa_supplicant( 3827): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3516): setWifiState: disabling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
D/SLocation( 3516): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : false mobile : false
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
,D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(0)
D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
D/HotspotTile( 3694): onReceive : 0, 0
D/EntConnectivity( 3516): Not allowed due to - mEnabled false
E/ConnectivityService( 3516): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/ConnectivityService( 3516): updateNetworkInfo()
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService( 3516): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService( 3516): updateNetworkInfo()
,D/Tethering( 3516): MasterInitialState.processMessage what=3
D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
,V/NetworkStats( 3516): updateIfacesLocked()
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): performPollLocked(flags=0x1)
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : false mobile : false
,D/NetworkStatsFactory( 3516): UpdateStatsForKnox
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,V/NetworkStats( 3516): performPollLocked() took 10ms
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/MySettingsProvider(12139): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(12139): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(12139): onCreate():(mDB == null)? false:true  =true
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,W/bt-l2cap( 5619): HC lib lpm enable=0 return 0
W/bt-l2cap( 5619): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5619): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5619): ag scb idx 1 not allocated
W/bt-btif ( 5619): ag scb idx 2 not allocated
E/bt-btif ( 5619): BTA AG is already disabled, ignoring ...
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/bt_userial( 5619): RX termination
W/bt_userial( 5619): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5619): Leaving userial_read_thread()
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/bt_userial( 5619): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 5619): hw_epilog_process
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
I/bt_userial_vendor( 5619): device fd = 65 close
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,I/GKI_LINUX( 5619): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 5619): GKI_exit_task 0 done
I/GKI_LINUX( 5619): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5619): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5619): isSecureModeOn:false
D/BluetoothAdapterService( 5619): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.gatt.GattService
,D/BtGatt.DebugUtils( 5619): handleDebugAction() action=null
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 5619): Received stop request...Stopping profile...
D/BtGatt.GattService( 5619): stop()
,W/ContextImpl(12139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.AdvertiseManager( 5619): advertise clients cleared
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 5619): Received stop request...Stopping profile...
,I/wpa_supplicant( 3827): Blacklist: Clear (all) 
,D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.pan.PanService
D/LocalBluetoothProfileManager(12139): PANU : true
D/LocalBluetoothProfileManager(12139): Adding local MAP profile
D/BluetoothMap(12139): Create BluetoothMap proxy object
,D/AudioService( 3516): onServiceDisconnected: Bluetooth profile: 1
,D/A2dpService( 5619): Received stop request...Stopping profile...
V/Avrcp   ( 5619): doQuit
,D/Avrcp   ( 5619): Unregistering previous receiver
,D/A2dpStateMachine( 5619): Exit Disconnected: -1
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5619): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothA2dp( 4909): Proxy object disconnected
W/BluetoothAdapterService( 5619): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothA2dp( 3516): Proxy object disconnected
D/AudioService( 3516): onServiceDisconnected: Bluetooth profile: 2
,W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5619): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5619): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5619): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5619): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5619): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5619): Stopping profile services that were post enabled
E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HidService( 5619): Received stop request...Stopping profile...
D/HidService( 5619): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5619): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5619): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5619): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5619): Profile still running: com.android.bluetooth.hid.HidService
W/ContextImpl(12139): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/HealthService( 5619): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,D/Bluetoothsap(12139): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager(12139): LocalBluetoothProfileManager construction complete
,I/wpa_supplicant( 3827): p2p0: CTRL-EVENT-TERMINATING 
,W/BluetoothHeadsetServiceJni( 5619): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5619): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 5619): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,D/BluetoothPan( 3516): BluetoothPAN Proxy object disconnected
,E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5619): Profile still running: com.android.bluetooth.hid.HidService
,D/DockEventReceiver(12139): finishStartingService: stopping service
I/wpa_supplicant( 3827): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/BluetoothPan(12139): BluetoothPAN Proxy object connected
D/PanProfile(12139): Bluetooth service connected
D/BluetoothMapService( 5619): Received stop request...Stopping profile...
I/wpa_supplicant( 3827): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
D/BluetoothNotiBroadcastReceiver(12139): onReceive
,D/BluetoothMap(12139): Proxy object connected
D/MapProfile(12139): Bluetooth service connected
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
D/Bluetoothsap(12139): BluetoothSAP Proxy object connected
,D/SapProfile(12139): Bluetooth service connected
D/Bluetoothsap(12139): getConnectedDevices()
,D/BluetoothPan(12139): BluetoothPAN Proxy object disconnected
D/PanProfile(12139): Bluetooth service disconnected
,D/BluetoothA2dp( 5619): Proxy object disconnected
D/BluetoothMap(12139): Proxy object disconnected
D/MapProfile(12139): Bluetooth service disconnected
D/BluetoothAdapterService( 5619): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 5619): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5619): GKI_exit_task 2 done
I/GKI_LINUX( 5619): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5619): cleanup
,I/ActivityManager( 3516): Killing 11105:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
D/SapService( 5619): Received stop request...Stopping profile...
D/SapService( 5619): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5619): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18cc672e
,D/Bluetoothsap(12139): BluetoothSAP Proxy object disconnected
D/SapProfile(12139): Bluetooth service disconnected
E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5619): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5619): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5619): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5619): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5619): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 5619): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5619): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5619): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5619): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(416048942)( 5619): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 5619): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5619): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 5619): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5619): Setting state to 10
I/BluetoothAdapterState( 5619): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5619): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5619): updateAdapterState state is 10
D/BluetoothAdapterService( 5619): Autoconnection is available 
D/BluetoothAdapterService( 5619): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5619): Entering OffState
,D/AndroidRuntime(12150): 
D/AndroidRuntime(12150): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AuthorizationBluetoothService( 4634): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothA2dp( 3516): onBluetoothStateChange: up=false
,D/BluetoothPbap(12139): onBluetoothStateChange: up=false
,D/AndroidRuntime(12150): CheckJNI is OFF
D/AndroidRuntime(12150): readGMSProperty: start
D/AndroidRuntime(12150): readGMSProperty: already setted!!
,D/AndroidRuntime(12150): readGMSProperty: end
D/AndroidRuntime(12150): addProductProperty: start
,D/BluetoothA2dp( 4909): onBluetoothStateChange: up=false
,I/Hs20UtilService( 4057): Starting #8
,I/Hs20UtilService( 4057): Message received 5007
,D/NearbySettings(12139): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(12139): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(12139): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings(12139): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/BluetoothMap(12139): onBluetoothStateChange: up=false
,V/NearbySettings(12139): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothA2dp( 5619): onBluetoothStateChange: up=false
,D/Bluetoothsap(12139): onBluetoothStateChange: up=false
D/Bluetoothsap(12139): Unbinding service...
,D/WifiService( 3516): New client listening to asynchronous messages
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/BluetoothManagerService( 3516): Broadcasting onBluetoothServiceDown() to 12 receivers.
I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12139): MountReceiver.onReceive - Set preference state off
V/NearbySettings(12139): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11223): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothManagerService( 3516): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/InputMethodManagerService( 3516): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3516): [BT Setting State] State =10
I/InputMethodManagerService( 3516): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 3694): 313077672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 3694): 313077672: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 3694): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3694): 313077672: getState() :  mService = null. Returning STATE_OFF
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Bluetooth
,D/BluetoothAdapter( 3694): 313077672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3694): 313077672: getState() :  mService = null. Returning STATE_OFF
I/SamsungIME( 4504): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 3516): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3516): setIconVisibility slot=bluetooth visible=false
,V/BluetoothEventManager(12139): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/PhoneStatusBar( 3694): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/NearbySettings(12139): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/GKI_LINUX( 5619): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 4634): 425592064: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 5619): GKI_exit_task 1 done
I/GKI_LINUX( 5619): GKI_shutdown(): task [BTIF] terminated
D/BluetoothAdapter( 4634): 425592064: getState() :  mService = null. Returning STATE_OFF
I/BluetoothServiceJni( 5619): cleanupNative: return from cleanup
V/NearbySettings(12139): DMSUtil.isNetworkConnected - flag-null, state-null
,I/art     ( 5619): System.exit called, status: 0
I/AndroidRuntime( 5619): VM exiting with result code 0, cleanup skipped.
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/wpa_supplicant( 3827): Blacklist: Clear (all) 
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12139): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(12139): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12198): MountEmulatedStorage()
I/libpersona(12198): KNOX_SDCARD checking this for 10079
E/Zygote  (12198): v2
I/libpersona(12198): KNOX_SDCARD not a persona
,I/SELinux (12198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12198 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12198): TimaSignature is unavailable
,D/ActivityThread(12198): Added TimaKeyStore provider
E/AffinityControl(12150): AffinityControl: registerfunction enter
,I/ActivityManager( 3516): Process com.android.bluetooth (pid 5619)(adj 0) has died(77,1314)
,D/ResourcesManager(12198): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/AndroidRuntime(12150): Calling main entry com.android.commands.pm.Pm
,D/FileShare-Server(12198): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/PackageManager( 3516): START PACKAGE DELETE: observer{470068004}
D/PackageManager( 3516): pkg{<packageName>}
D/PackageManager( 3516): user{0}
D/PackageManager( 3516): caller{2000}
D/PackageManager( 3516): flags{3}
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3516): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3516): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3516): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3516): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3516): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3516): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3516): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3516): !@killApplicatoin: 10549, uninstall pkg
I/ActivityManager( 3516): Force stopping com.example.hello appid=10549 user=-1: uninstall pkg
,I/ActivityManager( 3516): Killing 12030:com.example.hello/u0a549 (adj 0): stop com.example.hello
,I/ActivityManager( 3516):   Force finishing activity ActivityRecord{24a560c9 u0 com.example.hello/.MainActivity t26}
,W/ActivityManager( 3516): mDVFSHelper.acquire()
,W/PackageSettings( 3516): Skipping PackageSetting{2ebe8f48 com.test.thalitest/10548} due to missing metadata
,I/WindowState( 3516): WIN DEATH: Window{3d7a01d7 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 3516): Client connection lost with reason: 4
,I/SurfaceFlinger( 2847): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2847): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2847): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3516): Killing 11124:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3516): Force stopping com.example.hello appid=10549 user=0: pkg removed
,I/ActivityManager( 3516):   Force finishing activity ActivityRecord{24a560c9 u0 com.example.hello/.MainActivity t26 f}
W/ActivityManager( 3516): Duplicate finish request for ActivityRecord{24a560c9 u0 com.example.hello/.MainActivity t26 f}
,E/JavaBinder( 3516): !!! FAILED BINDER TRANSACTION !!!
,I/DBG_DM  ( 6279): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/art     ( 4075): Explicit concurrent mark sweep GC freed 33180(2037KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.313ms total 42.342ms
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 8910): Explicit concurrent mark sweep GC freed 24932(1451KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 4.314ms total 52.849ms
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/InputReader( 3516): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3982): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SamsungIME( 4504): mOCRHelper is null
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6279): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
,W/GeofencerStateMachine( 4634): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3982): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LWLocationManager(11332): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11332): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6279): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/Hs20UtilService( 4057): Starting #9
,I/Hs20UtilService( 4057): Message received 5007
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3516): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3516): Admin package name: com.google.android.gms
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/NetworkMonitor(11299): type=WIFI subType= reason=null isConnected=false
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/NearbySettings(12139): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(12139): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/SecContentProvider2( 3516): uri = 14 selection = getSealedState
D/SecContentProvider2( 3516): mCursor = null
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ApplicationPolicy( 3516): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3516): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ResourceType( 5338): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5338): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/NearbySettings(12139): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/NearbySettings(12139): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12139): MountReceiver.onReceive - Set preference state off
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,V/NearbySettings(12139): MountReceiver.mPrefHandler - 7002
,I/DBG_DM  ( 6279): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6279): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/DBG_DM  ( 6279): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6279): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6279): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3516): post active user change for 0
D/KnoxTimeoutHandler( 3516): postActiveUserChange for user 0
,I/DBG_DM  ( 6279): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 45863(2MB) AllocSpace objects, 6(144KB) LOS objects, 24% free, 48MB/64MB, paused 2.590ms total 169.829ms
,D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3516): WaitForGcToComplete blocked for 23.224ms for cause Explicit
,I/SignOutReceiver(11223): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2847): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/DBG_DM  ( 6279): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6279): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/Hs20UtilService( 4057): Starting #10
,I/Hs20UtilService( 4057): Message received 5011
,I/wpa_supplicant( 3827): wlan0: CTRL-EVENT-TERMINATING 
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 3516): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/Tethering( 3516): InitialState.processMessage what=4
,E/WifiStateMachine( 3516): Supplicant connection lost
,E/Tethering( 3516): No numeric data
,W/InputMethodManagerService( 3516): Got RemoteException sending setActive(false) notification to pid 12030 uid 10549
,V/ActivityThread( 6279): updateVisibility : ActivityRecord{29f9a8ff token=android.os.BinderProxy@190cf720 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,E/Zygote  (12220): MountEmulatedStorage()
I/libpersona(12220): KNOX_SDCARD checking this for 10127
E/Zygote  (12220): v2
I/libpersona(12220): KNOX_SDCARD not a persona
W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux (12220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/SELinux (12220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12220 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Timeline( 6279): Timeline: Activity_idle id: android.os.BinderProxy@190cf720 time:142404
,D/SecContentProvider2( 3516): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3516): mCursor = null
,E/WifiStateMachine( 3516): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL( 3516): callSECApiBoolean - ID [21]
,E/WifiStateMachine( 3516): setWifiState: disabled
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/Tethering( 3516): sendTetherStateChangedBroadcast 0, 0, 0
,D/RegisteredServicesCache( 3971): empty dynamic service
,D/HotspotTile( 3694): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): performPollLocked(flags=0x1)
D/HotspotTile( 3694): updateTetherState():false, false
,D/NetworkStatsFactory( 3516): UpdateStatsForKnox
,W/ResourceType( 3516): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/NetworkStats( 3516): performPollLocked() took 7ms
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider(12220): TimaSignature is unavailable
,D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(1)
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ActivityThread(12220): Added TimaKeyStore provider
,W/Settings( 4634): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/HotspotTile( 3694): onReceive : 1, 0
,W/ActivityManager( 3516): mDVFSHelper.release()
I/Timeline( 3516): Timeline: Activity_windows_visible id: ActivityRecord{1de8b5b2 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:142446
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,W/ResourcesManager(11332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3516): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/art     ( 3516): Explicit concurrent mark sweep GC freed 9311(472KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.530ms total 165.338ms
W/ResourcesManager( 3516): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager(12220): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
W/ResourcesManager( 3516): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3516): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11332): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/ResourcesManager(11332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11332): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11332): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/PackageManager( 3516): delete codoeFile: 
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/KeyguardWallpaperUpdator(12220): cancelUpdateWallpaper
,I/AASAUninstall( 3516):  com.example.hello not target!
D/PackageManager( 3516): result of delete: 1{470068004}
,D/KeyguardWallpaperUpdator(12220): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12220): stopCheckCategoryVersion
,D/AndroidRuntime(12150): Shutting down VM
,I/SignOutReceiver(11223): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ActivityManager( 3516): Killing 11140:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,W/ContextImpl(12139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/DockEventReceiver(12139): finishStartingService: stopping service
,D/ResourcesManager(11332): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/BluetoothNotiBroadcastReceiver(12139): onReceive
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12239): MountEmulatedStorage()
E/Zygote  (12239): v2
I/libpersona(12239): KNOX_SDCARD checking this for 1002
I/libpersona(12239): KNOX_SDCARD not a persona
,I/SELinux (12239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12239 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux (12239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3516): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/RCPManagerService( 3516): PackageReceiver onReceive()
I/HarmonyEASService( 3516): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3516): clearDefaults: com.example.hello
I/CrashAnrDetector( 3516): onPackageRemoved : com.example.hello
,D/KnoxMUMContainerPolicy( 3516): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/GpsLocationProvider( 3516): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/TimaKeyStoreProvider(12239): TimaSignature is unavailable
D/BackupManagerService( 3516): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3516): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3516): uID is 10549
V/EnterpriseBillingPolicy( 3516): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3516): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3516): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3516): getBillingProfileForVpnEngine - start - com.example.hello
D/ActivityThread(12239): Added TimaKeyStore provider
V/EnterpriseBillingPolicyStorage( 3516): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : false mobile : false
,W/SLocation( 3516): No Active Data Connection
,D/KnoxTimeoutHandler( 3516): handleActiveUserChange for user 0
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3516): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(12239): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/ResourcesManager(12239): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager(12239): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TaskPersister( 3516): removeObsoleteFile: deleting file=26_task.xml
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
D/TaskPersister( 3516): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,I/BluetoothA2dpSinkServiceJni(12239): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,I/ApplicationPolicy( 3516): updateDataUsageMap
I/ApplicationPolicy( 3516): updateDataUsageMap  idList is null 
,D/BtSettings.ProfileConfig(12239): Adding GattService
D/BtSettings.ProfileConfig(12239): Adding HeadsetService
D/BtSettings.ProfileConfig(12239): Adding A2dpService
,D/BtSettings.ProfileConfig(12239): Adding HidService
D/BtSettings.ProfileConfig(12239): Adding HealthService
D/BtSettings.ProfileConfig(12239): Adding PanService
D/BtSettings.ProfileConfig(12239): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12239): Adding SapService
D/BtSettings.ProfileConfig(12239): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12239): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12239): Adding SapClientService
,D/BtSettings.ProfileConfig(12239): Adding HidDevService
I/BtSettings.ProfileConfig(12239): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
,D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
,D/PanelView( 3694): There is/are notification(s) 
D/PanelView( 3694): There is/are notification(s) 
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/SettingsProvider( 3516): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3516): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3516): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3516): selectionArgs: false
D/SettingsProvider( 3516): selectionArgs: 1002
D/SecContentProvider( 3516): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3516): ret = -1
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager( 3516): Killing 11246:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
D/AuthorizationBluetoothService( 4634): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/Zygote  (12255): MountEmulatedStorage()
E/Zygote  (12255): v2
I/libpersona(12255): KNOX_SDCARD checking this for 10063
I/libpersona(12255): KNOX_SDCARD not a persona
I/SELinux (12255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/SELinux (12255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12255 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TimaKeyStoreProvider(12255): TimaSignature is unavailable
,D/ActivityThread(12255): Added TimaKeyStore provider
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(11332): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12255): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(11332): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12255): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12255): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12255): packagename:com.example.hello
,I/KLMS-2.4.521: (11570): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:12:39 GMT+01:00 2016
,I/KLMS-2.4.521: (11570): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3516): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3516): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (11570): KLMSIntentService(): onCreate()
,D/elm:14491(11718): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.4.521: (11570): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11570): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11570): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11570): KLMSIntentService(): PACKAGE_REMOVED
,D/elm:14491(11718): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.4.521: (11570): KLMSIntentService(): listeningToPackageRemoved().START
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11718): ElmAgentService : onCreate()
,D/elm:14491(11718): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/KLMS-2.4.521: (11570): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/elm:14491(11718): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11718): MDMBridge.getInstance()
D/elm:14491(11718): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11718): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12273): MountEmulatedStorage()
,E/Zygote  (12273): v2
I/libpersona(12273): KNOX_SDCARD checking this for 1000
I/libpersona(12273): KNOX_SDCARD not a persona
,I/SELinux (12273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12273 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(11718): ElmAgentService : onDestroy().
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12287): MountEmulatedStorage()
E/Zygote  (12287): v2
I/libpersona(12287): KNOX_SDCARD checking this for 10050
I/libpersona(12287): KNOX_SDCARD not a persona
,D/ResourcesManager(11332): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/SELinux (12287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/UsbHostManager( 3516): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3516): displayNotification : [02h,02h,01h]
,I/ActivityManager( 3516): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12287 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux (12287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/UsbHostManager( 3516): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3516): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3516): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3516): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3516): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/TimaKeyStoreProvider(12273): TimaSignature is unavailable
D/UsbHostManager( 3516): displayNotification : [0ah,00h,01h]
,D/ActivityThread(12273): Added TimaKeyStore provider
,D/UsbHostManager( 3516): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3516): displayNotification : [09h,00h,00h]
E/SELinux (12287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3516): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3516): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3516): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11666): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver(11666): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(11666): onReceive() : package name is not s health. Return !!!
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 909us total 25.285ms
,D/TimaKeyStoreProvider(12287): TimaSignature is unavailable
D/ResourcesManager(12273): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ActivityThread(12287): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 826us total 16.413ms
,D/LocationWidgetApplication(11332): getLastUiLocationId() : mLastUiLocationId = -100
,D/UsbHostManager( 3516): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3516): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,W/ResourcesManager(12273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (11570): KLMSIntentService(): listeningToPackageRemoved().END
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 663us total 21.555ms
,I/EventHub( 3516): Removing device '/dev/input/event10' due to inotify event
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11570): KLMSIntentService(): onDestroy()
,D/RCPManager(12273):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3516):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3516): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(12287): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12287): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Zygote  (12311): MountEmulatedStorage()
W/ResourcesManager(12287): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/Zygote  (12311): v2
I/libpersona(12311): KNOX_SDCARD checking this for 1000
I/libpersona(12311): KNOX_SDCARD not a persona
W/ResourcesManager(12287): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12287): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12287): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12287): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12287): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SELinux (12311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3516): Removing device '/dev/input/event7' due to inotify event
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11281): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11281): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11281): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11281): Widget is not attached.
,D/TimaKeyStoreProvider(12311): TimaSignature is unavailable
,D/ActivityThread(12311): Added TimaKeyStore provider
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3516): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (12326): MountEmulatedStorage()
E/Zygote  (12326): v2
I/libpersona(12326): KNOX_SDCARD checking this for 10101
I/libpersona(12326): KNOX_SDCARD not a persona
,I/EventHub( 3516): Removing device '/dev/input/event9' due to inotify event
,I/SELinux (12326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12326 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12326): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Killing 11171:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,I/EventHub( 3516): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager( 3516): Killing 11441:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,I/EventHub( 3516): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12311): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/SQLiteLog(12287): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,D/TimaKeyStoreProvider(12326): TimaSignature is unavailable
,D/ActivityThread(12326): Added TimaKeyStore provider
E/SQLiteDatabase(12287): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12287): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12287): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12287): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12287): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12287): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12287): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12287): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12287): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12287): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12287): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12287): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12287): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12287): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/EventHub( 3516): Removing device '/dev/input/event13' due to inotify event
,D/PackageBroadcastService( 6673): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/PCWCLIENTTRACE_LOG(12311): DEFAULT_LOGON : true
D/AccountUtils( 6673): Clearing selected account for com.example.hello
I/PCWCLIENTTRACE_LOG(12311): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12311): new DMDBOpenHelper instance
,E/SQLiteLog(12311): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3516): Removing device '/dev/input/event14' due to inotify event
,E/SharedPreferencesImpl(12287): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteDatabase(12311): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12311): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12311): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(12311): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12311): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12311): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12311): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12311): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12311): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PackageManager( 3516): findPreferredActivity: No PreferredActivities set
,D/AndroidRuntime(12311): Shutting down VM
,E/AndroidRuntime(12311): FATAL EXCEPTION: main
E/AndroidRuntime(12311): Process: com.sec.pcw.device, PID: 12311
E/AndroidRuntime(12311): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12311): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12311): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12311): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12311): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12311): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12311): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12311): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12311): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12311): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12311): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12311): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12311): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(12311): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12311): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12311): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12311): 	... 11 more
,D/ResourcesManager(12326): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/SQLiteLog( 6673): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6673): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 6673): disk I/O error (code 3850)
E/DriveAsyncService( 6673): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6673): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6673): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6673): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6673): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6673): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6673): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6673): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6673): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6673): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6673): 	at java.lang.Thread.run(Thread.java:818)
,V/ApplicationPolicy( 3516): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,I/LocationSettingsChecker( 6673): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 6673): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,D/ChimeraCfgMgr( 6673): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/SQLiteDatabase( 6673): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6673): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6673): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6673): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6673): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6673): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6673): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6673): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6673): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6673): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6673): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6673): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6673): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6673): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6673): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6673): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6673): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6673): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6673): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6673): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6673): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6673): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ChimeraModuleLdr( 6673): Module APK com.google.android.play.games already loaded
,W/SQLiteOpenHelper( 6673): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 6673): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6673): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6673): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6673): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 3516): Killing 11299:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,E/AndroidRuntime( 6673): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6673): Process: com.google.android.gms, PID: 6673
E/AndroidRuntime( 6673): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6673): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6673): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6673): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6673): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6673): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6673): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6673): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6673): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6673): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 3516): Can't write: system_app_crash
E/DropBoxManagerService( 3516): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3516): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3516): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3516): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3516): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3516): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3516): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3516): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3516): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3516): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3516): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3516): 	... 5 more
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0

```
