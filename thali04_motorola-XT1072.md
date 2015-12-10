#### Test 506502784dae475_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  883): send {3b4028e7, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {3986252d, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  883): done {3986252d, *walarm*:com.google.android.intent.action.SEND_IDLE} [16ms]
V/AlarmManager(  883): done {3b4028e7, *alarm*:android.intent.action.TIME_TICK} [45ms]
--------- beginning of main
D/AndroidRuntime( 5092): 
D/AndroidRuntime( 5092): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5092): CheckJNI is OFF
D/AndroidRuntime( 5092): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5111 uid=10376 gids={50376, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5092): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5111): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/global frequency( 2560): no tags to log
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/LibraryLoader( 5111): Time to load native libraries: 4 ms (timestamps 6043-6047)
,I/LibraryLoader( 5111): Expected native library version number "",actual native library version number ""
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/WebViewChromiumFactoryProvider( 5111): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 5111): Expected native library version number "",actual native library version number ""
I/chromium( 5111): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5111): Initializing chromium process, singleProcess=true
,W/art     ( 5111): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5111): ApplicationContext is null in ApplicationStatus
,W/chromium( 5111): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5111): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/libEGL  ( 5111): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5111): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5111): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5111): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5111): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5111): Local Branch: 
I/Adreno-EGL( 5111): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5111): Local Patches: NONE
I/Adreno-EGL( 5111): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BSUtils ( 2560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb7a274:true
,D/BluetoothAdapter( 5111): 174437516: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{b3fba62 u0 com.test.thalitest/.MainActivity t3}
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 24135(1223KB) AllocSpace objects, 8(282KB) LOS objects, 40% free, 7MB/12MB, paused 928us total 59.254ms
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/art     ( 5111): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  883): Explicit concurrent mark sweep GC freed 11718(671KB) AllocSpace objects, 2(190KB) LOS objects, 33% free, 19MB/29MB, paused 1.330ms total 118.031ms
I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,W/AwContents( 5111): onDetachedFromWindow called when already detached. Ignoring
,D/BSUtils ( 2560): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/SystemWebViewEngine( 5111): CordovaWebView is running on device made by: motorola
,I/BSUtils ( 2560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/art     ( 5111): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5111): Attempt to remove local handle scope entry from IRT, ignoring
I/BSUtils ( 2560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2560): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2560): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2560): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/OpenGLRenderer( 5111): Render dirty regions requested: true
,D/Atlas   ( 5111): Validating map...
,W/chromium( 5111): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5111): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5111): Enabling debug mode 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1067
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +990ms (total +1s67ms)
,W/IInputConnectionWrapper( 5111): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5111): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5111): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5111): Cannot call determinedVisibility() - never saw a connection for the pid: 5111
,I/global frequency( 2560): BcsDSCheckin.events found events 19
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/MotorolaSettings( 2560): no such table to get this name = privacy_droid_blast
,W/System.err( 2560): java.lang.Exception
W/System.err( 2560): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 2560): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 2560): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2560): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 2560): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 2560): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 2560): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsCore.limitRuleExceeded(BcsCore.java:810)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsCore.doCallHomeCore(BcsCore.java:592)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsCore.doCallHome(BcsCore.java:494)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:325)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:383)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 2560): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 2560): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 2560): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 2560): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 2560): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 2560): 	at java.lang.Thread.run(Thread.java:818)
,I/global frequency( 2560): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2560): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2560): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 2560): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 2560): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2560): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 2560): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/JsMessageQueue( 5111): Set native->JS mode to OnlineEventsBridgeMode
,I/BSUtils ( 2560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2560): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2560): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2560): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2560): unknown error code mapping for: 0
I/global frequency( 2560): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/jxcore_app_log( 5111): JniHelper::setJavaVM(0xb71af310), pthread_self() = -1219240328
,D/JX-Cordova( 5111): jxcore cordova android initializing
,W/jxcore-log( 5111): Initializing JXcore engine
W/jxcore-log( 5111): JXcore engine is ready
,W/jxcore-log( 5111): Starting JXcore engine
,W/.test.thalitest( 5111): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10376 path="socket:[6532]" dev="sockfs" ino=6532 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5111): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10376 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 5111): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10376 path="socket:[7652]" dev="sockfs" ino=7652 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5111): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10376 path="socket:[21410]" dev="sockfs" ino=21410 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5111): Platform android
W/jxcore-log( 5111): 
W/jxcore-log( 5111): Process ARCH arm
W/jxcore-log( 5111): 
,I/jxcore-log( 5111): JXcore Cordova bridge is ready!
I/jxcore-log( 5111): 
W/jxcore-log( 5111): JXcore engine is started
,I/chromium( 5111): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5111): Toggling radios to true
I/jxcore-log( 5111): 
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  883): Message: 1
W/Settings( 1459): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService(  883): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=5111, uid=10376
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/WifiStateMachine(  883): setting operational mode to 1
,I/ActivityManager(  883): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5181 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
W/Settings( 1459): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 5111): Radios toggled
I/jxcore-log( 5111): 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1459): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1459): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5181): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5181): Adding HeadsetService
D/AdapterServiceConfig( 5181): Adding A2dpService
D/AdapterServiceConfig( 5181): Adding HidService
D/AdapterServiceConfig( 5181): Adding HealthService
D/AdapterServiceConfig( 5181): Adding PanService
D/AdapterServiceConfig( 5181): Adding GattService
D/AdapterServiceConfig( 5181): Adding BluetoothMapService
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@706171a:true
D/BluetoothAdapterState( 5181): make
I/bluedroid( 5181): init
I/BluetoothAdapterState( 5181): Entering OffState
,I/bte_conf( 5181): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5181): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5181): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 5181): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5181): get_profile_interface socket
I/bluedroid( 5181): get_profile_interface map_client
,I/GKI_LINUX( 5181): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5181): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  883): Bluetooth Adapter name changed to XT1072
D/BluetoothAdapterProperties( 5181): Name is: XT1072
,D/BluetoothManagerService(  883): Stored Bluetooth name: XT1072
D/BluetoothManagerService(  883): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  883): Message: 40
,D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 5181): config_hci_snoop_log
D/BluetoothManagerService(  883): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5181): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5181): Setting state to 11
I/BluetoothAdapterState( 5181): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  883): Message: 60
D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  883): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 5181): make
,I/BluetoothBondStateMachine( 5181): StableState(): Entering Off State
,I/ActivityManager(  883): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5223 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothHeadset( 1507): Proxy object connected
,D/BluetoothHeadset( 1533): Proxy object connected
,D/HeadsetService( 5181): Received start request. Starting profile...
D/BluetoothHeadset(  883): Proxy object connected
I/BluetoothHeadsetServiceJni( 5181): classInitNative: succeeds
,D/HeadsetStateMachine( 5181): make
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Tethering(  883): InitialState.processMessage what=4
,D/BluetoothHeadset( 1507): Proxy object connected
,I/BluetoothAdapterState( 5181): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/TCMD    (  486): NL - Read 1008 bytes from update socket.
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/HeadsetStateMachine( 5181): max_hf_connections = 1
I/bluedroid( 5181): get_profile_interface handsfree
D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  486): NL - Read 1008 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothA2dp(  883): Proxy object connected
,D/A2dpService( 5181): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5181): classInitNative: succeeds
D/HeadsetStateMachine( 5181): Enter Disconnected: -2, size: 0
I/bluedroid( 5181): get_profile_interface avrcp
,D/QsoftapCmd(  296): Got softap fwreload command we are passing on
,D/SoftapController(  296): Softap fwReload - Ok
,D/CommandListener(  296): Setting iface cfg
,D/CommandListener(  296): Trying to bring down wlan0
,D/CommandListener(  296): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  883): setWifiState: enabling
,E/RemoteController( 5181): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5181): classInitNative: succeeds
D/A2dpStateMachine( 5181): make
,E/WifiStateMachine(  883): Supplicant start successful
I/bluedroid( 5181): get_profile_interface a2dp
D/WifiMonitor(  883): startMonitoring(wlan0) with mConnected = false
I/GKI_LINUX( 5181): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
I/BluetoothHidServiceJni( 5181): classInitNative: succeeds
,D/A2dpStateMachine( 5181): Enter Disconnected: -2
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/HidService( 5181): Received start request. Starting profile...
I/bluedroid( 5181): get_profile_interface hidhost
D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
I/BluetoothHealthServiceJni( 5181): classInitNative: succeeds
,D/HealthService( 5181): Received start request. Starting profile...
,I/bluedroid( 5181): get_profile_interface health
D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/BluetoothPanServiceJni( 5181): classInitNative(L105): succeeds
,D/PanService( 5181): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5181): initializeNative(L110): pan
,I/bluedroid( 5181): get_profile_interface pan
,I/wpa_supplicant( 5244): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5244): Long line in configuration file truncated
I/wpa_supplicant( 5244): rfkill: Cannot open RFKILL control device
D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
,D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/BtGatt.JNI( 5181): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5181): handleDebugAction() action=null
I/MDMCTBK (  298): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  298): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): wifi_connect_to_supplicant, current pid is = 298
,D/BtGatt.GattService( 5181): Received start request. Starting profile...
D/BtGatt.GattService( 5181): start()
I/bluedroid( 5181): get_profile_interface gatt
D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
D/BtGatt.AdvertiseManager( 5181): advertise manager created
,D/MDMCTBK (  298): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  298): wifi_close_sockets: Exit
,E/MDMCTBK (  298): Attach monitor thread
,D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothMapService( 5181): Received start request. Starting profile...
D/BluetoothMapService( 5181): start()
,D/BluetoothMapEmailSettingsLoader( 5181): Found 0 applications
D/BluetoothMapEmailAppObserver( 5181): createReceiver()
,D/BluetoothMapEmailAppObserver( 5181): initObservers()
D/BluetoothMapEmailAppObserver( 5181): getEnabledAccountItems()
,D/BluetoothAdapterService( 5181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
D/HeadsetStateMachine( 5181): Proxy object connected
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 5181): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5181): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 5181): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5181): enable
,I/GKI_LINUX( 5181): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5181): init
,I/bt-btu  ( 5181): btu_task pending for preload complete event
,I/bt_vendor( 5181): bt-vendor : init
D/bt_userial_mct( 5181): userial_init
,I/bt_hwcfg( 5181): Starting hciattach daemon
I/bt_hwcfg( 5181): try to set false
I/bt_hwcfg( 5181): Starting hciattach daemon
I/bt_hwcfg( 5181): try to set true
,I/libmdmdetect( 5244): ESOC framework not supported
E/Diag_Lib( 5244):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5244): baseband property is set to [msm]
I/libmdmdetect( 5244): ESOC framework not supported
,W/ResourcesManager( 5223): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/wpa_supplicant( 5244):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5244): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5244): card_info[i].card_state: 0x0
E/wpa_supplicant( 5244): card_info[i].error_code: 0x0
E/wpa_supplicant( 5244): SIM/USIM not ready
E/wpa_supplicant( 5244): Error while reading SIM card status
I/qcom-bluetooth( 5258): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/wpa_supplicant( 5244): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5244): card_info[i].card_state: 0x0
E/wpa_supplicant( 5244): card_info[i].error_code: 0x0
E/wpa_supplicant( 5244): SIM/USIM not ready
I/wpa_supplicant( 5244): eap_proxy: Card not ready
,I/qcom-bluetooth( 5265): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5266): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5268): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5269): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/ActivityManager(  883): Killing 4913:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/qcom-bluetooth( 5270): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 5244): Line 31: unknown global field 't'.
E/wpa_supplicant( 5244): Line 31: Invalid configuration line 't'.
I/wpa_supplicant( 5244): rfkill: Cannot open RFKILL control device
D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
,D/TCMD    (  486): Listening for incoming client connection request
,E/wpa_supplicant( 5244): baseband property is set to [msm]
I/libmdmdetect( 5244): ESOC framework not supported
,E/wpa_supplicant( 5244):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5244): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5244): card_info[i].card_state: 0x0
,E/wpa_supplicant( 5244): card_info[i].error_code: 0x0
E/wpa_supplicant( 5244): SIM/USIM not ready
E/wpa_supplicant( 5244): Error while reading SIM card status
,E/wpa_supplicant( 5244): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5244): card_info[i].card_state: 0x0
E/wpa_supplicant( 5244): card_info[i].error_code: 0x0
E/wpa_supplicant( 5244): SIM/USIM not ready
I/wpa_supplicant( 5244): eap_proxy: Card not ready
I/wpa_supplicant( 5244): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
I/MDMCTBK (  298): createWifiMonitorThread: Started the wifi monitor thread -1223905248
D/MDMCTBK (  298): wifi_wait_on_socket: Enter monitor thread
,E/WifiStateMachine(  883): setSuspendOptimizations: 2 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  883): Supplicant connection established
E/WifiStateMachine(  883): setWifiState: enabled
,D/MDMCTBK (  298): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 5244): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 5244): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-AVOID-FREQ ra
D/MDMCTBK (  298): Event received = CTRL-EVENT-AVOID-FREQ ra
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_4913/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  883): Loading config and enabling all networks 
,D/AuthorizationBluetoothService( 1692): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  883):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  883):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  883): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  883): Setting external_sim to 1
,D/WifiStateMachine(  883): Setting OUI to DA-A1-19
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e4289c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb71af310, mCls = 0x2017ca
I/WifiNative-HAL(  883): Could not start hal
,E/WifiStateMachine(  883): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5244): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5277 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
,E/native  (  883): do suspend true
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  883): SCAN_AVAILABLE : 3
D/RttService(  883): SCAN_AVAILABLE : 3
D/RttService(  883): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  296): Setting iface cfg
D/CommandListener(  296): Trying to bring up p2p0
,D/WifiScanningService(  883): DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  883): startHal
,D/WifiMonitor(  883): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  883): P2pEnablingState
D/WifiP2pService(  883): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2p socket connection successful
,D/WifiP2pService(  883): P2pEnabledState
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa197a9cc
D/wifi    (  883): halHandle = 0x0, mVM = 0xb71af310, mCls = 0x1452
I/WifiNative-HAL(  883): Could not start hal
E/WifiScanningService(  883): could not start HAL
D/WifiP2pService(  883): sending p2p connection changed broadcast
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/WifiNative-HAL(  883): p2pGetDeviceAddress
D/WifiNative-HAL(  883): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  883): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  883): MCC mode enabled 0
D/WifiP2pService(  883): mP2pAutoConnectSupport = 0
D/WifiP2pService(  883): sending p2p persistent groups changed broadcast
D/WifiP2pService(  883): InactiveState
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): set country code US
E/WifiStateMachine(  883): set frequency band 2
D/WifiP2pService(  883): InactiveState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5244): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5244): wlan0: Failed to initiate AP scan
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Reject scan trigger sinc
D/MDMCTBK (  298): Event received = Reject scan trigger sinc
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  298): Event received = Failed to initiate AP sc
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,D/WifiP2pService(  883): InactiveState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/SharedPreferencesImpl(  883): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5277): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  883): Killing 4822:android.process.acore/u0a7 (adj 15): empty #7
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4822/cgroup.procs: No such file or directory
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  486): NL - Read 56 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  298): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e428fc
D/wifi    (  883): halHandle = 0x0, mVM = 0xb71af310, mCls = 0x18d6
I/WifiNative-HAL(  883): Could not start hal
E/WifiStateMachine(  883): [1,420,590,143,907 ms] noteScanEnd no scan source
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,I/qcom-bluetooth( 5303): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,E/WifiStateMachine(  883): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  883):  rewrite network history for "NG700"WPA_PSK
E/WifiStateMachine(  883): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
I/qcom-bluetooth( 5304): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 5181): bluetooth satus is on
D/bt_userial_mct( 5181): userial_open(port:0)
,I/bt_userial_vendor( 5181): Done intiailizing UART
I/bt_userial_vendor( 5181): Done intiailizing UART
I/bt_userial_mct( 5181): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5181): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 5181): btu_task received preload complete event
,I/        ( 5181): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5181): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5181): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5181): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5181): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5181): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5181): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5181): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5181): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5181): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5181): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5181): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5181): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5181): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5181): BTE_InitTraceLevels -- TRC_BTIF
D/bt_userial_mct( 5181): Entering userial_read_thread()
,E/WifiConfigStore(  883): will read network variables netId=0
,E/bt-btm  ( 5181): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6e03d85 
,E/bt-btm  ( 5181): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6e03d85 
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  883): will read network variables netId=0
,E/bt-btif ( 5181): Calling BTA_HhEnable
E/bt-btif ( 5181): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5181): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  883): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  883): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 5181): Name is: XT1072
,D/BluetoothAdapterProperties( 5181): Scan Mode:20
D/BluetoothAdapterProperties( 5181): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5181): Adding bonded device:7C:F9:0E:37:96:AB
,I/wpa_supplicant( 5244): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  298): Event received = Trying to associate with
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/BluetoothAdapterProperties( 5181): Adding bonded device:58:2A:F7:ED:96:BE
E/wpa_supplicant( 5244): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiConfigStore(  883): setLastSelectedConfiguration -1
E/BluetoothRemoteDevices( 5181): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/wpa_supplicant( 5244): PNO: In assoc process
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/BluetoothRemoteDevices( 5181): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/bte_conf( 5181): Device ID record 1 : primary
,D/bte_conf( 5181):   vendorId            = 000f
,D/bte_conf( 5181):   vendorIdSource      = 0001
D/bte_conf( 5181):   product             = 1200
D/bte_conf( 5181):   version             = 1436
D/bte_conf( 5181):   clientExecutableURL = 
D/bte_conf( 5181):   serviceDescription  = 
D/bte_conf( 5181):   documentationURL    = 
D/bte_conf( 5181): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 5181): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5181): ScanMode =  20
,D/BluetoothAdapterProperties( 5181): State =  11
E/bt_mct  ( 5181): hci lib postload completed
D/BluetoothPanServiceJni( 5181): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 5181): Setting state to 12
I/BluetoothAdapterState( 5181): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 5181): Scan Mode:21
D/BluetoothManagerService(  883): Message: 60
D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothAdapterProperties( 5181): Discoverable Timeout:120
D/BluetoothManagerService(  883): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,D/BluetoothA2dp(  883): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 5181): Entering On State
D/BluetoothHeadset( 1507): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1507): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1533): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  883): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  883): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 5181): onReceive
D/BluetoothMapService( 5181): STATE_ON
D/BluetoothManagerService(  883): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  883): Message: 40
D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 5181): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 5181): MAS initSocket()
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/Telecom ( 1507): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothAdapter( 5181): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 5181): Accepting socket connection...
,W/ContextImpl( 5223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/HeadsetStateMachine( 5181): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 5181): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5181): mNumber:  mType: 128
D/HeadsetStateMachine( 5181): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5181): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38b44315:true
,D/LocalBluetoothProfileManager( 5223): Adding local A2DP profile
,D/BluetoothManagerService(  883): Message: 30
,D/LocalBluetoothProfileManager( 5223): Adding local HEADSET profile
,D/BluetoothManagerService(  883): Message: 30
,D/BluetoothManagerService(  883): Message: 30
,D/AuthorizationBluetoothService( 1692): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  883): Message: 30
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5181): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 5223): Adding local MAP profile
D/BluetoothMap( 5223): Create BluetoothMap proxy object
D/BluetoothManagerService(  883): Message: 30
,D/BluetoothManagerService(  883): Message: 30
,D/LocalBluetoothProfileManager( 5223): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5223): finishStartingService: stopping service
,D/BluetoothA2dp( 5223): Proxy object connected
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5181): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5181): Accept thread started.
D/A2dpProfile( 5223): Bluetooth service connected
,D/BluetoothHeadset( 5223): Proxy object connected
,D/HeadsetProfile( 5223): Bluetooth service connected
,D/BluetoothInputDevice( 5223): Proxy object connected
,D/HidProfile( 5223): Bluetooth service connected
,D/BluetoothMap( 5223): Proxy object connected
,D/MapProfile( 5223): Bluetooth service connected
D/BluetoothMap( 5223): getConnectedDevices()
,D/WifiP2pService(  883): InactiveState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledStateupdate channel list
,D/BluetoothPbap( 5223): Proxy object connected
D/PbapServerProfile( 5223): Bluetooth service connected
,D/BluetoothPan( 5223): BluetoothPAN Proxy object connected
D/PanProfile( 5223): Bluetooth service connected
,D/TCMD    (  486): NL - Read 312 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 192 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 68 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 80 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 80 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 68 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5244): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  298): Event received = Associated with c0:ff:d4
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5244): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  298): Event received = WPA: Key negotiation com
I/wpa_supplicant( 5244): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  298): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  298):  STA Connected !!
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
E/MDMCTBK (  298): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  298): get_freq !!, resp=2412
I/MDMCTBK (  298): get_freq !!, Strip data
I/MDMCTBK (  298): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223889184
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  296): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 1
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 5244): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5244): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bb48363 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bb48363 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5338): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5338): version 5.5.6 starting
,E/DHCPCD  ( 5338): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5338): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 5338): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5338): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5338): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 5338): wlan0: sending REQUEST (xid 0x4c01de6b), next in 3.32 seconds
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  298): NetlinkHandler, interfaceAdded
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
E/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  298): , Wifi = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223889184
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
,I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0,
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  298): send SAR ctrl over QMI,
,I/DHCPCD  ( 5338): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5338): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5338): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5338): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5338): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5338): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5338): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  486): NL - Read 60 bytes from update socket.
D/TCMD    (  486): NL - ignore NL message, type = 20
D/TCMD    (  486): Listening for incoming client connection request
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  883): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  883): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  883):    accepting network in place of null
D/ConnectivityService(  883): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-10ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,I/ModemStatsDSDetect( 1524): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1524): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1524): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:38:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1420590146289], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1420590146267]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1524): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1524): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1524): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1524): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  883): Explicit concurrent mark sweep GC freed 42370(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.602ms total 129.644ms
,D/MMApiWebService( 2560): generating token using payload instead of using session token
,I/art     ( 2560): Explicit concurrent mark sweep GC freed 14251(866KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.203ms total 64.936ms
,D/ Nonce  ( 2560):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2560): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/ Nonce  ( 2560):  Nonce Reponse 
D/MMApiWSBase( 2560): doRequest(): /v1/gdi/nonce.json resp length: 0
E/MMApiWSBase( 2560): doRequest(): got exception: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/ErrorTranslator( 2560): unknown exception mapping for: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: UnknownError msg: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate req: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 4094(179KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 779us total 28.669ms
,I/MMApiWSBase( 2560): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2560): invalid counter update blocked: 'in_bytes' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2560): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 2560): doRequest(): v1/gns/list/messages resp length: 0
E/MMApiWSBase( 2560): doRequest(): got exception: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/ErrorTranslator( 2560): unknown exception mapping for: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: UnknownError msg: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate req: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,W/DataUsage( 2560): invalid counter update blocked: 'in_bytes' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2560): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2560): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1459): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2560): now: 207614 ,futureTime: 9223372036854775807
D/PollingManager( 2560): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2560): now: 207619 ,futureTime: 9223372036854775807
D/PollingManager( 2560): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2560): now: 207629 ,futureTime: 9223372036854775807
,D/AlarmManagerService(  883): Setting time of day to sec=1449751102
W/AlarmManagerService(  883): Unable to set rtc to 1449751102: Invalid argument
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5410 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1459): now: 207673 ,futureTime: 86475888
D/Central_PollingManager( 1459): Polling alarm set to expire at: 86475888 Current Time: 207673
,V/AlarmManager(  883): send {ee4bd8c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): send {2f6d8cd5, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.HourlyAlarmTrigger}
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30800004 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,D/OtaApp  ( 2560): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  883): send {374cfbdb, *walarm*:com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION}
,D/OtaApp  ( 2560): [debug] > PollingManagerService, now: 207742 ,futureTime: 9223372036854775807
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  883): send {28872151, *walarm*:com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE}
,V/AlarmManager(  883): send {1250c14f, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,D/Finsky  ( 4981): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  883): send {34957ab7, *walarm*:com.google.android.gms.auth.authzen.CHECK_REGISTRATION}
,V/AlarmManager(  883): send {f933224, *walarm*:com.android.providers.calendar.SCHEDULE_ALARM}
,V/AlarmManager(  883): send {26cb818d, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MidnightAlarmTrigger}
V/AlarmManager(  883): send {62d4f42, *walarm*:com.google.android.gms.reminders.REFRESH_NOTIFICATION}
,V/AlarmManager(  883): send {3e7d0b53, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger}
,V/AlarmManager(  883): send {9e34c90, *alarm*:com.google.android.gms.playlog.service.UPLOAD_DEFAULT}
,D/MMApiProvisionService( 2560): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2560): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2560): createDeviceIdOrLogin update_device
D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2560): Not proxy app, so login/provision not allowed
D/MMApiWebService( 2560): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for service com.google.android.partnersetup/.RlzPingService: pid=5436 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
V/AlarmManager(  883): send {31451d8e, *walarm*:com.google.android.partnersetup/.RlzPingService}
,D/MMApiProvisionService( 2560): isDeviceProvisioned: deviceId = 2072049230914535424
,V/AlarmManager(  883): send {2bc091cb, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.WeeklyAlarmTrigger}
,I/Icing   ( 1939): Performing maintenance.
,D/CCE     ( 2560): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2560): createDeviceIdOrLogin update_device
D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service: pid=5454 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,V/AlarmManager(  883): send {1b6c1da8, *walarm*:com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service}
V/AlarmManager(  883): send {360200c1, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MonthlyAlarmTrigger}
,V/AlarmManager(  883): send {39461db9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  883): send {315b5066, *alarm*:com.google.android.calendar.APPWIDGET_SCHEDULED_UPDATE}
,V/AlarmManager(  883): send {312f6f43, *alarm*:android.intent.action.DATE_CHANGED}
,D/MMApiProvisionService( 2560): isDeviceProvisioned: deviceId = 2072049230914535424
,V/AlarmManager(  883): send {1430df82, *alarm*:com.motorola.context/.analytics.DailyCheckinService}
,V/AlarmManager(  883): send {37a506f9, *alarm*:com.motorola.migrate.NOTIFY_TO_RUN}
V/AlarmManager(  883): send {16fa063e, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED}
V/AlarmManager(  883): send {84fbc9f, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED}
V/AlarmManager(  883): send {1765f1ec, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED}
,V/AlarmManager(  883): done {374cfbdb, *walarm*:com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION} [255ms]
,V/AlarmManager(  883): done {28872151, *walarm*:com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE} [256ms]
V/AlarmManager(  883): done {1250c14f, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [256ms]
V/AlarmManager(  883): done {31451d8e, *walarm*:com.google.android.partnersetup/.RlzPingService} [256ms]
V/AlarmManager(  883): done {1b6c1da8, *walarm*:com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service} [256ms]
,V/AlarmManager(  883): done {1430df82, *alarm*:com.motorola.context/.analytics.DailyCheckinService} [261ms]
,D/MMApiProvisionService( 2560): isRequestAllowed(): already have outstanding request ... ignoring request
D/MMApiWebService( 2560): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiProvisionService( 2560): isDeviceProvisioned: deviceId = 2072049230914535424
,I/RlzPingService( 5436): Setting next ping for 1450355903117
,D/Checkin ( 5277): publish the event [tag = CONTEXT_ENGINE event name = INTERNAL]
,D/CCE     ( 2560): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2560): createDeviceIdOrLogin update_device
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2560): Not proxy app, so login/provision not allowed
,D/Checkin ( 5277): publish the event [tag = CONTEXT_ENGINE event name = BT_USAGE_STATS]
,D/MMApiWebService( 2560): generating token using payload instead of using session token
,D/OtaApp  ( 2560): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2560): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2560): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2560): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2560): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,E/GpsLocationProvider(  883): No APN found to select.
D/OtaApp  ( 2560): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2560): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
D/OtaApp  ( 2560): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524295
,D/OtaApp  ( 2560): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2560): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/ Nonce  ( 2560):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/OtaApp  ( 2560): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2560): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2560): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2560): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/Keyboard.Facilitator( 1407): onFinishInput()
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,583
,I/art     (  883): Explicit concurrent mark sweep GC freed 15248(759KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.750ms total 145.906ms
,I/UsageStatsDatabase(  883): Moving file /data/system/usagestats/0/daily/1420588800000 to /data/system/usagestats/0/daily/1449749753528
,I/UsageStatsDatabase(  883): Moving file /data/system/usagestats/0/weekly/1420070400000 to /data/system/usagestats/0/weekly/1449231353528
,I/UsageStatsDatabase(  883): Moving file /data/system/usagestats/0/monthly/1420416000000 to /data/system/usagestats/0/monthly/1449576953528
I/UsageStatsDatabase(  883): Moving file /data/system/usagestats/0/yearly/1419120000000 to /data/system/usagestats/0/yearly/1448280953528
,I/MusicStore( 5410): Database version: 120
,I/MMApiWSBase( 2560): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/VacuumService( 1692): Vacuum at: now=1449751103527 tag=VacuumService
,I/UsageStatsService(  883): User[0] Rollover scheduled @ 2015-12-11 01:00:00(1449792000000)
,E/ActivityThread( 1939): Failed to find provider info for com.android.contacts.metadata
,D/GpsLocationProvider(  883): NTP server returned: 1449751099826 (Thu Dec 10 13:38:19 GMT+01:00 2015) reference: 204667 certainty: 9 system time offset: -3781
,E/LocSvc_ApiV02(  883): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/SyncManager(  883): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 240364, reason: UserStart
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5410): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/SearchBackgroundTaskFac( 5454): refreshing internal icing corpora
,I/SearchBackgroundTaskFac( 5454): Checking for language pack updates
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5410): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5410): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Auth.Api.Credentials( 1939): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 5410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GservicesUpdateTask( 5454): Updating Gservices keys
,V/JNIHelp ( 5410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 5454): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/ Nonce  ( 2560):  Nonce Reponse 
D/        ( 2560): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"233e7e03-6b73-4667-a2b9-4e1420207f61"}
D/MMApiWSBase( 2560): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2560):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2560): mOutstandingReq set to false
,W/ActivityThread( 5410): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5410): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5410): GMSCore installation verified
,I/ConfigStore( 5410): Config Database version: 1
,D/MMApiWSBase( 2560): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2560): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2560): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 4325(187KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.775ms total 91.160ms
,W/art     ( 5454): Verification of void com.google.android.apps.gsa.extradex.backgroundtasks.a.xo() took 122.307ms
,D/WifiService(  883): New client listening to asynchronous messages
,D/Checkin ( 2560): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
D/SundryService( 2560): handleGetNotificationsResponse(): got 0; more=false
,D/MMApiProvisionService( 2560):  pTime 1449671329422 sExp 172742 cTime 1449751104413 tTime 1449844071422
D/MMApiProvisionService( 2560):  No login Required 
,I/MediaRouter( 5410): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5410): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=true
,I/WebViewFactory( 5454): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/UpdateIcingCorporaServi( 5454): UpdateCorporaTask done [took 235 ms] updated apps [took 235 ms] 
,I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5559 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 5454): Time to load native libraries: 5 ms (timestamps 9521-9526)
I/LibraryLoader( 5454): Expected native library version number "",actual native library version number ""
,W/art     ( 5454): Attempt to remove local handle scope entry from IRT, ignoring
,V/Mms     ( 5559): mnc/mcc: 
,V/Mms     ( 5559): tag: int value: recipientLimit - 20
,V/Mms     ( 5559): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 5559): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5559): tag: int value: maxSubjectLength - 80
,V/Mms     ( 5559): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5559): tag: bool value: enableGroupMms - false
V/Mms     ( 5559):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/art     ( 5454): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5590 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.978ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 363us total 20.689ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 326us total 20.636ms
,W/ResourcesManager( 5559): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneMonitor( 5590): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5590): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5590): onReceive CONNECTIVITY_CHANGE networkType=1
,W/DataUsage( 2560): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 1533): Explicit concurrent mark sweep GC freed 30254(1931KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 895us total 80.951ms
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1449748728355 min interval config: 0 actual interval: 2376780
,I/CheckinService( 1939): Disabling old GoogleServicesFramework version
,I/CheckinService( 1939): Checking schedule, now: 1449751105195 next: 1449748758315
I/CheckinService( 1939): active receiver: enabled
,I/iu.SyncManager( 1939): SYNC; picasa accounts
,I/CheckinService( 1939): Preparing to send checkin request
,I/EventLogService( 1939): Accumulating logs since 1449750585585
,W/DataUsage( 2560): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/GHttpClientFactory( 5410): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  883): Explicit concurrent mark sweep GC freed 23360(1086KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 20MB/30MB, paused 1.802ms total 154.248ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 5410): Using platform SSLCertificateSocketFactory
,D/NetworkLogImpl( 1939): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  883): Killing 5223:com.android.settings/1000 (adj 15): empty #7
I/iu.UploadsManager( 1939): num queued entries: 0
,I/iu.UploadsManager( 1939): num updated entries: 0
,I/iu.SyncManager( 1939): NEXT; no task
,I/ActivityManager(  883): Killing 4956:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_5223/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_4956/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5633 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 4981): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 4981): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 4981): untagSocket(37) failed with errno -22
,D/Finsky  ( 4981): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/GCM     ( 1692): GCM config loaded
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5655 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5661 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,W/ResourcesManager( 5655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 5661): VM with version 2.1.0 has multidex support
I/MultiDex( 5661): install
I/MultiDex( 5661): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5661): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5661): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5661): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5661): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5705 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/ChimeraCfgMgr( 5661): Reading stored module config
,D/ChimeraCfgMgr( 5661): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  298): NetlinkHandler, interfaceAdded
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
E/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  298): , Wifi = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223889184
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
E/MDMCTBK (  298): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ContactLocale( 5705): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/CAR.SERVICE( 5661): Connecting to CarCallService...
,I/art     ( 5661): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5661): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5661): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5661): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  883): Killing 5436:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/CAR.TEL.Service( 5661): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5661): Creating a new PhoneAdapter instance
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_5436/cgroup.procs: No such file or directory
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5661): setListener: com.google.android.gms.car.dn@2305b52
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5661): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5661): Starting CarCallService with initial phone null
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5742 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,I/ActivityManager(  883): Killing 5277:com.motorola.context/u0a8 (adj 15): empty #7
,W/ResourcesManager( 5742): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 5661): Package validated; name: com.android.vending
,E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_5277/cgroup.procs: No such file or directory
,V/Finsky  ( 4981): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     ( 5001): Explicit concurrent mark sweep GC freed 1802(79KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.049ms total 69.815ms
,I/HotwordDataManager( 5454): setSpeakerModel(thalitester@gmail.com,null)
,I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,I/qtaguid ( 4981): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 4981): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 4981): untagSocket(37) failed with errno -22
,I/PhenotypeConfigurator( 1692): Scheduling Phenotype for one-off execution 11955 seconds from now (1449751107369)
,D/GetConfigurationSnapshotOperation( 1692): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 5742): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5742): MmsConfig.loadMmsSettings
I/Babel_SMS( 5742): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5742): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5742): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5742): MmsConfig.loadFromResources
,E/Babel_SMS( 5742): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5742): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5742): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5742): startup - clean
,I/Babel   ( 5742): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5787 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Icing   ( 1939): Failed to connect to SearchIndex Apis
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5742): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5742): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5742): Unsupported profile 4 for video/mp4v-es
I/Icing   ( 1939): Performing maintenance usage 1832213 budget 1146757770 free 99.840% index free 99.965% purge? false target 802730439
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5742): onServiceConnected
W/Babel   ( 5742): Attempted to change video mute state without an active call.
,I/Babel   ( 5742): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 5410:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/PhenotypeFlagCommitter( 1692): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1692): Using platform SSLCertificateSocketFactory
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_5410/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 5454): Binding Chromium to main looper Looper (main, tid 1) {246f902a}
,I/LibraryLoader( 5454): Expected native library version number "",actual native library version number ""
I/chromium( 5454): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5787): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/BrowserStartupController( 5454): Initializing chromium process, singleProcess=true
W/art     ( 5454): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5454): ApplicationContext is null in ApplicationStatus
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5787): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/chromium( 5454): [ERROR:address_tracker_linux.cc(155)] Could not bind NETLINK socket: Address already in use
,I/GAv4    ( 5787): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5787):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5787):   adb logcat -s GAv4
,W/chromium( 5454): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5787): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5787): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
E/libEGL  ( 5454): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5454): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5454): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5454): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5454): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5454): Local Branch: 
I/Adreno-EGL( 5454): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5454): Local Patches: NONE
I/Adreno-EGL( 5454): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 5787): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5787): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5787): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/art     ( 5655): Attempt to remove local handle scope entry from IRT, ignoring
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a2da089:true
,W/art     ( 5454): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5454): onDetachedFromWindow called when already detached. Ignoring
,I/RefreshDomainCookieTask( 5454): refreshing cookies
I/art     (  883): Explicit concurrent mark sweep GC freed 28815(1250KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.797ms total 135.026ms
,W/chromium( 5454): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/Adreno-ES20( 5454): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5454): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/WebViewFactory( 5787): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 48813(3MB) AllocSpace objects, 40(640KB) LOS objects, 24% free, 14MB/19MB, paused 1.262ms total 175.186ms
,I/LibraryLoader( 5787): Time to load native libraries: 1 ms (timestamps 3940-3941)
I/LibraryLoader( 5787): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5787): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 5787): Expected native library version number "",actual native library version number ""
I/chromium( 5787): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5787): Initializing chromium process, singleProcess=true
,W/art     ( 5787): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5787): ApplicationContext is null in ApplicationStatus
,W/chromium( 5787): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5787): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5787): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5787): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5787): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5787): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5787): Local Branch: 
I/Adreno-EGL( 5787): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5787): Local Patches: NONE
I/Adreno-EGL( 5787): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 5787): Requires BLUETOOTH permission
,I/NSApplication( 5787): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5885 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1939): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 5111): Test app app.js loaded
I/jxcore-log( 5111): 
,W/IInputConnectionWrapper( 5111): showStatusIcon on inactive InputConnection
,I/chromium( 5111): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 55860(3MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 13MB/22MB, paused 1.201ms total 111.568ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bbe249a)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1838b1cb)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2451bda8)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@368720c1)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39c9f066)
,I/qtaguid ( 4981): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 4981): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 4981): untagSocket(37) failed with errno -22
,I/ActivityManager(  883): Killing 5559:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_5559/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2560): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2560): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2560): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5911 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Finsky  ( 4981): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.maps to false
D/Finsky  ( 4981): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to false
,W/BindingManager( 5454): Cannot call determinedVisibility() - never saw a connection for the pid: 5454
,W/ResourcesManager( 5911): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5932 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5590:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/ResourcesManager( 4981): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4981): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_5590/cgroup.procs: No such file or directory
,E/SQLiteLog( 5932): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/ResourcesManager( 4981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 4981): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4981): [1] DailyHygiene.access$600: Logging device features
,I/ActivityManager(  883): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5955 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  883): send {21b4b605, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,W/ResourcesManager( 5955): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5955): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,D/DeviceConnectionService( 1692): client connected with version: 8296000
I/ActivityManager(  883): Killing 5633:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  883): Killing 4981:com.android.vending/u0a32 (adj 15): empty #8
,I/Icing   ( 1939): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,I/Icing   ( 1939): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5454): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,W/ScreenOrientationListener( 5454): Removing an inexistent observer!
,I/ApplicationLogger( 5454): logBytes() : Old Hash = -1752052835 : New Hash = -1098915151
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_5633/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_4981/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5983 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.153ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.563ms
,D/CAR.SERVICE( 5661): mConnectedToCar = false, abort
,I/ActivityManager(  883): Killing 5705:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 338us total 21.412ms
,E/ActivityThread( 5661): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 5661): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 5661): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5661): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5661): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5661): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5661): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5661): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5661): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5661): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5661): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5661): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5661): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5661): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5661): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5661): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5661): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5661): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5661): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5661): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5661): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5661): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5661): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5661): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,I/ApplicationLogger( 5454): logEvent(): Logged 1972 bytes in 7155 ms
,I/AnalyticsLogBase( 5932): PlayLogger.onLoggerConnected
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_5705/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 5454:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/ActivityThread( 5661): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 5661): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 5661): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5661): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5661): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5661): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5661): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5661): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5661): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5661): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5661): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5661): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5661): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5661): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5661): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5661): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5661): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5661): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5661): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5661): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5661): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5661): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5661): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,I/System.out( 5983): TimeService: Loaded Library 
,D/TimeService( 5983): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751111218
D/        ( 5983): TimeServiceNative: User Time to be set is 1449751111219
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->ts_val = 1449751111219
D/QC-time-services( 5983): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  331): Daemon: Connection accepted:time_genoff
D/QC-time-services(  331): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751111219
D/QC-time-services(  331): Daemon:genoff_opr: Base = 2, val = 1449751111219, operation = 0
D/QC-time-services(  331): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 12:37:16
,D/QC-time-services(  331): Daemon:Value read from RTC seconds = 1449751036000
D/QC-time-services(  331): Daemon:new time 1449751111219 
D/QC-time-services(  331): Daemon: delta 75219 genoff 75219 
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 75219 to memory
D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/WifiService(  883): Client connection lost with reason: 4
,D/QC-time-services(  331): Updating the TOD offset
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 75219 to memory
D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  331): Daemon:Update to modem bit set
D/QC-time-services(  331): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5983): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  331): Daemon: Base = 2, Value being sent to MODEM = 18446743757744826835
,E/QC-time-services(  331): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  331): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/libprocessgroup(  883): failed to kill 1 processes for processgroup 5454
I/ActivityManager(  883): Killing 5661:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/ActivityManager(  883): Unbind failed: could not find connection for android.os.BinderProxy@35429cd6
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_5661/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6005 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5742:com.google.android.talk/u0a70 (adj 15): empty #7
,W/AbstractGoogleClient( 5932): Application name is not set. Call Builder#setApplicationName.
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_5742/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1449748728355 min interval config: 0 actual interval: 2383292
,I/CalendarProvider2( 5955): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AnalyticsLogBase( 5932): PlayLogger.onLoggerConnected
W/ContentResolver( 5955): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/ResourcesManager( 6005): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6005): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PeopleSync( 1939): onPerformSync() [5005f081]
,I/EventLogService( 1939): Aggregate from 1449751106047 (log), 1449750585585 (data)
,I/MultiDex( 6005): VM with version 2.1.0 has multidex support
I/MultiDex( 6005): install
I/MultiDex( 6005): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=6031 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6005): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6005): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6005): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6005): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6005): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6005): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAv4    ( 6031): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6031):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6031):   adb logcat -s GAv4
,W/GAv4    ( 6031): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6031): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6031): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 6005): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  883): Killing 5787:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f62000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f62000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xbec314e0
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb777e398, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb776d908, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb784ccc0, idLength=0xb1003730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=3296808978
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb776d908
D/DrmWidevineDash(  300): message_length=1591, signature=0xb771d9b0, signature_length=2969581332
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_5787/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {ee4bd8c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [9456ms]
,V/AlarmManager(  883): done {2f6d8cd5, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.HourlyAlarmTrigger} [9458ms]
,V/AuthZen ( 1939): Received broadcast action: com.google.android.gms.auth.authzen.CHECK_REGISTRATION
,V/AlarmManager(  883): done {34957ab7, *walarm*:com.google.android.gms.auth.authzen.CHECK_REGISTRATION} [9466ms]
,V/AuthZen ( 1939): Handling intent: com.google.android.gms.auth.authzen.CHECK_REGISTRATION
D/AuthZenEventHandler( 1939): Handling event: com.google.android.gms.auth.authzen.CHECK_REGISTRATION
,I/AuthZen ( 1939): Fetching signing key...
,V/AlarmManager(  883): done {f933224, *walarm*:com.android.providers.calendar.SCHEDULE_ALARM} [9486ms]
,V/AlarmManager(  883): done {26cb818d, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MidnightAlarmTrigger} [9488ms]
,V/AlarmManager(  883): done {62d4f42, *walarm*:com.google.android.gms.reminders.REFRESH_NOTIFICATION} [9496ms]
,V/AlarmManager(  883): done {3e7d0b53, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger} [9509ms]
,V/AlarmManager(  883): done {9e34c90, *alarm*:com.google.android.gms.playlog.service.UPLOAD_DEFAULT} [9516ms]
,I/AuthZen ( 1939): Signing key fetched successfully!
,V/AlarmManager(  883): done {2bc091cb, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.WeeklyAlarmTrigger} [9532ms]
V/AlarmManager(  883): done {360200c1, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MonthlyAlarmTrigger} [9533ms]
,V/AlarmManager(  883): done {39461db9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [9537ms]
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,V/AlarmManager(  883): done {315b5066, *alarm*:com.google.android.calendar.APPWIDGET_SCHEDULED_UPDATE} [9559ms]
D/AlarmManagerService(  883): Kernel timezone updated to -60 minutes west of GMT
,D/TimeService( 5983): Receivedandroid.intent.action.DATE_CHANGED intent. Current Time is 1449751112398
D/        ( 5983): TimeServiceNative: User Time to be set is 1449751112398
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5983): Lib:time_genoff_operation: pargs->ts_val = 1449751112398
D/QC-time-services(  331): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 5983): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  331): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751112398
D/QC-time-services(  331): Daemon:genoff_opr: Base = 2, val = 1449751112398, operation = 0
D/QC-time-services(  331): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 12:37:17
D/QC-time-services(  331): Daemon:Value read from RTC seconds = 1449751037000
D/QC-time-services(  331): Daemon:new time 1449751112398 
D/QC-time-services(  331): Daemon: delta 75398 genoff 75398 
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 75398 to memory
D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  331): Updating the TOD offset
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 75398 to memory
D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  331): Daemon:Update to modem bit set
D/QC-time-services(  331): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  331): Daemon: Base = 2, Value being sent to MODEM = 18446743757744827014
,I/PeopleSync( 1939): Setting subscription: result=true [5005f081]
E/QC-time-services( 5983): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  331): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  331): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,V/AlarmManager(  883): done {312f6f43, *alarm*:android.intent.action.DATE_CHANGED} [9654ms]
,I/PeopleSync( 1939): Starting sync, feed=null [5005f081]
,I/art     (  883): Explicit concurrent mark sweep GC freed 24587(1141KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.171ms total 167.601ms
,I/ActivityManager(  883): Start proc com.motorola.migrate for broadcast com.motorola.migrate/.helper.NotifReceiver: pid=6066 uid=10043 gids={50043, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/art     ( 5001): Explicit concurrent mark sweep GC freed 2789(112KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 464us total 33.521ms
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,D/FS      ( 6066): FS_Wtr_MigrateApp	Starting...
,D/FS      ( 6066): FS_Anl_RdrSessionAnl	Clearing
,I/PeopleSync( 1939): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/FS      ( 6066): FS_Lib_Util	Moto device
,D/FS      ( 6066): RunNotif	needToNotify: false
,V/AlarmManager(  883): done {37a506f9, *alarm*:com.motorola.migrate.NOTIFY_TO_RUN} [9884ms]
,I/ActivityManager(  883): Start proc com.motorola.contextual.smartrules2 for broadcast com.motorola.contextual.smartrules2/com.motorola.assist.ui.notifications.suggestion.SuggestionsReceiver: pid=6090 uid=10028 gids={50028, 9997, 3003, 1028, 1015, 3001, 3002, 1005, 2002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5885:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_5885/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {16fa063e, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED} [10144ms]
,V/AlarmManager(  883): done {84fbc9f, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED} [10158ms]
,V/AlarmManager(  883): done {1765f1ec, *alarm*:com.motorola.assist.intent.action.SUGGESTION_ALARM_FIRED} [10161ms]
,I/dex2oat ( 6112): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/OtaApp  ( 2560): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2560): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2560): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2560): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2560): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2560): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2560): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2560): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,I/SuggestionManager( 6090): show suggestion notification: key = sleep
,I/SuggestionManager( 6090): show suggestion notification: key = driving
,I/SuggestionManager( 6090): show suggestion notification: key = meeting
,I/ActivityManager(  883): Killing 5655:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/dex2oat ( 6112): dex2oat took 246.008ms (threads: 4)
,I/Adreno-EGL( 6005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6005): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6005): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6005): Local Branch: 
I/Adreno-EGL( 6005): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6005): Local Patches: NONE
I/Adreno-EGL( 6005): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6005): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6005): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6005): Local Branch: 
I/Adreno-EGL( 6005): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6005): Local Patches: NONE
I/Adreno-EGL( 6005): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_5655/cgroup.procs: No such file or directory
I/SundryService( 2560): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2560): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2560): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2560): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6130 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/GetNotificationsWS( 2560): unbindWebServices(): un-registering our AIDL callback...
,W/ResourcesManager( 6130): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarSyncAdapter( 5932): Found no pending settings
,I/ActivityManager(  883): Killing 5955:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/Adreno-EGL( 6005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6005): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6005): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6005): Local Branch: 
I/Adreno-EGL( 6005): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6005): Local Patches: NONE
I/Adreno-EGL( 6005): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_5955/cgroup.procs: No such file or directory
I/ActivityManager(  883): Killing 5911:com.motorola.context/u0a8 (adj 15): empty #7
,I/Adreno-EGL( 6005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6005): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6005): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6005): Local Branch: 
I/Adreno-EGL( 6005): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6005): Local Patches: NONE
I/Adreno-EGL( 6005): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_5911/cgroup.procs: No such file or directory
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,I/Babel_SMS( 6130): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6130): MmsConfig.loadMmsSettings
I/Babel_SMS( 6130): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6130): MmsConfig.loadFromDatabase
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f62000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f62000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb5430960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb771da18, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
E/Babel_SMS( 6130): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6130): MmsConfig.loadFromResources
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb776d908, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
E/Babel_SMS( 6130): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6130): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb784cd00, idLength=0xb1003730
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=2378849569
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb776d908
D/DrmWidevineDash(  300): message_length=1626, signature=0xb7700590, signature_length=2969581332
,W/Settings( 6130): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6130): startup - clean
,I/Babel   ( 6130): deleted: false for 0
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,W/BaseAppContext( 1692): Using Auth Proxy for data requests.
,W/art     ( 6130): Suspending all threads took: 30.881ms
E/BaseAppContext( 1692): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/SQLiteConnectionPool( 1939): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/WearableService( 1692): callingUid 10016, callindPid: 1692
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,D/AuthorizationBluetoothService( 1692): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1939): Restart initialization of location
,E/MDM     ( 1692): [255] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6130): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6130): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6130): Unsupported mime video/mpeg2
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6182 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1692): No location to return for getLastLocation()
W/FusedLocationProvider( 1692): location=null
,I/VideoCapabilities( 6130): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6130): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6130): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6130): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6130): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 5983:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,I/CheckinTask( 1939): Sending checkin request (9590 bytes)
,W/libprocessgroup(  883): failed to open /acct/uid_10096/pid_5983/cgroup.procs: No such file or directory
,I/vclib   ( 6130): onServiceConnected
,W/Babel   ( 6130): Attempted to change video mute state without an active call.
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.UdcSettingBroadcastReceiver: pid=6203 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6031:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10055/pid_6031/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  883): Explicit concurrent mark sweep GC freed 19206(974KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.482ms total 127.360ms
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6236 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=6258 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6066:com.motorola.migrate/u0a43 (adj 15): empty #7
,I/CheckinTask( 1939): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/libprocessgroup(  883): failed to open /acct/uid_10043/pid_6066/cgroup.procs: No such file or directory
,W/ResourcesManager( 1533): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/CheckinService( 1939): Checking schedule, now: 1449751115343 next: 1450352252300
I/CheckinService( 1939): active receiver: disabled
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,W/ContextImpl( 5932): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/PeopleSync( 1939): Sync finished, successful=true, took 2592ms
,D/CheckinService( 1939): Recording last checkin time for package unspecified as 1449751115409
,I/GAV2    ( 5932): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  883): Killing 6090:com.motorola.contextual.smartrules2/u0a28 (adj 15): empty #7
,I/GCoreUlr( 1692): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,W/libprocessgroup(  883): failed to open /acct/uid_10028/pid_6090/cgroup.procs: No such file or directory
,I/GCoreUlr( 1692): DispatchingService.onCreate()
,I/PeopleContactsSync( 1939): CP2 sync start [5005f081]
,D/Finsky  ( 6258): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/PeopleContactsSync( 1939): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/Launcher( 1559): Deferring update until onResume
,D/Finsky  ( 6258): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/PeopleContactsSync( 1939): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,W/Settings( 6258): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6258): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6305 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23919314
,I/GCoreNlp( 1692): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GCoreUlr( 1692): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1692): Unbound from all location providers
I/GCoreUlr( 1692): Place inference reporting - stopped
,I/art     ( 5001): Explicit concurrent mark sweep GC freed 3294(127KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.388ms total 47.231ms
,V/AlarmManager(  883): done {21b4b605, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [5611ms]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6258): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6258): [1] Libraries$2.run: Finished loading 1 libraries.
,I/GCoreUlr( 1692): DispatchingService.onDestroy()
,I/GCoreUlr( 1692): Stopping handler for UlrDispSvcFast
,D/Ads     ( 6258): Skipping gmscore version check
,I/GCoreUlr( 1692): Unbound from all location providers
I/GCoreUlr( 1692): Place inference reporting - stopped
,D/Finsky  ( 6258): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6258): [729] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6258): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 6258): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
D/Finsky  ( 6258): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ContactLocale( 6305): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6342 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.docs.editors.sheets for verification
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.messaging for verification
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.genie.geniewidget for verification
I/art     (  318): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 329us total 27.441ms
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.fitness for verification
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.GoogleCamera for verification
,I/art     (  318): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.407ms
,D/Finsky  ( 6258): [732] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.earth for verification
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 19.998ms
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6360 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6130:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6130/cgroup.procs: No such file or directory
,W/ResourcesManager( 6342): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6360): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6378 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6182:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CalendarProvider2( 6342): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6182/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 1939): CP2 cleanup done, kept= duration=722 ms
,E/MDM     ( 1692): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1939): Restart initialization of location
,D/AuthorizationBluetoothService( 1692): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/PeopleContactsSync( 1939): ===CP2 sync finished, success=true, time=934,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,W/GCoreFlp( 1692): No location to return for getLastLocation()
W/FusedLocationProvider( 1692): location=null
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6412 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Gmail   ( 6378): getAccountsCursor
,I/PeopleSync( 1939): ***Sync finished***, duration: 5118 [5005f081]
,I/art     (  883): Explicit concurrent mark sweep GC freed 21199(1048KB) AllocSpace objects, 3(143KB) LOS objects, 33% free, 20MB/30MB, paused 1.839ms total 134.534ms
,D/ActivityThread( 6378): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6412): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6436 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6442 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6476 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,W/ActivityManager(  883): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 6436): EasService.onCreate
,I/Exchange( 6436): RestartPingTask
,W/GAV2    ( 6378): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteLog( 6378): (283) recovered 111 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/AlarmManager(  883): send {466d6c5, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/Gmail   ( 6378): Observing account changes for notifications
,I/Gmail   ( 6378): getAccountsCursor
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   ( 6378): Sync started for account: account:61035162
,I/Exchange( 6436): RestartPingsTask did not start any pings.
I/Exchange( 6436): PSS stopIfIdle
I/Exchange( 6436): PSS has no active accounts; stopping service.
,I/Exchange( 6436): onDestroy
I/ActivityManager(  883): Killing 6236:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311013, SEQNUM=4410, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-316, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/Gmail   ( 6378): notifyAccountChanged
,I/Gmail   ( 6378): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6378): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_6236/cgroup.procs: No such file or directory
,I/Gmail   ( 6378): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6378): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,I/CalendarProvider2( 6342): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6342): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Babel_SMS( 6412): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6412): MmsConfig.loadMmsSettings
,E/ActivityThread( 1459): Failed to find provider info for com.android.email.provider
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.SmsCallsAction.onReceiveImpl:64 com.motorola.motocare.internal.SmsCallsAction.access$000:21 
,I/Babel_SMS( 6412): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6412): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6412): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6412): MmsConfig.loadFromResources
,E/Babel_SMS( 6412): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6412): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Gmail   ( 6378): notifyAccountChanged
,W/Settings( 6412): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6412): startup - clean
,I/Babel   ( 6412): deleted: false for 0
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6378): getAccountsCursor
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6378): getAccountsCursor
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6530 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6258:com.android.vending/u0a32 (adj 15): empty #7
,W/VideoCapabilities( 6412): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6412): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6412): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6412): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6412): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6412): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6412): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6412): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6258/cgroup.procs: No such file or directory
,W/asset   ( 6530): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6530): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6530): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6530): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Gmail   ( 6378): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12125, normalSync: true
,I/vclib   ( 6412): onServiceConnected
I/GoogleHttpClient( 5001): GMS http client unavailable, use old client
,W/Babel   ( 6412): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6412): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1939): Null package name or gms related package.  Ignoreing.
,E/MC_BatteryHealthAction( 2966): Invalid cycle_count 0
,E/MC_MmcStatsAction( 2966): Unable to find mmc block stat files.
W/System.err( 2966): java.io.FileNotFoundException: /sys/block/mmcblk1/stat: open failed: ENOENT (No such file or directory)
,W/System.err( 2966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 2966): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 2966): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 2966): 	at java.io.FileReader.<init>(FileReader.java:66)
W/System.err( 2966): 	at com.motorola.motocare.action.MmcStatsAction.readMmcSectorWrites(MmcStatsAction.java:87)
W/System.err( 2966): 	at com.motorola.motocare.action.MmcStatsAction.appendMmcStatsReport(MmcStatsAction.java:70)
W/System.err( 2966): 	at com.motorola.motocare.action.MmcStatsAction.onReceiveImpl(MmcStatsAction.java:49)
W/System.err( 2966): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/System.err( 2966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2966): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2966): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 2966): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 2966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 2966): 	... 11 more
,I/UpdateIcingCorporaServi( 6203): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,W/System  ( 6412): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6412): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 6378): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6378): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel   ( 6412): Account registration failed 1-Redacted-21
,E/Babel   ( 6412): cyp: null
E/Babel   ( 6412): 	at cap.a(SourceFile:488)
E/Babel   ( 6412): 	at com.google.android.apps.hangouts.requestwriter.RequestWriter.a(SourceFile:895)
E/Babel   ( 6412): 	at dhe.a(SourceFile:232)
E/Babel   ( 6412): 	at dhd.handleMessage(SourceFile:573)
E/Babel   ( 6412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Babel   ( 6412): 	at android.os.Looper.loop(Looper.java:135)
E/Babel   ( 6412): 	at dhc.run(SourceFile:529)
,I/art     (  883): Explicit concurrent mark sweep GC freed 22810(1120KB) AllocSpace objects, 1(110KB) LOS objects, 33% free, 20MB/30MB, paused 1.787ms total 140.043ms
,V/JNIHelp ( 6378): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6572 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6412): Note: end time exceeds epoch: 
,I/UpdateIcingCorporaServi( 6203): UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
,W/System  ( 6378): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6378): Installed default security provider GmsCore_OpenSSL
,I/ValidateNoPeople(  883): mEvictionCount: 0
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6572): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/SQLiteLog( 6305): (284) automatic index on sqlite_sq_B7410EA8(STAT_DATA_ID)
,D/Finsky  ( 6572): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
E/SQLiteLog( 6305): (284) automatic index on sqlite_sq_B7419A30(STAT_DATA_ID)
,W/Settings( 6572): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6572): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6572): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6572): [1] Libraries$2.run: Finished loading 1 libraries.
,E/SQLiteLog( 6305): (284) automatic index on sqlite_sq_B74CD9E0(STAT_DATA_ID)
D/Ads     ( 6572): Skipping gmscore version check
E/SQLiteLog( 6305): (284) automatic index on sqlite_sq_B74CF9D0(STAT_DATA_ID)
,I/ActivityManager(  883): Killing 6360:com.motorola.context/u0a8 (adj 15): empty #7
,I/ActivityManager(  883): Killing 6342:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6360/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_6342/cgroup.procs: No such file or directory
,D/Finsky  ( 6572): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6572): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6623 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6436:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,D/PhoneMonitor( 6623): Register our PhoneStateListener
,I/ActivityManager(  883): Killing 6530:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_6530/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10060/pid_6436/cgroup.procs: No such file or directory
,V/SetupWizard( 6623): Connected to Gservices successfully
,I/art     ( 5001): Explicit concurrent mark sweep GC freed 14444(752KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 7MB/13MB, paused 759us total 42.856ms
,I/ActivityManager(  883): Killing 6203:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/GCM     ( 1692): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_6203/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6646 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1939): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/ResourcesManager( 6646): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 1939): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6665 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 6646): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.547ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 18.909ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.708ms
,V/AlarmManager(  883): done {466d6c5, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [2486ms]
,E/SQLiteLog( 6646): (284) automatic index on view_events(_id)
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6686 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6442:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6442/cgroup.procs: No such file or directory
,W/ResourcesManager( 6686): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/GAv4    ( 6665): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6665):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6665):   adb logcat -s GAv4
,W/GAv4    ( 6665): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 78471(4MB) AllocSpace objects, 41(653KB) LOS objects, 39% free, 14MB/24MB, paused 1.363ms total 126.050ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 6665): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6665): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6665): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/Herrevad( 1692): mobile connection type with no cell id
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6665): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6665): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6665): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6665): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6665): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6665): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6665): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6665): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  883): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@b458e89}
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 6646): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6646): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  883): Killing 6305:android.process.acore/u0a7 (adj 15): empty #7
,I/art     ( 6378): Explicit concurrent mark sweep GC freed 23629(770KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 10MB/14MB, paused 656us total 45.714ms
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6305/cgroup.procs: No such file or directory
,I/Gmail   ( 6378): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12184, normalSync: true
,I/Gmail   ( 6378): lowestBackward conversation id 0
,W/Flag    ( 6665): Duration spec must be at least 2 characters long
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 39968(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 15MB/25MB, paused 1.431ms total 95.930ms
,I/Gmail   ( 6378): notifyAccountChanged
,I/Gmail   ( 6378): getAccountsCursor
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6378): notifyAccountChanged
,W/Gmail   ( 6378): Sync complete for account: account:61035162
,I/Gmail   ( 6378): getAccountsCursor
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Killing 6572:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 49326(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.778ms total 129.189ms
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6572/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6738 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:36000 mC
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6738): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6738): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6738): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6738):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6738):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6738): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6738): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6738): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6738): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6738): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Icing   ( 1939): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/Gmail   ( 6378): Backfilling search sequence table
,I/Icing   ( 1939): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/GAV2    ( 6378): Thread[GAThread,5,main]: No campaign data found.
,I/WebViewFactory( 6738): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6738): Time to load native libraries: 2 ms (timestamps 7196-7198)
,I/LibraryLoader( 6738): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6738): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 6738): Expected native library version number "",actual native library version number ""
I/chromium( 6738): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6738): Initializing chromium process, singleProcess=true
,W/art     ( 6738): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6738): ApplicationContext is null in ApplicationStatus
,W/chromium( 6738): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6738): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6738): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6738): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6738): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6738): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6738): Local Branch: 
I/Adreno-EGL( 6738): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6738): Local Patches: NONE
I/Adreno-EGL( 6738): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6738): Requires BLUETOOTH permission
,I/NSApplication( 6738): Starting up...
,I/SyncAdapterService( 6738): Ignoring sync request for non-current account
,I/ActivityManager(  883): Killing 6623:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6623/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6816 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6816): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/WifiService(  883): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@b458e89}
,W/ResourcesManager( 6816): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6816): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6849 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  883): send {24eb26f1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): done {24eb26f1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [35ms]
,V/JNIHelp ( 6816): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/ActivityThread( 6816): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6816): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6816): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6816): GMSCore installation verified
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,I/ConfigStore( 6816): Config Database version: 1
,I/ActivityManager(  883): Killing 6412:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6412/cgroup.procs: No such file or directory
,D/Finsky  ( 6849): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  883): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=6879 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,D/Finsky  ( 6849): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/MediaRouter( 6816): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/Settings( 6849): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6849): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6849): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6849): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6849): Skipping gmscore version check
,D/Finsky  ( 6849): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/GHttpClientFactory( 6816): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6816): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 6849): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NetworkMonitor( 6816): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 6816): Sync started
,I/ActivityManager(  883): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=6912 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/NetworkMonitor( 6816): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6816): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6816): Using platform SSLCertificateSocketFactory
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 6879): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  883): Killing 6005:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6005/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 6686:com.motorola.context/u0a8 (adj 15): empty #7
,D/Finsky  ( 6849): [810] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6849): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6686/cgroup.procs: No such file or directory
I/ActivityManager(  883): Killing 6646:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_6646/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 6378:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10063/pid_6378/cgroup.procs: No such file or directory
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1939): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  883): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=6942 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 75967(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/30MB, paused 1.619ms total 132.104ms
,I/CheckinService( 1939): Done disabling old GoogleServicesFramework version
,D/Checkin ( 2966): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DeviceLockStats]
,I/MusicSyncAdapter( 6816): Skipping periodic sync. Last sync was 79726 seconds ago. Frequency: 86400
,I/art     ( 5001): Explicit concurrent mark sweep GC freed 4571(185KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 513us total 33.828ms
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service: pid=6970 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  883): send {2ee43bb3, *walarm*:com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service}
V/AlarmManager(  883): done {2ee43bb3, *walarm*:com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service} [52ms]
,W/MusicApiClient( 6816): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 6816): Sync ended
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,I/ActivityManager(  883): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=6992 uid=10108 gids={50108, 9997, 3003} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/MusicLeanback( 6816): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6816): Stop autocaching.
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20118dcb
,D/WearableService( 1692): callingUid 10016, callindPid: 1692
,E/GmsUtils( 6816): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6816): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAv4    ( 6942): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6942):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6942):   adb logcat -s GAv4
,I/Launcher( 1559): Deferring update until onResume
,W/GAv4    ( 6942): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6942): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6942): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6942): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,I/NewsWeather( 6992): NewsAccounts 2, AllSystemAccounts 1
,I/NewsWeather( 6992): Last usage 0, idle 1449751125 seconds, sync interval 2592000 seconds
I/NewsWeather( 6992): setPeriodicSync in 2592000 seconds
,W/art     ( 6942): Suspending all threads took: 9.812ms
,I/GCoreNlp( 1692): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7047 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7069 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 21.496ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 19.365ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.886ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,W/ResourcesManager( 7069): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Killing 6738:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_6738/cgroup.procs: No such file or directory
,I/Babel_SMS( 7069): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7069): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7069): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7069): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7069): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7069): MmsConfig.loadFromResources
,E/Babel_SMS( 7069): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7069): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  883): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7107 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7107): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6992): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CalendarProvider2( 7107): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,W/Settings( 7069): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7069): startup - clean
,I/Babel   ( 7069): deleted: false for 0
,W/System  ( 6992): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6992): Installed default security provider GmsCore_OpenSSL
,I/GoogleURLConnFactory( 6992): binding HttpService
,I/NewsWeather( 6992): ApiOperation url https://news.google.com/news/exec/fetchNewsEditions
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7131 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6665:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7069): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7069): Unsupported mime video/mpeg2
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_6665/cgroup.procs: No such file or directory
,I/VideoCapabilities( 7069): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,I/art     (  883): Explicit concurrent mark sweep GC freed 26022(1331KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.890ms total 139.060ms
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7160 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6912:com.google.android.apps.cloudprint/u0a53 (adj 15): empty #7
,I/ContactLocale( 7131): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10053/pid_6912/cgroup.procs: No such file or directory
,I/vclib   ( 7069): onServiceConnected
W/Babel   ( 7069): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 7160): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7160): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7160): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7160): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = BattCap]
,W/ResourcesManager( 6942): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6942): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 7069): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/JNIHelp ( 6942): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/art     ( 7069): Suspending all threads took: 13.753ms
,I/ActivityManager(  883): Killing 6879:com.google.android.apps.cloudprint:sync/u0a53 (adj 15): empty #7
,I/PackageBroadcastService( 1939): Null package name or gms related package.  Ignoreing.
,W/System  ( 7069): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7069): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 6970): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ProviderInstaller( 6942): Installed default security provider GmsCore_OpenSSL
,W/art     ( 6970): Attempt to remove local handle scope entry from IRT, ignoring
,D/WifiService(  883): New client listening to asynchronous messages
,I/ActivityManager(  883): Killing 6849:com.android.vending/u0a32 (adj 15): empty #7
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_SDCARD]
,I/UpdateIcingCorporaServi( 6970): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,I/CalendarProvider2( 7107): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7107): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
W/libprocessgroup(  883): failed to open /acct/uid_10053/pid_6879/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6849/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,I/ActivityManager(  883): Killing 6816:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_ACCESSORY]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6816/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PAIRING]
,W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7203 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,W/ResourcesManager( 7203): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,I/art     ( 2966): Background sticky concurrent mark sweep GC freed 55655(3MB) AllocSpace objects, 12(233KB) LOS objects, 29% free, 8MB/12MB, paused 6.351ms total 43.897ms
,I/NewsWeather( 6992): NewsEditionsResponse.current_edition: arw: "us"
I/NewsWeather( 6992): arx: "US"
I/NewsWeather( 6992): ary: "en"
I/NewsWeather( 6992): arz: "U.S."
,I/NewsWeather( 6992): syncNewsAppData traffic type BACKGROUND_POLL
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,I/NewsWeather( 6992): Google Apps Location Setting disabled.
,I/NewsWeather( 6992): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,I/HotwordDataManager( 6970): setSpeakerModel(thalitester@gmail.com,null)
,I/CalendarSyncAdapter( 5932): Found no pending settings
,I/ActivityManager(  883): Killing 7047:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7047/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7235 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7160:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/NewsWeather( 6992): syncNewsAppData for edition arw: "us"
I/NewsWeather( 6992): arx: "US"
I/NewsWeather( 6992): ary: "en"
I/NewsWeather( 6992): arz: "U.S."
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7160/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,I/NewsWeather( 6992): Update section Top Stories
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,I/NewsWeather( 6992): Update section Suggested for you
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,I/NewsWeather( 6992): Update section World
,I/NewsWeather( 6992): Update section U.S.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,I/NewsWeather( 6992): Update section Business
,D/Finsky  ( 7235): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/NewsWeather( 6992): Update section Technology
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,I/NewsWeather( 6992): Update section Entertainment
,I/NewsWeather( 6992): Update section Sports
,I/NewsWeather( 6992): Update section Science
,I/Icing   ( 1939): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/NewsWeather( 6992): Update section Health
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,I/NewsWeather( 6992): DownSync SectionedStories success
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,I/Icing   ( 1939): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Finsky  ( 7235): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,W/Settings( 7235): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7235): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Finsky  ( 7235): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7235): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7235): Skipping gmscore version check
,I/ActivityManager(  883): Killing 6942:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10105/pid_6942/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7283 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6970:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/WifiService(  883): Client connection lost with reason: 4
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_6970/cgroup.procs: No such file or directory
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Finsky  ( 7235): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 7283): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,I/art     (  883): Explicit concurrent mark sweep GC freed 23280(1130KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.627ms total 132.170ms
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,D/Finsky  ( 7235): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/NewsWeather( 6992): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
,I/ActivityManager(  883): Killing 7107:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_7107/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7313 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,W/ResourcesManager( 7313): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7313): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypes]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengths]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOn]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOff]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = AppUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = AppUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L1 event name = DC_ACCOUNT]
,I/CalendarProvider2( 7313): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7313): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  883): Killing 7131:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{a7d1f6b u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7131/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:36000 mC
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=rO0ABXcEAAAAAXNyABFqYXZhLnV0aWwuSGFzaE1hcAUH2sHDFmDRAwABRgAKbG9hZEZhY3RvcnhwP0AAAHcIAAABAAAAAGp0AApldmVudDgtODc4c3IAUWNvbS5tb3Rvcm9sYS5tb3RvY2FyZS5pbnRlcm5hbC53YWtlbG9ja3MuS2VybmVsV2FrZWxvY2tBY3Rpb24kS2VybmVsV2FrZWxvY2tFbnRyeQAAAAAAAAABAgAFSgAObUFjdGl2ZVNpbmNlTXNKAAZtQ291bnRKAAttRHVyYXRpb25Nc0oADW1MYXN0Q2hhbmdlTXNMAAVtTmFtZXQAEkxqYXZhL2xhbmcvU3RyaW5nO3hwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAjdpxAH4AAnQAEnN0a19pbnB1dF93YWtlbG9ja3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQbcQB+AAZ0AAlwaWwtbW9kZW1zcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACPHEAfgAIdAAaaXBjMDAwMDAwNTRfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAgAAAAAAAAAAgAAAAAAAL8OXEAfgAKdAAObXNtX2hzdXNiX2hvc3RzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHNXEAfgAMdAAaaXBjMDAwMDAwMThfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAKDvHEAfgAOdAAKZXZlbnQ0LTg3OHNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAQAAAAAAAv0acQB+ABB0ABJzeW5hcHRpY3NfZndfZmxhc2hzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/3EAfgASdAAaaXBjMDAwMDAwNTNfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACV8nEAfgAUdAAKZXZlbnQ3LTg3OHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI1ocQB+ABZ0AAZ2aWRlbzFzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAAdQAAAAAAACdoXEAfgAYdAAVcXBucC1jaGFyZ2VyLWU0OWU1YTAwc3EAfgADAAAAAAAC/v8AAAAAAAAAAQAAAAAAAv7/AAAAAAAABXVxAH4AGnQACXBpbC13Y25zc3NxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAABggAAAAAAAB4qcQB+ABx0ABppcGMwMDAwMDAxN190aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACpwcQB+AB50AA9xbXV4ZF9wb3J0X3dsXzdzcQB+AAMAAAAAAAAAAAAAAAAAAAALAAAAAAAAAAEAAAAAAADizXEAfgAgdAAXcm10X3N0b3JhZ2VfLTEyMDU0NzUxOTJzcQB+AAMAAAAAAAAAAAAAAAAAAAACAAAAAAAAABkAAAAAAAAi/nEAfgAidAAaaXBjMDAwMDAwNTlfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAARAAAAAAAAAAgAAAAAAAKDvXEAfgAkdAAXaXBjMDAwMDAwMGJfdGltZV9kYWVtb25zcQB+AAMAAAAAAAAAAAAAAAAAAAApAAAAAAAAAAMAAAAAAAKDvXEAfgAmdAALbW1jMV9kZXRlY3RzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAATcAAAAAAAAGbXEAfgAodAAaaXBjMDAwMDAwMTZfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAKDvHEAfgAqdAASaXBjX3J0cl9zbWRfaXBjcnRyc3EAfgADAAAAAAAAAAAAAAAAAAAATQAAAAAAAAABAAAAAAAC/GhxAH4ALHQAF2lwYzAwMDAwMDA2X3JtdF9zdG9yYWdlc3EAfgADAAAAAAAAAAAAAAAAAAAAJgAAAAAAAAN8AAAAAAACg71xAH4ALnQAB0RJQUdfV1NzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADG3EAfgAwdAAGMi0wMDQ4c3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBtxAH4AMnQADGdwaW9fa2V5cy43NXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAc4cQB+ADR0AAhzbWRjbnRsM3NxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAAOKucQB+ADZ0ABVxY3JpbF9wcmVfY2xpZW50X2luaXRzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAD5MAAAAAAAAqn3EAfgA4dAAMcG93ZXItc3VwcGx5c3EAfgADAAAAAAAAAAAAAAAAAAAAIQAAAAAAAA2FAAAAAAAC/DJxAH4AOnQAEGlwYzAwMDAwMDBkX3JpbGRzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAayHEAfgA8dAAIc21kY250bDRzcQB+AAMAAAAAAAAAAAAAAAAAAAALAAAAAAAAAAEAAAAAAADitXEAfgA+dAARcXBucC1ibXMtZTQ5ZTVjMDBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFnHEAfgBAdAAGdmlkZW8yc3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAABmAAAAAAAAnm9xAH4AQnQACHNtZGNudGwyc3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAABAAAAAAAA4qdxAH4ARHQAF2lwYzAwMDAwMDBjX3RpbWVfZGFlbW9uc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAGRNxAH4ARnQACHNtZGNudGwwc3EAfgADAAAAAAAAAAAAAAAAAAAA+AAAAAAAAAAeAAAAAAAA4phxAH4ASHQAG2lwYzAwMDAwMDIzX3FtaV9tb3RleHRfaG9va3NxAH4AAwAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAvxocQB+AEp0ABppcGMwMDAwMDA1NV9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAABEAAAAAAAAACAAAAAAAAoO9cQB+AEx0ABppcGMwMDAwMDAxNF90aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAAAMAAAAAAAAAAAAAAAAAACpxcQB+AE50AA1zbXNtX3NuYXBzaG90c3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAFAAAAAAAAOgdxAH4AUHQAG1Bvd2VyTWFuYWdlclNlcnZpY2UuRGlzcGxheXNxAH4AAwAAAAAAAAhMAAAAAAAAAAIAAAAAAAJVdQAAAAAAAvwocQB+AFJ0AARxbWkxc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkNxAH4AVHQADXFwbnBfc29jX3dha2VzcQB+AAMAAAAAAAAAAAAAAAAAAAAWAAAAAAAACqkAAAAAAALH5HEAfgBWdAARcXBucC1ydGMtZTRhMzBlMDBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEMXEAfgBYdAAEcW1pMnNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAJDcQB+AFp0AA9xbXV4ZF9wb3J0X3dsXzRzcQB+AAMAAAAAAAAAAAAAAAAAAAALAAAAAAA
E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,E/MC_Serializer( 2966): Exception in deSerializeObject s=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
E/MC_Serializer( 2966): Exception in deSerializeObject s=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
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = MMCStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = MultiUserStats]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,I/ActivityManager(  883): Killing 7069:com.google.android.talk/u0a70 (adj 15): empty #7
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7069/cgroup.procs: No such file or directory
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,V/AlarmManager(  883): send {2ba1095, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED}
V/AlarmManager(  883): send {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {2ba1095, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [2ms]
,V/AlarmManager(  883): done {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS event name = STORAGESTATS]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L3 event name = SystemLocale]
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L3 event name = HwProps]
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.CallLogProvider: pid=7367 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 7367): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7203:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7203/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 5001:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_5001/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311390, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-378, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311962, SEQNUM=4434, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-379, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ClearcutLoggerApiImpl( 1692): disconnect managed GoogleApiClient
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:35000 mC
,I/ActivityManager(  883): Killing 6992:com.google.android.apps.genie.geniewidget/u0a108 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7235:com.android.vending/u0a32 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10108/pid_6992/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7235/cgroup.procs: No such file or directory
,W/IcingInternalCorpora( 1939): getNumBytesRead when not calculated.
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=304, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311339, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-426, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
,I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  883): send {3b4028e7, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM} [13ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
,I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,V/AlarmManager(  883): done {3b4028e7, *alarm*:android.intent.action.TIME_TICK} [79ms]
,I/ConfigService( 1692): onCreate
,I/LaunchCheckinHandler(  883): cleanup(): cleared. Last call was 29770 ms ago
I/ActivityManager(  883): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7417 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityThread( 1939): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  883): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 332088, reason: UserStart
,I/GAv4    ( 7417): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7417):   adb logcat -s GAv4
,W/GAv4    ( 7417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7417): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteLog( 7417): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7417): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7417): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7417): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7417): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Killing 7283:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_7283/cgroup.procs: No such file or directory
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigService( 1692): onDestroy
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310328, SEQNUM=4448, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-448, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  883): send {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {24939672, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311098, SEQNUM=4450, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-461, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5181): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC

```
