#### Test 5563415007e42e9_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
,V/IccIntentReceiver( 1683): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
--------- beginning of system
I/ActivityManager(  951): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=3124 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  951): killProcessQuiet, pid=2562
I/ActivityManager(  951): Killing 2562:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/htcbackup-core( 3124): ModelRegistry: Loading model meta data from resources...
E/cutils-trace( 3145): Error opening trace file: Permission denied (13)
I/ActivityManager(  951): Recipient 2562
D/CustomizationManager( 3145): ====startRecUseTime====
D/htc.customization.log.level( 3145):  is 
W/CustomizationLogLevel( 3145): Level value is invalid, use default level 2
I/htcbackup-core( 3124): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
I/htcbackup-core( 3124): SuperSaverModeReceiver: going to send resume event
I/ActivityManager(  951): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=3165 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/BluetoothManagerService(  951): Auto-enabling Bluetooth.
D/BluetoothManagerService(  951): checking for enable restriction...
D/BluetoothManagerService(  951): checkBTEasState, ret=true
I/BluetoothManagerService(  951): isBluetoothRestricted(): false
D/BluetoothManagerService(  951): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  951): MESSAGE_ENABLE: mBluetooth = null
I/htcbackup-core( 3124): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 3124): BackupRestoreManager: resume
I/ActivityManager(  951): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3185 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
D/PMS     (  951): acquireWL(20e907fe): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
D/UsbDeviceManager(  951): boot completed
D/UsbDeviceManager(  951): [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
V/SystemUIService( 1219): BOOT_COMPLETED received
D/UsbDeviceManager(  951): [USBNET] update2: 105,0
D/UsbDeviceManager(  951): sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
I/ActivityManager(  951): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3210 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/UsbDeviceManager(  951): [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/Tethering(  951): got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
D/UsbnetService(  951): onReceive ACTION_USB_STATE: true,false
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  951): [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
I/art     (  404): Explicit concurrent mark sweep GC freed 8617(365KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 20.471ms
D/CustomizationManager( 3145):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__102
D/MountService(  951): sharing = 0 
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__Y13
D/MountService(  951): Unmount PCTOOL.ISO
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__032
D/VoldConnector(  951): SND -> {10 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__M27
D/PMS     (  951): acquireWL(2267e4f1): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 951 1000 WorkSource{10024}
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__002
D/MountService(  951): unmountISO --
D/CIDMapFileReader( 3145): Parsing tag item name = HTC__031
W/ResourcesManager( 3185): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
V/CustomizationCIDLoader( 3145): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 3145): Parsing tag category name = system
I/CustomizationCIDLoader( 3145): Parsing tag category name = application
I/CustomizationCIDLoader( 3145): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3145): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3145): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3145): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3145): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3145): add string-array item, value = 42507
I/CustomizationCIDLoader( 3145): add string-array item, value = 21902
I/CustomizationCIDLoader( 3145): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3145): add string-array item, value = 23420
I/CustomizationCIDLoader( 3145): add string-array item, value = 22299
I/CustomizationCIDLoader( 3145): add string-array item, value = 24002
I/CustomizationCIDLoader( 3145): add string-array item, value = 23210
I/CustomizationCIDLoader( 3145): add string-array item, value = 23205
I/CustomizationCIDLoader( 3145): add string-array item, value = 23806
I/CustomizationCIDLoader( 3145): add string-array item, value = 23430
I/CustomizationCIDLoader( 3145): add string-array item, value = 23408
I/CustomizationCIDLoader( 3145): add string-array item, value = 27205
I/CustomizationCIDLoader( 3145): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3145): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3145):  Read CID file spent 0.115 (s)
D/CustomizationManager( 3145):  All configurations done spent 0.115 (s)
I/RecoverySystem(  951): No recovery log file
W/ResourcesManager(  951): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 229us total 31.921ms
I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 129us total 15.883ms
I/ActivityManager(  951): Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3239 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
I/ActivityManager(  951): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3145 on display 0
D/PMS     (  951): acquireHCC(39e07a4f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 951 1000 null
D/PMS     (  951): acquireHCC(31f255dc): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 951 1000 null
D/PMS     (  951): acquireWL(1ad46c6b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 951 1000 null
I/FeedHostManager( 1483): [onPause]
D/PMS     (  951): releaseWL(20e907fe): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/FeedProviderManager( 1483): onPause
D/PMS     (  951): acquireWL(19118474): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
I/AnimationUtil(  951): isHTCRecent(HelloWorld/Recent screens.)/5
D/PMS     (  951): releaseWL(19118474): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/FeedHostManager( 1483): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1b819571
D/PMS     (  951): acquireWL(1f213212): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
I/SocialFeedProvider( 1483): +onPause
I/SocialFeedProvider( 1483): -onPause
D/PMS     (  951): releaseWL(1f213212): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  951): acquireWL(2a4ffde3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
D/PMS     (  951): releaseWL(2a4ffde3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  951): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3261 uid=10374 gids={50374, 9997, 3003} abi=arm64-v8a
I/BootReceiver(  951): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
W/ResourcesManager( 3239): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 3239): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/art     ( 2175): Suspending all threads took: 6.452ms
I/art     ( 2175): Background sticky concurrent mark sweep GC freed 42(3KB) AllocSpace objects, 0(0B) LOS objects, 2% free, 4MB/4MB, paused 10.216ms total 23.403ms
I/BootReceiver(  951): Copying audit failures to DropBox
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  951): Copied 0 worth of audits to DropBox
I/BootReceiver(  951): Checking for fsck errors
I/BootReceiver(  951): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  951): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/AdapterServiceConfig( 3185): Adding HeadsetService,
D/AdapterServiceConfig( 3185): Adding A2dpService
D/AdapterServiceConfig( 3185): Adding HidService
I/ActivityManager(  951): Killing 2540:com.htc.sense.socialplugins/u0a21 (adj 15): empty #17
D/AdapterServiceConfig( 3185): Adding HealthService
I/BootReceiver(  951): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
D/AdapterServiceConfig( 3185): Adding PanService
D/AdapterServiceConfig( 3185): Adding GattService
D/Process (  951): killProcessQuiet, pid=2540
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/StatusBarManagerService(  951): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  951): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  951): hiding MENU key
I/DeviceManagement( 3165): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3165 dbg=false s=true
I/TrimMemoryManager( 1483): [trimMemory] 20
W/linker  ( 3185): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:2040] from screen [on:0 period:828866623] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828866624] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
W/System.err(  951): java.lang.Throwable: stack dump
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  951): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  951): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  951): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  951): 	at android.os.Binder.execTransact(Binder.java:454)
I/BootReceiver(  951): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@123e9bc5:true
D/BluetoothAdapterState( 3185): make
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BluetoothAdapterState( 3185): Entering OffState
I/wpa_supplicant( 1362): environment dirty rate=17 [17][3][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/bt_osi_config( 3185): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.09 txretriesrate=0.00 rxrate=11.19 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
D/BluetoothAdapterProperties( 3185): Address is:90:E7:C4:F6:69:77
I/BootReceiver(  951): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  951): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/ActivityManager(  951): Recipient 2540
I/BootReceiver(  951): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  951): Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
I/BootReceiver(  951): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/DeviceManagement( 3165): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 3165): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=22 rxSum=16} preTxRxSum={txSum=8 rxSum=5}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  951): handleMessage: X
I/DeviceManagement( 3165): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/[FDDMI]BootCompletedReceiver( 3239): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=36
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/BluetoothManagerService(  951): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  951): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  951): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/DeviceManagement( 3165): WorkflowService: Starting workflow service
I/art     ( 2175): Background sticky concurrent mark sweep GC freed 60(7KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 6.040ms total 32.149ms
D/BluetoothManagerService(  951): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  951): Broadcasting onBluetoothServiceUp() to 6 receivers.
D/BluetoothAdapter( 1219): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@13b4b96d
D/BluetoothAdapter( 1219): onBluetoothServiceUp done
D/BluetoothAdapter( 1447): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@ef539c8
D/BluetoothAdapter( 1447): onBluetoothServiceUp done
D/BluetoothAdapter( 1431): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@11ca8e10
D/BluetoothAdapter( 1431): onBluetoothServiceUp done
I/DeviceManagement( 3165): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3cae8ff3] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3165): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
D/BluetoothAdapter( 3185): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@3cae8ff3
D/BluetoothAdapter( 3185): onBluetoothServiceUp done
D/BluetoothAdapter(  951): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@104a1ce6
D/BluetoothAdapter(  951): onBluetoothServiceUp done
D/BluetoothAdapter( 2356): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@20f41bd
D/BluetoothAdapter( 2356): onBluetoothServiceUp done
D/BluetoothManagerService(  951): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3185): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3185): Setting state to 11
I/BluetoothAdapterState( 3185): Bluetooth adapter state changed: 10-> 11
D/OtaStartupReceiver( 1431): onReceive: android.intent.action.BOOT_COMPLETED
D/BluetoothManagerService(  951): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  951): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BootReceiver(  951): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
D/BluetoothManagerService(  951): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  951): Bluetooth State Change Intent: 10 -> 11
E/SharedPreferencesImpl(  951): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/WebViewFactory( 3261): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/DeviceManagement( 3165): ModelRegistry: Loading model meta data from resources...
D/BluetoothBondStateMachine( 3185): make
W/HtcActiveEngineManager(  951): Can't find out the target sensor
I/IntentController( 1219): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
E/WifiStateMachine(  951): handleMessage: E msg.what=131206
V/BluetoothPbapReceiver( 3185): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine(  951): processMsg: ConnectedState
V/BluetoothPbapReceiver( 3185): ***********state = 11
I/BluetoothBondStateMachine( 3185): StableState(): Entering Off State
D/BluetoothAdapterService( 3185): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 3185): checkA2dpState: returning
D/BluetoothAdapterService( 3185): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 3185): checkHfpState: returning
E/WifiStateMachine(  951):  ConnectedState !CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !CMD_BOOT_COMPLETED 0 0
D/ConnectivityService(  951): Got NetworkFactory Messenger for WIFI
E/WifiStateMachine(  951): processMsg: DefaultState
D/ConnectivityService(  951): NetworkFactory connected
E/WifiStateMachine(  951):  DefaultState !CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  951): handleMessage: X
D/WIFI    (  951): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    (  951):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/WIFI    (  951): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/UsbnetService(  951): UsbnetHandler::handleMessage+:4
D/UsbnetService(  951): MESSAGE_BOOT_COMPLETED+
D/UsbnetService(  951): systemReady+
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
D/UsbnetService(  951): systemReady-
D/WifiService(  951): updateDevicePolicy Exchange policy allowWifiStatus = 1
D/WifiService(  951): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
D/UsbnetService(  951): UsbnetHandler::handleMessage-
D/ConnectivityService(  951): Got NetworkFactory Messenger for usbnet
D/ConnectivityService(  951): NetworkFactory connected
D/usbnet  (  951): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/usbnet  (  951):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  951): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
I/LibraryLoader( 3261): Time to load native libraries: 13 ms (timestamps 8636-8649)
I/LibraryLoader( 3261): Expected native library version number "",actual native library version number ""
I/DeviceManagement( 3165): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3165): SessionStateController: Checking invariants...
I/ActivityManager(  951): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3300 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
D/BluetoothHeadset(  951): Proxy object connected
D/BluetoothHeadset( 1431): Proxy object connected
D/HeadsetService( 3185): Received start request. Starting profile...
D/BluetoothHeadset( 1431): Proxy object connected
D/BluetoothHeadset( 1431): Proxy object connected
D/BluetoothPhoneService( 1431): BluetoothHeadset onServiceConnected
D/HeadsetStateMachine( 3185): Version 1.5
D/HeadsetStateMachine( 3185): make
D/BluetoothAdapter( 1431): 1065745166: getState(). Returning 11
D/BluetoothAdapter(  951): 521759946: getState(). Returning 11
V/WebViewChromiumFactoryProvider( 3261): Binding Chromium to main looper Looper (main, tid 1) {3edb4ed6}
I/LibraryLoader( 3261): Expected native library version number "",actual native library version number ""
I/ActivityManager(  951): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3321 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
I/chromium( 3261): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BluetoothAdapterState( 3185): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/QuickSettingBluetooth( 1219): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/BluetoothHeadset( 1219): Proxy object connected
I/QuickSettingMiniLite( 1219): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@bc059a2
I/BrowserStartupController( 3261): Initializing chromium process, singleProcess=true
W/art     ( 3261): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3261): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  951): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3338 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
I/ActivityManager(  951): Killing 2474:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2474
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/chromium( 3261): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3261): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3261): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3261): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3261): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3261): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3261): Local Branch: 
I/Adreno-EGL( 3261): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3261): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3261):                  d74aa161a12b9c6fc6332151
W/AudioManagerAndroid( 3261): Requires BLUETOOTH permission
D/BluetoothAdapter( 1219): 34554301: getState(). Returning 11
I/QuickSettingMiniLite( 1219): updateLiteState:no connect device!
I/ActivityManager(  951): Recipient 2474
D/HeadsetStateMachine( 3185): max_hf_connections = 2
D/HeadsetPhoneState( 3185): listenForPhoneState..for service and signal 
D/HeadsetDualPhoneStateListener_SLOT1( 3185): listen phone state by slot:SLOT1  id:-1
D/HeadsetDualPhoneStateListener_SLOT2( 3185): listen phone state by slot:SLOT2  id:-100
D/HeadsetStateMachine( 3185): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/UsbReceiver( 3300): onReceiver android.intent.action.BOOT_COMPLETED
D/HeadsetDualPhoneStateListener_SLOT1( 3185): listen phone state by slot:SLOT1  id:-1
D/HtcModeClient( 3300): power connected, start service
D/A2dpService( 3185): Received start request. Starting profile...
D/BluetoothA2dp(  951): Proxy object connected
V/Avrcp   ( 3185): make
D/HtcBtWidget_BTWidgetProvider( 3321): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3321): updateWidget(context) for widget: 
D/BluetoothAdapter(  951): 521759946: getState(). Returning 11
D/HeadsetDualPhoneStateListener_SLOT2( 3185): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 3185): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 3185): BTHF: set_current_device
D/Utils   ( 3300): CMD:getprop ro.htc.htcmode.socket.type
W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
I/System  ( 3300): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
I/ActivityManager(  951): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3384 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/DeviceManagement( 3165): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
E/RemoteController( 3185): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 3185): make
I/ActivityManager(  951): Killing 2716:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2716
D/bt-btif ( 3185): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
D/DotMatrix( 2147): [CoverService] onDestroy, version: 1.3
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/A2dpService( 3185): setA2dpService(): set to: null
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/A2dpStateMachine( 3185): Enter Disconnected: -2
D/HidService( 3185): Received start request. Starting profile...
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/HtcModeClient( 3300): sSocketMode = LocalSocket
D/HealthService( 3185): Received start request. Starting profile...
D/HtcModeClient( 3300): start the htcmodeservice thread
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/HtcModeClient( 3300): initCanAgent
I/CANMesgAgentLocalSocket( 3300): CANAgent Id = 0
D/PanService( 3185): Received start request. Starting profile...
D/PanService( 3185): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/HtcModeClient( 3300): sense info: version = none, id = 2
D/HtcModeClient( 3300): display info: width = 1080, height = 1776
D/HtcModeClient( 3300): display info: mode = 10
D/BtGatt.DebugUtils( 3185): handleDebugAction() action=null
D/BtGatt.GattService( 3185): Received start request. Starting profile...
D/BtGatt.GattService( 3185): start()
D/BtGatt.AdvertiseManager( 3185): advertise manager created
W/art     ( 3261): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3261): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3261): CordovaWebView is running on device made by: HTC
I/ActivityManager(  951): Recipient 2716
W/art     ( 3261): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3261): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 3165): SessionStateController: Checking invariants...
D/HtcModeClient( 3300): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
D/HtcModeClient( 3300): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 3300): connectState: CONNECTION_READY = false
D/HtcModeClient( 3300): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3300): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3300): connectState: PHONE_PULGIN = false
D/HtcModeClient( 3300): connectState: Force_AWAKE = false
D/HtcModeClient( 3300): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3300): connectState: POWERCONNECTED_READY = true
D/BluetoothAdapterService( 3185): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e9f557
D/MediaProvider( 3338): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 3338): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3338): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3338): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3338): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3338): [MP][DEBUG] Storage State: removed
I/SensorManager( 2147): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@1e610c7b
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): disable: get sensor name = CM36686 Proximity sensor
D/BluetoothAdapter( 1431): 1065745166: getState(). Returning 11
W/BluetoothHeadset( 1431): Proxy not attached to service
D/BluetoothHeadset( 1431): java.lang.Throwable
D/BluetoothHeadset( 1431): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1431): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1431): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1431): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1431): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1431): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1431): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1431): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1431): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1431): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1431): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  951): pid=2147, uid=10041
W/SensorService(  951): Active sensors: size = 3
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@1e610c7b, eanble = 0, strlen(mName) = 41
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  951): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@25cb1b39
W/SensorService(  951): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f2ebf50
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2147): [CoverService] unregisterCallContentObserver()
D/Process (  951): killProcessQuiet, pid=2147
I/ActivityManager(  951): Killing 2147:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/HeadsetPhoneState( 3185): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 3185): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 3185): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3185): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3185): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3185): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 3185): btu_task pending for preload complete event
E/bt_vendor( 3185): get_bt_soc_type: Failed to get soc type
E/SQLiteLog( 3338): (283) recovered 44 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
D/Atlas   ( 3261): Validating map...
I/qcom-bluetooth( 3432): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
I/qcom-bluetooth( 3439): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/DeviceManagement( 3165): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/qcom-bluetooth( 3440): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/DeviceManagement( 3165): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3cae8ff3]
I/qcom-bluetooth( 3442): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 3443): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 3444): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 3445): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager(  951): Recipient 2147
I/DeviceManagement( 3165): WorkflowService: Stopping workflow service
W/ContextImpl( 3384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/chromium( 3261): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Process (  951): killProcessQuiet, pid=2973
I/ActivityManager(  951): Killing 2973:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/htcbackup-core( 3124): BackupRestoreManager: Storage is not configured
D/BluetoothMasReceiver( 3185): Bluetooth STATE CHANGED to 11
E/htcbackup-core( 3124): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=36
E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/FindExtension( 3261): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  951): Recipient 2973
E/BlobCache( 3261): unflatten: not enough room for cache entry headers
E/libEGL  ( 3261): error reading cache contents: Invalid argument (22)
I/InputMethodManager( 3261): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@7082a74, mServedView=org.apache.cordova.engine.SystemWebView{5219b9d VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@25274812
I/ActivityManager(  951): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3455 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/PMS     (  951): acquireWL(3dc5b2c): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10074}
V/AlarmManager(  951): sending alarm PendingIntent{38a269f5: PendingIntentRecord{1edf38a com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1452510000000, Int=86400000
V/AlarmManager(  951): sending alarm PendingIntent{3940edfb: PendingIntentRecord{3449fe18 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=39560, Int=0
I/InputMethodManagerService(  951): Disable input method client, pid=1483
D/StatusBarManagerService(  951): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  951): Displayed com.example.hello/.MainActivity: +1s437ms
I/InputMethodManagerService(  951): Enable input method client, pid=3261
V/BluetoothSapReceiver( 3185): SapReceiver onReceive 
V/BluetoothSapReceiver( 3185): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3185):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 3185): startService = false
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/PowerSaverNotificationService( 3384): updateNotification, mToggle = false
D/AuthorizationBluetoothService( 1908): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Process (  951): killProcessQuiet, pid=2996
I/ActivityManager(  951): Killing 2996:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/XT9_C   ( 1381): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1381): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 3261): Cannot call determinedVisibility() - never saw a connection for the pid: 3261
I/chromium( 3261): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/qcom-bluetooth( 3480): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
I/ActivityManager(  951): Recipient 2996
I/qcom-bluetooth( 3482): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
W/System.err( 3124): Starting the HTTP client
W/htcbackup-core( 3124): BackupServiceClientResourceProxy: Reseting appServerErrorCount
I/bt-btu  ( 3185): btu_task received preload complete event
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x1487
D/PMS     (  951): acquireWL(27dae2ad): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3185 1002 null
D/bt-btm  ( 3185): btm_acl_device_down
D/bt-btm  ( 3185): btm_acl_reset_paging
D/bt-btm  ( 3185): btm_acl_set_discing
D/JsMessageQueue( 3261): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3261): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/bt-btm  ( 3185): btm_reset_complete
I/bt-btm  ( 3185): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
D/bt-btm  ( 3185): Start reading local supported commands
D/bt-btm  ( 3185): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 3185): BTM reads next extended features page (1)
D/bt-btm  ( 3185): BTM reads next extended features page (2)
D/bt-btm  ( 3185): BTM reached last extended features page (2)
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 3185): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 3185): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3185): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 3185): btm_read_ble_wl_size 
D/bt-btm  ( 3185): btm_read_white_list_size_complete 
D/bt-btm  ( 3185): btm_get_ble_buffer_size 
D/bt-btm  ( 3185): btm_read_ble_buf_size_complete 
D/bt-btm  ( 3185): btm_read_ble_local_supported_states 
D/bt-btm  ( 3185): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 3185): btm_read_ble_local_supported_features 
D/bt-btm  ( 3185): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3185): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3185): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3185): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3185): Local supported SCO packet types: 0x038f
I/bt-btm  ( 3185): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3185): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3185): BTM_SetInquiryMode
I/bt-btm  ( 3185): BTM_SetPageScanType
I/bt-btm  ( 3185): BTM_SetInquiryScanType
D/bt-btm  ( 3185): btm_decode_ext_features_page page: 1
W/bt-btm  ( 3185): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 3185): btm_decode_ext_features_page page: 2
W/bt-btm  ( 3185): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 3185): BTM_BleLoadLocalKeys
D/bt-btm  ( 3185): BTM_BleLoadLocalKeys
I/bt-btm  ( 3185): BTM_Sec: application registered
E/bt-btm  ( 3185): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf9494d5 
I/bt-btm  ( 3185): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3185): SMP_Register state=0
E/bt-btm  ( 3185): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf9494d5 
I/bt-btm  ( 3185): BTM_Sec: application registered
D/bt-btm  ( 3185): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3185): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3185): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3185): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3185): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3185): BTM_RegBusyLevelNotif
D/bt-btm  ( 3185): BTM_BleReadControllerFeatures
I/bt-btm  ( 3185): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 3185): GATT_Register
D/bt-att  ( 3185): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3185): allocated gatt_if=3
I/bt-att  ( 3185): GATT_StartIf gatt_if=3
D/bt-att  ( 3185): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3185): gatt_find_the_connected_bda found=0 found_idx=16
D/bt-btm  ( 3185): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 3185): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 3185): BTM Register For VSEvents is successfully
D/bt-btm  ( 3185): BTM_BleGetVendorCapabilities
I/bt-btif ( 3185): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3185): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 3185): Calling BTA_HhEnable
E/bt-btif ( 3185): Calling BTA_HhEnable
I/bt-btif ( 3185): BTA_MceEnable
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185):  BTM_BleConfigPrivacy
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): btm_gen_resolvable_private_addr
I/bt-btm  ( 3185): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 3185): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3185): BTM_AllocateSCN
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3185): btif_storage_ge
E/bt-btif ( 3185): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 3185): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3185):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3185):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 3185): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 3185): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3185):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3185):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 3185): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
D/BluetoothAdapterProperties( 3185): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 3185): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3185): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3185): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
D/bt-btif ( 3185):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3185): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3185):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3185):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3185):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 3185): GATT_Register
D/bt-att  ( 3185): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3185): allocated gatt_if=4
I/bt-att  ( 3185): GATT_StartIf gatt_if=4
D/bt-att  ( 3185): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3185): gatt_find_the_connected_bda found=0 found_idx=16
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_gen_resolve_paddr_low
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 9a 47 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 3d 44 7c 51 2f 0e 2a f3 ce cf 97 86 e7 55 18 41 
I/bt-btm  ( 3185): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3185): Stopping oneshot timer
D/bt-btm  ( 3185): Starting oneshot timer type:103 timeout:900s
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 22 88 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 14 b4 19 35 ed ce 6c 41 fc 9e 20 d6 07 d0 0f b3 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 07 93 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = cc 1d 64 32 22 5b 62 0e 2a 3b d6 12 ff 1a 63 62 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 13 0d 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = b4 53 ac 5d f8 c3 d0 19 9e 1f 1d 17 9d 65 29 d6 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 38 d9 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 09 66 15 90 83 cc 77 29 84 24 6c db a3 56 62 fc 
D/Process (  951): killProcessQuiet, pid=3018
I/ActivityManager(  951): Killing 3018:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = c6 77 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 98 93 fe dd d0 0b 4f 29 b9 91 1a 65 3a 4b 16 e2 
W/htcbackup-core( 3124): BackupRestoreManager: No sense account found - aborting
I/htcbackup-core( 3124): BackupRestoreManager: DM is not ready, pending resume
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
W/ResourcesManager( 3455): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = f0 8c 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 1f 53 6e aa ee 97 85 60 62 dc 19 ae be ff 1a 8b 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = ae 80 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 7e 5c d9 f8 f7 14 41 0e 77 fc 0b fc cc 22 ff f3 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = 36 62 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = a6 20 35 df 92 18 a3 4d cd 3d ec 91 b3 c3 43 d8 
D/bt-btm  ( 3185): btm_ble_rand_enc_complete
I/bt-btm  ( 3185): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3185): smp_encrypt_data
W/bt-smp  ( 3185): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3185): Plain text(LSB ~ MSB) = d7 d0 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3185): Encrypted text(LSB ~ MSB) = 95 5b 9e 9c ea a2 88 fb 86 fb 79 62 4d 38 e7 2d 
I/ActivityManager(  951): Recipient 3018
,D/BluetoothAdapterProperties( 3185): Scan Mode:21,
,D/BluetoothAdapterProperties( 3185): Discoverable Timeout:120
I/bt-btif ( 3185): BTA_JvEnable
D/PMS     (  951): releaseWL(1ad46c6b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/bt-btif ( 3185): BTA_JvRegisterL2cCback
I/bt-btm  ( 3185): BTM_ReadConnectability
I/bt-btm  ( 3185): BTM_ReadDiscoverability
I/bt-btm  ( 3185): BTM_SetDiscoverability
I/bt-btm  ( 3185): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3185): disc_mode 0002
D/bt-btm  ( 3185): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 3185): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 3185): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3185): BTM_SetConnectability
I/bt-btm  ( 3185): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3185): disc_mode 0002
I/bt-btm  ( 3185): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 3185): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 3185): BTM_SetDiscoverability
I/bt-btm  ( 3185): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3185): disc_mode 0000
I/bt-btm  ( 3185): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3185): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3185): BTM_SetConnectability
I/bt-btm  ( 3185): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3185): disc_mode 0000
D/bt-btm  ( 3185): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3185): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3185): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3185): bta_pan_co_init
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3185): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3185):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3185):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3185):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3185): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3185):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
E/bt_mct  ( 3185): hci lib postload completed
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 3185): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 3185): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 3185): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 3185): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 3185): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 3185): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3185): ScanMode =  21
D/BluetoothAdapterProperties( 3185): State =  11
D/BluetoothAdapterProperties( 3185): Setting state to 12
,I/BluetoothAdapterState( 3185): Bluetooth adapter state changed: 11-> 12
I/bt-btif ( 3185): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3185): Discoverable Timeout:120
D/BluetoothManagerService(  951): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  951): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  951): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  951): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 3185): Entering On State
D/BluetoothHeadset( 1431): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1431): onBluetoothStateChange: up=true
I/ActivityManager(  951): Killing 1742:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=1742
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/BluetoothHeadset( 1219): onBluetoothStateChange: up=true
D/BluetoothA2dp(  951): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1431): onBluetoothStateChange: up=true
D/BluetoothHeadset(  951): onBluetoothStateChange: up=true
D/CalendarApplication( 3455): onCreate
D/AlertReceiver( 3455): beginStartingService
D/PMS     (  951): acquireWL(386ffca9): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3455 10010 null
,I/ActivityManager(  951): Recipient 1742
,D/BluetoothManagerService(  951): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1219): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/PMS     (  951): releaseHCC(39e07a4f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  951): releaseHCC(31f255dc): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/DriveInitializer( 2175): Background init thread started,
,D/BluetoothAdapter( 1219): 34554301: getState(). Returning 12
D/VoldConnector(  951): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/}
,D/BluetoothAdapter( 1219): 34554301: getState(). Returning 12
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
W/ContextImpl( 2175): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
I/QuickSettingBluetooth( 1219): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1219): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,I/art     (  951): Explicit concurrent mark sweep GC freed 28990(1905KB) AllocSpace objects, 56(3MB) LOS objects, 33% free, 16MB/24MB, paused 1.505ms total 161.962ms,
,D/BluetoothManagerService(  951): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService,
D/PMS     (  951): acquireWL(2a42e75c): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2076 10011 null
D/BluetoothManagerService(  951): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  951): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2,
D/PMS     (  951): acquireWL(1426d11d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null,
W/DriveInitializer( 2175): Background init thread ended
V/BluetoothPbapReceiver( 3185): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3185): ***********state = 12
,D/PMS     (  951): releaseWL(1426d11d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/BluetoothPbapService( 3185): Pbap Service onCreate
V/BluetoothPbapService( 3185): Starting PBAP service
,D/PMS     (  951): acquireWL(3fed4d63): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 1353 1000 null
,D/BluetoothAdapter( 3185): 70489609: getState(). Returning 12
V/BluetoothPbapService( 3185): Handler(): got msg=1
W/ContextImpl( 1353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothPbapService( 3185): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3185): Pbap Service initSocket
D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
D/HtcBtWidget_BTWidgetProvider( 3321): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3321): updateWidget(context) for widget: 
I/bt-btm  ( 3185): BTM_SetDiscoverability
D/PMS     (  951): releaseWL(2a42e75c): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
I/bt-btm  ( 3185): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3185): disc_mode 0000
I/bt-btm  ( 3185): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3185): BTA_JvCreateRecordByUser
I/bt-btif ( 3185): BTA_JvCreateRecordByUser
I/bt-btm  ( 3185): BTM_SetConnectability
I/bt-btm  ( 3185): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3185): disc_mode 0000
D/bt-btm  ( 3185): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 3185): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 3185): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3185): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3185):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3185): Succeed to create listening socket 
V/BluetoothPbapService( 3185): Accepting socket connection...
,D/PMS     (  951): releaseWL(3fed4d63): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  951): acquireWL(b646219): PARTIAL_WAKE_LOCK  StartingDockService 0x1 1353 1000 null
,D/BluetoothAdapterProperties( 3185): Scan Mode:21
,W/System.err(  951): java.lang.Throwable: stack dump
,W/System.err(  951): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  951): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  951): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  951): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_ADAPTER
D/DFPI.PIReciver( 3045): onReceiver action:android.intent.action.BOOT_COMPLETED
D/HtcAlertService( 3455): start to updateAlertNotification!
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24e5feea:true
D/DFPI    ( 3045): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@1e610c7b
,D/DFPI    ( 3045): set install APK prefrence is false
,W/CustomizationIntentService( 1683): failed at default contact creation!
W/CustomizationIntentService( 1683): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1683): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1683): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1683): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1683): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1683): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1683): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1683): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1683): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1683): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1683): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1683): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
W/CustomizationIntentService( 1683): AFH Enable: false, LEONCHAME: false
,D/HtcAlertService( 3455): No fired or scheduled alerts
W/CustomizationIntentService( 1683): hasBeenInit true
W/CustomizationIntentService( 1683): isNewChameleonHFASupported false
W/CustomizationIntentService( 1683): isHFA true
W/CustomizationIntentService( 1683): setupWizRun 1
D/HtcAlertUtils( 3455): -- cancelReminderNotification --
D/HtcAlertUtils( 3455): broadcastExistReminder!
,D/BluetoothAdapter( 1353): 465770886: getState(). Returning 12
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  951): releaseWL(386ffca9): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/BluetoothInputDevice( 1353): BluetoothInputDevice()
D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/AlertReceiver( 3455): stopSelfResult true
D/BluetoothManagerService(  951): Registered receivers: 7
,D/BluetoothPan( 1353): BluetoothPan()
,D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 8
,D/BluetoothMap( 1353): Create BluetoothMap proxy object
,D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 9
E/BluetoothMap( 1353): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 1353): BluetoothSap() call bindService
D/BluetoothManagerService(  951): Registered receivers: 10
,W/ContextImpl( 1353): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 ,
D/BluetoothPbap( 1353): BluetoothPbap()
D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 11
,D/BluetoothManagerService(  951): registerStateChangeCallback+
,D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 12
,D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothHeadset( 1353): BluetoothHeadset()
D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  951): Registered receivers: 13
,D/LocalBluetoothProfileManager( 1353): LocalBluetoothProfileManager construction complete
,I/bt-btif ( 3185): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3185):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3185): Accept thread started.
,D/DockEventReceiver( 1353): finishStartingService: stopping service
,D/BluetoothA2dp( 1353): Proxy object connected
D/A2dpProfile( 1353): Bluetooth service connected
D/BluetoothAdapter( 3185): 70489609: getState(). Returning 12
D/BluetoothAdapter( 1353): 465770886: getState(). Returning 12
D/BluetoothFtpService( 3185): ACTION_STATE_CHANGED: state: 12mHasStarted: true
,D/BluetoothMasReceiver( 3185): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 3185):  call MAP start service
,V/BluetoothPbapService( 3185): Pbap Service onBind
D/BluetoothInputDevice( 1353): Proxy object connected
D/HidProfile( 1353): Bluetooth service connected
,D/BluetoothFtpService( 3185): htc sense version is 6.0
,D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 1353): 465770886: getState(). Returning 12
,W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3185): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
,I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3185):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothPan( 1353): BluetoothPAN Proxy object connected
D/PanProfile( 1353): Bluetooth service connected
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3185): Run Accept thread
D/PMS     (  951): acquireWL(36b782d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
,E/BluetoothMasService( 3185): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothHeadset( 1353): Proxy object connected
,D/HeadsetProfile( 1353): Bluetooth service connected
D/PMS     (  951): releaseWL(2267e4f1): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
D/BluetoothAdapter( 1353): 465770886: getState(). Returning 12
,D/BluetoothMasService( 3185): Add permission for SmsProvider.
,D/PMS     (  951): releaseWL(b646219): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothMasService( 3185): Starting MAS instances
D/PMS     (  951): releaseWL(36b782d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/BluetoothPbap( 1353): Proxy object connected
D/BluetoothAdapter( 3185): 70489609: getState(). Returning 12
D/PbapServerProfile( 1353): Bluetooth service connected
I/ActivityManager(  951): Killing 3070:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3070
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/MailMessageReceiver( 3185): reg:com.android.bluetooth.btservice.AdapterApp@378dd2e6 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@21891027
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=41
E/WifiTrafficPoller(  951): notifying of data activity 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  951): Recipient 3070
,I/MailManager( 3185): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@21891027
V/EmailUtils( 3185): Manager Instance is not NULL
,I/ActivityManager(  951): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3527 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3543 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a,
,D/FlexNetS( 2076): setNetMode:0, false,
,D/FlexNetS( 2076): set2gLowSignalEnablePref: false
V/FlexNetS( 2076): [DRX] setHigherPowerIn2GPref to: true
,D/FlexNetS( 2076): setSimCardisWhiteList: false
,V/FlexNetS( 2076): setSimCardCamp3GNetworkSignalPref to: false
D/FlexNetS( 2076): setCampNetworkisBlackList: false
,V/FlexNetS( 2076): [DRX] setHigherPowerIn2GPref to: true
,V/FlexNetS( 2076): setRilHandOverW2GEnable: 0
,D/FlexNetS( 2076): updateSvcAllowedInSettings:false
,D/HtcAdjCursorFactory( 3527): Set CursorWindow size to: 4194304 KB, Tid: 3561
,I/ActivityManager(  951): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3573 uid=10026 gids={50026, 9997} abi=arm64-v8a
I/ActivityManager(  951): Killing 2672:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2672
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 2672,
,D/EmailUtils( 3185): ============NULL aList========,
V/EmailUtils( 3185): <-getEmailAccountIdList
V/BluetoothMasService( 3185): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3185): 70489609: getState(). Returning 12
V/BluetoothMasService( 3185): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3185): Manager Instance is not NULL
,D/EmailUtils( 3185): ============NULL aList========
V/EmailUtils( 3185): <-getEmailAccountIdList
V/BluetoothSapReceiver( 3185): SapReceiver onReceive 
V/BluetoothSapReceiver( 3185): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3185):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3185): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothMasService( 3185): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3185): BluetoothMns: isEmailEnabled: true
D/AuthorizationBluetoothService( 1908): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3185): BTA_JvCreateRecordByUser
D/bt-btm  ( 3185): BTM_AllocateSCN
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 3185):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3185): BTA_JvCreateRecordByUser
D/bt-btm  ( 3185): BTM_AllocateSCN
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 3185):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/A2dpService( 3185): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@27d43772
D/A2dpSinkService( 3185): getA2dpSinkService(): service is NULL
D/Process (  951): killProcessQuiet, pid=2808
I/ActivityManager(  951): Killing 2808:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,V/OneTimeInitializerReceiver( 3573): OneTimeInitializerReceiver.onReceive,
,I/ActivityManager(  951): Recipient 2808
,V/BluetoothSapService( 3185): Sap Service onCreate,
V/BluetoothSapService( 3185): initBinder
,V/BluetoothSapService( 3185): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@326c87c3
V/BluetoothSapService( 3185): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@3b711379
,V/BluetoothSapService( 3185): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3185): state: 12
V/OneTimeService( 3573): OneTimeService.onHandleIntent
,D/SapServerProfile( 1353): Bluetooth service connected
,V/BluetoothSapService( 3185): Starting SAP server process
,V/BluetoothSapService( 3185): SAP Service startRfcommListenerThread,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2859, uid=10027, userID:0
V/BluetoothSapService( 3185): Sap Service initRfcommSocket
D/BluetoothManagerService(  951): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3185): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3185): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3185): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3185): Write Extended Inquiry Response to controller
I/bt-btif ( 3185): BTA_JvRfcommStartServer
I/bt-btm  ( 3185): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3185):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3185): Succeed to create listening socket 
V/BluetoothSapService( 3185): Accepting socket connection...
,I/ActivityManager(  951): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3608 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a,
,D/PMS     (  951): acquireWL(171d607f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(171d607f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(2c22f84c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:2944] from screen [on:0 period:828869644] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/PMS     (  951): releaseWL(2c22f84c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828869645] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2859, uid=10027, userID:0
,D/PMS     (  951): acquireWL(2fa9a5aa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2fa9a5aa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  951): killProcessQuiet, pid=2905
,I/ActivityManager(  951): Killing 2905:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  951): acquireWL(731859b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
D/PMS     (  951): releaseWL(731859b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.05 txretriesrate=0.00 rxrate=8.09 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=41
,D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951): notifying of data activity 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  951): Recipient 2905
,I/ActivityManager(  951): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3635 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a,
,D/Process (  951): killProcessQuiet, pid=3124
I/ActivityManager(  951): Killing 3124:com.htc.backup/u0a109 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 3124
,E/WifiStateMachine(  951): handleMessage: X
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  951): killProcessQuiet, pid=3239
I/ActivityManager(  951): Killing 3239:com.futuredial/u0a82 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  951): Recipient 3239
,D/PMS     (  951): acquireWL(17ad4d38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(17ad4d38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/RlzPingService( 2859): Setting next ping for 1453132616308
,I/ActivityManager(  951): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3657 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  951): killProcessQuiet, pid=3210
I/ActivityManager(  951): Killing 3210:com.android.keychain/1000 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PMS     (  951): acquireWL(13a12111): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(13a12111): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/art     (  404): Explicit concurrent mark sweep GC freed 8632(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 202us total 30.050ms,
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 180us total 21.389ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 22.355ms
,I/ActivityManager(  951): Recipient 3210
,D/Process (  951): killProcessQuiet, pid=2880
I/ActivityManager(  951): Killing 2880:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  951): acquireWL(17d47276): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(17d47276): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/wpa_supplicant( 1362): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1362): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1362): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1362): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1362): wlan0: Scan completed in 6.081671 seconds
D/wpa_supplicant( 1362): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1362): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1362): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1362): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1362): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1362): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1362): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-93
D/wpa_supplicant( 1362): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 1362): wlan0: BSS: Add new id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 1362): wlan0: BSS: Add new id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 1362): wlan0: BSS: Add new id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 1362): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 1362): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1362): wlan0: Scan-only results received
D/wpa_supplicant( 1362): wlan0: Radio work 'scan'@0x55c5167680 done in 6.082837 seconds
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 a0:c5:62:7a:49:97]
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81]
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 06:7c:34:12:7f:81]
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:96]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState,
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1362): wlan0: Control interface command 'LIST_DONGLES'
,I/ActivityManager(  951): Recipient 2880,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=42
E/WifiTrafficPoller(  951): notifying of data activity 1
,D/WIFI_ICON( 1219): WifiActivity: 1
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  951): [1,452,527,816,849 ms] noteScanEnd no scan source,
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/Personalize.BootComple_( 3657): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
E/Personalize.BootComple_( 3657): action android.intent.action.BOOT_COMPLETED
E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39eefa30 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
,E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC243894600 a0:c5:62:7a:49:96 rssi=-93 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 7 now 1452527816855
E/WifiAutoJoinController (  951): newSupplicantResults size=7 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1362): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
,E/Personalize.Utilities( 3657): SimpleLauncher not found: com.htc.simplelauncher
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3657, uid=1000, userID:0
,D/Process (  951): killProcessQuiet, pid=3165
I/ActivityManager(  951): Killing 3165:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/WifiManager( 1811): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,I/ActivityManager(  951): Recipient 3165
,E/Personalize.BootComple_( 3657): initialize: false
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3657, uid=1000, userID:0
E/Personalize.Utilities( 3657): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
,D/Process (  951): killProcessQuiet, pid=3384
I/ActivityManager(  951): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3678 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  951): Killing 3384:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  951): Recipient 3384,
,V/BootCompletedReceiver( 3678): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling ,
,D/PeopleYouKnow( 3678): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) },
,I/ActivityManager(  951): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3703 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
D/Process (  951): killProcessQuiet, pid=3455
I/ActivityManager(  951): Killing 3455:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 3455
,D/AccTypeManager( 3678): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3703): ACTION_BOOT_COMPLETED,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3703, uid=10040, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 3703): ACTION_BOOT_COMPLETED
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3703, uid=10040, userID:0
,I/ActivityManager(  951): Killing 1353:com.android.settings/1000 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=1353
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/AccTypeManager( 3678): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  951): Recipient 1353
D/WifiService(  951): Client connection lost with reason: 4
,D/AccTypeManager( 3678): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/DotMatrix( 1302): [EventReceiver] onReceive, version:1.3
V/BluetoothSapService( 3185): onUnbind
,I/ActivityManager(  951): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3726 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ExternalAccountType( 3678): Unsupported attribute readOnly
,D/AccTypeManager( 3678): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/AccTypeManager( 3678): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 3678): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3678): Unsupported attribute readOnly
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=22 rxSum=16} preTxRxSum={txSum=22 rxSum=16}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=44
,I/art     (  951): Explicit concurrent mark sweep GC freed 17525(969KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.487ms total 144.278ms,
,I/ActivityManager(  951): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3751 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a,
,W/ResourcesManager( 3751): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,D/Process (  951): killProcessQuiet, pid=3321
I/ActivityManager(  951): Killing 3321:com.htc.widget.hmsproc3/u0a34 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 3321,
,D/MediaSessionHelper( 3751): Attempting to get helper with context android.app.ReceiverRestrictedContext@9cc475,
,D/MediaSessionService(  951): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
,D/MediaSessionHelper( 3751): addMediaButtonListener added PendingIntent{1e610c7b: android.os.BinderProxy@2e197c0a}
,I/ActivityManager(  951): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3774 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 3045:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3045
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 3045
,I/ActivityManager(  951): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  951): Killing 3338:android.process.media/u0a17 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3338
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 3338,
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 1 times.
,W/ContextImpl( 3796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 3796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 3796): MY_DEBUG = false
,W/ContextImpl( 3796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  951): sending alarm PendingIntent{21550a5f: PendingIntentRecord{3ed88cac com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452527818506, Int=0
,D/HtcAppUPService( 1565): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED,
D/HtcAppUPService( 1565): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@2280cce9
W/ContextImpl( 3796): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 
I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
,D/AutoSetting( 1565): receiver - intent: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1565): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,I/WSP     ( 1565): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,I/ActivityManager(  951): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3828 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/HtcAppUPService( 1565): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/AutoSetting( 1565): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1565): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1565): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1565): service - handleMessage() removing cache
D/HtcAppUPService( 1565): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
D/AutoSetting( 1565): service - AddressCache: clean up all cache
D/AutoSetting( 1565): service - handleMessage() setting current location null
,I/ActivityManager(  951): Killing 3543:com.htc.fm/u0a20 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3543
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:,
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1565): feature
D/FeatureList( 1565): type
D/FeatureList( 1565): description
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155),
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
,W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	,at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source),
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source),
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
,W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61),
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800),
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  951): Recipient 3543
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer,
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1565): Attempt to cast generated internal exception:,
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	,at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1565): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1565): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1565): Attempt to cast generated internal exception:
W/Bundle  ( 1565): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1565): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1565): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/BootReceiver( 3828): onReceive: android.intent.action.BOOT_COMPLETED
,D/BootReceiver( 3828): boot completed:
,D/BootReceiver( 3828): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true,
D/BootReceiver( 3828): Valid
D/BootReceiver( 3828): startService:
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:2700] from screen [on:0 period:828872711] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828872713] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
I/ActivityManager(  951): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3849 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
I/ActivityManager(  951): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3867 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.52 txretriesrate=0.00 rxrate=8.05 userTriggerdPenalty0
I/ActivityManager(  951): Killing 2076:com.htc.bgp/u0a11 (adj 15): empty #17
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=49
D/Process (  951): killProcessQuiet, pid=2076
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 2076
,D/PluginProvider( 1565): Begin Apply Batch
,E/PluginProvider( 1565): conflict when insert feature, ignored
,E/WifiStateMachine(  951): handleMessage: X
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,D/PMS     (  951): releaseWL(27dae2ad): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/NGFService( 3849): onCreate +++
,D/SettingUtils( 3849): getProcessNormalFlag: true,
D/NGFService( 3849): onCreate last time crash or 1st run=false
D/SettingUtils( 3849): setProcessNormalFlag: false
,D/NGFService( 3849): getAudioStreamType: ScoOn =false,
D/SoundEffects( 3849): init +++ 3
,W/LMW     ( 3867): [3896][ActionDeviceStorageHandler] onActionBootComplete++
,I/ActivityManager(  951): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3899 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a,
W/LMW     ( 3867): [3896][ActionDeviceStorageHandler] onActionBootComplete--,
D/Process (  951): killProcessQuiet, pid=3527
I/ActivityManager(  951): Killing 3527:com.htc.android.mail:sync/u0a62 (adj 15): empty #17,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  398): Heap size overflow! req size: 1058400, max size: 1048576
,W/NuPlayerRenderer(  398): AudioSink write short frame count 0 < 9824
,I/ActivityManager(  951): Recipient 3527,
,D/NGFLanguageMgr( 3849): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3849): language package name = preload_package
,W/libutils.threads(  398): Thread (this=0xab65f700): don't call join() from this Thread object's thread. It's a guaranteed deadlock!,
W/OMX     (  398): loop count is null and break
,D/PluginProvider( 1565): apply Batch success
,I/[PluginManager]RegisterService( 1565): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  951): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3970 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,D/Process (  951): killProcessQuiet, pid=3573
I/ActivityManager(  951): Killing 3573:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/NMT     ( 3849): NMT version: 1.6.1-B006 REL,
D/NGFService( 3849): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,I/ActivityManager(  951): Recipient 3573
,D/NGFService( 3849): applyCurrentSystemLanguage +++
D/NGFService( 3849): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3849): LanguageFromSystem: language:en  country:gb
,D/NGFService( 3849): Elvis language uses the language: 2
D/NGFService( 3849): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3849): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3849): bluetoothInitialize +++
,W/System.err(  951): java.lang.Throwable: stack dump
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d290f3:true
W/System.err(  951): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  951): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  951): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  951): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothHeadset( 3849): BluetoothHeadset(),
D/BluetoothManagerService(  951): registerStateChangeCallback+
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 7
,D/BluetoothManagerService(  951): registerStateChangeCallback+,
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  951): Registered receivers: 8
,D/NGFService( 3849): cloud_init +++
D/NGFLanguageMgr( 3849): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,V/AlarmManager(  951): sending alarm PendingIntent{1bd846c8: PendingIntentRecord{7574361 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=45425, Int=0,
,D/MediaProvider( 3970): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0,
D/MediaProvider( 3970): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3970): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd,
D/MediaProvider( 3970): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3970): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3970): [MP][DEBUG] Storage State: removed
,D/NGFService( 3849): elvisInitalize +++,
,E/SQLiteLog( 3970): (283) recovered 44 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal
,D/MediaScannerReceiver( 3970): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 3970): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 3970): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED,
,D/NGFService( 3849): elvisInitalize lang = British English
,D/NGFService( 3849): elvisInitalize: Freq Type:16000
D/NGFService( 3849): tts_init +++
D/NGFLanguageMgr( 3849): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,D/NGFLanguageMgr( 3849): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3849): language package name = preload_package
,D/NGFService( 3849): load vocalizer language = British English
,E/NGFService( 3849): registerObserver,
,D/NGFService( 3849): onCreate: Battery Level Remaining: 100%
,D/NGFService( 3849): onStartCommand(): service start
D/NGFService( 3849): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3849): QuickCall
,D/BluetoothHeadset( 3849): Proxy object connected,
,D/NGFService( 3849): BluetoothHeadset onServiceConnected: main
D/BluetoothAdapter( 3849): 818547307: getState(). Returning 12
W/NMT     ( 3849): Fail to open read-stream for file generic.lst
,W/NGFService( 3849): Headset deviceList = 0
D/BluetoothA2dp( 3849): Proxy object connected
,D/NGFService( 3849): BluetoothA2dp onServiceConnected: main
,D/BluetoothAdapter( 3849): 818547307: getState(). Returning 12
,W/NGFService( 3849): A2dp deviceList = 0,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=52
,W/NMT-OemFile( 3849): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3849): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,W/NMT-OemFile( 3849): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,W/NMT-OemFile( 3849): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3849): fopen(): Failed to open file sysdct.dat
D/MediaScannerServiceEx( 3970): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3970): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
,W/NMT-OemFile( 3849): fopen(): Failed to open file clm.dat
,D/PMS     (  951): acquireWL(1ccbfd99): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3970 10017 null
,D/MtpReceiver( 3970): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3970): [MTP][handleUsbStateAsync]1:1-
,D/MtpReceiver( 3970): [MTP][handleUsbState]+
,D/NGFService( 3849): Elvis is initialization Success
,D/NGFService( 3849): bElvisInitializeCompleted = true
D/NGFService( 3849): GrammarState = 0
D/NGFService( 3849): loadGrammar +++
D/NGFService( 3849): loadGrammar asr_grammar
I/NGFService( 3849): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3849): loadGrammar from cache
,W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishname.lst
I/ActivityManager(  951): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=4010 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishartist.lst
W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishplaylist.lst
D/MediaProvider( 3970): bindService() MTP Service Connection.
W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3849): Fail to open read-stream for file elvisBritish Englishgeneric.lst
,D/MediaScanner( 3970): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/MtpReceiver( 3970): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3970): [MTP][handleUsbState]-
D/MtpReceiver( 3970): [MTP][handleMessage]-
D/MtpService( 3970): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpService( 3970): addStorageInternal without MtpServer
,W/NMT-OemFile( 3849): fopen(): Failed to open file daniel_userdct_eng.dat
I/art     (  405): Explicit concurrent mark sweep GC freed 8682(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 377us total 27.427ms
,D/MtpService( 3970): [MTP][onCreate]-
,I/ActionCombine( 3970): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 302us total 19.733ms
,D/MtpService( 3970): [MTP] startForeground
,D/MtpService( 3970): updating state; isCurrentUser=true, mMtpLocked=false
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 245us total 16.892ms
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/PMS     (  951): acquireWL(34384d3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2175 10024 null
D/SettingUtils( 3849): setProcessNormalFlag: true
,D/MtpDatabase( 3970): TotalSize=1886532,MediaCacheLimit=6000
D/NGFService( 3849): RebuildListener constraintList size 17
,D/NGFService( 3849): RebuildListener: onComplete0
D/NGFService( 3849): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3849): switchScenario: htc_screen_140_19
D/NGFService( 3849): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3849): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3849): Loading grammar completed.
D/NGFService( 3849): update contact cache completed
D/SettingUtils( 3849): set Updatge Contact Cache: false
E/SQLiteLog( 3970): (283) recovered 588 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
,D/MtpService( 3970): starting MTP server in MTP mode
,W/HtcWrapAdjustableCursorFactory( 4010): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MtpService( 3970): addStorageInternal 65537 /storage/emulated/0,
D/MessageFrequencyProvider( 4010): onCreate
,I/RemoteViews( 1219): apply : com.android.providers.media 0 12 2 36
,V/GetPrviateResource( 4010): GetPrviateResource
,V/GetPrviateResource( 4010): GetPrviateResource
,D/MessageCustFlag( 4010): sense_version=6.0
,D/BTAccessoryUtil( 4010): createReceiver
I/RemoteViews( 1219): apply : com.android.providers.media 0 12 1 51
D/BTAccessoryUtil( 4010): registerReceiver return intent = null
,D/MessageCustFlag( 4010): sku_id=118,
,D/HtcBuildUtils( 4010): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4010): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 4010): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/MtpService( 3970): [checkStorageState] Storage state - mounted
,D/MtpDatabase( 3970): [MTP][addStorage] iHostType =2
D/MtpService( 3970): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,D/ExchangePolicystatus( 4010): onReceive()
D/ExchangePolicystatus( 4010): onReceive(): ACTION_BOOT_COMPLETED
,D/MessageUtils( 4010): Text messaging allow status = allow
D/Messaging( 4010): EAS allow SMS !!!
,D/ExchangePolicystatus( 4010): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 4010): EAS allow SMS !!!
D/PMS     (  951): acquireWL(33be641a): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 4010 10064 null
,I/ActivityManager(  951): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=4046 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/SmsReceiverService( 4010): onStart: #1, @1018073075,
V/SmsReceiverService( 4010): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 4010): isCbm: false
D/SmsReceiverService( 4010): isDiscard: false
D/SettingsManager( 4010): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@24e9f557
V/AlarmManager(  951): sending alarm PendingIntent{219ec928: PendingIntentRecord{2ed60641 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=45802, Int=0
,V/AlarmManager(  951): sending alarm PendingIntent{219ec928: PendingIntentRecord{2ed60641 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=45803, Int=0
V/SmsReceiverService( 4010): handleBootCompleted
,I/iu.UploadsManager( 2175): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,W/MediaScanner( 3970): Error opening directory '/oem/media/', skipping: No such file or directory.
,D/WeatherUtility( 1219): Weather sync is On
I/ClockController( 1219): schedule update now=1452527820017 next=59983
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
I/Clock   ( 1219): updateClock:16:57 Europe/Warsaw
I/Clock   ( 1219): updateClock:16:57 Europe/Warsaw
,I/Clock   ( 1219): updateClock:16:57 Europe/Warsaw
,W/ResourcesManager( 4010): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/MediaScanner( 3970): Error opening directory '/oem/media/', skipping: No such file or directory.
,D/MediaScanner( 3970):  prescan time: 151ms
,D/MediaScanner( 3970):     scan time: 32ms
D/MediaScanner( 3970): postscan time: 0ms
D/MediaScanner( 3970):    total time: 183ms
D/MediaScanner( 3970): -----------------------------------------------------------------
D/MediaScanner( 3970): firstscan(media) time: 18ms
D/MediaScanner( 3970): secondscan(non-media) time: 10ms
D/MediaScanner( 3970):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Total]    File(Image+Video+Audio+Others) in database : 339
,E/MediaScannerService( 3970): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3970): [handleMessage] --- Should not be here, ignore request. ----
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1431): sku_id=118
,D/SmsReceiverService( 4010): OutBoxSize = 0
D/SmsReceiverService( 4010): sendFirstQueuedMessage start: 0,
D/MessageCustFlag( 4010): sku_id=118
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/AccFlag ( 1431): sku_id=118
,D/MessageCustFlag( 4010): sku_id=118
,D/SmsReceiverService( 4010): sendFirstQueuedMessage end cnt> 0
,D/SpaceBufferUtil( 4010): > createBufferFile()
D/SpaceBufferUtil( 4010): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
,D/SpaceBufferUtil( 4010): < createBufferFile()
,I/iu.UploadsManager( 2175): End new media; added: 0, uploading: 0, time: 71 ms
,D/PMS     (  951): releaseWL(34384d3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/MediaProvider( 3970): [delete][63]
D/MediaProvider( 3970): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3970): [recoverParentNodes] - 0
,D/MediaProvider( 3970): [update][15],
D/MediaScannerServiceEx( 3970): [scan] Recover Parent Node is finished!
D/PMS     (  951): releaseWL(1ccbfd99): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,E/MediaScannerServiceEx( 3970): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3970): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3970): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3970): [update][6]#0#
,D/MediaProvider( 3970): [update][2]#0#
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3970): [sendStorageAdded] Already send to MTP: /storage/emulated/0
E/cutils-trace( 4072): Error opening trace file: Permission denied (13)
I/dex2oat ( 4072): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4072): dex2oat: override thread count:4
D/MediaProvider( 3970): [update][9]#1#
D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]-0, 0
,D/PMS     (  951): acquireWL(3e4ea7e6): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3970 10017 null,
,D/MediaScanner( 3970): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
,I/HtcModeClient( 3300): handler message = 4009
,I/HtcModeClient( 3300): start to setup the connection
,I/art     (  951): Explicit concurrent mark sweep GC freed 9011(440KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.446ms total 126.343ms
,I/dex2oat ( 4072): dex2oat took 629.646ms (threads: 4),
,I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=55
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 4046): ApplicationMonitor {f2184b0}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/ActivityManager(  951): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4080 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/PushClient( 4046): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
,D/Process (  951): killProcessQuiet, pid=3608
,I/ActivityManager(  951): Killing 3608:com.htc.video/u0a29 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 3608
,D/SMSBackup( 4080): Got ACTION_BOOT_COMPLETED event
,D/SMSBackup( 4080): setCheckAlarm
,D/SMSBackup( 4080): Next check is scheduled at 60s from now
,I/ActivityManager(  951): Killing 2859:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2859
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/AutoSetting( 1565): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1565): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1565): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  951): Recipient 2859,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1431, uid=1001, userID:0,
,I/ActivityManager(  951): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=4103 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/[AppShowMeDebug]BootCompletedReceiver( 4103): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 4103): push flag is false, skip check,
,I/ActivityManager(  951): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=4126 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,I/ActivityManager(  951): Killing 2240:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2240
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 2240,
,D/MyReportAgent( 4126): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED,
,D/MyReportAgent( 4126): DatabaseHelper [DatabaseHelper constructor]
,D/MyReportAgent( 4126): PolicyStore [Init] Get cached policy bundle
,I/ActivityManager(  951): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4148 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,D/MyReportAgent( 4126): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE,
,D/MyReportAgent( 4126): ReportServiceHandler on boot complete event 
I/art     (  404): Explicit concurrent mark sweep GC freed 8635(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 253us total 31.457ms
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=4126, uid=10083, userID:0
,V/MyReportAgent( 4126): ReportServiceHandler unregister the PowerConnected Listener,
,I/ActivityManager(  951): Killing 3635:com.htc.csrecommend/u0a31 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3635
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 23.752ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 181us total 21.776ms
,I/ActivityManager(  951): Recipient 3635,
,D/UpdaterAPK | UpdaterBootCompleteReceiver( 4148): onReceive() - start htcCheckinService
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState,
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:2789] from screen [on:0 period:828875739] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:828875742] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
I/htcCheckinService(  951): htcCheckinProvider V2.1
D/htcCheckinService(  951): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  951): Checkin service onCreate()!
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.26 txretriesrate=0.00 rxrate=8.02 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
I/ActivityManager(  951): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4173 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
,E/WifiStateMachine(  951): handleMessage: X
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/htcCheckinService(  951): onStartCommand(),
D/htcCheckinService(  951): onStartCommand() the action name = null
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=57
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/htcCheckinService(  951): InitThread start
,D/htcCheckinService(  951): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  951): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/ActivityManager(  951): Killing 2650:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  951): killProcessQuiet, pid=2650
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaScanner( 3970):  prescan time: 725ms,
D/MediaScanner( 3970):     scan time: 999ms
D/MediaScanner( 3970): postscan time: 2ms
D/MediaScanner( 3970):    total time: 1726ms
D/MediaScanner( 3970): -----------------------------------------------------------------
D/MediaScanner( 3970): firstscan(media) time: 577ms
D/MediaScanner( 3970): secondscan(non-media) time: 422ms
D/MediaScanner( 3970):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 3970): [delete][12],
D/MediaProvider( 3970): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3970): [recoverParentNodes] - 0,
D/MediaProvider( 3970): [update][6]
D/MediaScannerServiceEx( 3970): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3970): [updateImage]+,
,D/MediaScannerServiceEx( 3970): [updateImage]-0,
,I/ActivityManager(  951): Recipient 2650
,D/PMS     (  951): releaseWL(3e4ea7e6): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3970): [2] scan finished
D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+131073,
D/Messaging( 4010): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4010): networkCode: 
D/MmsConfig( 4010): SIE smsPri: null
D/MmsConfig( 4010): networkCode: 
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3970): [update][7]#1#
,D/MmsConfig( 4010): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4010): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 4010): ,
D/MmsAsyncWorkHandler( 4010): HM tk = 20001
D/ReportIndicatorCache( 4010): MSG_QUERY_REPORTS >>
D/Messaging( 4010): mNeedToUpdateDate2 start
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1431):  slotId = -1000
,D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/DraftCache( 4010): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4010): [DraftCache/1] refresh
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1431): sku_id=118
,I/Messaging( 4010): mccmnc> 
,D/MmsConfig( 4010): networkCode: 
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4010): [DraftCache/96] rebuildCache
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/MediaProvider( 3970): [update][33]#0#
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
D/Messaging( 4010): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/usb
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+196609
D/Messaging( 4010): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 4010): mNeedToUpdateDate2: false
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3970): [update][11]#1#
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/Jerry   ( 1431): URI_DRAFT
,D/PhoneStorageUtil( 4010): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4010): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4010): createReceiver
,D/DraftCache( 4010): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4010): [DraftCache/96] rebuildCache time: 10
D/MmsAsyncWorkHandler( 4010): 
D/MmsAsyncWorkHandler( 4010): HM tk = 20002
,D/MessageCustFlag( 4010): sense_version=6.0
,D/TelephUtils( 1431): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1431): Update uri=content://mms, match=0
V/MmsProvider( 1431): selection=st=129 AND m_type!=134
D/Jerry   ( 4010): start to preload cursor >>>>>>>
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73,
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/Messaging( 4010): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4010): TransactionService is going to be woken up.
,D/PMS     (  951): acquireWL(17478a39): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4173 10090 null
,V/TransactionService( 4010): 1-Creating TransactionService
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1431): sku_id=118
,D/MediaProvider( 3970): [update][30]#0#
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
,E/MediaScannerServiceEx( 3970): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3970): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3970): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]+65537, 11223344
,I/WorldClock.Global( 4173): isHEPDevice = true
,V/TransactionService( 4010): onStartCommand: 1,
D/MmsSystemEventReceiver( 4010): unRegisterForConnectionStateChanges
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1431): sku_id=118
V/TransactionService( 4010): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4010): Loading previous transactions.
W/ContextImpl(  951): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
D/Messaging( 4010): ViewCache CreatePreload
D/Messaging( 4010): ViewCache CreatePreloadOnlyMultipleOpsList
D/MediaProvider( 3970): [update][7]#0#
D/MediaProvider( 3970): [update][2]#0#
,W/SystemReader( 4173): Cannot find support_china_sense_feature, use default value instead
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 3970): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3970): [update][7]#1#
,D/Cust_MMSMS( 4010): _has_set_default_values_2=true
,D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]-0, 0
D/PMS     (  951): acquireWL(3aa9ecfb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3970 10017 null
D/MsgPreferenceUtils( 4010): def_index: 0
,D/MsgPreferenceUtils( 4010): globalIndex = 1
,I/ActivityManager(  951): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4214 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,I/WorldClock.AlarmUtils( 4173): saveSupportOffAlarmInPreference: isSupport = false
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1431): device_type: 1
,D/MsgPreferenceUtils( 4010): phone state: true
,D/MsgPreferenceUtils( 4010): sd state: false
D/MsgPreferenceUtils( 4010): vIndex = 0
D/MediaScanner( 3970): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/WorldClock.AlarmService( 4173): isDeviceEncryptionEnabled = false
D/TransactionService( 4010): Force clearing mTransactionList
,D/TransactionService( 4010): Force set service start id to 1
V/TransactionService( 4010): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4010): unRegisterForConnectionStateChanges
D/PMS     (  951): releaseWL(17478a39): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,D/Process (  951): killProcessQuiet, pid=3657
I/ActivityManager(  951): Killing 3657:com.htc.home.personalize/1000 (adj 15): empty #17
D/TransactionService( 4010): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4010): Destroying TransactionService
W/WorldClock.AlarmService( 4173): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/WorldClock.AlarmUtils( 4173): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  951): Recipient 3657,
,V/TransactionService( 4010): 4-Handling incoming message: { when=-106ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,I/WorldClock.AlarmUtils( 4173): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4173): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1219): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/WorldClock.AlarmUtils( 4173): isDeviceEncryptionEnabled = false
,I/WorldClock.AlarmUtils( 4173): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmService( 4173): resetStopwatchToDefault
,I/WorldClock.DmdCmd( 4173): This version is general off mode alarm function
,W/WorldClock.DmdCmd( 4173): Conn: fail e = java.io.IOException: No such file or directory
,I/WorldClock.AlarmService( 4173): resetTimerToDefault
,E/UpdateRequestReceiver( 4214): ignoring update request
,E/UpdateRequestReceiver( 4214): ignoring update request
,E/UpdateRequestReceiver( 4214): ignoring update request,
,E/UpdateRequestReceiver( 4214): ignoring update request,
,E/UpdateRequestReceiver( 4214): ignoring update request,
,E/UpdateRequestReceiver( 4214): ignoring update request
,I/ActivityManager(  951): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4262 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  951): Killing 3678:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3678
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 3678,
,I/DeviceManagement( 4262): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4262 dbg=false s=true,
,I/DeviceManagement( 4262): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 4262): WorkflowService: Starting workflow service,
,I/DeviceManagement( 4262): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@24760d2d] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 4262): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4262): BootCompletedWorkflow: Boot completed,
I/DeviceManagement( 4262): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 4262): ModelRegistry: Loading model meta data from resources...
,I/GoogleHttpClient( 1908): GMS http client unavailable, use old client
,I/ActivityManager(  951): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4286 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/DeviceManagement( 4262): BackgroundController: *** Update after boot...
I/DeviceManagement( 4262): SessionStateController: Checking invariants...
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=22 rxSum=16} preTxRxSum={txSum=22 rxSum=16}
,D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/htcbackup-core( 4286): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 4262): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 4262): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,I/DeviceManagement( 4262): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]],
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=60
,I/ActivityManager(  951): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/ActionCombine( 4286): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/DeviceManagement( 4262): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4262): SessionStateController: Checking invariants...
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
V/SmsReceiverService( 4010): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 4010): New incoming message, can't cancel notification now
D/MessagingNotification( 4010): newMsgCnt: 0, false
,I/ActivityManager(  951): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4343 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
D/Process (  951): killProcessQuiet, pid=3703
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
I/ActivityManager(  951): Killing 3703:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,I/RemoteViews( 1219): apply : com.htc.backup 1 13 6 38
I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 0 11 3 5
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 0 2 5 5,
I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1219): apply : com.htc.backup 1 13 27 50
,I/DeviceManagement( 4262): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/ActivityManager(  951): Recipient 3703,
,I/ActivityManager(  951): Killing 3726:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=3726
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 3726,
,D/PMS     (  951): releaseWL(33be641a): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,I/DeviceManagement( 4262): Perf: *** Cache update - start...,
,I/DeviceManagement( 4262): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4262): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 4262): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4262): Perf: Scan enabled apps - start...
D/ResetNotifyBootCompleteReceiver( 1431): userSerialNumber = 0
D/ResetNotifyBootCompleteReceiver( 1431): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1431): isOwnerUser = true
I/HtcCupdXmlParser( 4343): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  951): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4367 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/ActivityThread( 4343): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/DeviceManagement( 4262): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...,
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,I/HtcModeClient( 3300): handler message = 4011
E/HtcModeClient( 3300): Check connection and retry 2 times.
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159,
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
,W/ResourcesManager( 4262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/QXDM2SD:HtcNative( 1431): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/art     (  951): Explicit concurrent mark sweep GC freed 15567(749KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.491ms total 156.237ms,
,I/ActivityManager(  951): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
,I/HtcCupdXmlParser( 4343): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory),
W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/MediaScanner( 3970):  prescan time: 416ms,
,D/MediaScanner( 3970):     scan time: 1125ms
D/MediaScanner( 3970): postscan time: 89ms,
D/MediaScanner( 3970):    total time: 1630ms
D/MediaScanner( 3970): -----------------------------------------------------------------
,D/MediaScanner( 3970): firstscan(media) time: 661ms
D/MediaScanner( 3970): secondscan(non-media) time: 464ms
D/MediaScanner( 3970):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 3970):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 3970): [delete][17]
D/MediaProvider( 3970): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289),
,D/MediaProvider( 3970): [recoverParentNodes] - 0
,D/MediaProvider( 3970): [update][9]
D/MediaScannerServiceEx( 3970): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3970): [updateImage]+
,D/MediaScannerServiceEx( 3970): [updateImage]-0,
D/MediaScannerServiceEx( 3970): [3] scan finished
D/PMS     (  951): releaseWL(3aa9ecfb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+131073
,W/ResourcesManager( 4262): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4262): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/MediaProvider( 3970): [update][18]#1#
,I/AlarmManager(  951): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
,I/AlarmManager(  951): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  951): [AlarmQueuing] init alarm queuing list,
,I/ActivityManager(  951): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4414 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  951): killProcessQuiet, pid=3751,
I/ActivityManager(  951): Killing 3751:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3970): [update][29]#0#
I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193,
D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4392): -onCreate()
,W/ResourceType( 4262): ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019,
,I/ActivityManager(  951): Recipient 3751
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2,
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+196609
,W/ResourcesManager( 4262): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3970): [update][3]#1#
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/Settings:HtcSettingsApplication( 4392): [4392/4392] onCreate()
,D/MediaProvider( 3970): [update][21]#0#
W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  951): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/AlarmManager(  951): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@285aadd5
,I/AlarmManager(  951): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@175119ea,
,I/AlarmManager(  951): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@186984db,
,I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.facebook.katana
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
I/AlarmManager(  951): [AlarmQueuing] add queuing package: jp.naver.line.android
,I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.viber.voip
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=65
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  951): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  951): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  951): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  951): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/ActivityManager(  951): Killing 3774:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3774
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/TetherSettings( 4392): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4392): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4392): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4392): Cust_ConnectToPC   : spcsc>false
D/        ( 4392): Cust_ConnectToPC   : IPT>true
D/        ( 4392): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4392): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4262): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/DeviceManagement( 4262): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686,
,I/ActivityManager(  951): Recipient 3774,
,I/DeviceManagement( 4262): EnabledAppBuilder: Found 8 DM enabled apps.
,I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,E/SmartNS_Utility( 4392): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4392): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4392): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 4392): setISNotification
,D/SmartNS_Utility( 4392): usb_cable_connect = 1,
,D/SmartNS_Utility( 4392): usb_denied = 0
I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/SmartNS_PSService( 4392): usb notificaiton:true
,E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4392): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,D/SmartNS_Utility( 4392): usb_cable_connect = 1
,D/SmartNS_Utility( 4392): usb_denied = 0
I/SmartNS_PSService( 4392): usb notificaiton:true
,E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1219): reapply : com.android.settings 2 36,
,I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,V/Settings:HtcSettingsApplication( 4435): [4435/4435] onCreate()
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/Process (  951): killProcessQuiet, pid=3796
I/ActivityManager(  951): Killing 3796:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/RemoteViews( 1219): reapply : com.android.settings 1 36
,I/DeviceManagement( 4262): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 4262): Perf: Scan enabled apps - complete: 1056 ms
I/DeviceManagement( 4262): Perf: *** Enabled app cache update - complete: 1056 ms,
I/DeviceManagement( 4262): Perf: *** Config cache update - start...
,I/DeviceManagement( 4262): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4262): ConfigCacheController: *** Updating stale config cache entries...
,I/DeviceManagement( 4262): ConfigCacheController: *** Update config cache: updating 0 entries...
,I/DeviceManagement( 4262): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4262): AlarmController: Scheduling TTL alarm for: 2016.01.11 at 17:36:12.827 CET (due to: com.htc.cs)
,I/ActivityManager(  951): Recipient 3796
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4262, uid=10099, userID:0
I/DeviceManagement( 4262): Perf: *** Config cache update - complete: 198 ms
I/DeviceManagement( 4262): Perf: *** Cache update - complete: 1258 ms
I/DeviceManagement( 4262): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@24760d2d]
I/DeviceManagement( 4262): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@72fa93a] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4262): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4262): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true,
I/DeviceManagement( 4262): SessionStateController: Checking invariants...
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  951): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4460 uid=9987 gids={49987, 9997} abi=arm64-v8a
,I/ActivityManager(  951): Killing 3828:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=3828
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/art     (  404): Explicit concurrent mark sweep GC freed 8675(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 204us total 27.300ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 191us total 25.418ms
,I/DeviceManagement( 4262): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4262): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@72fa93a]
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 161us total 21.622ms
,I/ActivityManager(  951): Recipient 3828,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:828878762] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828878764] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.63 txretriesrate=0.00 rxrate=8.51 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{245a8ceb u0 com.google.android.gms/.gcm.GcmService}
,D/SmartDim(  951): Init customizeScreenOffDelayClass error
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
I/DeviceManagement( 4262): WorkflowService: Stopping workflow service
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951): handleMessage: X
I/ActivityManager(  951): Killing 3867:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3867
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SensorManager(  951): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@a1bc28d, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): enable: get sensor name = Accelerometer Sensor
,W/SensorService(  951): pid=951, uid=1000
W/SensorService(  951): Active sensors: size = 3
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  951): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@a1bc28d, eanble = 1, strlen(mName) = 35
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  951): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@25cb1b39
W/SensorService(  951): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f2ebf50
W/SensorService(  951): Listener[2] = com.htc.smartdim.sensor_eye@a1bc28d
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  951): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@a1bc28d, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): enable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  951): pid=951, uid=1000
W/SensorService(  951): Active sensors: size = 4
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  951): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@a1bc28d, eanble = 1, strlen(mName) = 35
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  951): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@25cb1b39
W/SensorService(  951): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f2ebf50
,W/SensorService(  951): Listener[2] = com.htc.smartdim.sensor_eye@a1bc28d
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  951): Recipient 3867
,I/htcbackup-core( 4286): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET],
W/BroadcastQueue(  951): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{2d0efa89 u0 ReceiverList{2e5d4190 951 system/1000/u0 local:2381b453}}
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,I/SensorManager(  951): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@a1bc28d
,I/ActivityManager(  951): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4483 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  951): Killing 3899:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=3899
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=66
,I/ActivityManager(  951): Recipient 3899
,V/AlarmManager(  951): sending alarm PendingIntent{eac9a8e: PendingIntentRecord{2e6942af com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=9, w=1447326412457, Int=604800000
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.htc.backup 3 38
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 0 2 0 5
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 0 2 0 5
,I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.backup 1 2 0 5
,I/RemoteViews( 1219): reapply : com.htc.backup 10 50
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4505 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  951): Killing 2175:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=2175
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 2175,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4505, uid=10072, userID:0
,W/global  ( 4505): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4505): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 4505): [apache-http] Connection GC has been deprecated!
,W/global  ( 4505): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4505): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  951): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4542 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 4505): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4505): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/ResourcesManager( 4542): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4542): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4505, uid=10072, userID:0
,I/MultiDex( 4542): VM with version 2.1.0 has multidex support,
I/MultiDex( 4542): install
I/MultiDex( 4542): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 4505): [404] DiskBasedCache.clear: Cache cleared.,
,D/Volley  ( 4505): [410] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4542): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  951): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4568 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/Process (  951): killProcessQuiet, pid=4046
I/ActivityManager(  951): Killing 4046:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=68
,W/ActivityThread( 4542): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4542): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4542): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  951): Recipient 4046
,D/Finsky  ( 4505): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4505): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 4568): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4568): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4505): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 4568): VM with version 2.1.0 has multidex support
I/MultiDex( 4568): install
I/MultiDex( 4568): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4505): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,V/JNIHelp ( 4568): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 4568): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4568): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30150e1e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4568): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  951): Killing 4080:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4080
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  951): Recipient 4080
,V/GLSUser ( 1908): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/PMS     (  951): acquireWL(c45b784): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1908 10024 null
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/NotificationStore( 1908): System rebooted after Notification storage file was last written
,I/NotificationStore( 1908): Deleting the file
,D/PMS     (  951): releaseWL(c45b784): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,V/Finsky  ( 4505): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  951): Killing 4103:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4103
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  951): Recipient 4103
,D/PersistentNotificationBroadcastReceiver( 1908): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4568): Found 10024
,D/FileApkUtils( 4568): Spent 23ms computing apk sha1.
,D/FileApkUtils( 4568): Module already staged or being staged:chimera-modules/MapsModule.apk,
I/art     ( 4568): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4568): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4568): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/GmsModuleFndr( 4568): Beginning GMS chimera module scan
,D/PMS     (  951): acquireWL(24bc77ee): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4568 10024 null
,W/asset   ( 4568): Copying FileAsset 0x55aeef8e40 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=69
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1908, uid=10024, userID:0
,D/GmsModuleFndr( 4568): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 4568): Beginning module configuration check
,D/ChimeraCfgMgr( 4568): Module APKs unchanged, check complete
,I/art     (  951): Explicit concurrent mark sweep GC freed 17508(854KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.379ms total 160.012ms
D/PMS     (  951): acquireWL(ddc48f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): acquireWL(178dbb25): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(36fc1aab): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): releaseWL(24bc77ee): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  951): releaseWL(178dbb25): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(fb60d20): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4568 10024 null
,D/GCM     ( 4568): COMPAT: Multi user not supported
,D/GCM     ( 1908): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/PMS     (  951): acquireWL(1cfeef7f): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(ddc48f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4568): Disabling old GoogleServicesFramework version
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0,
,I/GCoreUlr( 4568): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/PMS     (  951): acquireWL(1027c0aa): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1811): DispatchingService.onCreate(),
,W/art     ( 4568): Suspending all threads took: 11.853ms
,I/art     ( 4568): Background sticky concurrent mark sweep GC freed 496(41KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 15.141ms total 27.719ms
,D/PMS     (  951): acquireWL(2b5b47e4): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4568, uid=10024, userID:0,
I/CheckinService( 4568): Checking schedule, now: 1452527827424 next: 1453064464288
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
I/CheckinService( 4568): active receiver: disabled
,I/ActivityManager(  951): Delay finish: com.google.android.gms/.kids.chimera.SystemEventReceiverProxy
D/SystemUpdateService( 4568): onCreate
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4568, uid=10024, userID:0
,D/SystemUpdateService( 4568): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/GCoreUlr( 1811): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  951): java.lang.Throwable: stack dump
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60c4768:true
W/System.err(  951): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  951): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  951): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  951): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ConfigService( 1908): onCreate,
,I/SystemUpdateService( 4568): cancelUpdate (empty URL),
I/art     ( 4568): Background partial concurrent mark sweep GC freed 2755(243KB) AllocSpace objects, 4(80KB) LOS objects, 49% free, 4MB/8MB, paused 5.036ms total 42.904ms
I/SystemUpdateService( 4568): active receiver: disabled
I/ConfigFetchService( 4568): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,V/AuthZen ( 4568): Handling intent: android.intent.action.BOOT_COMPLETED,
,D/AuthZenEventHandler( 4568): Handling event: android.intent.action.BOOT_COMPLETED
,D/PMS     (  951): acquireWL(1921efac): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,I/art     ( 1811): Explicit concurrent mark sweep GC freed 23037(1390KB) AllocSpace objects, 4(80KB) LOS objects, 46% free, 4MB/8MB, paused 3.529ms total 65.054ms,
I/ConfigFetchService( 4568): service connected
I/GLSUser ( 4568): [ChannelManager] Attempting to channel bind connection HttpClient.
I/ActivityManager(  951): Resuming delayed broadcast
,D/PMS     (  951): releaseWL(36fc1aab): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(1921efac): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(1027c0aa): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 7060(422KB) AllocSpace objects, 4(80KB) LOS objects, 50% free, 3MB/7MB, paused 1.347ms total 48.966ms
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 4568): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true,
D/PMS     (  951): releaseWL(1cfeef7f): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4568): onDestroy
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1811, uid=10024, userID:0
,I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4666 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,D/ConfigFetchService( 4568): ConfigApi connection successful.
,I/AuthZen ( 4568): Fetching signing key...,
,I/GLSActivity( 1908): [ac] getting account id
W/ResourcesManager( 4666): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AuthZen ( 4568): Signing key fetched successfully!
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,I/GLSUser ( 1908): [ChannelManager] Attempting to channel bind connection HttpClient.,
I/GLSUser ( 1908): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/AuthZen ( 4568): Starting Enrollment...
,D/AuthZen ( 4568): getting auth token. Attempt 0
,I/GLSUser ( 1908): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AuthZen ( 4568): Error getting auth token
E/AuthZen ( 4568): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256),
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4568): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4568): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4568): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207),
E/AuthZen ( 4568): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4568): 	,at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4568): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4568): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4568): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4568): Initialized cache in: /data/data/com.google.android.gms/files,
D/AuthZenTransactionCache( 4568): Clearing transaction cache
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=22 rxSum=16} preTxRxSum={txSum=22 rxSum=16}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActionCombine( 1908): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,W/ResourcesManager( 1219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1302): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1302): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): apply : com.google.android.gms 0 9 4 40
,W/Kids    ( 4568): [AccountUtils] Account not ready,
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:2990] from screen [on:0 period:828881786] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828881787] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/GCoreUlr( 1811): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  951): acquireWL(325104f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(325104f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1811): Unbound from all location providers
,D/PMS     (  951): releaseWL(2b5b47e4): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.32 txretriesrate=0.00 rxrate=5.76 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
,E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  951): handleMessage: X
,I/GCoreUlr( 1811): DispatchingService.onDestroy()
,D/PMS     (  951): acquireWL(2bd2ddd1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2bd2ddd1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1811): Unbound from all location providers
,D/PMS     (  951): acquireWL(1c56860d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
,D/PMS     (  951): acquireWL(28bd39c2): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 951 1000 WorkSource{10024}
,I/IntentController( 1219): receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
D/PMS     (  951): releaseWL(1c56860d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/PMS     (  951): acquireWL(2401ea2f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
,D/PMS     (  951): releaseWL(2401ea2f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4666): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4666): MmsConfig.loadMmsSettings
D/MmsCustomizationProvider( 4010): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/MmsCustomizationProvider( 4010): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4666): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 4666): MmsConfig.loadFromDatabase
,D/PhoneStatusBar( 1219): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4666, uid=10112, userID:0
,E/Babel_SMS( 4666): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4666): MmsConfig.loadFromResources
,E/Babel_SMS( 4666): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4666): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 4666): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 4666): startup - clean,
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{175d981e u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/Babel   ( 4666): deleted: false for 0,
,D/PMS     (  951): acquireWL(18020c7d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null,
,D/PMS     (  951): releaseWL(28bd39c2): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
D/PMS     (  951): releaseWL(18020c7d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
I/IntentController( 1219): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=69
E/WifiTrafficPoller(  951): notifying of data activity 0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4666, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4666, uid=10112, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4666, uid=10112, userID:0
,W/VideoCapabilities( 4666): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4666): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4666): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 4666): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4666): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4666): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4666): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 4666): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4666): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4666): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4666): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4666): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 4666): onServiceConnected
,W/Babel   ( 4666): Attempted to change video mute state without an active call.
,I/ActivityManager(  951): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4705 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 3 times.
,W/ResourcesManager( 4705): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4705): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4705): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4705): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4705): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 4705): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4705): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/cutils-trace( 4737): Error opening trace file: Permission denied (13),
,I/dex2oat ( 4737): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1449191283.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads1449191283.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4737): dex2oat: override thread count:4
,E/YouTube MDX( 4705): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 4705): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4705): [NET] android_getaddrinfofornet-, SUCCESS
,I/dex2oat ( 4737): dex2oat took 45.729ms (threads: 4),
,D/VoldConnector(  951): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,W/art     ( 4705): Suspending all threads took: 11.348ms,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  951):  packet count Tx=35 Rx=69
,D/VoldConnector(  951): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  951): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
D/VoldConnector(  951): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4705): Found 10024,
,D/VoldConnector(  951): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4705): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  951): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4785 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 4705): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 4705): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4705): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4705): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4705): [NET] android_getaddrinfo_proxy+
D/libc    ( 4705): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  392): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  951): Killing 4126:com.htc.feedback/u0a83 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=4126
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4705): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4705): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 4705): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  951): Recipient 4126,
,D/libc    ( 4705): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 4705): [NET] android_getaddrinfofornet-, err=8
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/Gmail   ( 4785): getAccountsCursor,
,V/AlarmManager(  951): sending alarm PendingIntent{308787cd: PendingIntentRecord{aa37882 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=53943, Int=259200000,
V/AlarmManager(  951): sending alarm PendingIntent{daab7d0: PendingIntentRecord{1091d3c9 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452527829891, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{320d0527: PendingIntentRecord{2a4743d4 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452527822903, Int=20000
,I/art     (  951): Explicit concurrent mark sweep GC freed 19206(1066KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 16MB/24MB, paused 1.323ms total 168.767ms,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4785, uid=10106, userID:0
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 4785): Observing account changes for notifications
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4785, uid=10106, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4785, uid=10106, userID:0
,W/GAV2    ( 4785): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/iu.UploadsManager( 4568): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/iu.UploadsManager( 4568): End new media; added: 0, uploading: 0, time: 32 ms
,E/Gmail   ( 4785): Error finding the version of the Email provider.....,
E/Gmail   ( 4785): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4785): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4785): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4785): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4785): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4785): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4785): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4785): We do not support migrating this version of the Email provider.
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4785, uid=10106, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4785, uid=10106, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4785, uid=10106, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4785, uid=10106, userID:0
,I/Gmail   ( 4785): getAccountsCursor
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  951): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4832 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4785, uid=10106, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4785, uid=10106, userID:0
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4785): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@15a3d00e that was originally bound here
E/ActivityThread( 4785): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@15a3d00e that was originally bound here
E/ActivityThread( 4785): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4785): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4785): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4785): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4785): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4785): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4785): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4785): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4785): ,	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4785): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4785): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4785): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4785): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4785): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4785): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  951): Unbind failed: could not find connection for android.os.BinderProxy@32432418
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  951):  packet count Tx=48 Rx=84
D/WIFI_ICON( 1219): WifiActivity: 3
E/WifiTrafficPoller(  951): notifying of data activity 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/SQLiteLog( 4785): (283) recovered 997 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/Gmail   ( 4785): notifyAccountChanged
,I/Gmail   ( 4785): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4785): getAccountsCursor
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4785): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  951): acquireWL(14ee5e30): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4785 10106 null
,I/Gmail   ( 4785): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  951): acquireWL(14ee5e30): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4785 10106 null,
,I/Gmail   ( 4785): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  951): acquireWL(14ee5e30): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4785 10106 null
,I/Gmail   ( 4785): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4785): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) },
I/Gmail   ( 4785): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4785, uid=10106, userID:0
,D/Process (  951): killProcessQuiet, pid=4148
I/ActivityManager(  951): Killing 4148:com.htc.updater/u0a84 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 4148
,D/LocationManagerService(  951): getProviders()=[passive]
,E/AndroidHttpClient( 4505): Leak found,
E/AndroidHttpClient( 4505): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4505): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4505): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4505): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4505): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4505): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4505): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4505): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951),
E/AndroidHttpClient( 4505): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4505): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4505): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4505): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4505): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4505): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4505): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Gmail   ( 4785): master sync=false, engine sync=true
,I/ActivityManager(  951): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4863 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/Gmail   ( 4785): getAccountsCursor
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4832, uid=10085, userID:0,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4832, uid=10085, userID:0,
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4832, uid=10085, userID:0
,I/Gmail   ( 4785): master sync=false, engine sync=true
,E/WifiTrafficPoller(  951): ADD_CLIENT: 6,
D/WifiService(  951): New client listening to asynchronous messages
W/BroadcastQueue(  951): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  951): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4900 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  951): killProcessQuiet, pid=4173
I/ActivityManager(  951): Killing 4173:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828884806] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828884807] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=7 [13][1][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.66 txretriesrate=0.00 rxrate=10.38 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,I/ActivityManager(  951): Recipient 4173,
,E/WifiStateMachine(  951): handleMessage: X
,I/ActivityManager(  951): Killing 4214:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4214
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  951):  packet count Tx=48 Rx=84
E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  951): Recipient 4214
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3,
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4900): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4900): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4900): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  951): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4927 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0,
,W/ResourcesManager( 4927): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4927): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4900): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4900): [NET] android_getaddrinfofornet-, SUCCESS
,I/MultiDex( 4927): VM with version 2.1.0 has multidex support
I/MultiDex( 4927): install
,I/MultiDex( 4927): VM has multidex support, MultiDex support library is disabled.
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
,D/AccFlag ( 1431): sku_id=118
,I/ActivityManager(  951): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4956 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/LocationInitializer( 4568): Restart initialization of location
,D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4900): [NET] android_getaddrinfofornet-, err=8
I/art     (  404): Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 164us total 18.879ms
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1431): sku_id=118
,V/JNIHelp ( 4927): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 17.496ms
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1431): sku_id=118
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 155us total 17.544ms
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 73
D/AccFlag ( 1431): sku_id=118
,W/ActivityThread( 4927): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4927): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4927): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4927): callingUid 10024, callindPid: 4927
,E/MDM     ( 1811): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
W/Search.LoginHelper( 4832): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow,
W/Search.LoginHelper( 4832): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4832): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4832): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4832): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4832): ,	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4832): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4832): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4832): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4832): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4832): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4832): 	at java.lang.Thread.run(Thread.java:818),
W/Search.LoginHelper( 4832): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4832): Failed to get auth token
,I/art     (  951): Explicit concurrent mark sweep GC freed 10949(533KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/24MB, paused 1.414ms total 159.369ms
,D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4900): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4900): [NET] android_getaddrinfo_proxy+
D/libc    ( 4900): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  392): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/MusicStore( 4956): Database version: 120,
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4900): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4900): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
,D/libc    ( 4900): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  951): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 4956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  951): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  951): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,W/ContextImpl( 4956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=79 Rx=123
E/WifiTrafficPoller(  951): notifying of data activity 3
,D/WIFI_ICON( 1219): WifiActivity: 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/ResourcesManager( 4956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4956): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@327fee2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 4956): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 4956): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4956): GMSCore installation verified
,I/ConfigStore( 4956): Config Database version: 1,
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 14829(853KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 1.164ms total 56.684ms
,D/PMS     (  951): releaseWL(14ee5e30): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4956, uid=10159, userID:0,
,D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,D/MediaRouterService(  951): Client com.google.android.music (pid 4956): Registered,
,D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,I/MediaRouter( 4956): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 4956): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 4956): type=WIFI subType= reason=null isConnected=true,
,D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC <<
,I/NetworkMonitor( 4956): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  951): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4994 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4956, uid=10159, userID:0
,I/GHttpClientFactory( 4956): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 4956): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 4994): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Process (  951): killProcessQuiet, pid=4315,
I/ActivityManager(  951): Killing 4315:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=66 rxSum=67} preTxRxSum={txSum=22 rxSum=16}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  951): Recipient 4315,
,I/CalendarProvider2( 4994): Created com.android.providers.calendar.CalendarAlarmManager@3edb4ed6(com.htc.providers.calendar.HtcCalendarProvider@24e9f557)
,D/CalendarProvider2( 4994): wait start:true
,D/CalendarProvider2( 4994): wait end:false
D/AutoSetting( 1565): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5023 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/AutoSetting( 1565): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1565): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1565): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1565): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1565): service - handleMessage() setting current location null
,D/PhoneMonitor( 5023): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5023): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 5023): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Process (  951): killProcessQuiet, pid=4343
I/ActivityManager(  951): Killing 4343:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5023): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5023): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  951): Recipient 4343
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=82 Rx=126
,D/PMS     (  951): acquireWL(2910835a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(2d9a1a68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): releaseWL(2910835a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4568): Checking schedule, now: 1452527833183 next: 1452527662288,
I/CheckinService( 4568): active receiver: enabled
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/CheckinService( 4568): Preparing to send checkin request
,I/EventLogService( 4568): Accumulating logs since 1452527630069
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0,
,I/iu.SyncManager( 4568): SYNC; picasa accounts,
,D/Process (  951): killProcessQuiet, pid=4414,
I/ActivityManager(  951): Killing 4414:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/NetworkLogImpl( 4568): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4568): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,I/ActivityManager(  951): Recipient 4414
,I/iu.UploadsManager( 4568): num queued entries: 0
,I/iu.UploadsManager( 4568): num updated entries: 0
,I/iu.SyncManager( 4568): NEXT; no task
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 4 times.
,I/CheckinRequestBuilder( 4568): Checkin reason type: 8 attempt count: 1,
,D/WifiService(  951): New client listening to asynchronous messages
E/WifiTrafficPoller(  951): ADD_CLIENT: 7
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings,
,E/ActivityThread( 4568): Failed to find provider info for com.google.android.wearable.settings,
,I/art     ( 4568): Explicit concurrent mark sweep GC freed 23880(1830KB) AllocSpace objects, 23(460KB) LOS objects, 47% free, 4MB/8MB, paused 10.042ms total 101.426ms
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  951): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5055 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 4666): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 4666): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4666): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4666): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 4666): [NET] android_getaddrinfo_proxy+
D/libc    ( 4666): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    ( 4666): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4568): [AccountUtils] Account not ready
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 4666): connection state changed from UNKNOWN to CONNECTED
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{3c25410a u0 com.htc.HTCSpeaker/.NGFService},
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4568): awaiting user notification for token,
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,I/CalendarProvider2( 4994): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4994): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
D/Process (  951): killProcessQuiet, pid=4435
I/ActivityManager(  951): Killing 4435:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:2807] from screen [on:0 period:828887827] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828887828] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=10 [40][4][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=23.33 txretriesrate=0.00 rxrate=29.69 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,I/ActivityManager(  951): Recipient 4435,
,E/WifiStateMachine(  951): handleMessage: X
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/VoldConnector(  951): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  951): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  951): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5084 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/GAv4    ( 5055): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5055):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5055):   adb logcat -s GAv4
D/VoldConnector(  951): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,D/VoldConnector(  951): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5055): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5055): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 5084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 5055): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 5084): VM with version 2.1.0 has multidex support,
I/MultiDex( 5084): install
I/MultiDex( 5084): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 5055): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,V/JNIHelp ( 5084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=88 Rx=133,
,I/ActivityManager(  951): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5111 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  951): sending alarm PendingIntent{8aabedc: PendingIntentRecord{31027be5 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59943, Int=0
,W/ActivityThread( 5084): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5084): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
,I/ProviderInstaller( 5084): Installed default security provider GmsCore_OpenSSL
,W/global  ( 5055): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5055): [apache-http] Connection GC has been deprecated!,
,I/ActivityManager(  951): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5145 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/WebViewFactory( 5055): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/WVCdm   (  398): CdmEngine::OpenSession,
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
,I/LibraryLoader( 5055): Time to load native libraries: 2 ms (timestamps 200-202),
I/LibraryLoader( 5055): Expected native library version number "",actual native library version number ""
,W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,V/WebViewChromiumFactoryProvider( 5055): Binding Chromium to main looper Looper (main, tid 1) {37b52c3b},
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  398): Service_Initialize: starts!
I/LibraryLoader( 5055): Expected native library version number "",actual native library version number ""
I/chromium( 5055): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE,
E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
,I/BrowserStartupController( 5055): Initializing chromium process, singleProcess=true
,W/art     ( 5055): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5055): ApplicationContext is null in ApplicationStatus
,D/MdScBootUi( 5111): [c0a.1.2.] boot 118
,D/MdScBoot( 5111): [c0a.1.] 30@-155644 -> 40
,D/QSEECOMAPI: (  398): Loaded image: APP id = 6
D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9f000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9f000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/MdScSimSt( 5111): [c0a.1.2.] qry 118: 0+1 running 0
,D/DrmLibTime(  481): got the req here! ret=0
D/DrmLibTime(  481): command id, time_cmd_id = 770
D/DrmLibTime(  481): time_getutcsec starts!
D/DrmLibTime(  481): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  481): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  481): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  481): QSEE Time Listener: Checking if ATS_MODEM is set or not.,
E/QC-time-services(  481): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  481): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  481): QSEE Time Listener: Retrieved Android system time: 1452527834
D/DrmLibTime(  481): time_getutcsec returns 0, sec = 1452527834; nsec = 0
D/DrmLibTime(  481): time_getutcsec finished! 
D/DrmLibTime(  481): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  481): before calling ioctl to read the next time_cmd
E/QC-time-services(  424): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/chromium( 5055): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5055): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5055): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5055): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5055): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5055): Local Branch: 
I/Adreno-EGL( 5055): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5055): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5055):                  d74aa161a12b9c6fc6332151
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xf3de3928
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab531828, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e7050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab53f068, idLength=0xffdb2118
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xffdb212e, maximum = 0xffdb212f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
,D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffdb219c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=2196296901
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab5423c8
D/DrmWidevineDash(  398): message_length=1611, signature=0xab53d0c0, signature_length=0xffdb20fc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/NSApplication( 5055): Starting up...,
,W/AudioManagerAndroid( 5055): Requires BLUETOOTH permission
,I/ActivityManager(  951): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5191 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  951): killProcessQuiet, pid=4460
I/ActivityManager(  951): Killing 4460:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  398): CdmEngine::CloseSession
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  951): Recipient 4460
,I/ActivityManager(  951): Killing 4262:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4262
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  951): Recipient 4262,
,D/Process (  951): killProcessQuiet, pid=4483
I/ActivityManager(  951): Killing 4483:com.android.smith/1000 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 4483,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=88 Rx=134
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951): notifying of data activity 1,
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/art     (  951): Explicit concurrent mark sweep GC freed 14435(755KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 16MB/24MB, paused 1.854ms total 180.775ms
I/art     (  951): WaitForGcToComplete blocked for 181.545ms for cause HeapTrim
,I/GAV2    ( 4785): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5217 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  951): killProcessQuiet, pid=4392
I/ActivityManager(  951): Killing 4392:com.android.settings/1000 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,E/cutils-trace( 5230): Error opening trace file: Permission denied (13),
I/dex2oat ( 5230): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5230): dex2oat: override thread count:4
,I/ActivityManager(  951): Recipient 4392
,I/GAv4-SVC( 4568): Google Analytics 7.8.99 is starting up.,
,I/dex2oat ( 5230): dex2oat took 81.720ms (threads: 4)
,W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/Adreno-EGL( 5084): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5084): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5084): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5084): Local Branch: 
I/Adreno-EGL( 5084): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5084): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5084):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 5084): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5084): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5084): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5084): Local Branch: 
I/Adreno-EGL( 5084): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5084): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5084):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  398): CdmEngine::OpenSession,
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  398): Service_Initialize: starts!
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
,D/QSEECOMAPI: (  398): Loaded image: APP id = 7
,D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9f000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9f000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  481): got the req here! ret=0,
D/DrmLibTime(  481): command id, time_cmd_id = 770
D/DrmLibTime(  481): time_getutcsec starts!
D/DrmLibTime(  481): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  481): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  481): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  481): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  481): Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
D/DrmLibTime(  481): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  481): QSEE Time Listener: Retrieved Android system time: 1452527835
D/DrmLibTime(  481): time_getutcsec returns 0, sec = 1452527835; nsec = 0
D/DrmLibTime(  481): time_getutcsec finished! 
D/DrmLibTime(  481): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  481): before calling ioctl to read the next time_cmd
E/QC-time-services(  424): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xf3de3928
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab5432d8, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e7050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab53f0a8, idLength=0xf4fc86f8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24,
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4fc870e, maximum = 0xf4fc870f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4fc877c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=2745439591
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab53caf8
D/DrmWidevineDash(  398): message_length=1646, signature=0xab544208, signature_length=0xf4fc86dc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0,
,I/WVCdm   (  398): CdmEngine::CloseSession
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  951): Killing 4542:com.google.android.gms:car/u0a24 (adj 15): empty #17,
D/Process (  951): killProcessQuiet, pid=4542
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/CheckinRequestBuilder( 4568): Classify the device as Phone.
,I/ActivityManager(  951): Recipient 4542
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=91 Rx=136
D/WIFI_ICON( 1219): WifiActivity: 3
E/WifiTrafficPoller(  951): notifying of data activity 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  951): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5262 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4568): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 4568): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4568): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4568): [NET] android_getaddrinfo_proxy-, success
,I/ImageRamCache( 5262): create image Cache, size: 31457280.,
I/ImageRamCache( 5262): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5262): create image Cache, size: 31457280.,
,I/FeedSettings( 5262): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 5262): GroupBudget 0.500000 0.380000
I/FeedSettings( 5262): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5262): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5262): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5262): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 5262): [custom highlight] onReceive,
,D/CustomHighlightService( 5262): [custom highlight] onHandleIntent,
,D/NewsDB  ( 5262): set custom highlight []
,I/ActivityManager(  951): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5291 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,D/CustomHighlightService( 5262): [custom highlight] set tags 
,I/ActivityManager(  951): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5313 uid=10076 gids={50076, 9997} abi=arm64-v8a
I/ActivityManager(  951): Killing 4505:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4505
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4568): Sending checkin request (8522 bytes),
,I/ActivityManager(  951): Recipient 4505
,D/Process (  951): killProcessQuiet, pid=4010,
I/ActivityManager(  951): Killing 4010:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 4010,
,D/Process (  951): killProcessQuiet, pid=4705
I/ActivityManager(  951): Killing 4705:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=23.3, 0.0, 0.0  rx=29.7 bcn=0 [on:0 tx:0 rx:0 period:2903] from screen [on:0 period:828890837] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=23.3, 0.0, 0.0  rx=29.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828890838] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=8 [25][2][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=24.16 txretriesrate=0.00 rxrate=25.34 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,I/SocialFeedProvider( 1483): +disConnect socialManager
I/SocialFeedProvider( 1483): disconnect socialManager
,I/ActivityManager(  951): Recipient 4705
,E/WifiStateMachine(  951): handleMessage: X
,I/SocialFeedProvider( 1483): -disConnect socialManager
,D/SMSBackup( 5313): Got a database change event,
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
V/AlarmManager(  951): sending alarm PendingIntent{1d0aa3be: PendingIntentRecord{3e5fcc1f com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452527836996, Int=0
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SocialManager[SocialBiLogHelper]( 5262): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5262): last commit ulog time 1452491432917
I/SocialManager[SocialBiLogHelper]( 5262): skip commit this time
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
I/CheckinRequestBuilder( 4568): Checkin reason type: 8 attempt count: 1
E/WifiTrafficPoller(  951):  packet count Tx=114 Rx=157
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4568): Failed to find provider info for com.google.android.wearable.settings
,D/Process (  951): killProcessQuiet, pid=4785,
I/ActivityManager(  951): Killing 4785:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1565): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1483): action: android.intent.action.PACKAGE_ADDED,
,I/ActivityManager(  951): Recipient 4785
,I/ActivityManager(  951): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5340 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  404): Explicit concurrent mark sweep GC freed 8614(365KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 297us total 32.092ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 205us total 23.242ms,
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 181us total 23.743ms
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4568, uid=10024, userID:0,
I/DeviceManagement( 5340): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5340 dbg=false s=true
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/DeviceManagement( 5340): PackageUpdateReceiver: vvv Package added: [com.example.hello]
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4568, uid=10024, userID:0
D/Process (  951): killProcessQuiet, pid=4832
I/ActivityManager(  951): Killing 4832:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 9645(503KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 747us total 50.253ms,
,I/ActivityManager(  951): Recipient 4832
,D/WifiService(  951): Client connection lost with reason: 4
,W/SystemReader(  951): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1724): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/ResourcesManager( 1431): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5363 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/ResourcesManager(  951): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/Prism.AllAppsManager( 1483): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1724): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Launcher( 1483): Deferring update until onResume,
D/Launcher( 1483): waitUntilResume // bindAppsUpdated
I/Prism.ItemManager( 5262): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5262): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PhoneApp( 1431): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/HtcCupdReceiver(Provider)( 5363):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/Process (  951): killProcessQuiet, pid=4900,
I/ActivityManager(  951): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5384 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  951): Killing 4900:com.htc.club/u0a181 (adj 15): empty #17
,W/PackageManager(  951): Unable to load service info ResolveInfo{3d332fcc com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  951): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  951): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  951): 	at android.os.Handler.handleCallback(Handler.java:739),
W/PackageManager(  951): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  951): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/AccTypeManager( 1724): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1724): Unsupported attribute readOnly,
,I/ActivityManager(  951): Recipient 4900
,I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=96 rxSum=90} preTxRxSum={txSum=66 rxSum=67}
,D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5384): -onCreate(),
,V/GmsNetworkLocationProvi( 1811): DISABLE
,I/GCoreNlp( 1811): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationProviderProxy(  951): applying state to connected service
V/Settings:HtcSettingsApplication( 5384): [5384/5384] onCreate(),
D/PMS     (  951): acquireWL(37291797): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=114 Rx=160
E/WifiTrafficPoller(  951): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/PMS     (  951): releaseWL(37291797): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5408 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  951): killProcessQuiet, pid=4956
I/ActivityManager(  951): Killing 4956:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PMS     (  951): acquireWL(17793d84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null,
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(17793d84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Settings:HtcWirelessFeatureFlags( 5384): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 5384): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5384): The wrap header doesn't exist in header list.
,I/ActivityManager(  951): Recipient 4956
,D/MediaRouterService(  951): Client com.google.android.music (pid 4956): Died!,
,E/Settings:HtcWrapHeaderInfo( 5384): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 5384): isSupportMusicChannel(): false,
,D/HtcPowerSaver(  951): updateBatteryInfo
,D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NotificationService(  951): plugged=true pluggin=true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]support         :false
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/PMS     (  951): runPSCheck
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  951): >> updateStatus
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): handleMessage: E msg.what=155652
D/PMS     (  951): acquireWL(775996d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/LocationProviderProxy(  951): applying state to connected service
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  951): << updateStatus
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]support         :false
D/PMS     (  951): releaseWL(775996d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(191fb9a2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(125d9633): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(191fb9a2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(125d9633): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/CheckinRequestBuilder( 4568): awaiting user notification for token
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5384): isSupportVoWifi: null
E/ActivityThread( 5384): Failed to find provider info for com.htc.vowifi
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5384): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 5384): updateDevelopment, bPrefShow = true
,I/CheckinRequestBuilder( 4568): Classify the device as Phone.
,E/Settings:HtcUmcWidgetEnabler( 5384): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasBackKey      :false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5384): [supportHomeButton]support         :false
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5384): isSupportVoWifi: null,
,E/ActivityThread( 5384): Failed to find provider info for com.htc.vowifi
,I/CheckinTask( 4568): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5408, uid=10072, userID:0
,I/CheckinService( 4568): Checking schedule, now: 1452527838494 next: 1453064670487
,I/CheckinService( 4568): active receiver: disabled
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,W/global  ( 5408): [apache-http] Connection GC has been deprecated!
,D/PMS     (  951): releaseWL(2d9a1a68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5408): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5408): [apache-http] Connection GC has been deprecated!,
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 5 times.,
,W/global  ( 5408): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5408): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  951): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5451 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5408): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 5408): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5408, uid=10072, userID:0,
,W/ResourcesManager( 5451): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5451): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Killing 4994:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=4994
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/MultiDex( 5451): VM with version 2.1.0 has multidex support,
I/MultiDex( 5451): install
I/MultiDex( 5451): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  951): Recipient 4994,
,D/Finsky  ( 5408): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5408): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5408): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4568): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4568): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,V/JNIHelp ( 5451): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  951): acquireWL(3a3cb7dd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4568 10024 null
,D/Finsky  ( 5408): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 5451): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5451): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5451): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  951):  packet count Tx=114 Rx=162
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 +
I/Prism.WidgetManager( 1483): onLoadItems() +
,I/Prism.ItemManager( 5262): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 5262): loadItems() com.htc.launcher.pageview.WidgetManager@30ca0a6b +
I/Prism.WidgetManager( 5262): onLoadItems() +
,W/ResourcesManager( 1483): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ConfigFetchService( 4568): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  951): acquireWL(18d1f4d9): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4568 10024 WorkSource{10374 com.example.hello}
I/ConfigFetchService( 4568): launchTask
D/PMS     (  951): releaseWL(3a3cb7dd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  951): acquireWL(1fe40595): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4568): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,I/PeopleContactsSync( 4568): CP2 sync disabled
V/ConfigFetchTask( 4568): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WSP9mPlJ-oipAavmISvpQfZbxxtPuVkONpWQS5H2-UWhXOF9VeitlsLnuIrq9GE5cfcimUGACRP9Jp_8NJKBvEJeMClHQ3a3f_aN-5oGXsfSQb_CGbqT5vrIjUMb1Y4tWK4DxhZW8OshcDLsxkRu9DpaW_jI8425_bi_K1hZ-wjL15qMpmFr3KnyYGHQ4edHaUPwI9XlcscF0XanLJje5aGQ-iKXezLb0CQQ3fiJlCW36kK30aA82d9TWpJS81i8vVbIFD7h9xLZYCMxKKmc33Cg82lshSI-JmiPbLJnCKzjQcCdo
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4568, uid=10024, userID:0
I/GoogleURLConnFactory( 4568): Using platform SSLCertificateSocketFactory
,D/Vision  ( 4568): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4568): Failed to find package metadata for com.example.hello
D/Vision  ( 4568): No vision deps
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4568): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4568): [NET] android_getaddrinfo_proxy+
D/libc    ( 4568): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4568): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  951): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5490 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/Icing   ( 4568): Storage manager: low false usage 1.77MB avail 5.82GB capacity 7.95GB
,W/Icing   ( 4568): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4568): Received bad json for corpus context scoring override -- ignoring.,
,W/Icing   ( 4568): Received bad json for section weights override -- ignoring.
W/Icing   ( 4568): Received bad json for corpus context scoring override -- ignoring.
,D/Process (  951): killProcessQuiet, pid=5023,
I/ActivityManager(  951): Killing 5023:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,W/ResourcesManager( 1483): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ConfigFetchService( 4568): fetch service done; releasing wakelock
I/ConfigFetchService( 4568): stopping self
D/PMS     (  951): releaseWL(18d1f4d9): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
,I/ActivityManager(  951): Recipient 5023
,V/Finsky  ( 5408): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ResourcesManager( 5262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1483): Copying FileAsset 0x55af393c70 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/Finsky  ( 5408): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  951): sending alarm PendingIntent{1246d376: PendingIntentRecord{1fda2d77 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527839626, Int=0
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Prism.WidgetManager( 1483): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1483): onLoadItems() -
I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 -
,I/art     (  951): Explicit concurrent mark sweep GC freed 26513(1454KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 1.553ms total 159.954ms
,D/PhoneApp( 1431): EVENT_QUERY_MO_PACKAGES,
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,D/PhoneApp( 1431): -- N1 =0
,D/PhoneApp( 1431): -- N2 =0,
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/PhoneApp( 1431): -- N3 =0
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
W/asset   ( 5262): Copying FileAsset 0x55af0375a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5408): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Icing   ( 4568): Loading extension by file descriptor -1 failed
W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,I/Prism.WidgetManager( 5262): onLoadItems() -
,I/Prism.ItemManager( 5262): loadItems() com.htc.launcher.pageview.WidgetManager@30ca0a6b -
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/BaseAppContext( 4568): Using Auth Proxy for data requests.
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5408): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
,E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=24.2, 0.0, 0.0  rx=25.3 bcn=0 [on:0 tx:0 rx:0 period:2834] from screen [on:0 period:828893861] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=24.2, 0.0, 0.0  rx=25.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828893863] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1362): environment dirty rate=0 [13][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=18.58 txretriesrate=0.00 rxrate=22.17 userTriggerdPenalty0,
E/WifiStateMachine(  951):  good link -> stuck count =0
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  951): handleMessage: X
,I/Icing   ( 4568): updateResources: need to parse f{com.google.android.gms}
,I/GAv4    ( 5490): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5490):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5490):   adb logcat -s GAv4
,E/AndroidHttpClient( 5408): Leak found,
E/AndroidHttpClient( 5408): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5408): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5408): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5408): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5408): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5408): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5408): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5408): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5408): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5408): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5408): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5408): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5408): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5408): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5408): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5408): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,W/GAv4    ( 5490): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5490): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5490): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/Icing   ( 4568): Internal init done: storage state 0
,I/Icing   ( 4568): Post-init done
,D/PMS     (  951): releaseWL(1fe40595): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/AnalyticsTrackerProxyImpl( 5490): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,W/art     ( 5490): Suspending all threads took: 6.116ms
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=126 Rx=174
E/WifiTrafficPoller(  951): notifying of data activity 3
D/WIFI_ICON( 1219): WifiActivity: 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T],
,D/VoldConnector(  951): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5490): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  951): acquireWL(ff3b64f): PARTIAL_WAKE_LOCK  AsyncService 0x1 5217 10167 null
,D/PMS     (  951): acquireWL(367b62e5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5217 10167 null
,D/PMS     (  951): releaseWL(ff3b64f): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/ResourcesManager( 5490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 5490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
I/ActivityManager(  951): Waited long enough for: ServiceRecord{177ce6bc u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService}
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 13104(727KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 767us total 37.985ms
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  951): releaseWL(367b62e5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4568): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  951): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5540 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,W/Finsky  ( 5408): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5408): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5408): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/System  ( 5490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5490): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 5408): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,E/WifiStateMachine(  951): handleMessage: E msg.what=131165
,E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
E/WifiStateMachine(  951): processMsg: DefaultState
E/WifiStateMachine(  951):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  951): handleMessage: X
,D/Process (  951): killProcessQuiet, pid=4666,
I/ActivityManager(  951): Killing 4666:com.google.android.talk/u0a112 (adj 15): empty #17,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1811): client connected with version: 7571000
,I/ActivityManager(  951): Recipient 4666
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  951): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5569 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/HtcWrapAdjustableCursorFactory( 5569): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5569): onCreate
,V/GetPrviateResource( 5569): GetPrviateResource
,V/GetPrviateResource( 5569): GetPrviateResource
,D/MessageCustFlag( 5569): sense_version=6.0
,D/BTAccessoryUtil( 5569): createReceiver
,D/BTAccessoryUtil( 5569): registerReceiver return intent = null
,D/MessageCustFlag( 5569): sku_id=118,
,D/HtcBuildUtils( 5569): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5569): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 5569): packageName: com.htc.vvm.att does not exist,
D/MessageCustFlag( 5569): sku_id=118,
,D/MessagingShortcutReceiver( 5569): keep hiding shortcut bubble,
,D/LocationManagerService(  951): getProviders()=[passive]
,D/MessagingShortcut( 5569): updateMsgShortcut, msg count> -1,
,D/SettingsManager( 5569): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@24e9f557
,D/MessagingShortcut( 5569): After query: 0
D/MessagingShortcut( 5569): mPresentUnreadCount: -1
,D/MessageUtils( 5569): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 5569): setMsgShortcutDrawable> 0, false,
,D/MessagingShortcut( 5569): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1302): [EventService] reorderNotification, total:0,
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  951): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5601 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  951): Killing 5055:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=5055
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  951): Recipient 5055
,I/UpdateIcingCorporaServi( 5540): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Process (  951): killProcessQuiet, pid=5145,
I/ActivityManager(  951): Killing 5145:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/ResourcesManager( 5601): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=177
,I/ActivityManager(  951): Recipient 5145
,I/UpdateIcingCorporaServi( 5540): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] ,
,D/Process (  951): killProcessQuiet, pid=5191,
I/ActivityManager(  951): Killing 5191:com.android.chrome/u0a96 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/TodoTaskshortcut( 5601): update TASK shortcut>
,I/ActivityManager(  951): Recipient 5191,
,I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5625 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Process (  951): killProcessQuiet, pid=5291,
I/ActivityManager(  951): Killing 5291:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5291,
,W/ResourcesManager( 5625): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/Babel_SMS( 5625): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5625): MmsConfig.loadMmsSettings,
,D/MmsCustomizationProvider( 5569): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5625, uid=10112, userID:0,
,D/MmsCustomizationProvider( 5569): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 5625): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 5625): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5625): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5625): MmsConfig.loadFromResources
,E/Babel_SMS( 5625): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5625): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 5625): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5625): startup - clean
,I/Babel   ( 5625): deleted: false for 0,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5625, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5625, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5625, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5625, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5625, uid=10112, userID:0
,W/art     ( 5625): Suspending all threads took: 16.836ms,
,W/VideoCapabilities( 5625): Unrecognized profile 2130706433 for video/avc,
,D/PMS     (  951): acquireWL(1a582e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(1b236179): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5601 10069 null,
,D/PMS     (  951): releaseWL(1a582e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
W/VideoCapabilities( 5625): Unsupported mime video/x-ms-wmv
,D/MtpReceiver( 3970): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3970): [MTP][handleUsbStateAsync]1:1-
D/PMS     (  951): acquireWL(32598ebe): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5601 10069 null
D/MtpReceiver( 3970): [MTP][handleUsbState]+
,W/Utils   ( 5625): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5625): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5625): Unsupported mime audio/x-ms-wma
,I/ActivityManager(  951): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5659 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
W/AudioCapabilities( 5625): Unsupported mime audio/qcelp
,D/MtpReceiver( 3970): [MTP][scanExternalVolumeIfNeed] scan external volume,
W/VideoCapabilities( 5625): Unsupported mime video/x-ms-wmv
D/PMS     (  951): releaseWL(1b236179): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/MtpReceiver( 3970): [MTP][handleUsbState]-
,D/MtpReceiver( 3970): [MTP][handleMessage]-
,D/MtpService( 3970): updating state; isCurrentUser=true, mMtpLocked=false
E/TodoTaskNotifyService( 5601): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 5601): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
D/PMS     (  951): releaseWL(32598ebe): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 5601): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  951): acquireWL(189bd8ca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4568 10024 null
W/System.err( 5601): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5601): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5601): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5601): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MtpDatabase( 3970): TotalSize=1886532,MediaCacheLimit=6000
W/NotifyReceiver( 5601): stopSelfResult true
,D/MtpService( 3970): [isMtpConnected] connected: true
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=180
,D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951): notifying of data activity 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/VideoCapabilities( 5625): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5625): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5625): Unrecognized profile 2130706433 for video/avc
,E/MediaScannerService( 3970): [onStartCommand] --- Should not be here, redirect request. ----
,E/MediaScannerService( 3970): [handleMessage] --- Should not be here, ignore request. ----
,W/VideoCapabilities( 5625): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5625): Unrecognized profile 2130706433 for video/avc,
,I/art     (  951): Explicit concurrent mark sweep GC freed 19018(966KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.233ms total 161.041ms
,D/Process (  951): killProcessQuiet, pid=5313
I/ActivityManager(  951): Killing 5313:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5313
,E/MediaScannerServiceEx( 3970): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3970): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/SyncApplication( 5659): Loading default preferences
,I/vclib   ( 5625): onServiceConnected
W/Babel   ( 5625): Attempted to change video mute state without an active call.
D/MediaScannerServiceEx( 3970): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3970): [update][8]#0#
,D/MediaProvider( 3970): [update][5]#0#
,W/Resources( 5659): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/iu.UploadsManager( 4568): End new media; added: 0, uploading: 0, time: 350 ms
,D/PMS     (  951): releaseWL(189bd8ca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null,
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3970): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3970): [update][19]#1#
,D/MediaScannerServiceEx( 3970): [AliveExtStorageRows]-0, 0
D/PMS     (  951): acquireWL(1b0ac6b1): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3970 10017 null
,D/MediaScanner( 3970): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,V/AlarmManager(  951): sending alarm PendingIntent{2a06b796: PendingIntentRecord{4d00f17 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=68220, Int=0
,E/WifiTrafficPoller(  951): ADD_CLIENT: 7
D/WifiService(  951): New client listening to asynchronous messages
,D/SyncApplication( 5659): Overriding preferences with custom values,
,D/SyncApplication( 5659): Updating preferences succeeded
,E/SyncApplication( 5659): Application created.
,I/CalendarDefines( 5659): getNewCalendarAuthority()...
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5659, uid=10005, userID:0,
,W/VolumeInfo( 5659): Unable to read mount points
W/VolumeInfo( 5659): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5659): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5659): ,	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5659): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5659): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5659): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5659): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5659): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5659): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5659): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5659): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5659): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5659): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5659): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5659): ,	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5659): 	... 13 more
V/VolumeInfo( 5659): Found 0 mount point(s)
W/PackageManager(  951): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 5659): New VolumeInfo with mount point /storage/emulated/0 and sys path null created,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5659, uid=10005, userID:0
W/PackageManager(  951): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5659): enableAppOperation()+
,D/SyncApplication( 5659): enableAppOperation()-
,D/VolumeInfo( 5659): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 5659): isNeorSinged() + ,
,D/VolumeInfo( 5659): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5659): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 5659): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5659): isNeorSinged() return false
,D/CDMountReceiver( 5659): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5659): USB connected to PC
,D/FOTAReceiver( 5659): onReceive() enter 
,D/FOTAReceiver( 5659): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 5384): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5384): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5384): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5384): Cust_ConnectToPC   : spcsc>false,
D/        ( 5384): Cust_ConnectToPC   : IPT>true
D/        ( 5384): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5384): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5384): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5384): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5384): usb_cable_connect = 1
,D/SmartNS_Utility( 5384): usb_denied = 0
,I/SmartNS_NSReceiver( 5384): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 5384): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5384): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
,I/SmartNS_PSService( 5384): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/SmartNS_PSService( 5384):  defaultType:0
I/SmartNS_PSService( 5384): fail notificaiton:false
D/SmartNS_Utility( 5384): usb_cable_connect = 1
D/SmartNS_Utility( 5384): usb_denied = 0
I/SmartNS_PSService( 5384): usb notificaiton:true
,E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  951): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5384): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5384): usb_cable_connect = 1,
D/SmartNS_Utility( 5384): usb_denied = 0
I/SmartNS_PSService( 5384): usb notificaiton:true
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/SmartNS_Utility( 5384): usb_cable_connect = 1,
D/SmartNS_Utility( 5384): usb_denied = 0
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
,I/SmartNS_PSService( 5384): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5384): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  951): killProcessQuiet, pid=5262
I/ActivityManager(  951): Killing 5262:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/Messaging( 5569): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 5569): networkCode: 
D/MmsConfig( 5569): SIE smsPri: null
,D/MmsConfig( 5569): networkCode: 
,D/ReportIndicatorCache( 5569): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5569): 
D/MmsAsyncWorkHandler( 5569): HM tk = 20001
D/ReportIndicatorCache( 5569): MSG_QUERY_REPORTS >>
,D/Messaging( 5569): mNeedToUpdateDate2 start
,I/Messaging( 5569): mccmnc> 
,D/DraftCache( 5569): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5569): [DraftCache/1] refresh
,D/MmsConfig( 5569): networkCode: 
,D/Messaging( 5569): ViewCache CreatePreloadOnlyConversationList,
,D/MessageCustFlag( 5569): sense_version=6.0
,D/Jerry   ( 5569): start to preload cursor >>>>>>>,
,I/ActivityManager(  951): Recipient 5262
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,W/ContextImpl( 5696): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,D/PhoneStorageUtil( 5569): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5569): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5569): createReceiver
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1431): sku_id=118
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 5569): [DraftCache/117] rebuildCache
,I/ActivityManager(  951): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5726 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/TelephUtils( 1431): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1431): Update uri=content://mms, match=0,
V/MmsProvider( 1431): selection=st=129 AND m_type!=134
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
I/ActivityManager(  951): Killing 4863:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/Process (  951): killProcessQuiet, pid=4863
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/Messaging( 5569): Reset downloading state: 0
V/MmsSystemEventReceiver( 5569): TransactionService is going to be woken up.
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
,E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=18.6, 0.0, 0.0  rx=22.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:828896870] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=18.6, 0.0, 0.0  rx=22.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828896872] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 5569): ViewCache CreatePreload
D/Messaging( 5569): ViewCache CreatePreloadOnlyMultipleOpsList
D/Messaging( 5569): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,I/wpa_supplicant( 1362): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.29 txretriesrate=0.00 rxrate=14.59 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,D/Cust_MMSMS( 5569): _has_set_default_values_2=true,
,D/MsgPreferenceUtils( 5569): def_index: 0
,I/art     ( 3970): Background sticky concurrent mark sweep GC freed 2989(158KB) AllocSpace objects, 0(0B) LOS objects, 5% free, 3MB/4MB, paused 7.622ms total 24.043ms
,I/ActivityManager(  951): Recipient 4863,
,D/MediaProvider( 3970): [update][9]#1#,
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=110 rxSum=102} preTxRxSum={txSum=96 rxSum=90}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  951): handleMessage: X
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/Jerry   ( 1431): URI_DRAFT
,D/MsgPreferenceUtils( 5569): globalIndex = 1
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/DraftCache( 5569): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5569): [DraftCache/117] rebuildCache time: 3
D/MmsAsyncWorkHandler( 5569): 
D/MmsAsyncWorkHandler( 5569): HM tk = 20002
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
V/TransactionService( 5569): 1-Creating TransactionService
,E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=180
E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MmsSmsV2Provider( 1431):  slotId = -1000
D/MmsSmsV2Provider( 1431): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5569): mNeedToUpdateDate2: false
,V/TransactionService( 5569): onStartCommand: 1
D/MmsSystemEventReceiver( 5569): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 5569): phone state: true
D/MsgPreferenceUtils( 5569): sd state: false
D/MsgPreferenceUtils( 5569): vIndex = 0
D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1431): sku_id=118
,V/TransactionService( 5569): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5569): Loading previous transactions.
,W/ResourcesManager( 5726): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1431): device_type: 1
,D/TelephUtils( 1431): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1431): sku_id=118
,D/TransactionService( 5569): Force clearing mTransactionList,
D/TransactionService( 5569): Force set service start id to 1
V/TransactionService( 5569): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5569): unRegisterForConnectionStateChanges
D/TransactionService( 5569): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5569): Destroying TransactionService
V/TransactionService( 5569): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/CalendarProvider2( 5726): Created com.android.providers.calendar.CalendarAlarmManager@3edb4ed6(com.htc.providers.calendar.HtcCalendarProvider@24e9f557)
,D/CalendarProvider2( 5726): wait start:true,
,D/FlexNetS( 5726): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 5726): wait end:false,
,I/ActivityManager(  951): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  404): Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 212us total 29.061ms,
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 22.581ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 173us total 21.436ms,
,D/Process (  951): killProcessQuiet, pid=5340,
I/ActivityManager(  951): Killing 5340:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3970): [update][7]#1#,
,I/ActivityManager(  951): Recipient 5340
,I/HtcModeClient( 3300): handler message = 4011,
,E/HtcModeClient( 3300): Check connection and retry 6 times.
,W/ContextImpl( 5768): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5768): MY_DEBUG = false
,D/PMS     (  951): acquireWL(4156e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5768 1000 null,
,I/ActivityManager(  951): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5793 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/PowerUsageService( 5768): repeat time = 1452528743705,
,D/WeatherUtility( 1565): Weather sync is On,
,D/WSP     ( 1565): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PMS     (  951): acquireWL(50f9e7): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5726 10011 null
,E/SQLiteLog( 5726): (284) automatic index on view_events(_id),
I/ActivityManager(  951): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5820 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/WeatherUtility( 5793): Weather sync is On,
,I/ActivityManager(  951): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5841 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/WeatherRequest( 5793): request cur loc, but there is no sys cur
,W/Settings( 5793): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PowerUsageList:PowerUsageHelper( 5768): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/ActionCombine( 5793): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1483): reapply : com.htc.widget.weatherclock 9 17
,D/PowerUsageList:BatterySipperExt( 5768): gen(), null == sipper.uidObj, userId = 0,
,I/EASAppSvc( 5841): [ NA ]onCreate,
,I/VersionUtil( 5841): [ NA ]setIsFOTAing: true,
,I/VersionUtil( 5841): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5841): [ NA ]setIsFOTAing: false
,D/ORMLib  ( 5601): put(),
,D/HtcAdjCursorFactory( 5841): Set CursorWindow size to: 4194304 KB, Tid: 5864,
,I/ActivityManager(  951): Killing 5363:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  951): killProcessQuiet, pid=5363
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  951): releaseWL(50f9e7): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/MediaProvider( 3970): [update][30]#1#,
,D/MediaScanner( 3970):  prescan time: 585ms
D/MediaScanner( 3970):     scan time: 1041ms
,D/MediaScanner( 3970): postscan time: 3ms
D/MediaScanner( 3970):    total time: 1629ms
D/MediaScanner( 3970): -----------------------------------------------------------------
D/MediaScanner( 3970): firstscan(media) time: 535ms
,D/MediaScanner( 3970): secondscan(non-media) time: 506ms
,D/MediaScanner( 3970):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3970):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3970):  [Total]    File(Image+Video+Audio+Others) in database : 1546,
,D/MediaProvider( 3970): [delete][14]
D/MediaProvider( 3970): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3970): [recoverParentNodes] - 0
,D/MediaProvider( 3970): [update][6]
D/MediaScannerServiceEx( 3970): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3970): [updateImage]+
,D/MediaScannerServiceEx( 3970): [updateImage]-0
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=181,
E/WifiTrafficPoller(  951): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  951): Recipient 5363
,I/CalendarProvider2( 5726): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5726): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/PMS     (  951): releaseWL(1b0ac6b1): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3970): [1] scan finished
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
I/ActivityManager(  951): Killing 4927:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/ext_sd
D/Process (  951): killProcessQuiet, pid=4927
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/WifiService(  951): New client listening to asynchronous messages
E/WifiTrafficPoller(  951): ADD_CLIENT: 8
,I/ActivityManager(  951): Recipient 4927
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+131073
,I/EASAppSvc( 5841): [ NA ]onDestroy
I/EASAppSvc( 5841): [ NA ]> uninitEASService
,I/EASRequestController( 5841): [ NA ]release,
I/EASAppSvc( 5841): [ NA ]onCreate
,I/ActivityManager(  951): Killing 5490:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=5490
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/VersionUtil( 5841): [ NA ]setIsFOTAing: true
I/VersionUtil( 5841): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5841): [ NA ]setIsFOTAing: false
D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3970): [update][11]#1#
,D/EASPublicBinder( 5841): [ NA ]release
D/TaskBinder( 5841): [ NA ]release
,D/TaskBinder( 5841): [ NA ]release
I/EASAppSvc( 5841): [ NA ]< uninitEASService
,D/ORMLib  ( 5601): put(),
,D/MediaProvider( 3970): [update][57]#0#,
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  951): Recipient 5490,
,I/ConfigService( 1908): onDestroy,
,D/MediaProviderUtils( 3970): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3970): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3970): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3970): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3970): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]+196609
,I/art     ( 3970): Background sticky concurrent mark sweep GC freed 1696(93KB) AllocSpace objects, 0(0B) LOS objects, 5% free, 3MB/4MB, paused 5.539ms total 17.920ms
,D/MediaProvider( 3970): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3970): [update][15]#1#
I/ActivityManager(  951): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5883 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/EASAppSvc( 5841): [ NA ]onDestroy
I/EASAppSvc( 5841): [ NA ]> uninitEASService
,I/ActivityManager(  951): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5898 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  951): sending alarm PendingIntent{393735c: PendingIntentRecord{8165665 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452527844747, Int=0
,I/EASRequestController( 5841): [ NA ]release,
D/EASPublicBinder( 5841): [ NA ]release
D/TaskBinder( 5841): [ NA ]release
D/TaskBinder( 5841): [ NA ]release
I/EASAppSvc( 5841): [ NA ]< uninitEASService
,D/MediaProvider( 3970): [update][54]#0#
,E/SQLiteLog( 5820): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,D/MediaScannerServiceEx( 3970): [disAliveExtStorageRows]--1, 0
,D/Process (  951): killProcessQuiet, pid=5451
I/ActivityManager(  951): Killing 5451:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  951): Explicit concurrent mark sweep GC freed 19717(966KB) AllocSpace objects, 2(552KB) LOS objects, 33% free, 16MB/24MB, paused 1.527ms total 160.924ms
,I/MusicStore( 5883): Database version: 120
,I/ActivityManager(  951): Recipient 5451,
,D/VoldConnector(  951): SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5883): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/Process (  951): killProcessQuiet, pid=5408,
,I/ActivityManager(  951): Killing 5408:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 5601): put(),
D/VoldConnector(  951): SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5883): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  951): SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5883): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 8
,E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=185
,I/ActivityManager(  951): Recipient 5408,
,W/ResourcesManager( 5883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  951): releaseWL(4156e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ActivityThread( 5883): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@327fee2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5883): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5883): GMSCore installation verified,
,I/ConfigStore( 5883): Config Database version: 1,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5883, uid=10159, userID:0,
,D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,D/MediaRouterService(  951): Client com.google.android.music (pid 5883): Registered,
,D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,I/MediaRouter( 5883): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/NetworkMonitor( 5883): type=WIFI subType= reason=null isConnected=true,
,I/ActivityManager(  951): Killing 5217:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=5217
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/TelephonyReceiver( 1431): bind: true
,I/ActivityManager(  951): Recipient 5217,
,I/ActivityManager(  951): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5947 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/GenericMessagesProvider( 5569): query uri: content://htc-messages/wappush/count,
E/SQLiteLog( 5569): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5569): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5569): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5569): DB info: errno = 2, errno message = No such file or directory,
,E/SQLiteDatabase( 5569): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5569): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5569): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5569): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5569): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
,E/SQLiteDatabase( 5569): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5569): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5569): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5569): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5569): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5569): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5569): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5569): 	at android.os.Binder.execTransact(Binder.java:454)
D/TelephonyReceiver( 1431): switchBindHtcMsgCursor: null
,I/NetworkMonitor( 5883): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5883, uid=10159, userID:0,
,I/GHttpClientFactory( 5883): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5883): Using platform SSLCertificateSocketFactory
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102,
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  951): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5974 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/Process (  951): killProcessQuiet, pid=5540
I/ActivityManager(  951): Killing 5540:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=14.6 bcn=0 [on:0 tx:0 rx:0 period:2825] from screen [on:0 period:828899893] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=14.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828899894] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.15 txretriesrate=0.00 rxrate=11.79 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
,E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
,I/ActivityManager(  951): Recipient 5540
,E/WifiStateMachine(  951): handleMessage: X,
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3,
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 8,
E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=190
,I/ActivityManager(  951): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5998 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,W/BroadcastQueue(  951): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{3f19dc1c u0 ReceiverList{36f5318f 5974 com.htc.musicenhancer/10049/u0 remote:20978ee}},
,D/VoldConnector(  951): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
,E/Vold    (  382): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
W/ContextImpl( 5974): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService,
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
,V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true,
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/ActivityManager(  951): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=6024 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService,
I/ActivityManager(  951): Killing 5111:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=5111
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5111,
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/DFPI.ApkInstallService( 5947): onHandleIntent
,I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/DFPI.ApkInstallService( 5947): onHandleIntent
,I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/TelephonyReceiver( 1431): bind: false,
,D/TelephonyReceiver( 1431): switchBindHtcMsgCursor: null
D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102,
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/ActionCombine( 6024): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1219): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.updater 0 11 2 36,
,I/ActivityManager(  951): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6059 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4568): Restart initialization of location
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ResourcesManager( 6059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0,
,D/LocationInitializer( 4568): Restart initialization of location
,I/MultiDex( 6059): VM with version 2.1.0 has multidex support
,I/MultiDex( 6059): install
I/MultiDex( 6059): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/art     (  951): Explicit concurrent mark sweep GC freed 15540(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.526ms total 138.269ms
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
W/ActivityThread( 6059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
W/System  ( 6059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6059): Installed default security provider GmsCore_OpenSSL
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/WearableService( 6059): callingUid 10024, callindPid: 6059
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/FindExtension( 1219): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/ThreadedRenderer( 1219): Defer allocateBuffers to drawing time
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/PMS     (  951): acquireWL(39fd7d11): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(39fd7d11): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/art     ( 3970): Background sticky concurrent mark sweep GC freed 196(8KB) AllocSpace objects, 0(0B) LOS objects, 3% free, 4MB/4MB, paused 6.577ms total 11.797ms
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,E/MDM     ( 1811): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  951): acquireWL(392f9e76): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,E/MDM     ( 1811): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,D/PMS     (  951): releaseWL(392f9e76): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): Soun,dPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PMS     (  951): acquireWL(cca8913): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/PMS     (  951): acquireWL(a4aa36f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 8
E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=193
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/PMS     (  951): releaseWL(a4aa36f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/PMS     (  951): releaseWL(cca8913): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6098 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,D/PhoneMonitor( 6098): Register our PhoneStateListener
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma),
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/PhoneMonitor( 6098): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PhoneMonitor( 6098): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PMS     (  951): acquireWL(301a9126): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  951): acquireWL(301e7b14): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  951): releaseWL(301a9126): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/CheckinService( 4568): Checking schedule, now: 1452527847320 next: 1452527868487,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0,
I/CheckinService( 4568): active receiver: disabled
D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  951): releaseWL(301e7b14): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  951): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6125 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4568, uid=10024, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4568, uid=10024, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4568, uid=10024, userID:0
I/CheckinService( 4568): Done disabling old GoogleServicesFramework version
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Process (  951): killProcessQuiet, pid=5084
I/ActivityManager(  951): Killing 5084:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5084
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  951): Killing 5625:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=5625
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  951): Recipient 5625
,I/ActivityManager(  951): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6148 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Kids    ( 4568): [AccountUtils] Account not ready
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1219): reapply : com.google.android.gms 4 40,
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/Gmail   ( 6148): getAccountsCursor
,I/art     (  951): Explicit concurrent mark sweep GC freed 8773(437KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/24MB, paused 1.386ms total 154.393ms
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6148, uid=10106, userID:0
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6148, uid=10106, userID:0,
I/Gmail   ( 6148): Observing account changes for notifications,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6148, uid=10106, userID:0
,W/GAV2    ( 6148): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=110 rxSum=102} preTxRxSum={txSum=110 rxSum=102}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6148): Error finding the version of the Email provider.....
E/Gmail   ( 6148): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6148): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6148): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6148): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6148): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6148): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 6148): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6148): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6148): getAccountsCursor
,I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6188 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/Process (  951): killProcessQuiet, pid=5659
I/ActivityManager(  951): Killing 5659:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 8
E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=198
,I/ActivityManager(  951): Recipient 5659
D/WifiService(  951): Client connection lost with reason: 4
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6188): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/SQLiteLog( 6148): (283) recovered 998 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 6148): notifyAccountChanged
,I/Gmail   ( 6148): calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,I/Gmail   ( 6148): getAccountsCursor,
,I/Gmail   ( 6148): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6148): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6148): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel_SMS( 6188): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6188): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 5569): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/Gmail   ( 6148): master sync=false, engine sync=true
,D/MmsCustomizationProvider( 5569): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/SystemReader(  951): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1724): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Babel_SMS( 6188): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6188): MmsConfig.loadFromDatabase,
W/Prism.AllAppsManager( 1483): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1724): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Launcher( 1483): Deferring update until onResume
D/Launcher( 1483): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  951): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Babel_SMS( 6188): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6188): MmsConfig.loadFromResources
,E/Babel_SMS( 6188): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6188): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6188, uid=10112, userID:0
,I/HtcModeClient( 3300): handler message = 4011
E/HtcModeClient( 3300): Check connection and retry 7 times.
,I/Gmail   ( 6148): getAccountsCursor
,D/PhoneApp( 1431): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AccTypeManager( 1724): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Gmail   ( 6148): master sync=false, engine sync=true
,E/ExternalAccountType( 1724): Unsupported attribute readOnly
,W/Settings( 6188): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 6188): startup - clean
,I/Babel   ( 6188): deleted: false for 0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6188, uid=10112, userID:0,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6188, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6188, uid=10112, userID:0,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6188, uid=10112, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6188, uid=10112, userID:0
W/PackageManager(  951): Unable to load service info ResolveInfo{3328b72b com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  951): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
,W/PackageManager(  951): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  951): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  951): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  951): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/PMS     (  951): acquireWL(f2f5cc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6188 10112 null
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,V/GmsNetworkLocationProvi( 1811): DISABLE
,I/GCoreNlp( 1811): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv
,I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/Utils   ( 6188): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6188): Unsupported mime audio/qcelp
,D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client,
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  951): handleMessage: E msg.what=131143
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:6219 rssi=-60 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=11.8 fiv=60000 [on:0 tx:0 rx:0 period:2635] from screen [on:0 period:828902713]
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:6219 rssi=-60 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=11.8 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828902714]
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.15 rxSuccessRate=11.79 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=38134 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=false
W/AudioCapabilities( 6188): Unsupported mime audio/x-ms-wma
,E/WifiConfigStore(  951): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  951): has c0:ff:d4:d3:aa:48 freq=2412 age=2806 ?=true
,W/AudioCapabilities( 6188): Unsupported mime audio/qcelp
,E/WifiStateMachine(  951): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1362): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1362): wpa_supplicant_scan enter
D/wpa_supplicant( 1362): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1362): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1362): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1362): WPS:  * Request Type
D/wpa_supplicant( 1362): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1362): WPS:  * UUID-E
D/wpa_supplicant( 1362): WPS:  * Primary Device Type
D/wpa_supplicant( 1362): WPS:  * RF Bands (3)
D/wpa_supplicant( 1362): WPS:  * Association State
D/wpa_supplicant( 1362): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1362): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1362): WPS:  * Manufacturer
D/wpa_supplicant( 1362): WPS:  * Model Name
D/wpa_supplicant( 1362): WPS:  * Model Number
D/wpa_supplicant( 1362): WPS:  * Device Name
D/wpa_supplicant( 1362): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1362): P2P: * P2P IE header
D/wpa_supplicant( 1362): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1362): P2P: * Listen Channel: Regulatory Class 81 Channel 1
,D/wpa_supplicant( 1362): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1362): wlan0: Add radio work 'scan'@0x55c5167680
D/wpa_supplicant( 1362): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1362): wlan0: Starting radio work 'scan'@0x55c5167680 after 0.000038 second wait
D/wpa_supplicant( 1362): wlan0: nl80211: scan request
D/wpa_supplicant( 1362): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1362): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1362): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1362): wlan0: Own scan request started a scan in 0.000092 seconds
I/wpa_supplicant( 1362): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  951): [1,452,527,848,772 ms] noteScanstart no scan source
E/WifiStateMachine(  951): handleMessage: X
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/VideoCapabilities( 6188): Unsupported mime video/x-ms-wmv
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationProviderProxy(  951): applying state to connected service
,D/PMS     (  951): acquireWL(2aced689): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2aced689): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  951): applying state to connected service,
,D/PMS     (  951): acquireWL(11b372bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(11b372bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): acquireWL(2fc55245): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2fc55245): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(367d5d54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(367d5d54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/MDM     ( 1811): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/NotifUtils( 6148): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
,D/wpa_supplicant( 1362): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 1362): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1362): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1362): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1362): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1362): wlan0: Scan completed in 0.072467 seconds
,D/wpa_supplicant( 1362): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1362): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1362): nl80211: Received scan results (7 BSSes)
,D/wpa_supplicant( 1362): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60,
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1362): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1362): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1362): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-93
D/wpa_supplicant( 1362): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 1362): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1362): wlan0: Scan-only results received
D/wpa_supplicant( 1362): wlan0: Radio work 'scan'@0x55c5167680 done in 0.073345 seconds
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1362): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,I/ActivityManager(  951): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6236 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/LocationInitializer( 4568): Restart initialization of location
,E/WifiStateMachine(  951): [1,452,527,848,859 ms] noteScanEnd no scan source
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39eefa30 sup_state=COMPLETED debouncing=false
,E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
,E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC243894600 a0:c5:62:7a:49:96 rssi=-93 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 7 now 1452527848863
E/WifiAutoJoinController (  951): newSupplicantResults size=7 known=1 true
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1362): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
,I/VideoCapabilities( 6188): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,I/NotifUtils( 6148): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc,
,W/ResourcesManager( 6236): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6236): onCreate
,I/vclib   ( 6188): onServiceConnected
,W/Babel   ( 6188): Attempted to change video mute state without an active call.
,D/ProviderChangeReceiver( 6236): ---------------------------------------------------
,D/ProviderChangeReceiver( 6236): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:186] from screen [on:0 period:828902911] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828902912] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
I/ActivityManager(  951): Killing 5384:com.android.settings/1000 (adj 15): empty #17
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
D/Process (  951): killProcessQuiet, pid=5384
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/HtcAlertService( 6236): start to updateAlertNotification!
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.57 txretriesrate=0.00 rxrate=10.90 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 12959(674KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 629us total 37.164ms
,W/ResourcesManager( 6188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Recipient 5384,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=128 Rx=201
,E/WifiStateMachine(  951): handleMessage: X,
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/HtcAlertService( 6236): No fired or scheduled alerts
,D/HtcAlertUtils( 6236): -- cancelReminderNotification --
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/HtcAlertUtils( 6236): broadcastExistReminder!
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
,E/MDM     ( 1811): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4568): Restart initialization of location,
,D/PMS     (  951): acquireWL(1c3856b5): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5883 10159 null
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5883, uid=10159, userID:0
,I/MusicLeanback( 5883): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  951): releaseWL(1c3856b5): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5883): Stop autocaching.
,E/GmsUtils( 5883): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 5883): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/JNIHelp ( 6188): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6188): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6188): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  951): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6276 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,E/PhoneInterfaceManager( 1431): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  404): Explicit concurrent mark sweep GC freed 8633(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 235us total 27.833ms
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6188): Unrecognized profile 2130706433 for video/avc
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 204us total 22.874ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 191us total 22.674ms
,D/PMS     (  951): releaseWL(f2f5cc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  951): getProviders()=[passive]
,E/Babel   ( 6188): UserRecoverableAuthException.
,E/Babel   ( 6188): eei: BadAuthentication
E/Babel   ( 6188): 	at eeg.a(Unknown Source)
E/Babel   ( 6188): 	at eeg.a(Unknown Source)
E/Babel   ( 6188): 	at eeg.a(Unknown Source)
E/Babel   ( 6188): 	at g.a(Unknown Source)
E/Babel   ( 6188): 	at cae.a(SourceFile:3089)
E/Babel   ( 6188): 	at cae.a(SourceFile:1131)
E/Babel   ( 6188): 	at cws.a(SourceFile:4333)
E/Babel   ( 6188): 	at cws.a(SourceFile:1419)
E/Babel   ( 6188): 	at crl.a(SourceFile:492)
E/Babel   ( 6188): 	at crl.a(SourceFile:1468)
E/Babel   ( 6188): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6188): 	at cas.b(SourceFile:106)
E/Babel   ( 6188): 	at cap.d(SourceFile:335),
E/Babel   ( 6188): 	at caq.run(SourceFile:81)
E/Babel   ( 6188): Error getting auth token
,E/Babel   ( 6188): dvm
E/Babel   ( 6188): 	at g.a(Unknown Source)
E/Babel   ( 6188): 	at cae.a(SourceFile:3089)
E/Babel   ( 6188): 	at cae.a(SourceFile:1131)
E/Babel   ( 6188): 	at cws.a(SourceFile:4333)
E/Babel   ( 6188): 	at cws.a(SourceFile:1419)
E/Babel   ( 6188): 	at crl.a(SourceFile:492)
E/Babel   ( 6188): 	at crl.a(SourceFile:1468)
E/Babel   ( 6188): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6188): 	at cas.b(SourceFile:106)
E/Babel   ( 6188): 	at cap.d(SourceFile:335)
E/Babel   ( 6188): 	at caq.run(SourceFile:81)
,E/Babel   ( 6188): Account registration failed 1-Redacted-21,
E/Babel   ( 6188): cyp: null -- null
E/Babel   ( 6188): 	at cae.a(SourceFile:3121)
E/Babel   ( 6188): 	at cae.a(SourceFile:1131)
E/Babel   ( 6188): 	at cws.a(SourceFile:4333)
E/Babel   ( 6188): 	at cws.a(SourceFile:1419)
E/Babel   ( 6188): 	,at crl.a(SourceFile:492)
E/Babel   ( 6188): 	at crl.a(SourceFile:1468)
E/Babel   ( 6188): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6188): 	at cas.b(SourceFile:106)
E/Babel   ( 6188): 	at cap.d(SourceFile:335)
E/Babel   ( 6188): 	at caq.run(SourceFile:81)
,D/libc    ( 6188): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6188): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6188): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6188): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6188): [NET] android_getaddrinfo_proxy+
D/libc    ( 6188): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
I/art     ( 6188): Note: end time exceeds epoch: 
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6188): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  951): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6310 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,D/Process (  951): killProcessQuiet, pid=5696
,I/ActivityManager(  951): Killing 5696:com.htc.backupreset/1000 (adj 15): empty #17,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/Babel   ( 6188): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  951): Recipient 5696
,I/art     (  951): Explicit concurrent mark sweep GC freed 23487(1274KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.682ms total 136.821ms
,D/Process (  951): killProcessQuiet, pid=5768
I/ActivityManager(  951): Killing 5768:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 +
I/Prism.WidgetManager( 1483): onLoadItems() +
,I/ActivityManager(  951): Recipient 5768
,I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1565): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  951): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=207
E/WifiTrafficPoller(  951): notifying of data activity 3
,D/WIFI_ICON( 1219): WifiActivity: 3
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1908): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 4 40
E/Babel   ( 6188): Unexpected exception while authenticating.
,E/Babel   ( 6188): eej: User intervention required. Notification has been pushed.
E/Babel   ( 6188): 	at eeg.b(Unknown Source)
E/Babel   ( 6188): 	at eeg.b(Unknown Source)
E/Babel   ( 6188): 	at g.a(Unknown Source)
E/Babel   ( 6188): 	at cae.b(SourceFile:1146)
E/Babel   ( 6188): 	at dcg.run(SourceFile:5617)
E/Babel   ( 6188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6188): 	at java.lang.Thread.run(Thread.java:818)
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6332): -onCreate()
,V/Settings:HtcSettingsApplication( 6332): [6332/6332] onCreate()
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6359 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  951): killProcessQuiet, pid=5793,
I/ActivityManager(  951): Killing 5793:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 6332): id/is att sku: 118/false
,E/Settings:HtcWrapHeaderInfo( 6332): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6332): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 6332): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6332): isSupportMusicChannel(): false,
,I/ActivityManager(  951): Recipient 5793,
,E/Prism.WidgetManager( 1483): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1483): onLoadItems() -
,I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 -
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasBackKey      :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]support         :false
,V/AlarmManager(  951): sending alarm PendingIntent{1fc8ca50: PendingIntentRecord{2b449 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452527850548, Int=0
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6332): Failed to find provider info for com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 6332): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6332): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 6332): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6332): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6332): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 6332): isSupportVoWifi: null,
I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6332): Failed to find provider info for com.htc.vowifi
,D/PhoneApp( 1431): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1431): -- N1 =0
,D/PhoneApp( 1431): -- N2 =0
,D/PhoneApp( 1431): -- N3 =0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6359, uid=10072, userID:0,
,W/global  ( 6359): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6359): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6359): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6359): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6359): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  951): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6398 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6359): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 6359): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6359, uid=10072, userID:0
,W/ResourcesManager( 6398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6398): VM with version 2.1.0 has multidex support
,I/MultiDex( 6398): install
I/MultiDex( 6398): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6359): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 6359): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6359): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 6398): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 4568): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,D/Finsky  ( 6359): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6426 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 4568): Null package name or gms related package.  Ignoreing.,
D/Process (  951): killProcessQuiet, pid=5601
I/ActivityManager(  951): Killing 5601:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  405): Explicit concurrent mark sweep GC freed 8667(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 335us total 23.545ms,
,W/ActivityThread( 6398): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6398): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6398): Installed default security provider GmsCore_OpenSSL
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 262us total 18.471ms
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 259us total 17.556ms,
,I/ActivityManager(  951): Recipient 5601,
,D/PMS     (  951): acquireWL(a0b6780): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4568): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6426): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  951): releaseWL(a0b6780): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=209
E/WifiTrafficPoller(  951): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  951): acquireWL(3efe4075): PARTIAL_WAKE_LOCK  AsyncService 0x1 6426 10167 null
,D/PMS     (  951): releaseWL(3efe4075): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
D/PMS     (  951): acquireWL(10f4e87b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6426 10167 null
,I/UpdateIcingCorporaServi( 6276): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/SetupWizard( 6098): Connected to Gservices successfully
D/PMS     (  951): releaseWL(10f4e87b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/Process (  951): killProcessQuiet, pid=5726,
I/ActivityManager(  951): Killing 5726:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  951): Recipient 5726,
,I/UpdateIcingCorporaServi( 6276): UpdateCorporaTask done [took 136 ms] updated apps [took 136 ms] ,
D/Process (  951): killProcessQuiet, pid=5841
,I/ActivityManager(  951): Killing 5841:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  951): Recipient 5841
D/WifiService(  951): Client connection lost with reason: 4
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/Finsky  ( 6359): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0,
,E/MDM     ( 1811): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LocationInitializer( 4568): Restart initialization of location
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  951): acquireWL(1c65c7ba): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 951 1000 null
,D/PMS     (  951): acquireWL(e0ce66b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 951 1000 null
D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/PMS     (  951): releaseWL(1c65c7ba): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  951): releaseWL(e0ce66b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case ,
,D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/Kids    ( 4568): [AccountUtils] Account not ready
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/RemoteViews( 1219): reapply : com.google.android.gms 4 40
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/ProviderChangeReceiver( 6236): ---------------------------------------------------
,D/ProviderChangeReceiver( 6236): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/HtcAlertService( 6236): start to updateAlertNotification!
,I/ActivityManager(  951): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=6475 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
V/AlarmManager(  951): sending alarm PendingIntent{29d69674: PendingIntentRecord{1fda2d77 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527851753, Int=0
,D/Finsky  ( 6359): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  951): sending alarm PendingIntent{320d0527: PendingIntentRecord{2a4743d4 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452527842903, Int=20000
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5947): onHandleIntent
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
W/ResourcesManager( 6475): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5947): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/WSP     ( 1565): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
D/WeatherUtility( 1565): Weather sync is On
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DFPI.ApkInstallService( 5947): onHandleIntent
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/DFPI.ApkInstallService( 5947): Media Scan Finished Case 
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
D/DFPI.ApkInstallService( 5947): check CID = HTC__102
I/DFPI.ApkInstallService( 5947): There is no Demo.apk in sd card or phone storage
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WSP     ( 1565): [Receiver] next auto-sync alarm event is 60 mins later, at time: Mon Jan 11 17:57:31 CET 2016,
I/SoundPicker( 5998): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5998): SoundPickerReceiver [onReceive] startService
I/CalendarProvider2( 6475): Created com.android.providers.calendar.CalendarAlarmManager@3edb4ed6(com.htc.providers.calendar.HtcCalendarProvider@24e9f557)
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/CalendarProvider2( 6475): wait start:true
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  951): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6505 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
D/CalendarProvider2( 6475): wait end:false
W/Finsky  ( 6359): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4),
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/HtcAlertService( 6236): No fired or scheduled alerts
D/HtcAlertUtils( 6236): -- cancelReminderNotification --
D/HtcAlertUtils( 6236): broadcastExistReminder!
,D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
W/ResourcesManager( 6505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:2807] from screen [on:0 period:828905931] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828905932] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/wpa_supplicant( 1362): environment dirty rate=0 [4][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.29 txretriesrate=0.00 rxrate=11.95 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951): handleMessage: X
,E/MDM     ( 1811): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/Task_Calendar( 6505): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,D/LocationInitializer( 4568): Restart initialization of location
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
D/TodoTaskshortcut( 6505): update TASK shortcut>
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,V/AlarmManager(  951): sending alarm PendingIntent{149bac27: PendingIntentRecord{1e65ed4 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452527852039, Int=0
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5998): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5998): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5998): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/art     (  951): Explicit concurrent mark sweep GC freed 20563(1005KB) AllocSpace objects, 2(168KB) LOS objects, 33% free, 16MB/25MB, paused 2.007ms total 155.343ms
,D/PMS     (  951): acquireWL(7250eca): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6188 10112 null
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5883): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  951): releaseWL(7250eca): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1565): handle notify Blinkfeed plugin client changed
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5998): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/iu.UploadsManager( 4568): End new media; added: 0, uploading: 0, time: 84 ms,
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=212
I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5998): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SoundPicker( 5998): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
D/PackageBroadcastService( 4568): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4568): Null package name or gms related package.  Ignoreing.
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5998): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  951): acquireWL(38588e9): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  951): acquireWL(3cc8796e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6426 10167 null
D/PMS     (  951): releaseWL(3cc8796e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4568): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  951): acquireWL(ebe109c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6426 10167 null
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  951): releaseWL(ebe109c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 6276): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  951): releaseWL(38588e9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(2e52a95d): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5883 10159 null
,W/Kids    ( 4568): [AccountUtils] Account not ready
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5883, uid=10159, userID:0
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,D/PMS     (  951): releaseWL(2e52a95d): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5883): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5883): Stop autocaching.
,I/ActivityManager(  951): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6545 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UpdateIcingCorporaServi( 6276): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] ,
,E/GmsUtils( 5883): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 5883): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6359): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/SyncApplication( 6545): Loading default preferences,
,W/Resources( 6545): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,E/WifiTrafficPoller(  951): ADD_CLIENT: 7,
D/WifiService(  951): New client listening to asynchronous messages
,D/SyncApplication( 6545): Overriding preferences with custom values,
,D/SyncApplication( 6545): Updating preferences succeeded
,E/SyncApplication( 6545): Application created.,
,W/VolumeInfo( 6545): Unable to read mount points
W/VolumeInfo( 6545): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6545): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 6545): 	,at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 6545): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 6545): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 6545): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 6545): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 6545): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 6545): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 6545): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 6545): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 6545): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 6545): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 6545): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 6545): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 6545): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6545): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 6545): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 6545): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 6545): 	... 13 more
V/VolumeInfo( 6545): Found 0 mount point(s)
,V/VolumeInfo( 6545): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/CalendarDefines( 6545): getNewCalendarAuthority()...
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6545, uid=10005, userID:0
,W/PackageManager(  951): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6545, uid=10005, userID:0
W/PackageManager(  951): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 6545): enableAppOperation()+
D/VolumeInfo( 6545): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/SyncApplication( 6545): enableAppOperation()-
,D/HTCUtilities( 6545): isNeorSinged() + 
,D/VolumeInfo( 6545): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 6545): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 6545): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 6545): isNeorSinged() return false
,E/AndroidHttpClient( 6359): Leak found
E/AndroidHttpClient( 6359): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6359): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6359): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6359): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6359): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6359): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6359): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6359): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6359): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6359): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6359): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6359): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6359): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6359): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6359): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/CDMountReceiver( 6545): whether to enable CD Auto-mount: true
D/CDMountReceiver( 6545): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 6545): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/CDMountReceiver( 6545): enable CD Auto-mount: true,
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true,
D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/HTCUtilities( 6545): enable auto-mount
,D/HTCUtilities( 6545): enable auto-mount
,I/HtcMountManagerAdapter( 6545): mHtcMountManager is  null
,I/HtcMountManagerAdapter( 6545): mHtcMountManager is  null
I/HtcMountManagerAdapter( 6545): mStorageManager is  not null
I/HtcMountManagerAdapter( 6545): mStorageManager is  not null
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/VoldConnector(  951): SND -> {29 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/VoldConnector(  951): SND -> {30 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/MountService(  951): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  951): mountISO: /system/etc/PCTOOL.ISO
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/RemoteViews( 1219): apply : com.nero.android.htc.sync 0 11 2 38
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
,E/MDM     ( 1811): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/RemoteViews( 1219): apply : com.nero.android.htc.sync 0 11 3 53,
E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
E/WifiStateMachine(  951): handleMessage: E msg.what=131143
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):1 dur:87 rssi=-60 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=11.9 list=2412 [on:0 tx:0 rx:0 period:464] from screen [on:0 period:828906414]
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):4 dur:87 rssi=-60 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=11.9 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828906416]
,E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.29 rxSuccessRate=11.95 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
D/PMS     (  951): releaseWL(3dc5b2c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=41837 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  951): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  951): has c0:ff:d4:d3:aa:48 freq=2412 age=471 ?=true
E/WifiStateMachine(  951): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1362): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1362): wpa_supplicant_scan enter
,D/wpa_supplicant( 1362): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1362): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1362): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1362): WPS:  * Request Type
D/wpa_supplicant( 1362): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1362): WPS:  * UUID-E
D/wpa_supplicant( 1362): WPS:  * Primary Device Type
D/wpa_supplicant( 1362): WPS:  * RF Bands (3)
D/wpa_supplicant( 1362): WPS:  * Association State
D/wpa_supplicant( 1362): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1362): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1362): WPS:  * Manufacturer
D/wpa_supplicant( 1362): WPS:  * Model Name
D/wpa_supplicant( 1362): WPS:  * Model Number
D/wpa_supplicant( 1362): WPS:  * Device Name
D/wpa_supplicant( 1362): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1362): P2P: * P2P IE header
D/wpa_supplicant( 1362): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1362): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1362): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1362): wlan0: Add radio work 'scan'@0x55c5167680
D/wpa_supplicant( 1362): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1362): wlan0: Starting radio work 'scan'@0x55c5167680 after 0.000033 second wait
D/wpa_supplicant( 1362): wlan0: nl80211: scan request
D/LocationInitializer( 4568): Restart initialization of location
E/WifiStateMachine(  951): [1,452,527,852,466 ms] noteScanstart no scan source
D/wpa_supplicant( 1362): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1362): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1362): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1362): wlan0: Own scan request started a scan in 0.000071 seconds
I/wpa_supplicant( 1362): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  951): handleMessage: X
,D/wpa_supplicant( 1362): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1362): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1362): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1362): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1362): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1362): wlan0: Scan completed in 0.067269 seconds
D/wpa_supplicant( 1362): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1362): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1362): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1362): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1362): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1362): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1362): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-93
D/wpa_supplicant( 1362): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 1362): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1362): wlan0: Scan-only results received
D/wpa_supplicant( 1362): wlan0: Radio work 'scan'@0x55c5167680 done in 0.067992 seconds
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
,E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1362): wlan0: Control interface command 'LIST_DONGLES'
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  951): [1,452,527,852,536 ms] noteScanEnd no scan source
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39eefa30 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
,E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC243894600 a0:c5:62:7a:49:96 rssi=-93 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 7 now 1452527852540
E/WifiAutoJoinController (  951): newSupplicantResults size=7 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1362): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX,
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6359): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 6359): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6359): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6359): [1] DailyHygiene.reschedule: Scheduling new run in 96 minutes (failures=3)
,D/Process (  951): killProcessQuiet, pid=6024
I/ActivityManager(  951): Killing 6024:com.htc.updater/u0a84 (adj 15): empty #17
,D/DeviceConnectionService( 1811): client connected with version: 7571000
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6024
,D/Process (  951): killProcessQuiet, pid=5898
I/ActivityManager(  951): Killing 5898:com.htc.task.gtask/u0a66 (adj 15): empty #18
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 6475): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6475): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  951): Recipient 5898
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=114 rxSum=105} preTxRxSum={txSum=110 rxSum=102}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/GAV2    ( 6148): Thread[GAThread,5,main]: No campaign data found.
D/ProviderChangeReceiver( 6236): ---------------------------------------------------
,D/ProviderChangeReceiver( 6236): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 6236): start to updateAlertNotification!
I/ActivityManager(  951): Killing 6125:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=6125
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=213
,I/ActivityManager(  951): Recipient 6125
,D/HtcAlertService( 6236): No fired or scheduled alerts
,D/HtcAlertUtils( 6236): -- cancelReminderNotification --
D/HtcAlertUtils( 6236): broadcastExistReminder!
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcModeClient( 3300): handler message = 4011
E/HtcModeClient( 3300): Check connection and retry 8 times.
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=214
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=11.9 bcn=0 [on:0 tx:0 rx:0 period:2535] from screen [on:0 period:828908953] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=11.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828908954] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1362): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.64 txretriesrate=0.00 rxrate=6.97 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  951): handleMessage: X
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=214
E/WifiTrafficPoller(  951): notifying of data activity 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=216
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 1
,D/Process (  951): killProcessQuiet, pid=5569,
I/ActivityManager(  951): Killing 5569:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=217
,I/ActivityManager(  951): Recipient 5569
,D/Process (  951): killProcessQuiet, pid=6310
,I/ActivityManager(  951): Killing 6310:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6310
,I/ActivityManager(  951): Killing 5947:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
D/Process (  951): killProcessQuiet, pid=5947
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5947,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:828911963] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828911964] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.82 txretriesrate=0.00 rxrate=5.49 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=114 rxSum=105} preTxRxSum={txSum=114 rxSum=105},
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=218
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 9 times.
,D/PMS     (  951): acquireWL(162608d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{1000}
V/AlarmManager(  951): sending alarm PendingIntent{322d75c4: PendingIntentRecord{10d50cad android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=84563, Int=0
,D/PMS     (  951): releaseWL(162608d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=218
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiTrafficPoller(  951): notifying of data activity 0
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=219
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  951): notifying of data activity 1
,E/WifiStateMachine(  951): handleMessage: E msg.what=131326,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !what:131326 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !what:131326 1 0
E/WifiStateMachine(  951): handleMessage: X
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:828914982] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:21] from screen [on:0 period:828915003] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.41 txretriesrate=0.00 rxrate=3.24 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  951): handleMessage: X
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{38fe0697 u0 com.htc.musicenhancer/.EnhancerService},
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=219
,E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/art     (  951): Explicit concurrent mark sweep GC freed 23606(1117KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 1.840ms total 191.961ms,
,W/MediaManager( 5820): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  951): killProcessQuiet, pid=5998
I/ActivityManager(  951): Killing 5998:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5998,
,I/art     ( 3970): Explicit concurrent mark sweep GC freed 5021(272KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1513KB/5MB, paused 1.142ms total 37.592ms,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=219
,D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1565): service - handleMessage() stop self,
,D/AutoSetting( 1565): service - onDestroy() END,
D/AutoSetting( 1565): service - handleMessage() quit looper,
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=114 rxSum=105} preTxRxSum={txSum=114 rxSum=105},
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=220
E/WifiTrafficPoller(  951): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 10 times.
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828918023] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828918024] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.21 txretriesrate=0.00 rxrate=2.12 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=220
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 0
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=220
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=221
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951): notifying of data activity 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828921034] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828921035] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.10 txretriesrate=0.00 rxrate=1.56 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  951): handleMessage: X
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=221
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 0
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=114 rxSum=105} preTxRxSum={txSum=114 rxSum=105}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=221
,D/PMS     (  951): acquireWL(336e2a30): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10072},
V/AlarmManager(  951): sending alarm PendingIntent{7e2c6a9: PendingIntentRecord{3cc442e com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527867299, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{4533bcf: PendingIntentRecord{4c3b95c com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452527868487, Int=536832000
,V/AlarmManager(  951): sending alarm PendingIntent{320d0527: PendingIntentRecord{2a4743d4 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452527862903, Int=20000
V/CheckinService( 4568): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  951): acquireWL(22f82465): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
E/WifiStateMachine(  951): handleMessage: E msg.what=131143
D/PMS     (  951): releaseWL(336e2a30): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:70 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.6 list=2412 [on:0 tx:0 rx:0 period:1416] from screen [on:0 period:828922469]
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:70 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.6 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828922471]
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.10 rxSuccessRate=1.56 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=57892 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  951): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  951): has c0:ff:d4:d3:aa:48 freq=2412 age=1423 ?=true
E/WifiStateMachine(  951): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1362): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1362): wpa_supplicant_scan enter
D/wpa_supplicant( 1362): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1362): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1362): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1362): WPS:  * Request Type
D/wpa_supplicant( 1362): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1362): WPS:  * UUID-E
D/wpa_supplicant( 1362): WPS:  * Primary Device Type
D/wpa_supplicant( 1362): WPS:  * RF Bands (3)
D/wpa_supplicant( 1362): WPS:  * Association State
D/wpa_supplicant( 1362): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1362): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1362): WPS:  * Manufacturer
D/wpa_supplicant( 1362): WPS:  * Model Name
D/wpa_supplicant( 1362): WPS:  * Model Number
D/wpa_supplicant( 1362): WPS:  * Device Name
D/wpa_supplicant( 1362): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1362): P2P: * P2P IE header
D/wpa_supplicant( 1362): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1362): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1362): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1362): wlan0: Add radio work 'scan'@0x55c5167680
D/wpa_supplicant( 1362): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1362): wlan0: Starting radio work 'scan'@0x55c5167680 after 0.000051 second wait
D/wpa_supplicant( 1362): wlan0: nl80211: scan request
D/wpa_supplicant( 1362): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1362): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1362): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1362): wlan0: Own scan request started a scan in 0.000088 seconds
I/wpa_supplicant( 1362): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  951): [1,452,527,868,522 ms] noteScanstart no scan source
E/WifiStateMachine(  951): handleMessage: X
D/PMS     (  951): acquireWL(371c5eb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(22f82465): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4568): Checking schedule, now: 1452527868539 next: 1452527868487
,I/CheckinService( 4568): active receiver: enabled
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4568, uid=10024, userID:0
,I/CheckinService( 4568): Preparing to send checkin request
,I/EventLogService( 4568): Accumulating logs since 1452527833515
,I/CheckinRequestBuilder( 4568): Checkin reason type: 11 attempt count: 1
D/wpa_supplicant( 1362): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1362): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1362): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1362): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1362): wlan0: Scan completed in 0.062953 seconds
D/wpa_supplicant( 1362): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1362): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1362): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1362): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1362): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1362): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1362): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
D/wpa_supplicant( 1362): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1362): BSS: last_scan_res_used=6/32
D/wpa_supplicant( 1362): wlan0: Scan-only results received
D/wpa_supplicant( 1362): wlan0: Radio work 'scan'@0x55c5167680 done in 0.063879 seconds
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1362): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  951): [1,452,527,868,589 ms] noteScanEnd no scan source
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39eefa30 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC243894600 a0:c5:62:7a:49:96 rssi=-93 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 7 now 1452527868593
E/WifiAutoJoinController (  951): newSupplicantResults size=7 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1362): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/ActivityThread( 4568): Failed to find provider info for com.google.android.wearable.settings
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 11 times.
,I/art     ( 1908): Explicit concurrent mark sweep GC freed 24914(1471KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 1.019ms total 52.991ms,
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 4568): awaiting user notification for token
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,I/ActivityManager(  951): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6597 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,D/Finsky  ( 6359): [642] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6359): [1] 5.onFinished: Installation state replication succeeded.,
,W/ResourcesManager( 6597): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6597): VM with version 2.1.0 has multidex support
I/MultiDex( 6597): install
I/MultiDex( 6597): VM has multidex support, MultiDex support library is disabled.,
,V/JNIHelp ( 6597): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6597): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6597): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d656840: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6597): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1908): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 6059): callingUid 10024, callindPid: 6059
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0
,E/MDM     ( 1811): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 4568): Restart initialization of location
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=132 Rx=222
E/WifiTrafficPoller(  951): notifying of data activity 1
,D/WIFI_ICON( 1219): WifiActivity: 1
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/WVCdm   (  398): CdmEngine::OpenSession
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  398): Service_Initialize: starts!
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
,D/QSEECOMAPI: (  398): Loaded image: APP id = 8,
D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9e000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9e000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  481): got the req here! ret=0
D/DrmLibTime(  481): command id, time_cmd_id = 770
D/DrmLibTime(  481): time_getutcsec starts!
D/DrmLibTime(  481): QSEE Time Listener: time_getutcsec,
,D/DrmLibTime(  481): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  481): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  481): QSEE Time Listener: Checking if ATS_MODEM is set or not.,
E/QC-time-services(  481): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  481): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  481): QSEE Time Listener: Retrieved Android system time: 1452527869
D/DrmLibTime(  481): time_getutcsec returns 0, sec = 1452527869; nsec = 0
D/DrmLibTime(  481): time_getutcsec finished! 
D/DrmLibTime(  481): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  481): before calling ioctl to read the next time_cmd
,E/QC-time-services(  424): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xf4ec8928
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab661608, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e7050, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab53f088, idLength=0xf3de36f8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1,
,D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xf3de370e, maximum = 0xf3de370f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf3de377c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=770576771
,D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab573720
D/DrmWidevineDash(  398): message_length=1611, signature=0xab544208, signature_length=0xf3de36dc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  398): CdmEngine::CloseSession,
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 8
,D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6626): Error opening trace file: Permission denied (13)
I/dex2oat ( 6626): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6626): dex2oat: override thread count:4
,I/dex2oat ( 6626): dex2oat took 34.324ms (threads: 4),
,I/Adreno-EGL( 6597): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6597): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6597): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6597): Local Branch: 
I/Adreno-EGL( 6597): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6597): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6597):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6597): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6597): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6597): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6597): Local Branch: 
I/Adreno-EGL( 6597): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6597): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6597):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  398): CdmEngine::OpenSession,
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  398): Service_Initialize: starts!
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE,
,E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
,D/QSEECOMAPI: (  398): Loaded image: APP id = 9,
,D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9e000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d9e000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  481): got the req here! ret=0,
D/DrmLibTime(  481): command id, time_cmd_id = 770
D/DrmLibTime(  481): time_getutcsec starts!
D/DrmLibTime(  481): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  481): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  481): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  481): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  481): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
,D/DrmLibTime(  481): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  481): QSEE Time Listener: Retrieved Android system time: 1452527869
D/DrmLibTime(  481): time_getutcsec returns 0, sec = 1452527869; nsec = 0
D/DrmLibTime(  481): time_getutcsec finished! 
D/DrmLibTime(  481): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  481): before calling ioctl to read the next time_cmd
E/QC-time-services(  424): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xf4ec8928
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab6617f8, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e7050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab53f0a8, idLength=0xffdb2118
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xffdb212e, maximum = 0xffdb212f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffdb219c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=1149793385
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab573720
D/DrmWidevineDash(  398): message_length=1646, signature=0xab544208, signature_length=0xffdb20fc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  398): CdmEngine::CloseSession,
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!,
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4568): Classify the device as Phone.,
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4568): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4568): [NET] android_getaddrinfo_proxy+
D/libc    ( 4568): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4568): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1579] from screen [on:0 period:828924054] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828924055] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [3][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72,
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.55 txretriesrate=0.00 rxrate=2.28 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951): handleMessage: X
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4568): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4568): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4568): Sending checkin request (8492 bytes),
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 3
,E/WifiTrafficPoller(  951):  packet count Tx=147 Rx=231
E/WifiTrafficPoller(  951): notifying of data activity 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinRequestBuilder( 4568): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4568): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4568): awaiting user notification for token
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 3 40
,I/CheckinRequestBuilder( 4568): Classify the device as Phone.
,I/CheckinTask( 4568): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4568): Checking schedule, now: 1452527870718 next: 1453064702714,
I/CheckinService( 4568): active receiver: disabled
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4568, uid=10024, userID:0
,D/PMS     (  951): releaseWL(371c5eb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4568): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/GCM     ( 1908): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4568): [AccountUtils] Account not ready,
W/Kids    ( 4568): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4568): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/Kids    ( 4568): ,	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4568): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4568): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4568): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4568): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4568): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 3 40
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=148 Rx=235
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=148 Rx=236
E/WifiTrafficPoller(  951): notifying of data activity 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=118} preTxRxSum={txSum=114 rxSum=105}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:828927065] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828927067] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1362): environment dirty rate=0 [14][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.78 txretriesrate=0.00 rxrate=7.64 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=237
D/WIFI_ICON( 1219): WifiActivity: 3
E/WifiTrafficPoller(  951): notifying of data activity 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 12 times.
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=237
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 0
,D/Process (  951): killProcessQuiet, pid=6475
I/ActivityManager(  951): Killing 6475:com.htc.bgp/u0a11 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6475
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=238
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 1
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.8, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:828930076] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.8, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828930077] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.89 txretriesrate=0.00 rxrate=4.32 userTriggerdPenalty0
,E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  951): handleMessage: X
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=238
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 0
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=238
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=118} preTxRxSum={txSum=131 rxSum=118}
,D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=239
,D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  951): notifying of data activity 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AccTypeManager( 1724): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/SystemReader(  951): Cannot find grip_rejection_width, use default value instead
D/PMS     (  951): acquireWL(d3820f2): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6188 10112 null
,D/AccTypeManager( 1724): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,W/Prism.AllAppsManager( 1483): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1483): Deferring update until onResume
D/Launcher( 1483): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  951): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  951): releaseWL(d3820f2): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/AccTypeManager( 1724): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
,I/[PluginManager]RegisterService( 1565): handle notify Blinkfeed plugin client changed,
W/ResourcesManager( 6188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/PhoneApp( 1431): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
W/ResourcesManager( 6188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/HtcModeClient( 3300): handler message = 4011
,E/HtcModeClient( 3300): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3300): Don't start project servcice
,D/PackageBroadcastService( 4568): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,E/ExternalAccountType( 1724): Unsupported attribute readOnly
,D/HtcModeClient( 3300): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3300): connectState: CONNECTION_READY = false
D/SilentMusic( 3300): call stop
D/HtcModeClient( 3300): close connection
W/HtcModeClient( 3300): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3300): read the terminate packet, so break
,I/PackageBroadcastService( 4568): Null package name or gms related package.  Ignoreing.
,D/PMS     (  951): acquireWL(14e999d9): PARTIAL_WAKE_LOCK  AsyncService 0x1 6426 10167 null
,D/PMS     (  951): releaseWL(14e999d9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  951): acquireWL(2b2ccf9e): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4568): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  951): acquireWL(1c1e4a4c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6426 10167 null
,D/PMS     (  951): releaseWL(1c1e4a4c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
I/UpdateIcingCorporaServi( 6276): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  951): releaseWL(2b2ccf9e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/PackageManager(  951): Unable to load service info ResolveInfo{268b3d50 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  951): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  951): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  951): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  951): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  951): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Method.java:372),
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/UpdateIcingCorporaServi( 6276): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] ,
,V/GmsNetworkLocationProvi( 1811): DISABLE,
,I/GCoreNlp( 1811): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  951): acquireWL(17f073b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms},
D/LocationProviderProxy(  951): applying state to connected service
D/PMS     (  951): releaseWL(17f073b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  951): applying state to connected service,
,D/PMS     (  951): acquireWL(24a58bb1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(24a58bb1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  951): Explicit concurrent mark sweep GC freed 32898(1770KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 1.472ms total 150.300ms
D/PMS     (  951): acquireWL(38d88070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(38d88070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828933098] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828933100] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.94 txretriesrate=0.00 rxrate=2.66 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=239
,E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  951): acquireWL(31f0ffe9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{219ec928: PendingIntentRecord{2ed60641 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105802, Int=0
,D/PMS     (  951): releaseWL(31f0ffe9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,I/ClockController( 1219): schedule update now=1452527880057 next=59943,
,I/Clock   ( 1219): updateClock:16:58 Europe/Warsaw,
I/Clock   ( 1219): updateClock:16:58 Europe/Warsaw
I/Clock   ( 1219): updateClock:16:58 Europe/Warsaw
,I/Prism.ItemManager( 1483): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 +
I/Prism.WidgetManager( 1483): onLoadItems() +
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=239
,W/ResourcesManager( 1483): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1483): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1483): Copying FileAsset 0x55af1496f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1483): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1483): onLoadItems() -
I/Prism.ItemManager( 1483): loadItems() com.htc.launcher.pageview.WidgetManager@20a7feb2 -
,D/PhoneApp( 1431): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1431): -- N1 =0
,D/PhoneApp( 1431): -- N2 =0
,D/PhoneApp( 1431): -- N3 =0,
,I/ActivityManager(  951): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6656 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  951): acquireWL(8cc246e): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10076}
V/AlarmManager(  951): sending alarm PendingIntent{d19370f: PendingIntentRecord{271d339c com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452527880960, Int=60000
,D/PMS     (  951): releaseWL(8cc246e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,D/SMSBackup( 6656): SMSBackupAgentService started,
D/SMSBackup( 6656): Checking restore status,
,D/SMSBackup( 6656): Restore complete
,D/SMSBackup( 6656): cancelCheckAlarm
,D/SMSBackup( 6656): SMSBackupAgentService completed: completed in 0.0 seconds
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
E/WifiTrafficPoller(  951): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828936120] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828936122] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,D/PMS     (  951): acquireWL(28205346): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
,D/PMS     (  951): releaseWL(28205346): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.97 txretriesrate=0.00 rxrate=1.83 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
D/PMS     (  951): acquireWL(39825a34): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiStateMachine(  951): handleMessage: X
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
E/WifiTrafficPoller(  951): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  951): releaseWL(39825a34): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(1f40851e): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(1f40851e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(2e62bbcc): PARTIAL_WAKE_LOCK  Icing 0x1 4568 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): releaseWL(2e62bbcc): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
D/PMS     (  951): acquireWL(210a4e15): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{1000}
E/WifiStateMachine(  951): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
E/WifiStateMachine(  951): processMsg: ConnectedState
,V/AlarmManager(  951): sending alarm PendingIntent{320d0527: PendingIntentRecord{2a4743d4 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452527882903, Int=20000
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:67 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 list=2412 [on:0 tx:0 rx:0 period:708] from screen [on:0 period:828936858]
D/PMS     (  951): releaseWL(210a4e15): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:67 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828936860],
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.97 rxSuccessRate=1.83 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=72281 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN try full band scan age=72281 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1362): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1362): wpa_supplicant_scan enter
,D/wpa_supplicant( 1362): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1362): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1362): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1362): WPS:  * Request Type
D/wpa_supplicant( 1362): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1362): WPS:  * UUID-E
D/wpa_supplicant( 1362): WPS:  * Primary Device Type
D/wpa_supplicant( 1362): WPS:  * RF Bands (3)
D/wpa_supplicant( 1362): WPS:  * Association State
D/wpa_supplicant( 1362): WPS:  * Configuration Error (0),
D/wpa_supplicant( 1362): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1362): WPS:  * Manufacturer
D/wpa_supplicant( 1362): WPS:  * Model Name
D/wpa_supplicant( 1362): WPS:  * Model Number
D/wpa_supplicant( 1362): WPS:  * Device Name
D/wpa_supplicant( 1362): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1362): P2P: * P2P IE header
D/wpa_supplicant( 1362): P2P: * Capability dev=25 group=00,
D/wpa_supplicant( 1362): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1362): wlan0: Add radio work 'scan'@0x55c5167680
D/wpa_supplicant( 1362): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1362): wlan0: Starting radio work 'scan'@0x55c5167680 after 0.000047 second wait
D/wpa_supplicant( 1362): wlan0: nl80211: scan request
D/wpa_supplicant( 1362): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1362): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1362): wlan0: nl80211: Scan trigger,
D/wpa_supplicant( 1362): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1362): wlan0: Own scan request started a scan in 0.000099 seconds
I/wpa_supplicant( 1362): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  951): [1,452,527,882,911 ms] noteScanstart no scan source,
E/WifiStateMachine(  951): handleMessage: X
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=118} preTxRxSum={txSum=131 rxSum=118}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
,D/Process (  951): killProcessQuiet, pid=3300,
I/ActivityManager(  951): Killing 3300:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 3300,
,D/Process (  951): killProcessQuiet, pid=6505
I/ActivityManager(  951): Killing 6505:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6505
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
,D/wpa_supplicant( 1362): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1362): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1362): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700,
D/wpa_supplicant( 1362): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1362): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1362): wlan0: Scan completed in 2.136046 seconds
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1362): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1362): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1362): nl80211: Received scan results (8 BSSes),
D/wpa_supplicant( 1362): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1362): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1362): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
,I/wpa_supplicant( 1362): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1362): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
,I/wpa_supplicant( 1362): [NULL] a0:c5:62:7a:49:96 freq=2412 level=-92
I/wpa_supplicant( 1362): [NULL] 00:37:b7:9d:3e:72 freq=2437 level=-93
D/wpa_supplicant( 1362): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1362): wlan0: BSS: Add new id 7 BSSID 00:37:b7:9d:3e:72 SSID 'FunBox2-3E72'
D/wpa_supplicant( 1362): BSS: last_scan_res_used=8/32
D/wpa_supplicant( 1362): wlan0: Scan-only results received
D/wpa_supplicant( 1362): wlan0: Radio work 'scan'@0x55c5167680 done in 2.137326 seconds
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:37:b7:9d:3e:72]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1362): wlan0: Control interface command 'LIST_DONGLES'
,E/WifiStateMachine(  951): [1,452,527,885,054 ms] noteScanEnd no scan source
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39eefa30 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-86 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  951): UPC5999698 64:7c:34:12:7f:81 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): UPC243894600 a0:c5:62:7a:49:96 rssi=-92 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): FunBox2-3E72 00:37:b7:9d:3e:72 rssi=-93 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 8 now 1452527885058
E/WifiAutoJoinController (  951): newSupplicantResults size=8 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1362): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
D/WifiManager( 1811): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:2280] from screen [on:0 period:828939144] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:828939145] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
,I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.49 txretriesrate=0.00 rxrate=0.92 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f2ebf50
I/PMS     (  951): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  951): pid=951, uid=1000
W/PMN     (  951): goingToSleep
W/SensorService(  951): Active sensors: size = 4
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2f2ebf50, eanble = 0, strlen(mName) = 91
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  951): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@25cb1b39
W/SensorService(  951): Listener[1] = com.htc.smartdim.sensor_eye@a1bc28d
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  951): Sleeping (uid 1000)...
,D/XAN-DPS (  951): prepareColorFade 1
,W/HtcLockScreen( 1219): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
I/Adreno-EGL(  951): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  951): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  951): Build Date: 03/09/15 Mon
I/Adreno-EGL(  951): Local Branch: 
I/Adreno-EGL(  951): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  951): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  951):                  d74aa161a12b9c6fc6332151
,W/PMS     (  951): mWirelessDisplayManager is null
D/PMS     (  951): acquireWL(2e6bd52a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 951 1000 null
,W/PMN     (  951): goingToSleep done
W/PMS     (  951): mWirelessDisplayManager is still null
,W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
D/AlarmManager(  951): ACTION_SCREEN_ON
I/AlarmManager(  951): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  951): [AlarmQueuing] done recovering
I/AlarmManager(  951): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  951): [AlarmQueuing] done EPS screen off alarm recovering
,I/ActivityManager(  951): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6681 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,E/WifiTrafficPoller(  951): ENABLE_TRAFFIC_STATS_POLL true Token 11,
E/WifiTrafficPoller(  951):  packet count Tx=149 Rx=240
,D/PMS     (  951): releaseWL(2e6bd52a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null,
,E/WifiDataStallTracker(  951): ENABLE_DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=118} preTxRxSum={txSum=131 rxSum=118}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  951): handleMessage: E msg.what=131167
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  951): processMsg: DefaultState
E/WifiStateMachine(  951):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1362): SET_SCREEN_ON:On
I/wpa_supplicant( 1362): htc_wext_set_keepalive +
I/wpa_supplicant( 1362): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1362): getPrivFuncNum +	
I/wpa_supplicant( 1362): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1362): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client,
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
,D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
I/wpa_supplicant( 1362): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1362): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1362): htc_wext_set_TX_TRACKING - ret = 0
,E/WifiStateMachine(  951): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  951): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  951): handleScreenStateChanged Exit: true
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131154
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1362): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  398): ParamSet string: screen_state=on
E/audio_a2dp_hw(  398): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  951): handleMessage: E msg.what=155650
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/NetworkPolicy(  951): updateScreenOn: false
V/NetworkPolicy(  951): updateIfacesLocked()
D/NetworkManagementService(  951): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/wpa_supplicant( 1362): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131127
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131129
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/WifiStateMachine(  951):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1362): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1362): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  951): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=38 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  951): handleMessage: X
,W/ResourcesManager( 6681): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/IntentController( 1219): receive(android.intent.action.SCREEN_ON,1,false)
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 12 num clients 7,
D/PMS     (  951): acquireWL(2c972acd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
I/CalendarProvider2( 6681): Created com.android.providers.calendar.CalendarAlarmManager@3edb4ed6(com.htc.providers.calendar.HtcCalendarProvider@24e9f557)
D/PMS     (  951): acquireWL(32f5df82): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2c972acd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(32f5df82): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6681): wait start:true,
,D/AlarmManager(  951): ACTION_SCREEN_OFF,
E/WifiTrafficPoller(  951): ENABLE_TRAFFIC_STATS_POLL false Token 12
I/AlarmManager(  951): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  951): stopDataStallAlarm 
I/AlarmManager(  951): [AlarmQueuing] data connection: true
E/WifiDataStallTracker(  951): ENABLE_DATA_MONITOR_POLL false Token 2
I/AlarmManager(  951): [AlarmQueuing] wifi connection: true
,E/WifiStateMachine(  951): handleMessage: E msg.what=131167
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: DefaultState
E/WifiStateMachine(  951):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0",
D/wpa_supplicant( 1362): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1362): SET_SCREEN_ON:Off
I/wpa_supplicant( 1362): htc_wext_set_keepalive +
I/wpa_supplicant( 1362): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1362): getPrivFuncNum +	
I/wpa_supplicant( 1362): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1362): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1362): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1362): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1362): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  951): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,V/SRS_Proc(  398): ParamSet string: screen_state=off
D/XAN-DPS (  951): prepareColorFade done
E/audio_a2dp_hw(  398): adev_set_parameters: ERROR: set param called even when stream out is null
D/XAN-DPS (  951): setBrightness to 0
D/WifiStateMachine(  951): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  951): handleScreenStateChanged Exit: false
D/WifiController(  951): handleMessage: E msg.what=155651
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131154
D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkPolicy(  951): updateScreenOn: false
V/NetworkPolicy(  951): updateIfacesLocked()
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/WifiStateMachine(  951): handleMessage: X
,D/NetworkManagementService(  951): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1302): [EventService] getTotalRam: 1842 Mb
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@25cb1b39
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  951): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  951): pid=951, uid=1000
W/SensorService(  951): Active sensors: size = 3,
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
,V/ActivityManager(  951): Display changed displayId=0
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@25cb1b39, eanble = 0, strlen(mName) = 67
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.smartdim.sensor_eye@a1bc28d
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1302): [EventService]  onDisplayChanged: 0
E/qdutils (  384): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  384): int qdutils::getHDMINode(): Failed to find HDMI node
,D/CalendarProvider2( 6681): wait end:false
,D/DotMatrix( 1302): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/SensorManager( 1219): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@18304df0, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  951): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  951): pid=1219, uid=10041
,W/SensorService(  951): Active sensors: size = 4
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@18304df0, eanble = 1, strlen(mName) = 57
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  951): Listener[0] = com.htc.smartdim.sensor_eye@a1bc28d
W/SensorService(  951): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@18304df0
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  951): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  404): Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 26.589ms,
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 22.865ms
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 21.781ms
,D/ContactMessageStore( 1431): start background delete task...,
,D/ContactMessageStore( 1431): size: 0 , 0
D/ContactMessageStore( 1431): Background delete complete
,I/IntentController( 1219): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  951): acquireWL(3eb8cfe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(3eb8cfe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(39796601): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  951): releaseWL(39796601): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6711): MY_DEBUG = false
,D/SmartSyncUtils( 6711): isEpsOn(), nState = 0,
,D/PMS     (  951): acquireWL(3f3f0294): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6711 1000 null
,I/RemoteViews( 1219): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  951): releaseWL(3f3f0294): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  951): Init customizeScreenOffDelayClass error,
,I/RemoteViews( 1219): apply : com.htc.updater 0 16 1 36
,D/SurfaceControl(  951): Excessive delay in setPowerMode(): 300ms
E/qdutils (  384): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  951): Setting HAL interactive mode to false
E/qdutils (  384): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PMS     (  951): Setting HAL interactive mode to false done
D/PMS     (  951): Setting HAL auto-suspend mode to true
D/PMS     (  951): Setting HAL auto-suspend mode done
I/InputManager(  951): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/HABCtrl (  951): TPE algorithm. remove timeout.
D/PMS     (  951): OOBE c monitor 11,
I/InputMethodManagerService(  951): screenObserver, isScreenOn=false
D/StatusBarManagerService(  951): swetImeWindowStatus vis=0 backDisposition=0
W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  951): Disable input method client, pid=3261,
I/IntentController( 1219): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManager( 3261): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{5219b9d VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@f26645b
,W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/NfcService( 1447): ScreenObserver: OFF
,W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  951): acquireWL(3315613d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(3315613d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1447): applyRouting - 0
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): updateBatteryInfo
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/PMS     (  951): runPSCheck
D/WifiController(  951): handleMessage: E msg.what=155652
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): processMsg: DeviceActiveState
I/HtcPowerSaver(  951): >> updateStatus
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
,D/PMS     (  951): acquireWL(26b9aa83): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1447 1027 null
D/NfcService( 1447): applyRouting -2
D/NfcService( 1447): applyRouting
D/NfcService( 1447): Ignore this applyRouting...
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
D/SmartSyncUtils( 6711): isEpsOn(), nState = 0
D/SmartSyncUtils( 6711): isEpsOn(), nState = 0
,D/PMS     (  951): releaseWL(26b9aa83): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
D/PowerUI ( 1219): closing low battery warning: level=100
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@a1bc28d
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): disable: get sensor name = Accelerometer Sensor,
,W/SensorService(  951): pid=951, uid=1000,
W/SensorService(  951): Active sensors: size = 3
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@a1bc28d, eanble = 0, strlen(mName) = 35
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@18304df0
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  951): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  951): pid=951, uid=1000,
W/SensorService(  951): Active sensors: size = 2
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@a1bc28d, eanble = 0, strlen(mName) = 35
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@18304df0
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@a1bc28d
I/ClockController( 1219): stop clock update:screen off
E/ActivityThread(  951): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@926fc42 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  951): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@926fc42 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  951): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  951): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  951): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  951): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  951): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
,E/ActivityThread(  951): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  951): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  951): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  951): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  951): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  951): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  951): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  951): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,I/ActivityManager(  951): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6745 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 6711): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6711): gen(), null == sipper.uidObj, userId = 0,
,D/SmartSyncUtils( 6711): getMobilePolicyEnabled, result = true
I/ActivityManager(  951): Killing 6398:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=6398
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  951): New client listening to asynchronous messages
E/WifiTrafficPoller(  951): ADD_CLIENT: 8
,I/ActivityManager(  951): Recipient 6398
,D/PowerUsageList:PowerUsageHelper( 6711): MY_DEBUG = false
,D/Process (  951): killProcessQuiet, pid=5883,
I/ActivityManager(  951): Killing 5883:com.google.android.music:main/u0a159 (adj 15): empty #17,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL false Token 13 num clients 8,
,I/ActivityManager(  951): Recipient 5883
D/MediaRouterService(  951): Client com.google.android.music (pid 5883): Died!
,I/CalendarProvider2( 6681): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6681): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/PMS     (  951): releaseWL(fb60d20): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/ProviderChangeReceiver( 6236): ---------------------------------------------------
D/ProviderChangeReceiver( 6236): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/HtcAlertService( 6236): start to updateAlertNotification!
,D/Process (  951): killProcessQuiet, pid=6545,
I/ActivityManager(  951): Killing 6545:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6545
,D/WifiService(  951): Client connection lost with reason: 4
,D/HtcAlertService( 6236): No fired or scheduled alerts,
D/HtcAlertUtils( 6236): -- cancelReminderNotification --
,D/HtcAlertUtils( 6236): broadcastExistReminder!,
,D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL false Token 3,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState,
E/WifiStateMachine(  951):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:828942164] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:828942166] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): handleMessage: X
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:943] from screen [on:0 period:828943110] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:828943113] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): handleMessage: X
,D/HtcUPManager( 1219): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1431): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  951): Killing 5974:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=5974
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5974,
,D/PMS     (  951): acquireWL(137bd439): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10024},
V/AlarmManager(  951): sending alarm PendingIntent{2378ea7e: PendingIntentRecord{d626bdf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142308, Int=0
,D/PMS     (  951): releaseWL(137bd439): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  951): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  951): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  951): acquireWL(3d40102c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 951 1000 null
,D/libc    (  951): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  951): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  951): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  951): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  951): [NET] android_getaddrinfo_proxy+
D/libc    (  951): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  951): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  951): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  951): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  951): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  951): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  951): acquireWL(38b40318): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 951 1000 null
D/GpsLocationProvider(  951): [reportHTCStatus] INJECT_XTRA_DATA, status: 0,
D/PMS     (  951): releaseWL(3d40102c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  951):  [handleDownloadXtraData]inject done.
D/PMS     (  951): releaseWL(38b40318): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/GpsLocationProvider(  951): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  951): acquireWL(3a26d171): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null,
D/UsbnetService(  951): BroadcastReceiver::onReceive+
I/BatteryService(  951): n_update end
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PMS     (  951): releaseWL(3a26d171): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1219): closing low battery warning: level=100
D/WifiController(  951): processMsg: DeviceActiveState
D/HtcPowerSaver(  951): updateBatteryInfo
D/WifiController(  951): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DefaultState
D/PMS     (  951): runPSCheck
D/WifiController(  951): handleMessage: X
D/HtcPowerSaver(  951): Checking...
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  951): >> updateStatus
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1431): switchBindHtcMsgCursor: null,
,D/PMS     (  951): acquireWL(4bdcb56): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{3347f7d7: PendingIntentRecord{a7238c4 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=159561, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{2b8613ad: PendingIntentRecord{6e346e2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452527939025, Int=0,
V/AlarmManager(  951): sending alarm PendingIntent{219ec928: PendingIntentRecord{2ed60641 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165803, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{232a3a73: PendingIntentRecord{3ebc1d30 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192756, Int=0
,D/PMS     (  951): acquireWL(a1d3da9): PARTIAL_WAKE_LOCK  *backup* 0x1 951 1000 null
,D/PMS     (  951): acquireWL(10f2ef2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  951): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  951): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  951): releaseWL(a1d3da9): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  951): releaseWL(4bdcb56): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  951): acquireWL(27e40acf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(10f2ef2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  951): acquireWL(357df8e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(27e40acf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(357df8e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(77db606): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(77db606): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(ca084c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(1b75af4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(b2f2c92): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): releaseWL(ca084c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1908): Vacuum at: now=1452527967218 tag=VacuumService
,I/GoogleURLConnFactory( 1908): Using platform SSLCertificateSocketFactory,
,D/PMS     (  951): releaseWL(1b75af4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(23693260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1908): No account for auth token provided,
,D/PMS     (  951): releaseWL(23693260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(e9f148c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(e9f148c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1908): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1908): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1908): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1908): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1908): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1908): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1908): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1908): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1908): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1908): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1908): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1908): No account for auth token provided,
,W/Uploader( 1908): No account for auth token provided,
,W/Uploader( 1908):  no longer exists, so no auth token.,
,W/Uploader( 1908): No account for auth token provided,
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1908): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1908): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1908): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1908): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1908): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1908): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1908): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1908): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1219): reapply : com.google.android.gms 3 40
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  951): releaseWL(b2f2c92): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(10d7de42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(10d7de42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): acquireWL(1aadee53): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(1aadee53): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1565): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2280cce9
,D/Process (  951): killProcessQuiet, pid=6148
I/ActivityManager(  951): Killing 6148:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6148
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  951): acquireWL(1ddf390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
I/BatteryService(  951): n_update end
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  951): releaseWL(1ddf390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/NotificationService(  951): plugged=true pluggin=true
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  951): runPSCheck
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): handleMessage: E msg.what=155652
I/HtcPowerSaver(  951): >> updateStatus
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  951): acquireWL(1d16c489): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
,D/PMS     (  951): releaseWL(1d16c489): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PMS     (  951): runPSCheck
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  951): >> updateStatus
D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1219): closing low battery warning: level=100
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  951): << updateStatus
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1362): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1362): wlan0: BSS: Remove id 7 BSSID 00:37:b7:9d:3e:72 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age,
,D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11],
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:96]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:96
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:37:b7:9d:3e:72]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:37:b7:9d:3e:72
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  951): acquireWL(1d899c8e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{219ec928: PendingIntentRecord{2ed60641 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225802, Int=0
,V/AlarmManager(  951): sending alarm PendingIntent{2756b8bc: PendingIntentRecord{99e2045 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452528114299, Int=0
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data,
D/PMS     (  951): releaseWL(1d899c8e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  951): acquireWL(86f39a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
,D/PMS     (  951): releaseWL(86f39a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  951): plugged=true pluggin=true
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  951): battery changed pluggedType: 2
D/HeadsetStateMachine( 3185): Disconnected process message: 10, size: 0
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive BATTERY_CHANGED
,D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/HtcPowerSaver(  951): updateBatteryInfo
D/PMS     (  951): runPSCheck
,D/HtcPowerSaver(  951): Checking...
I/HtcPowerSaver(  951): >> updateStatus
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1908): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1908): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1908): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1908): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1908): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1908): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1908): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1908): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1908): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1908): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1908): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1908): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 1 40
,E/PlayEventLogger( 6359): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6359): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6359): Ignoring header User-Agent because its value was null.
,D/libc    ( 6359): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6359): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 6359): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6359): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6359): [NET] android_getaddrinfo_proxy+
D/libc    ( 6359): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6359): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,TIME-OUT KILL (timeout was 360000ms)
```
