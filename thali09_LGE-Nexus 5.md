#### Test 5497026186051be_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  773): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2654 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  773): Killing 1436:com.google.android.keep/u0a52 (adj 15): empty #17
--------- beginning of /dev/log/main
D/dalvikvm( 2616): GC_CONCURRENT freed 287K, 2% free 17811K/18128K, paused 2ms+2ms, total 32ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2616): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2616): VFY: unable to resolve instance field 36
D/dalvikvm( 2616): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2616): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2616): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2616): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42764088
D/dalvikvm( 2616): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42764088
D/dalvikvm( 2616): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42764088, skipping init
D/dalvikvm( 2616): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42764088
D/dalvikvm( 2616): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42764088
V/JNIHelp ( 2616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2616): GC_CONCURRENT freed 421K, 3% free 17901K/18352K, paused 3ms+1ms, total 30ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2616): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42764088
D/dalvikvm( 2616): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42764088
D/dalvikvm( 2616): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42764088
D/dalvikvm( 2616): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42764088
D/dalvikvm( 2616): GC_CONCURRENT freed 329K, 3% free 17961K/18352K, paused 2ms+1ms, total 14ms
W/Quickoffice( 2654): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2654): Loading recent documents list
D/Quickoffice( 2654): The number of lines present in  /proc/mount 21
D/Quickoffice( 2654): Parsing the storagedefinition.xml.
I/ProviderInstaller( 2616): Installed default security provider GmsCore_OpenSSL
D/Quickoffice( 2654): # of Storagedefinitions - 35
D/Quickoffice( 2654): The # of storage definitions available - 35
D/Quickoffice( 2654): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2654): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2654): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2654): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2654): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2654): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2654): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2654): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2654): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2654): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2654): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2654): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2654): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2654): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2654): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2654): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2654): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2654): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2654): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2654): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2654): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 2654): GC_CONCURRENT freed 181K, 2% free 16914K/17124K, paused 2ms+0ms, total 12ms
D/Quickoffice( 2654): Build properties are not configured for this storage definition.
D/Quickoffice( 2654): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2654): The # of mounts identified -  1
I/ActivityManager(  773): Killing 2229:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
D/com.google.android.apps.docs.quickoffice.X( 2654): Checking validity of 0 items
D/ContentResolverUtil( 2654): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2654): 0 items were valid
W/ActivityManager(  773): No permission grants found for com.quickoffice.android
W/Quickoffice( 2654): Could not load clipboard.
W/Quickoffice( 2654): Could not store clipboard.
D/AndroidRuntime( 2667): 
D/AndroidRuntime( 2667): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2667): CheckJNI is OFF
D/dalvikvm( 2667): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2667): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2667): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2667): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2667): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2667): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2667): Calling main entry com.android.commands.am.Am
I/ActivityManager(  773): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2667
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (149 us)
D/AndroidRuntime( 2667): Shutting down VM
D/dalvikvm( 2667): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  773): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2685 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1196): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1196): mic_close
I/Icing   ( 1301): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/ActivityManager(  773): Killing 2138:com.android.settings/1000 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1196): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1196): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2685): Binding Chromium to main looper Looper (main, tid 1) {425f7a70}
I/LibraryLoader( 2685): Expected native library version number "",actual native library version number ""
I/chromium( 2685): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2685): Initializing chromium process, renderers=0
D/BluetoothManagerService(  773): Message: 20
D/BluetoothManagerService(  773): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442eecd0:true
I/Adreno-EGL( 2685): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
D/dalvikvm( 1196): GC_CONCURRENT freed 588K, 4% free 18289K/18904K, paused 2ms+2ms, total 34ms
W/chromium( 2685): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2685): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2685): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2685): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2685): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2685): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2685): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2685): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2685): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2685): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2685): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2685): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2685): CordovaWebView is running on device made by: LGE
I/Icing   ( 1301): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1301): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1301): GC_CONCURRENT freed 538K, 3% free 19193K/19760K, paused 2ms+4ms, total 35ms
D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/OpenGLRenderer( 2685): Enabling debug mode 0
I/Icing   ( 1301): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
W/AwContents( 2685): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  773): Killing 1956:com.google.android.email/u0a36 (adj 15): empty #17
I/ActivityManager(  773): Displayed com.test.thalitest/.MainActivity: +280ms
D/JsMessageQueue( 2685): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2685): GC_CONCURRENT freed 250K, 2% free 16882K/17164K, paused 1ms+2ms, total 19ms
D/dalvikvm( 2685): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425fbd88
D/dalvikvm( 2685): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425fbd88
D/jxcore_app_log( 2685): JniHelper::setJavaVM(0x414dff00), pthread_self() = 1983664184
D/JX-Cordova( 2685): jxcore cordova android initializing
D/dalvikvm( 2685): GC_CONCURRENT freed 210K, 2% free 17183K/17424K, paused 1ms+1ms, total 11ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2685): GC_CONCURRENT freed 156K, 2% free 17526K/17724K, paused 1ms+2ms, total 15ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2685): GC_CONCURRENT freed 154K, 2% free 17870K/18068K, paused 1ms+2ms, total 17ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2685): GC_CONCURRENT freed 152K, 2% free 18213K/18412K, paused 1ms+1ms, total 19ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2685): GC_CONCURRENT freed 157K, 2% free 18549K/18756K, paused 2ms+2ms, total 25ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2685): GC_CONCURRENT freed 178K, 2% free 18967K/19200K, paused 2ms+1ms, total 16ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 2685): GC_CONCURRENT freed 220K, 2% free 19475K/19756K, paused 0ms+1ms, total 13ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2685): GC_CONCURRENT freed 278K, 2% free 20089K/20432K, paused 2ms+2ms, total 26ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 2685): GC_CONCURRENT freed 326K, 2% free 20853K/21252K, paused 1ms+3ms, total 23ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 2685): GC_CONCURRENT freed 401K, 3% free 21791K/22272K, paused 1ms+2ms, total 19ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2685): GC_CONCURRENT freed 1148K, 6% free 22299K/23520K, paused 1ms+2ms, total 24ms
D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 2685): GC_FOR_ALLOC freed 737K, 7% free 22380K/23840K, paused 19ms, total 19ms
I/dalvikvm-heap( 2685): Grow heap (frag case) to 22.345MB for 485740-byte allocation
D/dalvikvm( 2685): GC_FOR_ALLOC freed 1K, 7% free 22853K/24316K, paused 20ms, total 20ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 867K, 8% free 22546K/24316K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2685): Grow heap (frag case) to 22.739MB for 728606-byte allocation
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 15K, 8% free 23242K/25028K, paused 20ms, total 20ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 1258K, 9% free 22801K/25028K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2685): Grow heap (frag case) to 23.335MB for 1092904-byte allocation
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 20K, 9% free 23848K/26096K, paused 20ms, total 20ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 1926K, 12% free 23208K/26096K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2685): Grow heap (frag case) to 24.253MB for 1639352-byte allocation
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 31K, 11% free 24777K/27700K, paused 21ms, total 21ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 2960K, 14% free 23823K/27700K, paused 23ms, total 25ms
,I/dalvikvm-heap( 2685): Grow heap (frag case) to 25.636MB for 2459024-byte allocation
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 5K, 13% free 26218K/30104K, paused 23ms, total 23ms
,D/dalvikvm( 2685): GC_CONCURRENT freed 1775K, 19% free 24647K/30104K, paused 6ms+4ms, total 41ms
,D/dalvikvm( 2685): GC_CONCURRENT freed 2590K, 18% free 24709K/30104K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 577K, 19% free 24464K/30104K, paused 20ms, total 21ms
,I/dalvikvm-heap( 2685): Grow heap (frag case) to 27.435MB for 3688532-byte allocation
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 5K, 17% free 28060K/33708K, paused 22ms, total 22ms
,D/dalvikvm( 2685): GC_CONCURRENT freed 2653K, 24% free 25652K/33708K, paused 5ms+2ms, total 31ms
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 663K, 24% free 25698K/33708K, paused 17ms, total 18ms
,W/jxcore-log( 2685): Initializing JXcore engine
,W/jxcore-log( 2685): JXcore engine is ready
,D/dalvikvm( 2685): GC_CONCURRENT freed 5453K, 32% free 23234K/33708K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 2685): Starting JXcore engine
,W/jxcore-log( 2685): Platform android
W/jxcore-log( 2685): 
,W/jxcore-log( 2685): Process ARCH arm
W/jxcore-log( 2685): 
,I/jxcore-log( 2685): JXcore Cordova bridge is ready!
I/jxcore-log( 2685): 
,W/jxcore-log( 2685): JXcore engine is started
,I/chromium( 2685): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2685): Toggling radios to true
I/jxcore-log( 2685): 
,D/BluetoothAdapter( 2685): enable(): BT is already enabled..!
,I/jxcore-log( 2685): Radios toggled
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): My device name is: LGE-Nexus 5
I/jxcore-log( 2685): 
D/WifiService(  773): setWifiEnabled: true pid=2685, uid=10108
,I/wpa_supplicant(  881): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  773): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  773): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  773): Attempting to switch to mobile
,D/ConnectivityService(  773): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  773): android_net_utils_resetConnections in env=0x763119c0 clazz=0x5e300001 iface=wlan0 mask=0x3
D/ConnectivityService(  773): resetConnections(wlan0, 3)
,V/NativeCrypto( 1121): Read error: ssl=0x790791d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1121): SSL shutdown failed: ssl=0x790791d8: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  773): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  773): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  881): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  881): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  881): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  881): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  773): scanCount==0 - aborting
,D/ConnectivityService(  773): handleInetConditionChange: no active default network - ignore
,D/Tethering(  773): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  773): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  773): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2253): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@42712430 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1301): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1301): onCreate
,D/SystemUpdateService( 1301): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1301): active receiver: enabled
,I/iu.Environment( 1301): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 2000): connection state changed from CONNECTED to DISCONNECTED
I/iu.UploadsManager( 1301): num queued entries: 0
I/iu.UploadsManager( 1301): num updated entries: 0
I/SystemUpdateService( 1301): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1301): NEXT; no task
I/SystemUpdateService( 1301): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1301): now status is 0 (complete)
I/SystemUpdateService( 1301): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1301): file has been verified
,I/SystemUpdateService( 1301): OTA package size = 2571501
,I/SystemUpdateService( 1301): showing system update notification
I/ActivityManager(  773): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2802 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1301): onDestroy
,D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2802): VFY: unable to resolve instance field 68
D/dalvikvm( 2802): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2802): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2802): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2802): VFY: unable to resolve instance field 68
,D/dalvikvm( 2802): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2802): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/ActivityManager(  773): Killing 1800:com.google.android.deskclock/u0a33 (adj 15): empty #17
I/dalvikvm( 2802): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2802): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2802): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/WifiStateMachine(  773): VerifyingLinkState enter
,D/WifiStateMachine(  773): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  773): CaptivePortalCheckState enter
,D/WifiStateMachine(  773): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  773): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  773): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  773): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  773): Unexpected mtu value: android.net.wifi.WifiStateTracker@429071d0
,D/Nat464Xlat(  773): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1002): GC_CONCURRENT freed 339K, 3% free 17068K/17436K, paused 2ms+1ms, total 24ms
,D/ConnectivityService(  773): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  773): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  773):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  773): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1121): GC_CONCURRENT freed 379K, 4% free 18041K/18604K, paused 3ms+6ms, total 44ms
,D/dalvikvm( 1121): WAIT_FOR_CONCURRENT_GC blocked 3ms
,I/VacuumService(  980): Vacuum at: now=1452511751976 tag=VacuumService
,D/dalvikvm( 1121): GC_CONCURRENT freed 567K, 4% free 17880K/18604K, paused 2ms+1ms, total 18ms
,I/jxcore-log( 2685): Test app app.js loaded
I/jxcore-log( 2685): 
,I/Choreographer( 2685): Skipped 377 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2685): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  773): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  773): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2253): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@42712430 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2253): type=WIFI subType= reason=null isConnected=true
,D/dalvikvm( 1217): GC_CONCURRENT freed 369K, 3% free 16742K/17140K, paused 1ms+1ms, total 18ms
,I/SystemUpdateService( 1301): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1301): onCreate
,D/SystemUpdateService( 1301): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1301): active receiver: enabled
,I/SystemUpdateService( 1301): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1301): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/SystemUpdateService( 1301): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1301): now status is 0 (complete)
I/SystemUpdateService( 1301): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1301): file has been verified
,I/SystemUpdateService( 1301): OTA package size = 2571501
,I/iu.UploadsManager( 1301): num queued entries: 0
,I/SystemUpdateService( 1301): showing system update notification
,I/iu.UploadsManager( 1301): num updated entries: 0
,I/iu.SyncManager( 1301): NEXT; no task
,D/SystemUpdateService( 1301): onDestroy
,D/dalvikvm(  773): GC_EXPLICIT freed 23263K, 53% free 26153K/55608K, paused 2ms+5ms, total 106ms
,I/Babel   ( 2000): connection state changed from DISCONNECTED to CONNECTED
,I/PhenotypeConfigurator(  980): Scheduling Phenotype for one-off execution 10141 seconds from now (1452511752843)
,D/GetConfigurationSnapshotOperation(  980): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  980): GC_CONCURRENT freed 436K, 3% free 18761K/19292K, paused 3ms+3ms, total 23ms
,I/PhenotypeFlagCommitter(  980): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  980): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  980): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  980): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm(  980): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  980): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  980): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  980): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  980): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  980): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  980): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1121): GC_CONCURRENT freed 376K, 4% free 17917K/18604K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 1196): GC_CONCURRENT freed 859K, 6% free 17867K/18900K, paused 2ms+2ms, total 18ms
,D/dalvikvm(  980): GC_CONCURRENT freed 595K, 4% free 18880K/19568K, paused 4ms+2ms, total 32ms
,D/dalvikvm(  980): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 1196): GC_CONCURRENT freed 455K, 6% free 17879K/18900K, paused 3ms+3ms, total 20ms
,D/ConnectivityService(  773): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm(  980): GC_CONCURRENT freed 589K, 4% free 18975K/19660K, paused 3ms+2ms, total 20ms
,D/dalvikvm(  980): GC_CONCURRENT freed 552K, 4% free 19110K/19756K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  980): GC_CONCURRENT freed 738K, 5% free 19132K/19964K, paused 2ms+4ms, total 22ms
,D/dalvikvm(  980): GC_CONCURRENT freed 813K, 5% free 19071K/20020K, paused 2ms+4ms, total 22ms
,D/dalvikvm(  980): GC_CONCURRENT freed 735K, 5% free 19110K/20020K, paused 3ms+7ms, total 42ms
,D/dalvikvm( 2407): GC_CONCURRENT freed 1132K, 6% free 19681K/20852K, paused 3ms+2ms, total 37ms
,D/Finsky  ( 2407): [1] 5.onFinished: Installation state replication succeeded.
,D/CaptivePortalTracker(  773): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  773): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  773): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  773): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  773): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  773): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  773): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  773): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8d3d160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194077664)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194077664) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8d3d160
,I/ActivityManager(  773): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=2908 uid=10033 gids={50033, 1028}
,I/ActivityManager(  773): Killing 1758:com.google.android.calendar/u0a28 (adj 15): empty #17
,I/PowerManagerService(  773): Going to sleep due to screen timeout...
,I/Adreno-EGL(  773): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb8abf450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  773): Excessive delay in blankDisplay() while turning screen off: 291ms
,V/KeyguardServiceDelegate(  773): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42ce4f70)
,V/KeyguardServiceDelegate(  773): **** SHOWN CALLED ****
I/WindowManager(  773): No lock screen! windowToken=null
,D/NfcService( 1021): NFC-C OFF
,I/jxcore-log( 2685): --= Surplus to requirements =--
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): ****TEST TOOK:  ms ****
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2685): 
,D/AndroidRuntime( 2972): 
D/AndroidRuntime( 2972): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2972): CheckJNI is OFF
,D/dalvikvm( 2972): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2972): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2972): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2972): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2972): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2972): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 2972): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  773): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
,I/ActivityManager(  773): Killing 2685:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
,I/ActivityManager(  773):   Force finishing activity ActivityRecord{44a313a0 u0 com.test.thalitest/.MainActivity t2}
,W/InputDispatcher(  773): channel '447e5418 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  773): channel '447e5418 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowState(  773): WIN DEATH: Window{447e5418 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  773): Attempted to unregister already unregistered input channel '447e5418 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,W/PackageSettings(  773): Skipping PackageSetting{427079d8 com.example.hello/10116} due to missing metadata
,I/ActivityManager(  773): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
,D/dalvikvm( 1196): GC_EXPLICIT freed 202K, 6% free 17775K/18896K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 1044): GC_EXPLICIT freed 1263K, 7% free 26149K/27952K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 1301): GC_EXPLICIT freed 565K, 4% free 19034K/19760K, paused 4ms+5ms, total 52ms
,W/SQLiteConnectionPool( 1301): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputReader(  773): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1044): Deferring update until onResume
,I/LatinIME:LogUtils(  962): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,I/Launcher( 1044): Deferring update until onResume
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "sms"
,D/dalvikvm(  773): GC_EXPLICIT freed 1066K, 54% free 26127K/55608K, paused 4ms+8ms, total 92ms
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
W/GeofencerStateMachine(  980): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  773):   Scheme: "smsto"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  773):   Scheme: "mms"
,D/VoicemailCleanupService(  950): Cleaning up data for package: com.test.thalitest
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  950): GC_CONCURRENT freed 254K, 2% free 17062K/17344K, paused 1ms+0ms, total 10ms
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mmsto"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  773): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  773): removePackageParticipantsLocked: uid=10108 #1
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "sms"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "smsto"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  773): GC_EXPLICIT freed 498K, 54% free 26073K/55608K, paused 4ms+5ms, total 74ms
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mms"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mmsto"
,I/Icing.InternalIcingCorporaProvider( 1196): Updating corpora: A: com.test.thalitest, C: MAYBE
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 2972): Shutting down VM
,D/dalvikvm( 2972): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
,W/Launcher( 1044): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42600bd0 new=com.google.android.velvet.VelvetApplication@42600bd0
,I/ActivityManager(  773): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3008 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,W/ContextImpl( 3008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,I/ActivityManager(  773): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
,I/Icing.InternalIcingCorporaProvider( 1196): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  773): Resuming delayed broadcast
,D/PackageBroadcastService( 1301): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1301): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1301): Module APK com.google.android.play.games already loaded
,W/Binder  (  962): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  962): java.lang.NullPointerException
W/Binder  (  962): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  962): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  962): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  962): 	at dalvik.system.NativeStart.run(Native Method)
D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1301): Module APK com.google.android.play.games already loaded
W/InputMethodManagerService(  773): Got RemoteException sending setActive(false) notification to pid 2685 uid 10108
I/ActivityManager(  773): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 1301): Removing dialog suppression flag for package com.test.thalitest
,I/dalvikvm(  773): Jit: resizing JitTable from 8192 to 16384
,D/gH_CompatibleDatabase( 1301): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1301): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1301): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1301): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1301): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1301): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1301): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1301): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1301): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1301): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1301): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1301): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1301): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 1301): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1301): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/dalvikvm( 1301): GC_CONCURRENT freed 596K, 4% free 19211K/19900K, paused 3ms+6ms, total 28ms
,I/Icing   ( 1301): doRemovePackageData com.test.thalitest
,E/GMPM-SVC( 1301): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1775)
,E/SharedPreferencesImpl( 1301): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,W/FileUtils( 1301): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/DriveInitializer( 1301): Awaiting to be initialized
W/DriveInitializer( 1301): Background init thread started
,E/SQLiteLog( 1301): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,E/DocListDatabase( 1301): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1301): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1301): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1301): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1301): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1301): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1301): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/DocListDatabase( 1301): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1301): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1301): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1301): Background init thread ended
W/dalvikvm( 1301): threadid=26: thread exiting with uncaught exception (group=0x415a6ba8)
,E/SQLiteLog( 1301): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 1301): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1301): Process: com.google.android.gms, PID: 1301
E/AndroidRuntime( 1301): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1301): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1301): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1301): 	at com.google.android.gms.drive.t.run(SourceFile:62)

```
