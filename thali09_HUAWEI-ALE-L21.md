#### Test 7214543179cc02a_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-07 12:13:18.049  7888  7888 I appproc : CLASSPATH=/system/framework/am.jar
07-07 12:13:18.049  7888  7888 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-07 12:13:18.049  7888  7888 I appproc : app_process:number,5,0
07-07 12:13:18.049  7888  7888 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-07 12:13:18.189  7888  7888 I         : power log dlsym ok
07-07 12:13:18.239  7888  7888 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-07 12:13:18.239  7888  7888 I android_hardware_fm.cpp: ========64bit long size = 8
07-07 12:13:18.239  7888  7888 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-07 12:13:18.239  7888  7888 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-07 12:13:18.239  7888  7888 I fm_hisi : 
07-07 12:13:18.239  7888  7888 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-07 12:13:18.239  7888  7888 I fm_hisi : 
07-07 12:13:18.239  7888  7888 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-07 12:13:18.239  7888  7888 I fm_hisi : 
07-07 12:13:18.239  7888  7888 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-07 12:13:18.289  3019  3952 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-07 12:13:18.289  3019  3952 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-07 12:13:18.289  3019  3952 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-07 12:13:18.369  3019  3412 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-07 12:13:18.369  3658  4022 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-07 12:13:18.379  3991  7159 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 12:13:18.379  3991  7159 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 12:13:18.379  3776  3776 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-07 12:13:18.379  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-07 12:13:18.379  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-07 12:13:18.389  3991  4238 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-07 12:13:18.389  3776  3776 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-07 12:13:18.389  3776  3776 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-07 12:13:18.519  7908  7908 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-07 12:13:18.549  7908  7908 I LibraryLoader: Loading: webviewchromium
,07-07 12:13:18.609  7908  7908 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 8503-8566)
07-07 12:13:18.609  7908  7908 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 12:13:18.659  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.659  7908  7908 E ZipFileCache: init failed when open zip file.
,07-07 12:13:18.659  7908  7908 E ZipFileCache: init failed when open zip file.
,07-07 12:13:18.659  7908  7908 E ZipFileCache: init failed when open zip file.
,07-07 12:13:18.669  7908  7908 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 12:13:18.679  7908  7908 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 12:13:18.689  7908  7908 I BrowserStartupController: Initializing chromium process, renderers=0
,07-07 12:13:18.689  7908  7908 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 12:13:18.719  7908  7908 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-07 12:13:18.719  7908  7908 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
,07-07 12:13:18.729  7908  7908 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
,07-07 12:13:18.879  7908  7945 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-07 12:13:18.879  7908  7908 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-07 12:13:18.879  7908  7945 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-07 12:13:18.929  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.929  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.939  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.949  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.949  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.959  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.969  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.969  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.969  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.969  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.969  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.979  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.979  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.979  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.979  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.979  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.989  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:18.999  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.009  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.019  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.029  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.039  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.049  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.059  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.059  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.059  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.059  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.059  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.069  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.069  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.069  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.069  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.069  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.079  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.089  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.099  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.099  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.099  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.099  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.109  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 E ZipFileCache: init failed when open zip file.
07-07 12:13:19.119  7908  7908 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 12:13:19.129  7908  7908 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-07 12:13:19.139  7908  7908 I art     : Can not find class: Landroid/widget/ViewStub;
07-07 12:13:19.139  7908  7908 I art     : Can not find class: Landroid/webkit/ViewStub;
07-07 12:13:19.139  7908  7908 I art     : Can not find class: Landroid/app/ViewStub;
07-07 12:13:19.159  7908  7908 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 12:13:19.159  7908  7908 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 12:13:19.309  3383  3383 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 12:13:19.309  3383  3383 I PhoneStatusBar: shouldTranslucent:true
07-07 12:13:19.319  3383  3383 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 12:13:19.369  7908  7959 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 12:13:19.469  7908  7908 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 12:13:19.469  3019  3053 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s94ms (total +1s175ms)
,07-07 12:13:19.589  7908  7908 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-07 12:13:19.589  7908  7908 I chromium: 
,07-07 12:13:19.729  7908  7972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
,07-07 12:13:19.749  7908  7972 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 12:13:19.749  7908  7972 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 12:13:19.749  7908  7972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 12:13:19.749  7908  7972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,07-07 12:13:19.759  7908  7972 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 12:13:19.789  7908  7908 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 12:13:20.229  7908  7975 W jxcore-log: Initializing JXcore engine
07-07 12:13:20.229  7908  7975 W jxcore-log: JXcore engine is ready
,07-07 12:13:20.299  7908  7975 W jxcore-log: Starting JXcore engine
,07-07 12:13:20.399  7908  7975 W jxcore-log: Platform android
07-07 12:13:20.399  7908  7975 W jxcore-log: 
07-07 12:13:20.399  7908  7975 W jxcore-log: Process ARCH arm
07-07 12:13:20.399  7908  7975 W jxcore-log: 
,07-07 12:13:20.619  7908  7975 I jxcore-log: JXcore Cordova bridge is ready!
07-07 12:13:20.619  7908  7975 I jxcore-log: 
,07-07 12:13:20.619  7908  7975 W jxcore-log: JXcore engine is started
,07-07 12:13:20.619  7908  7972 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 12:13:20.629  7908  7908 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 12:13:20.629  7908  7975 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 12:13:20.629  7908  7975 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 12:13:20.639  7908  7908 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-07 12:13:20.639  7908  7908 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 12:13:20.859  7908  7972 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 220ms. Plugin should use CordovaInterface.getThreadPool().
07-07 12:13:20.859  3991  4014 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-07 12:13:20.859  3991  4563 I HwSystemManager: HoldService:uid:10084 pid:7116 died
07-07 12:13:20.859  3019  3752 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 12:13:20.859  3991  4563 I HwSystemManager: HoldService:oldVersionKey:10084,7116
07-07 12:13:20.859  3991  4084 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-07 12:13:20.859  3019  3752 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 7116
07-07 12:13:20.859  3019  3752 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 7116
,07-07 12:13:20.859  3991  4014 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 12:13:20.859  7908  7908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 12:13:20.869  7908  7908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 12:13:20.869  7908  7908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 12:13:20.869  7908  7908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 12:13:20.869  7908  7908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 12:13:20.869  7908  7908 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-07 12:13:20.869  3991  4238 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-07 12:13:20.869  7908  7908 W ScreenOrientationListener: Removing an inexistent observer!
,07-07 12:13:20.929  7977  7977 I appproc : CLASSPATH=/system/framework/pm.jar
07-07 12:13:20.929  7977  7977 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-07 12:13:20.929  7977  7977 I appproc : app_process:number,4,0
,07-07 12:13:20.939  7977  7977 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-07 12:13:21.069  7977  7977 I         : power log dlsym ok
,07-07 12:13:21.119  7977  7977 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-07 12:13:21.119  7977  7977 I android_hardware_fm.cpp: ========64bit long size = 8
07-07 12:13:21.119  7977  7977 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-07 12:13:21.119  7977  7977 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-07 12:13:21.119  7977  7977 I fm_hisi : 
07-07 12:13:21.119  7977  7977 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-07 12:13:21.119  7977  7977 I fm_hisi : 
07-07 12:13:21.119  7977  7977 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-07 12:13:21.119  7977  7977 I fm_hisi : 
07-07 12:13:21.119  7977  7977 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-07 12:13:21.159  3019  3292 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-07 12:13:21.159  3019  3292 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-07 12:13:21.279  3991  4345 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-07 12:13:21.279  3991  4084 I HwSystemManager: HoldService:uid:10072 pid:7908 died
07-07 12:13:21.279  3991  4084 I HwSystemManager: HoldService:oldVersionKey:10072,7908
07-07 12:13:21.279  3019  3491 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 12:13:21.279  3019  3491 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 7908
07-07 12:13:21.279  3019  3491 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 7908
,07-07 12:13:21.289  3019  3335 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-07 12:13:21.329  3019  3059 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-07 12:13:21.329  7243  7243 I art     : Explicit concurrent mark sweep GC freed 7925(599KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 413us total 45.870ms
,07-07 12:13:21.359  3599  4226 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 12:13:21.369  3019  3272 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 12:13:21.369  3019  3059 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-07 12:13:21.379  6676  6676 I art     : Explicit concurrent mark sweep GC freed 32668(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 722us total 91.365ms
,07-07 12:13:21.379  6676  6676 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 12:13:21.379  6676  6676 I HwSystemManager: HsmPackageManager:replacing:false
07-07 12:13:21.379  6676  6676 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-07 12:13:21.379  6676  6676 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-07 12:13:21.379  7079  7240 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@1d69e52f in the cache
,07-07 12:13:21.379  3709  3709 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-07 12:13:21.399  7079  7240 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
07-07 12:13:21.399  7079  7240 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-07 12:13:21.409  7079  7240 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@3b45173c in the cache
07-07 12:13:21.409  3019  3059 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-07 12:13:21.419  5974  5974 I art     : Explicit concurrent mark sweep GC freed 1954(81KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 949us total 134.286ms
,07-07 12:13:21.419  7079  7240 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,07-07 12:13:21.419  7079  7240 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-07 12:13:21.419  7079  7240 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-07 12:13:21.419  7079  7240 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-07 12:13:21.429  7079  7240 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@3de75cc5 in the cache
07-07 12:13:21.429  7079  7240 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@1f24b61a in the cache
,07-07 12:13:21.439  3991  3991 I art     : Explicit concurrent mark sweep GC freed 105087(6MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 10.177ms total 147.724ms
07-07 12:13:21.439  3991  3991 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 12:13:21.439  3991  3991 I HwSystemManager: HsmPackageManager:replacing:false
07-07 12:13:21.439  3991  3991 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-07 12:13:21.439  3991  3991 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-07 12:13:21.449  3991  3991 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-07 12:13:21.449  3776  3776 I art     : Explicit concurrent mark sweep GC freed 48092(2MB) AllocSpace objects, 71(3MB) LOS objects, 38% free, 25MB/41MB, paused 1.245ms total 140.200ms
07-07 12:13:21.449  3776  3776 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 12:13:21.449  3776  3776 I HwLauncher: Model replacing = false package = com.test.thalitest
,07-07 12:13:21.449  3776  3776 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-07 12:13:21.449  3776  3776 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-07 12:13:21.449  3776  3776 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-07 12:13:21.449  3776  3885 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
07-07 12:13:21.449  3776  3889 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
07-07 12:13:21.449  7079  7240 E ExternalAccountType: Unsupported attribute readOnly
,07-07 12:13:21.449  3019  3045 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
07-07 12:13:21.459  3776  3776 E HideAppsPagedView: removeItems begin 
07-07 12:13:21.459  3776  3776 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-07 12:13:21.459  3776  3776 E HideAppsPagedView: removeItems end 
,07-07 12:13:21.459  3776  3776 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
07-07 12:13:21.459  3776  3889 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-07 12:13:21.459  3776  3889 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-07 12:13:21.459  3776  3889 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-07 12:13:21.459  3776  3889 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-07 12:13:21.459  3776  3889 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-07 12:13:21.459  7079  7240 I AccountTypeManager: AccountManager, account size is: 2
,07-07 12:13:21.469  7079  7240 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 95ms(wall) 22ms(cpu)
,07-07 12:13:21.469  3776  3776 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-07 12:13:21.469  3776  3776 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-07 12:13:21.469  3776  3776 W System.err: java.lang.NullPointerException: null receiver
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 12:13:21.469  3776  3776 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 12:13:21.469  3776  3776 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 12:13:21.469  3776  3776 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-07 12:13:21.469  3776  3776 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
07-07 12:13:21.469  3776  3776 I HwLauncher: Launcher Deferring update until onResume
,07-07 12:13:21.479  3019  3277 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-07 12:13:21.479  3991  4141 I HwSystemManager: aor:Network Stats Updated
07-07 12:13:21.479  3991  4141 I HwSystemManager: aoi:onNetworkStatsUpdated
07-07 12:13:21.479  3991  4145 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 12:13:21.489  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 12:13:21.489  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 12:13:21.489  3991  4145 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 12:13:21.489  3991  4145 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-07 12:13:21.489  3991  4145 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-07 12:13:21.489  3991  4145 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 12:13:21.509  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 12:13:21.509  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 12:13:21.509  3991  4145 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 12:13:21.509  3991  4145 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-07 12:13:21.509  3991  4145 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-07 12:13:21.509  3991  4145 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 12:13:21.519  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 12:13:21.519  3991  4145 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 12:13:21.519  3991  4145 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 12:13:21.519  3991  4145 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-07 12:13:21.519  3991  4145 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-07 12:13:21.529  3776  3776 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-07 12:13:21.529  3776  3776 I HwLauncher: Launcher onStart()
07-07 12:13:21.529  3776  3776 I HwLauncher: Launcher dynamicIconsRegister
07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicUpdater registerReceiver
,07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicUpdater call updateFolder
07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-07 12:13:21.529  3776  3776 I HwLauncher: DynamicUpdater registerReceiver
,07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicUpdater call updateFolder
07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicUpdater registerReceiver
,07-07 12:13:21.539  3776  3885 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicUpdater call updateFolder
,07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-07 12:13:21.539  3776  3776 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,07-07 12:13:21.539  3776  3776 E HideAppsPagedView: removeHideApps  begin 
07-07 12:13:21.539  3776  3776 E HideAppsPagedView: removeHideApps  end 
07-07 12:13:21.539  3776  3776 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-07 12:13:21.539  3776  3885 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-07 12:13:21.539  3776  3885 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-07 12:13:21.539  3776  3885 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-07 12:13:21.539  3776  3776 E ZipFileCache: init failed when open zip file.
07-07 12:13:21.539  3776  3776 E ZipFileCache: init failed when open zip file.
07-07 12:13:21.539  3776  3776 E ZipFileCache: init failed when open zip file.
07-07 12:13:21.539  3776  3885 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,07-07 12:13:21.549  3776  3776 E ZipFileCache: init failed when open zip file.
,07-07 12:13:21.549  3776  3885 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-07 12:13:21.549  3776  3885 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-07 12:13:21.549  3776  3885 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-07 12:13:21.549  3776  3776 E ZipFileCache: init failed when open zip file.
,07-07 12:13:21.549  3776  3776 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,07-07 12:13:21.549  3776  3776 E HideAppsPagedView:  createAddIcon count = 0
,07-07 12:13:21.559  3776  3776 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
07-07 12:13:21.559  3019  3045 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
07-07 12:13:21.559  3776  3776 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
07-07 12:13:21.559  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-07 12:13:21.559  3776  3776 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-07 12:13:21.589  3776  3776 I HwLauncher: DynamicUpdater call updateFolder
,07-07 12:13:21.619  3019  3019 I art     : Explicit concurrent mark sweep GC freed 53721(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/42MB, paused 3.442ms total 299.296ms
,07-07 12:13:21.619  3019  3059 I art     : WaitForGcToComplete blocked for 185.478ms for cause Explicit
,07-07 12:13:21.639  8023  8023 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-07 12:13:21.649  8001  8001 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-07 12:13:21.649  8001  8001 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-07 12:13:21.669  8023  8043 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-07 12:13:21.679  8023  8023 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-07 12:13:21.749  3019  3265 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-07 12:13:21.749  3019  3265 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-07 12:13:21.749  3019  3265 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-07 12:13:21.749  3019  3265 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-07 12:13:21.749  3019  3265 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 12:13:21.749  3019  3265 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 12:13:21.749  3019  3265 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 12:13:21.829  3019  3059 I art     : Explicit concurrent mark sweep GC freed 6460(305KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.175ms total 214.297ms
,07-07 12:13:21.839  3776  3776 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
07-07 12:13:21.839  3776  3885 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-07 12:13:21.839  3776  3885 I HwLauncher:  stringArray[] [unknown]
,07-07 12:13:21.839  3019  3019 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-07 12:13:21.839  3019  3019 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-07 12:13:21.849  3019  3019 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-07 12:13:21.849  3019  3019 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-07 12:13:21.849  3019  3019 E ReportTools: Can't find sReporterClazz
07-07 12:13:21.849  3019  3019 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
07-07 12:13:21.849  3019  3019 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-07 12:13:21.849  3019  3019 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-07 12:13:21.859  3019  3019 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-07 12:13:21.859  3019  3019 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-07 12:13:21.859  3019  3019 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-07 12:13:21.859  3019  3019 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-07 12:13:21.859  3019  3019 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-07 12:13:21.859  3019  3019 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 12:13:21.859  3019  3019 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 12:13:21.859  3019  3019 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-07 12:13:21.859  3019  3019 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 12:13:21.859  3019  3019 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 12:13:21.859  3019  3019 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-07 12:13:21.859  3019  3019 E ReportTools: This is not beta user build
07-07 12:13:21.859  3383  3383 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 12:13:21.859  3383  3383 I PhoneStatusBar: shouldTranslucent:true
07-07 12:13:21.859  3383  3383 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 12:13:21.869  3991  4326 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-07 12:13:21.869  3991  4563 I HwSystemManager: HoldService:uid:10058 pid:6349 died
07-07 12:13:21.869  3991  4563 I HwSystemManager: HoldService:oldVersionKey:10058,6349
07-07 12:13:21.869  3019  3952 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 12:13:21.869  3019  3952 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 6349
07-07 12:13:21.869  3019  3952 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 6349
,07-07 12:13:22.079  3991  4084 I HwSystemManager: HoldService:uid:10010 pid:7271 died
07-07 12:13:22.079  3991  4345 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10010
07-07 12:13:22.079  3991  4084 I HwSystemManager: HoldService:oldVersionKey:10010,7271
07-07 12:13:22.079  3019  3514 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 12:13:22.079  3019  3514 I MediaProcessHandler: processOp opType: 1, uid: 10010, pid: 7271
07-07 12:13:22.079  3019  3514 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10010, pid: 7271
,07-07 12:13:22.099  3991  3991 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.099  3991  3991 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-07 12:13:22.109  3991  3991 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2769c974
,07-07 12:13:22.109  3991  3991 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,07-07 12:13:22.109  3991  8098 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,07-07 12:13:22.109  6676  6676 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.109  6676  6676 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3bd03052
,07-07 12:13:22.119  6676  6676 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-07 12:13:22.119  6676  6676 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,07-07 12:13:22.119  6676  8099 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-07 12:13:22.119  6676  8100 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-07 12:13:22.119  6676  6676 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.129  6676  8100 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.129  6676  8100 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
,07-07 12:13:22.129  6676  7521 I HwSystemManager: ProtectAppControl:handleMessage:7
07-07 12:13:22.129  3991  4563 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
,07-07 12:13:22.129  6676  7521 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
,07-07 12:13:22.129  3991  3991 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-07 12:13:22.129  3991  3991 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-07 12:13:22.129  3991  3991 E HwSystemManager: AppCleanUpService:msg is 1
,07-07 12:13:22.129  6676  8100 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.129  6676  8100 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
,07-07 12:13:22.139  6676  6676 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-07 12:13:22.139  6676  8101 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-07 12:13:22.139  6676  8101 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.139  6676  8101 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.139  6676  8101 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
,07-07 12:13:22.139  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.139  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
07-07 12:13:22.139  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-07 12:13:22.159  6676  6676 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
,07-07 12:13:22.159  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-07 12:13:22.159  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-07 12:13:22.159  6676  6676 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
,07-07 12:13:22.169  3991  4013 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 12:13:22.169  3991  4013 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-07 12:13:22.169  3991  4014 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-07 12:13:22.169  3991  4014 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 12:13:22.169  3991  4014 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-07 12:13:22.169  3991  8098 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.169  3991  8098 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
07-07 12:13:22.169  3991  8098 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-07 12:13:22.169  3991  4326 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-07 12:13:22.169  3991  4326 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 12:13:22.169  3991  4326 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-07 12:13:22.169  3383  3383 I PhoneStatusBar: notification pkg =com.android.settings
07-07 12:13:22.169  3383  3383 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-07 12:13:22.169  3383  3383 I PhoneStatusBar: notification pkg =android
07-07 12:13:22.169  3383  3383 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,07-07 12:13:22.179  6676  8099 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-07 12:13:22.179  6676  8099 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-07 12:13:22.179  6676  8103 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
07-07 12:13:22.179  6676  8103 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
,07-07 12:13:22.189  6676  6676 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
07-07 12:13:22.189  6676  8105 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
,07-07 12:13:22.199  6676  8106 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
07-07 12:13:22.199  6676  6676 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.209  6676  8106 I TrashManager: EngineManager not initialed, please EngineManager#init()
07-07 12:13:22.209  3991  8108 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-07 12:13:22.279  3991  3991 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2769c974
,07-07 12:13:22.309  6676  8099 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-07 12:13:22.319  6676  8099 I HwSystemManager: PermissionDbVisitor:removeHistoryRecord,pkgName:com.test.thalitest, delete count:0
,07-07 12:13:22.319  6676  8099 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-07 12:13:22.319  6676  8099 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-07 12:13:22.419  6676  8099 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-07 12:13:22.419  6676  8099 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.419  6676  8099 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-07 12:13:22.419  6676  8099 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-07 12:13:22.469  6676  6676 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3bd03052

```
