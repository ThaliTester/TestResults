#### Test 50650278654db8c_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2504): GC_CONCURRENT freed 276K, 2% free 17579K/17888K, paused 2ms+1ms, total 13ms
D/dalvikvm( 2504): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2504): GC_CONCURRENT freed 231K, 2% free 17841K/18104K, paused 1ms+3ms, total 15ms
--------- beginning of /dev/log/system
I/ActivityManager(  757): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2545 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  757): Killing 1907:com.google.android.exchange/u0a37 (adj 15): empty #17
D/dalvikvm( 2504): GC_CONCURRENT freed 422K, 3% free 17873K/18328K, paused 1ms+2ms, total 16ms
D/dalvikvm( 2504): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2504): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2504): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2504): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2504): VFY: unable to resolve instance field 36
D/dalvikvm( 2504): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2504): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2504): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2504): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2504): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2504): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2504): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428f3e10
D/dalvikvm( 2504): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428f3e10
D/dalvikvm( 2504): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428f3e10, skipping init
D/dalvikvm( 2504): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428f3e10
D/dalvikvm( 2504): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428f3e10
V/JNIHelp ( 2504): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2504): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428f3e10
D/dalvikvm( 2504): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428f3e10
D/dalvikvm( 2504): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428f3e10
D/dalvikvm( 2504): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428f3e10
D/dalvikvm( 2504): GC_CONCURRENT freed 358K, 3% free 17937K/18328K, paused 2ms+2ms, total 15ms
W/Quickoffice( 2545): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2545): Loading recent documents list
I/ProviderInstaller( 2504): Installed default security provider GmsCore_OpenSSL
D/Quickoffice( 2545): The number of lines present in  /proc/mount 21
D/Quickoffice( 2545): Parsing the storagedefinition.xml.
D/Quickoffice( 2545): # of Storagedefinitions - 35
D/Quickoffice( 2545): The # of storage definitions available - 35
D/Quickoffice( 2545): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2545): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2545): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2545): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2545): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2545): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2545): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2545): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2545): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2545): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2545): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2545): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2545): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2545): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2545): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2545): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2545): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2545): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2545): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2545): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2545): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2545): Build properties are not configured for this storage definition.
D/Quickoffice( 2545): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2545): The # of mounts identified -  1
I/ActivityManager(  757): Killing 1958:com.google.android.apps.maps/u0a57 (adj 15): empty #17
D/dalvikvm( 2545): GC_CONCURRENT freed 254K, 2% free 16957K/17240K, paused 3ms+3ms, total 32ms
D/dalvikvm( 2545): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2545): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/com.google.android.apps.docs.quickoffice.X( 2545): Checking validity of 0 items
D/ContentResolverUtil( 2545): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2545): 0 items were valid
W/ActivityManager(  757): No permission grants found for com.quickoffice.android
W/Quickoffice( 2545): Could not load clipboard.
W/Quickoffice( 2545): Could not store clipboard.
D/ConnectivityService(  757): Sampling interval elapsed, updating statistics ..
W/SocketClient(  179): write error (Broken pipe)
D/ConnectivityService(  757): Done.
D/ConnectivityService(  757): Setting timer for 720seconds
I/Icing   ( 1293): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Icing   ( 1293): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1293): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
D/dalvikvm( 1293): GC_CONCURRENT freed 557K, 4% free 18991K/19584K, paused 2ms+1ms, total 17ms
I/Icing   ( 1293): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/AndroidRuntime( 2579): 
D/AndroidRuntime( 2579): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2579): CheckJNI is OFF
D/dalvikvm( 2579): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2579): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2579): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2579): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2579): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2579): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2579): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2579
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
D/AndroidRuntime( 2579): Shutting down VM
D/dalvikvm( 2579): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2598 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1181): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1181): mic_close
I/ActivityManager(  757): Killing 1700:com.google.android.deskclock/u0a33 (adj 15): empty #17
I/ActivityManager(  757): Killing 1984:com.google.android.youtube/u0a71 (adj 15): empty #18
I/MicroHotwordRecognitionRunner( 1181): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1181): Stopping hotword detection.
D/dalvikvm( 1181): GC_CONCURRENT freed 686K, 4% free 18479K/19196K, paused 4ms+1ms, total 76ms
F/ActivityManager(  757): Service ServiceRecord{42ee17b8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42e11b30 1984:com.google.android.youtube/u0a71} not same as in map: null
V/WebViewChromiumFactoryProvider( 2598): Binding Chromium to main looper Looper (main, tid 1) {42771678}
I/LibraryLoader( 2598): Expected native library version number "",actual native library version number ""
I/chromium( 2598): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2598): Initializing chromium process, renderers=0
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@444cbc98:true
D/BluetoothAdapter( 2598): 1115185616: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2598): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2598): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2598): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2598): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2598): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2598): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2598): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2598): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2598): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2598): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2598): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2598): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2598): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2598): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2598): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2598): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2598): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2598): Enabling debug mode 0
,W/AwContents( 2598): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +313ms
,D/JsMessageQueue( 2598): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2598): GC_CONCURRENT freed 256K, 2% free 16926K/17196K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 2598): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427750b0
,D/dalvikvm( 2598): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427750b0
,D/jxcore_app_log( 2598): JniHelper::setJavaVM(0x41710ed0), pthread_self() = 1983003024
,D/JX-Cordova( 2598): jxcore cordova android initializing
,D/dalvikvm( 2598): GC_CONCURRENT freed 214K, 2% free 17224K/17468K, paused 1ms+1ms, total 9ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 156K, 2% free 17571K/17768K, paused 0ms+1ms, total 10ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 154K, 2% free 17914K/18112K, paused 1ms+2ms, total 12ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 151K, 2% free 18257K/18456K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 159K, 2% free 18598K/18808K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 181K, 2% free 19026K/19264K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 227K, 2% free 19548K/19836K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 285K, 2% free 20181K/20532K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 334K, 2% free 20964K/21376K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 393K, 3% free 21881K/22364K, paused 1ms+2ms, total 31ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 1224K, 6% free 22279K/23576K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 1416K, 7% free 22541K/24172K, paused 21ms, total 21ms
D/dalvikvm( 2598): GC_FOR_ALLOC freed 46K, 7% free 22546K/24172K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2598): Grow heap (frag case) to 22.743MB for 733480-byte allocation
,D/dalvikvm( 2598): GC_FOR_ALLOC freed <1K, 7% free 23262K/24892K, paused 33ms, total 33ms
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 1313K, 9% free 22773K/24892K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2598): Grow heap (frag case) to 23.315MB for 1100216-byte allocation
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 15K, 9% free 23832K/25968K, paused 20ms, total 20ms
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 1945K, 11% free 23181K/25968K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2598): Grow heap (frag case) to 24.238MB for 1650320-byte allocation
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 1081K, 15% free 23711K/27580K, paused 20ms, total 20ms
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 1971K, 14% free 23818K/27580K, paused 25ms, total 25ms
,I/dalvikvm-heap( 2598): Grow heap (frag case) to 25.647MB for 2475476-byte allocation
,D/dalvikvm( 2598): GC_CONCURRENT freed 0K, 13% free 26235K/30000K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 4649K, 18% free 24742K/30000K, paused 1ms+7ms, total 49ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 45ms
,I/dalvikvm-heap( 2598): Grow heap (frag case) to 27.730MB for 3713210-byte allocation
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 2453K, 23% free 25915K/33628K, paused 33ms, total 33ms
,D/dalvikvm( 2598): GC_CONCURRENT freed 228K, 23% free 25936K/33628K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 2598): GC_FOR_ALLOC freed 836K, 24% free 25676K/33628K, paused 21ms, total 21ms
,W/jxcore-log( 2598): Initializing JXcore engine
,W/jxcore-log( 2598): JXcore engine is ready
,D/dalvikvm( 2598): GC_CONCURRENT freed 5409K, 31% free 23238K/33628K, paused 1ms+1ms, total 19ms
,D/dalvikvm( 2598): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/jxcore-log( 2598): Starting JXcore engine
,W/jxcore-log( 2598): Platform android
W/jxcore-log( 2598): 
,W/jxcore-log( 2598): Process ARCH arm
W/jxcore-log( 2598): 
,I/jxcore-log( 2598): JXcore Cordova bridge is ready!
I/jxcore-log( 2598): 
,W/jxcore-log( 2598): JXcore engine is started
,I/chromium( 2598): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2598): Toggling radios to true
I/jxcore-log( 2598): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  757): Message: 1
,D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  757): setWifiEnabled: true pid=2598, uid=10108
,I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2662 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
,D/SoftapController(  179): Softap fwReload - Ok
,I/jxcore-log( 2598): Radios toggled
I/jxcore-log( 2598): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2598): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2598): 
,I/jxcore-log( 2598): Perf Test app loaded loaded
I/jxcore-log( 2598): 
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,I/Choreographer( 2598): Skipped 59 frames!  The application may be doing too much work on its main thread.
,D/WifiMonitor(  757): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  757): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2676 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/chromium( 2598): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2598): check test folder
I/jxcore-log( 2598): 
,I/jxcore-log( 2598): found test : ./testFindPeers.js
I/jxcore-log( 2598): 
,I/wpa_supplicant( 2675): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 2662): Adding HeadsetService
,D/AdapterServiceConfig( 2662): Adding A2dpService
D/AdapterServiceConfig( 2662): Adding HidService
D/AdapterServiceConfig( 2662): Adding HealthService
D/AdapterServiceConfig( 2662): Adding PanService
,D/AdapterServiceConfig( 2662): Adding GattService
,D/AdapterServiceConfig( 2662): Adding BluetoothMapService
,I/jxcore-log( 2598): found test : ./testSendData.js
I/jxcore-log( 2598): 
,D/BluetoothAdapterService( 2662): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService(  757): Message: 20
,D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4436c6d8:true
,D/BluetoothAdapterState( 2662): make
,I/bluedroid( 2662): init
,I/BluetoothAdapterState( 2662): Entering OffState
,I/bte_conf( 2662): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/wpa_supplicant( 2675): rfkill: Cannot open RFKILL control device
,I/bluedroid( 2662): get_profile_interface socket
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
I/GKI_LINUX( 2662): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 2662): Address is:34:FC:EF:11:B1:66
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:1 len:7
,I/bluedroid( 2662): config_hci_snoop_log
D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterProperties( 2662): Name is: Nexus 5
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterState( 2662): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2662): Setting state to 11
I/BluetoothAdapterState( 2662): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  757): Message: 20
D/BluetoothAdapterService( 2662): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44359b00:true
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2662): make
,I/BluetoothBondStateMachine( 2662): StableState(): Entering Off State
,D/BluetoothManagerService(  757): Message: 30
,D/HeadsetService( 2662): Received start request. Starting profile...
D/BluetoothHeadset(  757): Proxy object connected
D/BluetoothHeadset( 1004): Proxy object connected
,D/BluetoothHeadset( 1004): Proxy object connected
I/BluetoothHeadsetServiceJni( 2662): classInitNative: succeeds
,D/HeadsetStateMachine( 2662): make
,D/BluetoothHeadset( 1004): Proxy object connected
,W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/BluetoothManagerService(  757): Message: 30
I/BluetoothAdapterState( 2662): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/bluedroid( 2662): get_profile_interface handsfree
D/BluetoothA2dp(  757): Proxy object connected
D/A2dpService( 2662): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2662): classInitNative: succeeds
V/Avrcp   ( 2662): make
I/bluedroid( 2662): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 2662): classInitNative: succeeds
,D/A2dpStateMachine( 2662): make
I/bluedroid( 2662): get_profile_interface a2dp
,I/GKI_LINUX( 2662): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 2676): Adding local MAP profile
D/BluetoothMap( 2676): Create BluetoothMap proxy object
D/BluetoothManagerService(  757): Message: 30
I/BluetoothHidServiceJni( 2662): classInitNative: succeeds
D/A2dpStateMachine( 2662): Enter Disconnected: -2
D/HidService( 2662): Received start request. Starting profile...
I/bluedroid( 2662): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 2662): classInitNative: succeeds
,D/HealthService( 2662): Received start request. Starting profile...
,I/bluedroid( 2662): get_profile_interface health
I/BluetoothPanServiceJni( 2662): classInitNative(L105): succeeds
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothPan(  757): BluetoothPAN Proxy object connected
D/PanService( 2662): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 2662): initializeNative(L110): pan
,I/bluedroid( 2662): get_profile_interface pan
,D/BluetoothTethering(  757): got CMD_CHANNEL_HALF_CONNECTED
,D/LocalBluetoothProfileManager( 2676): LocalBluetoothProfileManager construction complete
,I/BtGatt.JNI( 2662): classInitNative(L684): classInitNative: Success!
W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BtGatt.DebugUtils( 2662): handleDebugAction() action=null
D/BtGatt.GattService( 2662): Received start request. Starting profile...
D/BtGatt.GattService( 2662): start()
I/bluedroid( 2662): get_profile_interface gatt
D/BluetoothPan( 2676): BluetoothPAN Proxy object connected
D/BluetoothMapService( 2662): Received start request. Starting profile...
D/BluetoothMapService( 2662): start()
D/PanProfile( 2676): Bluetooth service connected
D/BluetoothInputDevice( 2676): Proxy object connected
D/HidProfile( 2676): Bluetooth service connected
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2712 uid=10052 gids={50052, 3003, 1028, 1015}
,D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 2662): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.hdp.HealthService
,I/ActivityManager(  757): Killing 1885:com.google.android.email/u0a36 (adj 15): empty #17
D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 2662): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2662): enable
D/BluetoothMap( 2676): Proxy object connected
D/MapProfile( 2676): Bluetooth service connected
D/BluetoothMap( 2676): getConnectedDevices()
I/bt_hci_bdroid( 2662): init
D/BluetoothMap( 2676): Bluetooth is Not enabled
I/bt_vendor( 2662): init
I/bt_vnd_conf( 2662): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2662): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt_hci_bdroid( 2662): bt_hc_worker_thread started
,I/GKI_LINUX( 2662): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 2662): btu_task pending for preload complete event
,I/bt_userial_vendor( 2662): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2662): device fd = 65 open
,I/bt_hwcfg( 2662): bt vendor lib: set UART baud 4000000
,D/dalvikvm(  757): GC_EXPLICIT freed 22449K, 53% free 25981K/55200K, paused 2ms+5ms, total 105ms
,D/bt_hwcfg( 2662): Chipset BCM4335C0
,D/bt_hwcfg( 2662): Target name = [BCM4335C0]
,I/bt_hwcfg( 2662): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BroadcastQueue(  757): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
D/dalvikvm( 2712): GC_CONCURRENT freed 206K, 2% free 16925K/17160K, paused 2ms+3ms, total 23ms
,I/ActivityManager(  757): Killing 2084:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  757): Service ServiceRecord{42ee30a8 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42dc1018 2084:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42ecabb8 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42dc1018 2084:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42e97658 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42dc1018 2084:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42de5b60 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42dc1018 2084:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42de3f48 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42dc1018 2084:com.google.android.music:main/u0a58} not same as in map: null
,I/bt_hwcfg( 2662): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2662): Settlement delay -- 100 ms
,I/bt_hwcfg( 2662): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2662): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2662): vendor lib fwcfg completed
,I/bt-btu  ( 2662): btu_task received preload complete event
,I/        ( 2662): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2662): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2662): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2662): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2662): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2662): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2662): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2662): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2662): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2662): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2662): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2662): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2662): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2662): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 2662): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2662): BTM_SecRegister:p_cb_info->p_le_callback == 0x750c8f8d 
,E/bt-btm  ( 2662): BTM_SecRegister: btm_cb.api.p_le_callback = 0x750c8f8d 
,E/bt-btif ( 2662): Calling BTA_HhEnable
E/bt-btif ( 2662): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2662): Address is:34:FC:EF:11:B1:66
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothAdapterProperties( 2662): Name is: Nexus 5
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 2662): Scan Mode:20
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2662): Discoverable Timeout:120
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:8 len:42
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2662): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 2662): Adding bonded device:F8:95:C7:87:85:54
D/BluetoothAdapterProperties( 2662): Adding bonded device:00:F4:6F:30:E0:6C
D/BluetoothAdapterProperties( 2662): Adding bonded device:E0:DB:10:1F:C9:5E
D/BluetoothAdapterProperties( 2662): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 2662): Adding bonded device:F8:95:C7:87:3C:51
D/BluetoothAdapterProperties( 2662): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:3 len:48
E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,E/BluetoothRemoteDevices( 2662): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
I/bt_hwcfg( 2662): SCO PCM configure {0, 4, 0, 0, 0}
I/bte_conf( 2662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 2662): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 2662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothPanServiceJni( 2662): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 2662): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2662): ScanMode =  20
D/BluetoothAdapterProperties( 2662): State =  11
D/BluetoothAdapterProperties( 2662): Setting state to 12
I/BluetoothAdapterState( 2662): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 2662): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 10 receivers.
D/BluetoothPan(  757): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/dalvikvm( 2662): GC_CONCURRENT freed 274K, 2% free 16830K/17136K, paused 3ms+1ms, total 20ms
I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 2662): Entering On State
D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1115166856)( 2662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2662): Scan Mode:21
,I/BluetoothAdapterProperties( 2662): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2662): Discoverable Timeout:120
,D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/BluetoothPbap( 2676): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 2662): getBondedDevices: length=7
,D/BluetoothMap( 2676): onBluetoothStateChange: up=true
W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
,W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap$1.onBluetoothStateChange:132 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,D/BluetoothPan( 2676): onBluetoothStateChange(on) call bindService
,D/BluetoothInputDevice( 2676): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1115166856)( 2662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2662): getBondedDevices: length=7
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
D/BluetoothMapService( 2662): onReceive
D/BluetoothMapService( 2662): STATE_ON
D/BluetoothMapService( 2662): Map Service startRfcommSocketListener
E/bt_h4   ( 2662): vendor lib postload completed
D/BluetoothManagerService(  757): Message: 40
D/BluetoothAdapterService(1115166856)( 2662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2662): getBondedDevices: length=7
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LocalBluetoothProfileManager( 2676): Adding local A2DP profile
D/BluetoothMapService( 2662): Map Service initSocket
D/BluetoothManagerService(  757): Message: 30
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2662): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2662): SOCK FLAG = 1 ***********************
,D/BluetoothMapService( 2662): Accepting socket connection...
,D/LocalBluetoothProfileManager( 2676): Adding local HEADSET profile
,D/BluetoothManagerService(  757): Message: 30
W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/Tethering(  757): sendTetherStateChangedBroadcast 1, 0, 0
,D/BluetoothAdapterService(1115166856)( 2662): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2662): getBondedDevices: length=7
W/SocketClient(  179): write error (Broken pipe)
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(58:2A:F7:ED:96:BE)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,I/wpa_supplicant( 2675): rfkill: Cannot open RFKILL control device
,D/dalvikvm( 2676): GC_CONCURRENT freed 274K, 2% free 16826K/17132K, paused 2ms+1ms, total 14ms
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(F8:95:C7:87:3C:51)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(E0:DB:10:1F:C9:5E)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(F8:95:C7:87:85:54)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(F4:F1:E1:5C:3B:E2)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(08:EC:A9:50:76:27)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothMap( 2676): getConnectedDevices()
,D/BluetoothMap( 2676): getConnectionState(00:F4:6F:30:E0:6C)
,D/MapProfile( 2676): getConnectionStatus: status is: 0
,D/BluetoothA2dp( 2676): Proxy object connected
,D/A2dpProfile( 2676): Bluetooth service connected
W/ContextImpl( 2676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothHeadset( 2676): Proxy object connected
,D/HeadsetProfile( 2676): Bluetooth service connected
D/DockEventReceiver( 2676): finishStartingService: stopping service
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2662): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2662): SOCK FLAG = 1 ***********************
,D/BluetoothPbap( 2676): Proxy object connected
,D/PbapServerProfile( 2676): Bluetooth service connected
,D/AuthorizationBluetoothService( 1130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1130): Proximity feature is not enabled.
W/BroadcastQueue(  757): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2662): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2662): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 2662): Accept thread started.
,D/WifiConfigStore(  757): Loading config and enabling all networks
,W/Settings( 1920): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  757): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 2675): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant( 2675): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2675): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2675): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/WifiStateMachine(  757): VerifyingLinkState enter
,D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
,D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b54a58
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2598): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 2598): 
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1181): GC_CONCURRENT freed 1096K, 7% free 17908K/19196K, paused 2ms+5ms, total 22ms
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  757): Setting time of day to sec=1450201664
,W/        (  757): Unable to set rtc to 1450201664: Invalid argument
,I/SystemUpdateService( 1293): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1293): onCreate
,D/SystemUpdateService( 1293): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/dalvikvm( 2282): GC_CONCURRENT freed 317K, 2% free 17446K/17796K, paused 6ms+1ms, total 36ms
,I/SystemUpdateService( 1293): active receiver: enabled
,I/SystemUpdateService( 1293): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1293): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1293): now status is 0 (complete)
I/SystemUpdateService( 1293): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1293): file has been verified
,I/SystemUpdateService( 1293): OTA package size = 2571501
,I/SystemUpdateService( 1293): showing system update notification
,D/GpsLocationProvider(  757): NTP server returned: 1450201661321 (Tue Dec 15 18:47:41 CET 2015) reference: 87861 certainty: 33 system time offset: -3047
,I/dalvikvm( 1293): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1293): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1293): VFY: replacing opcode 0x6e at 0x003d
,I/iu.SyncManager( 1293): SYNC; picasa accounts
,D/NetworkLogImpl( 1293): Loaded NetworkSpeedPredictor
,E/Auth.Api.Credentials( 1293): [CredentialSyncAdapter] Unknown sync event.
,I/iu.Environment( 1293): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1293): onDestroy
,I/iu.UploadsManager( 1293): num queued entries: 0
,E/ActivityThread( 1293): Failed to find provider info for com.android.contacts.metadata
I/iu.UploadsManager( 1293): num updated entries: 0
I/iu.SyncManager( 1293): NEXT; no task
,I/ActivityManager(  757): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2872 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20875, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 91020, reason: UserStart
,I/Babel   ( 1920): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1130): GCM config loaded
,D/dalvikvm( 1130): GC_CONCURRENT freed 390K, 4% free 17936K/18604K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 1293): GC_CONCURRENT freed 562K, 4% free 19076K/19668K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2872): VFY: unable to resolve instance field 68
D/dalvikvm( 2872): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2872): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2872): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2872): VFY: unable to resolve instance field 68
,D/dalvikvm( 2872): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2872): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2872): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2872): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2872): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/dalvikvm(  984): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  984): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  984): VFY: replacing opcode 0x6e at 0x003d
I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2906 uid=10033 gids={50033, 1028}
,V/AlarmClock( 2906): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 2282): GC_CONCURRENT freed 256K, 2% free 17617K/17904K, paused 1ms+1ms, total 15ms
,I/AlarmClock( 2906): Displaying next alarm time: ''
,V/AlarmClock( 2906): AlarmInitReceiver finished
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2923 uid=10068 gids={50068}
,D/dalvikvm( 2923): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4277abe0, skipping init
D/TimeService( 2923): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201664835
D/        ( 2923): TimeServiceNative: User Time to be set is 1450201664835
D/QC-time-services( 2923): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2923): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2923): Lib:time_genoff_operation: pargs->ts_val = 1450201664835
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2923): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450201664835
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1450201664835, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/4/71 11:52:53
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 34516373000
D/QC-time-services(  198): Daemon:new time 1450201664835 
D/QC-time-services(  198): Daemon: delta 1415685291835 genoff 1415685291835 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685291835 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
I/ActivityManager(  757): Killing 1738:com.google.android.gm/u0a41 (adj 15): empty #17
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685291835 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1134236864835
,E/QC-time-services( 2923): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1293): Checkin interval check for package: unspecified last checkin: 1450186148736 min interval config: 0 actual interval: 15516128
,I/ActivityManager(  757): Killing 2425:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  757): Killing 2263:android.process.acore/u0a3 (adj 15): empty #17
,D/dalvikvm(  984): GC_CONCURRENT freed 506K, 4% free 18743K/19352K, paused 7ms+3ms, total 28ms
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 1615): GC_CONCURRENT freed 417K, 3% free 17430K/17880K, paused 2ms+3ms, total 24ms
,D/Finsky  ( 1615): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm(  757): GC_EXPLICIT freed 1736K, 53% free 26068K/55200K, paused 4ms+5ms, total 83ms
,D/dalvikvm( 1130): GC_CONCURRENT freed 363K, 4% free 17966K/18604K, paused 2ms+4ms, total 27ms
,I/VacuumService(  984): Vacuum at: now=1450201666896 tag=VacuumService
,D/dalvikvm( 1130): GC_CONCURRENT freed 477K, 4% free 17894K/18604K, paused 2ms+3ms, total 17ms
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.46/generate_204
W/ActivityThread(  757): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/PowerManagerService(  757): Going to sleep due to screen timeout...
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb75b8450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  757): Excessive delay in blankDisplay() while turning screen off: 292ms
,V/KeyguardServiceDelegate(  757): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42de5750)
,V/KeyguardServiceDelegate(  757): **** SHOWN CALLED ****
I/WindowManager(  757): No lock screen! windowToken=null
,D/dalvikvm( 1004): GC_CONCURRENT freed 345K, 3% free 17066K/17436K, paused 2ms+2ms, total 19ms
,D/NfcService( 1029): NFC-C OFF
,E/ActivityThread( 1293): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20874, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 151006, reason: UserStart
,I/PhenotypeConfigurator(  984): Scheduling Phenotype for one-off execution 366 seconds from now (1450201747504)
,D/GetConfigurationSnapshotOperation(  984): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  984): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  984): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  984): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  984): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  984): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  984): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  984): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  984): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  984): GC_CONCURRENT freed 593K, 4% free 18785K/19472K, paused 3ms+5ms, total 33ms
,D/dalvikvm(  984): GC_CONCURRENT freed 528K, 4% free 18927K/19552K, paused 2ms+2ms, total 20ms
,D/dalvikvm(  984): GC_CONCURRENT freed 541K, 4% free 19118K/19752K, paused 3ms+3ms, total 30ms
,D/dalvikvm(  984): GC_CONCURRENT freed 693K, 4% free 19202K/19988K, paused 1ms+4ms, total 24ms
,D/dalvikvm(  984): GC_CONCURRENT freed 836K, 5% free 19227K/20156K, paused 3ms+6ms, total 39ms
,D/dalvikvm(  984): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm(  984): GC_FOR_ALLOC freed 472K, 7% free 18923K/20184K, paused 18ms, total 18ms
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1130): GC_CONCURRENT freed 375K, 4% free 17938K/18604K, paused 2ms+2ms, total 15ms
,W/dalvikvm( 1130): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1130): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1130): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1130): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1130): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1130): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1130): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1130): GC_CONCURRENT freed 387K, 4% free 17940K/18604K, paused 2ms+3ms, total 16ms
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8b29160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1196256736)
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1196256736) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8b29160
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1615): GC_FOR_ALLOC freed 327K, 4% free 17225K/17920K, paused 10ms, total 10ms
,D/dalvikvm( 1615): GC_CONCURRENT freed 273K, 4% free 17340K/17920K, paused 3ms+3ms, total 15ms
,I/jxcore-log( 2598): Connected to the server!
I/jxcore-log( 2598): 
,I/chromium( 2598): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2598): --- start :testFindPeers.js---
I/jxcore-log( 2598): 
,I/jxcore-log( 2598): testFindPeers created [object Object]
I/jxcore-log( 2598): 
,I/jxcore-log( 2598): serverPort is 8876
I/jxcore-log( 2598): 
,I/dalvikvm( 2598): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 2598): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 2598): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 2598): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2598): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 2598): Shutting down VM
,W/dalvikvm( 2598): threadid=1: thread exiting with uncaught exception (group=0x41722ba8)
E/AndroidRuntime( 2598): FATAL EXCEPTION: main
E/AndroidRuntime( 2598): Process: com.test.thalitest, PID: 2598
E/AndroidRuntime( 2598): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 2598): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 2598): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 2598): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 2598): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 2598): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 2598): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 2598): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 2598): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 2598): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 2598): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2598): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2598): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2598): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2598): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2598): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2598): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2598): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2598): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  757):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  757): Killing 2442:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,I/Process ( 2598): Sending signal. PID: 2598 SIG: 9
,I/ActivityManager(  757): Process com.test.thalitest (pid 2598) has died.
,I/WindowState(  757): WIN DEATH: Window{44bddae8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ConnectivityService(  757): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  757): Done.
,D/ConnectivityService(  757): Setting timer for 720seconds
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  757): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  757): Done.
,D/ConnectivityService(  757): Setting timer for 720seconds
,I/EventLogService( 1293): Aggregate from 1450200831043 (log), 1450200831043 (data)
,I/ProcessStatsService(  757): Prepared write state in 50ms
,I/dalvikvm(  757): Jit: resizing JitTable from 8192 to 16384
I/ProcessStatsService(  757): Prepared write state in 7ms
,I/ProcessStatsService(  757): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-41-55.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  757): Killing 1181:com.google.android.googlequicksearchbox:search/u0a19 (adj 15): empty for 1802s
I/ActivityManager(  757): Killing 2676:com.android.settings/1000 (adj 15): empty for 1807s
I/ActivityManager(  757): Killing 2545:com.quickoffice.android/u0a65 (adj 15): empty for 1813s
I/ActivityManager(  757): Killing 2504:com.google.android.apps.docs/u0a35 (adj 15): empty for 1814s
I/ActivityManager(  757): Killing 2472:com.android.musicfx/u0a13 (adj 15): empty for 1814s
V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1293): GC_CONCURRENT freed 487K, 3% free 19269K/19788K, paused 5ms+7ms, total 31ms
I/ActivityManager(  757): Killing 2872:com.android.chrome/u0a31 (adj 15): empty for 1800s
D/AndroidRuntime( 3129): 
D/AndroidRuntime( 3129): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3129): CheckJNI is OFF
D/dalvikvm( 3129): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3129): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3129): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3129): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3129): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3129): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/AndroidRuntime( 3129): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
W/PackageSettings(  757): Skipping PackageSetting{42884390 com.example.hello/10116} due to missing metadata
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
D/dalvikvm(  757): GC_CONCURRENT freed 2084K, 53% free 26271K/55200K, paused 2ms+5ms, total 48ms
I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "sms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  757): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3146 uid=10003 gids={50003, 3003, 1028, 1015}
D/dalvikvm(  183): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 2ms+2ms, total 15ms
D/dalvikvm( 1043): GC_EXPLICIT freed 1252K, 7% free 26143K/27860K, paused 1ms+2ms, total 55ms
D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 3ms+1ms, total 15ms
I/Launcher( 1043): Deferring update until onResume
D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 12ms
I/LatinIME:LogUtils(  966): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
W/GeofencerStateMachine(  984): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "smsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  757): removePackageParticipantsLocked: uid=10108 #1
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1043): Deferring update until onResume
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mmsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "sms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/Binder  (  966): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  966): java.lang.NullPointerException
W/Binder  (  966): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  966): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  966): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  966): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 2598 uid 10108
D/dalvikvm(  757): GC_EXPLICIT freed 534K, 53% free 26251K/55200K, paused 9ms+6ms, total 104ms
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "smsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mmsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 3146): GC_CONCURRENT freed 211K, 2% free 16922K/17164K, paused 2ms+2ms, total 16ms
D/VoicemailCleanupService( 3146): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3178 uid=10013 gids={50013, 3003, 3002}
D/AndroidRuntime( 3129): Shutting down VM
D/dalvikvm( 3129): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
I/ActivityManager(  757): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver: pid=3194 uid=10019 gids={50019, 3003, 1028, 3002, 1015}
I/ActivityManager(  757): Killing 1659:com.google.android.calendar/u0a28 (adj 15): empty for 1801s
I/ActivityManager(  757): Killing 2712:com.google.android.keep/u0a52 (adj 15): empty for 1801s
I/ContactLocale( 3146): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Icing.InternalIcingCorporaProvider( 3194): Updating corpora: A: com.test.thalitest, C: MAYBE
W/Launcher( 1043): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4277cbc0 new=com.google.android.velvet.VelvetApplication@4277cbc0
I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3210 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
I/ActivityManager(  757): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3220 uid=10011 gids={50011, 3003}
W/ContextImpl( 3210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  757): Resuming delayed broadcast
I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  757): Resuming delayed broadcast
I/ActivityManager(  757): Killing 2923:com.qualcomm.timeservice/u0a68 (adj 15): empty for 1801s
D/PackageBroadcastService( 1293): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1293): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1293): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1293): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1293): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1293): Module APK com.google.android.play.games already loaded
I/ActivityManager(  757): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/dalvikvm( 3194): GC_CONCURRENT freed 218K, 2% free 16967K/17216K, paused 2ms+2ms, total 40ms
I/LocationSettingsChecker( 1293): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1293): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1293): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
W/BaseAppContext( 1293): Using Auth Proxy for data requests.
D/gH_MetricsDatabase( 1293): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1293): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/BaseAppContext( 1293): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1293): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1293): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1293): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1293): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1293): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1293): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1293): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1293): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1293): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/GMPM-SVC( 1293): App measurement is starting up, version: 8489
I/GMPM-SVC( 1293): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/dalvikvm( 1293): GC_CONCURRENT freed 744K, 4% free 19383K/20156K, paused 3ms+4ms, total 26ms
I/Icing   ( 1293): doRemovePackageData com.test.thalitest
E/SharedPreferencesImpl( 1293): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
W/FileUtils( 1293): Failed to chmod(/data/data/com.google.android.gms/databases/google_app_measurement.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1293): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/SQLiteDatabase( 1293): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1293): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 1293): 	at com.google.android.gms.drive.database.m.b(SourceFile:601)
E/SQLiteDatabase( 1293): 	at com.google.android.gms.drive.database.m.a(SourceFile:595)
E/SQLiteDatabase( 1293): 	at com.google.android.gms.drive.database.o.run(SourceFile:616)
W/dalvikvm( 1293): threadid=24: thread exiting with uncaught exception (group=0x41722ba8)
E/SQLiteLog( 1293): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1293): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
I/Process ( 1293): Sending signal. PID: 1293 SIG: 9
E/AndroidRuntime( 1293): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 1293): Process: com.google.android.gms, PID: 1293
E/AndroidRuntime( 1293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 1293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/AndroidRuntime( 1293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 1293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1293): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/AndroidRuntime( 1293): 	at com.google.android.gms.drive.database.m.b(SourceFile:601)
E/AndroidRuntime( 1293): 	at com.google.android.gms.drive.database.m.a(SourceFile:595)
E/AndroidRuntime( 1293): 	at com.google.android.gms.drive.database.o.run(SourceFile:616)
E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  757): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  757): 	... 5 more
I/ActivityManager(  757): Process com.google.android.gms (pid 1293) has died.
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
F/ActivityManager(  757): Service ServiceRecord{42dc0d58 u0 com.google.android.gms/.usagereporting.service.UsageReportingService} in process ProcessRecord{42e99880 1293:com.google.android.gms/u0a7} not same as in map: null
E/DropBoxManagerService(  757): Can't write: system_server_wtf
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop13.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10025)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:9832)
E/DropBoxManagerService(  757): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  757): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/DropBoxManagerService(  757): 	at android.util.Log.wtf(Log.java:293)
E/DropBoxManagerService(  757): 	at android.util.Slog.wtf(Slog.java:82)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2081)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:12427)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3606)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:3751)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1026)
E/DropBoxManagerService(  757): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService(  757): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  757): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  757): 	... 18 more
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
E/AppDataSearchClient( 3194): Register corpus failed.
E/AppDataSearchClient( 3194): android.os.DeadObjectException
E/AppDataSearchClient( 3194): 	at android.os.BinderProxy.transact(Native Method)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dh$a$a.b(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.registerCorpus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.setRegisteredCorpora(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:160)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  757): Resuming delayed broadcast
E/AppDataSearchClient( 3194): Register corpus failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.registerCorpus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.setRegisteredCorpora(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:160)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchClient( 3194): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 3194): 	... 21 more
E/SQLiteLog( 1130): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1130): Shutting down VM
W/dalvikvm( 1130): threadid=1: thread exiting with uncaught exception (group=0x41722ba8)
E/AppDataSearchClient( 3194): Register corpus failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.registerCorpus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.setRegisteredCorpora(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:160)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchClient( 3194): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 3194): 	... 21 more
E/AndroidRuntime( 1130): FATAL EXCEPTION: main
E/AndroidRuntime( 1130): Process: com.google.process.gapps, PID: 1130
E/AndroidRuntime( 1130): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1130): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2414)
E/AndroidRuntime( 1130): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/AndroidRuntime( 1130): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/AndroidRuntime( 1130): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1130): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1130): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 1130): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1130): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1130): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1130): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1130): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1130): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1130): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1130): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1130): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1130): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1130): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1130): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1130): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1130): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1130): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/AndroidRuntime( 1130): 	... 10 more
I/Process ( 1130): Sending signal. PID: 1130 SIG: 9
D/dalvikvm( 3194): GC_CONCURRENT freed 338K, 3% free 17103K/17476K, paused 2ms+3ms, total 15ms
E/AppDataSearchClient( 3194): Register UniversalSearchableAppInfo failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.registerGlobalSearchApplication(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:162)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchClient( 3194): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 3194): 	... 20 more
E/AppDataSearchClient( 3194): Get corpus status failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.getCorpusStatus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:313)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchClient( 3194): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 3194): 	... 21 more
E/.AppDataSearchProvider( 3194): Couldn't fetch status for corpus 'applications__id'
E/AppDataSearchClient( 3194): Get corpus status failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.getCorpusStatus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:313)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 3194): 	at android.os.Looper.loop(Looper.java:136)
E/AppDataSearchClient( 3194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchClient( 3194): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 3194): 	... 21 more
E/.AppDataSearchProvider( 3194): Couldn't fetch status for corpus 'emails_data_id'
E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop92.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  757): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  757): 	... 5 more
E/AppDataSearchClient( 3194): Get corpus status failed.
E/AppDataSearchClient( 3194): android.os.RemoteException
E/AppDataSearchClient( 3194): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.getCorpusStatus(Unknown Source)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:313)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/AppDataSearchClient( 3194): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/AppDataSearchClient( 3194): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AppDataSearchClient( 3194): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AppDataSearchClient( 3194): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AppDataSearchClient( 3194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 3194): 	at android.os.Handler.dispatchMessage(
```
