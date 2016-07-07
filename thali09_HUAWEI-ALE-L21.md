#### Test 757892685345aa0_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-07 15:48:08.368  8103  8103 I appproc : CLASSPATH=/system/framework/am.jar
07-07 15:48:08.368  8103  8103 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-07 15:48:08.368  8103  8103 I appproc : app_process:number,5,0
07-07 15:48:08.368  8103  8103 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-07 15:48:08.518  8103  8103 I         : power log dlsym ok
07-07 15:48:08.558  8103  8103 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-07 15:48:08.558  8103  8103 I android_hardware_fm.cpp: ========64bit long size = 8
07-07 15:48:08.558  8103  8103 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-07 15:48:08.558  8103  8103 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-07 15:48:08.558  8103  8103 I fm_hisi : 
07-07 15:48:08.558  8103  8103 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-07 15:48:08.558  8103  8103 I fm_hisi : 
07-07 15:48:08.558  8103  8103 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-07 15:48:08.558  8103  8103 I fm_hisi : 
07-07 15:48:08.558  8103  8103 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-07 15:48:08.608  3109  3930 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-07 15:48:08.618  3109  3930 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-07 15:48:08.618  3109  3930 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-07 15:48:08.678  3109  3939 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-07 15:48:08.688  3849  4256 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-07 15:48:08.688  4246  4341 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 15:48:08.698  4246  4341 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 15:48:08.698  3962  3962 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-07 15:48:08.698  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-07 15:48:08.698  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-07 15:48:08.698  4246  4477 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-07 15:48:08.708  3962  3962 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-07 15:48:08.708  3962  3962 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-07 15:48:08.838  8122  8122 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
,07-07 15:48:08.868  8122  8122 I LibraryLoader: Loading: webviewchromium
,07-07 15:48:08.928  8122  8122 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 1524-1581)
07-07 15:48:08.928  8122  8122 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 15:48:08.958  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:08.958  8122  8122 E ZipFileCache: init failed when open zip file.
,07-07 15:48:08.968  8122  8122 E ZipFileCache: init failed when open zip file.
,07-07 15:48:08.968  8122  8122 E ZipFileCache: init failed when open zip file.
,07-07 15:48:08.978  8122  8122 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 15:48:08.978  8122  8122 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 15:48:08.988  8122  8122 I BrowserStartupController: Initializing chromium process, renderers=0
,07-07 15:48:08.998  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 15:48:09.038  8122  8122 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-07 15:48:09.048  8122  8122 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
,07-07 15:48:09.048  8122  8122 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
,07-07 15:48:09.208  8122  8161 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-07 15:48:09.218  8122  8122 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-07 15:48:09.218  8122  8161 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-07 15:48:09.258  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.258  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.268  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.278  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.278  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.278  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.278  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.288  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.288  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.288  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.288  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.298  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.308  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.318  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.318  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.318  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.318  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.328  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.338  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.348  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.358  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.368  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.378  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.378  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.378  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.378  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.388  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.398  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.408  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.408  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.408  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.408  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.408  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.418  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.418  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.418  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.418  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.418  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.428  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.438  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 E ZipFileCache: init failed when open zip file.
07-07 15:48:09.448  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:48:09.458  8122  8122 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-07 15:48:09.458  8122  8122 I art     : Can not find class: Landroid/widget/ViewStub;
07-07 15:48:09.458  8122  8122 I art     : Can not find class: Landroid/webkit/ViewStub;
07-07 15:48:09.458  8122  8122 I art     : Can not find class: Landroid/app/ViewStub;
07-07 15:48:09.488  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:48:09.488  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:48:09.698  3622  3622 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 15:48:09.708  3622  3622 I PhoneStatusBar: shouldTranslucent:true
07-07 15:48:09.708  3622  3622 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 15:48:09.758  8122  8175 I OpenGLRenderer: Initialized EGL, version 1.4
07-07 15:48:09.818  3109  3169 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s131ms (total +1s204ms)
07-07 15:48:09.818  8122  8122 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-07 15:48:09.938  8122  8122 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-07 15:48:09.938  8122  8122 I chromium: 
,07-07 15:48:10.088  8122  8186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
,07-07 15:48:10.108  8122  8186 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 15:48:10.108  8122  8186 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 15:48:10.108  8122  8186 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 15:48:10.118  8122  8186 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,07-07 15:48:10.118  8122  8186 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 15:48:10.148  8122  8122 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 15:48:10.608  8122  8189 W jxcore-log: Initializing JXcore engine
07-07 15:48:10.608  8122  8189 W jxcore-log: JXcore engine is ready
,07-07 15:48:10.668  8122  8189 W jxcore-log: Starting JXcore engine
,07-07 15:48:10.778  8122  8189 W jxcore-log: Platform android
07-07 15:48:10.778  8122  8189 W jxcore-log: 
07-07 15:48:10.778  8122  8189 W jxcore-log: Process ARCH arm
07-07 15:48:10.778  8122  8189 W jxcore-log: 
,07-07 15:48:10.988  8122  8189 I jxcore-log: JXcore Cordova bridge is ready!
07-07 15:48:10.988  8122  8189 I jxcore-log: 
,07-07 15:48:10.988  8122  8189 W jxcore-log: JXcore engine is started
,07-07 15:48:10.988  8122  8186 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 15:48:10.998  8122  8122 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 15:48:11.008  8122  8189 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 15:48:11.008  8122  8189 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 15:48:11.008  8122  8122 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-07 15:48:11.008  8122  8122 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 15:48:11.128  8122  8186 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 117ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 15:48:11.128  4246  4534 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 15:48:11.138  4246  4534 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-07 15:48:11.138  8122  8122 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 15:48:11.138  8122  8122 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 15:48:11.138  8122  8122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 15:48:11.138  8122  8122 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 15:48:11.138  8122  8122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 15:48:11.138  4246  4341 I HwSystemManager: HoldService:uid:10084 pid:7274 died
07-07 15:48:11.138  4246  4341 I HwSystemManager: HoldService:oldVersionKey:10084,7274
07-07 15:48:11.138  4246  4534 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-07 15:48:11.138  3109  3533 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 15:48:11.138  3109  3533 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 7274
07-07 15:48:11.138  3109  3533 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 7274
,07-07 15:48:11.148  4246  4477 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-07 15:48:11.148  8122  8122 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-07 15:48:11.148  8122  8122 W ScreenOrientationListener: Removing an inexistent observer!
,07-07 15:48:11.268  8191  8191 I appproc : CLASSPATH=/system/framework/pm.jar
07-07 15:48:11.268  8191  8191 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-07 15:48:11.268  8191  8191 I appproc : app_process:number,4,0
,07-07 15:48:11.278  8191  8191 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-07 15:48:11.408  8191  8191 I         : power log dlsym ok
,07-07 15:48:11.458  8191  8191 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-07 15:48:11.458  8191  8191 I android_hardware_fm.cpp: ========64bit long size = 8
07-07 15:48:11.458  8191  8191 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-07 15:48:11.458  8191  8191 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-07 15:48:11.458  8191  8191 I fm_hisi : 
07-07 15:48:11.458  8191  8191 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-07 15:48:11.458  8191  8191 I fm_hisi : 
07-07 15:48:11.458  8191  8191 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-07 15:48:11.458  8191  8191 I fm_hisi : 
07-07 15:48:11.458  8191  8191 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-07 15:48:11.498  3109  3753 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-07 15:48:11.498  3109  3753 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-07 15:48:11.618  3109  3577 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-07 15:48:11.618  4246  4534 I HwSystemManager: HoldService:uid:10072 pid:8122 died
07-07 15:48:11.618  4246  4534 I HwSystemManager: HoldService:oldVersionKey:10072,8122
07-07 15:48:11.618  3109  3961 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 15:48:11.618  3109  3961 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 8122
07-07 15:48:11.618  3109  3961 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 8122
07-07 15:48:11.618  4246  4537 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
,07-07 15:48:11.668  7428  7428 I art     : Explicit concurrent mark sweep GC freed 7967(600KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 850us total 44.985ms
,07-07 15:48:11.668  3109  3188 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-07 15:48:11.668  3109  3188 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-07 15:48:11.678  3109  3188 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-07 15:48:11.688  4075  4470 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 15:48:11.688  3109  3512 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 15:48:11.698  7238  7418 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@1885da58 in the cache
,07-07 15:48:11.698  3109  3517 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-07 15:48:11.708  7238  7418 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
07-07 15:48:11.708  4246  4401 I HwSystemManager: aor:Network Stats Updated
07-07 15:48:11.708  4246  4401 I HwSystemManager: aoi:onNetworkStatsUpdated
07-07 15:48:11.708  4246  4402 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 15:48:11.708  7238  7418 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-07 15:48:11.718  7238  7418 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@3194f7b1 in the cache
,07-07 15:48:11.738  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 15:48:11.738  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 15:48:11.738  4246  4402 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 15:48:11.738  4246  4402 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-07 15:48:11.738  4246  4402 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-07 15:48:11.738  4246  4402 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 15:48:11.758  7238  7418 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-07 15:48:11.758  7238  7418 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-07 15:48:11.758  7238  7418 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-07 15:48:11.758  7238  7418 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-07 15:48:11.758  7238  7418 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@3cb9496 in the cache
,07-07 15:48:11.758  7238  7418 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@26f82817 in the cache
,07-07 15:48:11.768  3109  3156 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-07 15:48:11.768  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 15:48:11.768  7238  7418 E ExternalAccountType: Unsupported attribute readOnly
,07-07 15:48:11.768  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 15:48:11.768  4246  4402 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 15:48:11.768  4246  4402 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-07 15:48:11.768  4246  4402 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-07 15:48:11.768  4246  4402 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-07 15:48:11.778  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-07 15:48:11.778  5962  5962 I art     : Explicit concurrent mark sweep GC freed 32160(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 738us total 143.915ms
07-07 15:48:11.778  5962  5962 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 15:48:11.778  5962  5962 I HwSystemManager: HsmPackageManager:replacing:false
07-07 15:48:11.778  5962  5962 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-07 15:48:11.778  5962  5962 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-07 15:48:11.778  4246  4402 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-07 15:48:11.778  4246  4402 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-07 15:48:11.778  4246  4402 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
07-07 15:48:11.778  7238  7418 I AccountTypeManager: AccountManager, account size is: 2
07-07 15:48:11.778  4246  4402 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
07-07 15:48:11.788  7238  7418 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 98ms(wall) 21ms(cpu)
,07-07 15:48:11.798  3891  3891 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-07 15:48:11.808  4246  4246 I art     : Explicit concurrent mark sweep GC freed 104370(6MB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/23MB, paused 1.608ms total 174.545ms
07-07 15:48:11.808  4246  4246 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 15:48:11.808  4246  4246 I HwSystemManager: HsmPackageManager:replacing:false
07-07 15:48:11.808  4246  4246 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-07 15:48:11.808  4246  4246 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-07 15:48:11.818  4246  4246 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-07 15:48:11.828  3962  3962 I art     : Explicit concurrent mark sweep GC freed 74561(4MB) AllocSpace objects, 119(9MB) LOS objects, 38% free, 25MB/41MB, paused 2.791ms total 190.794ms
,07-07 15:48:11.828  3962  3962 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-07 15:48:11.828  3962  3962 I HwLauncher: Model replacing = false package = com.test.thalitest
,07-07 15:48:11.828  3962  3962 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
,07-07 15:48:11.828  3962  3962 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
,07-07 15:48:11.838  3962  4074 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-07 15:48:11.838  3962  3962 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
,07-07 15:48:11.838  3962  4091 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-07 15:48:11.838  3962  3962 E HideAppsPagedView: removeItems begin 
,07-07 15:48:11.838  3962  3962 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
,07-07 15:48:11.838  3962  3962 E HideAppsPagedView: removeItems end 
07-07 15:48:11.848  3962  4091 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
,07-07 15:48:11.848  3962  4091 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-07 15:48:11.848  3962  4091 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-07 15:48:11.848  3962  4091 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-07 15:48:11.848  3962  4091 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-07 15:48:11.858  3962  3962 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
07-07 15:48:11.858  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-07 15:48:11.858  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-07 15:48:11.868  3962  3962 I HwLauncher: Launcher onStart()
07-07 15:48:11.868  3962  3962 I HwLauncher: Launcher dynamicIconsRegister
07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicUpdater registerReceiver
,07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicUpdater call updateFolder
07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicUpdater registerReceiver
,07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicUpdater call updateFolder
07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-07 15:48:11.868  3962  3962 I HwLauncher: DynamicUpdater registerReceiver
07-07 15:48:11.868  3962  4074 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-07 15:48:11.878  3962  3962 I HwLauncher: DynamicUpdater call updateFolder
07-07 15:48:11.878  3962  4074 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-07 15:48:11.878  3962  3962 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-07 15:48:11.878  3962  4074 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-07 15:48:11.878  3962  3962 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-07 15:48:11.878  3962  3962 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
07-07 15:48:11.878  3962  4074 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-07 15:48:11.878  3962  3962 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-07 15:48:11.878  3962  3962 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-07 15:48:11.878  3962  3962 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-07 15:48:11.878  3962  3962 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-07 15:48:11.878  3962  3962 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-07 15:48:11.878  3962  3962 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 15:48:11.878  3962  3962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 15:48:11.878  3962  3962 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 15:48:11.878  3962  3962 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-07 15:48:11.878  3962  3962 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 15:48:11.878  3962  3962 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 15:48:11.878  3962  3962 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 15:48:11.878  3962  3962 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-07 15:48:11.878  3962  4074 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
07-07 15:48:11.878  3962  3962 W System.err: java.lang.NullPointerException: null receiver
,07-07 15:48:11.888  3962  4074 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-07 15:48:11.888  3962  3962 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-07 15:48:11.888  3962  3962 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-07 15:48:11.888  3962  3962 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-07 15:48:11.888  3962  3962 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-07 15:48:11.888  3962  3962 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 15:48:11.888  3962  3962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 15:48:11.888  3962  3962 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 15:48:11.888  3962  3962 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-07 15:48:11.888  3962  3962 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 15:48:11.888  3962  3962 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 15:48:11.888  3962  3962 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 15:48:11.888  3962  3962 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-07 15:48:11.888  3962  3962 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
,07-07 15:48:11.888  3962  4074 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-07 15:48:11.888  3962  3962 E HideAppsPagedView: removeHideApps  begin 
07-07 15:48:11.888  3962  3962 E HideAppsPagedView: removeHideApps  end 
07-07 15:48:11.888  3962  3962 E HideAppsPagedView:  syncPages mCurrentPage = 0
07-07 15:48:11.888  3962  4074 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-07 15:48:11.888  6181  6181 I art     : Explicit concurrent mark sweep GC freed 15876(979KB) AllocSpace objects, 3(60KB) LOS objects, 25% free, 23MB/31MB, paused 2.320ms total 266.365ms
07-07 15:48:11.888  3962  3962 E ZipFileCache: init failed when open zip file.
07-07 15:48:11.898  3962  3962 E ZipFileCache: init failed when open zip file.
07-07 15:48:11.898  3962  3962 E ZipFileCache: init failed when open zip file.
07-07 15:48:11.898  3962  3962 E ZipFileCache: init failed when open zip file.
07-07 15:48:11.898  3962  3962 E ZipFileCache: init failed when open zip file.
07-07 15:48:11.898  3962  3962 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-07 15:48:11.898  3962  3962 E HideAppsPagedView:  createAddIcon count = 0
07-07 15:48:11.908  3109  3156 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
07-07 15:48:11.908  3962  3962 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
07-07 15:48:11.908  3962  3962 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
07-07 15:48:11.908  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-07 15:48:11.908  3962  3962 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-07 15:48:11.928  3962  3962 I HwLauncher: DynamicUpdater call updateFolder
,07-07 15:48:11.968  3109  3109 I art     : Explicit concurrent mark sweep GC freed 70186(5MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 28MB/43MB, paused 2.342ms total 334.731ms
07-07 15:48:11.968  3109  3188 I art     : WaitForGcToComplete blocked for 289.555ms for cause Explicit
,07-07 15:48:11.988  8237  8237 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-07 15:48:11.988  8214  8214 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-07 15:48:11.988  8214  8214 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-07 15:48:12.018  8237  8257 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-07 15:48:12.028  8237  8237 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-07 15:48:12.068  3962  3962 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,07-07 15:48:12.068  3962  4074 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-07 15:48:12.068  3962  4074 I HwLauncher:  stringArray[] [unknown]
,07-07 15:48:12.088  3109  3505 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-07 15:48:12.088  3109  3505 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-07 15:48:12.088  3109  3505 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-07 15:48:12.088  3109  3505 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-07 15:48:12.088  3109  3505 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 15:48:12.088  3109  3505 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 15:48:12.088  3109  3505 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 15:48:12.168  3109  3188 I art     : Explicit concurrent mark sweep GC freed 7392(354KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.197ms total 208.569ms
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-07 15:48:12.188  3109  3109 E ReportTools: Can't find sReporterClazz
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-07 15:48:12.188  3109  3109 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-07 15:48:12.198  3109  3109 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-07 15:48:12.198  3109  3109 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-07 15:48:12.198  3109  3109 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-07 15:48:12.198  3109  3109 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-07 15:48:12.198  3109  3109 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-07 15:48:12.198  3109  3109 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-07 15:48:12.198  3109  3109 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 15:48:12.198  3109  3109 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 15:48:12.198  3109  3109 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-07 15:48:12.198  3109  3109 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 15:48:12.198  3109  3109 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-07 15:48:12.198  3109  3109 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-07 15:48:12.198  3109  3109 E ReportTools: This is not beta user build
,07-07 15:48:12.198  3622  3622 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 15:48:12.198  3622  3622 I PhoneStatusBar: shouldTranslucent:true
07-07 15:48:12.198  3622  3622 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-07 15:48:12.208  4246  4341 I HwSystemManager: HoldService:uid:10058 pid:7369 died
07-07 15:48:12.208  4246  4341 I HwSystemManager: HoldService:oldVersionKey:10058,7369
07-07 15:48:12.208  4246  4341 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-07 15:48:12.208  3109  3533 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 15:48:12.208  3109  3533 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 7369
07-07 15:48:12.208  3109  3533 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 7369
,07-07 15:48:12.248  3709  3709 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 15
,07-07 15:48:12.248  3109  4128 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 15
07-07 15:48:12.248  3109  3522 E WifiStateMachine:  ConnectedState what:147506 0 0
07-07 15:48:12.248  3109  3522 E WifiStateMachine:  L2ConnectedState what:147506 0 0
,07-07 15:48:12.248  3109  3522 E WifiStateMachine:  ConnectModeState what:147506 0 0
07-07 15:48:12.248  3109  3522 E WifiStateMachine:  DriverStartedState what:147506 0 0
07-07 15:48:12.248  3109  3522 E WifiStateMachine:  SupplicantStartedState what:147506 0 0
,07-07 15:48:12.398  4246  4537 I HwSystemManager: HoldService:uid:10007 pid:7633 died
07-07 15:48:12.398  4246  4537 I HwSystemManager: HoldService:oldVersionKey:10007,7633
07-07 15:48:12.398  4246  4535 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10007
07-07 15:48:12.398  3109  3961 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 15:48:12.398  3109  3961 I MediaProcessHandler: processOp opType: 1, uid: 10007, pid: 7633
07-07 15:48:12.398  3109  3961 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10007, pid: 7633
,07-07 15:48:12.408  4246  4246 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.408  4246  4246 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-07 15:48:12.418  4246  4246 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@126e433c
,07-07 15:48:12.418  4246  4246 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
07-07 15:48:12.418  4246  8308 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
07-07 15:48:12.418  5962  5962 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.418  5962  5962 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@846b680
07-07 15:48:12.428  5962  5962 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-07 15:48:12.428  5962  8310 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-07 15:48:12.428  5962  5962 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,07-07 15:48:12.428  5962  8311 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-07 15:48:12.428  5962  8311 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.428  5962  8311 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
,07-07 15:48:12.428  5962  8311 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.428  5962  8311 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #8,5,main], current active tasksize:2, queue size:0
07-07 15:48:12.428  5962  7783 I HwSystemManager: ProtectAppControl:handleMessage:7
,07-07 15:48:12.428  5962  5962 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.428  4246  4276 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
,07-07 15:48:12.428  5962  7783 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
,07-07 15:48:12.438  4246  4246 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-07 15:48:12.438  4246  4246 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-07 15:48:12.438  4246  4246 E HwSystemManager: AppCleanUpService:msg is 1
,07-07 15:48:12.438  5962  5962 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-07 15:48:12.438  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.438  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
07-07 15:48:12.438  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-07 15:48:12.438  5962  8312 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-07 15:48:12.438  5962  8312 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.438  5962  8312 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.438  5962  8312 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #9,5,main], current active tasksize:2, queue size:0
,07-07 15:48:12.478  4246  4537 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 15:48:12.478  4246  4537 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-07 15:48:12.478  4246  7223 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-07 15:48:12.478  4246  7223 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 15:48:12.478  4246  7223 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-07 15:48:12.478  4246  8308 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.478  4246  8308 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
07-07 15:48:12.478  4246  8308 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
07-07 15:48:12.478  5962  5962 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
07-07 15:48:12.478  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-07 15:48:12.478  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-07 15:48:12.478  5962  5962 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
07-07 15:48:12.478  4246  4535 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-07 15:48:12.478  4246  4535 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-07 15:48:12.478  4246  4535 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-07 15:48:12.488  3622  3622 I PhoneStatusBar: notification pkg =com.android.settings
07-07 15:48:12.488  3622  3622 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-07 15:48:12.488  3622  3622 I PhoneStatusBar: notification pkg =android
07-07 15:48:12.488  3622  3622 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-07 15:48:12.488  4246  8313 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
07-07 15:48:12.498  5962  8314 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
07-07 15:48:12.498  5962  8314 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
07-07 15:48:12.508  5962  8316 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
07-07 15:48:12.508  5962  8310 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-07 15:48:12.508  5962  8310 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
07-07 15:48:12.508  5962  5962 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
07-07 15:48:12.518  5962  8317 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
07-07 15:48:12.518  5962  5962 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-07 15:48:12.518  5962  8317 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-07 15:48:12.568  4246  4246 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@126e433c
,07-07 15:48:12.638  5962  8310 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-07 15:48:12.638  4246  4271 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM history_table WHERE packageName=?] disk I/O error - SQLITE_IOERR_LOCK
,07-07 15:48:12.648  4246  4271 E DatabaseUtils: Writing exception to parcel
07-07 15:48:12.648  4246  4271 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at pf.delete(Unknown Source)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at com.huawei.permissionmanager.db.PermissionDataProvider.delete(Unknown Source)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
07-07 15:48:12.648  4246  4271 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,07-07 15:48:12.648  5962  8310 E HwSystemManager: HsmIntentService:invoke error, InvocationTargetException:java.lang.reflect.InvocationTargetException
07-07 15:48:12.648  5962  8310 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-07 15:48:12.648  5962  8310 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #7,5,main], current active tasksize:1, queue size:0
07-07 15:48:12.648  5962  8310 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-07 15:48:12.698  5962  5962 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@846b680
,07-07 15:48:12.808  4246  4341 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10010
07-07 15:48:12.808  3109  3131 E HsmCoreServiceImpl: onTransact in code is: 102
07-07 15:48:12.808  3109  3131 I MediaProcessHandler: processOp opType: 1, uid: 10010, pid: 7455
07-07 15:48:12.808  3109  3131 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10010, pid: 7455
07-07 15:48:12.808  4246  7223 I HwSystemManager: HoldService:uid:10010 pid:7455 died
07-07 15:48:12.808  4246  7223 I HwSystemManager: HoldService:oldVersionKey:10010,7455

```
