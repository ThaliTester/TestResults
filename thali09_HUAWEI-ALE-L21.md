#### Test 7214543121d4f5c_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-06 13:55:45.745  8514  8514 I appproc : CLASSPATH=/system/framework/am.jar
07-06 13:55:45.745  8514  8514 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-06 13:55:45.745  8514  8514 I appproc : app_process:number,5,0
07-06 13:55:45.745  8514  8514 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-06 13:55:45.895  8514  8514 I         : power log dlsym ok
07-06 13:55:45.935  8514  8514 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-06 13:55:45.935  8514  8514 I android_hardware_fm.cpp: ========64bit long size = 8
07-06 13:55:45.935  8514  8514 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-06 13:55:45.935  8514  8514 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-06 13:55:45.935  8514  8514 I fm_hisi : 
07-06 13:55:45.935  8514  8514 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-06 13:55:45.935  8514  8514 I fm_hisi : 
07-06 13:55:45.935  8514  8514 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-06 13:55:45.935  8514  8514 I fm_hisi : 
07-06 13:55:45.935  8514  8514 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-06 13:55:45.985  3023  3445 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-06 13:55:45.995  3023  3445 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-06 13:55:45.995  3023  3445 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-06 13:55:46.055  3023  3447 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-06 13:55:46.065  3580  4085 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-06 13:55:46.065  3541  3562 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 13:55:46.075  3541  3562 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 13:55:46.075  5094  5094 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-06 13:55:46.075  5094  5094 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-06 13:55:46.075  5094  5094 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-06 13:55:46.075  3541  4115 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-06 13:55:46.085  5094  5094 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-06 13:55:46.085  5094  5094 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-06 13:55:46.215  8533  8533 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-06 13:55:46.235  8533  8533 I LibraryLoader: Loading: webviewchromium
,07-06 13:55:46.285  8533  8533 I LibraryLoader: Time to load native libraries: 46 ms (timestamps 4817-4863)
07-06 13:55:46.285  8533  8533 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 13:55:46.325  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.325  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.335  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.335  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.345  8533  8533 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 13:55:46.355  8533  8533 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 13:55:46.365  8533  8533 I BrowserStartupController: Initializing chromium process, renderers=0
07-06 13:55:46.365  8533  8533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 13:55:46.425  8533  8533 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-06 13:55:46.425  8533  8533 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-06 13:55:46.425  8533  8533 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-06 13:55:46.595  8533  8569 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 13:55:46.595  8533  8533 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-06 13:55:46.595  8533  8569 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 13:55:46.635  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.635  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.645  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.655  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.655  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.665  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.675  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.675  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.675  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.675  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.685  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.695  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.705  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.705  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.705  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.705  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.715  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.725  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.735  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.745  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.755  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.765  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.765  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.765  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.765  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.775  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.785  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.795  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.795  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.795  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.795  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.805  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.815  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.825  8533  8533 E ZipFileCache: init failed when open zip file.
07-06 13:55:46.835  8533  8533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 13:55:46.835  8533  8533 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-06 13:55:46.845  8533  8533 I art     : Can not find class: Landroid/widget/ViewStub;
07-06 13:55:46.845  8533  8533 I art     : Can not find class: Landroid/webkit/ViewStub;
07-06 13:55:46.845  8533  8533 I art     : Can not find class: Landroid/app/ViewStub;
07-06 13:55:46.865  8533  8533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 13:55:46.865  8533  8533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 13:55:47.035  3319  3319 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 13:55:47.045  3319  3319 I PhoneStatusBar: shouldTranslucent:true
07-06 13:55:47.045  3319  3319 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 13:55:47.105  8533  8583 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 13:55:47.155  3023  3057 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s88ms (total +1s160ms)
07-06 13:55:47.155  8533  8533 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-06 13:55:47.275  8533  8533 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-06 13:55:47.275  8533  8533 I chromium: 
,07-06 13:55:47.425  8533  8596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
,07-06 13:55:47.445  8533  8596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-06 13:55:47.445  8533  8596 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-06 13:55:47.445  8533  8596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-06 13:55:47.445  8533  8596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,07-06 13:55:47.455  8533  8596 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-06 13:55:47.485  8533  8533 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 13:55:47.935  8533  8599 W jxcore-log: Initializing JXcore engine
07-06 13:55:47.935  8533  8599 W jxcore-log: JXcore engine is ready
,07-06 13:55:47.995  8533  8599 W jxcore-log: Starting JXcore engine
,07-06 13:55:48.105  8533  8599 W jxcore-log: Platform android
07-06 13:55:48.105  8533  8599 W jxcore-log: 
07-06 13:55:48.105  8533  8599 W jxcore-log: Process ARCH arm
07-06 13:55:48.105  8533  8599 W jxcore-log: 
,07-06 13:55:48.315  8533  8599 I jxcore-log: JXcore Cordova bridge is ready!
07-06 13:55:48.315  8533  8599 I jxcore-log: 
,07-06 13:55:48.315  8533  8599 W jxcore-log: JXcore engine is started
,07-06 13:55:48.325  8533  8596 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 13:55:48.325  8533  8533 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 13:55:48.335  8533  8599 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-06 13:55:48.335  8533  8599 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-06 13:55:48.335  8533  8533 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-06 13:55:48.335  8533  8533 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-06 13:55:48.345  3334  3334 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 13
07-06 13:55:48.345  3023  3900 E WifiMonitor: WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 13
07-06 13:55:48.345  3023  3190 E WifiStateMachine:  ConnectedState what:147506 0 0
07-06 13:55:48.345  3023  3190 E WifiStateMachine:  L2ConnectedState what:147506 0 0
07-06 13:55:48.345  3023  3190 E WifiStateMachine:  ConnectModeState what:147506 0 0
07-06 13:55:48.345  3023  3190 E WifiStateMachine:  DriverStartedState what:147506 0 0
07-06 13:55:48.345  3023  3190 E WifiStateMachine:  SupplicantStartedState what:147506 0 0
,07-06 13:55:48.455  8533  8596 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 114ms. Plugin should use CordovaInterface.getThreadPool().
,07-06 13:55:48.455  3541  4495 I HwSystemManager: HoldService:uid:10058 pid:7690 died
07-06 13:55:48.455  3541  4495 I HwSystemManager: HoldService:oldVersionKey:10058,7690
07-06 13:55:48.455  3541  3562 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
,07-06 13:55:48.455  3023  3808 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 13:55:48.455  8533  8533 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-06 13:55:48.455  3023  3808 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 7690
07-06 13:55:48.455  3023  3808 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 7690
07-06 13:55:48.455  8533  8533 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-06 13:55:48.455  8533  8533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-06 13:55:48.455  8533  8533 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-06 13:55:48.455  8533  8533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-06 13:55:48.455  3541  3560 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-06 13:55:48.465  3541  3560 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-06 13:55:48.465  8533  8533 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-06 13:55:48.465  3541  4115 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-06 13:55:48.465  8533  8533 W ScreenOrientationListener: Removing an inexistent observer!
,07-06 13:55:48.625  8604  8604 I appproc : CLASSPATH=/system/framework/pm.jar
07-06 13:55:48.625  8604  8604 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-06 13:55:48.625  8604  8604 I appproc : app_process:number,4,0
,07-06 13:55:48.635  8604  8604 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-06 13:55:48.765  8604  8604 I         : power log dlsym ok
,07-06 13:55:48.815  8604  8604 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-06 13:55:48.815  8604  8604 I android_hardware_fm.cpp: ========64bit long size = 8
07-06 13:55:48.815  8604  8604 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-06 13:55:48.815  8604  8604 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-06 13:55:48.815  8604  8604 I fm_hisi : 
07-06 13:55:48.815  8604  8604 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-06 13:55:48.815  8604  8604 I fm_hisi : 
07-06 13:55:48.815  8604  8604 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-06 13:55:48.815  8604  8604 I fm_hisi : 
07-06 13:55:48.815  8604  8604 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-06 13:55:48.855  3023  3447 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-06 13:55:48.855  3023  3447 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-06 13:55:48.995  3023  3243 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-06 13:55:49.035  3541  3562 I HwSystemManager: HoldService:uid:10072 pid:8533 died
07-06 13:55:49.035  3541  3562 I HwSystemManager: HoldService:oldVersionKey:10072,8533
,07-06 13:55:49.035  3023  4232 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 13:55:49.035  3541  3560 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-06 13:55:49.035  3023  4232 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 8533
07-06 13:55:49.035  3023  4232 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 8533
,07-06 13:55:49.095  3023  3063 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-06 13:55:49.115  3023  3167 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-06 13:55:49.125  7741  7741 I art     : Explicit concurrent mark sweep GC freed 7967(600KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 30.662ms total 82.842ms
07-06 13:55:49.125  3978  4406 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-06 13:55:49.125  7548  7732 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@4732c7c in the cache
,07-06 13:55:49.135  7548  7732 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-06 13:55:49.135  3023  3049 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-06 13:55:49.145  3645  3645 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
07-06 13:55:49.145  7548  7732 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-06 13:55:49.145  7548  7732 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@207fe905 in the cache
,07-06 13:55:49.165  7548  7732 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-06 13:55:49.165  7548  7732 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-06 13:55:49.165  7548  7732 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-06 13:55:49.165  7548  7732 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-06 13:55:49.165  7548  7732 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@e53ed5a in the cache
,07-06 13:55:49.165  7548  7732 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@19a9ab8b in the cache
,07-06 13:55:49.175  7548  7732 E ExternalAccountType: Unsupported attribute readOnly
,07-06 13:55:49.185  6272  6272 I art     : Explicit concurrent mark sweep GC freed 17619(1096KB) AllocSpace objects, 5(100KB) LOS objects, 25% free, 23MB/31MB, paused 2.915ms total 145.769ms
07-06 13:55:49.185  7548  7732 I AccountTypeManager: AccountManager, account size is: 2
,07-06 13:55:49.185  7109  7109 I art     : Explicit concurrent mark sweep GC freed 32723(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 998us total 144.514ms
07-06 13:55:49.185  7109  7109 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-06 13:55:49.195  7109  7109 I HwSystemManager: HsmPackageManager:replacing:false
07-06 13:55:49.195  7109  7109 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-06 13:55:49.205  7548  7732 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 83ms(wall) 21ms(cpu)
07-06 13:55:49.205  7109  7109 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-06 13:55:49.205  3541  3541 I art     : Explicit concurrent mark sweep GC freed 105758(6MB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/23MB, paused 13.074ms total 157.269ms
,07-06 13:55:49.215  3023  3063 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-06 13:55:49.215  3541  3541 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-06 13:55:49.215  3541  3541 I HwSystemManager: HsmPackageManager:replacing:false
07-06 13:55:49.215  3541  3541 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-06 13:55:49.215  3541  3541 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-06 13:55:49.215  3023  3063 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-06 13:55:49.225  3541  3541 I HwSystemManager: ww:deleteLockData:com.test.thalitest
07-06 13:55:49.225  5094  5094 I art     : Explicit concurrent mark sweep GC freed 36808(2MB) AllocSpace objects, 64(9MB) LOS objects, 40% free, 23MB/39MB, paused 8.710ms total 178.940ms
07-06 13:55:49.225  5094  5094 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-06 13:55:49.225  5094  5094 I HwLauncher: Model replacing = false package = com.test.thalitest
07-06 13:55:49.225  5094  5094 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-06 13:55:49.225  5094  5094 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-06 13:55:49.225  5094  5094 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-06 13:55:49.225  5094  5169 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
07-06 13:55:49.225  5094  5169 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-06 13:55:49.225  5094  5169 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-06 13:55:49.225  5094  5169 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-06 13:55:49.225  5094  5169 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-06 13:55:49.225  5094  5169 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-06 13:55:49.235  3023  3173 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
07-06 13:55:49.235  5094  5166 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-06 13:55:49.235  5094  5094 E HideAppsPagedView: removeItems begin 
07-06 13:55:49.235  5094  5094 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-06 13:55:49.235  5094  5094 E HideAppsPagedView: removeItems end 
,07-06 13:55:49.245  5094  5094 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-06 13:55:49.255  5094  5094 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-06 13:55:49.255  5094  5094 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
,07-06 13:55:49.255  5094  5094 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-06 13:55:49.255  5094  5094 W System.err: java.lang.NullPointerException: null receiver
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 13:55:49.255  5094  5094 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 13:55:49.255  5094  5094 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 13:55:49.255  5094  5094 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-06 13:55:49.255  5094  5094 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
,07-06 13:55:49.255  5094  5094 I HwLauncher: Launcher Deferring update until onResume
07-06 13:55:49.255  5094  5094 I HwLauncher: Launcher onStart()
07-06 13:55:49.255  5094  5094 I HwLauncher: Launcher dynamicIconsRegister
07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicUpdater registerReceiver
,07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicUpdater call updateFolder
,07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicUpdater registerReceiver
,07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicUpdater call updateFolder
,07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-06 13:55:49.255  5094  5094 I HwLauncher: DynamicUpdater registerReceiver
,07-06 13:55:49.265  5094  5166 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 13:55:49.265  5094  5094 I HwLauncher: DynamicUpdater call updateFolder
07-06 13:55:49.265  5094  5094 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
,07-06 13:55:49.265  5094  5094 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-06 13:55:49.265  5094  5094 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,07-06 13:55:49.265  5094  5166 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 13:55:49.265  5094  5166 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-06 13:55:49.265  5094  5166 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 13:55:49.265  5094  5166 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,07-06 13:55:49.275  5094  5166 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-06 13:55:49.275  5094  5166 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-06 13:55:49.275  5094  5166 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
,07-06 13:55:49.275  5094  5094 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
,07-06 13:55:49.275  5094  5094 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
,07-06 13:55:49.275  5094  5094 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-06 13:55:49.305  5094  5094 I HwLauncher: DynamicUpdater call updateFolder
07-06 13:55:49.305  5094  5094 E HideAppsPagedView: removeHideApps  begin 
07-06 13:55:49.305  5094  5094 E HideAppsPagedView: removeHideApps  end 
07-06 13:55:49.305  5094  5094 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-06 13:55:49.305  5094  5094 E ZipFileCache: init failed when open zip file.
,07-06 13:55:49.305  5094  5094 E ZipFileCache: init failed when open zip file.
,07-06 13:55:49.305  5094  5094 E ZipFileCache: init failed when open zip file.
,07-06 13:55:49.305  5094  5094 E ZipFileCache: init failed when open zip file.
,07-06 13:55:49.305  5094  5094 E ZipFileCache: init failed when open zip file.
,07-06 13:55:49.305  5094  5094 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-06 13:55:49.305  5094  5094 E HideAppsPagedView:  createAddIcon count = 0
,07-06 13:55:49.315  5094  5094 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,07-06 13:55:49.315  3023  3049 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-06 13:55:49.335  3541  3878 I HwSystemManager: aor:Network Stats Updated
07-06 13:55:49.335  3541  3878 I HwSystemManager: aoi:onNetworkStatsUpdated
07-06 13:55:49.335  3541  3879 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 13:55:49.345  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 13:55:49.355  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 13:55:49.355  3541  3879 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 13:55:49.355  3541  3879 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-06 13:55:49.355  3541  3879 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-06 13:55:49.355  3541  3879 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 13:55:49.355  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 13:55:49.365  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 13:55:49.365  3541  3879 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 13:55:49.365  3541  3879 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-06 13:55:49.365  3541  3879 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-06 13:55:49.365  3541  3879 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 13:55:49.365  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 13:55:49.365  3541  3879 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 13:55:49.365  3541  3879 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 13:55:49.365  3541  3879 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-06 13:55:49.365  3541  3879 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-06 13:55:49.375  3023  3023 I art     : Explicit concurrent mark sweep GC freed 43818(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/42MB, paused 2.138ms total 331.885ms
,07-06 13:55:49.375  3023  3063 I art     : WaitForGcToComplete blocked for 144.972ms for cause Explicit
,07-06 13:55:49.385  8650  8650 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-06 13:55:49.385  8627  8627 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-06 13:55:49.385  8627  8627 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-06 13:55:49.415  8650  8670 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-06 13:55:49.435  8650  8650 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-06 13:55:49.475  5094  5094 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
07-06 13:55:49.475  5094  5166 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-06 13:55:49.475  5094  5166 I HwLauncher:  stringArray[] [unknown]
,07-06 13:55:49.495  3023  3159 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 13:55:49.495  3023  3159 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-06 13:55:49.495  3023  3159 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-06 13:55:49.495  3023  3159 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-06 13:55:49.495  3023  3159 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 13:55:49.495  3023  3159 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 13:55:49.495  3023  3159 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-06 13:55:49.565  3023  3063 I art     : Explicit concurrent mark sweep GC freed 6129(288KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.055ms total 191.570ms
,07-06 13:55:49.585  3023  3023 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-06 13:55:49.585  3023  3023 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-06 13:55:49.585  3023  3023 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
07-06 13:55:49.585  3023  3023 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
07-06 13:55:49.585  3023  3023 E ReportTools: Can't find sReporterClazz
,07-06 13:55:49.585  3023  3023 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-06 13:55:49.595  3023  3023 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-06 13:55:49.595  3023  3023 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-06 13:55:49.595  3023  3023 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-06 13:55:49.595  3023  3023 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-06 13:55:49.595  3023  3023 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-06 13:55:49.595  3023  3023 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-06 13:55:49.595  3023  3023 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-06 13:55:49.595  3023  3023 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 13:55:49.595  3023  3023 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 13:55:49.595  3023  3023 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-06 13:55:49.595  3023  3023 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 13:55:49.595  3023  3023 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 13:55:49.595  3023  3023 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-06 13:55:49.595  3023  3023 E ReportTools: This is not beta user build
07-06 13:55:49.595  3319  3319 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-06 13:55:49.595  3319  3319 I PhoneStatusBar: shouldTranslucent:true
,07-06 13:55:49.595  3319  3319 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 13:55:49.605  3541  3562 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10007
07-06 13:55:49.605  3541  4250 I HwSystemManager: HoldService:uid:10007 pid:8007 died
07-06 13:55:49.605  3541  4250 I HwSystemManager: HoldService:oldVersionKey:10007,8007
07-06 13:55:49.605  3023  3318 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 13:55:49.605  3023  3318 I MediaProcessHandler: processOp opType: 1, uid: 10007, pid: 8007
07-06 13:55:49.605  3023  3318 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10007, pid: 8007
,07-06 13:55:49.815  3541  4495 I HwSystemManager: HoldService:uid:10010 pid:7770 died
07-06 13:55:49.815  3541  4495 I HwSystemManager: HoldService:oldVersionKey:10010,7770
07-06 13:55:49.815  3541  5484 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10010
07-06 13:55:49.815  3023  3447 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 13:55:49.815  3023  3447 I MediaProcessHandler: processOp opType: 1, uid: 10010, pid: 7770
07-06 13:55:49.815  3023  3447 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10010, pid: 7770
,07-06 13:55:49.825  3541  3541 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.825  3541  3541 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
07-06 13:55:49.835  3541  3541 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@27429a69
07-06 13:55:49.835  3541  3541 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
07-06 13:55:49.835  3541  8721 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
07-06 13:55:49.835  7109  7109 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.835  7109  7109 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@308b075c
07-06 13:55:49.835  7109  7109 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
07-06 13:55:49.845  7109  8723 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-06 13:55:49.845  7109  7109 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
07-06 13:55:49.845  7109  8724 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-06 13:55:49.845  7109  8724 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.845  7109  8092 I HwSystemManager: ProtectAppControl:handleMessage:7
07-06 13:55:49.845  7109  8724 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
07-06 13:55:49.845  3541  3560 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
07-06 13:55:49.845  7109  8724 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.845  7109  8724 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
07-06 13:55:49.845  7109  7109 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.845  7109  8092 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
07-06 13:55:49.855  3541  3541 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-06 13:55:49.855  3541  3541 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-06 13:55:49.855  3541  3541 E HwSystemManager: AppCleanUpService:msg is 1
07-06 13:55:49.855  7109  7109 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-06 13:55:49.865  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.865  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
07-06 13:55:49.865  7109  8725 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-06 13:55:49.865  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
07-06 13:55:49.865  7109  8725 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.865  7109  8725 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.865  7109  8725 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
,07-06 13:55:49.885  3541  3562 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-06 13:55:49.885  3541  3562 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 13:55:49.885  3541  3562 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-06 13:55:49.885  3541  5484 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 13:55:49.885  3541  5484 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-06 13:55:49.895  3541  8721 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:49.895  3541  8721 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
07-06 13:55:49.895  3541  8721 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
07-06 13:55:49.895  3541  3560 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-06 13:55:49.895  3541  3560 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 13:55:49.895  3541  3560 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-06 13:55:49.895  7109  7109 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
07-06 13:55:49.895  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-06 13:55:49.895  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-06 13:55:49.895  3319  3319 I PhoneStatusBar: notification pkg =com.android.settings
07-06 13:55:49.895  3319  3319 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-06 13:55:49.895  3319  3319 I PhoneStatusBar: notification pkg =android
07-06 13:55:49.895  3319  3319 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-06 13:55:49.895  7109  7109 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
07-06 13:55:49.915  7109  8723 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-06 13:55:49.915  7109  8723 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-06 13:55:49.925  3541  8727 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-06 13:55:49.945  3541  3541 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@27429a69
,07-06 13:55:49.945  7109  8728 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
07-06 13:55:49.945  7109  8728 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
,07-06 13:55:49.955  7109  8730 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
,07-06 13:55:49.955  7109  7109 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
,07-06 13:55:49.965  7109  8731 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
07-06 13:55:49.965  7109  7109 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-06 13:55:49.965  7109  8731 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-06 13:55:49.995  7109  8723 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-06 13:55:50.005  7109  8723 I HwSystemManager: PermissionDbVisitor:removeHistoryRecord,pkgName:com.test.thalitest, delete count:0
,07-06 13:55:50.005  7109  8723 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-06 13:55:50.005  7109  8723 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-06 13:55:50.025  7109  8731 W System.err: java.io.FileNotFoundException: /data/data/com.huawei.systemmanager/files/ye_app_trash: open failed: EROFS (Read-only file system)
,07-06 13:55:50.025  7109  8731 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:463)
07-06 13:55:50.025  7109  8731 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-06 13:55:50.025  7109  8731 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-06 13:55:50.025  7109  8731 W System.err: 	at yhdsengine.fm.b(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at yhdsengine.fo.a(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at yhdsengine.fj.a(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at com.dianxinos.optimizer.engine.trash.TrashManager.scanUninstalledAppTrash(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at bgr.bf(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at com.huawei.optimizer.PackageChangeReceiver.i(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at com.huawei.optimizer.PackageChangeReceiver.onPackageChange(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at com.huawei.optimizer.CommonIntentService.onHandleIntent(Unknown Source)
07-06 13:55:50.025  7109  8731 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-06 13:55:50.025  7109  8731 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 13:55:50.025  7109  8731 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 13:55:50.025  7109  8731 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 13:55:50.025  7109  8731 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-06 13:55:50.025  7109  8731 W System.err: 	at libcore.io.Posix.open(Native Method)
07-06 13:55:50.025  7109  8731 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-06 13:55:50.025  7109  8731 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:449)
07-06 13:55:50.025  7109  8731 W System.err: 	... 14 more
,07-06 13:55:50.125  7109  8723 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-06 13:55:50.125  7109  8723 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 13:55:50.125  7109  8723 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-06 13:55:50.125  7109  8723 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-06 13:55:50.175  7109  7109 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@308b075c

```
