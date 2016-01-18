#### Test 56151093f6e24ff_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  883): send {8d22921, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {1ffe1324, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  883): done {1ffe1324, *walarm*:com.google.android.intent.action.SEND_IDLE} [19ms]
V/AlarmManager(  883): done {8d22921, *alarm*:android.intent.action.TIME_TICK} [47ms]
--------- beginning of main
D/AndroidRuntime( 7064): 
D/AndroidRuntime( 7064): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7064): CheckJNI is OFF
D/AndroidRuntime( 7064): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7083 uid=10460 gids={50460, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7064): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  883): Explicit concurrent mark sweep GC freed 33252(1632KB) AllocSpace objects, 2(219KB) LOS objects, 33% free, 20MB/30MB, paused 1.536ms total 128.742ms
,I/WebViewFactory( 7083): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7083): Time to load native libraries: 3 ms (timestamps 6444-6447)
I/LibraryLoader( 7083): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7083): Binding Chromium to main looper Looper (main, tid 1) {258d1cc7}
,I/LibraryLoader( 7083): Expected native library version number "",actual native library version number ""
,I/chromium( 7083): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7083): Initializing chromium process, singleProcess=true
,W/art     ( 7083): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7083): ApplicationContext is null in ApplicationStatus
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{3adb4e8d u0 com.test.thalitest/.MainActivity t6}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,W/chromium( 7083): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7083): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7083): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7083): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7083): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7083): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7083): Local Branch: 
I/Adreno-EGL( 7083): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7083): Local Patches: NONE
I/Adreno-EGL( 7083): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f88c245:true
,W/art     ( 7083): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7083): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7083): CordovaWebView is running on device made by: motorola
,E/global frequency( 2737): no tags to log
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/art     ( 7083): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7083): Attempt to remove local handle scope entry from IRT, ignoring
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/OpenGLRenderer( 7083): Render dirty regions requested: true
,D/Atlas   ( 7083): Validating map...
,W/chromium( 7083): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 57983(3MB) AllocSpace objects, 36(1249KB) LOS objects, 40% free, 7MB/12MB, paused 1.071ms total 63.513ms
,I/OpenGLRenderer( 7083): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7083): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1165
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s83ms (total +1s165ms)
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/IInputConnectionWrapper( 7083): showStatusIcon on inactive InputConnection
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2737): Explicit concurrent mark sweep GC freed 20202(1235KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 1.052ms total 69.156ms
,E/Adreno-ES20( 7083): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7083): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 7083): Cannot call determinedVisibility() - never saw a connection for the pid: 7083
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 3740(159KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 595us total 31.037ms
,D/BSUtils ( 2737): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2737): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2737): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2737): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/JsMessageQueue( 7083): Set native->JS mode to OnlineEventsBridgeMode
,D/Checkin ( 2737): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,D/jxcore_app_log( 7083): JniHelper::setJavaVM(0xb848e310), pthread_self() = -1199445024
D/JX-Cordova( 7083): jxcore cordova android initializing
,I/art     (  883): Explicit concurrent mark sweep GC freed 8586(596KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.899ms total 141.578ms
,I/global frequency( 2737): BcsDSCheckin.events found events 75
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2737): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 2737): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,W/jxcore-log( 7083): Initializing JXcore engine
W/jxcore-log( 7083): JXcore engine is ready
,W/jxcore-log( 7083): Starting JXcore engine
,W/.test.thalitest( 7083): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10460 path="socket:[9893]" dev="sockfs" ino=9893 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 7083): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10460 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 7083): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10460 path="socket:[8479]" dev="sockfs" ino=8479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7083): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10460 path="socket:[31465]" dev="sockfs" ino=31465 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 7083): Platform android
W/jxcore-log( 7083): 
W/jxcore-log( 7083): Process ARCH arm
W/jxcore-log( 7083): 
,D/MMApiWSBase( 2737): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2737): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2737): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2737): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  883): 75 events delete 0 left
,I/global frequency( 2737): BcsDSCheckin.events found events 0
,D/Checkin ( 2737): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2737): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/DataUsage( 2737): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,I/jxcore-log( 7083): JXcore Cordova bridge is ready!
I/jxcore-log( 7083): 
,W/jxcore-log( 7083): JXcore engine is started
,I/chromium( 7083): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7083): Toggling radios to true
I/jxcore-log( 7083): 
,D/BluetoothAdapter( 7083): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=7083, uid=10460
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7083): Radios toggled
I/jxcore-log( 7083): 
I/jxcore-log( 7083): My device name is: motorola-XT1072
I/jxcore-log( 7083): 
,I/wpa_supplicant( 1412): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  313): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  313):  STA Disconnected !!
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): get_property_value, Enter
I/MDMCTBK (  313): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  313): get_property_value, Exit
I/MDMCTBK (  313): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  313): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  313): set_property_value, Enter
I/MDMCTBK (  313): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  477): NL - Read 1004 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
I/wpa_supplicant( 1412): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/MDMCTBK (  313): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  313): set_property_value, Exit
I/MDMCTBK (  313): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  313): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  313): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  313): set_property_value, Enter
I/MDMCTBK (  313): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  313): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  313): set_property_value, Exit
E/MDMCTBK (  313): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  313): Event received = CTRL-EVENT-REGDOM-CHANGE
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
D/Tethering(  883): InitialState.processMessage what=4
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
I/wpa_supplicant( 1412): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  313): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883):  0
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1412): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  310): Clearing all IP addresses on wlan0
D/TCMD    (  477): NL - Read 60 bytes from update socket.
D/TCMD    (  477): NL - ignore NL message, type = 21
D/TCMD    (  477): Listening for incoming client connection request
,V/NativeCrypto( 1715): Read error: ssl=0xb87de760: I/O error during system call, Connection timed out
,V/NativeCrypto( 1715): SSL shutdown failed: ssl=0xb87de760: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname,
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7178 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  883): connected time updated 132688
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1412): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1412): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  313): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1412): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 7178): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  310): Clearing all IP addresses on wlan0
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 7178): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7178): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7178): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7178): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7178): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7178): MmsConfig.loadFromResources
,E/Babel_SMS( 7178): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7178): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  313): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  313): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1412): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  313): Event received = Trying to associate with
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1412): DSDS: eapol_sm_notify_config config->sim_num = 1
D/TCMD    (  477): NL - Read 56 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  883): [1,453,125,307,941 ms] noteScanEnd no scan source
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@85b858b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 7178): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7178): startup - clean
,I/Babel   ( 7178): deleted: false for 0
,V/AlarmManager(  883): send {2ac26287, *walarm*:android.content.syncmanager.SYNC_ALARM}
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7217 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/TCMD    (  477): NL - Read 312 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 192 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 1004 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
I/wpa_supplicant( 1412): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  313): Event received = Associated with c0:ff:d4
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  477): NL - Read 80 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 80 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1412): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  313): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1412): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  313): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  313):  STA Connected !!
D/TCMD    (  477): NL - Read 1004 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
E/MDMCTBK (  313): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  313): get_freq !!, resp=2412
I/MDMCTBK (  313): get_freq !!, Strip data
I/MDMCTBK (  313): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): get_property_value, Enter
I/MDMCTBK (  313): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  313): get_property_value, Exit
I/MDMCTBK (  313): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  313): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  313): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  313): set_property_value, Enter
I/MDMCTBK (  313): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  313): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  313): set_property_value, Exit
I/MDMCTBK (  313): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  313): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  313): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): get_property_value, Enter
I/MDMCTBK (  313): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  313): get_property_value, Exit
I/MDMCTBK (  313): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216070224
I/MDMCTBK (  313): return from set_get_from_wpa_supplicant
I/MDMCTBK (  313): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  313): set_property_value, Enter
I/MDMCTBK (  313): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  313): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  313): set_property_value, Exit
E/MDMCTBK (  313): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  313): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  313): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  313): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  313): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  313): , reply_len: 3, ret: 0
E/MDMCTBK (  313): MdmCutbackHndler, resp=OK
E/MDMCTBK (  313): 
D/MDMCTBK (  313): wifi_set_tx_pwr: Exit
I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 30.354ms
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.928ms
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 20.335ms
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  310): Setting iface cfg
E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1412): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1412): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b672c8c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b672c8c target=com.android.internal.util.StateMachine$SmHandler }
,W/ResourcesManager( 7217): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7178): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7178): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7178): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 6841:com.google.android.videos/u0a98 (adj 15): empty #7
,E/DHCPCD  ( 7237): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 7237): version 5.5.6 starting
E/DHCPCD  ( 7237): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 7237): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 7237): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  883): failed to open /acct/uid_10098/pid_6841/cgroup.procs: No such file or directory
,I/vclib   ( 7178): onServiceConnected
W/Babel   ( 7178): Attempted to change video mute state without an active call.
,V/AlarmManager(  883): done {2ac26287, *walarm*:android.content.syncmanager.SYNC_ALARM} [498ms]
,D/DHCPCD  ( 7237): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 7237): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 7237): wlan0: sending REQUEST (xid 0x5999338a), next in 4.66 seconds
,I/ActivityManager(  883): Killing 6944:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_6944/cgroup.procs: No such file or directory
,I/DHCPCD  ( 7237): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 7237): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 7237): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 7237): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7237): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7237): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  477): NL - Read 60 bytes from update socket.
D/TCMD    (  477): NL - ignore NL message, type = 20
D/TCMD    (  477): Listening for incoming client connection request
D/DHCPCD  ( 7237): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 13:55:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453125310205], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453125310185]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6920): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6920): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6920): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1469): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2737): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7302 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2737): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2737): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2737): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2737): Registering with Alarm Manager to restart CCE
D/CCE     ( 2737): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2737): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2737): [debug] > CusSM.onRadioDown
,V/Mms     ( 7302): mnc/mcc: 
V/Mms     ( 7302): tag: int value: recipientLimit - 20
V/Mms     ( 7302): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7302): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7302): tag: int value: maxSubjectLength - 80
V/Mms     ( 7302): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7302): tag: bool value: enableGroupMms - false
V/Mms     ( 7302):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7302): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7331 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6703:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PhoneMonitor( 7331): Register our PhoneStateListener
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6703/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7331): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7331): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=7349 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6510:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6510/cgroup.procs: No such file or directory
,W/ResourcesManager( 7349): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7349): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7349): VM with version 2.1.0 has multidex support
I/MultiDex( 7349): install
I/MultiDex( 7349): VM has multidex support, MultiDex support library is disabled.
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,V/JNIHelp ( 7349): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7349): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7349): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3156329e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7349): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  883): send {1d6f78f4, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/NativeLibraryUtils( 7349): Install completed successfully. count=14 extracted=0
,I/CheckinService( 7349): Checkin interval check for package: unspecified last checkin: 1453125222293 min interval config: 0 actual interval: 89480
,I/CheckinService( 7349): Disabling old GoogleServicesFramework version
,I/CheckinService( 7349): Checking schedule, now: 1453125311842 next: 1453125252273
I/CheckinService( 7349): active receiver: enabled
,I/iu.SyncManager( 7349): SYNC; picasa accounts
,D/NetworkLogImpl( 7349): Loaded NetworkSpeedPredictor
,I/CheckinService( 7349): Preparing to send checkin request
,I/iu.Environment( 7349): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 7349): Accumulating logs since 1453125219318
,I/iu.UploadsManager( 7349): num queued entries: 0
I/iu.UploadsManager( 7349): num updated entries: 0
,I/iu.SyncManager( 7349): NEXT; no task
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7383 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7349): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7349): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7083): 
,I/CheckinRequestBuilder( 7349): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 7349): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7411 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 7178): connection state changed from UNKNOWN to CONNECTED
,I/art     (  883): Explicit concurrent mark sweep GC freed 46240(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.843ms total 143.710ms
,I/ActivityManager(  883): Killing 7217:com.motorola.context/u0a8 (adj 15): empty #7
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_7217/cgroup.procs: No such file or directory
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7083): 
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7083): 
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7083): 
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7411): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7411):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7411):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7083): 
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7083): 
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7446 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/jxcore-log( 7083): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7083): 
,W/GAv4    ( 7411): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7411): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 7446): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7446): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 7411): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 7446): VM with version 2.1.0 has multidex support
I/MultiDex( 7446): install
I/MultiDex( 7446): VM has multidex support, MultiDex support library is disabled.
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): now: 206958 ,futureTime: 9223372036854775807
,D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): now: 206960 ,futureTime: 9223372036854775807
,D/PollingManager( 2737): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2737): now: 206960 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2737): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): now: 206964 ,futureTime: 86476707
D/Central_PollingManager( 1469): Polling alarm set to expire at: 86476707 Current Time: 206964
,D/OtaApp  ( 2737): [debug] > PollingManagerService, now: 206965 ,futureTime: 85721022
D/OtaApp  ( 2737): [debug] > Polling alarm set to expire at: 85721022 Current Time: 206965
,I/NetworkMonitor( 6920): type=WIFI subType= reason=null isConnected=true
,V/JNIHelp ( 7446): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MMApiProvisionService( 2737): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2737): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2737): createDeviceIdOrLogin update_device
D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2737): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2737): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2737): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2737): createDeviceIdOrLogin update_device
D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2737): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2737): set mOutstandingReq to true.
I/ Nonce  ( 2737):  Nonce getNonce 
I/ Nonce  ( 2737):  Nonce Request 
I/ Nonce  ( 2737):  Nonce execute Request 
,D/MMApiWebService( 2737): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2737): isDeviceProvisioned: deviceId = 2072049230914535424
,W/ActivityThread( 7446): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7446): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f19bfd8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7446): Installed default security provider GmsCore_OpenSSL
,D/CCE     ( 2737): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2737): createDeviceIdOrLogin update_device
D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2737): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2737): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2737): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2737): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2737): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2737): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2737): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2737): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2737): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2737): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2737): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 4157(177KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 695us total 29.244ms
,I/art     ( 7446): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7446): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/MMApiWebService( 2737): generating token using payload instead of using session token
,D/ Nonce  ( 2737):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2737): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,I/WebViewFactory( 7411): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NativeLibraryUtils( 7446): Install completed successfully. count=14 extracted=0
,I/LibraryLoader( 7411): Time to load native libraries: 1 ms (timestamps 7332-7333)
I/LibraryLoader( 7411): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7411): Binding Chromium to main looper Looper (main, tid 1) {23e8cf08}
I/LibraryLoader( 7411): Expected native library version number "",actual native library version number ""
I/chromium( 7411): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/WVCdm   (  315): Instantiating CDM.
,I/WVCdm   (  315): CdmEngine::OpenSession
I/WVCdm   (  315): Level3 Library Sep 25 2014 17:10:03
,I/BrowserStartupController( 7411): Initializing chromium process, singleProcess=true
,W/art     ( 7411): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7411): ApplicationContext is null in ApplicationStatus
,W/WVCdm   (  315): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/chromium( 7411): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/DrmWidevineDash(  315): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  315): Service_Initialize: starts!
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
,D/QSEECOMAPI: (  315): Loaded image: APP id = 3
,D/DrmWidevineDash(  315): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb0000
E/DrmWidevineDash(  315): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb0000
E/libEGL  ( 7411): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7411): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: starts!
,I/Adreno-EGL( 7411): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7411): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7411): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7411): Local Branch: 
I/Adreno-EGL( 7411): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7411): Local Patches: NONE
I/Adreno-EGL( 7411): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  315): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: starts! SID=0xb13c0960
,D/DrmWidevineDash(  315): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: starts! randomData=0xb84c4708, dataLength=8
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb84f6568, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  315): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  315): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  315): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  315): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: starts! deviceID=0xb862f730, idLength=0xb5485730
,D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  315): PrepareKeyRequest: nonce=2809109355
D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8548ed8
D/DrmWidevineDash(  315): message_length=1591, signature=0xb85d34f0, signature_length=3041416980
,I/jxcore-log( 7083): Test app app.js loaded
I/jxcore-log( 7083): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7083): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7083): BLE advertisement is supported
I/jxcore-log( 7083): 
,I/chromium( 7083): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  315): CdmEngine::CloseSession
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  315): L3 Terminate.
D/DrmWidevineDash(  315): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  315): Service_Uninitialize: starts!
D/QSEECOMAPI: (  315): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  315): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  315): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  315): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 7411): Requires BLUETOOTH permission
,I/NSApplication( 7411): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7503 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6920:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6920/cgroup.procs: No such file or directory
,I/ Nonce  ( 2737):  Nonce Reponse 
D/        ( 2737): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"e51f6706-b2e5-40ed-9a94-05787a2bc144"}
D/MMApiWSBase( 2737): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2737):  Nonce Handle Reponse 
D/MMApiProvisionService( 2737): mOutstandingReq set to false
,I/dex2oat ( 7527): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/MMApiProvisionService( 2737):  pTime 1453032756427 sExp 172742 cTime 1453125314334 tTime 1453205498427
D/MMApiProvisionService( 2737):  No login Required 
,I/dex2oat ( 7527): dex2oat took 167.389ms (threads: 4)
,I/Adreno-EGL( 7446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7446): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7446): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7446): Local Branch: 
I/Adreno-EGL( 7446): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7446): Local Patches: NONE
I/Adreno-EGL( 7446): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7546 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7302:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 7446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7446): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7446): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7446): Local Branch: 
I/Adreno-EGL( 7446): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7446): Local Patches: NONE
I/Adreno-EGL( 7446): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7302/cgroup.procs: No such file or directory
,W/ResourcesManager( 7546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  315): CdmEngine::OpenSession
,I/WVCdm   (  315): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  315): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  315): Service_Initialize: starts!
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
,E/QSEECOMAPI: (  315): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
W/DataUsage( 2737): invalid counter update blocked: 'err' by 0
D/Checkin ( 2737): publish the event [tag = MOT_CCE event name = LOG]
,D/QSEECOMAPI: (  315): Loaded image: APP id = 3
,D/DrmWidevineDash(  315): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb0000
E/DrmWidevineDash(  315): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb0000
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
,D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  315): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: starts! SID=0xbeb344e0
D/DrmWidevineDash(  315): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: starts! randomData=0xb85d3370, dataLength=8
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8549760, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  315): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  315): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  315): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  315): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: starts! deviceID=0xb862f770, idLength=0xb5585730
,D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  315): PrepareKeyRequest: nonce=4221355410
D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb84f8648
D/DrmWidevineDash(  315): message_length=1626, signature=0xb84f8ca8, signature_length=3042465556
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7572 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  315): CdmEngine::CloseSession
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  315): L3 Terminate.
D/DrmWidevineDash(  315): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  315): Service_Uninitialize: starts!
D/QSEECOMAPI: (  315): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  315): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  315): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7596 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7383:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7572): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7331:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7383/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7331/cgroup.procs: No such file or directory
,I/MusicStore( 7596): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Adreno-EGL( 7446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7446): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7446): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7446): Local Branch: 
I/Adreno-EGL( 7446): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7446): Local Patches: NONE
I/Adreno-EGL( 7446): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7446): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7446): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7446): Local Branch: 
I/Adreno-EGL( 7446): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7446): Local Patches: NONE
I/Adreno-EGL( 7446): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  883): Explicit concurrent mark sweep GC freed 11628(544KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.689ms total 114.788ms
,I/CheckinRequestBuilder( 7349): Classify the device as Phone.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7596): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7596): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7596): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7596): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@114fbe13: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7596): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7596): GMSCore installation verified
,I/ConfigStore( 7596): Config Database version: 1
,I/CheckinTask( 7349): Sending checkin request (9451 bytes)
,I/MediaRouter( 7596): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7596): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7596): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7596): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7629 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7596): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7596): Using platform SSLCertificateSocketFactory
I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 21.630ms
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 19.731ms
,I/ActivityManager(  883): Killing 7178:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.911ms
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7178/cgroup.procs: No such file or directory
,V/Mms     ( 7629): mnc/mcc: 
,V/Mms     ( 7629): tag: int value: recipientLimit - 20
,V/Mms     ( 7629): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7629): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7629): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7629): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7629): tag: bool value: enableGroupMms - false
V/Mms     ( 7629):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7629): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7655 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7411:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/CheckinRequestBuilder( 7349): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7411/cgroup.procs: No such file or directory
,E/ActivityThread( 7349): Failed to find provider info for com.google.android.wearable.settings
,D/PhoneMonitor( 7655): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7655): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7655): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 7349): Checkin interval check for package: unspecified last checkin: 1453125222293 min interval config: 0 actual interval: 93933
,I/art     ( 6668): Explicit concurrent mark sweep GC freed 1651(59KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 379us total 35.651ms
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7673 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7503:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7503/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 7349): Classify the device as Phone.
,I/CheckinTask( 7349): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7349): Checking schedule, now: 1453125316511 next: 1453726453506
I/CheckinService( 7349): active receiver: disabled
,I/CheckinService( 7349): Checking schedule, now: 1453125316530 next: 1453726453506
I/CheckinService( 7349): active receiver: disabled
,D/CheckinService( 7349): Recording last checkin time for package unspecified as 1453125316533
,I/ActivityManager(  883): Killing 7572:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7546:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7572/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7546/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7693 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7596:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7596/cgroup.procs: No such file or directory
,W/ResourcesManager( 7693): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7693): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7693): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7693): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7693): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7693): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7693): MmsConfig.loadFromResources
E/Babel_SMS( 7693): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7693): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7693): startup - clean
,I/Babel   ( 7693): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7731 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7693): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7693): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7693): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7693): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7693): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7693): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7693): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7693): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7693): onServiceConnected
,W/Babel   ( 7693): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7731): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7731):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7731):   adb logcat -s GAv4
,I/Babel   ( 7693): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7629:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7629/cgroup.procs: No such file or directory
,W/GAv4    ( 7731): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7731): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7731): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7731): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7731): Time to load native libraries: 2 ms (timestamps 1596-1598)
I/LibraryLoader( 7731): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7731): Binding Chromium to main looper Looper (main, tid 1) {23e8cf08}
,I/LibraryLoader( 7731): Expected native library version number "",actual native library version number ""
,I/chromium( 7731): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7731): Initializing chromium process, singleProcess=true
,W/art     ( 7731): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7731): ApplicationContext is null in ApplicationStatus
,W/chromium( 7731): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7731): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7731): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7731): Local Branch: 
I/Adreno-EGL( 7731): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7731): Local Patches: NONE
I/Adreno-EGL( 7731): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7731): Requires BLUETOOTH permission
,I/NSApplication( 7731): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7799 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7655:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7655/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7818 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7673:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7673/cgroup.procs: No such file or directory
,W/ResourcesManager( 7818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7838 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 11236(569KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.726ms total 120.721ms
,I/ActivityManager(  883): Killing 7731:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7838): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7693:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2737): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7693/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7731/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2737): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2737): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2737): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2737): onServiceConnected()
,D/GetNotificationsWS( 2737): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2737): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2737): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,E/MDM     ( 1715): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7349): Restart initialization of location
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  883): done {1d6f78f4, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [7266ms]
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7879 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,W/IcingInternalCorpora( 7349): getNumBytesRead when not calculated.
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7908 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7908): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7908): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7908): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7908): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@114fbe13: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7908): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7908): GMSCore installation verified
,I/ConfigStore( 7908): Config Database version: 1
,I/MediaRouter( 7908): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7908): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7908): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7908): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7942 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7908): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7908): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7942): mnc/mcc: 
,V/Mms     ( 7942): tag: int value: recipientLimit - 20
V/Mms     ( 7942): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7942): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7942): tag: int value: maxSubjectLength - 80
V/Mms     ( 7942): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7942): tag: bool value: enableGroupMms - false
,V/Mms     ( 7942):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7942): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7976 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.732ms
,I/ActivityManager(  883): Killing 7799:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.523ms
,D/PhoneMonitor( 7976): Register our PhoneStateListener
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.751ms
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7799/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7976): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7976): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7818:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7818/cgroup.procs: No such file or directory
,I/CheckinService( 7349): Checkin interval check for package: unspecified last checkin: 1453125316533 min interval config: 0 actual interval: 3594
,I/CheckinService( 7349): Checkin interval check for package: unspecified last checkin: 1453125316533 min interval config: 0 actual interval: 3598,
,I/CheckinService( 7349): Checking schedule, now: 1453125320133 next: 1453125346506
,I/CheckinService( 7349): active receiver: disabled
,I/CheckinService( 7349): Checking schedule, now: 1453125320146 next: 1453125346506
I/CheckinService( 7349): active receiver: disabled
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7997 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7997): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7997): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7997): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7997): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7997): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7997): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7997): MmsConfig.loadFromResources
,E/Babel_SMS( 7997): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7997): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7997): startup - clean
,I/Babel   ( 7997): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8034 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7838:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7838/cgroup.procs: No such file or directory
,W/VideoCapabilities( 7997): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7997): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7997): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7997): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7997): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7997): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7997): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7997): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7997): onServiceConnected
W/Babel   ( 7997): Attempted to change video mute state without an active call.
,I/Babel   ( 7997): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7908:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 9851(459KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.612ms total 126.668ms
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7908/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8034): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 8034): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8034):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8034):   adb logcat -s GAv4
W/ContextImpl( 8034): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8034): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8034): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8034): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8034): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8034): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8034): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8034): Time to load native libraries: 2 ms (timestamps 5134-5136)
I/LibraryLoader( 8034): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8034): Binding Chromium to main looper Looper (main, tid 1) {23e8cf08}
,I/LibraryLoader( 8034): Expected native library version number "",actual native library version number ""
,I/chromium( 8034): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8034): Initializing chromium process, singleProcess=true
,W/art     ( 8034): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8034): ApplicationContext is null in ApplicationStatus
,W/chromium( 8034): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8034): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8034): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8034): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8034): Local Branch: 
I/Adreno-EGL( 8034): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8034): Local Patches: NONE
I/Adreno-EGL( 8034): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8034): Requires BLUETOOTH permission
,I/NSApplication( 8034): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8106 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7942:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7942/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8125 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7976:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7976/cgroup.procs: No such file or directory
,W/ResourcesManager( 8125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8145 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Killing 7446:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  883): Killing 7879:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 8145): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2737): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_7446/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7879/cgroup.procs: No such file or directory
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/GetNotificationsWS( 2737): bindWebServices(): registering our AIDL callback...
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@885facf
,I/SundryService( 2737): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2737): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2737): onServiceConnected()
D/GetNotificationsWS( 2737): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2737): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2737): started with background data enabled, making sure notification mechanism is enabled
I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,E/MDM     ( 1715): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7349): Restart initialization of location
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2737): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2737): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2737): [debug] > In cancelAnyPendingIntentSetPreviously
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,I/art     ( 2737): Explicit concurrent mark sweep GC freed 35353(2MB) AllocSpace objects, 5(103KB) LOS objects, 40% free, 11MB/19MB, paused 947us total 69.834ms
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2737): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2737): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2737): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8185 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2737): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2737): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2737): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2737): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2737): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2737): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2737): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2737): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2737): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
,W/IInputConnectionWrapper( 7083): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 8185): Register our PhoneStateListener
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,162
,V/SetupWizard( 8185): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 7997:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7997/cgroup.procs: No such file or directory
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8209 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8232 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8034:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_8034/cgroup.procs: No such file or directory
,W/ResourcesManager( 8232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8232): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8232): MmsConfig.loadMmsSettings
I/Babel_SMS( 8232): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8232): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8232): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8232): MmsConfig.loadFromResources
,E/Babel_SMS( 8232): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8232): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8232): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8232): startup - clean
,I/Babel   ( 8232): deleted: false for 0
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8266 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/VideoCapabilities( 8232): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8232): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8232): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8232): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8232): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8232): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8232): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8232): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 8106:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_8106/cgroup.procs: No such file or directory
,I/vclib   ( 8232): onServiceConnected
W/Babel   ( 8232): Attempted to change video mute state without an active call.
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8289 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8308 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8125:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  329): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 22.744ms
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.969ms
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.966ms
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8125/cgroup.procs: No such file or directory
,W/asset   ( 8308): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8308): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8308): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8308): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8232): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 7349): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 8266): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d2bbb19 new=com.google.android.velvet.VelvetApplication@3d2bbb19
,I/PackageBroadcastService( 7349): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8341 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 18488(948KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.934ms total 139.677ms
,W/System  ( 8232): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8232): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8341): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 7349): Storage manager: low false usage 1.76MB avail 3.11GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 8266): UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
,I/ActivityManager(  883): Killing 8209:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_8209/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8376 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8185:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 7349): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_8185/cgroup.procs: No such file or directory
,D/Finsky  ( 8376): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 7349): Internal init done: storage state 0
,I/Icing   ( 7349): Post-init done
,I/Icing   ( 7349): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 7349): Background sticky concurrent mark sweep GC freed 27731(2MB) AllocSpace objects, 27(432KB) LOS objects, 19% free, 11MB/14MB, paused 7.335ms total 55.988ms
,D/Finsky  ( 8376): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8376): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8376): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8376): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8376): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8376): Skipping gmscore version check
,D/Finsky  ( 8376): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8376): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 8289:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8289/cgroup.procs: No such file or directory
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 7349): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 7349): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7349): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 8308:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_8308/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310801, SEQNUM=4524, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-820, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,I/ActivityManager(  883): Killing 8232:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_8232/cgroup.procs: No such file or directory
,I/CheckinService( 7349): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309997, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-871, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  883): send {32853e9e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): send {39315d4c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {32853e9e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
V/AlarmManager(  883): done {39315d4c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,I/CheckinService( 7349): Checkin interval check for package: unspecified last checkin: 1453125316533 min interval config: 0 actual interval: 39826
,I/CheckinService( 7349): Checking schedule, now: 1453125356371 next: 1453125346506
I/CheckinService( 7349): active receiver: enabled
,I/CheckinService( 7349): Preparing to send checkin request
I/EventLogService( 7349): Accumulating logs since 1453125312179
,I/CheckinRequestBuilder( 7349): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7349): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8469 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8469): VM with version 2.1.0 has multidex support
I/MultiDex( 8469): install
I/MultiDex( 8469): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8469): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f19bfd8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8469): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,D/LocationInitializer( 7349): Restart initialization of location
,E/MDM     ( 1715): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1715): No location to return for getLastLocation()
,W/FusedLocationProvider( 1715): location=null
,I/art     ( 8469): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8469): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8469): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  315): Instantiating CDM.
,I/WVCdm   (  315): CdmEngine::OpenSession
I/WVCdm   (  315): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  315): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  315): Service_Initialize: starts!
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  315): App is not loaded in QSEE
,D/QSEECOMAPI: (  315): Loaded image: APP id = 3
,D/DrmWidevineDash(  315): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fae000
E/DrmWidevineDash(  315): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fae000
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  315): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: starts! SID=0xb13c0960
,D/DrmWidevineDash(  315): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: starts! randomData=0xb8500340, dataLength=8
D/DrmWidevineDash(  315): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb84f6568, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  315): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  315): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  315): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  315): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: starts! deviceID=0xb862f750, idLength=0xb5485730
,D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  315): PrepareKeyRequest: nonce=1392648055
D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8548ed8
D/DrmWidevineDash(  315): message_length=1591, signature=0xb85d3478, signature_length=3041416980
,D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  315): CdmEngine::CloseSession
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  315): L3 Terminate.
D/DrmWidevineDash(  315): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  315): Service_Uninitialize: starts!
D/QSEECOMAPI: (  315): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  315): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  315): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8514): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8514): dex2oat took 71.151ms (threads: 4)
,I/Adreno-EGL( 8469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8469): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8469): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8469): Local Branch: 
I/Adreno-EGL( 8469): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8469): Local Patches: NONE
I/Adreno-EGL( 8469): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8469): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8469): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8469): Local Branch: 
I/Adreno-EGL( 8469): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8469): Local Patches: NONE
I/Adreno-EGL( 8469): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  315): CdmEngine::OpenSession
I/WVCdm   (  315): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  315): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  315): Service_Initialize: starts!
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
,E/QSEECOMAPI: (  315): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
E/QSEECOMAPI: (  315): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  315): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  315): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  315): App is not loaded in QSEE
,D/QSEECOMAPI: (  315): Loaded image: APP id = 3
,D/DrmWidevineDash(  315): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fae000
,E/DrmWidevineDash(  315): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fae000
,D/DrmWidevineDash(  315): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  315): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  315): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  315): OEMCrypto_OpenSession: starts! SID=0xb13c0960
,D/DrmWidevineDash(  315): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  315): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  315): OEMCrypto_GetRandom: starts! randomData=0xb85d3238, dataLength=8
,D/DrmWidevineDash(  315): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8549760, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  315): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  315): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  315): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  315): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  315): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: starts! deviceID=0xb862f770, idLength=0xb5585730
,D/DrmWidevineDash(  315): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  315): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  315): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  315): hlos api version =  9
D/DrmWidevineDash(  315): tz api version =  8
D/DrmWidevineDash(  315): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  315): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  315): PrepareKeyRequest: nonce=440819946
D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb84f8648
D/DrmWidevineDash(  315): message_length=1626, signature=0xb84f8ca8, signature_length=3042465556
,D/DrmWidevineDash(  315): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  315): CdmEngine::CloseSession
D/DrmWidevineDash(  315): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  315): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  315): L3 Terminate.
D/DrmWidevineDash(  315): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  315): Service_Uninitialize: starts!
D/QSEECOMAPI: (  315): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  315): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  315): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  315): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8469): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8469): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8469): Local Branch: 
I/Adreno-EGL( 8469): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8469): Local Patches: NONE
I/Adreno-EGL( 8469): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8469): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8469): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8469): Local Branch: 
I/Adreno-EGL( 8469): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8469): Local Patches: NONE
I/Adreno-EGL( 8469): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 7349): Classify the device as Phone.
,I/CheckinTask( 7349): Sending checkin request (9457 bytes)
,I/CheckinRequestBuilder( 7349): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7349): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 7349): Classify the device as Phone.
,I/CheckinTask( 7349): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7349): Checking schedule, now: 1453125359798 next: 1453726496793
I/CheckinService( 7349): active receiver: disabled
,D/CheckinService( 7349): Recording last checkin time for package unspecified as 1453125359807
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8537 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8537): Register our PhoneStateListener
,V/SetupWizard( 8537): Connected to Gservices successfully
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Killing 8145:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  883): Killing 8266:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_8145/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8266/cgroup.procs: No such file or directory
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1715): disconnect managed GoogleApiClient
,I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8574 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@277a370
,I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,I/art     (  883): Explicit concurrent mark sweep GC freed 22345(1155KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.361ms total 115.765ms
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8614 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8632 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8341:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  883): Killing 8376:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8341/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_8376/cgroup.procs: No such file or directory
,W/ResourcesManager( 8632): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8632): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8632): MmsConfig.loadMmsSettings
I/Babel_SMS( 8632): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8632): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8632): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8632): MmsConfig.loadFromResources
,E/Babel_SMS( 8632): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8632): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8632): startup - clean
,I/Babel   ( 8632): deleted: false for 0
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8669 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8632): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8632): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8632): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8632): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8632): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8632): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8632): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8632): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8688 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8537:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8669): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_8537/cgroup.procs: No such file or directory
,W/asset   ( 8688): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8688): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8688): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 7349): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7349): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8574): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/vclib   ( 8632): onServiceConnected
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d2bbb19 new=com.google.android.velvet.VelvetApplication@3d2bbb19
W/Babel   ( 8632): Attempted to change video mute state without an active call.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8719 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8632): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8632): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 7349): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8719): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8632): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 8574): UpdateCorporaTask done [took 176 ms] updated apps [took 175 ms] 
,W/System  ( 8632): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8632): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8748 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.277ms
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.164ms
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.575ms
,I/ActivityManager(  883): Killing 8469:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_8469/cgroup.procs: No such file or directory
,D/Finsky  ( 8748): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8748): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8748): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8748): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8748): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8748): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8748): Skipping gmscore version check
D/Finsky  ( 8748): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8748): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 8614:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8614/cgroup.procs: No such file or directory
,I/Icing   ( 7349): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 7349): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 8688:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_8688/cgroup.procs: No such file or directory
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Killing 8574:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8574/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
,I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1715): onCreate
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1715): onDestroy
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310512, SEQNUM=4560, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-998, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2579): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  313): NetlinkHandler, power_supply subsys
I/MDMCTBK (  313): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  313): checkDefaultInst, current pid is = 313
I/MDMCTBK (  313): checkDefaultInst, pid match
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  313): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  313): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 7083): --= Surplus to requirements =--
I/jxcore-log( 7083): 
I/jxcore-log( 7083): ****TEST TOOK:  ms ****
I/jxcore-log( 7083): 
I/jxcore-log( 7083): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7083): 
,D/AndroidRuntime( 8823): 
D/AndroidRuntime( 8823): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8823): CheckJNI is OFF
,D/AndroidRuntime( 8823): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.test.thalitest appid=10460 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 7083:com.test.thalitest/u0a460 (adj 9): stop com.test.thalitest
,W/PackageSettings(  883): Skipping PackageSetting{1355f9ac com.example.hello/10440} due to missing metadata
,I/WindowState(  883): WIN DEATH: Window{1ef2e597 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{3adb4e8d u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  883): Spurious death for ProcessRecord{38347106 7083:com.test.thalitest/u0a460}, curProc for 7083: null
,I/ActivityManager(  883): Force stopping com.test.thalitest appid=10460 user=0: pkg removed
I/ActivityManager(  883):   Force finishing activity ActivityRecord{3adb4e8d u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{3adb4e8d u0 com.test.thalitest/.MainActivity t6 f}
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1715): Ignoring removeGeofence because network location is disabled.
,I/art     ( 3342): Explicit concurrent mark sweep GC freed 9608(2MB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 7MB/12MB, paused 3.741ms total 67.515ms
,D/VoicemailCleanupService( 8669): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
,I/Decoder ( 1416): createOrResetDecoder
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8853 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1571): Explicit concurrent mark sweep GC freed 5049(311KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 478us total 133.621ms
,I/art     (  883): Explicit concurrent mark sweep GC freed 16241(1071KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.391ms total 167.937ms
I/art     (  883): WaitForGcToComplete blocked for 136.139ms for cause Explicit
,I/ConfigService( 1715): onCreate
,W/asset   ( 8853): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8853): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8853): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8853): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8879 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 3838(205KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.219ms total 184.962ms
,I/ActivityManager(  883): Killing 8632:com.google.android.talk/u0a70 (adj 15): empty #7
,D/AndroidRuntime( 8823): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_8632/cgroup.procs: No such file or directory
,I/Launcher( 1571): Deferring update until onResume
,W/ContextImpl( 8879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 7349): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 7349): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 7349): Reading stored module config
,D/ChimeraCfgMgr( 7349): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 7349): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 7349): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 7349): App measurement is starting up, version: 8489
I/GMPM-SVC( 7349): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1715): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1715): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8915 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 7349): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 7349): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 7349): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 7349): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Icing   ( 7349): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 7349): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 7349): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 7349): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d2bbb19 new=com.google.android.velvet.VelvetApplication@3d2bbb19
,D/gH_CompatibleDatabase( 7349): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 7349): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 7349): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,D/ChimeraCfgMgr( 7349): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7349): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 7349): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8947 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,--------- beginning of crash
E/AndroidRuntime( 7349): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 7349): Process: com.google.android.gms, PID: 7349
E/AndroidRuntime( 7349): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7349): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7349): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 7349): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7349): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7349): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 7349): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 7349): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 7349): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7349): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7349): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7349): Sending signal. PID: 7349 SIG: 9
,D/WifiService(  883): Client connection lost with reason: 4
,E/DropBoxManagerService(  883): Can't write: system_app_crash
E/DropBoxManagerService(  883): java.io.IOException: Can't rename /data/system/dropbox/drop119.tmp to /data/system/dropbox/system_app_crash@1453125439813.txt
E/DropBoxManagerService(  883): 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:504)
E/DropBoxManagerService(  883): 	at com.android.server.DropBoxManagerService.createEntry(DropBoxManagerService.java:685)
E/DropBoxManagerService(  883): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:245)
E/DropBoxManagerService(  883): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  883): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
,E/native  ( 1416): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1416): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  883): Process com.google.android.gms (pid 7349) has died
,W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1080ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11080ms
,W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11080ms
,E/native  ( 1416): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1416): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1416): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1416): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1416): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1416): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
