#### Test 543122980a88295_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2739): GC_CONCURRENT freed 254K, 2% free 17698K/18020K, paused 2ms+2ms, total 14ms
D/dalvikvm( 2739): GC_CONCURRENT freed 303K, 2% free 17907K/18240K, paused 1ms+2ms, total 13ms
D/dalvikvm( 2739): WAIT_FOR_CONCURRENT_GC blocked 6ms
,--------- beginning of /dev/log/system
I/ActivityManager(  756): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2779 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  756): Killing 1975:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2739): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2739): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2739): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2739): VFY: unable to resolve instance field 36
D/dalvikvm( 2739): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2739): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2739): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2739): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2739): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2739): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ca9f10
D/dalvikvm( 2739): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ca9f10
D/dalvikvm( 2739): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ca9f10, skipping init
D/dalvikvm( 2739): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ca9f10
D/dalvikvm( 2739): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ca9f10
V/JNIHelp ( 2739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2739): GC_CONCURRENT freed 499K, 3% free 17902K/18432K, paused 1ms+15ms, total 28ms
D/dalvikvm( 2739): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ca9f10
D/dalvikvm( 2739): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42ca9f10
D/dalvikvm( 2739): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ca9f10
D/dalvikvm( 2739): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42ca9f10
W/Quickoffice( 2779): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2779): Loading recent documents list
D/Quickoffice( 2779): The number of lines present in  /proc/mount 21
D/Quickoffice( 2779): Parsing the storagedefinition.xml.
D/dalvikvm( 2739): GC_FOR_ALLOC freed 146K, 3% free 17965K/18432K, paused 12ms, total 12ms
D/Quickoffice( 2779): # of Storagedefinitions - 35
D/Quickoffice( 2779): The # of storage definitions available - 35
D/Quickoffice( 2779): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2779): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2779): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2779): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2779): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 2739): GC_FOR_ALLOC freed <1K, 3% free 18004K/18472K, paused 13ms, total 13ms
D/Quickoffice( 2779): Build properties are not configured for this storage definition.
I/dalvikvm-heap( 2739): Grow heap (frag case) to 17.685MB for 79892-byte allocation
D/Quickoffice( 2779): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2779): The # of mounts identified -  1
I/ActivityManager(  756): Killing 2369:com.android.chrome/u0a31 (adj 15): empty #17
D/dalvikvm( 2739): GC_FOR_ALLOC freed 0K, 3% free 18082K/18552K, paused 14ms, total 14ms
D/com.google.android.apps.docs.quickoffice.X( 2779): Checking validity of 0 items
D/dalvikvm( 2779): GC_CONCURRENT freed 249K, 2% free 16941K/17220K, paused 2ms+2ms, total 27ms
D/ContentResolverUtil( 2779): There are 0 persisted uri permissions.
W/ActivityManager(  756): No permission grants found for com.quickoffice.android
D/com.google.android.apps.docs.quickoffice.X( 2779): 0 items were valid
W/Quickoffice( 2779): Could not load clipboard.
W/Quickoffice( 2779): Could not store clipboard.
I/ProviderInstaller( 2739): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2790): 
D/AndroidRuntime( 2790): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2790): CheckJNI is OFF
D/dalvikvm( 2790): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2790): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2790): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2790): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2790): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2790): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2790): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2790
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (293 us)
D/AndroidRuntime( 2790): Shutting down VM
D/dalvikvm( 2790): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2811 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1205): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1205): mic_close
I/Icing   ( 1315): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/ActivityManager(  756): Killing 955:com.google.android.keep/u0a52 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 2811): Binding Chromium to main looper Looper (main, tid 1) {42b9b998}
I/LibraryLoader( 2811): Expected native library version number "",actual native library version number ""
I/chromium( 2811): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2811): Initializing chromium process, renderers=0
I/MicroHotwordRecognitionRunner( 1205): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1205): Stopping hotword detection.
D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44829170:true
I/Adreno-EGL( 2811): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2811): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2811): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2811): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2811): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2811): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2811): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2811): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2811): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2811): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2811): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2811): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2811): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2811): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2811): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2811): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2811): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2811): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2811): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2811): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2811): CordovaWebView is running on device made by: LGE
I/Icing   ( 1315): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1315): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1315): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/OpenGLRenderer( 2811): Enabling debug mode 0
,D/dalvikvm( 1315): GC_CONCURRENT freed 478K, 3% free 19223K/19736K, paused 5ms+4ms, total 40ms
,W/AwContents( 2811): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +272ms
I/ActivityManager(  756): Killing 2390:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,D/JsMessageQueue( 2811): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2811): GC_CONCURRENT freed 294K, 2% free 16917K/17240K, paused 2ms+1ms, total 26ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2811): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42b9fda0
D/dalvikvm( 2811): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42b9fda0
D/jxcore_app_log( 2811): JniHelper::setJavaVM(0x41b37ed0), pthread_self() = 1983797920
D/JX-Cordova( 2811): jxcore cordova android initializing
D/dalvikvm( 2811): GC_CONCURRENT freed 194K, 2% free 17234K/17460K, paused 2ms+1ms, total 12ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2811): GC_CONCURRENT freed 155K, 2% free 17580K/17776K, paused 1ms+1ms, total 11ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2811): GC_CONCURRENT freed 155K, 2% free 17925K/18124K, paused 1ms+2ms, total 17ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2811): GC_CONCURRENT freed 151K, 2% free 18268K/18468K, paused 1ms+2ms, total 20ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2811): GC_CONCURRENT freed 160K, 2% free 18613K/18824K, paused 1ms+2ms, total 20ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2811): GC_CONCURRENT freed 183K, 2% free 19046K/19284K, paused 3ms+2ms, total 23ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2811): GC_CONCURRENT freed 223K, 2% free 19559K/19848K, paused 2ms+1ms, total 15ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2811): GC_CONCURRENT freed 285K, 2% free 20193K/20544K, paused 1ms+2ms, total 25ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 2811): GC_CONCURRENT freed 335K, 2% free 20976K/21388K, paused 1ms+1ms, total 18ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 2811): GC_FOR_ALLOC freed 386K, 3% free 21878K/22348K, paused 18ms, total 18ms
,D/dalvikvm( 2811): GC_CONCURRENT freed 1226K, 6% free 22281K/23576K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 1446K, 7% free 22548K/24176K, paused 20ms, total 20ms
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 17K, 7% free 22549K/24176K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2811): Grow heap (frag case) to 22.747MB for 733480-byte allocation
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 2K, 7% free 23262K/24896K, paused 20ms, total 20ms
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 1310K, 9% free 22776K/24896K, paused 26ms, total 26ms
,I/dalvikvm-heap( 2811): Grow heap (frag case) to 23.318MB for 1100216-byte allocation
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 28K, 9% free 23822K/25972K, paused 20ms, total 20ms
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 1931K, 11% free 23184K/25972K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2811): Grow heap (frag case) to 24.242MB for 1650320-byte allocation
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 1079K, 15% free 23716K/27584K, paused 21ms, total 21ms
,D/dalvikvm( 2811): GC_FOR_ALLOC freed 1976K, 14% free 23823K/27584K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2811): Grow heap (frag case) to 25.652MB for 2475476-byte allocation
,D/dalvikvm( 2811): GC_CONCURRENT freed 59K, 13% free 26182K/30004K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2811): GC_CONCURRENT freed 4595K, 18% free 24747K/30004K, paused 1ms+4ms, total 44ms
,D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/dalvikvm-heap( 2811): Grow heap (frag case) to 27.735MB for 3713210-byte allocation
,D/dalvikvm( 2811): GC_FOR_ALLOC freed <1K, 16% free 28374K/33632K, paused 24ms, total 24ms
,D/dalvikvm( 2811): GC_CONCURRENT freed 2751K, 23% free 25991K/33632K, paused 4ms+4ms, total 46ms
,W/jxcore-log( 2811): Initializing JXcore engine
,W/jxcore-log( 2811): JXcore engine is ready
,D/dalvikvm( 2811): GC_CONCURRENT freed 772K, 16% free 28300K/33632K, paused 5ms+17ms, total 32ms
W/jxcore-log( 2811): Starting JXcore engine
,W/jxcore-log( 2811): Platform android
W/jxcore-log( 2811): 
,W/jxcore-log( 2811): Process ARCH arm
W/jxcore-log( 2811): 
,I/jxcore-log( 2811): JXcore Cordova bridge is ready!
I/jxcore-log( 2811): 
,W/jxcore-log( 2811): JXcore engine is started
,I/chromium( 2811): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2811): Toggling radios to true
I/jxcore-log( 2811): 
,D/BluetoothAdapter( 2811): enable(): BT is already enabled..!
,D/WifiService(  756): setWifiEnabled: true pid=2811, uid=10108
I/jxcore-log( 2811): Radios toggled
I/jxcore-log( 2811): 
D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 2811): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2811): 
I/jxcore-log( 2811): Perf Test app loaded loaded
I/jxcore-log( 2811): 
,I/jxcore-log( 2811): check test folder
I/jxcore-log( 2811): 
,I/wpa_supplicant(  925): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/jxcore-log( 2811): found test : ./testFindPeers.js
I/jxcore-log( 2811): 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,I/jxcore-log( 2811): found test : ./testSendData.js
I/jxcore-log( 2811): 
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x77987718 clazz=0x5f300001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto( 1094): Read error: ssl=0x78d08200: I/O error during system call, Connection timed out
,I/jxcore-log( 2811): found test : ./testSendData2.js
I/jxcore-log( 2811): 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1094): SSL shutdown failed: ssl=0x78d08200: I/O error during system call, Broken pipe
,I/Choreographer( 2811): Skipped 67 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2811): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  925): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  925): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  925): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  925): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@430a5b08
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1015): GC_CONCURRENT freed 347K, 3% free 17064K/17440K, paused 1ms+0ms, total 75ms
,D/MusicLifecycle( 2224): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@42cb67b8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2224): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1315): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1315): onCreate
,D/SystemUpdateService( 1315): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1315): active receiver: enabled
,I/SystemUpdateService( 1315): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1315): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1315): now status is 0 (complete)
I/SystemUpdateService( 1315): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1315): file has been verified
,I/SystemUpdateService( 1315): OTA package size = 2571501
,I/SystemUpdateService( 1315): showing system update notification
,D/SystemUpdateService( 1315): onDestroy
,I/ActivityManager(  756): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2952 uid=10031 gids={50031, 3003, 1028, 1015}
,D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2952): VFY: unable to resolve instance field 68
D/dalvikvm( 2952): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2952): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2952): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2952): VFY: unable to resolve instance field 68
,D/dalvikvm( 2952): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2952): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2952): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2952): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2952): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  756): Killing 2224:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{4330be48 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{4333d340 2224:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{432a7950 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{4333d340 2224:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{43265740 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4333d340 2224:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{43202d80 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{4333d340 2224:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{431b4aa0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4333d340 2224:com.google.android.music:main/u0a58} not same as in map: null
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,I/dalvikvm( 2811): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 2811): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2811): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 2811): Shutting down VM
,W/dalvikvm( 2811): threadid=1: thread exiting with uncaught exception (group=0x41b49ba8)
E/AndroidRuntime( 2811): FATAL EXCEPTION: main
E/AndroidRuntime( 2811): Process: com.test.thalitest, PID: 2811
E/AndroidRuntime( 2811): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 2811): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 2811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 2811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 2811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 2811): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 2811): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 2811): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 2811): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 2811): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 2811): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2811): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2811): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2811): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2811): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  756):   Force finishing activity com.test.thalitest/.MainActivity
,D/dalvikvm(  756): GC_FOR_ALLOC freed 23222K, 52% free 27204K/56064K, paused 84ms, total 86ms
,W/ActivityManager(  756): Activity pause timeout for ActivityRecord{439cd8f8 u0 com.test.thalitest/.MainActivity t2 f}
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 1205): GC_CONCURRENT freed 1315K, 7% free 17941K/19288K, paused 3ms+6ms, total 26ms
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1315): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1315): onCreate
,D/SystemUpdateService( 1315): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1315): active receiver: enabled
,I/SystemUpdateService( 1315): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1315): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1315): now status is 0 (complete)
I/SystemUpdateService( 1315): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1315): file has been verified
,I/SystemUpdateService( 1315): OTA package size = 2571501
,I/SystemUpdateService( 1315): showing system update notification
,D/SystemUpdateService( 1315): onDestroy
,I/ActivityManager(  756): Killing 1840:com.google.android.gm/u0a41 (adj 15): empty #17
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm( 1094): GC_CONCURRENT freed 383K, 3% free 18098K/18620K, paused 2ms+3ms, total 24ms
,I/VacuumService(  995): Vacuum at: now=1450834000203 tag=VacuumService
,D/dalvikvm(  995): GC_CONCURRENT freed 500K, 4% free 18736K/19332K, paused 2ms+5ms, total 44ms
,D/Finsky  ( 2466): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 1094): GC_CONCURRENT freed 494K, 4% free 18021K/18620K, paused 2ms+1ms, total 18ms
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityManager(  756): Activity destroy timeout for ActivityRecord{439cd8f8 u0 com.test.thalitest/.MainActivity t2 f}
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8f95160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1191620912)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1191620912) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8f95160
,I/PowerManagerService(  756): Going to sleep due to screen timeout...
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb7ae4450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  756): Excessive delay in blankDisplay() while turning screen off: 296ms
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@431172e0)
,V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
I/WindowManager(  756): No lock screen! windowToken=null
,D/NfcService( 1043): NFC-C OFF
,I/PhenotypeConfigurator(  995): Scheduling Phenotype for one-off execution 13747 seconds from now (1450834079833)
,D/GetConfigurationSnapshotOperation(  995): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  995): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  995): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  995): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  995): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  995): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1094): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1094): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  995): GC_CONCURRENT freed 570K, 4% free 18750K/19416K, paused 5ms+4ms, total 43ms
,D/dalvikvm(  995): GC_CONCURRENT freed 526K, 4% free 18908K/19528K, paused 3ms+4ms, total 31ms
,D/dalvikvm(  995): GC_CONCURRENT freed 456K, 3% free 19099K/19648K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  995): GC_CONCURRENT freed 655K, 4% free 19172K/19924K, paused 1ms+5ms, total 23ms
,D/dalvikvm(  995): GC_CONCURRENT freed 749K, 5% free 19189K/20032K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  995): GC_CONCURRENT freed 821K, 5% free 19172K/20088K, paused 2ms+5ms, total 38ms
,D/dalvikvm(  995): GC_FOR_ALLOC freed 406K, 7% free 18887K/20108K, paused 45ms, total 45ms
,D/dalvikvm( 1094): GC_CONCURRENT freed 444K, 4% free 17976K/18620K, paused 2ms+1ms, total 25ms
,I/Process ( 2811): Sending signal. PID: 2811 SIG: 9
,I/ActivityManager(  756): Process com.test.thalitest (pid 2811) has died.
,I/WindowState(  756): WIN DEATH: Window{439cf9b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3130
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3135
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3136
,I/dalvikvm(  756): Jit: resizing JitTable from 8192 to 16384
,I/ActivityManager(  756): Killing 1760:com.google.android.calendar/u0a28 (adj 15): empty for 1816s
,I/ProcessStatsService(  756): Prepared write state in 30ms
,I/ProcessStatsService(  756): Prepared write state in 12ms
,I/ProcessStatsService(  756): Pruning old procstats: /data/system/procstats/state-2015-12-22-02-21-06.bin
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,I/ActivityManager(  756): Killing 2707:com.android.musicfx/u0a13 (adj 15): empty for 1811s
,I/ActivityManager(  756): Killing 2681:com.google.android.partnersetup/u0a11 (adj 15): empty for 1811s
,I/ActivityManager(  756): Killing 967:android.process.acore/u0a3 (adj 15): empty for 1811s
,I/ActivityManager(  756): Killing 2665:com.android.defcontainer/u0a4 (adj 15): empty for 1811s
,I/ActivityManager(  756): Killing 2289:com.android.providers.calendar/u0a1 (adj 15): empty for 1832s
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm(  756): GC_CONCURRENT freed 2543K, 52% free 27233K/56064K, paused 2ms+4ms, total 63ms
,V/GLSActivity( 1094): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1094): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1315): Aggregate from 1450833718701 (log), 1450833718701 (data)
,V/NativeCrypto( 1094): SSL shutdown failed: ssl=0x78c9e540: I/O error during system call, Connection timed out
,V/NativeCrypto( 1094): SSL shutdown failed: ssl=0x78c7f8a8: I/O error during system call, Connection timed out
,D/dalvikvm( 1094): GC_CONCURRENT freed 403K, 4% free 17968K/18620K, paused 1ms+1ms, total 13ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1800000ms)
```
