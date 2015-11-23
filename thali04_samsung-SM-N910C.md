#### Test 503880197c51433_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
V/AlarmManager( 3523): waitForAlarm result :8
--------- beginning of main
I/wpa_supplicant( 3832): nl80211: Received scan results (12 BSSes)
E/WifiStateMachine( 3523): [1,448,299,020,524 ms] noteScanEnd no scan source
D/WifiP2pService( 3523): InactiveState{ what=147461 }
D/WifiP2pService( 3523): P2pEnabledState{ what=147461 }
D/WifiP2pService( 3523): DefaultState{ what=147461 }
E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@d147a87 sup_state=COMPLETED debouncing=false
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3523): waitForAlarm result :4
D/KeyguardViewMediator( 3690): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 3690): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
D/AndroidRuntime(11695): 
D/AndroidRuntime(11695): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11695): CheckJNI is OFF
D/AndroidRuntime(11695): readGMSProperty: start
D/AndroidRuntime(11695): readGMSProperty: already setted!!
D/AndroidRuntime(11695): readGMSProperty: end
D/AndroidRuntime(11695): addProductProperty: start
D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
E/AffinityControl(11695): AffinityControl: registerfunction enter
D/AndroidRuntime(11695): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11710): MountEmulatedStorage()
E/Zygote  (11710): v2
I/libpersona(11710): KNOX_SDCARD checking this for 10419
I/libpersona(11710): KNOX_SDCARD not a persona
I/SELinux (11710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11710 uid=10419 gids={50419, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (11710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11695): Shutting down VM
E/SELinux (11710): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11710): TimaSignature is unavailable
D/ActivityThread(11710): Added TimaKeyStore provider
V/ActivityManager( 3523): Display changed displayId=0
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11710): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/ActivityThread( 6361): updateVisibility : ActivityRecord{4cd92b token=android.os.BinderProxy@3030b61c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11710): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11710): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11710): Loading: webviewchromium
I/LibraryLoader(11710): Time to load native libraries: 4 ms (timestamps 9365-9369)
I/LibraryLoader(11710): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11710): Binding Chromium to main looper Looper (main, tid 1) {2137498a}
I/LibraryLoader(11710): Expected native library version number "",actual native library version number ""
I/chromium(11710): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11710): Initializing chromium process, renderers=0
W/art     (11710): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11710): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11710): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11710): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/PowerManagerService( 3523): [PWL] Off : 5s ago
,W/chromium(11710): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11710): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11710): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11710): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11710): CordovaWebView is running on device made by: samsung
,W/art     (11710): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11710): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11710): performCreate Call secproduct feature valuefalse
D/Activity(11710): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11710): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2851): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer(11710): Initialized EGL, version 1.4
,D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11710): HWUI protection enabled for context ,  &this =0xaf6ad1c8 ,&mEglDisplay = 1 , &mEglConfig = -1278897904 
,D/OpenGLRenderer(11710): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,D/OpenGLRenderer(11710): Enabling debug mode 0
,D/mali_winsys(11710): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11710): updateVisibility : ActivityRecord{2ffd293a token=android.os.BinderProxy@91ee139 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{146b9e86 u0 com.example.hello/.MainActivity t28} time:69881
,W/IInputConnectionWrapper(11710): showStatusIcon on inactive InputConnection
,I/Timeline(11710): Timeline: Activity_idle id: android.os.BinderProxy@91ee139 time:69892
,I/chromium(11710): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(11710): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium(11710): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11710): 
,D/JsMessageQueue(11710): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11710): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357428096
D/JX-Cordova(11710): jxcore cordova android initializing
,W/jxcore-log(11710): Initializing JXcore engine
W/jxcore-log(11710): JXcore engine is ready
,W/jxcore-log(11710): Starting JXcore engine
,E/auditd  ( 4609): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/ActivityManager( 3523): Waited long enough for: ServiceRecord{381963af u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,W/jxcore-log(11710): Platform android
W/jxcore-log(11710): 
W/jxcore-log(11710): Process ARCH arm
W/jxcore-log(11710): 
,I/jxcore-log(11710): JXcore Cordova bridge is ready!
I/jxcore-log(11710): 
W/jxcore-log(11710): JXcore engine is started
,E/jxcore-log(11710): >> samsung-SM-N910C
E/jxcore-log(11710): 
,I/jxcore-log(11710): Total memory 2970812416
I/jxcore-log(11710): 
,I/jxcore-log(11710): Free memory 74649600
I/jxcore-log(11710): 
I/jxcore-log(11710): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11710): 
I/jxcore-log(11710): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11710): 
,I/jxcore-log(11710): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11710): 
,I/jxcore-log(11710): Size 1440 2560
I/jxcore-log(11710): 
,I/jxcore-log(11710): Screen Brightness 134
I/jxcore-log(11710): 
,E/jxcore-log(11710): Dummy Error Log.
E/jxcore-log(11710): 
,I/jxcore-log(11710): getBuffer is called!!!!
I/jxcore-log(11710): 
,V/AlarmManager( 3523): waitForAlarm result :8
,E/Watchdog( 3523): !@Sync 2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3523): waitForAlarm result :4
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:2, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:-23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:150
D/BatteryService( 3523): stay LED for charging
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5689): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5689): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 11811
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 11815
,V/AlarmManager( 3523): waitForAlarm result :4
,D/Finsky  (10639): [1445] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10639): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRM:n  ( 3523): SIOP:: AP = 310, PST = 336, CUR = -23
,D/BluetoothAdapter(11710): disable()
,D/SettingsProvider( 3523): name = bluetooth_on
,D/BluetoothAdapterState( 5689): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5689): Setting state to 13
,I/BluetoothAdapterState( 5689): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5689): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5689): updateAdapterState state is 13
,I/BluetoothPbapService( 5689): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 5689): close() in, this: android.bluetooth.BluetoothSocket@3004f9ec, channel: 19, state: LISTENING
,D/BluetoothSocket( 5689): close() this: android.bluetooth.BluetoothSocket@3004f9ec, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fce4ffd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ecc81b5mSocket: android.net.LocalSocket@396904a impl:android.net.LocalSocketImpl@a4e2bbb fd:FileDescriptor[74]
D/BluetoothSocket( 5689): Closing mSocket: android.net.LocalSocket@396904a impl:android.net.LocalSocketImpl@a4e2bbb fd:FileDescriptor[74]
,D/BluetoothAdapterService( 5689): Autoconnection is available 
,D/BluetoothAdapterService( 5689): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5689): terminating service from this receiver
,D/BluetoothAdapterProperties( 5689): onBluetoothDisable()
,D/SecContentProvider( 3523): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 5689): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5689): Scan Mode:20
,D/BluetoothAdapterState( 5689): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 5689): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5689): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 5689): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 5689): cmd socket is not created
,D/btif_config_util( 5689): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 5689): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 5689): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5689): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5689): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x001b not found for deregistration
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3523): [BT Setting State] State =13
,D/BluetoothTile( 3690):  onBluetoothStateChange:
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/WifiService( 3523): New client listening to asynchronous messages
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,I/SamsungIME( 4463): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/WifiManager(11710): packageName : com.example.hello
D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3523): mCursor = null
D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/BluetoothSocket( 5689): close() in, this: android.bluetooth.BluetoothSocket@36908431, channel: 5, state: LISTENING
D/BluetoothSocket( 5689): close() this: android.bluetooth.BluetoothSocket@36908431, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@201f7454, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32b56716mSocket: android.net.LocalSocket@2da9c897 impl:android.net.LocalSocketImpl@28329a84 fd:FileDescriptor[72]
D/BluetoothSocket( 5689): Closing mSocket: android.net.LocalSocket@2da9c897 impl:android.net.LocalSocketImpl@28329a84 fd:FileDescriptor[72]
,D/WifiService( 3523): setWifiEnabled: false pid=11710, uid=10419
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3523): name = wifi_on
D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
I/BtOppRfcommListener( 5689): stopping Accept Thread
D/BluetoothSocket( 5689): close() in, this: android.bluetooth.BluetoothSocket@eb8326d, channel: 12, state: LISTENING
D/BluetoothSocket( 5689): close() this: android.bluetooth.BluetoothSocket@eb8326d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@365e49f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1118dea2mSocket: android.net.LocalSocket@2eb85733 impl:android.net.LocalSocketImpl@3380daf0 fd:FileDescriptor[77]
D/BluetoothSocket( 5689): Closing mSocket: android.net.LocalSocket@2eb85733 impl:android.net.LocalSocketImpl@3380daf0 fd:FileDescriptor[77]
I/BtOppRfcommListener( 5689): BluetoothSocket listen thread finished
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
I/jxcore-log(11710): ****TEST TOOK:  5158  ms ****
I/jxcore-log(11710): 
,I/jxcore-log(11710): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11710): 
,D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3832): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): P2P: Current p2p state = IDLE
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 3832): Scan requested (ret=0) - scan timeout 30 seconds
V/[CarModeFW](11292): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,W/ContextImpl(10743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.113/24 (Unknown error -1)
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/Zygote  (11836): MountEmulatedStorage()
E/Zygote  (11836): v2
I/libpersona(11836): KNOX_SDCARD checking this for 10022
I/libpersona(11836): KNOX_SDCARD not a persona
I/SELinux (11836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11836 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3523): scanCount==0 - aborting
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/WifiStateMachine( 3523): [1,448,299,028,495 ms] noteScanEnd no scan source
,D/WifiScanningService( 3523): SCAN_AVAILABLE : 1
,W/bt-l2cap( 5689): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5689): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5689): ag scb idx 1 not allocated
W/bt-btif ( 5689): ag scb idx 2 not allocated
D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/bt-btif ( 5689): BTA AG is already disabled, ignoring ...
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/bt_userial( 5689): RX termination
W/bt_userial( 5689): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5689): Leaving userial_read_thread()
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/bt_userial( 5689): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 5689): hw_epilog_process
,D/WifiP2pService( 3523): InactiveState{ what=131204 }
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524292
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
I/bt_userial_vendor( 5689): device fd = 65 close
,D/WifiP2pService( 3523): P2pEnabledState{ what=131204 }
,D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/RttService( 3523): SCAN_AVAILABLE : 1
D/ConnectivityManager.CallbackHandler( 7017): CM callback handler got msg 524292
D/WifiScanningService( 3523): DefaultState got{ when=-9ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3523): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/TimaKeyStoreProvider(11836): TimaSignature is unavailable
D/LocalBluetoothProfileManager(10743): PANU : true
D/LocalBluetoothProfileManager(10743): Adding local MAP profile
,D/BluetoothMap(10743): Create BluetoothMap proxy object
D/ActivityThread(11836): Added TimaKeyStore provider
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/GKI_LINUX( 5689): gki_task task_id=0 [BTU] terminating
D/WifiP2pService( 3523): sending p2p connection changed broadcast: FAILED
,D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/GKI_LINUX( 5689): GKI_exit_task 0 done
I/GKI_LINUX( 5689): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 5689): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5689): isSecureModeOn:false
D/BluetoothAdapterService( 5689): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.gatt.GattService
,D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/WifiDisplayAdapter( 3523): onP2pDisconnected
,D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
,D/WifiP2pService( 3523): sending p2p connection changed broadcast: DISCONNECTED
,D/BtGatt.DebugUtils( 5689): handleDebugAction() action=null
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/BtGatt.GattService( 5689): Received stop request...Stopping profile...
D/BtGatt.GattService( 5689): stop()
D/BtGatt.AdvertiseManager( 5689): advertise clients cleared
W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.hfp.HeadsetService
D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/ResourcesManager(11836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11836): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
,E/ConnectivityService( 3523): updateNetworkInfo()
D/WifiP2pService( 3523): P2pDisablingState
V/NetworkStats( 3523): performPollLocked() took 14ms
D/WifiP2pService( 3523): P2pDisablingState{ what=147458 }
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/WifiP2pService( 3523): p2p socket connection lost
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/WifiP2pService( 3523): P2pDisabledState
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.hid.HidService
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/HeadsetService( 5689): Received stop request...Stopping profile...
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/WifiP2pService( 3523): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3523): DefaultState{ what=143375 }
E/WifiStateMachine( 3523): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3523): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3523): disconnect
D/WifiDisplayController( 3523): updateConnection
D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.hdp.HealthService
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.pan.PanService
D/CommandListener( 2846): Clearing all IP addresses on wlan0
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3523): onP2pDisconnected
D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 1
W/BluetoothAdapterService( 5689): Not skipping com.android.bluetooth.map.BluetoothMapService
E/WifiStateMachine( 3523): stopping supplicant
I/wpa_supplicant( 3832): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3523): setWifiState: disabling
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5689): Not skipping com.broadcom.bt.service.sap.SapService
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
I/LocationWidgetApplication(11836): onCreate() : start
D/LocationWidgetApplication(11836): countryCode = POLAND
D/AllShareCastTile( 3690): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3690): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
W/ContextImpl(10743): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3690): onReceive : 0, 0
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
D/Bluetoothsap(10743): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager(10743): LocalBluetoothProfileManager construction complete
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5689): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5689): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/BluetoothAdapterService( 5689): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5689): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5689): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/BluetoothAdapterState( 5689): Stopping profile services that were post enabled
D/A2dpService( 5689): Received stop request...Stopping profile...
V/Avrcp   ( 5689): doQuit
D/A2dpStateMachine( 5689): Exit Disconnected: -1
D/Avrcp   ( 5689): Unregistering previous receiver
D/DockEventReceiver(10743): finishStartingService: stopping service
D/BluetoothPan(10743): BluetoothPAN Proxy object connected
D/PanProfile(10743): Bluetooth service connected
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
D/BluetoothMap(10743): Proxy object connected
D/MapProfile(10743): Bluetooth service connected
D/Bluetoothsap(10743): BluetoothSAP Proxy object connected
D/SapProfile(10743): Bluetooth service connected
D/Bluetoothsap(10743): getConnectedDevices()
D/BluetoothA2dp( 5017): Proxy object disconnected
D/BluetoothA2dp( 3523): Proxy object disconnected
D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 5689): Received stop request...Stopping profile...
D/HidService( 5689): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5689): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5689): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5689): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothNotiBroadcastReceiver(10743): onReceive
D/BluetoothAdapterService( 5689): Profile still running: com.android.bluetooth.hid.HidService
D/HealthService( 5689): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
I/ActivityManager( 3523): Killing 9966:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
I/wpa_supplicant( 3832): Blacklist: Clear (all) 
D/PanService( 5689): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
,D/BluetoothPan( 3523): BluetoothPAN Proxy object disconnected
D/BluetoothPan(10743): BluetoothPAN Proxy object disconnected
D/PanProfile(10743): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 5689): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5689): Cleaning up Bluetooth Handsfree callback object
D/BluetoothMapService( 5689): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
D/BluetoothMap(10743): Proxy object disconnected
D/MapProfile(10743): Bluetooth service disconnected
D/SapService( 5689): Received stop request...Stopping profile...
D/SapService( 5689): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5689): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2137498a
D/Bluetoothsap(10743): BluetoothSAP Proxy object disconnected
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/SapProfile(10743): Bluetooth service disconnected
D/BluetoothAdapterService( 5689): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5689): Proxy object disconnected
D/BluetoothAdapterService( 5689): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 5689): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5689): GKI_exit_task 2 done
I/GKI_LINUX( 5689): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5689): cleanup
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5689): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5689): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5689): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5689): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5689): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5689): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5689): Cleaning up Bluetooth PAN callback object
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5689): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5689): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(557271434)( 5689): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 5689): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
D/BluetoothAdapterState( 5689): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
W/BluetoothSAPServiceJni( 5689): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterProperties( 5689): Setting state to 10
I/BluetoothAdapterState( 5689): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5689): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5689): updateAdapterState state is 10
D/BluetoothAdapterService( 5689): Autoconnection is available 
D/BluetoothAdapterService( 5689): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5689): Entering OffState
D/AuthorizationBluetoothService( 4186): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Bluetoothsap(10743): onBluetoothStateChange: up=false
D/Bluetoothsap(10743): Unbinding service...
I/Hs20UtilService( 4079): Starting #8
D/BluetoothMap(10743): onBluetoothStateChange: up=false
I/Hs20UtilService( 4079): Message received 5007
D/NearbySettings(10743): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(10743): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(10743): MountReceiver.onReceive - Create mPrefHandler
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/NearbySettings(10743): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(10743): DMSUtil.isNetworkConnected - flag-null, state-null
D/BluetoothA2dp( 5017): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 5689): onBluetoothStateChange: up=false
,I/wpa_supplicant( 3832): p2p0: CTRL-EVENT-TERMINATING 
,I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
I/wpa_supplicant( 3832): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
D/BluetoothA2dp( 3523): onBluetoothStateChange: up=false
,I/wpa_supplicant( 3832): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothPbap(10743): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/AndroidRuntime(11839): 
D/AndroidRuntime(11839): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(11839): CheckJNI is OFF
,D/AndroidRuntime(11839): readGMSProperty: start
D/AndroidRuntime(11839): readGMSProperty: already setted!!
,D/WifiService( 3523): New client listening to asynchronous messages
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/AndroidRuntime(11839): readGMSProperty: end
D/AndroidRuntime(11839): addProductProperty: start
D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceDown() to 14 receivers.
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
I/NearbySettings(10743): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10743): MountReceiver.onReceive - Set preference state off
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
V/NearbySettings(10743): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11528): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3523): [BT Setting State] State =10
I/InputMethodManagerService( 3523): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 3690): 504986916: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 3690): 504986916: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3690): 504986916: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
D/BluetoothAdapter( 3690): 504986916: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3690): 504986916: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
I/SamsungIME( 4463): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager(10743): Received android.bluetooth.adapter.action.STATE_CHANGED
D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/BluetoothAdapter( 4649): 160643243: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4649): 160643243: getState() :  mService = null. Returning STATE_OFF
,D/NearbySettings(10743): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings(10743): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/GKI_LINUX( 5689): gki_task task_id=1 [BTIF] terminating
I/NearbySettings(10743): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10743): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(10743): MountReceiver.mPrefHandler - 7002
I/GKI_LINUX( 5689): GKI_exit_task 1 done
I/GKI_LINUX( 5689): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 5689): cleanupNative: return from cleanup
,I/art     ( 5689): System.exit called, status: 0
I/AndroidRuntime( 5689): VM exiting with result code 0, cleanup skipped.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
V/[CarModeFW](11292): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](11292): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,I/wpa_supplicant( 3832): Blacklist: Clear (all) 
,E/Zygote  (11893): MountEmulatedStorage()
I/libpersona(11893): KNOX_SDCARD checking this for 10079
E/Zygote  (11893): v2
I/libpersona(11893): KNOX_SDCARD not a persona
,I/SELinux (11893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11893 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11893): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/TimaKeyStoreProvider(11893): TimaSignature is unavailable
,D/ActivityThread(11893): Added TimaKeyStore provider
,D/ResourcesManager(11893): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/ActivityManager( 3523): Process com.android.bluetooth (pid 5689)(adj 0) has died(96,1234)
,D/FileShare-Server(11893): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3523): Killing 11153:com.policydm/1000 (adj 15): bgCount ##31
,E/AffinityControl(11839): AffinityControl: registerfunction enter
,I/Hs20UtilService( 4079): Starting #9
,I/Hs20UtilService( 4079): Message received 5007
,D/NearbySettings(10743): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(10743): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(10743): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(10743): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(10743): MountReceiver.onReceive - Set preference state off
V/NearbySettings(10743): MountReceiver.mPrefHandler - 7002
,D/AndroidRuntime(11839): Calling main entry com.android.commands.pm.Pm
,I/SignOutReceiver(11528): NETWORK_STATE_CHANGED_ACTION
,D/PackageManager( 3523): START PACKAGE DELETE: observer{858598187}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
,D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3523): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3523): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3523): !@killApplicatoin: 10419, uninstall pkg
,I/Hs20UtilService( 4079): Starting #10
I/ActivityManager( 3523): Force stopping com.example.hello appid=10419 user=-1: uninstall pkg
I/ActivityManager( 3523): Killing 11710:com.example.hello/u0a419 (adj 0): stop com.example.hello
I/Hs20UtilService( 4079): Message received 5011
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{146b9e86 u0 com.example.hello/.MainActivity t28}
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,W/PackageSettings( 3523): Skipping PackageSetting{2cf01a51 com.test.thalitest/10418} due to missing metadata
,I/WindowState( 3523): WIN DEATH: Window{93b453c u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger( 2851): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger( 2851): id=13 Removed NainActivit (-2/8)
D/WifiService( 3523): Client connection lost with reason: 4
,I/SurfaceFlinger( 2851): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3523): Force stopping com.example.hello appid=10419 user=0: pkg removed
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{146b9e86 u0 com.example.hello/.MainActivity t28 f}
W/ActivityManager( 3523): Duplicate finish request for ActivityRecord{146b9e86 u0 com.example.hello/.MainActivity t28 f}
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 8184): Explicit concurrent mark sweep GC freed 27390(1557KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.079ms total 42.716ms
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 32753(2015KB) AllocSpace objects, 2(103KB) LOS objects, 21% free, 28MB/36MB, paused 7.611ms total 50.704ms
,E/SamsungIME( 4463): mOCRHelper is null
,W/GeofencerStateMachine( 4649): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/LocationManagerService( 3523): getProviders()=[]
,D/LocationManagerService( 3523): getProviders()=[passive]
D/LocationManagerService( 3523): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
E/Zygote  (11912): MountEmulatedStorage()
E/Zygote  (11912): v2
I/libpersona(11912): KNOX_SDCARD checking this for 10127
I/libpersona(11912): KNOX_SDCARD not a persona
I/SELinux (11912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/SELinux (11912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11912 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (11912): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(11912): TimaSignature is unavailable
,I/DBG_DM  ( 6361): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ActivityThread(11912): Added TimaKeyStore provider
,D/LWLocationManager(11836): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11836): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 5
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 70579(4MB) AllocSpace objects, 16(256KB) LOS objects, 24% free, 49MB/65MB, paused 2.561ms total 172.854ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/art     ( 3523): WaitForGcToComplete blocked for 44.411ms for cause Explicit
,W/ResourceType( 5391): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
W/ResourceType( 5391): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 5391): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 5391): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6361): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 5
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6361): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourceType( 5391): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5391): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/wpa_supplicant( 3832): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine( 3523): Supplicant connection lost
,D/Tethering( 3523): InitialState.processMessage what=4
,D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
,E/Tethering( 3523): No numeric data
,D/ResourcesManager(11912): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL( 3523): callSECApiBoolean - ID [21]
D/Tethering( 3523): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine( 3523): setWifiState: disabled
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 5
,V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/HotspotTile( 3690): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3690): updateTetherState():false, false
,I/DBG_DM  ( 6361): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6361): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6361): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6361): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6361): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,V/NetworkStats( 3523): performPollLocked() took 17ms
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,I/DBG_DM  ( 6361): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/KeyguardWallpaperUpdator(11912): cancelUpdateWallpaper
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/HotspotTile( 3690): onReceive : 1, 0
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/SurfaceFlinger( 2851): id=14 createSurf (1440x2560),2 flag=404, YUIInstallC
,W/Settings( 4649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 3966): empty dynamic service
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/KeyguardWallpaperUpdator(11912): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11912): stopCheckCategoryVersion
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/DBG_DM  ( 6361): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/DBG_DM  ( 6361): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/SignOutReceiver(11528): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
V/ActivityThread( 6361): updateVisibility : ActivityRecord{4cd92b token=android.os.BinderProxy@3030b61c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (11932): MountEmulatedStorage()
E/Zygote  (11932): v2
I/libpersona(11932): KNOX_SDCARD checking this for 1000
I/libpersona(11932): KNOX_SDCARD not a persona
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 11752(620KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 3.041ms total 171.039ms
I/SELinux (11932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11932): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3523): Killing 11169:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8768(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 901us total 23.038ms
,W/ResourcesManager(11836): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/InputMethodManagerService( 3523): Got RemoteException sending setActive(false) notification to pid 11710 uid 10419
,I/Timeline( 6361): Timeline: Activity_idle id: android.os.BinderProxy@3030b61c time:76638
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 865us total 19.161ms
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{1d068f96 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t27} time:76658
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 885us total 13.551ms
,D/TimaKeyStoreProvider(11932): TimaSignature is unavailable
,D/ActivityThread(11932): Added TimaKeyStore provider
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(11932): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11836): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11836): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/ActivityManager( 3523): Killing 11080:com.android.mms/u0a52 (adj 13): bgCount ##31
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/ContextImpl(10743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/PackageManager( 3523): delete codoeFile: 
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/AASAUninstall( 3523):  com.example.hello not target!
,D/PackageManager( 3523): result of delete: 1{858598187}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/AndroidRuntime(11839): Shutting down VM
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/DockEventReceiver(10743): finishStartingService: stopping service
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11836): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/UsbSettingsManager( 3523): clearDefaults: com.example.hello
,I/CrashAnrDetector( 3523): onPackageRemoved : com.example.hello
D/BluetoothNotiBroadcastReceiver(10743): onReceive
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/CountryDetector( 3523): No listener is left
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  (11952): MountEmulatedStorage()
E/Zygote  (11952): v2
I/libpersona(11952): KNOX_SDCARD checking this for 1002
I/libpersona(11952): KNOX_SDCARD not a persona
,I/SELinux (11952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=11952 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/TimaKeyStoreProvider(11952): TimaSignature is unavailable
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ActivityThread(11952): Added TimaKeyStore provider
,D/RCPManagerService( 3523): PackageReceiver onReceive()
,I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10419
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,W/SLocation( 3523): No Active Data Connection
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11952): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(11952): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager(11952): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=28_task.xml
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=27_task.xml
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Books/Books.apk
,I/BluetoothA2dpSinkServiceJni(11952): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,I/ApplicationPolicy( 3523): updateDataUsageMap
,I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
,D/BtSettings.ProfileConfig(11952): Adding GattService
D/BtSettings.ProfileConfig(11952): Adding HeadsetService
D/BtSettings.ProfileConfig(11952): Adding A2dpService
D/BtSettings.ProfileConfig(11952): Adding HidService
D/BtSettings.ProfileConfig(11952): Adding HealthService
,D/BtSettings.ProfileConfig(11952): Adding PanService
D/BtSettings.ProfileConfig(11952): Adding BluetoothMapService
D/BtSettings.ProfileConfig(11952): Adding SapService
D/BtSettings.ProfileConfig(11952): Adding HeadsetClientService
D/BtSettings.ProfileConfig(11952): Adding A2dpSinkService
D/BtSettings.ProfileConfig(11952): Adding SapClientService
D/BtSettings.ProfileConfig(11952): Adding HidDevService
I/BtSettings.ProfileConfig(11952): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/StatusBar( 3690): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
D/SettingsProvider( 3523): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PanelView( 3690): There is/are notification(s) 
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/ActivityManager( 3523): Killing 11186:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/AuthorizationBluetoothService( 4186): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,E/Zygote  (11969): MountEmulatedStorage()
E/Zygote  (11969): v2
I/libpersona(11969): KNOX_SDCARD checking this for 10063
I/libpersona(11969): KNOX_SDCARD not a persona
,I/SELinux (11969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11969 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider(11969): TimaSignature is unavailable
,D/ActivityThread(11969): Added TimaKeyStore provider
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager(11969): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/VRSetupWizardStub/PackageIntentReceiver(11969): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(11969): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11969): packagename:com.example.hello
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(11836): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/Zygote  (11985): MountEmulatedStorage()
,E/Zygote  (11985): v2
I/libpersona(11985): KNOX_SDCARD checking this for 10021
I/libpersona(11985): KNOX_SDCARD not a persona
,I/SELinux (11985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11985 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(11836): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/SELinux (11985): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 11215:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(11836): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/TimaKeyStoreProvider(11985): TimaSignature is unavailable
,D/ActivityThread(11985): Added TimaKeyStore provider
,D/ResourcesManager(11836): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(11985): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(11836): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/KLMS-2.4.521: (11985): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 18:17:09 GMT+01:00 2015
,I/KLMS-2.4.521: (11985): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11985): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11985): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11985): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11985): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11985): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (11985): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  (12001): MountEmulatedStorage()
E/Zygote  (12001): v2
I/libpersona(12001): KNOX_SDCARD checking this for 10106
I/KLMS-2.4.521: (11985): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
I/libpersona(12001): KNOX_SDCARD not a persona
,I/SELinux (12001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12001 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
I/SELinux (12001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12001): TimaSignature is unavailable
,D/ActivityThread(12001): Added TimaKeyStore provider
,E/Zygote  (12022): MountEmulatedStorage()
E/Zygote  (12022): v2
I/libpersona(12022): KNOX_SDCARD checking this for 10050
I/libpersona(12022): KNOX_SDCARD not a persona
,I/SELinux (12022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12022 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
,W/ContextImpl(11454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/KLMS-2.4.521: (11985): KLMSIntentService(): listeningToPackageRemoved().END
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,D/TimaKeyStoreProvider(12022): TimaSignature is unavailable
,D/ActivityThread(12022): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11985): KLMSIntentService(): onDestroy()
,D/ResourcesManager(12001): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,D/elm:14491(12001): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12001): ELMEngine.ELMEngine( context ).
,D/elm:14491(12001): MDMBridge.setEnterpriseBridge()
,E/Zygote  (12040): MountEmulatedStorage()
E/Zygote  (12040): v2
I/libpersona(12040): KNOX_SDCARD checking this for 10190
I/libpersona(12040): KNOX_SDCARD not a persona
,I/SELinux (12040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12040 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 10116
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=12054 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
,D/elm:14491(12001): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TimaKeyStoreProvider(12040): TimaSignature is unavailable
,D/ActivityThread(12040): Added TimaKeyStore provider
D/elm:14491(12001): ElmAgentService : onCreate()
,D/elm:14491(12001): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12001): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12001): MDMBridge.getInstance()
D/elm:14491(12001): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12001): MDMBridge.getAllLicenseInfoFromSDK()
,I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12022): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12022): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:14491(12001): ElmAgentService : onDestroy().
,D/ResourcesManager(12040): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12040): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12040): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/ResourcesManager(12054): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,E/Zygote  (12072): MountEmulatedStorage()
E/Zygote  (12072): v2
I/libpersona(12072): KNOX_SDCARD checking this for 10019
I/libpersona(12072): KNOX_SDCARD not a persona
I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,I/SELinux (12072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12072 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/SELinux (12072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TapandpayWidget:Utils(12040): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12040): Widget is not attached.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12072): TimaSignature is unavailable
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12072): Added TimaKeyStore provider
,E/Zygote  (12088): MountEmulatedStorage()
E/Zygote  (12088): v2
I/libpersona(12088): KNOX_SDCARD checking this for 1000
I/libpersona(12088): KNOX_SDCARD not a persona
,I/SELinux (12088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
,E/SELinux (12088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=12088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11231:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11231/oom_score_adj; errno=22
,E/SQLiteLog(12022): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)

```
