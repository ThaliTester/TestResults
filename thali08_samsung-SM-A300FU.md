#### Test 62509094b685d58_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 12:28:18.254  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
--------- beginning of system
03-17 12:28:18.254  1020  1565 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 12:28:18.264  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.274  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.294  2662  2662 D BluetoothAdapterState: make
03-17 12:28:18.294  1020  1502 D SettingsProvider: name = db_smartlock_supported
03-17 12:28:18.294  2662  2662 I bluedroid: init
03-17 12:28:18.294  2662  2747 I BluetoothAdapterState: Entering OffState
03-17 12:28:18.304  2662  2662 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
03-17 12:28:18.304  2662  2662 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
03-17 12:28:18.304  2662  2662 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
03-17 12:28:18.304  2662  2662 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
03-17 12:28:18.304  2662  2662 E bt-btif : btif_fetch_local_ble_random_bdaddr
03-17 12:28:18.304  2662  2662 I bluedroid: get_profile_interface socket
03-17 12:28:18.304  2662  2662 I bluedroid: get_profile_interface map_client
03-17 12:28:18.304  2662  2662 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
03-17 12:28:18.314  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.314  1020  1242 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.314  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.324  2662  2751 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
03-17 12:28:18.324  2662  2751 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-17 12:28:18.324  2662  2751 E BluetoothServiceJni: populateRssiValuesNative
03-17 12:28:18.324  2662  2751 I bluedroid: getModelRssiValues
03-17 12:28:18.324  2662  2751 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 12:28:18.324  2662  2751 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-17 12:28:18.324  1020  1020 D SettingsProvider: name = bluetooth_name
03-17 12:28:18.324  2662  2751 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-17 12:28:18.334  2662  2670 I bluedroid: config_hci_snoop_log
03-17 12:28:18.334  1020  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
03-17 12:28:18.334  1020  1050 D BluetoothManagerService: Ble is always on enable gatt
03-17 12:28:18.334  1020  1050 I BluetoothManagerService: enableGattForLeMode, doBind called
03-17 12:28:18.344  1020  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-17 12:28:18.344  1020  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-17 12:28:18.344  1020  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
03-17 12:28:18.354  2662  2747 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
03-17 12:28:18.354  2662  2747 D BluetoothAdapterProperties: Setting state to 11
,03-17 12:28:18.354  2662  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
03-17 12:28:18.354  2662  2747 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 12:28:18.354  2662  2747 D BluetoothAdapterService: updateAdapterState state is 11
03-17 12:28:18.354  2662  2747 D BluetoothAdapterService: Autoconnection is available 
03-17 12:28:18.354  2662  2747 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
03-17 12:28:18.354  2662  2747 D BluetoothSecureManager: getInstant: null
03-17 12:28:18.354  2662  2747 D BluetoothSecureManager: calling getMethod for getService
03-17 12:28:18.364  2662  2747 D BluetoothSecureManager: calling getService
03-17 12:28:18.364  1020  1060 D PackageManager: [MSG] MCS_UNBIND
03-17 12:28:18.364  2662  2747 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@30df0802
03-17 12:28:18.374  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 12:28:18.374  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 12:28:18.374  1173  1173 D BluetoothTile:  getBluetoothState : 11
03-17 12:28:18.374  1866  1866 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 12:28:18.374  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 12:28:18.374  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
03-17 12:28:18.374  2662  2662 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
03-17 12:28:18.374  1173  1631 D BluetoothTile:  handleUpdatestate:false name:null
03-17 12:28:18.374  1173  1631 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
03-17 12:28:18.384  1020  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 12:28:18.384  1020  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
03-17 12:28:18.394  1020  1486 D BluetoothSecureManagerService: isSecureModeEnabled
03-17 12:28:18.394  1020  1486 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
03-17 12:28:18.394  2662  2747 D BtConfig.SecureMode: isSecureModeOn:false
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-17 12:28:18.394  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
03-17 12:28:18.394  1020  1242 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
03-17 12:28:18.394  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
03-17 12:28:18.394  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
03-17 12:28:18.394  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
03-17 12:28:18.394  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
03-17 12:28:18.394  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
03-17 12:28:18.404  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
03-17 12:28:18.404  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
03-17 12:28:18.404  2662  2747 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
03-17 12:28:18.404  2662  2747 D BluetoothBondStateMachine: make
03-17 12:28:18.404  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
03-17 12:28:18.414  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
03-17 12:28:18.414  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-17 12:28:18.414  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
03-17 12:28:18.414  2662  2755 I BluetoothBondStateMachine: StableState(): Entering Off State
03-17 12:28:18.414  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:18.414  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:18.414  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.414  1020  1242 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.414  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.414  2662  2662 D BtGatt.DebugUtils: handleDebugAction() action=null
03-17 12:28:18.414  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
03-17 12:28:18.414  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
03-17 12:28:18.414  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
03-17 12:28:18.414  2662  2662 D BtGatt.GattService: Received start request. Starting profile...
03-17 12:28:18.414  2662  2662 D BtGatt.GattService: start()
03-17 12:28:18.414  2662  2662 D BtGatt.GattService: start()
03-17 12:28:18.414  2662  2662 I bluedroid: get_profile_interface gatt
03-17 12:28:18.414  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.414  2662  2662 D BtGatt.AdvertiseManager: advertise manager created
03-17 12:28:18.414  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.414  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.414  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.424  1020  1565 I AccessibilityManagerService: setmDNIeNegative (false)
03-17 12:28:18.424  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
03-17 12:28:18.424  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
03-17 12:28:18.424  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
03-17 12:28:18.434  1020  1567 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.434  1020  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.434  1020  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.434  2662  2662 D BtGatt.GattService: mStartError = false
03-17 12:28:18.434  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.444  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
03-17 12:28:18.444  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
03-17 12:28:18.444  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
03-17 12:28:18.444  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.444  1020  1242 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.444  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: pid: 3299, tid: 3630, name: Thread-458  >>> com.test.thalitest <<<
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9eaf4734  r2 00000002  r3 00000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     r4 b8f0ab70  r5 00000000  r6 b8f0a400  r7 b9e05d98
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     r8 b8f41fec  r9 b8f0ab70  sl b8f0a3d8  fp 9eaf472c
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 9eaf471c  lr 9efcfb30  pc 9efcfa34  cpsr 60000010
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     scr 20000017
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf469c  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46a0  b9259cb0  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46a4  b8f0ab70  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46a8  0000000b  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46ac  b9259670  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46b0  9eaf46cc  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46b4  9f043904  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::jit::BaselineScript::trace(JSTracer*)+120)
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46b8  00000001  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46bc  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46c0  b8f0b6a0  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46c4  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46c8  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46cc  b8f0ab70  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46d0  b8f0b6a0  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46d4  9f65bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46d8  9eaf4744  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46dc  9efd6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46e0  b8f0ab70  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46e4  b8f0a3d8  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46e8  9eafa000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46ec  9eaf4710  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46f0  9eaf4708  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46f4  9eaf4714  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46f8  9f5826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf46fc  9eaf4718  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4700  00000004  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4704  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4708  00000001  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf470c  b8f0ab70  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4710  9252f640  [anon:js-gc-heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4714  b8f0a400  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4718  9eaf472c  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     #00  9eaf471c  9eaf472c  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4720  9eaf9838  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4724  b9e01490  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4728  9eaf4744  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf472c  9efd306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:     #01  9eaf4730  b8f41fec  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4734  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4738  b8f0a3fc  [heap]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf473c  9f503cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4740  9eaf479c  [stack:3630]
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4744  9efd7dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          9eaf4748  00000000  
03-17 12:28:18.444  1020  1020 D CrashAnrDetector:          
03-17 12:28:18.444  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:18.444  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:18.444  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
03-17 12:28:18.444  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
03-17 12:28:18.454  2662  2662 D HeadsetService: Received start request. Starting profile...
03-17 12:28:18.454  2662  2662 D HeadsetService: start()
03-17 12:28:18.454  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:18.454  2662  2662 I BluetoothHeadsetServiceJni: classInitNative: succeeds
03-17 12:28:18.454  2662  2662 D HeadsetStateMachine: make
03-17 12:28:18.454  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.454  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.454  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.454  2662  2662 E HeadsetStateMachine: # of Max HF connection is 2
03-17 12:28:18.464  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
03-17 12:28:18.464  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
03-17 12:28:18.464  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
03-17 12:28:18.464  1020  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.464  1020  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.464  1020  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-17 12:28:18.464  1020  1502 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.464  1020  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.464  1020  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.474  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
03-17 12:28:18.474  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
03-17 12:28:18.474  2662  2747 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
03-17 12:28:18.474  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.474  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.474  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.474  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
03-17 12:28:18.474  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
03-17 12:28:18.474  2662  2747 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
03-17 12:28:18.474  1020  1301 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.474  1020  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.474  1020  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
03-17 12:28:18.484  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:18.484  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 12:28:18.484  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:18.484  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
03-17 12:28:18.484  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
03-17 12:28:18.484  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
03-17 12:28:18.484  2662  2747 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
03-17 12:28:18.484  2662  2747 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
03-17 12:28:18.484  2662  2747 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
03-17 12:28:18.484  2662  2662 I bluedroid: get_profile_interface handsfree
03-17 12:28:18.484  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.494  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.494  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.494  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.504  1317  1317 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-17 12:28:18.504  2763  2763 E Zygote  : MountEmulatedStorage()
03-17 12:28:18.504  2763  2763 I libpersona: KNOX_SDCARD checking this for 10117
03-17 12:28:18.504  2763  2763 E Zygote  : v2
03-17 12:28:18.504  2763  2763 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:18.504  2763  2763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:18.504  1020  1045 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=2763 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:28:18.504  2662  2662 I DualScoManager: Instantiating Dual Sco Manager
03-17 12:28:18.504  2662  2662 I DualScoManager: Set HeadsetServiceHelper
03-17 12:28:18.504  2763  2763 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:18.504  2662  2662 D BluetoothAtMessage: createCMTIContentObservers
03-17 12:28:18.504  1020  1486 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
03-17 12:28:18.504  1020  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:18.504  1020  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:18.504  1020  1486 D SettingsProvider: selectionArgs: false
03-17 12:28:18.504  1020  1486 D SettingsProvider: selectionArgs: 1002
03-17 12:28:18.504  1020  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:18.504  1020  1486 D SettingsProvider: ret = -1
03-17 12:28:18.504  2763  2763 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:18.514  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_1193/cgroup.procs: No such file or directory
03-17 12:28:18.524  2722  2773 D DelayedSyncController: Delaying sync.
03-17 12:28:18.524  1020  1486 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 12:28:18.524  2662  2762 D HeadsetStateMachine: Enter Disconnected: -2
03-17 12:28:18.534  2662  2662 D HeadsetService: mStartError = false
03-17 12:28:18.534  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.534  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
03-17 12:28:18.534  2763  2763 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:18.534  1020  1020 D BluetoothA2dp: Proxy object connected
03-17 12:28:18.534  2763  2763 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:18.534  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:18.534  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:18.534  2662  2662 D A2dpService: Received start request. Starting profile...
03-17 12:28:18.534  2662  2662 D A2dpService: start()
03-17 12:28:18.534  2662  2662 I BluetoothAvrcpServiceJni: classInitNative: succeeds
03-17 12:28:18.534  2662  2662 I bluedroid: get_profile_interface avrcp
03-17 12:28:18.544  2090  2774 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
03-17 12:28:18.544  2662  2762 D HeadsetStateMachine: Clear mHeadsetBrsf
03-17 12:28:18.544  2662  2762 D HeadsetStateMachine: map size, before remove : 0
03-17 12:28:18.544  2662  2762 D HeadsetStateMachine: map size, after remove: 0
03-17 12:28:18.564  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.564  1020  1045 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 25036, reason: UserStart, SyncResult: databaseError: true stats []
03-17 12:28:18.564  1020  1045 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 64202, reason: UserStart
03-17 12:28:18.574  2662  2662 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
03-17 12:28:18.584  1020  1566 D SettingsProvider: name = block_emergency_message
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: pid: 5627, tid: 6272, name: Thread-956  >>> com.test.thalitest <<<
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d40bff0
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     r0 703224a8  r1 728378f8  r2 12d40cc0  r3 134181a0
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     r4 000000c2  r5 703224a8  r6 728378f8  r7 134181a0
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     r8 728378a0  r9 ba06ac88  sl 12d40cc0  fp 9d50d8a8
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     ip 9d40bff0  sp 9d40dff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d0  12d40cc0728378a0  d1  0073002000650081
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d2  c0c0c0c0c0c0c041  d3  0102020202020213
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d4  0040404040404040  d5  0004000400040004
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0003000400040004
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d16 0000000000000000  d17 7320656d69746e75
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d18 0069007200750064  d19 007200200067006e
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d20 0101010101010101  d21 0101010101010101
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d22 8080808080808080  d23 8080808080808080
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d24 4000404040404040  d25 0040404040404040
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d28 0101010101010101  d29 0101010101010101
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     d30 0000000000000000  d31 0000000000000000
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     #00 pc 0009230c  /system/framework/arm/boot.oat
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     #01 pc 00092387  /system/framework/arm/boot.oat
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: 
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df70  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df74  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df78  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df7c  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df80  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df84  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df88  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df8c  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df90  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df94  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df98  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40df9c  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfa0  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfa4  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfa8  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfac  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfb0  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfb4  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfb8  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfbc  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfc0  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfc4  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfc8  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfcc  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfd4  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfd8  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfdc  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfe0  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfe8  e3a070ad  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dfec  ef9000ad  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     #00  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          ........  ........
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:     #01  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dff4  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dff8  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40dffc  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e000  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e004  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e010  134181a0  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e018  12d40cc0  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e01c  7541f33d  /system/framework/arm/boot.oat
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e024  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e028  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e02c  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e034  00000000  
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e040  134181a0  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:18.584  1020  1020 D CrashAnrDetector:          9d40e044  728
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:18.584  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:18.584  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:18.584  2763  2763 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:18.604  2662  2662 I Avrcp   :  Updating now playing list upon AVRCP Start
03-17 12:28:18.604  2662  2785 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 12:28:18.604  1020  1032 D SettingsProvider: name = safetycare_geolookout_registering
03-17 12:28:18.614  2662  2662 I BluetoothA2dpServiceJni: classInitNative: succeeds
03-17 12:28:18.614  2662  2662 D A2dpStateMachine: make
03-17 12:28:18.614  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 12:28:18.614  2662  2662 I bluedroid: get_profile_interface a2dp
03-17 12:28:18.614  2662  2788 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
03-17 12:28:18.614  2662  2662 E bt-btif : warning : media task started media_task_refcnt 1 
03-17 12:28:18.624  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.624  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 12:28:18.624  2662  2662 D A2dpService: mStartError = false
03-17 12:28:18.624  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.624  2662  2787 D A2dpStateMachine: Enter Disconnected: -2
03-17 12:28:18.624  2662  2785 D BluetoothMediaBrowser: no now playing list
03-17 12:28:18.624  2662  2785 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 12:28:18.634  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:18.634  1020  1567 I ActivityManager: Killing 1518:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
03-17 12:28:18.644  1020  1485 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 12:28:18.644  1020  1485 D SecContentProvider2: mCursor = null
03-17 12:28:18.674  2662  2662 I BluetoothHidServiceJni: classInitNative: succeeds
03-17 12:28:18.684   299   299 E USB_UICC: Timeout! No signal received. Retry num = 27
03-17 12:28:18.704   320   320 I ServiceManager: Waiting for service AtCmdFwd...
03-17 12:28:18.714  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_1518/cgroup.procs: No such file or directory
03-17 12:28:18.724  2662  2662 D HidService: Received start request. Starting profile...
03-17 12:28:18.724  2662  2662 D HidService: start()
03-17 12:28:18.724  2662  2662 I bluedroid: get_profile_interface hidhost
03-17 12:28:18.724  2662  2662 D HidService: setHidService(): set to: null
03-17 12:28:18.724  2662  2662 D HidService: mStartError = false
03-17 12:28:18.724  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.724  2662  2662 I BluetoothHealthServiceJni: classInitNative: succeeds
03-17 12:28:18.724  2662  2662 D HealthService: Received start request. Starting profile...
03-17 12:28:18.724  2662  2662 D HealthService: start()
03-17 12:28:18.734  2662  2662 I bluedroid: get_profile_interface health
03-17 12:28:18.734  2662  2662 D HealthService: mStartError = false
03-17 12:28:18.734  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.734  2662  2662 I BluetoothPanServiceJni: classInitNative(L105): succeeds
03-17 12:28:18.744  2662  2662 D PanService: Received start request. Starting profile...
03-17 12:28:18.744  2662  2662 D PanService: start()
03-17 12:28:18.744  2662  2662 D BluetoothPanServiceJni: initializeNative(L110): pan
03-17 12:28:18.744  2662  2662 I bluedroid: get_profile_interface pan
03-17 12:28:18.744  2662  2662 D PanService: mStartError = false
03-17 12:28:18.744  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.744  2662  2662 D HeadsetStateMachine: Try to query the phonestate on bind
03-17 12:28:18.744  1437  1448 I Telecom : BluetoothPhoneService: queryPhoneState
03-17 12:28:18.744  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
03-17 12:28:18.744  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-17 12:28:18.754  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 12:28:18.754  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 12:28:18.754  1020  1301 I ActivityManager: Killing 1402:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
03-17 12:28:18.764  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-17 12:28:18.764  1437  1437 W BluetoothHeadset: Proxy not attached to service
03-17 12:28:18.764  1437  1448 I Telecom : BluetoothPhoneService: Result of Message : true
03-17 12:28:18.774  2662  2662 D BluetoothMapService: Received start request. Starting profile...
03-17 12:28:18.774  2662  2662 D BluetoothMapService: start()
03-17 12:28:18.784  2662  2662 D BluetoothMapService: mStartError = false
03-17 12:28:18.784  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.784  2662  2662 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
03-17 12:28:18.844  2424  2437 W CursorWrapperInner: Cursor finalized without prior close()
03-17 12:28:18.844  2662  2662 D SapService: Received start request. Starting profile...
03-17 12:28:18.844  2662  2662 D SapService: start()
03-17 12:28:18.844  2662  2662 D BluetoothSAPServiceJni: initializeNative(L209): sap
03-17 12:28:18.844  2662  2662 I bluedroid: get_profile_interface sap
03-17 12:28:18.844  2662  2662 D SapService: mStartError = false
03-17 12:28:18.844  2662  2662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@272a6daa
03-17 12:28:18.844  2662  2662 D HeadsetStateMachine: Proxy object connected
03-17 12:28:18.844  2662  2662 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
03-17 12:28:18.844  2662  2662 D HeadsetPhoneState: sendDeviceDataStateChanged
03-17 12:28:18.844  2662  2662 D HeadsetPhoneState: Signal level : previous=0 curr=0
03-17 12:28:18.844  2662  2762 D HeadsetStateMachine: Disconnected process message: 11
03-17 12:28:18.844  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
03-17 12:28:18.844  2662  2762 D HeadsetStateMachine: Disconnected process message: 18
03-17 12:28:18.844  2662  2662 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 12:28:18.844  2662  2662 D BluetoothA2dp: Proxy object connected
03-17 12:28:18.844  2662  2662 D BluetoothAdapterService: Bluetooth A2dp source service connected
03-17 12:28:18.844  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
03-17 12:28:18.844  2662  2762 D HeadsetStateMachine: Disconnected process message: 10
03-17 12:28:18.844  2662  2762 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-17 12:28:18.844  2662  2762 D HeadsetStateMachine: Disconnected process message: 11
03-17 12:28:18.854  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
03-17 12:28:18.854  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
03-17 12:28:18.854  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
03-17 12:28:18.854  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.854  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.854  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.854  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:18.864  2794  2794 E Zygote  : MountEmulatedStorage()
03-17 12:28:18.864  2794  2794 I libpersona: KNOX_SDCARD checking this for 10141
03-17 12:28:18.864  2794  2794 E Zygote  : v2
03-17 12:28:18.864  2794  2794 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:18.874  2794  2794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:18.874  2794  2794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:18.874  1020  1502 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2794 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-17 12:28:18.874  1020  1045 W libprocessgroup: failed to open /acct/uid_10092/pid_1402/cgroup.procs: No such file or directory
03-17 12:28:18.874  2794  2794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:18.894  2794  2794 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:18.894  2794  2794 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:18.914  2794  2794 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 12:28:18.914  2794  2794 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:18.914  2794  2794 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:18.914  2794  2794 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 12:28:18.954  1020  1095 E SmartFaceService: onReceive: android.intent.action.BOOT_COMPLETED
03-17 12:28:18.954  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
03-17 12:28:18.954  1020  1095 D SmartFaceIndicator: no icon
03-17 12:28:18.954  1020  1095 E SmartFaceService: mActiveServiceType: 0
03-17 12:28:18.954  1020  1095 E SmartFaceService: mLightIntensityEnough: true mLux: 0.0
03-17 12:28:18.954  1020  1095 D Stay/Rotation Worker: updateClientsDone. def. do nothing.
03-17 12:28:18.954  1020  1095 E SmartFaceService: Service Type to Worker: 0
03-17 12:28:18.954  1020  1095 E SmartFaceService: Last Active clients:0 Current Active clients: 0
03-17 12:28:18.954  1020  1095 E SmartFaceService: Last Smart Pause clients: 0 Current Smart Pause clients: 0
03-17 12:28:18.954  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
03-17 12:28:18.954  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 12:28:18.954  1020  1020 D SensorService: [SO] activate (ident=0xb92185d0, enabled=0)
03-17 12:28:18.954  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 12:28:18.974  1020  1020 D SensorManager: unregisterListener ::   
03-17 12:28:18.974  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-17 12:28:18.974  1020  1020 D SensorService: [SO] changed settle time [0]
03-17 12:28:18.974  1020  1020 D SensorService: [SO] setDelay [200000000]
03-17 12:28:18.974  1020  1020 D SensorService: [SO] activate (ident=0xb92185d0, enabled=1)
03-17 12:28:18.974  1020  1020 D SensorService: [SO] AR_init
03-17 12:28:18.974  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 12:28:18.974  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 12:28:18.974  1020  1020 D RCPManagerService: ACTION_BOOT_COMPLETED
03-17 12:28:18.974  1020  1020 E RCPManagerService:  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
03-17 12:28:18.984  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:28:18.984  1020  1020 D RCPManagerService: BootReceiver.onReceive(): Starting RCP Proxy for user = null
03-17 12:28:18.984  1020  1020 E RCPManagerService:  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
03-17 12:28:18.984  1020  1020 V AlarmManagerEXT: mGmsLocationBundling: false
03-17 12:28:18.984  1020  1020 D MotionRecognitionService:   mReceiver.onReceive : ACTION_BOOT_COMPLETED
03-17 12:28:19.044  1845  1845 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 12:28:19.044  1845  1845 I dhcpcd  : wlan0: no IPv6 Routers available
03-17 12:28:19.074  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:19.074  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:19.114  2757  2757 D AndroidRuntime: 
03-17 12:28:19.114  2757  2757 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:28:19.114  2757  2757 D AndroidRuntime: CheckJNI is OFF
03-17 12:28:19.114  2757  2757 D AndroidRuntime: readGMSProperty: start
03-17 12:28:19.114  2757  2757 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:28:19.114  2757  2757 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:28:19.114  2757  2757 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:28:19.114  2757  2757 D AndroidRuntime: readGMSProperty: end
03-17 12:28:19.114  2757  2757 D AndroidRuntime: addProductProperty: start
03-17 12:28:19.134  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
03-17 12:28:19.134  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
03-17 12:28:19.144  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
03-17 12:28:19.144  1020  1020 D EnterpriseDeviceManagerService: android.intent.action.BOOT_COMPLETED
03-17 12:28:19.144  1020  1153 D EnterpriseDeviceManagerService: runAdminUpdate
03-17 12:28:19.144  1020  1153 D EnterpriseUtils: File Not Found : /data/system/selfUpdateAdmin.conf
03-17 12:28:19.144  1020  1153 D EnterpriseDeviceManagerService: nothing to selfUpdate
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: pid: 5655, tid: 6424, name: Thread-966  >>> com.test.thalitest <<<
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d209ff0
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     r0 703224a8  r1 728378f8  r2 12c0ba50  r3 133acf40
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     r4 000000c2  r5 703224a8  r6 728378f8  r7 133acf40
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     r8 728378a0  r9 b90e0430  sl 12c0ba50  fp 9d30b8a8
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     ip 9d209ff0  sp 9d20bff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d0  12c0ba5072837840  d1  00730020006500cf
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d2  c0c0c0c0c0c0c03a  d3  0102020202020213
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d4  0040404040404040  d5  0004000400040004
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0003000400040004
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d16 0000000000000000  d17 7320656d69746e75
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d18 0069007200750064  d19 007200200067006e
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d20 0101010101010101  d21 0101010101010101
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d22 8080808080808080  d23 8080808080808080
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d24 4000404040404040  d25 0040404040404040
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d28 0101010101010101  d29 0101010101010101
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     d30 0000000000000000  d31 0000000000000000
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     #00 pc 0009230c  /system/framework/arm/boot.oat
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     #01 pc 00092387  /system/framework/arm/boot.oat
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf70  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf74  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf78  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf7c  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf80  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf84  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf88  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf8c  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf90  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf94  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf98  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bf9c  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfa0  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfa4  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfa8  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfac  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfb0  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfb4  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfb8  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfbc  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfc0  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfc4  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfc8  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfcc  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfd4  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfd8  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfdc  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfe0  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfe8  e3a070ad  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bfec  ef9000ad  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     #00  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          ........  ........
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:     #01  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bff4  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bff8  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20bffc  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c000  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c004  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c010  133acf40  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c018  12c0ba50  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c01c  7541f33d  /system/framework/arm/boot.oat
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c024  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c028  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c02c  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c034  00000000  
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c040  133acf40  /dev/ashmem/dalvik-main space (deleted)
03-17 12:28:19.164  1020  1020 D CrashAnrDetector:          9d20c044  728
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:19.164  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.an,droid.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:19.164  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:19.164  1020  1020 V ApplicationPolicy: boot completed - refreshWidgetStatus
03-17 12:28:19.164  1020  1020 V ApplicationPolicy: refresh widget status for user 0
03-17 12:28:19.174  1020  2793 I i       : No model
03-17 12:28:19.174  1020  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 12:28:19.184  1020  2793 D FactoryTest: Not factory mode
03-17 12:28:19.184  1020  2793 D FactoryTest: Not factory mode. isFactoryMode() returend false
03-17 12:28:19.184  1020  2793 D w       : isUserBuild = true
03-17 12:28:19.194  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-17 12:28:19.194  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.email
03-17 12:28:19.194  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname flipboard.app
03-17 12:28:19.194  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.chrome
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.mms
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gm
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.talk
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 12:28:19.204  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-17 12:28:19.224  1020  2793 D SSRM:n  : SIOP:: AP = 400
03-17 12:28:19.234  1020  1565 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.234  1020  2793 D SSRM:a  : DeviceInfo:: 000000000000
03-17 12:28:19.234  1020  2793 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-17 12:28:19.304  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:19.304  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:19.314  1020  1020 W PhoneRestrictionPolicy: Message received - msg { when=-4ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
03-17 12:28:19.324  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.324  1020  2833 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: pid: 3041, tid: 3372, name: Thread-383  >>> com.example.hello <<<
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     r0 00000000  r1 00000000  r2 00000000  r3 00000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     r4 9e1a7e78  r5 9e1a7e38  r6 b7dca130  r7 9e1a7e38
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     r8 00000000  r9 9e1a7e74  sl 9e1a93d0  fp 9e1a7e1c
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     ip 9ec7dba0  sp 9e1a7e00  lr 9e984308  pc b6ee9468  cpsr 600d0030
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d0  00000035020000d5  d1  513802003a373ef1
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d2  0000b80c0300009d  d3  88000000560a1060
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d4  07490c0000003d01  d5  0000008849000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d6  0a0e000000b80c0c  d7  01003a0f0000003d
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d16 0000000000000000  d17 ffffffffffffffff
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d20 0000000000000001  d21 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d26 0002000200020001  d27 0002000200020002
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     scr 20000012
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     #00 pc 00010468  /system/lib/libc.so (strlen+83)
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d80  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d84  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d88  9de2b820  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d8c  f5cf96b7  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d90  9e1a7dbc  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d94  9e1a7e64  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d98  b7dca130  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7d9c  00000003  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7da0  9e1a7ddc  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7da4  b7ebd960  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7da8  9de53b00  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dac  9df11b30  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7db0  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7db4  ffffff82  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7db8  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dbc  ffffff82  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dc0  9de2b040  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dc4  b7eba960  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dc8  b7f16b48  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dcc  00000001  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dd0  9de49160  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dd4  b7dca130  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dd8  9de4f1c0  [anon:js-gc-heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7ddc  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7de0  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7de4  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7de8  00000003  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dec  000000aa  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7df0  0000006b  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7df4  0001416e  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7df8  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7dfc  9e1a7e30  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     #00  9e1a7e00  9e1a7e78  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          ........  ........
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:     #01  9e1a7e00  9e1a7e78  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e04  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e08  9e1a7e78  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e0c  9e1a7e5c  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e10  9e1a7e48  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e14  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e18  9e1a8e94  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e1c  9e95b3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e20  9e1a7e50  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e24  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e28  9e1a7e44  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e2c  9e78d184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e30  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e34  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e38  b6f2fde4  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e3c  00000000  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e40  9e1a81cc  [stack:3372]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e44  9e869b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e48  b7dca130  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e4c  b7dca130  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e50  b7f16b48  [heap]
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e54  00000001  
03-17 12:28:19.344  1020  1020 D CrashAnrDetector:          9e1a7e58  9
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: processName:com.example.hello
03-17 12:28:19.354  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:19.344  1020  1020 D CrashAnrDetector: broadcastEvent : null SYSTEM_TOMBSTONE
03-17 12:28:19.354  1020  1020 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-17 12:28:19.354  1020  1020 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-17 12:28:19.364  1020  2833 W PhoneRestrictionPolicy: cvList size 0
03-17 12:28:19.364  1020  2833 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-17 12:28:19.364  1020  2833 W PhoneRestrictionPolicy: cvList size 0
03-17 12:28:19.374  1020  1043 D SensorService: [SO] currT = 33831062000, prevT = 33391080000, diff = 439982000, [-0.460 0.211 9.883]
03-17 12:28:19.374  1020  1043 D SensorService: [SO] -0.460 0.211 9.883
03-17 12:28:19.374  1020  1043 D SensorService: [SO] [100 -> 255]
03-17 12:28:19.394  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-17 12:28:19.394  2662  2662 E BluetoothAdapterService(657092010): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
03-17 12:28:19.404  1020  1566 I ActivityManager: Killing 1572:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
03-17 12:28:19.404  2662  2747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-17 12:28:19.404  2662  2747 I bluedroid: enable
03-17 12:28:19.414  2662  2839 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-17 12:28:19.414  2662  2747 I bt_hci_bdroid: init
03-17 12:28:19.414  2662  2747 I bt_vendor: bt-vendor : init
03-17 12:28:19.414  2662  2747 I bt_vendor: bt-vendor : get_bt_soc_type
03-17 12:28:19.414  2662  2747 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-17 12:28:19.414  2662  2747 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
03-17 12:28:19.414  2662  2747 D bt_userial_mct: userial_init
03-17 12:28:19.414  2662  2747 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-17 12:28:19.414  2090  2784 D ConnectivityManager: CallingUid : 10011, CallingPid : 2090
03-17 12:28:19.414  2662  2747 I bt_vendor: Starting hciattach daemon
03-17 12:28:19.414  2662  2747 I bt_vendor: try to set false
03-17 12:28:19.414  2662  2747 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-17 12:28:19.414  2662  2747 I bt_vendor: Starting hciattach daemon
03-17 12:28:19.414  2662  2747 I bt_vendor: try to set true
03-17 12:28:19.424  1625  1634 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-17 12:28:19.424  1020  1301 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-17 12:28:19.424  1020  1136 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
03-17 12:28:19.424  1020  1136 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
03-17 12:28:19.424  1020  1136 D ConnectivityService: apparently satisfied.  currentScore=60
03-17 12:28:19.424  2090  2842 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-17 12:28:19.444  1625  1634 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 12:28:19.444  1625  1634 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:19.444  1487  1487 D Launcher.Model: reloadBadges entered.
03-17 12:28:19.444  1625  1634 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 12:28:19.444  1625  1634 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:19.444  1625  1634 D BadgeProvider: update, [UpdateCount] : 1
03-17 12:28:19.444  2844  2844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
03-17 12:28:19.464  1020  1486 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.474  1020  1133 D WifiP2pService: InactiveState{ what=143415 }
03-17 12:28:19.474  1020  1133 D WifiP2pService: P2pEnabledState{ what=143415 }
03-17 12:28:19.474  1020  1133 D WifiP2pService: DefaultState{ what=143415 }
03-17 12:28:19.484  1020  1136 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-17 12:28:19.484  1020  1134 E WifiStateMachine: Blacklist file delete
03-17 12:28:19.484  1020  1020 D Tethering: Boot complete.
03-17 12:28:19.504  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.514  2854  2854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
03-17 12:28:19.524  2855  2855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-17 12:28:19.554  1020  1020 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-17 12:28:19.554  1020  1136 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-17 12:28:19.554  2858  2858 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-17 12:28:19.554  1020  1020 V EnterpriseBillingEngine: handleAllprofiles - start
03-17 12:28:19.554  1020  1020 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
03-17 12:28:19.554  1020  1133 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 12:28:19.554  1020  1020 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-17 12:28:19.554  1020  1020 V EnterpriseBillingEngine: handleAllprofiles - end
03-17 12:28:19.554  1020  1133 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 12:28:19.564  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:19.564  1020  1045 W libprocessgroup: failed to open /acct/uid_10052/pid_1572/cgroup.procs: No such file or directory
03-17 12:28:19.564  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:19.564  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:19.564  2860  2860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
03-17 12:28:19.564  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:19.564  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:19.564  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:19.574  1020  1020 D UsbHostNotification: boot completed
03-17 12:28:19.584  2861  2861 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-17 12:28:19.584  1020  1134 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 12:28:19.584  1020  1020 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-17 12:28:19.584  1020  1134 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 12:28:19.584  1020  1020 D UsbHostRestrictor: initSetUsbBlock STARTED
03-17 12:28:19.584  2862  2862 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
03-17 12:28:19.604  1020  1020 D UsbHostRestrictor: SIM was never inserted
03-17 12:28:19.604  1020  1020 D UsbHostRestrictor: writableHostSysNode[false]
03-17 12:28:19.604  1020  1020 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
03-17 12:28:19.604  1020  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:19.604  1020  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:19.604  1020  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 12:28:19.614  1020  1046 W ProcessCpuTracker: Skipping unknown process pid 2852
03-17 12:28:19.634  1020  1046 W ProcessCpuTracker: Skipping unknown process pid 2853
03-17 12:28:19.674  1020  1020 D PersonaManagerService: ACTION_BOOT_COMPLETED
03-17 12:28:19.674  1020  1065 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-17 12:28:19.674   290   290 E SMD     : DCD OFF
03-17 12:28:19.684  1020  1020 D UsbStorageNotification: boot completed
03-17 12:28:19.684   299   299 E USB_UICC: Timeout! No signal received. Retry num = 28
03-17 12:28:19.684  1173  1173 D StorageNotification: boot completed
03-17 12:28:19.704  1020  1045 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-17 12:28:19.704  1020  1045 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-17 12:28:19.704   320   320 I ServiceManager: Waiting for service AtCmdFwd...
03-17 12:28:19.714  1020  1045 D GpsLocationProvider: set_capabilities_callback: 55u
03-17 12:28:19.734  1020  2867 E LocSvc_api_v02: I/locClientOpen:2279]: Service instance id is -1
03-17 12:28:19.754  1020  1045 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-17 12:28:19.754  1020  1045 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-17 12:28:19.754  1020  1045 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
03-17 12:28:19.754  1020  1485 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 12:28:19.764  1173  1173 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 12:28:19.764  1020  1065 D KnoxKeyguardUpdateMonitor: onBootComplete
03-17 12:28:19.764  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:19.764  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:19.764  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:19.764  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:19.764  1020  1565 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.774  1020  1020 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-17 12:28:19.774  1020  1020 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
03-17 12:28:19.784  1173  1173 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-17 12:28:19.784  2871  2871 E Zygote  : MountEmulatedStorage()
03-17 12:28:19.784  2757  2757 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:28:19.784  2871  2871 E Zygote  : v2
03-17 12:28:19.784  2871  2871 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:19.784  2871  2871 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:19.784  1020  1033 I ActivityManager: Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:19.784  2871  2871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:19.784  2871  2871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:19.784  1020  1065 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:28:19.794  2871  2871 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:19.804  1020  1502 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:19.814  2871  2871 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:19.814  2871  2871 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:19.834  2757  2757 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:28:19.844  2892  2892 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
03-17 12:28:19.854  2893  2893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-17 12:28:19.874  2662  2747 I bt_vendor: bluetooth satus is on
03-17 12:28:19.874  2662  2841 D bt_userial_mct: userial_open(port:0)
03-17 12:28:19.874  2662  2841 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
03-17 12:28:19.874  2662  2841 I bt_vendor: Done intiailizing UART
03-17 12:28:19.884  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-17 12:28:19.884  2662  2841 I bt_vendor: Done intiailizing UART
03-17 12:28:19.884  2662  2841 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-17 12:28:19.884  2662  2841 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-17 12:28:19.884  2662  2895 D bt_userial_mct: Entering userial_read_thread()
03-17 12:28:19.884  1020  1033 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:28:19.884  1020  1033 I PersonaManagerService: PersonaId don't exist
03-17 12:28:19.884  1020  1033 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:28:19.884  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-17 12:28:19.894  1020  2867 D qmi_secgps_clnt: qmi_secgps_client_init()
03-17 12:28:19.904  1020  2867 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-17 12:28:19.904  1020  2867 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-17 12:28:19.904  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:19.914  1020  2867 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 12:28:19.924  1020  1502 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 34389
03-17 12:28:19.934  1020  1502 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
03-17 12:28:19.934  1020  1502 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3515)
03-17 12:28:19.934  1020  1033 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 12:28:19.934  1020  1033 W ActivityManager: mDVFSHelper.acquire()
03-17 12:28:19.934  1020  1033 D FocusedStackFrame: Set to : 0
03-17 12:28:19.944  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:28:19.944  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:19.944  1020  1033 D InputDispatcher: Focused application set to: xxxx
03-17 12:28:19.944  2871  2871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 12:28:19.944  1020  1033 D InputDispatcher: Focus left window: 1487
03-17 12:28:19.954  1487  1487 D Launcher.HomeView: onPause
03-17 12:28:19.954  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 12:28:19.964  1020  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:28:19.964  1020  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 12:28:19.964  2757  2757 D AndroidRuntime: Shutting down VM
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_HCI
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_AVDT
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_AVRC
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_A2D
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_BNEP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_BTM
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_GAP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_PAN
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_SAP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_SDP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_GATT
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_SMP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_BTIF
03-17 12:28:19.974  2662  2839 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-17 12:28:19.974  1020  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:19.974  1020  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:19.974  1020  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
03-17 12:28:19.974  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:28:19.974  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:28:19.974  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:28:19.974  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:19.974  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:28:19.974  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:19.974   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-17 12:28:20.004  1020  2867 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 12:28:20.004  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.004  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.004  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.004  1020  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.014  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 12:28:20.014  1020  2793 D SSRM:a  : DeviceInfo:: 000000000000
03-17 12:28:20.014  1020  2793 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-17 12:28:20.014  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 12:28:20.024  2906  2906 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.024  2906  2906 E Zygote  : v2
03-17 12:28:20.024  2906  2906 I libpersona: KNOX_SDCARD checking this for 10167
03-17 12:28:20.024  2906  2906 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.024  2906  2906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:20.024  2906  2906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.024  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 12:28:20.024  1020  2867 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 12:28:20.024  1020  2867 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 12:28:20.034  1020  1502 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2906 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:28:20.034  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 12:28:20.034  1020  2867 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 12:28:20.034  2906  2906 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:28:20.034  1020  1242 I art     : Explicit concurrent mark sweep GC freed 182937(10MB) AllocSpace objects, 90(8MB) LOS objects, 33% free, 22MB/34MB, paused 2.644ms total 347.520ms
03-17 12:28:20.034  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 12:28:20.034  1020  2867 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 12:28:20.044  1020  1033 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
03-17 12:28:20.044  1020  1033 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-17 12:28:20.044  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.044  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.044  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.044  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.054  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 12:28:20.054  1020  2867 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 12:28:20.054  1020  2867 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 12:28:20.054  1020  2867 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 12:28:20.054  1020  2867 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 12:28:20.054  1020  2867 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: pid: 4387, tid: 4703, name: Thread-677  >>> com.test.thalitest <<<
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9dbf6494  r2 00000002  r3 00000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     r4 b8d43750  r5 00000000  r6 b8d42fe0  r7 bb70b440
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     r8 b8d2beb4  r9 b8d43750  sl b8d42fb8  fp 9dbf648c
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 9dbf647c  lr 9e0d1b30  pc 9e0d1a34  cpsr 60000010
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     scr 20000012
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf63fc  00000006  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6400  8fd92780  [anon:js-gc-heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6404  b8d43750  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6408  9e611b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf640c  b8d43750  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6410  9dbf642c  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6414  9e2f2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6418  00000001  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf641c  00000000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6420  b8d44280  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6424  00000000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6428  00000000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf642c  b8d43750  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6430  b8d44280  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6434  9e75db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6438  9dbf64a4  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf643c  9e0d8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6440  b8d43750  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6444  b8d42fb8  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6448  9dbfc000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf644c  9dbf6470  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6450  9dbf6468  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6454  9dbf6474  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6458  9e6846d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf645c  9dbf6478  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6460  00000004  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6464  00000000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6468  00000001  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf646c  b8d43750  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6470  8fdcd3a0  [anon:js-gc-heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6474  b8d42fe0  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6478  9dbf648c  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     #00  9dbf647c  9dbf648c  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6480  9dbfb838  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6484  bb701888  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6488  9dbf64a4  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf648c  9e0d506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:     #01  9dbf6490  b8d2beb4  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6494  00000000  
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf6498  b8d42fdc  [heap]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf649c  9e605cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf64a0  9dbf64fc  [stack:4703]
03-17 12:28:20.054  1020  1020 D CrashAnrDetector:          9dbf64a4  9e0d9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.054  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:20.054  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.064  1020  2867 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 12:28:20.064  1020  2867 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 12:28:20.064  2662  2839 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-17 12:28:20.064  2662  2839 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa442dead 
03-17 12:28:20.074  2918  2918 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.074  2918  2918 E Zygote  : v2
03-17 12:28:20.074  2918  2918 I libpersona: KNOX_SDCARD checking this for 10097
03-17 12:28:20.074  2662  2839 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa442dead 
03-17 12:28:20.074  2918  2918 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.074  1020  1033 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2918 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:20.074  2918  2918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:20.074  2918  2918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.084  2918  2918 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:28:20.084  1020  1129 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 12:28:20.084  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:20.084  2906  2906 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.094  2906  2906 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:20.094  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:20.094  2662  2751 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-17 12:28:20.094  2662  2751 E bt-btif : Calling BTA_HhEnable
03-17 12:28:20.094  2662  2751 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-17 12:28:20.094  2662  2751 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-17 12:28:20.094  2662  2751 E BluetoothServiceJni: populateRssiValuesNative
03-17 12:28:20.094  2662  2751 I bluedroid: getModelRssiValues
03-17 12:28:20.104  2662  2751 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 12:28:20.104  2662  2751 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-17 12:28:20.104   307   307 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 934us total 28.598ms
03-17 12:28:20.114  2918  2918 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.114  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.114  2918  2918 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:20.114  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.114  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 12:28:20.114  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.114  1020  2867 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 12:28:20.114  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.114  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 12:28:20.114  1020  2870 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 12:28:20.114  1020  2867 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 12:28:20.124   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 779us total 19.864ms
03-17 12:28:20.134  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{2ff67012 token=android.os.BinderProxy@10c442 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 12:28:20.134   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.680ms
03-17 12:28:20.144  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:20.144  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:20.154  2937  2937 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.154  2937  2937 E Zygote  : v2
03-17 12:28:20.154  2937  2937 I libpersona: KNOX_SDCARD checking this for 10081
03-17 12:28:20.154  2937  2937 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.154  2937  2937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:20.154  2937  2937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.154  2937  2937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:20.154  1020  1046 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2937 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:20.164  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.164  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.164  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.164  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.174  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:20.174  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
03-17 12:28:20.184  2757  2757 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 12:28:20.184  1020  1046 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2951 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 12:28:20.194  2662  2751 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-17 12:28:20.194  1020  1567 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:28:20.194  1020  1567 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:28:20.194  1020  1567 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:28:20.194  2951  2951 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.194  2951  2951 I libpersona: KNOX_SDCARD checking this for 1101
03-17 12:28:20.194  2951  2951 E Zygote  : v2
03-17 12:28:20.194  2951  2951 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.194  2951  2951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:20.194  2951  2951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.194  2951  2951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:20.204  1487  1487 D Launcher.HomeView: onStop
,03-17 12:28:20.204  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{2ff67012 token=android.os.BinderProxy@10c442 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 12:28:20.204  1487  1487 D Launcher: onTrimMemory. Level: 20
,03-17 12:28:20.204  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:28:20.214  2937  2937 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:20.214  2937  2937 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.214  1020  2698 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,03-17 12:28:20.214  1020  2746 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 12:28:20.214  1020  1567 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:28:20.214  2951  2951 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:20.214  2951  2951 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.234  2662  2751 D BluetoothAdapterProperties: Scan Mode:20
,03-17 12:28:20.234  2662  2751 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 12:28:20.234  2662  2751 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-17 12:28:20.234  2662  2751 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 12:28:20.234  2662  2751 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-17 12:28:20.234  2662  2751 E bt-btif : HC lpm_result_cb 1
03-17 12:28:20.234  2662  2751 E bt-btif : btif_sock_init: !vhci_init
,03-17 12:28:20.244  2662  2751 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,03-17 12:28:20.244  2662  2751 D IOP_DB_BT: db_open: db_open : handle 3028148240l, read 13894 bytes onto local cache
03-17 12:28:20.244  2662  2751 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,03-17 12:28:20.244  2662  2751 D IOP_DB_BT: db_query: result 1
03-17 12:28:20.244  2662  2751 I         : iop_db_open: iop_db_open status 0
,03-17 12:28:20.244  2662  2751 D bte_conf: Device ID record 1 : primary
03-17 12:28:20.244  2662  2751 D bte_conf:   vendorId            = 0075
03-17 12:28:20.244  2662  2751 D bte_conf:   vendorIdSource      = 0001
03-17 12:28:20.244  2662  2751 D bte_conf:   product             = 0100
03-17 12:28:20.244  2662  2751 D bte_conf:   version             = 0200
03-17 12:28:20.244  2662  2751 D bte_conf:   clientExecutableURL = 
03-17 12:28:20.244  2662  2751 D bte_conf:   serviceDescription  = 
03-17 12:28:20.244  2662  2751 D bte_conf:   documentationURL    = 
03-17 12:28:20.244  2662  2751 D bte_conf: bte_load_did_conf no section named DID2.
03-17 12:28:20.244  2662  2751 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,03-17 12:28:20.244  2662  2895 E bt_mct  : hci lib postload completed
,03-17 12:28:20.254  1020  1020 D SettingsProvider: name = bluetooth_name
,03-17 12:28:20.274  2662  2747 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 12:28:20.274  2662  2747 D BluetoothAdapterProperties: ScanMode =  20
03-17 12:28:20.274  2662  2747 D BluetoothAdapterProperties: State =  11
,03-17 12:28:20.274  1020  1485 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: pid: 3807, tid: 4175, name: Thread-562  >>> com.test.thalitest <<<
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9368b424  r2 00000002  r3 00000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     r4 b7a20c80  r5 00000000  r6 b7a20510  r7 b9bb7a70
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     r8 b7a7363c  r9 b7a20c80  sl b7a204e8  fp 9368b41c
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 9368b40c  lr 93d81b30  pc 93d81a34  cpsr 60000010
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     scr 20000012
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b38c  00000006  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector,:          9368b390  90f5e780  [anon:js-gc-heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b394  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b398  942c1b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b39c  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3a0  9368b3bc  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3a4  93fa2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3a8  00000001  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3ac  00000000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3b0  b7a217b0  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3b4  00000000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3b8  00000000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3bc  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3c0  b7a217b0  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3c4  9440db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3c8  9368b434  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3cc  93d88514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3d0  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3d4  b7a204e8  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3d8  93693000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3dc  9368b400  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3e0  9368b3f8  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3e4  9368b404  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3e8  943346d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3ec  9368b408  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3f0  00000004  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3f4  00000000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3f8  00000001  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b3fc  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b400  b7a20c80  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b404  929401e0  [anon:js-gc-heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b408  9368b41c  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     #00  9368b40c  9368b41c  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b410  93692838  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b414  b9bb3cd8  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b418  9368b434  [stack:4175]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b41c  93d8506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:     #01  9368b420  b7a7363c  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b424  00000000  
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b428  b7a2050c  [heap]
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b42c  942b5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.274  1020  1020 D CrashAnrDetector:          9368b430  9368b48c  [stack:4175]
03-17 12:28:20.,274  1020  1020 D CrashAnrDetector:          9368b434  93d89dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.274  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.274  2662  2747 D BluetoothAdapterProperties: Setting state to 12
03-17 12:28:20.274  2662  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,03-17 12:28:20.284  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,03-17 12:28:20.284  2662  2751 D BluetoothAdapterProperties: Scan Mode:21
03-17 12:28:20.284  2662  2751 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-17 12:28:20.284  1020  1486 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 12:28:20.284  1020  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:20.284  1020  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:20.284  1020  1486 D SettingsProvider: selectionArgs: false
03-17 12:28:20.284  1020  1486 D SettingsProvider: selectionArgs: 1002
03-17 12:28:20.284  1020  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:20.284  1020  1486 D SettingsProvider: ret = -1
,03-17 12:28:20.284  2937  2937 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 12:28:20.284  1020  1486 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 12:28:20.294  2937  2937 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:20.294  2937  2937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:20.294  2937  2937 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:20.294  2937  2937 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 12:28:20.294  2662  2747 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,03-17 12:28:20.294  2662  2747 D BluetoothAdapterService: updateAdapterState state is 12
,03-17 12:28:20.294  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.294  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.294  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: pid: 3548, tid: 4067, name: Thread-502  >>> com.test.thalitest <<<
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9372793c  r2 00000002  r3 00000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     r4 b8aef3c8  r5 00000000  r6 b8aeec58  r7 b8cc7760
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     r8 b8b7cde4  r9 b8aef3c8  sl b8aeec30  fp 93727934
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 93727924  lr 93c02234  pc 93c02138  cpsr 60000010
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     #00 pc 003d1138  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     #01 pc 003d1230  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278a4  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector,:          937278a8  916fc0a0  [anon:js-gc-heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278ac  b8aef3c8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278b0  b8aef3c8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278b4  00000001  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278b8  937278d4  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278bc  93c01854  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278c0  00000001  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278c4  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278c8  b8aefef8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278cc  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278d0  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278d4  b8aef3c8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278d8  b8aefef8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278dc  9428db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278e0  9372794c  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278e4  93c08c18  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278e8  b8aef3c8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278ec  b8aeec30  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278f0  9372d000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278f4  93727918  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278f8  93727910  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          937278fc  9372791c  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727900  941b4dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727904  93727920  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727908  00000004  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          9372790c  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727910  00000001  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727914  b8aef3c8  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727918  908b3a60  [anon:js-gc-heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          9372791c  b8aeec58  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727920  93727934  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     #00  93727924  93727934  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727928  9372c838  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          9372792c  b8cc6890  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727930  9372794c  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727934  93c05770  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     #01  93727938  b8b7cde4  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          9372793c  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727940  b8aeec54  [heap]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727944  941363d0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727948  937279a4  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          9372794c  93c0a4d0  /data/app/com.test.thalite,st-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727950  00000000  
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:          93727954  9372796c  [stack:4067]
03-17 12:28:20.304  1020  1020 D CrashAnrDetector:     
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.304  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:20.304  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.304  2951  2951 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 12:28:20.314  2662  2747 D BluetoothAdapterService: Autoconnection is available 
,03-17 12:28:20.314  2662  2747 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 12:28:20.314  2662  2747 D BluetoothAdapterService: starting service from this receiver
,03-17 12:28:20.324  1020  1566 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: pid: 4389, tid: 4508, name: Thread-702  >>> com.test.thalitest <<<
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9ede682c  r2 00000002  r3 00000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     r4 b7f0c840  r5 00000000  r6 b7f0c0d0  r7 b986b2f8
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     r8 b7de4664  r9 b7f0c840  sl b7f0c0a8  fp 9ede6824
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 9ede6814  lr 9f2cfb30  pc 9f2cfa34  cpsr 600f0010
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d16 0000000000000000  d17 000027b700000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6794  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector,:          9ede6798  90dfc0a0  [anon:js-gc-heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede679c  b7f0c840  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67a0  00000001  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67a4  90d6d0d0  [anon:js-gc-heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67a8  9ede67c4  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67ac  9f2cf12c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67b0  00000001  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67b4  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67b8  b7f0d370  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67bc  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67c0  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67c4  b7f0c840  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67c8  b7f0d370  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67cc  9f95bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67d0  9ede683c  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67d4  9f2d6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67d8  b7f0c840  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67dc  b7f0c0a8  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67e0  9edfa000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67e4  9ede6808  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67e8  9ede6800  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67ec  9ede680c  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67f0  9f8826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67f4  9ede6810  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67f8  00000004  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede67fc  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6800  00000001  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6804  b7f0c840  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6808  91951af0  [anon:js-gc-heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede680c  b7f0c0d0  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6810  9ede6824  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     #00  9ede6814  9ede6824  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6818  9edf9838  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede681c  b9866048  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6820  9ede683c  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6824  9f2d306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:     #01  9ede6828  b7de4664  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede682c  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6830  b7f0c0cc  [heap]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6834  9f803cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6838  9ede6894  [stack:4508]
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede683c  9f2d7dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6840  00000000  
03-17 12:28:20.324  1020  1020 D CrashAnrDetector:          9ede6844  9ede685c  [stack
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.324  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:20.324  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.324  1924  2200 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.324  1924  2200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.324  1020  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.324  1020  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 12:28:20.324  2662  2672 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.324  2662  2747 I BluetoothAdapterState: Entering On State from state = 11
03-17 12:28:20.324  2662  2672 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.324  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:20.334  1020  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.334  1020  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.334  1020  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 12:28:20.334  1461  1813 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.334  1461  1813 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.334  2253  2261 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.334  2253  2261 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.344  1437  2761 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.344  1437  2761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.344  1452  1480 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.344  1452  1480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.344  1173  1897 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 12:28:20.344  1173  1897 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 12:28:20.344  2662  2672 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: pid: 4273, tid: 4624, name: Thread-667  >>> com.test.thalitest <<<
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     r0 00000000  r1 920d54e4  r2 00000002  r3 00000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     r4 b84d6800  r5 00000000  r6 b84d6090  r7 ba6fdeb8
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     r8 b8196a74  r9 b84d6800  sl b84d6068  fp 920d54dc
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 920d54cc  lr 925b1b30  pc 925b1a34  cpsr 60000010
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d544c  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5450  8fcfc0a0  [anon:js-gc-heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5454  b84d6800  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5458  00000001  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d545c  8fced280  [anon:js-gc-heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5460  920d547c  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5464  925b112c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5468  00000001  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d546c  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5470  b84d7330  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5474  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5478  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d547c  b84d6800  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5480  b84d7330  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5484  92c3db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5488  920d54f4  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d548c  925b8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5490  b84d6800  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5494  b84d6068  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d5498  920dc000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d549c  920d54c0  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54a0  920d54b8  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54a4  920d54c4  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54a8  92b646d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54ac  920d54c8  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54b0  00000004  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54b4  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54b8  00000001  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54bc  b84d6800  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54c0  901e6eb0  [anon:js-gc-heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54c4  b84d6090  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54c8  920d54dc  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     #00  920d54cc  920d54dc  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54d0  920db838  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54d4  ba6fb020  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54d8  920d54f4  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54dc  925b506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:     #01  920d54e0  b8196a74  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54e4  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54e8  b84d608c  [heap]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54ec  92ae5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54f0  920d554c  [stack:4624]
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54f4  925b9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54f8  00000000  
03-17 12:28:20.344  1020  1020 D CrashAnrDetector:          920d54fc  920d5514  [stack
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.344  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.344  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:20.344  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 12:28:20.344  1020  1020 D SensorService: [SO] activate (ident=0xb92185d0, enabled=0)
03-17 12:28:20.344  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 12:28:20.354  2951  2951 V SmartcardService: main Received broadcast
03-17 12:28:20.354  2951  2951 V SmartcardService: Starting smartcard service after boot completed
,03-17 12:28:20.354  1020  1020 D SensorManager: unregisterListener ::   
03-17 12:28:20.354  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 12:28:20.354  1020  1020 D SensorService: [SO] changed settle time [1]
03-17 12:28:20.354  1020  1020 D SensorService: [SO] setDelay [66000000]
03-17 12:28:20.354  1020  1020 D SensorService: [SO] activate (ident=0xb94ceec8, enabled=1)
03-17 12:28:20.354  1020  1020 D SensorService: [SO] AR_init
03-17 12:28:20.354  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 12:28:20.364  1234  1234 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 12:28:20.364  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 12:28:20.374  1173  1173 D BluetoothTile:  onBluetoothStateChange:
03-17 12:28:20.374  2662  2662 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 12:28:20.374  1437  1437 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@effce2d, true
03-17 12:28:20.384  1866  1866 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 12:28:20.384  1437  1437 D BluetoothHeadset: registerMessageListener
03-17 12:28:20.384  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 12:28:20.384  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 12:28:20.394  1173  1173 D BluetoothTile:  getBluetoothState : 12
03-17 12:28:20.394  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.394  1020  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.394  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 12:28:20.394  1173  1631 D BluetoothTile:  handleUpdatestate:false name:null
03-17 12:28:20.394  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.394  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.394  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:28:20.394  2662  2670 D HeadsetService: registerMessageListener
,03-17 12:28:20.404  2662  2670 D HeadsetService: registerMessageListener
,03-17 12:28:20.404  1020  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-17 12:28:20.404  1020  1033 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,03-17 12:28:20.404  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-17 12:28:20.404  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 12:28:20.404  2662  2762 D HeadsetStateMachine: Disconnected process message: 70
03-17 12:28:20.404  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
03-17 12:28:20.404  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-17 12:28:20.404  2662  2762 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2560536b
,03-17 12:28:20.404  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 12:28:20.404  1173  1631 D BluetoothTile:  handleUpdatestate:false name:null
03-17 12:28:20.404  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-17 12:28:20.414  1173  1631 D BluetoothTile:  handleUpdatestate:false name:null
,03-17 12:28:20.414  1020  1486 I ActivityManager: Killing 2044:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
,03-17 12:28:20.414  1020  1567 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 12:28:20.414  1020  1567 D SecContentProvider2: mCursor = null
,03-17 12:28:20.414  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 12:28:20.414  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 12:28:20.414  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Hardware: MSM8916
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Revision: 1
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Radio: unknown
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: Revision: '1'
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: ABI: 'arm'
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: pid: 4085, tid: 4524, name: Thread-617  >>> com.test.thalitest <<<
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     r0 00000000  r1 9358a7dc  r2 00000002  r3 00000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     r4 b8b4ae28  r5 00000000  r6 b8b4a6b8  r7 ba8998a0
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     r8 b872115c  r9 b8b4ae28  sl b8b4a690  fp 9358a7d4
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     ip ffffffff  sp 9358a7c4  lr 9e9e1b30  pc 9e9e1a34  cpsr 60000010
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d20 0000000000010001  d21 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d26 0002000200010001  d27 0002000200020002
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     scr 20000013
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: backtrace:
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: 
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: stack:
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a744  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector,:          9358a748  8fffc0a0  [anon:js-gc-heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a74c  b8b4ae28  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a750  b8b4ae28  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a754  00000001  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a758  9358a774  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a75c  9e9e1150  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a760  00000001  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a764  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a768  b8b4b958  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a76c  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a770  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a774  b8b4ae28  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a778  b8b4b958  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a77c  9f06db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a780  9358a7ec  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a784  9e9e8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a788  b8b4ae28  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a78c  b8b4a690  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a790  93590000  /dev/kgsl-3d0
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a794  9358a7b8  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a798  9358a7b0  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a79c  9358a7bc  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7a0  9ef946d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7a4  9358a7c0  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7a8  00000012  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7ac  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7b0  00000001  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7b4  b8b4ae28  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7b8  91e462b0  [anon:js-gc-heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7bc  b8b4a6b8  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7c0  9358a7d4  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     #00  9358a7c4  9358a7d4  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7c8  9358f838  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7cc  ba897cf8  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7d0  9358a7ec  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7d4  9e9e506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:     #01  9358a7d8  b872115c  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7dc  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7e0  b8b4a6b4  [heap]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7e4  9ef15cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7e8  9358a844  [stack:4524]
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7ec  9e9e9dcc  /data/app/com,.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7f0  00000000  
03-17 12:28:20.424  1020  1020 D CrashAnrDetector:          9358a7f4  9358a80c  [sta
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: processName:com.test.thalitest
03-17 12:28:20.424  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 12:28:20.424  1020  1020 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 12:28:20.434  1020  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 12:28:20.434  1020  1301 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.434  1020  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.434  1020  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 12:28:20.444  2662  2762 D HeadsetStateMachine: Disconnected process message: 9
03-17 12:28:20.444  2662  2762 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 12:28:20.454  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.454  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.454  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.454  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.464  2977  2977 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.464  2977  2977 E Zygote  : v2
03-17 12:28:20.464  2977  2977 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:20.464  2977  2977 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:20.464  2977  2977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:20.474  1234  1234 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 12:28:20.474  1020  1242 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:20.474  2977  2977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.474  2977  2977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:20.474  2662  2662 I BluetoothPbapService: Handler(): got msg=1
03-17 12:28:20.484   285   763 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 12:28:20.484   285   763 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-17 12:28:20.484   285   763 V voice   : voice_set_parameters: exit with code(-2)
03-17 12:28:20.484   285   763 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 12:28:20.484   285   763 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 12:28:20.484   285   763 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 12:28:20.484   285   763 V audio_hw_primary: adev_set_parameters: exit
03-17 12:28:20.484  2662  2762 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-17 12:28:20.484  1020  1567 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-17 12:28:20.504  1020  1043 D SensorService: [SO] currT = 34961070000, prevT = 34631038000, diff = 330032000, [-0.460 0.192 9.902]
03-17 12:28:20.504  1020  1043 D SensorService: [SO] -0.460 0.192 9.902
03-17 12:28:20.504  1020  1043 D SensorService: [SO] [100 -> 255]
,03-17 12:28:20.504  2906  2906 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 12:28:20.514  2906  2906 I LibraryLoader: Loading: webviewchromium
,03-17 12:28:20.524  2906  2906 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 4975-4982)
03-17 12:28:20.524  2906  2906 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:28:20.534  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:20.534  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:20.534  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 12:28:20.534  2977  2977 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:20.534  2977  2977 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.534  2662  2994 V BluetoothPbapService: PBAP Service initSocket try: 0
,03-17 12:28:20.534   259  1898 I SurfaceFlinger: id=10 Removed Uoast (9/9)
,03-17 12:28:20.544  1020  1045 W libprocessgroup: failed to open /acct/uid_10134/pid_2044/cgroup.procs: No such file or directory
,03-17 12:28:20.544   259  1898 I SurfaceFlinger: id=10 Removed Uoast (-2/9)
,03-17 12:28:20.544  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.544  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.544  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:28:20.554  2662  2995 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-17 12:28:20.554  2662  2994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 12:28:20.554  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:20.554  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:20.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:20.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:20.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:20.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:20.564  2662  2994 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 12:28:20.564  2662  2994 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 12:28:20.564  2662  2994 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 12:28:20.564  2662  2994 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c5f8f74
,03-17 12:28:20.564  2662  2994 D BluetoothSocket: channel: 19
03-17 12:28:20.564  2662  2994 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,03-17 12:28:20.574  2662  2995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-17 12:28:20.574  2662  2995 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,03-17 12:28:20.574  2662  2995 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 12:28:20.574  2662  2995 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-17 12:28:20.574  2662  2995 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a1d9c9d
,03-17 12:28:20.574  2662  2995 D BluetoothSocket: channel: 5
,03-17 12:28:20.584  2906  2906 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {272a6daa}
,03-17 12:28:20.584  2906  2906 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:28:20.584  2906  2906 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:28:20.594  1020  1032 D SettingsProvider: name = next_alarm_formatted
,03-17 12:28:20.594  1020  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 12:28:20.604  1020  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 12:28:20.604  1020  1032 D SettingsProvider: selectionArgs: false
,03-17 12:28:20.604  1020  1032 D SettingsProvider: selectionArgs: 10081
,03-17 12:28:20.604  1020  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:20.604  1020  1032 D SettingsProvider: ret = -1
,03-17 12:28:20.614  2918  2918 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-17 12:28:20.614  2918  2918 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-17 12:28:20.624  2977  2977 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:20.624  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:20.624  1020  1242 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:20.624  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-17 12:28:20.624  2906  2906 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 12:28:20.624  2906  2906 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:20.634  1020  1032 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
,03-17 12:28:20.654  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.654  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.654  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.654  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.664  1234  2997 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
,03-17 12:28:20.664  2906  2906 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 12:28:20.664  2906  2906 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,03-17 12:28:20.664  2906  2906 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-17 12:28:20.674  3008  3008 E Zygote  : MountEmulatedStorage(),
03-17 12:28:20.674  3008  3008 I libpersona: KNOX_SDCARD checking this for 10153
03-17 12:28:20.674  3008  3008 E Zygote  : v2
03-17 12:28:20.674  3008  3008 I libpersona: KNOX_SDCARD not a persona,
03-17 12:28:20.674  3008  3008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:20.674  3008  3008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:20.674  1020  1129 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3008 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,03-17 12:28:20.674  3008  3008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:20.684   299   299 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 12:28:20.684  1020  1129 I ActivityManager: Killing 1737:com.android.vending/u0a26 (adj 15): empty #31
,03-17 12:28:20.684  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:20.684   259  1898 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 12:28:20.684   259   454 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 12:28:20.694  1020  1020 I DrmEventReceiver: DrmEventReceiver : onReceive
,03-17 12:28:20.694  1020  1020 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-17 12:28:20.704  1020  1020 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 12:28:20.704  1020  1020 I System.out: start Service
,03-17 12:28:20.704  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,03-17 12:28:20.714   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 12:28:20.714  1020  1046 I ActivityManager: Waited long enough for: ServiceRecord{1b6ffc21 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 12:28:20.724  2906  2906 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:28:20.724  2906  2906 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:20.724  2906  2906 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:20.724  2906  2906 I Adreno-EGL: Local Branch: 
03-17 12:28:20.724  2906  2906 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:20.724  2906  2906 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:20.724  2906  2906 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:20.724  3008  3008 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:20.724  3008  3008 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.734  1020  1566 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:28:20.734  1020  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.734  1020  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:28:20.744  1234  1234 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 12:28:20.754  3008  3008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:20.764  1461  1482 D TP/MmsProvider: Update uri=content://mms, match=0
,03-17 12:28:20.764  1461  1482 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 12:28:20.764  1461  1482 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 12:28:20.774  2424  2424 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 12:28:20.774  2424  2424 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 3989.8788
,03-17 12:28:20.774  2424  2424 I Mms/ReservationManager: resetAfterConnected()
,03-17 12:28:20.784  2424  3033 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-17 12:28:20.784  2424  3033 D Mms/TelephonyPermission: isDefault true
03-17 12:28:20.784  1461  1813 D TP/MmsSmsProvider: query,matched:7, calling pid = 2424
,03-17 12:28:20.784  1461  1474 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2424
,03-17 12:28:20.784  1461  1813 D TP/MmsSmsProvider: match 7:Elapsed time : 4.265 ms
,03-17 12:28:20.794  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.794  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.794  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.794  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.804  3037  3037 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.804  3037  3037 E Zygote  : v2
03-17 12:28:20.804  3037  3037 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:20.804  3037  3037 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:20.814  3037  3037 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:20.814  3037  3037 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.814  1020  1033 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:20.814  3037  3037 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:20.814   284   506 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 1867
03-17 12:28:20.814   284   506 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 1867
,03-17 12:28:20.834  2424  2424 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 12:28:20.834  1461  1813 D TP/MmsSmsProvider: query,matched:200, calling pid = 2424
,03-17 12:28:20.834  1461  1813 D TP/MmsSmsProvider: match 200:Elapsed time : 0.963 ms
,03-17 12:28:20.834  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.834  1020  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.834  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 12:28:20.834  2937  2937 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 165.094ms
,03-17 12:28:20.844  3037  3037 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.844  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.844  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.844  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.844  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.854  3037  3037 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.854  2906  3028 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 12:28:20.854  2906  2906 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 12:28:20.864  3057  3057 E Zygote  : MountEmulatedStorage()
,03-17 12:28:20.864  3057  3057 E Zygote  : v2
03-17 12:28:20.864  3057  3057 I libpersona: KNOX_SDCARD checking this for 10043
03-17 12:28:20.864  3057  3057 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:20.864  3057  3057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 12:28:20.864  1020  1301 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3057 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:28:20.864  3057  3057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:20.874  1020  3054 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-17 12:28:20.874  3057  3057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:20.884  1020  1020 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-17 12:28:20.894  1234  2997 E SQLiteLog: (283) recovered 372 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-17 12:28:20.904  2424  2424 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 12:28:20.904  1461  1809 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 12:28:20.904  1461  1809 D TP/SmsProvider: match 0:Elapsed time : 1.154 ms
,03-17 12:28:20.904   284   284 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,03-17 12:28:20.904  2424  3070 D Mms/TelephonyPermission: isDefault true
03-17 12:28:20.904  2906  2906 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:28:20.904  3057  3057 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.904  3057  3057 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:20.904  2424  3070 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 12:28:20.904  2424  3070 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 136.883542
,03-17 12:28:20.914  2906  2906 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:28:20.924  1461  1461 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
,03-17 12:28:20.934  2906  2906 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:28:20.934  2906  2906 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 12:28:20.934  3057  3057 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:28:20.934  3057  3057 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:20.944  3057  3057 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 12:28:20.944  2906  2906 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 12:28:20.944  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.944  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.944  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.944  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.944  1020  1045 W libprocessgroup: failed to open /acct/uid_10026/pid_1737/cgroup.procs: No such file or directory
,03-17 12:28:20.954  3075  3075 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.954  3075  3075 E Zygote  : v2
03-17 12:28:20.954  3075  3075 I libpersona: KNOX_SDCARD checking this for 10155
03-17 12:28:20.954  3075  3075 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:20.954  3075  3075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:20.954  3075  3075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:20.954  1020  1485 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3075 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 12:28:20.954  1020  1485 I ActivityManager: Killing 2222:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-17 12:28:20.964  3075  3075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:20.964  1020  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.964  1020  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.964  1020  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 12:28:20.964  1020  1566 I ActivityManager: Killing 1503:com.android.printspooler/u0a132 (adj 15): empty #31
,03-17 12:28:20.974  2906  2906 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:28:20.974  2906  2906 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:20.994  3075  3075 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:20.994  3075  3075 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:20.994  1234  2997 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 12:28:21.004  1020  1502 D SettingsProvider: name = block_emergency_message
,03-17 12:28:21.004  1020  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:21.004  1020  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:21.004  1020  1502 D SettingsProvider: selectionArgs: false
03-17 12:28:21.004  1020  1502 D SettingsProvider: selectionArgs: 10043
03-17 12:28:21.004  1020  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 12:28:21.004  1020  1502 D SettingsProvider: ret = -1
,03-17 12:28:21.014  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.014  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.014  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.014  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.014  3075  3075 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:21.024  1461  1482 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 12:28:21.024  1461  1482 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-17 12:28:21.024  1461  1482 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 12:28:21.024  1461  1482 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 12:28:21.024  1461  1482 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.024  1461  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:21.044  3097  3097 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.044  3097  3097 E Zygote  : v2
03-17 12:28:21.044  3097  3097 I libpersona: KNOX_SDCARD checking this for 10002
03-17 12:28:21.044  3097  3097 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.044  3097  3097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:21.044  1020  1032 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3097 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-17 12:28:21.044  3097  3097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:21.044  3097  3097 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:21.054  1020  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.054  1020  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:21.054  1020  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 12:28:21.054  1020  1485 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
,03-17 12:28:21.064  3097  3097 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.074  3097  3097 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.074  2906  3112 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:28:21.074  1020  1045 W libprocessgroup: failed to open /acct/uid_10132/pid_1503/cgroup.procs: No such file or directory
,03-17 12:28:21.074  1020  1045 W libprocessgroup: failed to open /acct/uid_10064/pid_2222/cgroup.procs: No such file or directory
,03-17 12:28:21.084  1020  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 12:28:21.084  1020  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:28:21.084  1020  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:28:21.084  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:28:21.084  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:28:21.084  2906  2906 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:28:21.084  2906  2906 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 12:28:21.124  2090  2784 W DriveInitializer: Awaiting to be initialized
,03-17 12:28:21.134  2090  3114 W DriveInitializer: Background init thread started
,03-17 12:28:21.174  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:21.174  1020  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.174  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 12:28:21.174  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.174  1020  1242 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.174  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 12:28:21.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.184  1020  1486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:28:21.184  1020  1486 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 12:28:21.184  1020  1486 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 12:28:21.184  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:28:21.194  3119  3119 E Zygote  : MountEmulatedStorage(),
03-17 12:28:21.194  3119  3119 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.194  3119  3119 E Zygote  : v2
03-17 12:28:21.194  3119  3119 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:21.204  1020  1032 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 12:28:21.204  1020  1020 I MotionRecognitionService: Plugged,
03-17 12:28:21.204  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:28:21.204  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:28:21.204  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:28:21.214  1173  1173 D PowerUI : Cable  true --> true mBootCompleted : true
,03-17 12:28:21.214  1173  1173 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,03-17 12:28:21.214  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 12:28:21.214  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:28:21.214  2662  2662 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 12:28:21.214  2662  2762 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:28:21.224  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 12:28:21.224  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 12:28:21.224  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 12:28:21.224  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 12:28:21.224  1173  1173 D SViewCoverView: level :100 plugged : 2
03-17 12:28:21.224  3075  3075 D [0]UMC:Core: onCreate(): 
,03-17 12:28:21.284  1461  1482 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 12:28:21.284  1461  1482 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 12:28:21.294  1234  2997 V MediaScanner: processDirectory :  /system/media
03-17 12:28:21.294  2424  3070 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-17 12:28:21.294  1461  3126 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 12:28:21.294  3119  3119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:21.304  3119  3119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:21.304  1461  3126 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 12:28:21.304  3119  3119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.304  2424  3070 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
,03-17 12:28:21.304  2424  3070 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 12:28:21.304  2424  3070 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-17 12:28:21.314  1461  1474 I art     : Explicit concurrent mark sweep GC freed 33838(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 1.072ms total 348.189ms
,03-17 12:28:21.314  3075  3075 D [0]UMC:DeviceInfo: USA==US==
,03-17 12:28:21.314  1461  1474 D TP/SmsProvider: query,matched:51, calling pid = 2424
,03-17 12:28:21.314  1461  1474 D TP/SmsProvider: match 51:Elapsed time : 1.743 ms
,03-17 12:28:21.314  1461  1482 D TP/SmsProvider: query,matched:26, calling pid = 2424
,03-17 12:28:21.324  2424  3033 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 12:28:21.334  3119  3119 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.334  1461  1482 D TP/SmsProvider: match 26:Elapsed time : 16.491 ms
,03-17 12:28:21.334  3119  3119 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.344  1234  2997 V MediaScanner:  prescan time: 273ms (DB items: 138)
03-17 12:28:21.344  1234  2997 V MediaScanner:     scan time: 307ms (Caching mode: true), (makeEntry time: 14ms ~4%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 12:28:21.344  1234  2997 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 12:28:21.344  1234  2997 V MediaScanner:    total time: 580ms
03-17 12:28:21.344  1234  2997 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
,03-17 12:28:21.344  1234  2997 D MediaScanner: checkDefaultSounds
,03-17 12:28:21.344  1234  2997 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-17 12:28:21.344  1234  2997 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 12:28:21.344  2424  3070 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
,03-17 12:28:21.344  2424  3070 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 12:28:21.344  2424  3070 D Mms/TelephonyPermission: isDefault true
,03-17 12:28:21.344  1234  2997 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-17 12:28:21.354  1461  3126 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2424
03-17 12:28:21.354  1234  2997 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-17 12:28:21.354  1234  2997 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-17 12:28:21.354  1234  2997 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 12:28:21.354  1234  2997 D MediaScannerService: !@done scanning volume internal
,03-17 12:28:21.354  2640  2640 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2640) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 12:28:21.364  2640  2640 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2640) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 12:28:21.364  2640  2640 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2640) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-17 12:28:21.364  1234  2997 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 12:28:21.364  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 12:28:21.364  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 12:28:21.364  1461  1474 D TP/MmsSmsProvider: query,matched:200, calling pid = 2424
,03-17 12:28:21.374  1461  1474 D TP/MmsSmsProvider: match 200:Elapsed time : 0.991 ms
,03-17 12:28:21.384  3075  3075 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
,03-17 12:28:21.384  1461  1482 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 12:28:21.384  1461  1482 D TP/SmsProvider: match 0:Elapsed time : 1.604 ms
,03-17 12:28:21.394  1461  3126 D TP/SmsProvider: query,matched:51, calling pid = 2424
,03-17 12:28:21.394  1461  3126 D TP/SmsProvider: match 51:Elapsed time : 1.233 ms
,03-17 12:28:21.404  2424  3070 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 12:28:21.414  1020  1502 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.414  1020  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:21.414  1020  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 12:28:21.434  1924  1924 W art     : Verification of android.os.Bundle com.google.android.gms.auth.o.a(android.accounts.Account, java.lang.String, android.os.Bundle) took 131.956ms
,03-17 12:28:21.434  1461  1461 D CscUpdateService: onStart
,03-17 12:28:21.434  1461  1461 E CscUpdateService: costomer file is exists : it has been preconfiged.
,03-17 12:28:21.434  1461  1461 I CscUpdateService: set_CSC_version,
03-17 12:28:21.434  1461  1461 E CscParser: update(): xml file exist
,03-17 12:28:21.444  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 12:28:21.444  3075  3075 D [0]UMC:AdminManager: init - start
,03-17 12:28:21.444  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.444  1020  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.444  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 12:28:21.454  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 12:28:21.454  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:21.454  1317  1317 I WifiCredService: onCreate
,03-17 12:28:21.454   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
,03-17 12:28:21.454   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:28:21.454  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:21.454   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-17 12:28:21.454  2090  3114 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,03-17 12:28:21.464  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 12:28:21.464  1461  1461 I CscUtil : isWifiOnly = false
,03-17 12:28:21.464  1461  1461 I System.out: HandDataNode = null
,03-17 12:28:21.464  1461  1461 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-17 12:28:21.464  1461  1461 I CscUpdateService: This is normal boot : CSC not updated
,03-17 12:28:21.464  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-17 12:28:21.474  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-17 12:28:21.474  1461  3138 E CscParser: update(): xml file exist
,03-17 12:28:21.474  1234  2997 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 12:28:21.484  1020  1567 D InputDispatcher: Focus entered window: 2906
,03-17 12:28:21.484  2906  2906 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:28:21.494  2906  3112 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:28:21.494  1461  3138 D CscGPS  : CSCGPS.updateParameters
03-17 12:28:21.494  1461  3138 D CscGPS  : supl host : null
03-17 12:28:21.494  1461  3138 D CscGPS  : SUPL Host is null or invalid
03-17 12:28:21.494  1461  3138 D CscGPS  : supl_ver : null
03-17 12:28:21.494  1461  3138 D CscGPS  : SUPL Ver is null or invalid
03-17 12:28:21.494  1461  3138 D CscGPS  : supl port : null
03-17 12:28:21.494  1461  3138 D CscGPS  : SUPL PORT is null or invalid
03-17 12:28:21.494  1461  3138 D CscGPS  : LPP : null
03-17 12:28:21.494  1461  3138 D CscGPS  : LPP is null or invalid
03-17 12:28:21.494  1461  3138 D CscGPS  : CSC don't have any AGPS value.
,03-17 12:28:21.494  1461  1461 I CscUpdateService: same CSC Version
03-17 12:28:21.494  1461  1461 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
,03-17 12:28:21.494  1317  1317 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 12:28:21.494  1317  1317 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 12:28:21.494  1317  1317 D MY_TAG  : Action boot completed received
,03-17 12:28:21.494  2906  3112 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 12:28:21.494  2906  3112 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:28:21.494  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 12:28:21.504  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:28:21.514  1317  1317 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-17 12:28:21.514  1020  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
03-17 12:28:21.514  1020  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 12:28:21.514  1020  1134 E WifiNative-wlan0: invaild command id : 215
03-17 12:28:21.514  3119  3119 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal,
,03-17 12:28:21.524  1234  2997 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true,
,03-17 12:28:21.554  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:21.554  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:21.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:21.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.554  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:21.554  1317  1317 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 12:28:21.564  1020  1033 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-17 12:28:21.564  1317  2219 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-17 12:28:21.574  3119  3119 D DSM     : [Lines:107] Normal booted
03-17 12:28:21.574  3075  3075 D [0]UMC:AdminManager: loadAdmins
03-17 12:28:21.574  3119  3119 D DSM     : [Lines:114] Boot completed
,03-17 12:28:21.584  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.594  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.594  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.594  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.604  1020  1242 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:28:21.614  3075  3075 D [0]UMC:AdminManager: init - end
,03-17 12:28:21.614  3075  3075 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 12:28:21.614  3153  3153 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.614  1020  1567 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:21.614  3153  3153 E Zygote  : v2
03-17 12:28:21.614  3153  3153 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.614  3153  3153 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:21.624  3153  3153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:21.624  3153  3153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:21.624  3153  3153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:21.634  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:21.634  1234  2997 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 12:28:21.634  1317  1317 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 12:28:21.634  1317  1317 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 12:28:21.634  1234  2997 D MediaScanner: Skipping:
03-17 12:28:21.634  1234  2997 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 12:28:21.644  3075  3075 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 12:28:21.644  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.644  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:21.644  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:28:21.644  3075  3075 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 12:28:21.654  3075  3075 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 12:28:21.654  3075  3075 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 12:28:21.654  3075  3075 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 12:28:21.654  3075  3075 D [0]UMC:UMCAdmin: isContainer : 0
03-17 12:28:21.654  1173  1173 D PanelView: There is/are notification(s) 
,03-17 12:28:21.654  1020  1032 I art     : Explicit concurrent mark sweep GC freed 40097(2MB) AllocSpace objects, 94(7MB) LOS objects, 33% free, 22MB/33MB, paused 14.358ms total 328.798ms
,03-17 12:28:21.664  1020  3163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:21.664  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.664  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.664  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.664  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.664  1234  2997 D MediaScanner: Skipping:
03-17 12:28:21.664  1234  2997 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 12:28:21.664  1234  2997 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 12:28:21.664  1234  2997 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 12:28:21.664  1234  2997 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 12:28:21.674  1020  1242 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0,
,03-17 12:28:21.674  3153  3153 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.674  3153  3153 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.674  1625  1634 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 12:28:21.674  1234  2997 V MediaScanner:  prescan time: 156ms (DB items: 26)
03-17 12:28:21.674  1234  2997 V MediaScanner:     scan time: 37ms (Caching mode: true), (makeEntry time: 15ms ~40%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 12:28:21.674  1234  2997 V MediaScanner: postscan time: 8ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 12:28:21.674  1234  2997 V MediaScanner:    total time: 201ms
03-17 12:28:21.674  1234  2997 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
,03-17 12:28:21.684  3174  3174 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.684  3174  3174 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.684  3174  3174 E Zygote  : v2
03-17 12:28:21.684  3174  3174 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:21.684  3174  3174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:21.684   299   299 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 12:28:21.684  1020  1567 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3174 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:21.694  3174  3174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:21.694  2906  2906 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2192d881 time:36151
03-17 12:28:21.694  3174  3174 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:21.704  1625  2845 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 12:28:21.704  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.704  1020  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:21.704  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:28:21.704  1020  1051 I ActivityManager: Displayed Component not be shown by security: +1s701ms
,03-17 12:28:21.704  1020  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 12:28:21.714   307   307 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 25.026ms
,03-17 12:28:21.714   320   320 I ServiceManager: Waiting for service AtCmdFwd...
03-17 12:28:21.714  1020  1051 W ActivityManager: mDVFSHelper.release()
03-17 12:28:21.714  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a7f72e4 u0 com.test.thalitest/.MainActivity t11} time:36172
,03-17 12:28:21.724  1020  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:28:21.724   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.770ms
,03-17 12:28:21.734  1020  1129 D SettingsProvider: name = personal_mode_enabled
,03-17 12:28:21.734  1625  1638 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.734  1625  1638 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:21.734  1625  1638 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.734  1625  1638 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:21.734  1625  1638 D BadgeProvider: update, [UpdateCount] : 1
03-17 12:28:21.734  1487  1487 D Launcher.Model: reloadBadges entered.
03-17 12:28:21.734  1487  1487 D Launcher.Model: reloadBadges entered.
,03-17 12:28:21.734  1234  2997 D MediaScannerService: !@done scanning volume external
,03-17 12:28:21.744  1625  2846 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.744  1625  2846 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:21.744  1625  2846 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.744  1625  2846 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:21.744  1625  2846 D BadgeProvider: update, [UpdateCount] : 1
,03-17 12:28:21.744  2640  2640 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2640) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 12:28:21.744  2640  2640 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2640) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 12:28:21.744  2640  2640 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2640) ...
03-17 12:28:21.744  2640  2640 D FactoryTestApp: [Support$Values.getString](2640) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 12:28:21.744  2640  2640 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2640) mConnectionMode = gsm
03-17 12:28:21.744  2640  2640 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2640) Create IPCWriterToSecPhoneService
03-17 12:28:21.744  2640  2640 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2640)  
03-17 12:28:21.744  1020  1033 I ActivityManager: Killing 2238:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-17 12:28:21.744  2424  3033 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 12:28:21.744   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.169ms
,03-17 12:28:21.754  2640  2640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 12:28:21.754  2424  3070 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 12:28:21.754  3075  3075 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-17 12:28:21.754  3075  3075 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 12:28:21.774  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:21.774  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:21.774  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 12:28:21.774  3174  3174 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.774  3174  3174 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.774  2424  3033 D Mms/MessagingNotification: remove alarm
,03-17 12:28:21.784  2424  3070 D Mms/MessagingNotification: remove alarm
,03-17 12:28:21.784  2424  3191 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 12:28:21.784  3153  3153 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:21.784  3075  3075 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 12:28:21.794  3075  3075 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
,03-17 12:28:21.794  3075  3075 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 12:28:21.814  1461  3125 D TP/SmsProvider: query,matched:0, calling pid = 2424
03-17 12:28:21.814  1461  3125 D TP/SmsProvider: match 0:Elapsed time : 1.265 ms
,03-17 12:28:21.814  3075  3075 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 12:28:21.814   299   299 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 12:28:21.814   299   299 E USB_UICC: usb_uicc_init_qmi failed ! 
,03-17 12:28:21.814   299   299 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 12:28:21.814   299   299 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 12:28:21.824  3075  3075 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-17 12:28:21.824  3075  3075 I [0]UMC:Core: shutdown
,03-17 12:28:21.824  2424  3190 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 12:28:21.834  3174  3174 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:21.834  3075  3075 I art     : System.exit called, status: 0
03-17 12:28:21.834  3075  3075 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 12:28:21.834  2090  3114 W DriveInitializer: Background init thread ended
,03-17 12:28:21.834  1866  1866 I SamsungIME: getCurrentCandidateView
,03-17 12:28:21.864  2662  2785 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 12:28:21.874  2424  3033 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 965.653958
,03-17 12:28:21.874  1461  1809 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 12:28:21.874  1020  1045 W libprocessgroup: failed to open /acct/uid_10065/pid_2238/cgroup.procs: No such file or directory
,03-17 12:28:21.874  1461  1809 D TP/SmsProvider: match 0:Elapsed time : 3.309 ms
,03-17 12:28:21.874  1461  1461 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:21.874  1461  1461 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:21.874  1461  1461 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:21.884  1461  1461 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:21.884  1461  1461 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:21.884  1461  1461 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:28:21.884  1684  1707 I art     : Explicit concurrent mark sweep GC freed 7297(364KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.353ms total 39.946ms
03-17 12:28:21.884  2662  2785 D BluetoothMediaBrowser: no now playing list
03-17 12:28:21.884  2662  2785 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 12:28:21.904  2424  3070 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 31.988437
,03-17 12:28:21.924  2640  2640 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2640) connected done
03-17 12:28:21.924  2640  2640 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2640) Send Response Message to SecPhone
03-17 12:28:21.924  2640  2640 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2640) Response ��
,03-17 12:28:21.924  1317  1317 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 12:28:21.924  1317  1317 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 12:28:21.934  1020  1565 I ActivityManager: Killing 2253:com.vlingo.midas/u0a28 (adj 15): empty #31
03-17 12:28:21.934   313  1077 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 12:28:21.944  2640  2640 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2640) Send BOOTING COMPLETED done
03-17 12:28:21.954  1020  1486 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3075)(adj 0) has died(43,650)
03-17 12:28:21.954   259   457 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
03-17 12:28:21.954   259  1898 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
,03-17 12:28:21.974  3174  3174 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:28:21.974  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.974  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 12:28:21.974  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,03-17 12:28:21.974  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.974  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 12:28:21.984  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:21.984  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 12:28:21.984  3174  3174 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,03-17 12:28:21.984  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:28:21.984  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.984  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:21.994  1317  1317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:21.994  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 12:28:22.004  3213  3213 I libpersona: KNOX_SDCARD checking this for 10082
03-17 12:28:22.004  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 12:28:22.004  3213  3213 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.004  3213  3213 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.004  1020  1032 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3213 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
03-17 12:28:22.004  3213  3213 E Zygote  : v2
03-17 12:28:22.004  3213  3213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:22.004  1020  1032 I ActivityManager: Killing 2281:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-17 12:28:22.004  3213  3213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:22.004  3213  3213 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.014  1020  1045 W libprocessgroup: failed to open /acct/uid_10028/pid_2253/cgroup.procs: No such file or directory
,03-17 12:28:22.014  1317  1317 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 12:28:22.024  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:28:22.034  2906  2906 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:28:22.034  1814  1814 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 12:28:22.034  1814  1814 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:28:22.034  1814  1814 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 12:28:22.034  1814  1814 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 12:28:22.034  1814  1814 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:28:22.034  1814  1814 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 12:28:22.034  1814  1814 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 12:28:22.034   313  1077 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 12:28:22.034   313  1077 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 12:28:22.044  1020  1129 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 12:28:22.044  1020  1129 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:22.044  1020  1129 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:22.044  1020  1129 D SettingsProvider: selectionArgs: false
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 12:28:22.044  1020  1129 D SettingsProvider: selectionArgs: 10157
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 12:28:22.044  1020  1129 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 12:28:22.044  1020  1129 D SettingsProvider: ret = -1
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-17 12:28:22.044  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 12:28:22.054  3213  3213 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-17 12:28:22.054  3174  3174 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-17 12:28:22.054  3213  3213 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.054  1020  1129 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,03-17 12:28:22.064  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:22.064  3174  3174 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 12:28:22.074  1020  1045 W libprocessgroup: failed to open /acct/uid_10045/pid_2281/cgroup.procs: No such file or directory
03-17 12:28:22.074  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:22.074  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 12:28:22.074  1317  1317 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-17 12:28:22.074  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:22.084  1020  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:22.084  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:22.084  1866  1866 D SamsungIME: Dismiss ExpandCandiate
,03-17 12:28:22.094  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:22.094  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:22.094  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 12:28:22.104  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:22.104  1317  1317 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-17 12:28:22.104  1317  1317 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 12:28:22.104  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.104  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.104  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.104  1020  1301 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.104  1814  1814 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 12:28:22.104  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:22.114  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458214102119
,03-17 12:28:22.114  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458235680000
,03-17 12:28:22.114  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 12:28:22.114  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-17 12:28:22.114  2906  3185 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!,
03-17 12:28:22.114  2906  3185 I chromium: 
,03-17 12:28:22.134  3234  3234 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.134  3234  3234 E Zygote  : v2
03-17 12:28:22.134  3234  3234 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:22.134  3234  3234 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.134  3234  3234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:22.134  1020  1301 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3234 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-17 12:28:22.134  1317  1317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 12:28:22.134  3234  3234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:22.134  3234  3234 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.134  1020  1301 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:22.134  1020  1301 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:22.134  1020  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:22.144  1317  3243 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 12:28:22.154  1020  1502 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:22.154  1020  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:22.154  1020  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:22.154  1814  1814 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458235680000
,03-17 12:28:22.174  1020  1242 I ActivityManager: Killing 2338:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,03-17 12:28:22.184  3234  3234 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.184  3234  3234 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.204  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.204  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.204  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.204  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.214  3253  3253 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.214  3253  3253 I libpersona: KNOX_SDCARD checking this for 10146
03-17 12:28:22.214  3253  3253 E Zygote  : v2
03-17 12:28:22.214  3253  3253 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.214  3253  3253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:22.224  3253  3253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:22.224  3253  3253 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:28:22.224  1020  1032 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3253 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,03-17 12:28:22.244  1814  1814 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 83
,03-17 12:28:22.244  1814  1814 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458235680000
,03-17 12:28:22.244  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.244  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.244  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.244  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.244  1020  1045 W libprocessgroup: failed to open /acct/uid_10110/pid_2338/cgroup.procs: No such file or directory
,03-17 12:28:22.254  3253  3253 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.264  3253  3253 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.264  3268  3268 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.264  3268  3268 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 12:28:22.264  3268  3268 E Zygote  : v2
03-17 12:28:22.264  3268  3268 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.264  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:22.264  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:22.264  1020  1129 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:22.264  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.284  2906  3252 D jxcore_app_log: JniHelper::setJavaVM(0xb8af1448), pthread_self() = -1189802576
,03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c4d44 added. We now have 1 listener(s)
,03-17 12:28:22.304  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.304  3268  3268 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.304  2906  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 12:28:22.304  2906  3252 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 12:28:22.304  2906  3252 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 12:28:22.304  2906  3252 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 12:28:22.304  2906  3252 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 12:28:22.314  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 12:28:22.314  2906  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f48b8f3 added. We now have 1 listener(s)
,03-17 12:28:22.314  2906  3252 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:28:22.324  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.334  2906  3252 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 12:28:22.334  2906  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 12:28:22.334  2906  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 12:28:22.334  2906  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 12:28:22.334  2906  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 12:28:22.334  3268  3268 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:22.334  2906  3252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 12:28:22.344  2906  3252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:28:22.344  2906  3252 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:28:22.344  2906  3252 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 12:28:22.344  2906  3252 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:28:22.354  2906  2906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:28:22.354  2906  2906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:28:22.364  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.374  2906  2906 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:28:22.374  3234  3234 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 12:28:22.384  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.394  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.394  3213  3213 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:22.404  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.404  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.404  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.404  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.414  3299  3299 E Zygote  : MountEmulatedStorage(),
03-17 12:28:22.414  3299  3299 I libpersona: KNOX_SDCARD checking this for 10088
03-17 12:28:22.414  3299  3299 E Zygote  : v2
03-17 12:28:22.414  3299  3299 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.414  3299  3299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:22.414  1020  1242 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3299 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 12:28:22.424  1020  1242 I ActivityManager: Killing 1673:com.google.android.partnersetup/u0a14 (adj 15): empty #31,
,03-17 12:28:22.424  3299  3299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:22.424  3299  3299 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.454  1866  1866 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:28:22.454  3299  3299 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.454  3299  3299 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.464  1020  1301 I ActivityManager: Killing 2409:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 12:28:22.494  3268  3268 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 12:28:22.504  1814  1814 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 12:28:22.504  1814  1814 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 12:28:22.534  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.534  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.534  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.534  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.554  3316  3316 E Zygote  : MountEmulatedStorage(),
03-17 12:28:22.554  3316  3316 E Zygote  : v2
03-17 12:28:22.554  3316  3316 I libpersona: KNOX_SDCARD checking this for 10161
,03-17 12:28:22.554  3316  3316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:22.554  3316  3316 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.554  3316  3316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:22.554  3316  3316 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:22.554  1020  1242 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3316 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:28:22.594  3316  3316 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.594  1020  1045 W libprocessgroup: failed to open /acct/uid_10014/pid_1673/cgroup.procs: No such file or directory
03-17 12:28:22.594  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2409/cgroup.procs: No such file or directory
,03-17 12:28:22.594  3316  3316 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.594  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 12:28:22.604  2906  2926 I art     : Background partial concurrent mark sweep GC freed 6622(493KB) AllocSpace objects, 7(198KB) LOS objects, 39% free, 7MB/11MB, paused 6.189ms total 51.039ms
,03-17 12:28:22.614  3234  3234 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 12:28:22.614  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 12:28:22.614  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 12:28:22.634  3234  3234 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 12:28:22.644  3234  3234 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 12:28:22.644  3234  3234 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 12:28:22.644  3234  3234 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 12:28:22.644  3234  3234 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 12:28:22.674   290   290 E SMD     : DCD OFF
,03-17 12:28:22.704  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.704  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.704  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.704  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.714   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:28:22.714  3333  3333 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.714  3333  3333 E Zygote  : v2
03-17 12:28:22.714  3333  3333 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:22.714  3333  3333 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.714  3333  3333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:22.714  3333  3333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:22.724  1020  1565 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3333 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:28:22.724  3333  3333 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:28:22.754  3333  3333 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.754  3333  3333 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.834  1866  1866 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:28:22.904  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:22.904  1020  1485 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 12:28:22.904  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 12:28:22.904  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.904  3316  3348 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:28:22.904  3316  3348 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:28:22.904  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.904  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.904  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.924  3351  3351 E Zygote  : MountEmulatedStorage()
,03-17 12:28:22.924  3351  3351 E Zygote  : v2
03-17 12:28:22.924  3351  3351 I libpersona: KNOX_SDCARD checking this for 10088
03-17 12:28:22.924  3351  3351 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.924  1020  1485 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3351 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:22.984  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.984  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.984  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.984  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.994  3362  3362 E Zygote  : MountEmulatedStorage()
,03-17 12:28:22.994  3362  3362 E Zygote  : v2
03-17 12:28:22.994  3362  3362 I libpersona: KNOX_SDCARD checking this for 10008
03-17 12:28:22.994  3362  3362 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.004  1020  1485 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3362 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:23.014  3351  3351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 12:28:23.014  3362  3362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:28:23.014  3351  3351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:23.014  3362  3362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:23.014  3351  3351 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:28:23.014  3362  3362 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.024  2906  3292 W jxcore-log: Initializing JXcore engine,
03-17 12:28:23.024  2906  3292 W jxcore-log: JXcore engine is ready
,03-17 12:28:23.034  1866  1866 I SamsungIME: KeybaordView init() : load resources
,03-17 12:28:23.034  3351  3351 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.034  3362  3362 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:23.034  3362  3362 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.044  3351  3351 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.044  3268  3268 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 12:28:23.044  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 12:28:23.044  3268  3268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 12:28:23.044  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.044  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.044  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 12:28:23.064  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.064  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 12:28:23.074  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 12:28:23.074  1173  1173 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.094  1173  1173 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 12:28:23.094  1173  1173 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 12:28:23.104  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 12:28:23.104  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 12:28:23.104  1173  1173 D OverheatReceiver: isSafeMode = false
03-17 12:28:23.114  2906  2926 I art     : Background sticky concurrent mark sweep GC freed 42830(3MB) AllocSpace objects, 7(1925KB) LOS objects, 19% free, 9MB/11MB, paused 1.056ms total 174.376ms
,03-17 12:28:23.114  3333  3333 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 12:28:23.114  3333  3333 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 12:28:23.124  3316  3348 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:28:23.124  1461  1461 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.124  1020  1129 D SettingsProvider: name = internet_call_settings_visibility
03-17 12:28:23.124  1020  1129 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:23.124  1020  1129 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:23.124  1020  1129 D SettingsProvider: selectionArgs: false
03-17 12:28:23.124  1020  1129 D SettingsProvider: selectionArgs: 1001
03-17 12:28:23.124  1020  1129 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:23.124  1020  1129 D SettingsProvider: ret = -1
03-17 12:28:23.124  1461  1461 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 12:28:23.134  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 12:28:23.144  3268  3325 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 12:28:23.144  1905  1905 E audit   : type=1400 msg=audit(1458214103.144:205): avc:  denied  { ioctl } for  pid=3292 comm="Thread-352" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 12:28:23.154  1905  1905 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:23.154  1905  1905 E audit   : type=1300 msg=audit(1458214103.144:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=926f08f8 items=0 ppid=307 ppcomm=main pid=3292 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-352" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-17 12:28:23.154  1905  1905 E audit   : type=1320 msg=audit(1458214103.144:205): 
03-17 12:28:23.154  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 12:28:23.154  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 12:28:23.164  3333  3385 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 12:28:23.164  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 12:28:23.164  2906  3292 W jxcore-log: Starting JXcore engine
,03-17 12:28:23.164  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 12:28:23.174  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 12:28:23.174  3268  3325 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 12:28:23.174  3268  3325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 12:28:23.174  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 12:28:23.174  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 12:28:23.174  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.174  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.174  3333  3333 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 12:28:23.174  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 12:28:23.184  3333  3385 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 12:28:23.194  1866  1866 I SamsungIME: getCurrentKeyboard,
03-17 12:28:23.194  1866  1866 I SamsungIME: getTextKeyboard
,03-17 12:28:23.194  3333  3333 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] ,
,03-17 12:28:23.194  3333  3333 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 12:28:23.204  3333  3333 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !,
,03-17 12:28:23.214  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard,
,03-17 12:28:23.214  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true],
,03-17 12:28:23.234  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 12:28:23.234  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 12:28:23.234  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 12:28:23.234  3333  3385 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 12:28:23.234  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 12:28:23.254  1437  1437 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 12:28:23.254  1020  1502 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.254  3268  3268 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 12:28:23.254  1020  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.254  1020  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 12:28:23.254  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 12:28:23.264  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.264  1020  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:23.264  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 12:28:23.264   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:28:23.264   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:23.274  3316  3316 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:28:23.274  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.274  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.274  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.274  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.294  3316  3348 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c5deaaf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:28:23.294  3316  3348 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 12:28:23.294  3316  3348 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 12:28:23.294  1020  1566 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3395 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 12:28:23.294  3395  3395 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.294  3395  3395 I libpersona: KNOX_SDCARD checking this for 10052
03-17 12:28:23.294  3395  3395 E Zygote  : v2
03-17 12:28:23.294  3395  3395 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.294  3395  3395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:23.294  3395  3395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:23.304  3395  3395 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.304  2906  3292 W jxcore-log: Platform android
03-17 12:28:23.304  2906  3292 W jxcore-log: 
03-17 12:28:23.304  2906  3292 W jxcore-log: Process ARCH arm
03-17 12:28:23.304  2906  3292 W jxcore-log: 
,03-17 12:28:23.324  3299  3299 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 12:28:23.324  3268  3325 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 12:28:23.324  3395  3395 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:23.334  1866  1866 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 12:28:23.334  3395  3395 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.364  3299  3299 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 12:28:23.364  1437  1437 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 12:28:23.424  3299  3299 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 12:28:23.494  3333  3385 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,03-17 12:28:23.494  3333  3385 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:23.504   285   285 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 12:28:23.504   285   285 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 12:28:23.504   285   285 V msm8974_platform: platform_get_parameters: exit: returns - 
,03-17 12:28:23.504   285   285 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 12:28:23.504   285   285 I str_params: key: 'call_forwarding' value: ''
,03-17 12:28:23.504  1961  1961 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 12:28:23.504  1961  1961 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 12:28:23.504  1961  1961 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 12:28:23.514  1961  1961 D ScoverManager: serviceVersion : 16908288
,03-17 12:28:23.514  1020  1567 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:23.514  3333  3385 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 12:28:23.514  3333  3385 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 12:28:23.514  3333  3385 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 12:28:23.524  1020  1567 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.524  1020  1567 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:23.524  1020  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:23.534  1961  1961 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 12:28:23.534  1437  1437 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 12:28:23.534  1020  1486 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:28:23.534  1961  1961 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 12:28:23.534  1961  1961 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 12:28:23.534  1961  1961 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS,
03-17 12:28:23.544  1961  1961 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 12:28:23.544  3333  3342 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:28:23.544  3333  3342 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 12:28:23.544  3299  3299 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 12:28:23.554  3333  3342 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:28:23.554  3333  3385 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 12:28:23.554  1961  1961 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 12:28:23.554  1961  1961 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 12:28:23.554  3299  3299 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 12:28:23.564  3333  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:28:23.564  3333  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:28:23.564  3333  3341 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:28:23.574  2906  3292 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:28:23.574  2906  3292 I jxcore-log: 
,03-17 12:28:23.584  2906  3292 W jxcore-log: JXcore engine is started
,03-17 12:28:23.584  3268  3325 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 12:28:23.584  1020  1502 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.584  1020  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:23.584  1020  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:23.594  1173  1173 D PhoneStatusBarView: setCallBackground:0
,03-17 12:28:23.594  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:23.594  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:23.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:23.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:23.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:23.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:23.594  2906  3252 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-17 12:28:23.594  3333  3385 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 12:28:23.604  1020  1033 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:23.604  1961  1961 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 12:28:23.604  2906  2906 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 12:28:23.604  3333  3385 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:23.604  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 12:28:23.614  3333  3386 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 12:28:23.614  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 12:28:23.614  3333  3386 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:23.624  2906  3292 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:28:23.624  2906  3292 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:28:23.624  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 12:28:23.624  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/12:28:23
,03-17 12:28:23.624  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 12:28:23.624  3333  3385 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 12:28:23.634  2906  2906 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 12:28:23.634  2906  2906 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 12:28:23.634  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 12:28:23.634  3333  3386 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 12:28:23.644  1020  1567 D FocusedStackFrame: Set to : 0
03-17 12:28:23.644  1020  1567 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:23.644  1020  1567 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:28:23.644  1020  1567 D InputDispatcher: Focused application set to: xxxx
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-17 12:28:23.644  1020  1567 D InputDispatcher: Focus left window: 2906
03-17 12:28:23.644  3299  3299 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-17 12:28:23.644  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-17 12:28:23.654  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:28:23.654  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:28:23.654   259   454 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (306 us)
03-17 12:28:23.654  3268  3325 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 12:28:23.654  3268  3325 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 12:28:23.664  3268  3325 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 12:28:23.674  2906  3252 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 41ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 12:28:23.674  3299  3299 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 12:28:23.684  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.684  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.684  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.684  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.684  1961  1961 D VideoCallManager: Instantiating VideoCallManager
,03-17 12:28:23.684  2763  3314 I art     : WaitForGcToComplete blocked for 114.020ms for cause DisableMovingGc
03-17 12:28:23.684  2763  3427 I art     : WaitForGcToComplete blocked for 93.699ms for cause DisableMovingGc
,03-17 12:28:23.694  3434  3434 E Zygote  : MountEmulatedStorage()
,03-17 12:28:23.694  3434  3434 E Zygote  : v2
03-17 12:28:23.694  3434  3434 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:23.694  3434  3434 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.694  3434  3434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:23.704  3434  3434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 12:28:23.704  1020  1032 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3434 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:28:23.704  3434  3434 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.704  1020  1032 I ActivityManager: Killing 2450:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 12:28:23.704  1020  1032 I ActivityManager: Killing 2441:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #32
,03-17 12:28:23.704  1020  1566 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 12:28:23.704  1020  1566 W ActivityManager: mDVFSHelper.acquire()
,03-17 12:28:23.714   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 12:28:23.724  1020  1566 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:28:23.724  1020  1566 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:28:23.724  1020  1566 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 12:28:23.724   307   307 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 23.985ms
,03-17 12:28:23.724  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 12:28:23.734  1961  1961 I GFX construct_block_size_descriptor_2d second part: took 2.653490ms for 0*0 texture 0
,03-17 12:28:23.734  3333  3385 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 12:28:23.744  3434  3434 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:23.744  1961  1961 I GFX generate_partition_tables: took 5.383699ms for 0*0 texture 0
03-17 12:28:23.744  3434  3434 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.744  1961  1961 I GFX raster: took 11.845365ms for 176*144 texture 0
03-17 12:28:23.744  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9bbb0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8e9b480 counterpartCT=4 counterpartW=176 counterparth=144
03-17 12:28:23.744   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 17.919ms,
,03-17 12:28:23.754  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-17 12:28:23.754  1961  1961 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:28:23.754  1961  1961 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:23.754  1961  1961 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:23.754  1961  1961 I Adreno-EGL: Local Branch: 
03-17 12:28:23.754  1961  1961 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:23.754  1961  1961 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:23.754  1961  1961 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:23.764   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 18.055ms
,03-17 12:28:23.764  1487  1487 D Launcher: onRestart, Launcher: 446282358
,03-17 12:28:23.774  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:23.794  1961  1961 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 12:28:23.794  1487  1487 D Launcher: onStart, Launcher: 446282358
,03-17 12:28:23.794  1020  1242 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.794  1020  1242 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:23.794  1020  1242 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 12:28:23.794  1487  1487 D Launcher.HomeView: onStart
03-17 12:28:23.794  1487  1487 D Launcher: onResume, Launcher: 446282358
03-17 12:28:23.794  1961  1961 I glCompressedTexImage2D: took 0.236510ms for 320*61440 texture 37809
,03-17 12:28:23.794  1020  1502 I ActivityManager: Killing 2473:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 12:28:23.794  1020  1565 D SettingsProvider: name = kids_home_mode
03-17 12:28:23.794  1020  1565 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:23.794  1020  1565 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:23.794  1020  1565 D SettingsProvider: selectionArgs: false
03-17 12:28:23.794  1020  1565 D SettingsProvider: selectionArgs: 10006
03-17 12:28:23.794  1020  1565 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:23.794  1020  1565 D SettingsProvider: ret = -1
03-17 12:28:23.804  1487  1487 D Launcher.HomeView: onResume
03-17 12:28:23.804  3299  3299 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 12:28:23.804  1961  1961 I draw setup: took 10.581718ms for 320*240 texture 37809
03-17 12:28:23.804  1961  1961 E GFX GPU raster: drawn
,03-17 12:28:23.804  1961  1961 I GFX GPU raster ASTC: took 38.210156ms for 320*240 texture 12
03-17 12:28:23.804  1961  1961 I GFX raster: took 38.293384ms for 320*240 texture 0
03-17 12:28:23.804  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9bb30 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8e9b698 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 12:28:23.814  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:28:23.814  1020  1020 D SensorService: [SO] activate (ident=0xb94ceec8, enabled=0)
03-17 12:28:23.814  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 12:28:23.814  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 12:28:23.824  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 12:28:23.824  1961  1961 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:28:23.824  1020  1020 D SensorManager: unregisterListener ::   
03-17 12:28:23.824  1961  1961 I glCompressedTexImage2D: took 0.327447ms for 480*122880 texture 37813
03-17 12:28:23.824  1961  1961 I draw setup: took 0.609583ms for 480*640 texture 37813
03-17 12:28:23.824  1961  1961 E GFX GPU raster: drawn
03-17 12:28:23.824  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-17 12:28:23.824  1020  1020 D SensorService: [SO] changed settle time [0]
03-17 12:28:23.824  1020  1020 D SensorService: [SO] setDelay [200000000]
03-17 12:28:23.824  1020  1020 D SensorService: [SO] activate (ident=0xb94ceec8, enabled=1)
03-17 12:28:23.824  1020  1020 D SensorService: [SO] AR_init
03-17 12:28:23.824  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 12:28:23.824  1487  1487 D MenuAppsGridFragment: onResume
03-17 12:28:23.824  1020  3451 D ActivityManager: handle home activity for 0
03-17 12:28:23.824  1020  3451 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 12:28:23.824  1020  3451 D KnoxTimeoutHandler: post home show event for user 0
03-17 12:28:23.834  1020  3451 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 12:28:23.834  1020  3451 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:28:23.834  1020  3451 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 12:28:23.834  1961  1961 I GFX GPU raster ASTC: took 7.027760ms for 480*640 texture 12
03-17 12:28:23.834  1961  1961 I GFX raster: took 7.102916ms for 480*640 texture 0
03-17 12:28:23.834  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9b698 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb90dd0f0 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 12:28:23.834   259   259 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-17 12:28:23.834  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,03-17 12:28:23.844  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 12:28:23.844  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 12:28:23.844  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 12:28:23.844  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:28:23.844  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 12:28:23.854  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:28:23.854  1020  1033 D InputDispatcher: Focus entered window: 1487
,03-17 12:28:23.854  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:28:23.854  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:28:23.864  1487  1487 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:28:23.874  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-17 12:28:23.874  1961  1961 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 12:28:23.874  1961  1961 I glCompressedTexImage2D: took 0.381198ms for 440*116864 texture 37809
03-17 12:28:23.874  1961  1961 I draw setup: took 0.721876ms for 440*330 texture 37809
03-17 12:28:23.874  1961  1961 E GFX GPU raster: drawn
,03-17 12:28:23.884  1961  1961 I GFX GPU raster ASTC: took 5.057500ms for 440*330 texture 12
03-17 12:28:23.884  1961  1961 I GFX raster: took 5.142813ms for 440*330 texture 0
03-17 12:28:23.884  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb90dd0d0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb90dd4a0 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 12:28:23.894  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:28:23.894  1020  3451 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:28:23.894  1173  1173 D PanelView: There is/are notification(s) 
,03-17 12:28:23.904  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.904  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.904  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.904  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.904  1866  1866 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 12:28:23.914  1020  3460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 12:28:23.924  2906  2906 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:28:23.924  3463  3463 E Zygote  : MountEmulatedStorage()
,03-17 12:28:23.924  3463  3463 E Zygote  : v2
03-17 12:28:23.924  3463  3463 I libpersona: KNOX_SDCARD checking this for 10014
03-17 12:28:23.924  3463  3463 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:23.924  1020  1565 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3463 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:23.924  3463  3463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:23.934  3463  3463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:23.934  3463  3463 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.944  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 12:28:23.954  1487  1487 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10c442 time:38411
,03-17 12:28:23.954  1020  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:28:23.964  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 12:28:23.964  1961  1961 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 12:28:23.974  1961  1961 I glCompressedTexImage2D: took 0.475625ms for 480*163840 texture 37811
03-17 12:28:23.974  1961  1961 I draw setup: took 0.948020ms for 480*640 texture 37811
03-17 12:28:23.974  1961  1961 E GFX GPU raster: drawn
,03-17 12:28:23.974  1961  1961 I GFX GPU raster ASTC: took 7.166458ms for 480*640 texture 12
03-17 12:28:23.974  1961  1961 I GFX raster: took 7.248594ms for 480*640 texture 0
03-17 12:28:23.974  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb90dcf10 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb90eff38 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 12:28:23.984  1020  1051 I ActivityManager: Displayed Component not be shown by security: +261ms
,03-17 12:28:23.984  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2450/cgroup.procs: No such file or directory
03-17 12:28:23.984  1020  1045 W libprocessgroup: failed to open /acct/uid_10127/pid_2441/cgroup.procs: No such file or directory
03-17 12:28:23.984  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2473/cgroup.procs: No such file or directory
,03-17 12:28:23.994  3442  3442 D AndroidRuntime: 
03-17 12:28:23.994  3442  3442 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 12:28:23.994  3442  3442 D AndroidRuntime: CheckJNI is OFF
,03-17 12:28:23.994  3442  3442 D AndroidRuntime: readGMSProperty: start
03-17 12:28:23.994  3442  3442 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:28:23.994  3442  3442 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:28:23.994  3442  3442 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:28:23.994  3442  3442 D AndroidRuntime: readGMSProperty: end
03-17 12:28:23.994  3442  3442 D AndroidRuntime: addProductProperty: start
,03-17 12:28:24.004  3463  3463 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.004  3463  3463 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:24.014  1020  1301 D LocationManagerService: getProviders()=[passive]
,03-17 12:28:24.024  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
03-17 12:28:24.024  1961  1961 I GFX construct_block_size_descriptor_2d second part: took 2.212604ms for 0*0 texture 0
,03-17 12:28:24.034  1961  1961 I GFX generate_partition_tables: took 7.571770ms for 0*0 texture 0
,03-17 12:28:24.034  1961  1961 I GFX raster: took 11.717447ms for 176*144 texture 0
03-17 12:28:24.034  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb90cd020 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb90eff58 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 12:28:24.044  1020  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 12:28:24.054  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:24.054  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:24.054  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:24.054  1961  1961 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,03-17 12:28:24.064  1961  1961 I GFX construct_block_size_descriptor_2d second part: took 2.688073ms for 0*0 texture 0
,03-17 12:28:24.064  1961  1961 I GFX generate_partition_tables: took 6.151302ms for 0*0 texture 0
,03-17 12:28:24.064  1961  1961 I GFX raster: took 10.916303ms for 176*144 texture 0
03-17 12:28:24.064  1961  1961 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb90dd580 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb90f1c48 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 12:28:24.074  1961  1961 D ScoverManager: registerListener
,03-17 12:28:24.074  1020  1032 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:24.074  1020  1485 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:28:24.074  1020  1485 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1827c0a8, pid : 1961, uid : 1001, type : 1
,03-17 12:28:24.114  3434  3434 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 12:28:24.124  3434  3434 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 12:28:24.124  3434  3434 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
03-17 12:28:24.124  3434  3434 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 12:28:24.134  3442  3442 E AffinityControl: AffinityControl: registerfunction enter
,03-17 12:28:24.134  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.134  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.134  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.134  1020  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.154  3494  3494 E Zygote  : MountEmulatedStorage()
,03-17 12:28:24.154  3494  3494 E Zygote  : v2
03-17 12:28:24.154  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
03-17 12:28:24.154  3494  3494 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:24.154  3494  3494 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.154  3494  3494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:24.154  3494  3494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:24.154  3494  3494 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:28:24.154  1020  1129 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:28:24.164  3442  3442 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-17 12:28:24.164  3333  3385 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 12:28:24.164  1961  1961 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 12:28:24.174  3494  3494 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.184  3494  3494 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.204  1020  1046 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 12:28:24.204  1020  1046 W ActivityManager: mDVFSHelper.release()
,03-17 12:28:24.204  1020  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
03-17 12:28:24.204  3395  3512 I Velvet.VelvetFactory: checking for language pack updates
,03-17 12:28:24.224  3494  3494 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 12:28:24.224  3494  3494 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 12:28:24.234  3494  3494 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 12:28:24.244  1020  1043 D SensorService: [SO] currT = 38701060000, prevT = 38251064000, diff = 449996000, [-0.460 0.211 9.883]
,03-17 12:28:24.244  1020  1043 D SensorService: [SO] -0.460 0.211 9.883
03-17 12:28:24.244  1020  1043 D SensorService: [SO] [100 -> 255]
,03-17 12:28:24.244  3494  3506 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 12:28:24.244  1020  1486 D PackageManager: START PACKAGE DELETE: observer{455123928}
03-17 12:28:24.244  1020  1486 D PackageManager: pkg{<packageName>}
03-17 12:28:24.244  1020  1486 D PackageManager: user{0}
03-17 12:28:24.244  1020  1486 D PackageManager: caller{2000}
03-17 12:28:24.244  1020  1486 D PackageManager: flags{2}
,03-17 12:28:24.244  1020  1486 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 12:28:24.244  1020  1486 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,03-17 12:28:24.244  1020  1486 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,03-17 12:28:24.254  1020  1486 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 12:28:24.254  1020  1486 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 12:28:24.254  1020  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 12:28:24.254  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 12:28:24.254  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 12:28:24.254  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 12:28:24.254  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 12:28:24.254  1020  1060 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-17 12:28:24.254  1020  1129 E Tethering: No numeric data
,03-17 12:28:24.264  3316  3316 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 12:28:24.264  1020  1046 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-17 12:28:24.264  1020  1046 I ActivityManager: Killing 2906:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 12:28:24.274  1020  1301 E Tethering: No numeric data,
,03-17 12:28:24.274  1020  1032 E Tethering: No numeric data
,03-17 12:28:24.274  1020  1566 E Tethering: No numeric data
,03-17 12:28:24.284  3434  3434 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 12:28:24.284  3434  3434 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 12:28:24.294  3434  3434 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 12:28:24.314  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 12:28:24.324  3395  3512 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 12:28:24.334  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:28:24.344  3333  3386 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 12:28:24.354  3299  3299 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-17 12:28:24.374  1020  1567 I WindowState: WIN DEATH: Window{17ab77b1 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 12:28:24.384  1020  1242 I art     : Explicit concurrent mark sweep GC freed 27904(1600KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 24MB/36MB, paused 4.022ms total 215.456ms
,03-17 12:28:24.384   259  1101 I SurfaceFlinger: id=12 Removed NainActivit (7/8)
,03-17 12:28:24.384   259  1898 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-17 12:28:24.394  3333  3385 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 12:28:24.424  1020  1060 W PackageSettings: Skipping PackageSetting{7a189f4 com.example.hello/10168} due to missing metadata
,03-17 12:28:24.454  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.454  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.454  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.454  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.454  1020  1502 E Tethering: No numeric data
,03-17 12:28:24.464  1020  1242 E Tethering: No numeric data
,03-17 12:28:24.474  3517  3517 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:24.474  3517  3517 E Zygote  : v2,
03-17 12:28:24.474  1020  1032 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:28:24.474  1020  1032 I ActivityManager: Killing 2565:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-17 12:28:24.474  1020  1032 I ActivityManager: Killing 2516:com.wsomacp/u0a23 (adj 15): empty #32
03-17 12:28:24.474  3517  3517 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:24.474  3517  3517 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.474  3517  3517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:24.484  1020  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:24.484  3517  3517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:24.484  1020  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:24.484  1020  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 12:28:24.484  3517  3517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:24.484  1020  1060 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
03-17 12:28:24.484  1020  2849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 12:28:24.504  1020  1060 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 12:28:24.504  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:28:24.504  1020  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 12:28:24.514  3517  3517 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.514  3517  3517 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.514  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{319c7c83 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:38976
,03-17 12:28:24.554  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,03-17 12:28:24.554  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 12:28:24.564  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 12:28:24.574  1866  1866 E SamsungIME: mOCRHelper is null
,03-17 12:28:24.604  1020  1131 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-17 12:28:24.604  1020  1131 V NetworkStats: performPollLocked(flags=0x3)
03-17 12:28:24.604  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 12:28:24.604  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 12:28:24.604  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 12:28:24.604  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:24.604  1461  1461 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:24.604  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 12:28:24.604  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-17 12:28:24.604  1020  1131 V NetworkStats: performPollLocked() took 5ms
03-17 12:28:24.604  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 12:28:24.634  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.634  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.634  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.634  1020  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.654  3541  3541 E Zygote  : MountEmulatedStorage()
03-17 12:28:24.654  3541  3541 E Zygote  : v2
03-17 12:28:24.654  3541  3541 I libpersona: KNOX_SDCARD checking this for 10090
03-17 12:28:24.654  3541  3541 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.654  3541  3541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:24.654  3541  3541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:24.654  3541  3541 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:24.654  1020  1485 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3541 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:24.654  3299  3533 I System.out: Thread-424(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:28:24.664  1020  1485 I ActivityManager: Killing 2581:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-17 12:28:24.674  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 12:28:24.674  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 12:28:24.694  1020  1565 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 12:28:24.694  1020  1565 D SecContentProvider2: mCursor = null
,03-17 12:28:24.694  3541  3541 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.694  3541  3541 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.704  1924  2206 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 12:28:24.714  3517  3517 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 12:28:24.724  3517  3517 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 12:28:24.734  3299  3533 I System.out: Thread-424(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:28:24.734  3299  3533 I System.out: Thread-424(ApacheHTTPLog):isShipBuild true
03-17 12:28:24.734  3299  3533 I System.out: Thread-424(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:28:24.734  3299  3533 I System.out: Thread-424(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:28:24.734   280  1014 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 12:28:24.734   280  1014 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 12:28:24.744  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 12:28:24.744  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 12:28:24.754  1020  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 12:28:24.754  1020  1502 I ActivityManager: Killing 2394:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 12:28:24.754  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 12:28:24.784  3395  3512 I Velvet.VelvetFactory: refreshing search history.
,03-17 12:28:24.784  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 12:28:24.784  1020  1162 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 12:28:24.784  1020  2793 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 12:28:24.784  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 12:28:24.784  1020  1162 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-17 12:28:24.794  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:24.794  3268  3325 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 12:28:24.794  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:24.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:24.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:24.804  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:24.804  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:24.804  3494  3504 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 12:28:24.814  1452  1452 D RegisteredServicesCache: empty dynamic service
,03-17 12:28:24.814  3395  3513 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-17 12:28:24.814  1317  3243 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 12:28:24.814  1317  3243 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 12:28:24.814  3517  3517 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 12:28:24.824  1020  1566 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:24.834  3517  3517 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 12:28:24.834  1020  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 12:28:24.834  1020  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 12:28:24.834  1020  1045 W TextServicesManagerService: no available spell checker services found
,03-17 12:28:24.844  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.844  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.854  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.854  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.854  3395  3558 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 12:28:24.854  3395  3513 I Search.GservicesUpdateTask: Updating Gservices keys
03-17 12:28:24.854  3395  3558 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 12:28:24.864  3541  3541 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 12:28:24.864  3541  3541 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 12:28:24.864  3541  3541 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 12:28:24.874  1020  3516 E Tethering: No numeric data
,03-17 12:28:24.874  1020  1033 E Tethering: No numeric data
,03-17 12:28:24.874  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:24.874  1020  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:24.874  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 12:28:24.884  1020  1033 E Tethering: No numeric data
03-17 12:28:24.884  1020  1242 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:24.884  3541  3541 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 12:28:24.884  1020  1486 I AudioService: getStreamVolume 3 index 0
,03-17 12:28:24.894  3541  3541 D elm:15121: ElmAgentService : onCreate()
,03-17 12:28:24.894  1020  1301 E Tethering: No numeric data
,03-17 12:28:24.894  3541  3566 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 12:28:24.904  3541  3541 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-17 12:28:24.904  3541  3541 D elm:15121: BootCompletedState : startBootCompleted() call
,03-17 12:28:24.914  1421  1421 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 12:28:24.924  3541  3541 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:28:24.924  2640  3211 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3211)  
,03-17 12:28:24.934  1020  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 12:28:24.944  1020  1060 I art     : Explicit concurrent mark sweep GC freed 23299(1649KB) AllocSpace objects, 10(1074KB) LOS objects, 33% free, 23MB/35MB, paused 6.422ms total 431.333ms
,03-17 12:28:24.954  3541  3541 I elm:15121: Get License : 0
,03-17 12:28:24.954  3541  3541 D elm:15121: ElmAgentService : onDestroy().
,03-17 12:28:24.964  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.974  1020  1060 D PackageManager: delete codoeFile: 
,03-17 12:28:24.974  1020  1060 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-17 12:28:24.974  1020  1060 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 12:28:24.974  1020  1060 D PackageManager: result of delete: 1{455123928}
03-17 12:28:24.974  1020  3451 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:24.984  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:24.984   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:28:24.984   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:24.984  3316  3316 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:28:24.984  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:24.994  1020  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:24.994  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 12:28:24.994   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:28:24.994   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:24.994  3316  3316 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:28:25.004  1020  1567 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.004  1020  1567 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.004  1020  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:25.004  3517  3517 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 12:28:25.004   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:28:25.004   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:25.004  1020  1301 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:25.004  3316  3316 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:28:25.004  3517  3517 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 12:28:25.004  3517  3517 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 12:28:25.014  3517  3517 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 12:28:25.014  3517  3517 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 12:28:25.014  3517  3517 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 12:28:25.014  3517  3517 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 12:28:25.014  2763  2902 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:28:25.024  1020  3451 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.024  1020  3451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.024  1020  3451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:25.024  1020  1242 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:25.034  1020  1032 I AudioService: getStreamVolume 3 index 0
,03-17 12:28:25.034  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:25.034  3395  3395 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 12:28:25.034  1317  3243 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-17 12:28:25.034  3442  3442 D AndroidRuntime: Shutting down VM
03-17 12:28:25.034  1020  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:25.034  1020  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:25.034  1020  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:25.044  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:25.044  3395  3395 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 12:28:25.044  3395  3395 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 12:28:25.044  1020  1301 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:25.044  1020  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 12:28:25.044  1020  1060 D PackageManager: userId{-1}
03-17 12:28:25.044  1020  1060 D PackageManager: andCode{true}
,03-17 12:28:25.054  1020  3535 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:25.054  1421  1421 V EmergencyMode: [EmergencyBase] setBootTime
03-17 12:28:25.054  1421  1421 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 12:28:25.064  1317  3243 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:25.084  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.084  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.084  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.084  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.094  3362  3362 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:28:25.094  3593  3593 E Zygote  : MountEmulatedStorage()
,03-17 12:28:25.104  3593  3593 E Zygote  : v2
03-17 12:28:25.104  3593  3593 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:25.104  3593  3593 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.104  3593  3593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.104  1020  1242 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:28:25.104  3593  3593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.104  3593  3593 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.114  1020  1242 I ActivityManager: Killing 1641:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 12:28:25.114  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:25.124  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:25.124  3362  3362 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 12:28:25.124  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:25.124  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:28:25.134  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.134  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.134  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.134  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.134  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:25.134  3362  3362 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 12:28:25.134  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:25.134  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:28:25.134  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:25.134  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:28:25.144  3611  3611 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:25.144  3611  3611 I libpersona: KNOX_SDCARD checking this for 10055
03-17 12:28:25.144  3611  3611 E Zygote  : v2
03-17 12:28:25.144  3611  3611 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.144  3611  3611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.144  3611  3611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:25.144  3611  3611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.154  1020  1242 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3611 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,03-17 12:28:25.154  1020  1565 I ActivityManager: Killing 2619:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 12:28:25.164  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:28:25.164  1020  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-17 12:28:25.164  1020  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 12:28:25.164  3593  3593 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.174  3593  3593 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.174  1020  1045 W libprocessgroup: failed to open /acct/uid_10023/pid_2516/cgroup.procs: No such file or directory
03-17 12:28:25.174  1020  1045 W libprocessgroup: failed to open /acct/uid_10139/pid_2565/cgroup.procs: No such file or directory
03-17 12:28:25.174  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2394/cgroup.procs: No such file or directory
03-17 12:28:25.174  1020  1045 W libprocessgroup: failed to open /acct/uid_10135/pid_2581/cgroup.procs: No such file or directory
,03-17 12:28:25.174  1020  1242 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:25.174  3362  3362 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 12:28:25.184  3611  3611 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.184  3611  3611 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:25.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.184  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.204  3632  3632 E Zygote  : MountEmulatedStorage()
03-17 12:28:25.204  3632  3632 I libpersona: KNOX_SDCARD checking this for 10013
03-17 12:28:25.204  3632  3632 E Zygote  : v2
03-17 12:28:25.204  3632  3632 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.204  3632  3632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.204  3632  3632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.214  3632  3632 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:25.214  1020  1032 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3632 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-17 12:28:25.214  1020  1032 I ActivityManager: Killing 2674:com.android.keychain/1000 (adj 15): empty #31
,03-17 12:28:25.224  3395  3512 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 12:28:25.234  3632  3632 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.234  3632  3632 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.234  1020  3535 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.234  1020  3535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.234  1020  3535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:25.244  3442  3442 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 12:28:25.264  1487  1487 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 12:28:25.264  1487  1487 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 12:28:25.274  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_1641/cgroup.procs: No such file or directory
03-17 12:28:25.274  1020  1045 W libprocessgroup: failed to open /acct/uid_10131/pid_2619/cgroup.procs: No such file or directory
03-17 12:28:25.274  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2674/cgroup.procs: No such file or directory
,03-17 12:28:25.274  1020  1033 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:25.284  3593  3593 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 12:28:25.284  3593  3593 I testFeature: Feature.Feature(context)
03-17 12:28:25.284  3593  3593 I testFeature: Feature.readInternalDefaultXml()
03-17 12:28:25.284  3593  3593 I testFeature: ResetFeatureValue
,03-17 12:28:25.294  3593  3593 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-17 12:28:25.294  3593  3593 I CameraApp: CameraApp.getAppFeature()...
,03-17 12:28:25.294  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.294  3395  3512 I LibraryLoader: Loading: webviewchromium
,03-17 12:28:25.294  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.294  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.294  1020  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.304  3395  3512 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9756-9760)
03-17 12:28:25.304  3395  3512 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:28:25.314  3656  3656 E Zygote  : MountEmulatedStorage()
03-17 12:28:25.314  3656  3656 E Zygote  : v2
03-17 12:28:25.314  3656  3656 I libpersona: KNOX_SDCARD checking this for 10095
03-17 12:28:25.314  3656  3656 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.314  1020  1566 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3656 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 12:28:25.314  1020  1566 I ActivityManager: Killing 2722:com.android.chrome/u0a77 (adj 15): empty #31
,03-17 12:28:25.324  3656  3656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.324  3656  3656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 12:28:25.324  3656  3656 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.334  1317  3243 D ScoverManager: serviceVersion : 16908288
,03-17 12:28:25.334  3395  3513 W GAV2    : Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:28:25.334  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.334  1020  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 12:28:25.334  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 12:28:25.344  3395  3558 I ContactAccountLoggerTas: canRun() : Opted Out
03-17 12:28:25.344  3395  3513 W GAV2    : Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
03-17 12:28:25.344  3395  3558 I ContactAccountLoggerTas: canRun() : Opted Out
03-17 12:28:25.344  3656  3656 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.344  3656  3656 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.344  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.344  1020  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.344  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:25.354  1020  1567 I ActivityManager: Killing 2534:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-17 12:28:25.374  3611  3611 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 12:28:25.374  3395  3512 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:25.384  1020  3535 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.384  1020  3535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.384  1020  3535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:25.384  3632  3632 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 12:28:25.384  1020  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.384  1020  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.384  1020  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 12:28:25.384  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.384  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.384  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:25.394  3316  3666 W MessageQueue: Handler (android.os.Handler) {cb05334} sending message to a Handler on a dead thread
03-17 12:28:25.394  3316  3666 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {cb05334} sending message to a Handler on a dead thread
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:25.394  3316  3666 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:28:25.394  3656  3656 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 12:28:25.394  3632  3676 V OneTimeService: OneTimeService.onHandleIntent
,03-17 12:28:25.414  3395  3513 E File    : fail readDirectory() errno=2
,03-17 12:28:25.414  3656  3656 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 12:28:25.424  1020  1045 W libprocessgroup: failed to open /acct/uid_10077/pid_2722/cgroup.procs: No such file or directory
,03-17 12:28:25.424  1020  1045 W libprocessgroup: failed to open /acct/uid_10039/pid_2534/cgroup.procs: No such file or directory
,03-17 12:28:25.424  3395  3513 I ContactLabelSupplier: get() : OptedIn = false
,03-17 12:28:25.424  1953  1953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:25.424  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.424  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:25.424  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 12:28:25.434  1953  1953 D SecUISvc: Service started flags 0 startId 1
,03-17 12:28:25.434  1953  3681 D SecUISvc: Thread created.
,03-17 12:28:25.434  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.434  3611  3611 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 12:28:25.434  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.434  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.434  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.444  3611  3611 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 12:28:25.444  3611  3611 D UserAnalysis: Create SecureDbHelper
,03-17 12:28:25.454  3683  3683 E Zygote  : MountEmulatedStorage()
,03-17 12:28:25.454  3683  3683 E Zygote  : v2
03-17 12:28:25.454  3683  3683 I libpersona: KNOX_SDCARD checking this for 10026
03-17 12:28:25.454  3683  3683 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.454  3683  3683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.454  3683  3683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.454  1020  1242 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3683 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:25.454  3683  3683 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.464  3656  3656 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 12:28:25.464  3656  3656 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 12:28:25.474  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.474  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.474  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.474  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.484  3698  3698 E Zygote  : MountEmulatedStorage(),
03-17 12:28:25.484  3698  3698 I libpersona: KNOX_SDCARD checking this for 10098
03-17 12:28:25.484  3698  3698 E Zygote  : v2
03-17 12:28:25.484  3698  3698 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.484  3698  3698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 12:28:25.494  3698  3698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:25.494  3698  3698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:25.494  3683  3683 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:25.494  3683  3683 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.494  1020  1565 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3698 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 12:28:25.504  1020  1567 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.504  1020  1567 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.504  1020  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.504  3611  3611 D IntelligenceServiceApplication: onCreate()
03-17 12:28:25.504  3611  3611 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 12:28:25.514  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.514  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.514  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.514  1020  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.514  3698  3698 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.514  3698  3698 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.524  3316  3653 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,03-17 12:28:25.524  3316  3653 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 12:28:25.524  3316  3653 I System.out: Thread-475(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:28:25.524  3316  3653 I System.out: Thread-475(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:28:25.524  3316  3653 I System.out: Thread-475(ApacheHTTPLog):isShipBuild true
03-17 12:28:25.524  3316  3653 I System.out: Thread-475(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:28:25.524  3316  3653 I System.out: Thread-475(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:28:25.534  3714  3714 E Zygote  : MountEmulatedStorage(),
03-17 12:28:25.534  3714  3714 E Zygote  : v2
03-17 12:28:25.534  3714  3714 I libpersona: KNOX_SDCARD checking this for 10056
03-17 12:28:25.534   280  1014 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 12:28:25.534  3714  3714 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.534   280  1014 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 12:28:25.534  3714  3714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.534  3714  3714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.534  3714  3714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 12:28:25.534  1020  1565 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3714 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:28:25.534  1020  1565 I ActivityManager: Killing 2794:com.android.email/u0a141 (adj 15): empty #31
,03-17 12:28:25.554  1020  3535 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.554  1020  3535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.554  1020  3535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.554  3611  3611 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 12:28:25.564  1020  3516 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.564  1020  3516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 12:28:25.564  1020  3516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.564   307   307 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 27.017ms
,03-17 12:28:25.574  1020  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.574  1020  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.574  1020  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.574  3611  3611 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 12:28:25.584  3714  3714 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.584  3714  3714 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.584   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.447ms
,03-17 12:28:25.594  3395  3513 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 12:28:25.594  3395  3558 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 12:28:25.594  1020  1502 I ActivityManager: Killing 1625:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-17 12:28:25.604   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 18.485ms
,03-17 12:28:25.614  1020  3451 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.614  1020  3451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.614  1020  3451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.624  1020  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.624  1020  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:25.624  1020  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:25.624  1602  1602 I Hs20UtilService: Starting #7
,03-17 12:28:25.624  1602  1647 I Hs20UtilService: Message received 5003
,03-17 12:28:25.624  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.624  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.624  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.624  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.634  3736  3736 E Zygote  : MountEmulatedStorage()
03-17 12:28:25.634  3736  3736 E Zygote  : v2
03-17 12:28:25.634  3736  3736 I libpersona: KNOX_SDCARD checking this for 10018
03-17 12:28:25.634  3736  3736 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.634  3698  3698 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 12:28:25.644  3698  3698 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
03-17 12:28:25.644  1020  1242 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3736 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:25.654  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.654  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.654  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.654  1020  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.664  3736  3736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.664  3736  3736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.664  3744  3744 E Zygote  : MountEmulatedStorage()
03-17 12:28:25.664  3744  3744 I libpersona: KNOX_SDCARD checking this for 10099
03-17 12:28:25.664  3744  3744 E Zygote  : v2
03-17 12:28:25.664  3744  3744 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.664  3736  3736 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.664  3744  3744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.674  3744  3744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:28:25.674  1020  1045 W libprocessgroup: failed to open /acct/uid_10141/pid_2794/cgroup.procs: No such file or directory
03-17 12:28:25.674  1020  1045 W libprocessgroup: failed to open /acct/uid_10068/pid_1625/cgroup.procs: No such file or directory
,03-17 12:28:25.674  3744  3744 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.674  1020  1242 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3744 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:25.684   290   290 E SMD     : DCD OFF
,03-17 12:28:25.684  3611  3611 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 12:28:25.684  3611  3611 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
03-17 12:28:25.684  3736  3736 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.684  3736  3736 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.704  3744  3744 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.704  3744  3744 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.734  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.734  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.734  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 12:28:25.734  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:25.734  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:25.744  1317  3243 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 12:28:25.784  1317  3243 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 12:28:25.794  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:25.794  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:25.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:25.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:25.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:25.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:25.794  3268  3325 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-17 12:28:25.794  1020  3516 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:25.794  1020  3516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.794  1020  3516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:25.824  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.824  3463  3463 I RlzPingService: Setting next ping for 1458818905831
03-17 12:28:25.824  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:25.824  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 12:28:25.834  1020  1033 I ActivityManager: Killing 2918:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 12:28:25.834  1020  1033 I ActivityManager: Killing 2871:com.mobeam.barcodeService/1000 (adj 15): empty #32
,03-17 12:28:25.854  3736  3736 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:28:25 GMT+01:00 2016
,03-17 12:28:25.854  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:25.854  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:25.854  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:28:25.864  3736  3736 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:28:25.864  3683  3683 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 12:28:25.864  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.864  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.864  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.864  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.874  3736  3736 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 12:28:25.874  3736  3736 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:28:25.884  3776  3776 E Zygote  : MountEmulatedStorage()
03-17 12:28:25.884  3776  3776 E Zygote  : v2
03-17 12:28:25.884  3776  3776 I libpersona: KNOX_SDCARD checking this for 10020
03-17 12:28:25.884  3776  3776 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.884  3776  3776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:25.884  3776  3776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:25.884  1020  1033 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3776 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 12:28:25.884  3776  3776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.884  3736  3736 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:28:25.894  3736  3775 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 12:28:25.904  1317  3243 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 12:28:25.904  1317  3243 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
03-17 12:28:25.904  3736  3775 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-17 12:28:25.914  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2871/cgroup.procs: No such file or directory
,03-17 12:28:25.914  1020  1045 W libprocessgroup: failed to open /acct/uid_10097/pid_2918/cgroup.procs: No such file or directory
,03-17 12:28:25.914  3776  3776 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.914  3776  3776 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.984  1020  3516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.984  1020  3516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.984  1020  3516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.984  1020  3516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.004  3799  3799 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.004  3799  3799 E Zygote  : v2
,03-17 12:28:26.004  3799  3799 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:26.004  3799  3799 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.004  3799  3799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:26.004  3799  3799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:28:26.004  1020  3516 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:26.004  3799  3799 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:26.004  1020  3516 I ActivityManager: Killing 2951:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 12:28:26.034  3316  3653 I System.out: Thread-475 calls detatch()
,03-17 12:28:26.054  3736  3736 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 12:28:26.054   280  1014 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 12:28:26.054   280  1014 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-17 12:28:26.054  3799  3799 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.054  3799  3799 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.074  3299  3533 I System.out: pool-10-thread-1 calls detatch()
,03-17 12:28:26.104  3799  3799 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 12:28:26.104  1020  1301 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 12:28:26.104  1020  1301 D SecContentProvider2: mCursor = null
,03-17 12:28:26.104  1020  1129 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 12:28:26.104  1020  1129 D SecContentProvider2: mCursor = null
,03-17 12:28:26.114  3799  3799 V MTPRx   : sealedState: false,
03-17 12:28:26.114  3799  3799 V MTPRx   : sealedUsbMassStorageState: false
,03-17 12:28:26.114  3395  3512 I qtaguid : Tagging socket 28 with tag 100000000{1,0} for uid -1, pid: 3395, getuid(): 10052
,03-17 12:28:26.114  1020  1242 D SettingsProvider: name = mtp_usb_connection_status
,03-17 12:28:26.134  3714  3714 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 12:28:26.144  3683  3683 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 12:28:26.154  1020  1129 I ActivityManager: Killing 2296:flipboard.app/u0a96 (adj 15): empty #31
,03-17 12:28:26.154  1020  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:26.154  1020  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:28:26.154  1020  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 12:28:26.164  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.164  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.164  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.164  1020  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.164  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:26.184  1924  1924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:26.184  3830  3830 E Zygote  : MountEmulatedStorage()
03-17 12:28:26.184  3830  3830 E Zygote  : v2
03-17 12:28:26.184  3830  3830 I libpersona: KNOX_SDCARD checking this for 10058
03-17 12:28:26.184  3830  3830 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.184  3683  3828 E SQLiteLog: (28) failed to open "/data/data/com.android.vending/databases/library.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 12:28:26.184  3830  3830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:28:26.184  3683  3683 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:28:26.184  3683  3683 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:28:26.184  3830  3830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:28:26.194  3830  3830 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:26.194  1020  1567 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3830 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:26.194  1020  1567 I ActivityManager: Killing 3008:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 12:28:26.194  1020  1045 W libprocessgroup: failed to open /acct/uid_1101/pid_2951/cgroup.procs: No such file or directory
,03-17 12:28:26.224  3830  3830 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.224  3830  3830 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.224  3683  3843 E SQLiteLog: (28) failed to open "/data/data/com.android.vending/databases/localappstate.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 12:28:26.234  3683  3828 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at com.google.android.finsky.g.av.iterator(SourceFile:15308)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at com.google.android.finsky.g.w.run(SourceFile:1078)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:26.234  3683  3828 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:28:26.234  3683  3843 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at com.google.android.finsky.b.x.a(SourceFile:2298)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at com.google.android.finsky.b.z.c(SourceFile:55)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at com.google.android.finsky.receivers.j.doInBackground(SourceFile:3083)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:28:26.234  3683  3843 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 12:28:26.244  3683  3843 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #1
03-17 12:28:26.244  3683  3843 E AndroidRuntime: Process: com.android.vending, PID: 3683
03-17 12:28:26.244  3683  3843 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at com.google.android.finsky.b.x.a(SourceFile:2298)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at com.google.android.finsky.b.z.c(SourceFile:55)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at com.google.android.finsky.receivers.j.doInBackground(SourceFile:3083)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:28:26.244  3683  3843 E AndroidRuntime: 	... 4 more
,03-17 12:28:26.244  1020  1502 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found

```
