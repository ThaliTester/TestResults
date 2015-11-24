#### Test 5133502860beea6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 258062260762; DSPS: 8597381; Offset : -4323127969
,D/AndroidRuntime( 6113): 
D/AndroidRuntime( 6113): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6113): CheckJNI is OFF
D/AndroidRuntime( 6113): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1030): create ActivityStackEx
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2c59a82 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2c59a82 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1412): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1412): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6133 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6113): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1866): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{1a81e107 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{2e472234 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 6133): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6133): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6133): Loading: webviewchromium
I/LibraryLoader( 6133): Time to load native libraries: 4 ms (timestamps 7396-7400)
I/LibraryLoader( 6133): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6133): Binding Chromium to main looper Looper (main, tid 1) {36a68550}
I/LibraryLoader( 6133): Expected native library version number "",actual native library version number ""
I/chromium( 6133): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6133): Initializing chromium process, renderers=0
W/art     ( 6133): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6133): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  315): registerClient() client 0xb1427220, uid 10311
W/chromium( 6133): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6133): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6133): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@98c92fc:true
D/BluetoothAdapter( 6133): 761615177: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6133): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6133): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6133): Build Date: 12/12/14 금
I/Adreno-EGL( 6133): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6133): Remote Branch: 
I/Adreno-EGL( 6133): Local Patches: 
I/Adreno-EGL( 6133): Reconstruct Branch: 
W/chromium( 6133): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6133): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6133): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6133): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6133): CordovaWebView is running on device made by: LGE
W/art     ( 6133): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6133): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{25c29593 u0 com.test.thalitest/.MainActivity t2}
D/LgDataFeature( 6133): LgDataFeature() Constructor: none
D/LgDataFeature( 6133): LgDataFeature() Constructor Done, null
I/art     ( 1030): Explicit concurrent mark sweep GC freed 26872(1241KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.181ms total 98.840ms
D/OpenGLRenderer( 6133): Render dirty regions requested: true
I/OpenGLRenderer( 6133): Initialized EGL, version 1.4
D/OpenGLRenderer( 6133): Enabling debug mode 0
D/Atlas   ( 6133): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{3b595656 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b772d2d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6133): Timeline: Activity_idle id: android.os.BinderProxy@342ca0b9 time:277870
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +652ms (total +772ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{25c29593 u0 com.test.thalitest/.MainActivity t2} time:277888
I/chromium( 6133): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6133): 
D/JsMessageQueue( 6133): Set native->JS mode to OnlineEventsBridgeMode
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 278063545678; DSPS: 9252784; Offset : -4323155335
I/chromium( 6133): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6133): 
D/jxcore_app_log( 6133): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435235584
D/JX-Cordova( 6133): jxcore cordova android initializing
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{10525973 type 0 when 1448361559823 com.android.vending} when 1448361559823
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Giving up after 6 failures.
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6133): Initializing JXcore engine
W/jxcore-log( 6133): JXcore engine is ready
,W/jxcore-log( 6133): Starting JXcore engine
,W/.test.thalitest( 6133): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10660]" dev="sockfs" ino=10660 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6133): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6133): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7565]" dev="sockfs" ino=7565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6133): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6133): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[30400]" dev="sockfs" ino=30400 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 6133): Background sticky concurrent mark sweep GC freed 122344(11MB) AllocSpace objects, 21(7MB) LOS objects, 28% free, 39MB/55MB, paused 4.093ms total 112.096ms
,W/jxcore-log( 6133): Platform android
W/jxcore-log( 6133): 
,W/jxcore-log( 6133): Process ARCH arm
W/jxcore-log( 6133): 
I/jxcore-log( 6133): JXcore Cordova bridge is ready!
I/jxcore-log( 6133): 
W/jxcore-log( 6133): JXcore engine is started
,I/jxcore-log( 6133): Toggling radios to true
I/jxcore-log( 6133): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6213 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager( 6213): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6213): Loading JNI Library
,D/BluetoothAdapterApp( 6213): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@22d05ee4 Instance Count = 1
,D/BluetoothAdapterApp( 6213): onCreate
D/ProfileConfigQcom( 6213): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 6213): Adding HeadsetService
D/ProfileConfigQcom( 6213): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6213): Adding A2dpService
D/ProfileConfigQcom( 6213): [BTUI] HidService is supported
D/ProfileConfigQcom( 6213): Adding HidService
D/ProfileConfigQcom( 6213): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6213): Adding HealthService
D/LGBluetoothFeatureConfig( 6213): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6213): [BTUI] PanService is supported
D/ProfileConfigQcom( 6213): Adding PanService
D/ProfileConfigQcom( 6213): [BTUI] GattService is supported
D/ProfileConfigQcom( 6213): Adding GattService
D/ProfileConfigQcom( 6213): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6213): Adding BluetoothMapService
D/ProfileConfigQcom( 6213): [BTUI] HeadsetClientService is NOT supported
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8022ade:true
D/BluetoothAdapterState( 6213): make
,I/LGFMServiceAdapter( 6213): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6213): init
I/BluetoothAdapterState( 6213): Entering OffState
I/bte_conf( 6213): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6213): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6213): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6213): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6213): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6213): get_profile_interface socket
I/bluedroid-qcom( 6213): get_profile_interface map_client
I/GKI_LINUX( 6213): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6213): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6213): Name is: G3-1
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6213): config_hci_snoop_log
,D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
W/bdaddr_loader( 6249): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6249): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6249): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6249): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6249): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr_loader ::: END
,V/LGMDMManagerInternal( 6213): Create singleton instance
D/BluetoothAdapterState( 6213): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6213): Setting state to 11
I/BluetoothAdapterState( 6213): Bluetooth adapter state changed: 10-> 11
,I/LGBluetoothServiceJni( 6213): classInitNative: succeeds
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6213): make
,D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/LGBluetoothServiceAdapter( 6213): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/LGBluetoothServiceAdapter( 6213): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6213): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6213): StableState(): Entering Off State
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6255 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothHeadset( 1030): Proxy object connected
,D/BluetoothHeadset( 1866): Proxy object connected
D/HeadsetService( 6213): Received start request. Starting profile...
D/BluetoothHeadset( 1866): Proxy object connected
D/BluetoothHeadset( 1866): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6213): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6213): Version 1.6
D/LGBluetoothFeatureConfig( 6213): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6213): classInitNative: succeeds
D/HeadsetStateMachine( 6213): make
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
,D/LgDataFeature( 6213): LgDataFeature() Constructor: none
D/LgDataFeature( 6213): LgDataFeature() Constructor Done, null
D/HeadsetStateMachine( 6213): max_hf_connections = 1
I/bluedroid-qcom( 6213): get_profile_interface handsfree
V/ToneGenerator( 6213): ToneGenerator constructor: streamType=8, volume=1.000000
,V/AudioPolicyService(  315): registerClient() client 0xb152e060, uid 1002
V/AudioPolicyManager(  315): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6213): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  315): registerClient() client 0xb5581688, pid 6213
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1458): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1458): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3296): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3296): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1458): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1458): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3296): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3296): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6213): ioConfigChanged() event 0, ioHandle 2
V/ToneGenerator( 6213): Create Track: 0xb4928080
V/AudioTrack( 6213): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6213): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6213): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AudioSystem( 6213): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6213): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6213): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6213): getLatency() output 2, latency 50
V/AudioSystem( 6213): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6213): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): createTrack() lSessionId: 16
V/AudioTrack( 6213): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  315): acquiring 16 from 6213, for 6213
V/AudioFlinger(  315):  added new, entry for 16
V/ToneGenerator( 6213): ToneGenerator INIT OK, time: 281046
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/BluetoothA2dp( 1030): Proxy object connected
D/A2dpService( 6213): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6213): classInitNative: succeeds
V/Avrcp   ( 6213): make
D/Avrcp   ( 6213): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6213): get_profile_interface avrcp
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
D/HeadsetStateMachine( 6213): Enter Disconnected: -2, size: 0
,D/HeadsetPhoneState( 6213): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6213): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6213): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  315): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6213
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
D/audio_hw_primary(  315): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  315): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: exit
V/voice   (  315): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  315): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  315): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  315): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  315): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6213): ToneGenerator destructor
V/ToneGenerator( 6213): stopTone
V/ToneGenerator( 6213): Delete Track: 0xb4928080
V/AudioTrack( 6213): ~AudioTrack, releasing session id from 6213 on behalf of 6213
V/AudioFlinger(  315): releasing 16 from 6213 for 6213
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
V/AudioPolicyService(  315): AudioCommandThread() adding release output 2
V/AudioPolicyService(  315): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  315): PlaybackThread::Track destructor
V/AudioPolicyService(  315): AudioCommandThread() waking up
V/AudioFlinger(  315): removeClient_l() pid 6213, calling pid 315
V/AudioPolicyService(  315): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  315): releaseOutput() 2
V/AudioPolicyService(  315): AudioCommandThread() going to sleep
V/AudioManager( 6213): registerRemoteController: size of Media player list: 0
E/AudioManager( 6213): No RCC entry present to update
E/RemoteController( 6213): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6213): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6213): initQcomNative: succeeds
,E/BluetoothAdapterService( 6213): File transfer profiles supported!!
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] [+] updateMediaPlayerInfo
E/BluetoothAdapterService( 6213): File transfer profiles supported!!
,V/LGMDMManager( 6213): Create singleton instance
I/BluetoothAdapterState( 6213): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
W/ResourcesManager( 6255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6255): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          playState: 2 (PAUSED)
,D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6213): classInitNative
I/BluetoothA2dpServiceJni( 6213): classInitNative: succeeds
D/A2dpStateMachine( 6213): make
I/bluedroid-qcom( 6213): get_profile_interface a2dp
,I/GKI_LINUX( 6213): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6213): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6213): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
I/BluetoothHidServiceJni( 6213): classInitNative: succeeds
,D/HidService( 6213): Received start request. Starting profile...
I/bluedroid-qcom( 6213): get_profile_interface hidhost
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/HeadsetStateMachine( 6213): Proxy object connected
D/LGBluetoothHfpAdapter( 6213): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6213): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1866):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1866): Proxy not attached to service
D/BluetoothHeadset( 1866): java.lang.Throwable
D/BluetoothHeadset( 1866): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1866): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1866): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.gatt.GattService
I/BluetoothHealthServiceJni( 6213): classInitNative: succeeds
D/HeadsetStateMachine( 6213): Disconnected process message: 10, size: 0
D/A2dpStateMachine( 6213): Enter Disconnected: -2
D/HealthService( 6213): Received start request. Starting profile...
D/HeadsetPhoneState( 6213): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 6213): Disconnected process message: 11, size: 0
I/bluedroid-qcom( 6213): get_profile_interface health
,I/LGBluetoothHealthServiceJni( 6213): classInitNative: succeeds
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
I/BluetoothPanServiceJni( 6213): classInitNative(L105): succeeds
D/PanService( 6213): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6213): initializeNative(L110): pan
I/bluedroid-qcom( 6213): get_profile_interface pan
I/ActivityManager( 1030): Killing 5834:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5834/cgroup.procs: No such file or directory
,I/LGBluetoothPanAdapter( 6213): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
I/BtGatt.JNI( 6213): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6213): handleDebugAction() action=null
,D/BtGatt.GattService( 6213): Received start request. Starting profile...
D/BtGatt.GattService( 6213): start()
I/bluedroid-qcom( 6213): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6213): advertise manager created
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
,D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
I/LGBluetoothMapAdapter( 6213): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6213): BluetoothMapBinder()
D/BluetoothMapService( 6213): Received start request. Starting profile...
D/BluetoothMapService( 6213): start()
D/BluetoothMapEmailSettingsLoader( 6213): Found 0 applications
D/BluetoothMapEmailAppObserver( 6213): createReceiver()
D/BluetoothMapEmailAppObserver( 6213): initObservers()
,D/BluetoothMapEmailAppObserver( 6213): getEnabledAccountItems()
,D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.gatt.GattService
V/BluetoothPbapReceiver( 6213): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6213): ***********state = 11
V/PanService( 6213): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6213): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,V/BluetoothMapService( 6213): Handler(): got msg=1
D/BluetoothAdapterState( 6213): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6213): enable
I/GKI_LINUX( 6213): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6213): btu_task pending for preload complete event
I/bt_hci_bdroid( 6213): init
I/bt_vendor( 6213): bt-vendor : init
I/bt_vendor( 6213): bt-vendor : get_bt_soc_type
,E/bt_vendor( 6213): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6213): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6213): userial_init
D/bt_hci_bdroid( 6213): set_power 1
I/bt_vendor( 6213): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6213): Starting hciattach daemon
I/bt_vendor( 6213): try to set true
W/sh      ( 6299): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6299): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6301 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/qcom-bluetooth( 6300): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 6323): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6324): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6326): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/ActivityThread( 6301): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6301): No ProfileInfo entries
I/LG Account v2.2( 6301): isEnabled: false
I/Feature ( 6301): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6301): [Lifetracker]Country: EU
I/Feature ( 6301): [Lifetracker]Operator: OPEN
I/Feature ( 6301): [Lifetracker]Ranking support: false
I/Feature ( 6301): [Lifetracker]Comfort support: false
I/Feature ( 6301): [Lifetracker]Accessory: true
I/Feature ( 6301): [Lifetracker]Health device: true
I/Feature ( 6301): [Lifetracker]Extra Pedometer: false
I/Feature ( 6301): [Lifetracker]Blood glucose device: false
I/Feature ( 6301): [Lifetracker]Device Number: 3
I/qcom-bluetooth( 6329): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6330): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6331): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/BluetoothPermissionRequest( 6255): onReceive
D/LGBluetoothFeatureConfig( 6255):  get() - isFeatureLoaded : false
I/libmdmdetect( 6333): ESOC framework not supported
E/Diag_Lib( 6333):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27f9fc6d:true
D/LGBluetoothResetSettingReceiver( 6255): return without doing reset settings.
I/ActivityManager( 1030): Killing 5505:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/bthci_qcomm_linux( 6333): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6333): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6333): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6333): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6333): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6333): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6333): [BTUI] init_riva_entries: set NORMAL power settings
,I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/LGBluetoothOppAdapter( 6213): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5505/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6213): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6213): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6213): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 6213): SapReceiver onReceive 
V/BluetoothSapReceiver( 6213): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6213):  Bluetooth Adapter state = 11
,I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6337 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  306): 
,I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  897): [IMS_FATAL]| 3347 | 911 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/ResourcesManager( 6337): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Killing 5525:com.android.contacts/u0a19 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5525/cgroup.procs: No such file or directory
E/QC-QMI  ( 6333): qmi_client [6333] 13: failed to locate client data
E/QC-QMI  (  475): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  475): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,I/qcom-bluetooth( 6368): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6369): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6213): bluetooth satus is on
D/bt_hci_bdroid( 6213): preload
D/bt_userial_mct( 6213): userial_open(port:0)
I/bt_vendor( 6213): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6213): Done intiailizing UART
I/bt_vendor( 6213): Done intiailizing UART
I/bt_userial_mct( 6213): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6213): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6213): Entering userial_read_thread()
I/bt-btu  ( 6213): btu_task received preload complete event
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6213): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6213): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6213): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6213): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6213): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6213): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6213): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6213): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6213): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6213): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6213): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6213): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6213): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6213): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6213): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6213): BTE_InitTraceLevels -- TRC_BTIF
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6133): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6133): 
I/jxcore-log( 6133): my name is : LGE-LG-D855_PT9543
I/jxcore-log( 6133): 
W/bt-btm  ( 6213): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6213): BTM_SecRegister:p_cb_info->p_le_callback == 0xa013b061 
E/bt-btm  ( 6213): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa013b061 
,I/jxcore-log( 6133): attempting to connect to test coordinator
I/jxcore-log( 6133): 
I/jxcore-log( 6133): check test folder
I/jxcore-log( 6133): 
I/jxcore-log( 6133): found test : ./testFindPeers.js
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): found test : ./testReConnect.js
I/jxcore-log( 6133): 
E/bt-btif ( 6213): Calling BTA_HhEnable
E/bt-btif ( 6213): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 6213): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0017
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
I/jxcore-log( 6133): found test : ./testSendData.js
I/jxcore-log( 6133): 
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6213): Name is: G3-1
D/BluetoothAdapterProperties( 6213): Scan Mode:20
D/BluetoothAdapterProperties( 6213): Discoverable Timeout:120
D/bt_hci_bdroid( 6213): postload
D/bt_hci_bdroid( 6213): Used up Tx Cmd credits
W/bt-l2cap( 6213): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6213): Used up Tx Cmd credits
D/bt_hci_bdroid( 6213): Used up Tx Cmd credits
D/bt_hci_bdroid( 6213): Used up Tx Cmd credits
E/bt_mct  ( 6213): hci lib postload completed
,D/bte_conf( 6213): Device ID record 1 : primary
D/bte_conf( 6213):   vendorId            = 00c4
D/bte_conf( 6213):   vendorIdSource      = 0001
D/bte_conf( 6213):   product             = 13a1
D/bte_conf( 6213):   version             = 1000
D/bte_conf( 6213):   clientExecutableURL = 
D/bte_conf( 6213):   serviceDescription  = 
D/bte_conf( 6213):   documentationURL    = 
D/bte_conf( 6213): bte_load_did_conf no section named DID2.
W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = 61 56 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = 14 7f e6 3d ca 47 be b4 4a c0 e5 45 af 0b f1 5f 
W/bt-btm  ( 6213): Stopping oneshot timer
D/BluetoothAdapterState( 6213): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6213): ScanMode =  20
D/BluetoothAdapterProperties( 6213): State =  11
D/BluetoothAdapterProperties( 6213): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6213): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6213): Setting state to 12
I/BluetoothAdapterState( 6213): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 6213): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6213): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/sh      ( 6374): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
W/sh      ( 6374): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/BluetoothAdapterState( 6213): Entering On State
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothServiceAdapter( 6213): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6213): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6213): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6213): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 6213): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6213): STATE_ON
,V/BluetoothMapService( 6213): Handler(): got msg=1
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 1
D/LGBluetoothAPIService( 1961): MESSAGE_BOOT_COMPLETED
I/jxcore-log( 6133): Test app app.js loaded
I/jxcore-log( 6133): 
W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = 12 f6 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = ab ae d1 88 be 8b 35 83 f7 31 61 f4 73 14 cb b7 
W/bt-btm  ( 6213): Stopping oneshot timer
D/BluetoothMapMasInstance( 6213): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6213): MAS initSocket()
D/BluetoothMapMasInstance( 6213):   masId = 00
D/BluetoothMapMasInstance( 6213):   msgTypes = 0e
D/BluetoothMapMasInstance( 6213):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6213):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6213): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6213): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6213): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6213): Accepting socket connection...
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = b8 1d 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = 0a 65 1c 2d d9 dd 15 97 84 56 8c ce 7c f3 6d 11 
W/bt-btm  ( 6213): Stopping oneshot timer
I/Choreographer( 6133): Skipped 149 frames!  The application may be doing too much work on its main thread.
,I/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothDeviceModeControllManager( 6213): [BTUI] checkDeviceModeAndSet, sinkMode : false
,W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = c7 be 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = 1b 72 72 2f 9f 0a 23 ab b1 d7 a4 db 96 a1 a4 8f 
W/bt-btm  ( 6213): Stopping oneshot timer
I/chromium( 6133): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/qcom-bt-wlan-coex( 6390): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,W/ContextImpl( 6255): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/chromium( 6133): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
V/BluetoothPbapService( 6213): Pbap Service onCreate
V/BluetoothPbapService( 6213): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6213): [BTUI] getInstance : create
D/LocalBluetoothProfileManager( 6255): Adding local A2DP profile
V/BluetoothPbapService( 6213): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6213): state: 12
W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = aa 09 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = ac a2 d9 ff f9 c8 58 01 24 6c 08 da 22 ac 89 08 
W/bt-btm  ( 6213): Stopping oneshot timer
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6255): Adding local HEADSET profile
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6255): Adding local MAP profile
,D/BluetoothMap( 6255): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6255): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6255): [BTUI] initUserBindClient
W/ContextImpl( 6255): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6255): finishStartingService: stopping service
D/BluetoothA2dp( 6255): Proxy object connected
D/A2dpProfile( 6255): Bluetooth service connected
D/LGBluetoothAPIServer( 6213): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6213): [BTUI] onBind()
D/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapReceiver( 6213): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 100
V/BluetoothPbapReceiver( 6213): ***********state = 12
D/LGBluetoothAPIService( 1961): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,V/BluetoothPbapService( 6213): Handler(): got msg=1
V/BluetoothPbapService( 6213): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6213): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothHeadset( 6255): Proxy object connected
V/BluetoothPbapService( 6213): Pbap Service onBind
W/BluetoothAdapter( 6213): getBluetoothService() called with no BluetoothManagerCallback
D/HeadsetProfile( 6255): Bluetooth service connected
D/BluetoothAdapterProperties( 6213): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6213): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/LGBluetoothServiceAdapter( 6213): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6213): Succeed to create listening socket 
V/BluetoothPbapService( 6213): Accepting socket connection...
D/BluetoothAdapterProperties( 6213): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6213): getDeviceMode  deviceMode 0
D/BluetoothInputDevice( 6255): Proxy object connected
D/HidProfile( 6255): Bluetooth service connected
D/BluetoothPan( 6255): BluetoothPAN Proxy object connected
D/PanProfile( 6255): Bluetooth service connected
,D/BluetoothMap( 6255): Proxy object connected
D/MapProfile( 6255): Bluetooth service connected
D/BluetoothMap( 6255): getConnectedDevices()
V/BluetoothMapService( 6213): getConnectedDevices()
D/BluetoothPbap( 6255): Proxy object connected
D/PbapServerProfile( 6255): Bluetooth service connected
D/LGBluetoothUserBindClient( 6255): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6255): onReceive
D/LGBluetoothFeatureConfig( 6255): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6255): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6255): return without doing reset settings.
V/BluetoothOppReceiver( 6213): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6213): [BTUI] startOppService()
V/BluetoothOppManager( 6213): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6213): isPrivacyLogsEnabled : true
V/BtOppService( 6213): onCreate
,V/BluetoothOppNotification( 6213): send message
V/BtOppService( 6213): Starting RfcommListener
D/BluetoothOppPreference( 6213): Dumping Names:  
D/BluetoothOppPreference( 6213): {}
D/BluetoothOppPreference( 6213): Dumping Channels:  
D/BluetoothOppPreference( 6213): {}
V/BtOppService( 6213): onStartCommand
V/BluetoothFtpReceiver( 6213): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6213): BluetoothFtpReceiver Start Service
V/BtOppService( 6213): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BtOppService( 6213): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6213): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6213): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 6213): new notify threadi!
V/BluetoothOppNotification( 6213): send delay message
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@25fbf8d1 on behalf of 
V/BtOppService( 6213): start RfcommListener
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@34becf36 on behalf of 
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6213): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@1224de37 on behalf of 
V/BtOppService( 6213): RfcommListener started
V/BtOppService( 6213): ContentObserver received notification
V/BtOppRfcommListener( 6213): Starting RFCOMM listener....
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 6213): pendingUpdate is true keepUpdateThread is false sListenStarted is true
W/BluetoothAdapter( 6213): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6213): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6213): Started RFCOMM listener....
I/BtOppRfcommListener( 6213): Accept thread started.
V/BtOppRfcommListener( 6213): Accepting connection...
V/BluetoothOppNotification( 6213): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@af18fa4 on behalf of 
,V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppNotification( 6213): update too frequent, put in queue
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@3f76510d on behalf of 
V/BluetoothOppNotification( 6213): outbound: succ-0  fail-0
V/BtOppService( 6213): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6213): outbound notification was removed.
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@f20a8c2 on behalf of 
V/BluetoothOppNotification( 6213): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6213): inbound notification was removed.
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@2c5f26d3 on behalf of 
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
V/BluetoothFtpService( 6213): Ftp Service onCreate
I/BluetoothFtpService( 6213): Ftp Service onCreate
,V/BluetoothFtpService( 6213): Ftp Service onStartCommand
V/BluetoothFtpService( 6213): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 6213): Starting Listening on sockets
V/BtOppService( 6213): ContentObserver received notification
V/BluetoothSapReceiver( 6213): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6213): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6213): SapReceiver onReceive 
V/BluetoothSapReceiver( 6213): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6213):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6213): Calling SAP service start service with action = null
V/BtOppService( 6213): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothFtpService( 6213): Handler(): got msg=1
V/BluetoothFtpService( 6213): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6213): Ftp Service initSocket
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@3bc3f109 on behalf of 
V/BluetoothOppNotification( 6213): update too frequent, put in queue
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/BtOppService( 6213): pendingUpdate is false keepUpdateThread is false sListenStarted is true
W/BluetoothAdapter( 6213): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6213): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6213): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6213): Run Accept thread
D/BluetoothAdapterService( 6213): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cb7296f
V/BluetoothSapService( 6213): Sap Service onCreate
,V/BluetoothSapService( 6213): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6213): state: 12
V/BluetoothSapService( 6213): Starting SAP server process
V/BluetoothSapService( 6213): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6213): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/sapd    ( 6411): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/BluetoothAdapter( 6213): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6411): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGBluetoothServiceAdapter( 6213): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6213): Succeed to create listening socket 
V/BluetoothSapService( 6213): Accepting socket connection...
,V/BT_SAP  ( 6411): Event pipe created
V/BT_SAP  ( 6411): create_server_socket qcom.sap.server
V/BT_SAP  ( 6411): created socket fd 6
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/BluetoothOppNotification( 6213): new notify threadi!
V/BluetoothOppNotification( 6213): send delay message
,V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@73194c5 on behalf of 
,V/BluetoothOppNotification( 6213): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@ce8e1a on behalf of 
V/BluetoothOppNotification( 6213): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6213): outbound notification was removed.
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@95a9d4b on behalf of 
V/BluetoothOppNotification( 6213): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6213): inbound notification was removed.
V/BluetoothOppProvider( 6213): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6213): created cursor android.database.sqlite.SQLiteCursor@a840328 on behalf of 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 298065828900; DSPS: 9908219; Offset : -4323160880
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 318067997174; DSPS: 10563649; Offset : -4323128705
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 338070243260; DSPS: 11219083; Offset : -4323140894
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4906): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 358072132367; DSPS: 11874505; Offset : -4323143747
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{7b85e2d type 2 when 347686 com.google.android.gms} when 347686
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 378073806057; DSPS: 12529920; Offset : -4323148524
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 16154(829KB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 3.095ms total 155.808ms
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 398075993028; DSPS: 13185352; Offset : -4323159209
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 418078113177; DSPS: 13840781; Offset : -4323144564
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 438084276868; DSPS: 14496343; Offset : -4323145321
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 458086281860; DSPS: 15151769; Offset : -4323154411
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 478088551383; DSPS: 15807203; Offset : -4323143189
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 498090751636; DSPS: 16462635; Offset : -4323140279
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 518092986421; DSPS: 17118068; Offset : -4323133381
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 538095157090; DSPS: 17773499; Offset : -4323129174
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 558097365936; DSPS: 18428932; Offset : -4323148319
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 578098632647; DSPS: 19084334; Offset : -4323163477
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 598101385505; DSPS: 19739784; Offset : -4323157096
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 618103609974; DSPS: 20395216; Offset : -4323129972
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 638105513093; DSPS: 21050639; Offset : -4323149459
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/ActivityManager( 1030): Killing 5855:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5855/cgroup.procs: No such file or directory
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 658107715533; DSPS: 21706071; Offset : -4323143946
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 678109937505; DSPS: 22361504; Offset : -4323150097
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 698111610310; DSPS: 23016919; Offset : -4323155394
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 718113793948; DSPS: 23672350; Offset : -4323138868
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 738115900972; DSPS: 24327779; Offset : -4323137480
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3cc8d4e3 type 2 when 673282 com.google.android.gms} when 673282
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 758117940912; DSPS: 24983206; Offset : -4323142164
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 778120752675; DSPS: 25638658; Offset : -4323137915
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 798122887408; DSPS: 26294088; Offset : -4323139517
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 818124779118; DSPS: 26949510; Offset : -4323139818
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 838126935569; DSPS: 27604941; Offset : -4323150298
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 858128869155; DSPS: 28260364; Offset : -4323139214
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 878131364512; DSPS: 28915806; Offset : -4323146221
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 898133369193; DSPS: 29571232; Offset : -4323155909
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 918135080487; DSPS: 30226648; Offset : -4323153625
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 938137255895; DSPS: 30882079; Offset : -4323144704
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
,D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 958139310471; DSPS: 31537506; Offset : -4323134858
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 978142089839; DSPS: 32192957; Offset : -4323132616
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 998144254259; DSPS: 32848388; Offset : -4323134866
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1018146486125; DSPS: 33503821; Offset : -4323130861
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1038148714867; DSPS: 34159255; Offset : -4323160550
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1058150654757; DSPS: 34814678; Offset : -4323143190
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1078152754384; DSPS: 35470107; Offset : -4323149275
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1098154700157; DSPS: 36125531; Offset : -4323156341
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1118156912181; DSPS: 36780963; Offset : -4323141947
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1138159106027; DSPS: 37436395; Offset : -4323145184
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1158161477218; DSPS: 38091833; Offset : -4323154338
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1178163674138; DSPS: 38747265; Offset : -4323154762
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{a84770d type 2 when 1182712 com.android.bluetooth} when 1182712
,W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = 2a ec 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = 41 d3 ef b7 74 5c c4 07 5e 18 6f 5e 00 27 39 e3 
W/bt-btm  ( 6213): Stopping oneshot timer
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1198165630380; DSPS: 39402689; Offset : -4323151880
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1218167751518; DSPS: 40058118; Offset : -4323136403
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/UsageStatsService( 1030): User[0] Flushing usage stats to disk
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1238169994114; DSPS: 40713552; Offset : -4323152055
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1258172168534; DSPS: 41368983; Offset : -4323144357
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1278174086912; DSPS: 42024406; Offset : -4323148769
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1298175534769; DSPS: 42679813; Offset : -4323135029
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1318177761219; DSPS: 43335246; Offset : -4323136364
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6213): Disconnected process message: 10, size: 0
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1338179971472; DSPS: 43990679; Offset : -4323153971
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1358182157038; DSPS: 44646110; Offset : -4323134998
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1378184892447; DSPS: 45301560; Offset : -4323146170
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1398187157387; DSPS: 45956994; Offset : -4323139505
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1418189176702; DSPS: 46612420; Offset : -4323134377
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1438191243935; DSPS: 47267848; Offset : -4323142364
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{8c97927 type 2 when 1061771 com.google.android.gms} when 1061771
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3bdca7d4 type 2 when 1355367 com.google.android.gms} when 1355367
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PerfProfileCollectorService( 2355): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 2355): removeStateFiles() called
D/PerfProfileCollectorService( 2355): User is not opt-in to Usage & Diagnostics.
,I/VacuumService( 2126): Vacuum at: now=1448362731677 tag=VacuumService
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1458193557156; DSPS: 47923284; Offset : -4323148635
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1478195473137; DSPS: 48578707; Offset : -4323155209
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1498197638911; DSPS: 49234138; Offset : -4323155898
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1518199582132; DSPS: 49889561; Offset : -4323135596
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1538202509729; DSPS: 50545017; Offset : -4323137505
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1558204695607; DSPS: 51200449; Offset : -4323149022
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1578206851068; DSPS: 51855879; Offset : -4323129767
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1598209047310; DSPS: 52511311; Offset : -4323130764
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1618211867043; DSPS: 53166764; Offset : -4323149166
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1638213807868; DSPS: 53822187; Offset : -4323131104
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1658215974111; DSPS: 54477618; Offset : -4323131296
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1678218028217; DSPS: 55133046; Offset : -4323152568
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1698219939042; DSPS: 55788468; Offset : -4323133703
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1718222237786; DSPS: 56443904; Offset : -4323154503
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1738224314913; DSPS: 57099332; Offset : -4323152468
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1758226326625; DSPS: 57754758; Offset : -4323154994
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1778228296669; DSPS: 58410182; Offset : -4323138049
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1798230652443; DSPS: 59065619; Offset : -4323132102
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1818232498477; DSPS: 59721040; Offset : -4323147615
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1838234670552; DSPS: 60376471; Offset : -4323142261
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1030): Prepared write state in 11ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34becf36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService( 1030): Pruning old procstats: /data/system/procstats/state-2015-11-23-16-36-43.bin
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1858236857523; DSPS: 61031903; Offset : -4323152451
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1878238959443; DSPS: 61687332; Offset : -4323156348
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1898241838029; DSPS: 62342786; Offset : -4323146493
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1918243924897; DSPS: 62998214; Offset : -4323134743
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1938246278743; DSPS: 63653652; Offset : -4323161398
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1958248458214; DSPS: 64309083; Offset : -4323148544
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1978250824979; DSPS: 64964520; Offset : -4323131556
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1998252886741; DSPS: 65619948; Offset : -4323145093
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{17355fff type 0 when 1448363146762 com.google.android.gms} when 1448363146762
I/ActivityManager( 1030): Killing 5607:com.google.android.apps.plus/u0a97 (adj 15): empty for 1888s
,I/ActivityManager( 1030): Killing 5574:com.lge.lockscreensettings/u0a80 (adj 15): empty for 1888s
,I/ActivityManager( 1030): Killing 5901:com.google.android.apps.docs/u0a61 (adj 15): empty for 1888s
,I/ActivityManager( 1030): Killing 5765:com.android.defcontainer/u0a4 (adj 15): empty for 1890s
,I/ActivityManager( 1030): Killing 5882:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 1889s
,I/ActivityManager( 1030): Killing 5174:com.wsandroid.suite.lge/1000 (adj 15): empty for 1890s
,I/ActivityManager( 1030): Killing 5551:com.android.gallery3d/u0a27 (adj 15): empty for 1890s
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5607/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5901/cgroup.procs: No such file or directory
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5765/cgroup.procs: No such file or directory
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5882/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5174/cgroup.procs: No such file or directory
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5551/cgroup.procs: No such file or directory
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5574/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
I/EventLogService( 2355): Aggregate from 1448361346682 (log), 1448361346682 (data)
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 37068(2MB) AllocSpace objects, 13(1872KB) LOS objects, 51% free, 30MB/62MB, paused 797us total 32.905ms
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2018255049858; DSPS: 66275379; Offset : -4323148515
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2038256827403; DSPS: 66930797; Offset : -4323141198
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2058258916145; DSPS: 67586225; Offset : -4323127495
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2078261553272; DSPS: 68241672; Offset : -4323145449
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=99836595, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3ce0630b type 2 when 2082741 com.android.bluetooth} when 2082741
,W/bt-smp  ( 6213): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6213): Plain text(LSB ~ MSB) = e8 44 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6213): Encrypted text(LSB ~ MSB) = 59 ad f0 35 62 32 49 b2 ea 7c 83 98 ce 38 7a a8 
W/bt-btm  ( 6213): Stopping oneshot timer
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=99836595 [*alarm*], flags=0x0
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 6133): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6133): 
D/AndroidRuntime( 6831): 
D/AndroidRuntime( 6831): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6831): CheckJNI is OFF
D/AndroidRuntime( 6831): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 6133:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1030): WIN DEATH: Window{3b595656 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1030): Window went away: Window{3b595656 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1030): Skipping PackageSetting{9845686 com.example.hello/10318} due to missing metadata
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{25c29593 u0 com.test.thalitest/.MainActivity t2}
E/GBMv2   (  340): DFP En is all cleared set to be enabled
W/ActivityManager( 1030): Spurious death for ProcessRecord{2f39b5e8 6133:com.test.thalitest/u0a311}, curProc for 6133: null
I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{25c29593 u0 com.test.thalitest/.MainActivity t2 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{25c29593 u0 com.test.thalitest/.MainActivity t2 f}
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2083): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{268465d2 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{fd186a3 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2083): [Launcher.java:903:onResume()]onResume
D/SplitWindowManager( 1030): removeStackAndNeedHomeResume ActivityStack{a6f5401 stackId=1, 0 tasks}
I/[LGHome]EVENT( 2083): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1918): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2716): handleMessage: what(1000) actionID(0x1000003)
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2039): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2716): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] [+] updateMediaPlayerInfo
I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6856 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2083): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     ( 4254): Explicit concurrent mark sweep GC freed 15060(865KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 532us total 53.863ms
W/System.err( 4208): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4208): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4208): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4208): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4208): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4208): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4208): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4208): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4208): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4208): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6879 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2083): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1458): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2083): [Launcher.java:1114:onPause()]onPause
I/art     ( 1030): Explicit concurrent mark sweep GC freed 36872(2MB) AllocSpace objects, 14(1159KB) LOS objects, 33% free, 44MB/67MB, paused 5.503ms total 187.697ms
I/art     ( 1030): WaitForGcToComplete blocked for 154.873ms for cause Explicit
D/ActionManagerService( 1918): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2716): handleMessage: what(1000) actionID(0x1000004)
D/SplitUIManager( 1883): split_name #11 / not available #0
D/SplitUIService( 1883): removed split : 
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2716): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
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
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2083): , create_time: 1447937694406
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
D/WallpaperManager( 2083): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1458): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b772d2d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/administrator( 1030): Handling package changes for user 0
D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/LockScreenSettings( 6879): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2098264416287; DSPS: 68897126; Offset : -4323150566
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
W/ResourcesManager( 6856): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/PluginManager( 6856): init()
I/ActivityManager( 1030): Killing 5944:com.lge.eula/1000 (adj 15): empty for 1981s
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/art     ( 1030): Explicit concurrent mark sweep GC freed 8841(494KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.928ms total 182.543ms
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1458): handleShortcutListChanged...
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5944/cgroup.procs: No such file or directory
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6213): [BTUI] [-] updateMediaPlayerInfo
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[LGHome]EVENT( 2083): [Launcher.java:5349:onStop()]onStop
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1030): removeObsoleteFile: deleting file=2_task.xml
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): handleShortcutListChanged...
I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3125): Thermal-Lib-Client: Client request sent
D/AndroidRuntime( 6831): Shutting down VM
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{35e4b15d u0 com.lge.launcher2/.Launcher t1} time:2098480
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2083): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2607): onStartCommand(). Type : 8
D/[Concierge]Service( 2607): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2607): Update widget ID : 11
D/[Concierge]WidgetView( 2083): change position of spinner
I/[Concierge]WidgetView( 2083): initWebView(). Time : 1448363390989
D/[Concierge]Service( 2607): onStartCommand(). Type : 0
I/[Concierge]WebView( 2083): Return exist ConciergeWebView. Reuse : 141574661
D/[Concierge]WidgetView( 2083): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2083): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@32a21ee9
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2083): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2083): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2083): Widget kill message received. Destory myself. My : 1448361320826, New one : 1448363390989
D/[Concierge]WidgetView( 2083): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2083): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ExternalStrings( 6856): load override strings
W/ExternalStrings( 6856): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6856): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6856): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6856): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6856): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6856): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6856): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6856): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6856): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6856): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6856): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6856): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6856): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6856): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6856): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6856): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6856): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6856): onCreate
I/Timeline( 2083): Timeline: Activity_idle id: android.os.BinderProxy@214e2e79 time:2098634
V/Signer  ( 6856): override build config not found
D/Signer  ( 6856): value of property debug is false
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6856): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6856): Create singleton instance
D/LGMDMWrapper( 6856): LG MDM library v4.0.0 is available on this device.
I/chromium( 2083): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/PostponalbeReceiver( 6856): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 6856): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/GBoardtInterface( 2083): onReloaded()
I/GBoardWebViewClient( 2083): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6912 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5966:com.lge.bnr/1000 (adj 15): empty for 1981s
I/art     (  344): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 12.762ms
I/art     (  344): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.209ms

```
