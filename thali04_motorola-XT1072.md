#### Test 6216742584ac8ae_thali04_motorola-XT1072 Logs


```
--------- beginning of system
D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=312, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312030, SEQNUM=4340, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-122, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,--------- beginning of main
D/AndroidRuntime( 5185): 
D/AndroidRuntime( 5185): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5185): CheckJNI is OFF
D/AndroidRuntime( 5185): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5185): Shutting down VM
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5204 uid=10563 gids={50563, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5204): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5204): Time to load native libraries: 3 ms (timestamps 3764-3767)
I/LibraryLoader( 5204): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5204): Binding Chromium to main looper Looper (main, tid 1) {131ee8f1}
I/LibraryLoader( 5204): Expected native library version number "",actual native library version number ""
I/chromium( 5204): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5204): Initializing chromium process, singleProcess=true
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5204): ApplicationContext is null in ApplicationStatus
,W/chromium( 5204): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5204): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5204): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5204): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5204): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5204): Local Branch: 
I/Adreno-EGL( 5204): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5204): Local Patches: NONE
I/Adreno-EGL( 5204): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@311b45bd:true
,D/BluetoothAdapter( 5204): 136110178: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5204): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5204): CordovaWebView is running on device made by: motorola
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5204): Render dirty regions requested: true
,D/Atlas   ( 5204): Validating map...
,W/chromium( 5204): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5204): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5204): Enabling debug mode 0
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1051
,I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s52ms
,I/Keyboard.Facilitator( 1408): onFinishInput()
,E/Adreno-ES20( 5204): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5204): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5204): Cannot call determinedVisibility() - never saw a connection for the pid: 5204
,D/JsMessageQueue( 5204): Set native->JS mode to OnlineEventsBridgeMode
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (21:295 vsyncs) (23:1039)
,E/Adreno-ES20( 5204): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5204): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5204): JniHelper::setJavaVM(0xb71ee310), pthread_self() = -1219006448
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc37c2 added. We now have 1 listener(s)
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5204): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5204): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5204): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14640c09 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5204): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5204): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,D/WifiService(  884): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5204): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5204): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5204): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5204): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:34000 mC
,W/jxcore-log( 5204): Initializing JXcore engine
W/jxcore-log( 5204): JXcore engine is ready
,W/Thread-605( 5267): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10563 path="socket:[7366]" dev="sockfs" ino=7366 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5267): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10563 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-605( 5267): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10563 path="socket:[9683]" dev="sockfs" ino=9683 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5267): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10563 path="socket:[23254]" dev="sockfs" ino=23254 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5204): Starting JXcore engine
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/SFPerfTracer(  279):      triggers: (rate: 13:506) (compose: 0:1) (post: 0:1) (render: 0:2) (16:989 frames) (17:1077)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb78bc558): 0:14)* (DimLayer (0xb78f0cd0): 0:6)* (StatusBar (0xb79203e8): 0:179) (NavigationBar (0xb7921d50): 0:37) (com.android.systemui.ImageWallpaper (0xb7951dc8): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7954cc8): 0:55)- (Starting com.test.thalitest (0xb7953a38): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb78f3de8): 17:53) 
,V/AlarmManager(  884): send {196e8aba, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  884): send {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {196e8aba, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [10ms]
,V/AlarmManager(  884): done {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [12ms]
,D/Finsky  ( 5017): [585] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5017): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/CdsService( 2472): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2472): [i] > Retry handler returned true; Retry web request after backoff time: 30000
,D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,W/jxcore-log( 5204): Platform android
W/jxcore-log( 5204): 
W/jxcore-log( 5204): Process ARCH arm
W/jxcore-log( 5204): 
,I/jxcore-log( 5204): JXcore Cordova bridge is ready!
I/jxcore-log( 5204): 
,W/jxcore-log( 5204): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5204): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2472):  Nonce Reponse 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: nonce.json
D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5204): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 5204): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 5204): BLE multiple advertisement supported
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): My device name is: motorola-XT1072
I/jxcore-log( 5204): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,V/AlarmManager(  884): send {ddb4403, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {ddb4403, *alarm*:android.intent.action.TIME_TICK} [33ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  884): BstSensorExt: id=1598182242, en=0
D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb7818550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  884): Display changed displayId=0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8be8820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1195473608)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1195473608) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8be8820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  884): Excessive delay in setPowerMode(): 322ms
I/PowerManagerService(  884): Sleeping (uid 1000)...
,I/WindowManager(  884): AOD feature not enabled!
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e6589c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb71ee310, mCls = 0x2012c2
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
E/msm8974_platform(  296): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e6589c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb71ee310, mCls = 0x2012aa
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
,E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,D/CdsService( 2472): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2472): [i] > Retry handler returned true; Retry web request after backoff time: 60000
D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5204): 
,I/art     (  884): Explicit concurrent mark sweep GC freed 16594(862KB) AllocSpace objects, 5(323KB) LOS objects, 33% free, 20MB/30MB, paused 1.652ms total 129.993ms
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5204): 
,I/io.jxcore.node.ConnectivityInfo( 5204): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5204):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5204):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5204):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 5204):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5204):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 5204):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 5204):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 5204):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5204): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 5204): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5204): 
,V/AlarmManager(  884): send {7c7b712, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  884): done {7c7b712, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:35000 mC
,V/AlarmManager(  884): send {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): send {ceda3ac, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [3ms]
,V/AlarmManager(  884): done {ceda3ac, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): Unit Test app is loaded
I/jxcore-log( 5204): 
,I/jxcore-log( 5204): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 5204): 
,I/chromium( 5204): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,E/global frequency( 2472): no tags to log
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2472): Explicit concurrent mark sweep GC freed 29979(1722KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.789ms total 113.027ms
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2472): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 53404(2MB) AllocSpace objects, 33(1051KB) LOS objects, 39% free, 7MB/12MB, paused 789us total 49.266ms
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2472): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2472): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2472): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2472): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2472): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2472): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2472): publish the event [tag = DEV_ATTRIBS event name = SW]
,V/AlarmManager(  884): send {34e6325e, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {34e6325e, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/global frequency( 2472): BcsDSCheckin.events found events 2000
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2472): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 4176(174KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 730us total 29.320ms
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2472): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2472): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2472): unknown error code mapping for: 0
I/global frequency( 2472): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2472): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2472): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:34000 mC
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  884): Explicit concurrent mark sweep GC freed 7225(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 6.345ms total 123.785ms
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2472):  Nonce Reponse 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2472): Explicit concurrent mark sweep GC freed 38052(3MB) AllocSpace objects, 5(132KB) LOS objects, 39% free, 11MB/18MB, paused 1.611ms total 71.993ms
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {ddb4403, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {831ed6b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [11ms]
,V/AlarmManager(  884): done {ddb4403, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/VacuumService( 1700): Vacuum at: now=1457489223541 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1700): disconnect managed GoogleApiClient
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311529, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-267, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  884): send {32a8cc55, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  884): done {32a8cc55, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
,I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1700): onCreate
,D/CdsService( 2472): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
I/CdsService( 2472): [i] > Retry handler returned true; Retry web request after backoff time: 300000
D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,I/ConfigService( 1700): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=293, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311166, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-319, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  884): send {ceda3ac, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): send {ddb4403, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {ceda3ac, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  884): done {ddb4403, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311075, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-422, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  884): send {ddb4403, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {f6d8d1, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2472): alarm fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2472): alarm fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2472): alarm fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  884): done {ddb4403, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/OtaApp  ( 2472): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1463): alarm fired!
,V/AlarmManager(  884): done {f6d8d1, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [71ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310967, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-736, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2472):  Nonce Reponse 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2472): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2472): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  884): send {ddb4403, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {12670f80, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  884): send {15582672, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  884): done {12670f80, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,V/AlarmManager(  884): done {15582672, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [37ms]
,V/AlarmManager(  884): done {ddb4403, *alarm*:android.intent.action.TIME_TICK} [61ms]
,I/EventLogService( 1939): Aggregate from 1457487516833 (log), 1457487516833 (data)
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312304, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1314, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2472):  Nonce Reponse 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310530, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=-47, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2472): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2472): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2472): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 3266(129KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 772us total 29.863ms
,D/MMApiWebService( 2472): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2472): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2472): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2472): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2472): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2472): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2472): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  884): User[0] Flushing usage stats to disk
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311694, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-82, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5434): 
D/AndroidRuntime( 5434): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5434): CheckJNI is OFF
D/AndroidRuntime( 5434): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10563 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5204:com.test.thalitest/u0a563 (adj 0): stop com.test.thalitest
W/PackageSettings(  884): Skipping PackageSetting{1c8969c9 com.example.hello/10561} due to missing metadata
I/WindowState(  884): WIN DEATH: Window{330e182d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  884): Client connection lost with reason: 4
I/ActivityManager(  884):   Force finishing activity ActivityRecord{8b8c79b u0 com.test.thalitest/.MainActivity t9}
V/ActivityManager(  884): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10563 user=0: pkg removed
I/ActivityManager(  884):   Force finishing activity ActivityRecord{8b8c79b u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  884): Duplicate finish request for ActivityRecord{8b8c79b u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 2902): Explicit concurrent mark sweep GC freed 4060(843KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 838us total 38.308ms
W/ActivityManager(  884): Spurious death for ProcessRecord{2dc87d2b 5204:com.test.thalitest/u0a563}, curProc for 5204: null
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
W/GeofencerStateMachine( 1700): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1408): createOrResetDecoder
D/OtaApp  ( 2472): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2472): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2472): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
D/VoicemailCleanupService( 4840): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5464 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7311(531KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 503us total 155.436ms
D/OtaApp  ( 2472): [debug] > cancelling the previous pending intent set for download later
I/art     ( 1939): Explicit concurrent mark sweep GC freed 3935(226KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 958us total 173.857ms
I/ConfigService( 1700): onCreate
I/OtaApp  ( 2472): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2472): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  884): Explicit concurrent mark sweep GC freed 19405(1316KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 3.269ms total 198.746ms
I/art     (  884): WaitForGcToComplete blocked for 125.235ms for cause Explicit
W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 5204 uid 10563
I/Keyboard.Facilitator( 1408): onFinishInput()
W/asset   ( 5464): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5464): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5464): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5464): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5492 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  884): Killing 4984:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  884): Explicit concurrent mark sweep GC freed 5838(294KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.578ms total 203.327ms
W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4984/cgroup.procs: No such file or directory
I/Launcher( 1558): Deferring update until onResume
D/AndroidRuntime( 5434): Shutting down VM
W/ContextImpl( 5492): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5517 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@81ce062 new=com.google.android.velvet.VelvetApplication@81ce062
I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5540 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
