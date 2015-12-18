#### Test 539786637913587_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2563): no tags to log
D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
I/art     ( 2563): Explicit concurrent mark sweep GC freed 28740(1735KB) AllocSpace objects, 6(119KB) LOS objects, 39% free, 11MB/19MB, paused 5.231ms total 113.233ms
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1478): Explicit concurrent mark sweep GC freed 55147(3MB) AllocSpace objects, 36(1233KB) LOS objects, 39% free, 7MB/12MB, paused 1.016ms total 44.929ms
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 6431): 
D/AndroidRuntime( 6431): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6431): CheckJNI is OFF
I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6431): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     (  882): Explicit concurrent mark sweep GC freed 31685(1557KB) AllocSpace objects, 2(213KB) LOS objects, 33% free, 20MB/30MB, paused 1.734ms total 130.106ms
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6455 uid=10389 gids={50389, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6431): Shutting down VM
I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2563): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2563): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2563): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2563): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2563): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6455): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6455): Time to load native libraries: 2 ms (timestamps 4834-4836)
I/LibraryLoader( 6455): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6455): Binding Chromium to main looper Looper (main, tid 1) {1ef279f2}
,I/LibraryLoader( 6455): Expected native library version number "",actual native library version number ""
I/chromium( 6455): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6455): Initializing chromium process, singleProcess=true
W/art     ( 6455): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6455): ApplicationContext is null in ApplicationStatus
,W/chromium( 6455): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6455): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6455): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6455): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6455): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6455): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6455): Local Branch: 
I/Adreno-EGL( 6455): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6455): Local Patches: NONE
I/Adreno-EGL( 6455): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30a5ad61:true
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{d84e229 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6455): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6455): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6455): CordovaWebView is running on device made by: motorola
,W/art     ( 6455): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6455): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6455): Render dirty regions requested: true
,D/Atlas   ( 6455): Validating map...
,W/chromium( 6455): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6455): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6455): Enabling debug mode 0
,I/Keyboard.Facilitator( 1420): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,922
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +833ms (total +922ms)
,W/IInputConnectionWrapper( 6455): showStatusIcon on inactive InputConnection
,V/AlarmManager(  882): send {3c2aa909, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  882): done {3c2aa909, *walarm*:com.google.android.intent.action.SEND_IDLE} [7ms]
,E/Adreno-ES20( 6455): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6455): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6455): Cannot call determinedVisibility() - never saw a connection for the pid: 6455
,D/JsMessageQueue( 6455): Set native->JS mode to OnlineEventsBridgeMode
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 924 seconds from now (1450442906379)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
,D/jxcore_app_log( 6455): JniHelper::setJavaVM(0xb89e2310), pthread_self() = -1193857664
D/JX-Cordova( 6455): jxcore cordova android initializing
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 6455): Initializing JXcore engine
W/jxcore-log( 6455): JXcore engine is ready
,W/jxcore-log( 6455): Starting JXcore engine
,W/.test.thalitest( 6455): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10389 path="socket:[9822]" dev="sockfs" ino=9822 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6455): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10389 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6455): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10389 path="socket:[8493]" dev="sockfs" ino=8493 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6455): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10389 path="socket:[27848]" dev="sockfs" ino=27848 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6455): Platform android
W/jxcore-log( 6455): 
,W/jxcore-log( 6455): Process ARCH arm
W/jxcore-log( 6455): 
,I/jxcore-log( 6455): JXcore Cordova bridge is ready!
I/jxcore-log( 6455): 
W/jxcore-log( 6455): JXcore engine is started
I/Choreographer( 6455): Skipped 174 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6455): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6455): Toggling radios to true
I/jxcore-log( 6455): 
,D/BluetoothAdapter( 6455): enable(): BT is already enabled..!
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=6455, uid=10389
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6455): Radios toggled
I/jxcore-log( 6455): 
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302):  STA Disconnected !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
,I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
,D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
,D/Tethering(  882): InitialState.processMessage what=4
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 21
D/TCMD    (  453): Listening for incoming client connection request
V/NativeCrypto( 1735): Read error: ssl=0xb8c25890: I/O error during system call, Connection timed out
,V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xb8c25890: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6550 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  882): connected time updated 129804
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  882): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): ConnectModeState: Network connection lost 
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiP2pService(  882): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ResourcesManager( 6550): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6550): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6550): MmsConfig.loadMmsSettings
I/Babel_SMS( 6550): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6550): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6550): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6550): MmsConfig.loadFromResources
E/Babel_SMS( 6550): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6550): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6550): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6550): startup - clean
,I/Babel   ( 6550): deleted: false for 0
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6589 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  302): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 1441): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  302): Event received = Trying to associate with
,D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  882): [1,450,442,910,479 ms] noteScanEnd no scan source
,E/wpa_supplicant( 1441): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@13cdf686 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6589): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6550): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6550): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6550): Unsupported mime video/mpeg2
,I/ActivityManager(  882): Killing 6125:android.process.acore/u0a7 (adj 15): empty #7
,I/VideoCapabilities( 6550): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6550): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6550): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6550): Unrecognized profile 2130706433 for video/avc
,D/TCMD    (  453): NL - Read 312 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 192 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
I/wpa_supplicant( 1441): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  302): Event received = Associated with c0:ff:d4
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,W/VideoCapabilities( 6550): Unrecognized profile 2130706433 for video/avc
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1441): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  302): Event received = WPA: Key negotiation com
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302):  STA Connected !!
,E/MDMCTBK (  302): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  302): get_freq !!, resp=2412
I/MDMCTBK (  302): get_freq !!, Strip data
I/MDMCTBK (  302): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
,I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  302): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  302): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213681608
I/MDMCTBK (  302): return from set_get_from_wpa_supplicant
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
D/MDMCTBK (  302): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/MDMCTBK (  302): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  302): , reply_len: 3, ret: 0
E/MDMCTBK (  302): MdmCutbackHndler, resp=OK
E/MDMCTBK (  302): 
D/MDMCTBK (  302): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6125/cgroup.procs: No such file or directory
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  882): Killing 6319:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/vclib   ( 6550): onServiceConnected
W/Babel   ( 6550): Attempted to change video mute state without an active call.
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6319/cgroup.procs: No such file or directory
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  299): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,W/ProcessCpuTracker(  882): Skipping unknown process pid 6542
W/ProcessCpuTracker(  882): Skipping unknown process pid 6575
W/ProcessCpuTracker(  882): Skipping unknown process pid 6612
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c98a3a2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c98a3a2 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 6628): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6628): version 5.5.6 starting
E/DHCPCD  ( 6628): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6628): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6628): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6628): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6628): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6628): wlan0: sending REQUEST (xid 0x558bb7e7), next in 4.87 seconds
,I/DHCPCD  ( 6628): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6628): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6628): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6628): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6628): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6628): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 20
D/TCMD    (  453): Listening for incoming client connection request
,D/DHCPCD  ( 6628): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  882): Adding iface wlan0 to network 101
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882):    accepting network in place of null
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524295
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6684 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.429ms
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.289ms
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:48:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450442913220], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450442913176]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
,D/OtaApp  ( 2563): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 27.596ms
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioDown
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6455): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): my name is : motorola-XT1072_PT5087
I/jxcore-log( 6455): 
,I/MusicStore( 6684): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/jxcore-log( 6455): attempting to connect to test coordinator
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): check test folder
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): found test : ./testFindPeers.js
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): found test : ./testReConnect.js
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): found test : ./testSendData.js
I/jxcore-log( 6455): 
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6684): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 6455): Test app app.js loaded
I/jxcore-log( 6455): 
,V/JNIHelp ( 6684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
I/Choreographer( 6455): Skipped 229 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6455): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityThread( 6684): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6684): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6684): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6684): GMSCore installation verified
,I/ConfigStore( 6684): Config Database version: 1
,I/MediaRouter( 6684): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6684): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6716 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6684): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6684): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6263:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_6263/cgroup.procs: No such file or directory
,I/art     (  882): Explicit concurrent mark sweep GC freed 53422(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.478ms total 133.673ms
,V/Mms     ( 6716): mnc/mcc: 
,V/Mms     ( 6716): tag: int value: recipientLimit - 20
V/Mms     ( 6716): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6716): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6716): tag: int value: maxSubjectLength - 80
V/Mms     ( 6716): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6716): tag: bool value: enableGroupMms - false
,V/Mms     ( 6716):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6746 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6204:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6746): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_6204/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6746): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6746): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6550:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6550/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450442825327 min interval config: 0 actual interval: 88977
,I/CheckinService( 1956): Checking schedule, now: 1450442914315 next: 1450442855301
I/CheckinService( 1956): active receiver: enabled
,I/CheckinService( 1956): Preparing to send checkin request
I/EventLogService( 1956): Accumulating logs since 1450442820257
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6765 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6783 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6783): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6783): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/MultiDex( 6783): VM with version 2.1.0 has multidex support
I/MultiDex( 6783): install
I/MultiDex( 6783): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6801 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/JNIHelp ( 6783): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityThread( 6783): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6783): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a6cf77: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6783): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6783): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6783): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6801): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6801): MmsConfig.loadMmsSettings
I/Babel_SMS( 6801): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6801): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6801): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6801): MmsConfig.loadFromResources
,E/Babel_SMS( 6801): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6801): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6783): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  304): Instantiating CDM.
,I/WVCdm   (  304): CdmEngine::OpenSession
I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
,W/Settings( 6801): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  304): Service_Initialize: starts!
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,I/Babel_Crash( 6801): startup - clean
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,V/AlarmManager(  882): send {14673bf2, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
I/Babel   ( 6801): deleted: false for 0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xb5446960
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843e250, dataLength=8
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
,W/art     ( 6783): Suspending all threads took: 6.245ms
,W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d38, idLength=0xbeaa12b0
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  304): PrepareKeyRequest: nonce=3014490472
D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1591, signature=0xb8474898, signature_length=3198816916
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6841 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6801): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6801): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  304): CdmEngine::CloseSession
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities( 6801): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6801): onServiceConnected
,W/Babel   ( 6801): Attempted to change video mute state without an active call.
,I/Babel   ( 6801): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6589:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_6589/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6841): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6841):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6841):   adb logcat -s GAv4
,W/GAv4    ( 6841): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6841): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6841): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6869): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6869): dex2oat took 198.483ms (threads: 4)
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): now: 205554 ,futureTime: 9223372036854775807
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): now: 205555 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): now: 205560 ,futureTime: 9223372036854775807
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): now: 205564 ,futureTime: 86473895
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86473895 Current Time: 205564
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2563): [debug] > PollingManagerService, now: 205563 ,futureTime: 80734770
,D/OtaApp  ( 2563): [debug] > Polling alarm set to expire at: 80734770 Current Time: 205566
,I/Adreno-EGL( 6783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6783): Local Branch: 
I/Adreno-EGL( 6783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6783): Local Patches: NONE
I/Adreno-EGL( 6783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 5159(237KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 663us total 34.311ms
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2563): set mOutstandingReq to true.
I/ Nonce  ( 2563):  Nonce getNonce 
I/ Nonce  ( 2563):  Nonce Request 
I/ Nonce  ( 2563):  Nonce execute Request 
D/MMApiWebService( 2563): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/Adreno-EGL( 6783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6783): Local Branch: 
I/Adreno-EGL( 6783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6783): Local Patches: NONE
I/Adreno-EGL( 6783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/WebViewFactory( 6841): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,I/LibraryLoader( 6841): Time to load native libraries: 2 ms (timestamps 5734-5736)
,I/LibraryLoader( 6841): Expected native library version number "",actual native library version number ""
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
V/WebViewChromiumFactoryProvider( 6841): Binding Chromium to main looper Looper (main, tid 1) {32b48467}
D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,I/LibraryLoader( 6841): Expected native library version number "",actual native library version number ""
I/chromium( 6841): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2563): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,I/BrowserStartupController( 6841): Initializing chromium process, singleProcess=true
,W/art     ( 6841): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6841): ApplicationContext is null in ApplicationStatus
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,W/chromium( 6841): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6841): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6841): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6841): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6841): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6841): Local Branch: 
I/Adreno-EGL( 6841): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6841): Local Patches: NONE
I/Adreno-EGL( 6841): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6841): Requires BLUETOOTH permission
,I/art     (  882): Explicit concurrent mark sweep GC freed 12009(586KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.626ms total 117.279ms
,D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/NSApplication( 6841): Starting up...
,D/MMApiWebService( 2563): generating token using payload instead of using session token
,D/ Nonce  ( 2563):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2563): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6919 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6684:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6783): Local Branch: 
I/Adreno-EGL( 6783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6783): Local Patches: NONE
I/Adreno-EGL( 6783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6783): Local Branch: 
I/Adreno-EGL( 6783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6783): Local Patches: NONE
I/Adreno-EGL( 6783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6684/cgroup.procs: No such file or directory
,I/WVCdm   (  304): CdmEngine::OpenSession
I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  304): Service_Initialize: starts!
,D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  304): hlos api version =  9
,D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xb5446960
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843e578, dataLength=8
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d78, idLength=0xb5546730
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  304): PrepareKeyRequest: nonce=3054262232
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1626, signature=0xb8474898, signature_length=3042207508
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6944 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6716:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  304): CdmEngine::CloseSession
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6716/cgroup.procs: No such file or directory
,W/ResourcesManager( 6944): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:33000 mC
,I/CheckinTask( 1956): Sending checkin request (9512 bytes)
,I/ Nonce  ( 2563):  Nonce Reponse 
D/        ( 2563): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"0023fdee-02f8-4945-b305-d619e456e265"}
,D/MMApiWSBase( 2563): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2563):  Nonce Handle Reponse 
D/MMApiProvisionService( 2563): mOutstandingReq set to false
,I/art     ( 2563): Explicit concurrent mark sweep GC freed 17975(1036KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/19MB, paused 1.441ms total 67.630ms
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6969 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MMApiProvisionService( 2563):  pTime 1450280700010 sExp 172742 cTime 1450442917359 tTime 1450453442010
D/MMApiProvisionService( 2563):  No login Required 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6993 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6765:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6969): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 6746:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6765/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6746/cgroup.procs: No such file or directory
,I/MusicStore( 6993): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6993): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6993): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6993): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/DataUsage( 2563): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 6993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6993): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1956): Checking schedule, now: 1450442917784 next: 1451044054773
I/CheckinService( 1956): active receiver: disabled
,D/CheckinService( 1956): Recording last checkin time for package unspecified as 1450442917797
,I/ActivityManager(  882): Killing 6801:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ActivityThread( 6993): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6993): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6993): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6993): GMSCore installation verified
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6801/cgroup.procs: No such file or directory
,I/ConfigStore( 6993): Config Database version: 1
,I/MediaRouter( 6993): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6993): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6993): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Killing 6841:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/ProcessCpuTracker(  882): Skipping unknown process pid 7034
,W/ProcessCpuTracker(  882): Skipping unknown process pid 7037
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_6841/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6993): type=WIFI subType= reason=null isConnected=true,
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7051 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.622ms
,I/GHttpClientFactory( 6993): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 27.484ms
,I/GoogleURLConnFactory( 6993): Using platform SSLCertificateSocketFactory
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.954ms
,I/ActivityManager(  882): Killing 6919:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7051): mnc/mcc: 
,V/Mms     ( 7051): tag: int value: recipientLimit - 20
V/Mms     ( 7051): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7051): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7051): tag: int value: maxSubjectLength - 80
V/Mms     ( 7051): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7051): tag: bool value: enableGroupMms - false
,V/Mms     ( 7051):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_6919/cgroup.procs: No such file or directory
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6455): BLE supported!!
I/jxcore-log( 6455): 
,W/ResourcesManager( 7051): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7086 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6969:android.process.acore/u0a7 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6969/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7086): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7086): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6944:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 8981(453KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.649ms total 119.920ms
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6944/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450442917797 min interval config: 0 actual interval: 857
,I/CheckinService( 1956): Checking schedule, now: 1450442918659 next: 1450442947773
,I/CheckinService( 1956): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7109 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7129 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 6993:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6993/cgroup.procs: No such file or directory
,W/ResourcesManager( 7129): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/Babel_SMS( 7129): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7129): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7129): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7129): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7129): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7129): MmsConfig.loadFromResources
,E/Babel_SMS( 7129): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7129): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7129): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7129): startup - clean
,I/Babel   ( 7129): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7156 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7129): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7129): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7129): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7129): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7129): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7129): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7129): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7129): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7129): onServiceConnected
W/Babel   ( 7129): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7156): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7156):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7156):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7156): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7156): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7156): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7129): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7051:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7051/cgroup.procs: No such file or directory
,I/art     ( 6347): Explicit concurrent mark sweep GC freed 1936(85KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 354us total 24.624ms
,I/WebViewFactory( 7156): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7156): Time to load native libraries: 1 ms (timestamps 9600-9601)
I/LibraryLoader( 7156): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7156): Binding Chromium to main looper Looper (main, tid 1) {32b48467}
,I/LibraryLoader( 7156): Expected native library version number "",actual native library version number ""
,I/chromium( 7156): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7156): Initializing chromium process, singleProcess=true
W/art     ( 7156): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7156): ApplicationContext is null in ApplicationStatus
,W/chromium( 7156): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7156): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7156): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7156): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7156): Local Branch: 
I/Adreno-EGL( 7156): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7156): Local Patches: NONE
I/Adreno-EGL( 7156): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7156): Requires BLUETOOTH permission
,I/NSApplication( 7156): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7230 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7086:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7086/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7249 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7109:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7109/cgroup.procs: No such file or directory
,W/ResourcesManager( 7249): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7272 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7156:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7272): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7129:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7156/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7129/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
,D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7301 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2563): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1735): callingUid 10016, callindPid: 1735
,E/MDM     ( 1735): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1956): Restart initialization of location
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  882): done {14673bf2, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6350ms]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7331 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/MusicStore( 7331): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7331): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7331): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7331): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,V/JNIHelp ( 7331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7331): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7331): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7331): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7331): GMSCore installation verified
,I/ConfigStore( 7331): Config Database version: 1
,I/MediaRouter( 7331): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7331): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7331): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7331): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7371 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7331): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7331): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7230:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7371): mnc/mcc: 
,V/Mms     ( 7371): tag: int value: recipientLimit - 20
V/Mms     ( 7371): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7371): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7371): tag: int value: maxSubjectLength - 80
V/Mms     ( 7371): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7371): tag: bool value: enableGroupMms - false
V/Mms     ( 7371):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7230/cgroup.procs: No such file or directory
,I/art     (  882): Explicit concurrent mark sweep GC freed 12208(590KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.492ms total 115.438ms
,W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7397 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.797ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.508ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.293ms
,I/ActivityManager(  882): Killing 7249:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7397): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7249/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7397): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7397): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7272:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7272/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450442917797 min interval config: 0 actual interval: 4818
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450442917797 min interval config: 0 actual interval: 4821
,I/CheckinService( 1956): Checking schedule, now: 1450442922626 next: 1450442947773
I/CheckinService( 1956): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7417 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1956): Checking schedule, now: 1450442922685 next: 1450442947773
I/CheckinService( 1956): active receiver: disabled
,W/ResourcesManager( 7417): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7417): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7417): MmsConfig.loadMmsSettings
I/Babel_SMS( 7417): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7417): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7417): MmsConfig.loadFromResources
,E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7417): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7417): startup - clean
,I/Babel   ( 7417): deleted: false for 0
,W/art     ( 7417): Suspending all threads took: 5.873ms
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7448 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7417): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7417): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7417): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7417): onServiceConnected
,W/Babel   ( 7417): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7448): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7448):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7448):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7448): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7448): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7448): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7417): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6783:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_6783/cgroup.procs: No such file or directory
,I/WebViewFactory( 7448): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7448): Time to load native libraries: 2 ms (timestamps 3067-3069)
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7448): Binding Chromium to main looper Looper (main, tid 1) {32b48467}
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
,I/chromium( 7448): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7448): Initializing chromium process, singleProcess=true
,W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7448): ApplicationContext is null in ApplicationStatus
,W/chromium( 7448): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7448): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7448): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7448): Local Branch: 
I/Adreno-EGL( 7448): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7448): Local Patches: NONE
I/Adreno-EGL( 7448): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7448): Requires BLUETOOTH permission
,I/NSApplication( 7448): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7519 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7331:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7331/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7538 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7371:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7371/cgroup.procs: No such file or directory
,W/ResourcesManager( 7538): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7558 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7301:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7558): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7397:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7301/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7397/cgroup.procs: No such file or directory
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2563): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2563): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2563): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2563): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7593 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@186d1e41
,I/Keyboard.Facilitator( 1420): onFinishInput()
,W/IInputConnectionWrapper( 6455): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7593): Register our PhoneStateListener
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1568): Deferring update until onResume
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,193
,V/SetupWizard( 7593): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 7417:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7417/cgroup.procs: No such file or directory
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7615 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7641 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7448:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7448/cgroup.procs: No such file or directory
,W/ResourcesManager( 7641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7641): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7641): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7641): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7641): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7641): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7641): MmsConfig.loadFromResources
,E/Babel_SMS( 7641): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7641): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7641): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7641): startup - clean
,I/Babel   ( 7641): deleted: false for 0
,W/art     ( 7641): Suspending all threads took: 16.116ms
,W/VideoCapabilities( 7641): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7641): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7641): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7641): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7641): Unrecognized profile 2130706433 for video/avc
,I/art     (  882): Explicit concurrent mark sweep GC freed 19010(964KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.637ms total 115.606ms
,I/ActivityManager(  882): Killing 7519:com.android.chrome/u0a52 (adj 15): empty #7
,I/vclib   ( 7641): onServiceConnected
W/Babel   ( 7641): Attempted to change video mute state without an active call.
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7519/cgroup.procs: No such file or directory
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7682 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7708 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7538:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7538/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7727 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 22.828ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 18.988ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 4.814ms total 25.151ms
,W/asset   ( 7727): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7727): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7727): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7727): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7641): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7641): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Killing 7615:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7641): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7641): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7641): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7615/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1956): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@560f6ec new=com.google.android.velvet.VelvetApplication@560f6ec
,I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 7682): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7768 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7768): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7682): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7793 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7593:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7593/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:34000 mC
,D/Finsky  ( 7793): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7793): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7793): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7793): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7793): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7793): Skipping gmscore version check
D/Finsky  ( 7793): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  882): Killing 7708:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7708/cgroup.procs: No such file or directory
,D/Finsky  ( 7793): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7793): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  882): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1956): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1956): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 7727:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7727/cgroup.procs: No such file or directory
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ActivityManager(  882): Killing 7641:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7641/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=302, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311339, SEQNUM=4494, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-350, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310263, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-363, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {220735d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  882): send {1cd0dea8, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  882): done {220735d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [24ms]
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  882): done {1cd0dea8, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [54ms]
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450442917797 min interval config: 0 actual interval: 42771
,I/CheckinService( 1956): Checking schedule, now: 1450442960578 next: 1450442947773
I/CheckinService( 1956): active receiver: enabled
,I/CheckinService( 1956): Preparing to send checkin request
I/EventLogService( 1956): Accumulating logs since 1450442914371
,I/CheckinRequestBuilder( 1956): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7869 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7869): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7869): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7869): VM with version 2.1.0 has multidex support
I/MultiDex( 7869): install
I/MultiDex( 7869): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7869): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7869): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7869): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a6cf77: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7869): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1735): callingUid 10016, callindPid: 1735
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1956): Restart initialization of location
,E/MDM     ( 1735): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
,I/art     ( 7869): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7869): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7869): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  304): Instantiating CDM.
,I/WVCdm   (  304): CdmEngine::OpenSession
,I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  304): Service_Initialize: starts!
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
,D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xb5546960
D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843e950, dataLength=8
,D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d58, idLength=0xb5446730
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  304): PrepareKeyRequest: nonce=2548108721
D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1591, signature=0xb8474898, signature_length=3041158932
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  304): CdmEngine::CloseSession
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
,D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7915): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7915): dex2oat took 66.974ms (threads: 4)
,I/Adreno-EGL( 7869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7869): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7869): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7869): Local Branch: 
I/Adreno-EGL( 7869): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7869): Local Patches: NONE
I/Adreno-EGL( 7869): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7869): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7869): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7869): Local Branch: 
I/Adreno-EGL( 7869): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7869): Local Patches: NONE
I/Adreno-EGL( 7869): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7869): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7869): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7869): Local Branch: 
I/Adreno-EGL( 7869): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7869): Local Patches: NONE
I/Adreno-EGL( 7869): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7869): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7869): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7869): Local Branch: 
I/Adreno-EGL( 7869): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7869): Local Patches: NONE
I/Adreno-EGL( 7869): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  304): CdmEngine::OpenSession
I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  304): Service_Initialize: starts!
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xbeaa14e0
D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843eb40, dataLength=8
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d78, idLength=0xb135c730
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  304): PrepareKeyRequest: nonce=371083305
D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1626, signature=0xb8474898, signature_length=2973091604
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  304): CdmEngine::CloseSession
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Sending checkin request (9518 bytes)
,I/CheckinRequestBuilder( 1956): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 14991(749KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.509ms total 118.862ms
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1956): Checking schedule, now: 1450442963764 next: 1451044100754
I/CheckinService( 1956): active receiver: disabled
,D/CheckinService( 1956): Recording last checkin time for package unspecified as 1450442963786
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7938 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7938): Register our PhoneStateListener
,V/SetupWizard( 7938): Connected to Gservices successfully
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ActivityManager(  882): Killing 7558:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  882): Killing 7682:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7558/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7682/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7960 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1568): Deferring update until onResume
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 95932(5MB) AllocSpace objects, 27(455KB) LOS objects, 40% free, 15MB/25MB, paused 1.082ms total 108.021ms
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b65852d
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7997 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8004 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7768:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7768/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 7793:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_7793/cgroup.procs: No such file or directory
,W/ResourcesManager( 8004): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8004): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8004): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8004): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8004): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8004): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8004): MmsConfig.loadFromResources
E/Babel_SMS( 8004): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8004): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8004): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8004): startup - clean
,I/Babel   ( 8004): deleted: false for 0
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8048 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8004): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8004): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8004): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8004): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8004): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8004): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8004): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8004): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8073 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7938:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8048): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7938/cgroup.procs: No such file or directory
,I/vclib   ( 8004): onServiceConnected
,W/Babel   ( 8004): Attempted to change video mute state without an active call.
,W/asset   ( 8073): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8073): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8073): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8073): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1956): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7960): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@560f6ec new=com.google.android.velvet.VelvetApplication@560f6ec
,I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8101 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8004): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7960): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8129 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 239us total 23.069ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.186ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.180ms
,I/ActivityManager(  882): Killing 7869:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_7869/cgroup.procs: No such file or directory
,D/Finsky  ( 8129): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8129): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8129): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8129): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8129): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8129): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8129): Skipping gmscore version check
,D/Finsky  ( 8129): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8129): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 7997:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311275, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-377, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7997/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/Icing   ( 1956): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1956): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 8073:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_8073/cgroup.procs: No such file or directory
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ActivityManager(  882): Killing 8004:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8004/cgroup.procs: No such file or directory
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1735): onCreate
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ConfigService( 1735): onDestroy
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310994, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5450, POWER_SUPPLY_CHARGE_COUNTER=-430, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311844, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-440, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {256a0b79, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {256a0b79, *walarm*:android.content.syncmanager.SYNC_ALARM} [14ms]
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect called
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Coordinator is now connected to the server!
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311511, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-482, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311493, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-520, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6455): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): DBG, CoordinatorConnector command called
I/jxcore-log( 6455): 
I/jxcore-log( 6455): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":16,"addressList":[{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Start now : testSendData.js
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 16
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): check server
I/jxcore-log( 6455): 
I/jxcore-log( 6455): serverPort is 55603
I/jxcore-log( 6455): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT5087
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6455): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6455): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6455): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): start: OK
I/io.jxcore.node.ConnectionHelper( 6455): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT5087
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6455): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6455): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6455): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ddbd4650 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ddbd4650 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState add service
D/WifiP2pService(  882): add a new client
,I/art     (  882): Explicit concurrent mark sweep GC freed 22015(1253KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.426ms total 119.613ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): start: OK
D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6455): start: OK
I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6455): StartBroadcasting started ok
I/jxcore-log( 6455): 
D/WifiP2pService(  882): discovery change broadcast true
,I/jxcore-log( 6455): do fake peer & start
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:33.101Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:33.102Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:33.102Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [58:3F:54:73:64:C0 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 6455): 2015-12-18T12:53:33.113Z SendDataTCPServer.js: TCP/IP server is bound to port: 55603
I/jxcore-log( 6455): 
I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 780)
I/io.jxcore.node.ConnectionHelper( 6455): onConnectionManagerStateChanged: RUNNING
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6455): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6455): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1441): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 1441): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 6455): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service request added successfully
,I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 92
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service discovery started successfully
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9205","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9205","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9205","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/io.jxcore.node.ConnectionHelper( 6455): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] is available
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 7e
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2438): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 2438): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e237922:true
,I/BluetoothBondStateMachine( 2438): Entering PendingCommandState State
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8216 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2438): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ef279f2
,D/BluetoothMetrics( 2438): btclass5a020c
,W/ResourcesManager( 8216): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin ( 2438): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2438): StableState(): Entering Off State
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22cb3970:true
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8253 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7960:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:1
W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onSocketConnected: [58:3F:54:73:64:C0 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 780)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): onBytesWritten: 81 bytes successfully written (thread ID: 781)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Outgoing connection initialized (*handshake* thread ID: 781)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 780)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 781)
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7960/cgroup.procs: No such file or directory
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 0a
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): onBytesRead: Read 77 bytes successfully (thread ID: 781)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 781)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] is available
,I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6455): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6455): Entering thread (ID: 782)
,D/io.jxcore.node.OutgoingSocketThread( 6455): Server socket local port: 51704
,I/io.jxcore.node.OutgoingSocketThread( 6455): Now accepting connections...
,W/ResourcesManager( 8253): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a92040f:true
,I/ActivityManager(  882): Killing 8048:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8048/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 6455): onListeningForIncomingConnections: Outgoing connection is using port 51704 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log( 6455): 2015-12-18T12:53:39.689Z SendDataConnector.js: CLIENT connected to 51704, error: null
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:39.689Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6455): 
,I/io.jxcore.node.OutgoingSocketThread( 6455): Incoming data from address: /127.0.0.1, port: 51704
,D/io.jxcore.node.OutgoingSocketThread( 6455): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6455): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6455): Exiting thread (ID: 782)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 783, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 784, name: Receiver)
,I/jxcore-log( 6455): 2015-12-18T12:53:39.708Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6455): 
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6455): 2015-12-18T12:53:40.529Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:40.586Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6455): 
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6455): 2015-12-18T12:53:40.733Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:40.875Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6455): 
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6455): 2015-12-18T12:53:41.016Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.134Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.762Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.784Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.785Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.796Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:41.797Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6455): 
D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 6455): close
D/io.jxcore.node.OutgoingSocketThread( 6455): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 784
D/io.jxcore.node.OutgoingSocketThread( 6455): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 783
D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 783, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6455): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 784, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 783, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 784, name: Receiver)
,I/jxcore-log( 6455): 2015-12-18T12:53:41.820Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 6455): 
I/jxcore-log( 6455): ---- round done--------
I/jxcore-log( 6455): 
I/jxcore-log( 6455): do fake peer & start
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:41.822Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:41.822Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:41.822Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 785)
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2438): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5d89c rs_disc_pending=1
W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5da5c rs_disc_pending=1
W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2438): process_service_search_attr_rsp
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8293 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2438): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2438): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
D/BluetoothAdapterProperties( 2438): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,D/BluetoothMetrics( 2438): btclass5a020c
,I/BluetoothBondStateMachine( 2438): StableState(): Entering Off State
,D/Checkin ( 2438): publish the event [tag = MOT_BT event name = PAIRING]
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@474d22b:true
,I/BTConnectionReceiver( 8293): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8334 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:1
W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onSocketConnected: [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 785)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): onBytesWritten: 81 bytes successfully written (thread ID: 786)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Outgoing connection initialized (*handshake* thread ID: 786)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 785)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 786)
,I/BluetoothClassifier( 8293): Bluetooth Device Name: G3-1
,I/ActivityManager(  882): Killing 8101:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8101/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): onBytesRead: Read 82 bytes successfully (thread ID: 786)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Handshake succeeded with [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onHandshakeSucceeded: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 786)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Outgoing connection to peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] is available
I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Outgoing socket thread, for peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6455): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6455): Entering thread (ID: 787)
,D/io.jxcore.node.OutgoingSocketThread( 6455): Server socket local port: 44480
I/io.jxcore.node.OutgoingSocketThread( 6455): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6455): onListeningForIncomingConnections: Outgoing connection is using port 44480 (peer ID: F8:CF:C5:D9:E5:61)
,I/jxcore-log( 6455): 2015-12-18T12:53:48.578Z SendDataConnector.js: CLIENT connected to 44480, error: null
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:48.579Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6455): 
,I/io.jxcore.node.OutgoingSocketThread( 6455): Incoming data from address: /127.0.0.1, port: 44480
,D/io.jxcore.node.OutgoingSocketThread( 6455): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6455): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 6455): Exiting thread (ID: 787)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 789, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 788, name: Sender)
,I/jxcore-log( 6455): 2015-12-18T12:53:48.607Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6455): 
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5da5c rs_disc_pending=0
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29080
,I/jxcore-log( 6455): 2015-12-18T12:53:49.389Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6455): 
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19038
,I/jxcore-log( 6455): 2015-12-18T12:53:49.724Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:49.860Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6455): 
,D/        ( 2438): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9138
,I/jxcore-log( 6455): 2015-12-18T12:53:50.197Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:50.332Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:50.764Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:51.089Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:51.614Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6455): 
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6455): 2015-12-18T12:53:51.839Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:52.255Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:52.255Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:52.263Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:52.264Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6455): 
,D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
I/io.jxcore.node.OutgoingSocketThread( 6455): close
D/io.jxcore.node.OutgoingSocketThread( 6455): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 789
D/io.jxcore.node.OutgoingSocketThread( 6455): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 788
,D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 788, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Outgoing connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6455): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 6455): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 789, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Outgoing connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:CF:C5:D9:E5:61
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 788, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 789, name: Receiver)
,I/jxcore-log( 6455): 2015-12-18T12:53:52.291Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): ---- round done--------
I/jxcore-log( 6455): 
I/jxcore-log( 6455): do fake peer & start
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:53:52.292Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:52.292Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:53:52.292Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 790)
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5da5c rs_disc_pending=1
W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2438): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ea
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 ea
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 8293): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8293): Bluetooth Device Name: Nexus 6
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{2faec6a5 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139268 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1441): P2P-FIND-STOPPED 
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  302): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1441): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1441): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ea
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 ea
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionTimeout: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/jxcore-log( 6455): 2015-12-18T12:54:07.300Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:07.300Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:07.301Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6455): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1441): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 1441): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6455): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service request added successfully
,I/jxcore-log( 6455): 2015-12-18T12:54:12.302Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:12.303Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/wpa_supplicant( 1441): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1441): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  302): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service discovery started successfully
,I/wpa_supplicant( 1441): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-34
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 ee
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6455): 2015-12-18T12:54:17.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:17.307Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:17.307Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:17.307Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 792)
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ea
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 ea
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 a2
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 790)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 790)
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2438): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2438): Entering PendingCommandState State
,I/ActivityManager(  882): Killing 8129:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_8129/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2438): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2438): StableState(): Entering Off State
,D/BluetoothMetrics( 2438): btclass5a020c
,D/Checkin ( 2438): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection initialized (thread ID: 793)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 793)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): onBytesRead: Read 82 bytes successfully (thread ID: 793)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): onBytesWritten: 81 bytes successfully written (thread ID: 793)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): removeThreadFromList: Removing thread with ID 793
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Handshake thread disposed (thread ID: 793)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 793)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] is available
I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], created successfully
D/io.jxcore.node.ConnectionHelper( 6455): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6455): Entering thread (ID: 794)
,I/io.jxcore.node.IncomingSocketThread( 6455): Local host address: localhost/127.0.0.1, port: 55603
,D/io.jxcore.node.IncomingSocketThread( 6455): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6455): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6455): Exiting thread (ID: 794)
I/jxcore-log( 6455): 2015-12-18T12:54:30.595Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6455): 
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 796, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 795, name: Sender)
,I/jxcore-log( 6455): 2015-12-18T12:54:31.666Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.671Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.676Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.740Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.810Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.815Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.825Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.893Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:31.968Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.169Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6455): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionTimeout: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/jxcore-log( 6455): 2015-12-18T12:54:32.318Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:32.318Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:32.319Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.403Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.452Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.639Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.644Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.664Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.674Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.771Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.807Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.814Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.846Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.851Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.921Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.986Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:32.991Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.001Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.081Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.091Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.126Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.133Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.166Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.198Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.205Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.236Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.276Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.286Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:54:33.290Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6455): 
,W/bt-btif ( 2438): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 796, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6455): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 794
,D/io.jxcore.node.IncomingSocketThread( 6455): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 796
D/io.jxcore.node.IncomingSocketThread( 6455): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 795
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6455): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 796, name: Receiver)
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x47
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 795, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 795, name: Sender)
,I/jxcore-log( 6455): 2015-12-18T12:54:33.402Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6455): 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2412 92
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 8293): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8293): Bluetooth Device Name: S5-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): 2015-12-18T12:54:37.319Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:37.319Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
I/io.jxcore.node.ConnectionHelper( 6455): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205]
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6455): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] removed
D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9205] not available
,D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6455): 2015-12-18T12:54:42.322Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:42.322Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:42.322Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:42.322Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 798)
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1441): P2P-FIND-STOPPED 
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  302): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1441): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1441): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1441): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302):  STA Disconnected !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  882): InitialState.processMessage what=4
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,E/WifiStateMachine(  882): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
E/WifiStateMachine(  882): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/TCMD    (  453): NL - Read 60 bytes from update socket.
,D/TCMD    (  453): NL - ignore NL message, type = 21
D/TCMD    (  453): Listening for incoming client connection request
,V/NativeCrypto( 1735): Read error: ssl=0xb8c29798: I/O error during system call, Connection timed out
,V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xb8c29798: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-26ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-26ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,I/jxcore-log( 6455): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6455): 
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8449 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 6455): The Coordinator has disconnected!
I/jxcore-log( 6455): 
,D/WifiMetrics(  882): connected time updated 502408
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
,W/ResourcesManager( 8449): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524292
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 8449): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8449): MmsConfig.loadMmsSettings
I/Babel_SMS( 8449): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8449): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8449): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8449): MmsConfig.loadFromResources
,E/Babel_SMS( 8449): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8449): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8449): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8449): startup - clean
,I/Babel   ( 8449): deleted: false for 0
,W/VideoCapabilities( 8449): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8449): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8449): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8449): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8449): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8449): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8449): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8449): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8449): onServiceConnected
,W/Babel   ( 8449): Attempted to change video mute state without an active call.
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,D/WifiService(  882): setWifiEnabled: false pid=6455, uid=10389
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiScanningService(  882): SCAN_AVAILABLE : 1
D/RttService(  882): SCAN_AVAILABLE : 1
,D/RttService(  882): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  882): DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): [1,450,443,286,968 ms] noteScanEnd no scan source
,D/WifiP2pService(  882): InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pDisablingState
D/WifiP2pService(  882): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): p2p socket connection lost
D/WifiP2pService(  882): P2pDisabledState
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1441): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  299): Clearing all IP addresses on wlan0
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiService(  882): setWifiEnabled: true pid=6455, uid=10389
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): stopping supplicant
,E/WifiStateMachine(  882): setWifiState: disabling
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiController(  882): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 397ms
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 6455): Wifi toggled for connection repairment
I/jxcore-log( 6455): 
,I/wpa_supplicant( 1441): eap_proxy Deinitialzed
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): stop: Stopping services
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: NOT_INITIALIZED
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6455): Failed to clear local services, got error code: 2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Failed to shutdown P2P device discovery, got error code: 2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Failed to clear service requests, got error code: 2
I/io.jxcore.node.ConnectionHelper( 6455): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
I/wpa_supplicant( 1441): wlan0: CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  302): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  302):  Wpa Supplicant Exiting !!
D/MDMCTBK (  302): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  302): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  302): wifi_close_sockets: Exit
,E/WifiStateMachine(  882): Supplicant connection lost
,D/Checkin ( 3019): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/QC-QMI  (  385): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,E/WifiStateMachine(  882): setWifiState: disabled
,W/Settings( 8449): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  882): DEFERRED_TOGGLE handled
,E/WifiStateMachine(  882): setting operational mode to 1
,D/Checkin ( 3019): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  453): NL - Read 444 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 17
D/TCMD    (  453): Listening for incoming client connection request
,D/Checkin ( 3019): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 444 bytes from update socket.
,D/TCMD    (  453): NL - ignore NL message, type = 17
D/TCMD    (  453): Listening for incoming client connection request
,D/Checkin ( 3019): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/TCMD    (  453): NL - Read 1008 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 1008 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/QsoftapCmd(  299): Got softap fwreload command we are passing on
,D/SoftapController(  299): Softap fwReload - Ok
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8548 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  882): InitialState.processMessage what=4
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2563): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioDown
,I/wpa_supplicant( 8554): Successfully initialized wpa_supplicant
I/wpa_supplicant( 8554): Long line in configuration file truncated
,I/wpa_supplicant( 8554): rfkill: Cannot open RFKILL control device
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,E/WifiStateMachine(  882): setWifiState: enabling
E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MusicStore( 8548): Database version: 120
,I/libmdmdetect( 8554): ESOC framework not supported
E/Diag_Lib( 8554):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8554): baseband property is set to [msm]
I/libmdmdetect( 8554): ESOC framework not supported
,E/wpa_supplicant( 8554):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8554): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8554): card_info[i].card_state: 0x0
E/wpa_supplicant( 8554): card_info[i].error_code: 0x0
E/wpa_supplicant( 8554): SIM/USIM not ready
E/wpa_supplicant( 8554): Error while reading SIM card status
,E/wpa_supplicant( 8554): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8554): card_info[i].card_state: 0x0
E/wpa_supplicant( 8554): card_info[i].error_code: 0x0
E/wpa_supplicant( 8554): SIM/USIM not ready
I/wpa_supplicant( 8554): eap_proxy: Card not ready
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8548): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8548): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8548): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8548): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8548): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8548): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/wpa_supplicant( 8554): Long line in configuration file truncated
,I/wpa_supplicant( 8554): rfkill: Cannot open RFKILL control device
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,E/wpa_supplicant( 8554): baseband property is set to [msm]
,I/libmdmdetect( 8554): ESOC framework not supported
,W/ActivityThread( 8548): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8548): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8548): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8548): GMSCore installation verified
E/wpa_supplicant( 8554):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8554): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8554): card_info[i].card_state: 0x0
E/wpa_supplicant( 8554): card_info[i].error_code: 0x0
E/wpa_supplicant( 8554): SIM/USIM not ready
E/wpa_supplicant( 8554): Error while reading SIM card status
,E/wpa_supplicant( 8554): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8554): card_info[i].card_state: 0x0
E/wpa_supplicant( 8554): card_info[i].error_code: 0x0
E/wpa_supplicant( 8554): SIM/USIM not ready
I/wpa_supplicant( 8554): eap_proxy: Card not ready
,E/WifiStateMachine(  882): setSuspendOptimizations: 2 true
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  882): Supplicant connection established
E/WifiStateMachine(  882): setWifiState: enabled
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ConfigStore( 8548): Config Database version: 1
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  882): Loading config and enabling all networks 
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  882): Setting external_sim to 1
W/Settings( 8449): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2e1489c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb89e2310, mCls = 0x1012be
I/WifiNative-HAL(  882): Could not start hal
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 8554): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  882): do suspend true
,D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiScanningService(  882): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa1a549cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb89e2310, mCls = 0x2012ae
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
,D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  299): Setting iface cfg
,D/CommandListener(  299): Trying to bring up p2p0
D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
E/WifiStateMachine(  882): set country code US
D/WifiNative-HAL(  882): p2pGetDeviceAddress
D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT5087
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6455): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5087","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): MCC mode enabled 0
,E/WifiStateMachine(  882): set frequency band 2
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setState: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6455): onDiscoveryManagerStateChanged: RUNNING
I/wpa_supplicant( 8554): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
D/WifiP2pService(  882): InactiveState
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): InactiveState{ when=-17ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-18ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ddbd4650 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139292 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ddbd4650 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
D/WifiP2pService(  882): add a new client
,D/WifiP2pService(  882): InactiveState{ when=-3ms what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6455): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: STARTED
D/WifiP2pService(  882): InactiveState{ when=-4ms what=139268 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 8554): P2P-FIND-STOPPED 
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: RESTARTING
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,I/MediaRouter( 8548): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8548): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8585 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8548): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8548): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 8334:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8334/cgroup.procs: No such file or directory
,V/Mms     ( 8585): mnc/mcc: 
,V/Mms     ( 8585): tag: int value: recipientLimit - 20
,V/Mms     ( 8585): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8585): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8585): tag: int value: maxSubjectLength - 80
V/Mms     ( 8585): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8585): tag: bool value: enableGroupMms - false
V/Mms     ( 8585):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8585): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8616 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  882): Explicit concurrent mark sweep GC freed 46580(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.636ms total 134.393ms
,I/ActivityManager(  882): Killing 8253:com.android.settings/1000 (adj 15): empty #7
,D/PhoneMonitor( 8616): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_8253/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8616): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8616): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1956): num queued entries: 0
,I/iu.UploadsManager( 1956): num updated entries: 0
I/ActivityManager(  882): Killing 8293:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
I/iu.SyncManager( 1956): NEXT; no task
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8293/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8635 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8656 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 8449): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  882): Killing 8548:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_8548/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8656): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8656):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8656):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,W/GAv4    ( 8656): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8656): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8656): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8656): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8656): Time to load native libraries: 1 ms (timestamps 9899-9900)
,I/LibraryLoader( 8656): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8656): Binding Chromium to main looper Looper (main, tid 1) {37b9c781}
I/LibraryLoader( 8656): Expected native library version number "",actual native library version number ""
I/chromium( 8656): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8656): Initializing chromium process, singleProcess=true
,W/art     ( 8656): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8656): ApplicationContext is null in ApplicationStatus
,W/chromium( 8656): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8656): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8656): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8656): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8656): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8656): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8656): Local Branch: 
I/Adreno-EGL( 8656): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8656): Local Patches: NONE
I/Adreno-EGL( 8656): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8656): Requires BLUETOOTH permission
,I/NSApplication( 8656): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8713 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8585:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 25.218ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.075ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.702ms
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_8585/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8732 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8616:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8616/cgroup.procs: No such file or directory
,W/ResourcesManager( 8732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8752 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8775 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 8449:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 8752): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 8635:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8449/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8635/cgroup.procs: No such file or directory
,I/MusicStore( 8775): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8775): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8775): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8775): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{175f5ba3 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,W/ActivityThread( 8775): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8775): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8775): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8775): GMSCore installation verified
,I/ConfigStore( 8775): Config Database version: 1
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {14673bf2, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/MediaRouter( 8775): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8775): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [33ms]
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8803 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8775): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8775): Using platform SSLCertificateSocketFactory
,V/Mms     ( 8803): mnc/mcc: 
,V/Mms     ( 8803): tag: int value: recipientLimit - 20
V/Mms     ( 8803): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8803): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8803): tag: int value: maxSubjectLength - 80
V/Mms     ( 8803): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 8803): tag: bool value: enableGroupMms - false
,V/Mms     ( 8803):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/ActivityManager(  882): Killing 8656:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_8656/cgroup.procs: No such file or directory
,W/ResourcesManager( 8803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8839 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8713:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_8713/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8839): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8839): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8839): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 8732:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8732/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8857 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8880 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 8752:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8752/cgroup.procs: No such file or directory
,W/ResourcesManager( 8880): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8880): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8880): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8880): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8880): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8880): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8880): MmsConfig.loadFromResources
,E/Babel_SMS( 8880): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8880): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8880): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8880): startup - clean
,I/Babel   ( 8880): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8911 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8880): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8880): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8880): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8880): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8880): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8880): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8880): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8880): Unrecognized profile 2130706433 for video/avc
,I/art     (  882): Explicit concurrent mark sweep GC freed 13372(697KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.540ms total 112.678ms
,I/vclib   ( 8880): onServiceConnected
I/Babel   ( 8880): connection state changed from UNKNOWN to DISCONNECTED
W/Babel   ( 8880): Attempted to change video mute state without an active call.
,I/ActivityManager(  882): Killing 8775:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_8775/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8911): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8911): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8911): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8911):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8911):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8911): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8911): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8911): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8911): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8911): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/WebViewFactory( 8911): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310375, SEQNUM=4630, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=-10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/LibraryLoader( 8911): Time to load native libraries: 1 ms (timestamps 3262-3263)
,I/LibraryLoader( 8911): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8911): Binding Chromium to main looper Looper (main, tid 1) {37b9c781}
,I/LibraryLoader( 8911): Expected native library version number "",actual native library version number ""
I/chromium( 8911): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/BrowserStartupController( 8911): Initializing chromium process, singleProcess=true
W/art     ( 8911): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8911): ApplicationContext is null in ApplicationStatus
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,E/WifiStateMachine(  882): [1,450,443,293,855 ms] noteScanEnd no scan source
,W/chromium( 8911): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8911): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8911): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8911): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8911): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8911): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8911): Local Branch: 
I/Adreno-EGL( 8911): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8911): Local Patches: NONE
I/Adreno-EGL( 8911): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8911): Requires BLUETOOTH permission
,I/NSApplication( 8911): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8982 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8803:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_8803/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9001 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8839:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8839/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 8554): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/ResourcesManager( 9001): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9021 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.930ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.392ms
,I/ActivityManager(  882): Killing 8880:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.449ms
,I/ContactLocale( 9021): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 8857:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8880/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8857/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
,D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9059 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): done {14673bf2, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [3308ms]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9085 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8911:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_8911/cgroup.procs: No such file or directory
,W/ResourcesManager( 9085): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/Babel_SMS( 9085): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9085): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9085): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9085): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9085): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9085): MmsConfig.loadFromResources
,E/Babel_SMS( 9085): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9085): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9085): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9085): startup - clean
,I/Babel   ( 9085): deleted: false for 0
,I/wpa_supplicant( 8554): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
I/wpa_supplicant( 8554): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 6455): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service request added successfully
,W/VideoCapabilities( 9085): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9085): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9085): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9085): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9085): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9085): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9085): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9085): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 1956:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@232da2e7)
D/WifiService(  882): Client connection lost with reason: 4
,D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_1956/cgroup.procs: No such file or directory
,I/vclib   ( 9085): onServiceConnected
W/Babel   ( 9085): Attempted to change video mute state without an active call.
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service discovery started successfully
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 6455): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] is available
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionTimeout: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/jxcore-log( 6455): 2015-12-18T12:54:57.331Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:57.331Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] timed out
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:54:57.331Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6455): 
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4523","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4523","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4523","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/io.jxcore.node.ConnectionHelper( 6455): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6455): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] is available
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
,E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 792)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Maximum number of allowed retries (0) reached, giving up... (thread ID: 792)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 792)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 792)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
,I/jxcore-log( 6455): 2015-12-18T12:55:02.342Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:02.343Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=9136 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14b4f932:true
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9175 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothClassifier( 9136): Bluetooth Device Name: G3-1
,I/ActivityManager(  882): Killing 8982:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  882): Killing 9001:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_8982/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9001/cgroup.procs: No such file or directory
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 8554): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-89
,I/wpa_supplicant( 8554): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-34
D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  882):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  882):  primary type: 3-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 128
D/WifiP2pService(  882):  grpcapab: 9
D/WifiP2pService(  882):  devcapab: 4
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -89 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  882):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  882):  primary type: 3-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 128
D/WifiP2pService(  882):  grpcapab: 9
D/WifiP2pService(  882):  devcapab: 4
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -89 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
,I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6455): 2015-12-18T12:55:07.359Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:07.359Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:07.360Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:07.360Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6455): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
,E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 798)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 798)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Maximum number of allowed retries (0) reached, giving up... (thread ID: 798)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 798)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/jxcore-log( 6455): 2015-12-18T12:55:07.691Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:07.691Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:07.691Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6455): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant( 8554): p2p0: CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {256a0b79, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {256a0b79, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,I/wpa_supplicant( 8554): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [62ms]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6455): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Service request added successfully
,--------- beginning of crash
F/libc    ( 8554): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 8554 (wpa_supplicant)
,I/libc    ( 8554): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,E/QC-QMI  (  385): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 22
,E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 23
E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 24
E/QC-QMI  (  385): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 25
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6455): Failed to start the service discovery, got error code: 3
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
,I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/jxcore-log( 6455): 2015-12-18T12:55:12.706Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:12.706Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 11
,W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection initialized (thread ID: 802)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 802)
,W/bt-btif ( 2438): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): removeThreadFromList: Removing thread with ID 802
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Handshake failed (thread ID: 802)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 802)
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x4c
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
,I/jxcore-log( 6455): 2015-12-18T12:55:17.717Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:17.718Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:17.718Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:17.718Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 803)
,W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection initialized (thread ID: 804)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 804)
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Maximum number of allowed retries (0) reached, giving up... (thread ID: 800)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 800)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/jxcore-log( 6455): 2015-12-18T12:55:18.031Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] failed
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:18.031Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] failed
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:18.040Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6455): 
D/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6455): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6455): 2015-12-18T12:55:18.041Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6455): 
I/jxcore-log( 6455): ---- round done--------
I/jxcore-log( 6455): 
I/jxcore-log( 6455): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 6455): 
I/jxcore-log( 6455): do fake peer & start
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:18.043Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:18.043Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6455): 
I/jxcore-log( 6455): 2015-12-18T12:55:18.043Z SendDataConnector.js: do connect now
I/jxcore-log( 6455): 
I/io.jxcore.node.ConnectionHelper( 6455): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 6455): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): connect: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6455): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 806)
W/BluetoothAdapter( 6455): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2438): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2438): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): removeThreadFromList: Removing thread with ID 804
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Handshake failed (thread ID: 804)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 804)
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2438): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 2438): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2438): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 803)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Maximum number of allowed retries (0) reached, giving up... (thread ID: 803)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 803)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 803)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2438): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2438): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2438): Entering PendingCommandState State
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=9215 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9021:android.process.acore/u0a7 (adj 15): empty #7
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2438): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2438): StableState(): Entering Off State
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9021/cgroup.procs: No such file or directory
,D/BluetoothMetrics( 2438): btclass5a020c
,D/Checkin ( 2438): publish the event [tag = MOT_BT event name = PAIRING]
,W/ResourcesManager( 9215): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bae7c8a:true
,I/ActivityManager(  882): Killing 9059:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9059/cgroup.procs: No such file or directory
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [58:3f:54:73:64:c0]: 7, f, 230f
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 9136): Bluetooth Device Name: G3-1
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5df9c rs_disc_pending=1
W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:1
W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onSocketConnected: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 806)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): shutdown (thread ID: 806)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): onBytesWritten: 81 bytes successfully written (thread ID: 808)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Outgoing connection initialized (*handshake* thread ID: 808)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6455): Exiting thread (thread ID: 806)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 808)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 808)
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5df9c rs_disc_pending=1
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection initialized (thread ID: 809)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 809)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): onBytesRead: Read 77 bytes successfully (thread ID: 809)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): onBytesWritten: 81 bytes successfully written (thread ID: 809)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): removeThreadFromList: Removing thread with ID 809
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Handshake thread disposed (thread ID: 809)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6455): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 809)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6455): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/io.jxcore.node.ConnectionHelper( 6455): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 6455): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6455): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], created successfully
,D/io.jxcore.node.ConnectionHelper( 6455): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6455): Entering thread (ID: 810)
,I/jxcore-log( 6455): 2015-12-18T12:55:26.253Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6455): 
,I/io.jxcore.node.IncomingSocketThread( 6455): Local host address: localhost/127.0.0.1, port: 55603
D/io.jxcore.node.IncomingSocketThread( 6455): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6455): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6455): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6455): Exiting thread (ID: 810)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 811, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6455): Entering thread (ID: 812, name: Receiver)
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5df9c rs_disc_pending=0
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2438): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 6455): 2015-12-18T12:55:27.267Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.275Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.280Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.294Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.300Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.306Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.313Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6455): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6455): 2015-12-18T12:55:27.347Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.354Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.431Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.438Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.447Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.454Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.486Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.493Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.526Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.566Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.571Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.606Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.646Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.657Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.764Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.796Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.861Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.868Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.906Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.921Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.956Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): 2015-12-18T12:55:27.961Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6455): 
,W/bt-btif ( 2438): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 812, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6455): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 810
D/io.jxcore.node.IncomingSocketThread( 6455): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 812
D/io.jxcore.node.IncomingSocketThread( 6455): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6455): doStop: Thread ID: 811
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6455): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6455): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 812, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6455): Either failed to read from the output stream or write to the input stream (thread ID: 811, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6455): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6455): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6455): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6455): Exiting thread (ID: 811, name: Sender)
,I/jxcore-log( 6455): 2015-12-18T12:55:28.052Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6455): 
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5df9c rs_disc_pending=1
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5d89c rs_disc_pending=0
W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
,I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2438): info:x10
D/        ( 2438): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5d89c rs_disc_pending=1
,W/bt-btif ( 2438): bta_dm_check_av:0
W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5d89c rs_disc_pending=0
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: G3-1
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2438): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
I/BluetoothBondStateMachine( 2438): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2438): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2438): Removing bonded device:7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2438): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2438): StableState(): Entering Off State
,D/BluetoothMetrics( 2438): btclass5a020c
,D/Checkin ( 2438): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 2438): tBTM_SEC_DEV:0xa6f5d35c rs_disc_pending=0
,W/bt-btif ( 2438): bta_dm_check_av:0
,W/bt-btif ( 2438): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6455): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6455): 
I/jxcore-log( 6455): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6455): 
,I/chromium( 6455): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection initialized (thread ID: 813)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Entering thread (ID: 813)
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2438): invalid rfc slot id: 17
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): removeThreadFromList: Removing thread with ID 813
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Handshake failed (thread ID: 813)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6455): Exiting thread (ID: 813)
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x45
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,E/WifiStateMachine(  882): Connection lost, restart supplicant
,E/WifiStateMachine(  882): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,W/Settings( 9085): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
,D/WifiScanningService(  882): SCAN_AVAILABLE : 1
,D/WifiScanningService(  882): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  882): SCAN_AVAILABLE : 1
,D/RttService(  882): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): [1,450,443,338,134 ms] noteScanEnd no scan source
,D/WifiP2pService(  882): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): P2pDisablingState
,D/WifiP2pService(  882): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): p2p socket connection lost
,D/WifiP2pService(  882): P2pDisabledState
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): Failed to shutdown P2P device discovery, got error code: 0
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): stop: Stopping services
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139298 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139298 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139268 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139268 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6455): setState: NOT_INITIALIZED
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6455): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6455): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 6455): Shutting down VM
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 444 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 17
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 444 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 17
D/TCMD    (  453): Listening for incoming client connection request
,I/MDMCTBK (  302): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  302): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open '',
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: A5-1
,I/art     (  882): Explicit concurrent mark sweep GC freed 21707(1105KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.420ms total 127.255ms
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: A5-1
,W/bt-btif ( 2438): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2438): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2438): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6455): Incoming connection accepted
,W/bt-btif ( 2438): invalid rfc slot id: 18
,W/google-breakpad( 9339): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad( 9339): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad( 9339): S 0 A1BCBFF0 A1BCB000 00008000
,W/bt-rfcomm( 2438): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2438): RFCOMM_DisconnectInd LCID:0x49
,W/google-breakpad( 9339): S A1BCB000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB780 000000000000000000000000,0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000002812C0B8000000007B2400001812C0B82812C0B8000000000010000000C0A6B40000000000000000371900002812C0B81812C0B8C0B8BCA17003000000000000C0B8BCA1E43DF7B61812C0B880BCBCA100BDBCA1A8A47FA99B882EA90B0000000000000002000000F09FBCA1000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCB900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000D20000000000000000000000000000000C0B7A400000000002000000E00000017000000041200006871406FE0A5E76F901A2323E0EC3423C40000006871406FE0A5E76FE0EC342338A6E76F00FAFDBA901A232370B8CCA1F09FBCA1F0BFBCA16D2AB2713C2AB27130000FA0F09FBCA10412000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000000D20000000000000D0FFFFFF00001582983A0000000000000A510600000010820000000000000000
W/google-breakpad( 9339): S A1BCBA80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E403422231016222310BA2323000000000000000000B53C6F000000000074242338CD9F73100000006C0000003719000000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCBC00 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000D1A332E4000000000B00000080BCBCA100BDBCA10000000053892EA9089B11A10000000004000040B017F2B86871406FC40000006871406FE0A5E76FE0EC342338A6E76F00FAFDBAD845F8B60B0000000000000002000000F09FBCA100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0B7A400000000002000000E00000017000000041200006871406FE0A5E76F901A2323E0EC3423C40000006871406FE0A5E76FE0EC342338A6E76F00FAFDBA901A232370B8CCA1F09FBCA1F0BFBCA16D2AB2713C2AB27130000FA0F09FBCA1041200000000000000000000000000000000000000000000
W/google-breakpad( 9339): S A1BCBD80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000000D20000000000000D0FFFFFF00001582983A0000000000000A51060000001082000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E403422231016222310BA2323000000000000000000B53C6F000000000074242338CD9F73100000006C0000003719000000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC0
W/google-breakpad( 9339): S A1BCBF00 3465F2C000000000000000000000000000000000000000000000000000000000000000000000000000000,0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCC080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCC200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCC380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCC500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCC680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCC800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCC980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCCB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCCC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCCE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCCF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCD880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCDA00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCDB80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCDD00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCDE80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCE900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCEA80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCEC00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCED80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCEF00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
,W/google-breakpad( 9339): S A1BCF680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCF980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCFB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCFC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCFE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BCFF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD0E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD1F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2680 6871406F0000000000000000,0000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB271
W/google-breakpad( 9339): S A1BD2F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FE0EC342338A6E76F901A23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FE0EC3423E0A5E76F901A2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad( 9339): C 060000406871406FE0A5E76F901A2323E0EC3423C40000006871406FE0A5E76FE0EC342338A6E76F00FAFDBA901A232370B8CCA1F09FBCA1F0BFBCA16D2AB2713C2AB27130000FA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9339): M B6F95000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad( 9339): M A0DB3000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad( 9339): M A44F1000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad( 9339): M A44FB000 00000000 00009000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad( 9339): M A5AAD000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad( 9339): M A6BC1000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad( 9339): M A7BA0000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad( 9339): M ADFA0000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad( 9339): M ADFA3000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
W/google-breakpad( 9339): M ADFB3000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
W/google-breakpad( 9339): M AE0EE000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad( 9339): M AE122000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad( 9339): M AE14A000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad( 9339): M AE711000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad( 9339): M AE729000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad( 9339): M AE732000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad( 9339): M AE738000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad( 9339): M AE73C000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
W/google-breakpad( 9339): M AE74A000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
W/google-breakpad( 9339): M AE765000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
W/google-breakpad( 9339): M AE769000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
W/google-breakpad( 9339): M AE788000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad( 9339): M AE78B000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
W/google-breakpad( 9339): M AE792000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
W/google-breakpad( 9339): M AE797000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
W/google-breakpad( 9339): M AE7D3000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
,W/google-breakpad( 9339): M AE7EE000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
,W/google-breakpad( 9339): M AE915000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
,W/google-breakpad( 9339): M AE92C000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad( 9339): M AE958000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad( 9339): M B0DBA000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
W/google-breakpad( 9339): M B0DC4000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad( 9339): M B0DC9000 00000000 00005000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
,W/google-breakpad( 9339): M B24C0000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad( 9339): M B2535000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad( 9339): M B2556000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
,W/google-breakpad( 9339): M B2559000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
,W/google-breakpad( 9339): M B2561000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
,W/google-breakpad( 9339): M B4424000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
W/google-breakpad( 9339): M B4E5C000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad( 9339): M B4E66000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
W/google-breakpad( 9339): M B5198000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad( 9339): M B519C000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
W/google-breakpad( 9339): M B51DD000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
,W/google-breakpad( 9339): M B52DC000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
,W/google-breakpad( 9339): M B52EB000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
W/google-breakpad( 9339): M B52FA000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,W/google-breakpad( 9339): M B52FE000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
,W/google-breakpad( 9339): M B575E000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
W/google-breakpad( 9339): M B5762000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad( 9339): M B5769000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
,W/google-breakpad( 9339): M B576D000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
W/google-breakpad( 9339): M B5779000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
,W/google-breakpad( 9339): M B577C000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad( 9339): M B5791000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad( 9339): M B57E7000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad( 9339): M B57F6000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad( 9339): M B5800000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad( 9339): M B589B000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad( 9339): M B58D8000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
,W/google-breakpad( 9339): M B58F3000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad( 9339): M B5900000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad( 9339): M B5933000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
,W/google-breakpad( 9339): M B5B69000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
W/google-breakpad( 9339): M B5B86000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad( 9339): M B5BAE000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
,W/google-breakpad( 9339): M B5C08000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
W/google-breakpad( 9339): M B5C45000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad( 9339): M B5C88000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
W/google-breakpad( 9339): M B5D1E000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
W/google-breakpad( 9339): M B665D000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad( 9339): M B6697000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
W/google-breakpad( 9339): M B66E3000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
,W/google-breakpad( 9339): M B67F7000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/google-breakpad( 9339): M B67FD000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
,W/google-breakpad( 9339): M B6964000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad( 9339): M B69AC000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
W/google-breakpad( 9339): M B69B1000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
,W/google-breakpad( 9339): M B69B8000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad( 9339): M B69C0000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
,W/google-breakpad( 9339): M B69D7000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
W/google-breakpad( 9339): M B6B38000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
,W/google-breakpad( 9339): M B6B3B000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
W/google-breakpad( 9339): M B6B47000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
,W/google-breakpad( 9339): M B6B4A000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
,W/google-breakpad( 9339): M B6B99000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad( 9339): M B6BA1000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
,W/google-breakpad( 9339): M B6BDB000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
,W/google-breakpad( 9339): M B6BE1000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad( 9339): M B6BE7000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
,W/google-breakpad( 9339): M B6C01000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
,W/google-breakpad( 9339): M B6C31000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
W/google-breakpad( 9339): M B6C59000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
,W/google-breakpad( 9339): M B6C64000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
,W/google-breakpad( 9339): M B6C6B000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
W/google-breakpad( 9339): M B6C6F000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
,W/google-breakpad( 9339): M B6C73000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad( 9339): M B6CC7000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
W/google-breakpad( 9339): M B6CD0000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad( 9339): M B6CD9000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad( 9339): M B6CF1000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
W/google-breakpad( 9339): M B6D2C000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad( 9339): M B6D3A000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad( 9339): M B6DAB000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad( 9339): M B6E16000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
,W/google-breakpad( 9339): M B6EF3000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
W/google-breakpad( 9339): M B6EF7000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
W/google-breakpad( 9339): M B6F11000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
W/google-breakpad( 9339): M B6F19000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
W/google-breakpad( 9339): M B6F7D000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad( 9339): M B6F85000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
W/google-breakpad( 9339): -----END BREAKPAD MICRODUMP-----
,W/google-breakpad( 6455): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 6455): Chrome build fingerprint:
W/google-breakpad( 6455): 0.0.1
W/google-breakpad( 6455): 18
W/google-breakpad( 6455): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6455): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 6455): ### WebView Version 44.0.2403.90 (code 240309000)
,F/libc    ( 6455): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa1bc9ff0 in tid 8205 (Thread-779)
,I/DEBUG   (  301): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   (  301): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
,I/DEBUG   (  301): Revision: 'p300'
I/DEBUG   (  301): ABI: 'arm'
I/DEBUG   (  301): pid: 6455, tid: 8205, name: Thread-779  >>> com.test.thalitest <<<
,I/DEBUG   (  301): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa1bc9ff0
,I/DEBUG   (  301):     r0 6f407168  r1 6fe7a5e0  r2 23231a90  r3 2334ece0
,I/DEBUG   (  301):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 2334ece0
I/DEBUG   (  301):     r8 6fe7a638  r9 bafdfa00  sl 23231a90  fp a1ccb870
I/DEBUG   (  301):     ip a1bc9ff0  sp a1bcbff0  lr 71b22a6d  pc 71b22a3c  cpsr a00f0030
,I/DEBUG   (  301): 
I/DEBUG   (  301): backtrace:
,I/DEBUG   (  301):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   (  301):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,D/WifiP2pService(  882): P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  882): InitialState.processMessage what=4
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
,D/Tethering(  882):  upstream interface types: 
,D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  453): NL - Read 1008 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 1008 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/QsoftapCmd(  299): Got softap fwreload command we are passing on
D/SoftapController(  299): Softap fwReload - Ok
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  882): setWifiState: enabling
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Supplicant start successful
,D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 9356): Successfully initialized wpa_supplicant
I/wpa_supplicant( 9356): Long line in configuration file truncated
I/wpa_supplicant( 9356): rfkill: Cannot open RFKILL control device
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/MDMCTBK (  302): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  302): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): wifi_connect_to_supplicant, current pid is = 302
D/MDMCTBK (  302): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  302): wifi_close_sockets: Exit
E/MDMCTBK (  302): Attach monitor thread
,I/libmdmdetect( 9356): ESOC framework not supported
,E/Diag_Lib( 9356):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 9356): baseband property is set to [msm]
I/libmdmdetect( 9356): ESOC framework not supported
,E/wpa_supplicant( 9356):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9356): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9356): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9356): card_info[i].error_code: 0x0
E/wpa_supplicant( 9356): SIM/USIM not ready
E/wpa_supplicant( 9356): Error while reading SIM card status
,E/wpa_supplicant( 9356): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9356): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9356): card_info[i].error_code: 0x0
E/wpa_supplicant( 9356): SIM/USIM not ready
I/wpa_supplicant( 9356): eap_proxy: Card not ready
,I/DEBUG   (  301): 
I/DEBUG   (  301): Tombstone written to: /data/tombstones/tombstone_02
,I/BootReceiver(  882): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  882): WIN DEATH: Window{3c26a7a4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  882): Client connection lost with reason: 4
,I/wpa_supplicant( 9356): Long line in configuration file truncated
,I/wpa_supplicant( 9356): rfkill: Cannot open RFKILL control device
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,E/wpa_supplicant( 9356): baseband property is set to [msm]
,I/libmdmdetect( 9356): ESOC framework not supported
,I/Zygote  (  320): Process 6455 exited due to signal (11)
,E/wpa_supplicant( 9356):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9356): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9356): card_info[i].card_state: 0x0
E/wpa_supplicant( 9356): card_info[i].error_code: 0x0
E/wpa_supplicant( 9356): SIM/USIM not ready
E/wpa_supplicant( 9356): Error while reading SIM card status
,E/wpa_supplicant( 9356): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9356): card_info[i].card_state: 0x0
E/wpa_supplicant( 9356): card_info[i].error_code: 0x0
E/wpa_supplicant( 9356): SIM/USIM not ready
I/wpa_supplicant( 9356): eap_proxy: Card not ready
,E/WifiStateMachine(  882): Supplicant connection established
E/WifiStateMachine(  882): setWifiState: enabled
,I/MDMCTBK (  302): createWifiMonitorThread: Started the wifi monitor thread -1213698272
D/MDMCTBK (  302): wifi_wait_on_socket: Enter monitor thread
,I/ActivityManager(  882): Process com.test.thalitest (pid 6455) has died
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/wpa_supplicant( 9356): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 9356): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/WifiConfigStore(  882): Loading config and enabling all networks 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-AVOID-FREQ ra
D/MDMCTBK (  302): Event received = CTRL-EVENT-AVOID-FREQ ra
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 9085): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  882): Setting external_sim to 1
D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2e1489c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb89e2310, mCls = 0x1aba
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 9356): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
E/native  (  882): do suspend true
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
,D/WifiScanningService(  882): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa1a549cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb89e2310, mCls = 0x1aae
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  299): Setting iface cfg
,D/CommandListener(  299): Trying to bring up p2p0
,D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/WifiNative-HAL(  882): p2pGetDeviceAddress
,D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  882): MCC mode enabled 0
,D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
D/WifiP2pService(  882): InactiveState
E/WifiStateMachine(  882): set country code US
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): set frequency band 2
D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 9356): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 9356): wlan0: Failed to initiate AP scan
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Reject scan trigger sinc
D/MDMCTBK (  302): Event received = Reject scan trigger sinc
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  302): Event received = Failed to initiate AP sc
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
,E/WifiStateMachine(  882): setDetailed state send new extra info0x
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 9356): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 9356): wlan0: Failed to initiate AP scan
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Reject scan trigger sinc
D/MDMCTBK (  302): Event received = Reject scan trigger sinc
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  302): Event received = Failed to initiate AP sc
,D/WifiP2pService(  882): InactiveState{ when=-3ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{18ac2f18 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/ConnectivityService(  882): Failed to find a new network - expiring NetTransition Wakelock
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2438): onReceive
,I/BTConnectionReceiver( 9136): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9136): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 9356): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 9356): wlan0: Failed to initiate AP scan
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Reject scan trigger sinc
D/MDMCTBK (  302): Event received = Reject scan trigger sinc
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  302): Event received = Failed to initiate AP sc
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  302): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  882): [1,450,443,346,195 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@13cdf686 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,I/wpa_supplicant( 9356): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  302): Event received = Trying to associate with
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 9356): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,E/wpa_supplicant( 9356): PNO: In assoc process
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  453): NL - Read 312 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 192 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 9356): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  302): Event received = Associated with c0:ff:d4
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 9356): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  302): Event received = WPA: Key negotiation com
I/wpa_supplicant( 9356): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  302): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  302):  STA Connected !!
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/MDMCTBK (  302): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  302): get_freq !!, resp=2412
I/MDMCTBK (  302): get_freq !!, Strip data
I/MDMCTBK (  302): get_freq !!, band = 2, freq = 2412
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
,I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
,I/MDMCTBK (  302): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
,I/MDMCTBK (  302): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
,I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213681816
I/MDMCTBK (  302): return from set_get_from_wpa_supplicant
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  302): set_property_value, Enter
,I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 9356): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  302): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  302): , reply_len: 3, ret: 0
,E/MDMCTBK (  302): MdmCutbackHndler, resp=OK
E/MDMCTBK (  302): 
D/MDMCTBK (  302): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
,E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  299): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 3
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
E/wpa_supplicant( 9356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 9356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@354d37c1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@354d37c1 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 9433): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9433): version 5.5.6 starting
E/DHCPCD  ( 9433): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 9433): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9433): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 9433): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 9433): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 9433): wlan0: sending REQUEST (xid 0xd75e8e11), next in 4.82 seconds
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 3
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 1 38
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  302): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService(  882): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): [1,450,443,353,141 ms] noteScanEnd no scan source
D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request,
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ObtainingIpState@dffd5e5 sup_state=COMPLETED debouncing=false
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311059, SEQNUM=4738, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/DHCPCD  ( 9433): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9433): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9433): wlan0: adding IP address 192.168.1.123/24
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 20
D/TCMD    (  453): Listening for incoming client connection request
D/DHCPCD  ( 9433): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 9433): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9433): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 9433): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  882): Adding iface wlan0 to network 102
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  882): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:55:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450443354420], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450443354367]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): now: 646750 ,futureTime: 9223372036854775807
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): now: 646751 ,futureTime: 9223372036854775807
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): now: 646751 ,futureTime: 9223372036854775807
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9505 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/OtaApp  ( 2563): [debug] > PollingManagerService, now: 646812 ,futureTime: 80734770
D/OtaApp  ( 2563): [debug] > Polling alarm set to expire at: 80734770 Current Time: 646812
,D/Central_PollingManager( 1478): now: 646815 ,futureTime: 86473895
,D/Central_PollingManager( 1478): Polling alarm set to expire at: 86473895 Current Time: 646815
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2563): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 6700(345KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 554us total 37.508ms
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2563): set mOutstandingReq to true.
,I/ Nonce  ( 2563):  Nonce getNonce 
I/ Nonce  ( 2563):  Nonce Request 
I/ Nonce  ( 2563):  Nonce execute Request 
,D/MMApiWebService( 2563): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2563): generating token using payload instead of using session token
,I/MusicStore( 9505): Database version: 120
,D/ Nonce  ( 2563):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2563): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9505): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9505): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9505): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9505): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9505): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9505): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9505): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9505): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7242ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9505): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9505): GMSCore installation verified
,I/ConfigStore( 9505): Config Database version: 1
,I/MediaRouter( 9505): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9505): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9505): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9505): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9556 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9505): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9505): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9574 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/Mms     ( 9556): mnc/mcc: 
,V/Mms     ( 9556): tag: int value: recipientLimit - 20
,V/Mms     ( 9556): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9556): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9556): tag: int value: maxSubjectLength - 80
V/Mms     ( 9556): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9556): tag: bool value: enableGroupMms - false
V/Mms     ( 9556):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 9574): VM with version 2.1.0 has multidex support
I/MultiDex( 9574): install
I/MultiDex( 9574): VM has multidex support, MultiDex support library is disabled.
,W/ResourcesManager( 9556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9608 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9085:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_9085/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9608): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9608): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9608): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 9175:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 44813(2MB) AllocSpace objects, 9(3MB) LOS objects, 33% free, 20MB/30MB, paused 1.575ms total 130.909ms
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_9175/cgroup.procs: No such file or directory
,V/JNIHelp ( 9574): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9574): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9574): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30572475: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9574): Installed default security provider GmsCore_OpenSSL
,D/NativeLibraryUtils( 9574): Install completed successfully. count=14 extracted=0
,I/CheckinService( 9574): Checkin interval check for package: unspecified last checkin: 1450442963786 min interval config: 0 actual interval: 395011
,I/CheckinService( 9574): Disabling old GoogleServicesFramework version
,I/CheckinService( 9574): Checking schedule, now: 1450443358825 next: 1450442993754
I/CheckinService( 9574): active receiver: enabled
,I/CheckinService( 9574): Preparing to send checkin request
,I/EventLogService( 9574): Accumulating logs since 1450442960599
,I/iu.SyncManager( 9574): SYNC; picasa accounts
,D/NetworkLogImpl( 9574): Loaded NetworkSpeedPredictor
,I/iu.Environment( 9574): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 9574): num queued entries: 0
,I/iu.UploadsManager( 9574): num updated entries: 0
I/iu.SyncManager( 9574): NEXT; no task
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9654 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 9574): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9574): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9675 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9215:com.android.settings/1000 (adj 15): empty #7
,I/CheckinRequestBuilder( 9574): Checkin reason type: 8 attempt count: 1
,I/art     (  320): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 23.299ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.374ms
,D/WifiService(  882): New client listening to asynchronous messages
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.091ms
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_9215/cgroup.procs: No such file or directory
,E/ActivityThread( 9574): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 9675): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9706 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9706): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9706): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 9675): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9675): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9675): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9675): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9675): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9675): MmsConfig.loadFromResources
E/Babel_SMS( 9675): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9675): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 9706): VM with version 2.1.0 has multidex support
I/MultiDex( 9706): install
,I/MultiDex( 9706): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 9706): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 9675): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9675): startup - clean
,I/Babel   ( 9675): deleted: false for 0
,W/ActivityThread( 9706): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9706): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a6cf77: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9706): Installed default security provider GmsCore_OpenSSL
,I/art     ( 9706): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9706): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9741 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 9706): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 9675): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 9675): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9675): Unsupported mime video/mpeg2
,D/WVCdm   (  304): Instantiating CDM.
,I/WVCdm   (  304): CdmEngine::OpenSession
I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  304): Service_Initialize: starts!
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,I/VideoCapabilities( 9675): Unsupported profile 4 for video/mp4v-es
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,W/VideoCapabilities( 9675): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9675): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xb5546960
D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843efd8, dataLength=8
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d38, idLength=0xb5446730
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  304): PrepareKeyRequest: nonce=3566580941
D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1591, signature=0xb8474898, signature_length=3041158932
W/VideoCapabilities( 9675): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9675): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 9741): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9741):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9741):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 9675): onServiceConnected
W/Babel   ( 9675): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9741): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9741): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9741): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 9675): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 9136:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  304): CdmEngine::CloseSession
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_9136/cgroup.procs: No such file or directory
,I/WebViewFactory( 9741): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9741): Time to load native libraries: 2 ms (timestamps 44-46)
,I/LibraryLoader( 9741): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9741): Binding Chromium to main looper Looper (main, tid 1) {32b48467}
,I/LibraryLoader( 9741): Expected native library version number "",actual native library version number ""
I/chromium( 9741): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9741): Initializing chromium process, singleProcess=true
W/art     ( 9741): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9741): ApplicationContext is null in ApplicationStatus
,W/chromium( 9741): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9741): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9741): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9741): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9741): Local Branch: 
I/Adreno-EGL( 9741): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9741): Local Patches: NONE
I/Adreno-EGL( 9741): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 9798): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 9741): Requires BLUETOOTH permission
,I/NSApplication( 9741): Starting up...
,I/dex2oat ( 9798): dex2oat took 75.305ms (threads: 4)
,I/Adreno-EGL( 9706): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9706): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9706): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9706): Local Branch: 
I/Adreno-EGL( 9706): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9706): Local Patches: NONE
I/Adreno-EGL( 9706): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9816 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9505:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 9706): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9706): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9706): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9706): Local Branch: 
I/Adreno-EGL( 9706): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9706): Local Patches: NONE
I/Adreno-EGL( 9706): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_9505/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9836 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9556:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 9706): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9706): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9706): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9706): Local Branch: 
I/Adreno-EGL( 9706): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9706): Local Patches: NONE
I/Adreno-EGL( 9706): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_9556/cgroup.procs: No such file or directory
,W/ResourcesManager( 9836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 9706): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9706): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9706): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9706): Local Branch: 
I/Adreno-EGL( 9706): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9706): Local Patches: NONE
I/Adreno-EGL( 9706): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  304): CdmEngine::OpenSession
I/WVCdm   (  304): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  304): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  304): Service_Initialize: starts!
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
E/QSEECOMAPI: (  304): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  304): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  304): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  304): App is not loaded in QSEE
,D/QSEECOMAPI: (  304): Loaded image: APP id = 3
,D/DrmWidevineDash(  304): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
E/DrmWidevineDash(  304): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6b000
,D/DrmWidevineDash(  304): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  304): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  304): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  304): OEMCrypto_OpenSession: starts! SID=0xb5446960
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  304): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: starts! randomData=0xb843f300, dataLength=8
D/DrmWidevineDash(  304): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb850c0a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  304): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  304): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  304): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  304): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  304): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: starts! deviceID=0xb8546d78, idLength=0xb135c730
,D/DrmWidevineDash(  304): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  304): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  304): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  304): hlos api version =  9
D/DrmWidevineDash(  304): tz api version =  8
D/DrmWidevineDash(  304): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  304): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  304): PrepareKeyRequest: nonce=3986947843
D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8410b38
D/DrmWidevineDash(  304): message_length=1626, signature=0xb8474898, signature_length=2973091604
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9858 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9654:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/DrmWidevineDash(  304): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  304): CdmEngine::CloseSession
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  304): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  304): L3 Terminate.
D/DrmWidevineDash(  304): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  304): Service_Uninitialize: starts!
D/QSEECOMAPI: (  304): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  304): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  304): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  304): OEMCrypto_Terminate: ends! returns 0
I/ContactLocale( 9858): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/CheckinRequestBuilder( 9574): Classify the device as Phone.
,I/ActivityManager(  882): Killing 9608:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9654/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9608/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
,D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2563): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2563): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2563): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2563): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1735): callingUid 10016, callindPid: 1735
,E/MDM     ( 1735): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 9574): Restart initialization of location
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9896 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
,I/ Nonce  ( 2563):  Nonce Reponse 
D/        ( 2563): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"9982a636-92a6-450d-bf9c-c9fde3a54f80"}
D/MMApiWSBase( 2563): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2563):  Nonce Handle Reponse 
D/MMApiProvisionService( 2563): mOutstandingReq set to false
,I/CheckinTask( 9574): Sending checkin request (9517 bytes)
,I/art     (  882): Explicit concurrent mark sweep GC freed 15335(758KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.645ms total 116.666ms
,I/art     ( 6347): Explicit concurrent mark sweep GC freed 2440(94KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 735us total 32.386ms
,D/MMApiProvisionService( 2563):  pTime 1450280700010 sExp 172742 cTime 1450443362066 tTime 1450453442010
D/MMApiProvisionService( 2563):  No login Required 
,W/IcingInternalCorpora( 9574): getNumBytesRead when not calculated.
,E/MDM     ( 1735): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 9574): Restart initialization of location
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/ActivityManager(  882): Killing 9741:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_9741/cgroup.procs: No such file or directory
,W/DataUsage( 2563): invalid counter update blocked: 'err' by 0
D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinRequestBuilder( 9574): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9574): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 9574): Classify the device as Phone.
,I/CheckinTask( 9574): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9574): Checking schedule, now: 1450443362958 next: 1451044499951
I/CheckinService( 9574): active receiver: disabled
,D/CheckinService( 9574): Recording last checkin time for package unspecified as 1450443362968
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9943 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9943): Register our PhoneStateListener
,V/SetupWizard( 9943): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 9816:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9816/cgroup.procs: No such file or directory
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Killing 9836:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9836/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 9858:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9858/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9967 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1ff88345
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1568): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10000 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10019 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9896:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9896/cgroup.procs: No such file or directory
,W/ResourcesManager( 9675): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9675): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9675): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 9675): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9675): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10041 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9943:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.538ms
,I/ContactLocale(10019): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 18.960ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.311ms
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9943/cgroup.procs: No such file or directory
,W/asset   (10041): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10041): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10041): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10041): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 9574): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/UpdateIcingCorporaServi( 9967): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@560f6ec new=com.google.android.velvet.VelvetApplication@560f6ec
,I/UpdateIcingCorporaServi( 9967): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,I/art     (  882): Explicit concurrent mark sweep GC freed 14830(771KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.598ms total 114.534ms
,I/PackageBroadcastService( 9574): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10068 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(10068): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 9574): Storage manager: low false usage 1.77MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10105 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9706:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/Icing   ( 9574): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_9706/cgroup.procs: No such file or directory
,D/Finsky  (10105): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 9574): Internal init done: storage state 0
,I/Icing   ( 9574): Post-init done
,I/Icing   ( 9574): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10105): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10105): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10105): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10105): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10105): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     (10105): Skipping gmscore version check
,D/Finsky  (10105): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10105): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 10000:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_10000/cgroup.procs: No such file or directory
,I/Icing   ( 9574): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9574): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 9574): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 10041:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_10041/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 9675:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_9675/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/CheckinService( 9574): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
,E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311003, SEQNUM=4772, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=32, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {19b61d9a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {19b61d9a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [17ms]
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [45ms]
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311135, SEQNUM=4776, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=82, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2ee714d, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  882): cleanup(): cleared. Last call was 230686 ms ago
I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=10167 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [86ms]
,I/GAv4    (10167): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (10167):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10167):   adb logcat -s GAv4
,W/GAv4    (10167): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10167): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10167): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  882): done {2ee714d, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [309ms]
,I/ActivityManager(  882): Killing 9967:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_9967/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310835, SEQNUM=4780, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311403, SEQNUM=4782, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311381, SEQNUM=4783, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-170, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310788, SEQNUM=4784, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-189, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2438): info:x10
,D/        ( 2438): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2438): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2438): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310770, SEQNUM=4785, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2725, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311343, SEQNUM=4787, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-13, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311057, SEQNUM=4789, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-16, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {19b61d9a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {19b61d9a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [16ms]
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {1499e402, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [39ms]
,V/AlarmManager(  882): done {1499e402, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [87ms]
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {48ae113, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  882): done {48ae113, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [20ms]
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {257ea9c0, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  882): send {2dc6579e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {103dd549, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  882): send {c63e4e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  882): Prepared write state in 15ms
,V/AlarmManager(  882): done {257ea9c0, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [57ms]
,I/ProcessStatsService(  882): Prepared write state in 6ms
,V/AlarmManager(  882): done {2dc6579e, *alarm*:android.intent.action.TIME_TICK} [81ms]
,V/AlarmManager(  882): done {103dd549, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [110ms]
,V/AlarmManager(  882): done {c63e4e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [128ms]
,I/EventLogService( 9574): Aggregate from 1450443359194 (log), 1450442768594 (data)
,I/ProcessStatsService(  882): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-45-16.bin
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310178, SEQNUM=4798, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-296, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2438): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(10239): 
D/AndroidRuntime(10239): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10239): CheckJNI is OFF
D/AndroidRuntime(10239): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  882):   Force finishing activity ActivityRecord{d84e229 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  882): Skipping PackageSetting{3487c45b com.example.hello/10377} due to missing metadata
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/art     ( 3019): Explicit concurrent mark sweep GC freed 19279(3MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 7MB/12MB, paused 991us total 35.814ms
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
D/VoicemailCleanupService(10019): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
I/Decoder ( 1420): createOrResetDecoder
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10271 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1568): Explicit concurrent mark sweep GC freed 5357(325KB) AllocSpace objects, 7(353KB) LOS objects, 24% free, 13MB/17MB, paused 5.149ms total 146.533ms
I/art     (  882): Explicit concurrent mark sweep GC freed 24198(1669KB) AllocSpace objects, 11(261KB) LOS objects, 33% free, 20MB/30MB, paused 1.699ms total 142.851ms
I/art     (  882): WaitForGcToComplete blocked for 20.131ms for cause Explicit
I/ConfigService( 1735): onCreate
W/asset   (10271): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10271): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10271): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10294 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  882): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
I/ActivityManager(  882): Killing 10068:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
I/art     (  882): Explicit concurrent mark sweep GC freed 5300(307KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.142ms total 193.218ms
W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_10068/cgroup.procs: No such file or directory
D/AndroidRuntime(10239): Shutting down VM
W/ContextImpl(10294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 9574): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 9574): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 9574): Reading stored module config
D/ChimeraCfgMgr( 9574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9574): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 9574): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 9574): App measurement is starting up, version: 8489
I/GMPM-SVC( 9574): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Launcher( 1568): Deferring update until onResume
E/NetworkScheduler.SchedulerReceiver( 1735): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1735): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 9574): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 9574): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 9574): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 9574): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=10325 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 9574): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 9574): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 9574): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@560f6ec new=com.google.android.velvet.VelvetApplication@560f6ec
I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10347 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 9574): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 9574): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 9574): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 9574): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
E/AndroidRuntime( 9574): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 9574): Process: com.google.android.gms, PID: 9574
E/AndroidRuntime( 9574): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 9574): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 9574): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 9574): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 9574): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 9574): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 9574): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 9574): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 9574): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 9574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 9574): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 9574): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Icing   ( 9574): doRemovePackageData com.test.thalitest
W/FileUtils( 9574): Failed to chmod(/data/data/com.google.android.gms/databases/pluscontacts.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/FileUtils( 9574): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 9574): Failed to open Apps corpus file.
E/Icing   ( 9574): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 9574): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
I/Process ( 9574): Sending signal. PID: 9574 SIG: 9
E/DropBoxManagerService(  882): Can't write: system_app_crash
E/DropBoxManagerService(  882): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  882): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  882): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  882): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  882): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  882): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  882): 	... 5 more
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
