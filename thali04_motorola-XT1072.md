#### Test 573480784751f5c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5203): 
D/AndroidRuntime( 5203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5203): CheckJNI is OFF
D/AndroidRuntime( 5203): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  893): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5222 uid=10483 gids={50483, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5203): Shutting down VM
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 21.600ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.628ms
V/ActivityManager(  893): Display changed displayId=0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 397us total 22.532ms
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5222): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5222): Time to load native libraries: 4 ms (timestamps 7395-7399)
I/LibraryLoader( 5222): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5222): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 5222): Expected native library version number "",actual native library version number ""
I/chromium( 5222): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5222): Initializing chromium process, singleProcess=true
,W/art     ( 5222): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5222): ApplicationContext is null in ApplicationStatus
,W/chromium( 5222): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5222): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5222): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5222): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5222): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5222): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5222): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5222): Local Branch: 
I/Adreno-EGL( 5222): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5222): Local Patches: NONE
I/Adreno-EGL( 5222): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  893): Message: 20
D/BluetoothManagerService(  893): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56d1b85:true
,D/BluetoothAdapter( 5222): 446216149: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  893): Activity pause timeout for ActivityRecord{3ab17af6 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5222): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5222): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5222): CordovaWebView is running on device made by: motorola
,W/art     ( 5222): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5222): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5222): Render dirty regions requested: true
,D/Atlas   ( 5222): Validating map...
,W/chromium( 5222): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5222): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5222): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  893): Displayed com.test.thalitest/.MainActivity,cp,ca,1011
I/ActivityManager(  893): Displayed com.test.thalitest/.MainActivity: +907ms (total +1s11ms)
,W/IInputConnectionWrapper( 5222): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5222): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5222): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5222): Cannot call determinedVisibility() - never saw a connection for the pid: 5222
,D/JsMessageQueue( 5222): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5222): JniHelper::setJavaVM(0xb7bff310), pthread_self() = -1208420960
,I/chromium( 5222): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5222): Initializing JXcore engine
W/jxcore-log( 5222): JXcore engine is ready
,W/Thread-572( 5278): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10483 path="socket:[9658]" dev="sockfs" ino=9658 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-572( 5278): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10483 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-572( 5278): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10483 path="socket:[8633]" dev="sockfs" ino=8633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-572( 5278): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10483 path="socket:[23239]" dev="sockfs" ino=23239 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5222): Starting JXcore engine
,W/jxcore-log( 5222): Platform android
W/jxcore-log( 5222): 
,W/jxcore-log( 5222): Process ARCH arm
W/jxcore-log( 5222): 
,I/jxcore-log( 5222): JXcore Cordova bridge is ready!
I/jxcore-log( 5222): 
W/jxcore-log( 5222): JXcore engine is started
,E/jxcore  ( 5222): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5222): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5222): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  893): Killing 5019:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/PluginManager( 5222): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_5019/cgroup.procs: No such file or directory
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2516): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2516): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2516): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2516): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  893): send {3ec93a73, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  893): send {1148fba3, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  893): done {1148fba3, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,W/IInputConnectionWrapper( 5222): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1421): onFinishInput()
,V/AlarmManager(  893): done {3ec93a73, *alarm*:android.intent.action.TIME_TICK} [62ms]
,I/VacuumService( 1737): Vacuum at: now=1453985645229 tag=VacuumService
,E/global frequency( 2516): no tags to log
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 53636(2MB) AllocSpace objects, 34(1066KB) LOS objects, 39% free, 7MB/12MB, paused 1.067ms total 49.994ms
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     (  893): Explicit concurrent mark sweep GC freed 17107(893KB) AllocSpace objects, 4(232KB) LOS objects, 33% free, 19MB/29MB, paused 1.422ms total 111.635ms
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 4106(171KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 581us total 35.818ms
,I/art     ( 2516): Explicit concurrent mark sweep GC freed 15267(761KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.437ms total 59.575ms
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2516): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2516): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2516): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/TaskPersister(  893): removeObsoleteFile: deleting file=5_task.xml
,I/global frequency( 2516): BcsDSCheckin.events found events 939
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/MotorolaSettings( 2516): no such table to get this name = privacy_droid_blast
W/System.err( 2516): java.lang.Exception
W/System.err( 2516): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 2516): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 2516): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2516): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2516): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 2516): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 2516): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsCore.limitRuleExceeded(BcsCore.java:810)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsCore.doCallHomeCore(BcsCore.java:592)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsCore.doCallHome(BcsCore.java:494)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:325)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:383)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 2516): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 2516): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 2516): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 2516): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 2516): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 2516): 	at java.lang.Thread.run(Thread.java:818)
,I/global frequency( 2516): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2516): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2516): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 2516): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
V/AlarmManager(  893): send {3666d773, *walarm*:com.google.android.intent.action.SEND_IDLE}
,W/Settings( 2516): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2516): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
W/Settings( 2516): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/AlarmManager(  893): done {3666d773, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2516): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2516): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2516): unknown error code mapping for: 0
,I/global frequency( 2516): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2516): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2516): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  893): send {22d4dcd0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  893): send {1560f630, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  893): done {22d4dcd0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,V/AlarmManager(  893): done {1560f630, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [6ms]
,I/ClearcutLoggerApiImpl( 1737): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311446, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-197, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311991, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-253, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  893): send {3ec93a73, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  893): done {3ec93a73, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 3282(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 858us total 30.468ms
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  893): Explicit concurrent mark sweep GC freed 9820(552KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 1.855ms total 116.251ms
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2516): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2516): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311014, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-1201, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  893): send {3ec93a73, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  893): send {1375b493, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 5044): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  893): send {3f2b6d8f, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  893): done {3f2b6d8f, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [20ms]
,V/AlarmManager(  893): done {1375b493, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [32ms]
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  893): done {3ec93a73, *alarm*:android.intent.action.TIME_TICK} [73ms]
,W/Finsky  ( 5044): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5044): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5044): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5044): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  893): send {2f8c484a, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5044): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1737): client connected with version: 8296000
,D/WearableService( 1737): callingUid 10016, callindPid: 1737
,V/AlarmManager(  893): done {2f8c484a, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [14ms]
,D/Finsky  ( 5044): [574] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5044): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5044): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  893): send {2358a069, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  893): done {2358a069, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [10ms]
,D/Finsky  ( 5044): [560] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5044): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2516): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2516): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  893): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e9ecf33)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2131f2f0)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fe9c069)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@195d1aee)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ced2b8f)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23db4e1c)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bd4fa25)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b83f7fa)
,I/art     ( 1737): Explicit concurrent mark sweep GC freed 37593(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/22MB, paused 1.158ms total 90.636ms
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@321af1ab)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a8013a1)
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311581, SEQNUM=4394, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11418, POWER_SUPPLY_CHARGE_COUNTER=-15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5430): 
D/AndroidRuntime( 5430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5430): CheckJNI is OFF
D/AndroidRuntime( 5430): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  893): Force stopping com.test.thalitest appid=10483 user=-1: uninstall pkg
I/ActivityManager(  893): Killing 5222:com.test.thalitest/u0a483 (adj 11): stop com.test.thalitest
W/PackageSettings(  893): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
W/ActivityManager(  893): Spurious death for ProcessRecord{3acdb3aa 5222:com.test.thalitest/u0a483}, curProc for 5222: null
I/ActivityManager(  893): Force stopping com.test.thalitest appid=10483 user=0: pkg removed
I/art     ( 2956): Explicit concurrent mark sweep GC freed 4797(1013KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 503us total 33.989ms
W/GeofencerStateMachine( 1737): Ignoring removeGeofence because network location is disabled.
I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1421): resetDictionaries() : en_US
I/ActivityManager(  893): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5455 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1421): run()
D/VoicemailCleanupService( 1621): Cleaning up data for package: com.test.thalitest
I/art     ( 4957): Explicit concurrent mark sweep GC freed 688(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 358us total 112.676ms
I/art     ( 1554): Explicit concurrent mark sweep GC freed 7299(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 501us total 151.023ms
I/Decoder ( 1421): createOrResetDecoder
I/art     ( 1962): Explicit concurrent mark sweep GC freed 2207(89KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 2.518ms total 198.409ms
I/art     (  893): Explicit concurrent mark sweep GC freed 16522(1056KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 2.373ms total 163.239ms
I/art     (  893): WaitForGcToComplete blocked for 85.290ms for cause Explicit
W/asset   ( 5455): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5455): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5455): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5455): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1421): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1421): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1421): run()
I/StatsUtilsManager( 1421): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1421): shouldRecordStats() = Too Soon
I/ActivityManager(  893): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5479 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  893): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  893): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1554): Deferring update until onResume
I/art     (  893): Explicit concurrent mark sweep GC freed 6743(372KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.442ms total 172.035ms
W/ContextImpl( 5479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1737): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1737): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1962): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/Launcher( 1554): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  893): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5509 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 4957): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Icing   ( 1962): doRemovePackageData com.test.thalitest
D/AndroidRuntime( 5430): Shutting down VM
I/UpdateIcingCorporaServi( 4957): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
I/GAv4    ( 5509): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5509):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5509):   adb logcat -s GAv4
W/GAv4    ( 5509): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5509): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5509): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5509): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5509): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5509): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5509): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5550 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 5105:com.google.android.gms:car/u0a16 (adj 15): empty #7
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_5105/cgroup.procs: No such file or directory

```
