#### Test 50242285e132180_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  760): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=1865 uid=1001 gids={41001, 3002, 3001, 3003, 2001, 1028, 1015}
--------- beginning of /dev/log/main
D/QcrilMsgTunnelAutoboot( 1865): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 1865): onCreate method
D/QcrilMsgTunnelIfaceManager( 1865): : Instantiated
V/QcrilMsgTunnelSocket( 1865): Starting QcRilReceiver
D/QcrilMsgTunnelIfaceManager( 1865):  Registered for UNSOL OEM HOOK Responses to deliver external apps
D/QcrilMsgTunnelSocket( 1865): Connecting to socket android.net.LocalSocket@425f56c0 impl:android.net.LocalSocketImpl@425f56e8 fd:FileDescriptor[42]
I/QcrilMsgTunnelSocket( 1865): Connected to 'qmux_radio/rild_oem0' socket
V/QcrilMsgTunnelSocket( 1865): Before reading offset = 0 remaining = 4 countRead = 0
I/ActivityManager(  760): Start proc com.google.android.email for broadcast com.google.android.email/com.android.email.service.EmailBroadcastReceiver: pid=1879 uid=10036 gids={50036, 3003, 1028, 1015}
D/ActivityThread( 1879): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/ActivityThread( 1879): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/ActivityThread( 1879): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
I/ActivityManager(  760): Delay finish: com.google.android.email/com.android.email.service.EmailBroadcastReceiver
D/dalvikvm( 1879): GC_CONCURRENT freed 199K, 2% free 16911K/17144K, paused 2ms+3ms, total 18ms
I/Email   ( 1879): Observing account changes for notifications
W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  760): Delaying start of: ServiceRecord{42cb4f60 u0 com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService}
I/ActivityManager(  760): Start proc com.google.android.exchange for service com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService: pid=1906 uid=10037 gids={50037, 3003, 1028, 1015}
I/ActivityManager(  760): Killing 1422:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=1919 uid=10051 gids={50051, 3003, 1028, 1015, 3002}
I/ActivityManager(  760): Killing 1363:com.google.android.apps.maps/u0a57 (adj 15): empty #17
I/dalvikvm( 1919): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 1919): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 1919): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0000
E/dalvikvm( 1919): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0037
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
I/dalvikvm( 1919): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0000
E/dalvikvm( 1919): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
I/dalvikvm( 1919): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 1919): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Ldqp;)
D/dalvikvm( 1919): GC_CONCURRENT freed 239K, 2% free 16881K/17152K, paused 2ms+2ms, total 14ms
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 1919): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1919): Link of class 'Ldqp;' failed
I/dalvikvm( 1919): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 1919): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1919): Link of class 'Lax;' failed
E/dalvikvm( 1919): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 1919): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1919): Link of class 'Laz;' failed
E/dalvikvm( 1919): Could not find class 'az', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 1919): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 1919): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 1919): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1919): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 1919): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 1919): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1919): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 1919): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1919): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 1919): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 1919): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 1919): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 1919): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x23 at 0x0005
I/dalvikvm( 1919): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0009
W/dalvikvm( 1919): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 1919): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 1919): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 1919): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 1919): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 1919): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
D/dalvikvm( 1919): VFY: replacing opcode 0x1f at 0x000c
D/dalvikvm( 1919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1919): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1919): VFY: replacing opcode 0x62 at 0x0006
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 1919): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1919): Link of class 'Lax;' failed
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 1919): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1919): Link of class 'Laz;' failed
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
D/dalvikvm( 1919): GC_CONCURRENT freed 322K, 3% free 17023K/17388K, paused 2ms+0ms, total 10ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 1919): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425f41c8
D/dalvikvm( 1919): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425f41c8
D/dalvikvm( 1919): GC_CONCURRENT freed 267K, 2% free 17269K/17564K, paused 2ms+2ms, total 25ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 2ms
I/dalvikvm( 1919): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 1919): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0076
I/Babel_SMS( 1919): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 1919): MmsConfig.loadMmsSettings
I/Babel_SMS( 1919): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 1919): MmsConfig.loadFromDatabase
D/dalvikvm( 1919): GC_CONCURRENT freed 242K, 2% free 17541K/17812K, paused 3ms+1ms, total 26ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 3ms
E/Babel_SMS( 1919): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 1919): MmsConfig.loadFromResources
E/Babel_SMS( 1919): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 1919): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 1919): ApnsOta: OTA version -1
W/dalvikvm( 1919): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 1919): Link of class 'Lfzc;' failed
E/dalvikvm( 1919): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 1919): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
D/dalvikvm( 1919): GC_CONCURRENT freed 251K, 2% free 17799K/18084K, paused 3ms+1ms, total 12ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 3ms
I/dalvikvm( 1919): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 1919): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 1919): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 1919): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 1919): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 1919): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 1919): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 1919): Link of class 'Lfzc;' failed
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
W/Settings( 1919): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 1919): startup - clean
I/dalvikvm( 1919): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x000d
I/Babel   ( 1919): deleted: false for 0
D/dalvikvm( 1919): GC_CONCURRENT freed 307K, 2% free 18001K/18340K, paused 2ms+1ms, total 13ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 3ms
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 1919): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 1919): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1919): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 1919): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 1919): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1919): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 1919): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 1919): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 1919): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 1919): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
V/Babel   ( 1919): babel boot account: thalitester@gmail.com
I/dalvikvm( 1919): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 1919): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 1919): VFY: replacing opcode 0x6e at 0x0074
I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
I/vclib   ( 1919): onServiceConnected
W/Babel   ( 1919): Attempted to change video mute state without an active call.
D/dalvikvm( 1919): GC_CONCURRENT freed 224K, 2% free 18285K/18532K, paused 3ms+4ms, total 33ms
,D/dalvikvm( 1919): GC_CONCURRENT freed 220K, 2% free 18584K/18848K, paused 1ms+1ms, total 14ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm(  760): GC_EXPLICIT freed 776K, 10% free 23631K/26116K, paused 1ms+3ms, total 45ms
D/dalvikvm( 1919): GC_CONCURRENT freed 194K, 2% free 18988K/19240K, paused 2ms+2ms, total 24ms
E/dalvikvm( 1919): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 1919): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
I/ActivityManager(  760): Resuming delayed broadcast
D/dalvikvm( 1919): VFY: replacing opcode 0x1f at 0x0014
I/ActivityManager(  760): Killing 1078:com.android.printspooler/u0a64 (adj 15): empty #17
D/dalvikvm( 1919): GC_FOR_ALLOC freed 434K, 3% free 19178K/19696K, paused 13ms, total 14ms
D/dalvikvm( 1919): GC_FOR_ALLOC freed 196K, 3% free 19362K/19952K, paused 14ms, total 14ms
I/dalvikvm-heap( 1919): Grow heap (frag case) to 19.432MB for 521860-byte allocation
D/dalvikvm( 1302): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1302): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1302): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1919): GC_FOR_ALLOC freed 254K, 5% free 19618K/20464K, paused 17ms, total 17ms
D/dalvikvm( 1302): GC_FOR_ALLOC freed 59K, 5% free 17812K/18560K, paused 12ms, total 12ms
D/dalvikvm( 1919): GC_FOR_ALLOC freed 628K, 5% free 19548K/20464K, paused 15ms, total 15ms
D/dalvikvm( 1919): GC_FOR_ALLOC freed 126K, 4% free 19676K/20464K, paused 14ms, total 14ms
I/dalvikvm-heap( 1919): Grow heap (frag case) to 19.738MB for 520922-byte allocation
D/dalvikvm( 1919): GC_FOR_ALLOC freed 254K, 5% free 19931K/20976K, paused 15ms, total 15ms
D/AndroidRuntime( 1956): 
D/AndroidRuntime( 1956): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1956): CheckJNI is OFF
D/dalvikvm( 1919): GC_FOR_ALLOC freed 750K, 5% free 19989K/20976K, paused 20ms, total 20ms
D/dalvikvm( 1956): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 1956): Added shared lib libjavacore.so 0x0
D/dalvikvm( 1302): GC_FOR_ALLOC freed 126K, 5% free 17805K/18560K, paused 11ms, total 11ms
D/dalvikvm( 1956): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 1956): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 1956): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1919): GC_FOR_ALLOC freed 254K, 4% free 20243K/20976K, paused 15ms, total 15ms
D/dalvikvm( 1956): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
E/dalvikvm( 1302): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1302): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1302): VFY: replacing opcode 0x1f at 0x000e
D/dalvikvm( 1302): GC_FOR_ALLOC freed 191K, 4% free 17850K/18560K, paused 12ms, total 12ms
E/dalvikvm( 1302): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1302): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
D/dalvikvm( 1302): VFY: replacing opcode 0x1f at 0x00ef
W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1302): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1302): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1302): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1302): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1302): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1302): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1302): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/dalvikvm( 1302): DexOpt: unable to optimize static field ref 0x00a2 at 0x0c in Lcom/google/android/gms/checkin/d;.a
D/dalvikvm( 1919): GC_CONCURRENT freed 760K, 4% free 20627K/21420K, paused 3ms+5ms, total 26ms
D/dalvikvm( 1302): GC_FOR_ALLOC freed 134K, 4% free 17872K/18560K, paused 11ms, total 11ms
D/GCM     ( 1302): COMPAT: Multi user not supported
D/GCM     ( 1138): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1302): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr(  984): DispatchingService.onCreate()
D/dalvikvm( 1138): GC_FOR_ALLOC freed 160K, 4% free 18160K/18732K, paused 18ms, total 18ms
I/CheckinService( 1302): Checkin interval check for package: unspecified last checkin: 1449470925449 min interval config: 0 actual interval: 30161291
D/dalvikvm(  984): GC_CONCURRENT freed 377K, 3% free 17868K/18344K, paused 1ms+1ms, total 16ms
D/AndroidRuntime( 1956): Calling main entry com.android.commands.am.Am
I/CheckinService( 1302): Disabling old GoogleServicesFramework version
W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 1956
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (122 us)
D/dalvikvm(  760): GC_FOR_ALLOC freed 152K, 10% free 23614K/26116K, paused 36ms, total 36ms
I/dalvikvm-heap(  760): Grow heap (frag case) to 23.909MB for 856096-byte allocation
D/dalvikvm( 1919): GC_CONCURRENT freed 389K, 2% free 21550K/21968K, paused 2ms+2ms, total 23ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm(  760): GC_FOR_ALLOC freed 10K, 10% free 24439K/26956K, paused 40ms, total 40ms
D/dalvikvm( 1302): GC_FOR_ALLOC freed 181K, 4% free 17930K/18560K, paused 16ms, total 16ms
D/FileApkUtils( 1302): Spent 39ms computing apk sha1.
D/FileApkUtils( 1302): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 1302): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1302): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
D/dalvikvm(  760): GC_FOR_ALLOC freed 1K, 10% free 24439K/26956K, paused 41ms, total 41ms
I/dalvikvm-heap(  760): Grow heap (frag case) to 24.715MB for 856096-byte allocation
D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 10% free 25275K/27796K, paused 35ms, total 35ms
D/AndroidRuntime( 1956): Shutting down VM
D/dalvikvm( 1956): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1996 uid=10115 gids={50115, 3003, 3001, 3002}
I/SearchController( 1196): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1196): mic_close
D/SystemUpdateService( 1302): onCreate
D/dalvikvm( 1302): GC_FOR_ALLOC freed 115K, 4% free 17958K/18560K, paused 16ms, total 16ms
D/GmsModuleFndr( 1302): Beginning GMS chimera module scan
D/dalvikvm( 1919): GC_CONCURRENT freed 1122K, 5% free 22045K/23200K, paused 1ms+1ms, total 60ms
D/dalvikvm( 1919): WAIT_FOR_CONCURRENT_GC blocked 53ms
V/WebViewChromiumFactoryProvider( 1996): Binding Chromium to main looper Looper (main, tid 1) {425ed950}
I/ActivityManager(  760): Killing 1542:com.google.android.dialer/u0a8 (adj 15): empty #17
I/LibraryLoader( 1996): Expected native library version number "",actual native library version number ""
I/chromium( 1996): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 1996): Initializing chromium process, renderers=0
D/dalvikvm( 1302): GC_FOR_ALLOC freed 3K, 4% free 17991K/18560K, paused 14ms, total 14ms
I/dalvikvm-heap( 1302): Grow heap (frag case) to 17.611MB for 16400-byte allocation
D/dalvikvm( 1302): GC_FOR_ALLOC freed <1K, 4% free 18007K/18580K, paused 17ms, total 17ms
I/MicroHotwordRecognitionRunner( 1196): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1196): Stopping hotword detection.
D/dalvikvm( 1302): GC_FOR_ALLOC freed <1K, 4% free 18006K/18580K, paused 15ms, total 15ms
I/dalvikvm-heap( 1302): Grow heap (frag case) to 17.626MB for 16400-byte allocation
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426a7a48:true
D/BluetoothAdapter( 1996): 1113600232: getState() :  mService = null. Returning STATE_OFF
D/dalvikvm( 1302): GC_FOR_ALLOC freed 1K, 4% free 18021K/18600K, paused 15ms, total 15ms
I/CheckinService( 1302): Checking schedule, now: 1449501087091 next: 1449513414402
I/CheckinService( 1302): active receiver: disabled
D/SystemUpdateService( 1302): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/dalvikvm( 1302): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1302): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
D/dalvikvm( 1302): VFY: replacing opcode 0x6e at 0x040d
D/dalvikvm( 1302): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1302): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1302): VFY: replacing opcode 0x62 at 0x0022
D/ChimeraCfgMgr( 1302): Beginning module configuration check
I/Adreno-EGL( 1996): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
D/ChimeraCfgMgr( 1302): Module APKs unchanged, check complete
V/AuthZen ( 1302): Handling intent: android.intent.action.BOOT_COMPLETED
I/GCoreUlr(  984): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1302): Handling event: android.intent.action.BOOT_COMPLETED
W/Auth    ( 1138): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/chromium( 1996): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 1996): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 1996): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 1996): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 1996): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 1996): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
V/GLSActivity( 1138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1996): VFY: replacing opcode 0x6e at 0x0008
,V/GLSActivity( 1138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 1996): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 1996): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 1996): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 1996): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 1996): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 1996): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 1996): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 1996): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 1996): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 1996): CordovaWebView is running on device made by: LGE
,D/dalvikvm( 1302): GC_FOR_ALLOC freed 293K, 3% free 18075K/18600K, paused 20ms, total 20ms
,V/GmsCoreStatsServiceLauncher( 1302): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/SystemUpdateService( 1302): active receiver: enabled
,W/BaseAppContext( 1302): Using Auth Proxy for data requests.
,W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1302): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1302): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1302): VFY: replacing opcode 0x6e at 0x00bb
,D/OpenGLRenderer( 1996): Enabling debug mode 0
,W/AwContents( 1996): nativeOnDraw failed; clearing to background color.
,I/EventLogService( 1302): Aggregate from 1449498942130 (log), 1449498942130 (data)
,I/SystemUpdateService( 1302): Already downloaded, skipping offpeak checks.
,D/PersistentNotificationBroadcastReceiver( 1138): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +355ms
,I/dalvikvm( 1302): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1302): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1302): VFY: replacing opcode 0x6e at 0x002f
,D/dalvikvm( 1302): GC_CONCURRENT freed 335K, 3% free 18174K/18600K, paused 3ms+5ms, total 31ms
,I/ActivityManager(  760): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=2056 uid=10057 gids={50057, 3003, 1028, 1015}
,I/AuthZen ( 1302): Fetching signing key...
,I/SystemUpdateService( 1302): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/AuthZen ( 1302): Signing key fetched successfully!
,I/GCoreUlr(  984): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/dalvikvm( 1302): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/BaseAppContext( 1302): Using Auth Proxy for data requests.
I/GCoreUlr(  984): Unbound from all location providers
,D/dalvikvm( 1302): GC_CONCURRENT freed 305K, 3% free 18315K/18692K, paused 3ms+2ms, total 19ms
,I/DownloadAttempt( 1302): current file is /cache/update.zip
,I/DownloadAttempt( 1302): mSize 2571501 mDownloaded 2571501
D/AuthZenTransactionCache( 1302): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1302): Clearing transaction cache
I/SystemUpdateService( 1302): status is 0 (complete)
I/SystemUpdateService( 1302): now status is 0 (complete)
I/SystemUpdateService( 1302): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1302): file has been verified
,I/SystemUpdateService( 1302): OTA package size = 2571501
,I/GCoreUlr(  984): DispatchingService.onDestroy()
,I/GCoreUlr(  984): Stopping handler for UlrDispSvcFast
,I/SystemUpdateService( 1302): showing system update notification
,I/GCoreUlr(  984): Unbound from all location providers
,D/dalvikvm( 2056): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x425f3b38
,D/dalvikvm( 1302): GC_CONCURRENT freed 433K, 3% free 18317K/18784K, paused 2ms+3ms, total 18ms
,D/SystemUpdateService( 1302): onDestroy
,D/dalvikvm( 2056): GC_CONCURRENT freed 336K, 3% free 16841K/17208K, paused 3ms+7ms, total 48ms
,D/dalvikvm( 2056): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x425f3b38
,D/dalvikvm( 2056): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x425f3b38
,D/dalvikvm( 2056): GC_CONCURRENT freed 231K, 2% free 17074K/17336K, paused 3ms+2ms, total 18ms
,I/chromium( 1996): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 1996): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 2056): GC_CONCURRENT freed 329K, 3% free 17233K/17592K, paused 4ms+2ms, total 26ms
,D/JsMessageQueue( 1996): Set native->JS mode to OnlineEventsBridgeMode
,I/dalvikvm( 2056): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2056): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2056): VFY: replacing opcode 0x6e at 0x01fb
I/ActivityManager(  760): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2086 uid=10071 gids={50071, 3003, 1028, 1015}
I/ActivityManager(  760): Killing 1594:com.google.android.configupdater/u0a2 (adj 15): empty #17
,D/dalvikvm( 1996): GC_CONCURRENT freed 279K, 2% free 16923K/17232K, paused 1ms+1ms, total 33ms
I/dalvikvm( 2056): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2056): VFY: unable to resolve virtual method 556: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2056): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2056): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.apps.gmm.iamhere.ble.o.b
W/dalvikvm( 2056): VFY: unable to resolve virtual method 1434: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 2056): VFY: replacing opcode 0x6e at 0x00a6
I/dalvikvm( 2056): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.c
W/dalvikvm( 2056): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2056): VFY: replacing opcode 0x6e at 0x01c0
,D/dalvikvm( 2056): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x425f3b38
,D/dalvikvm( 2056): GC_CONCURRENT freed 284K, 2% free 17396K/17708K, paused 3ms+3ms, total 18ms
,D/dalvikvm( 1996): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425f1fe0
D/dalvikvm( 1996): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425f1fe0
D/jxcore_app_log( 1996): JniHelper::setJavaVM(0x414d7f00), pthread_self() = 1978065936
,D/JX-Cordova( 1996): jxcore cordova android initializing
,W/com.google.a.a.b.d.a( 2056): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429c5140:true
,D/dalvikvm( 1996): GC_CONCURRENT freed 251K, 2% free 17148K/17428K, paused 3ms+2ms, total 16ms
,D/dalvikvm( 1996): GC_FOR_ALLOC freed 319K, 3% free 17208K/17592K, paused 9ms, total 9ms
,W/jxcore-log( 1996): Initializing JXcore engine
,W/jxcore-log( 1996): JXcore engine is ready
,D/dalvikvm( 1996): GC_CONCURRENT freed 257K, 3% free 17342K/17736K, paused 1ms+1ms, total 11ms
,D/dalvikvm( 1996): WAIT_FOR_CONCURRENT_GC blocked 10ms
,W/jxcore-log( 1996): Starting JXcore engine
,E/dalvikvm( 2086): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
,W/dalvikvm( 2086): VFY: unable to resolve new-instance 404 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 2086): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 2086): Unable to resolve superclass of Lal; (761)
,W/dalvikvm( 2086): Link of class 'Lal;' failed
E/dalvikvm( 2086): Could not find class 'al', referenced from method b.a
W/dalvikvm( 2086): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
D/dalvikvm( 2086): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2086): Unable to resolve superclass of Lan; (761)
W/dalvikvm( 2086): Link of class 'Lan;' failed
E/dalvikvm( 2086): Could not find class 'an', referenced from method b.a
W/dalvikvm( 2086): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 2086): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 2086): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 2086): VFY: unable to resolve virtual method 5625: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 2086): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 2086): VFY: unable to resolve virtual method 5440: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 2086): GC_CONCURRENT freed 259K, 2% free 16859K/17148K, paused 2ms+1ms, total 15ms
,W/dalvikvm( 2086): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 2086): Could not find class 'android.app.RemoteInput[]', referenced from method b.b
W/dalvikvm( 2086): VFY: unable to resolve new-array 12965 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 2086): VFY: replacing opcode 0x23 at 0x0007
,D/dalvikvm( 2086): DexOpt: unable to opt direct call 0x09cd at 0x0e in Lb;.a
,W/dalvikvm( 2086): Unable to resolve superclass of Lal; (761)
W/dalvikvm( 2086): Link of class 'Lal;' failed
D/dalvikvm( 2086): DexOpt: unable to opt direct call 0x0741 at 0x08 in Lb;.a
W/dalvikvm( 2086): Unable to resolve superclass of Lan; (761)
,W/dalvikvm( 2086): Link of class 'Lan;' failed
D/dalvikvm( 2086): DexOpt: unable to opt direct call 0x08c3 at 0x2c in Lb;.a
,D/dalvikvm( 2086): DexOpt: unable to opt direct call 0x0a11 at 0x0f in Lb;.b
,I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eau.a
,W/dalvikvm( 2086): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2086): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2086): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2086): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2086): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2086): VFY: unable to resolve instance field 46
,D/dalvikvm( 2086): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2086): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2086): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2086): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 2086): GC_CONCURRENT freed 304K, 2% free 16996K/17328K, paused 4ms+3ms, total 16ms
D/dalvikvm( 2086): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2086): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 2086): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x425e5a10
D/dalvikvm( 2086): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x425e5a10
D/dalvikvm( 2086): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x425e5a10, skipping init
D/dalvikvm( 2086): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x425e5a10
D/dalvikvm( 2086): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x425e5a10
V/JNIHelp ( 2086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/jxcore-log( 1996): Platform android
W/jxcore-log( 1996): 
,W/jxcore-log( 1996): Process ARCH arm
W/jxcore-log( 1996): 
,D/dalvikvm( 2086): GC_CONCURRENT freed 310K, 2% free 17197K/17536K, paused 1ms+4ms, total 14ms
,D/dalvikvm( 2086): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2086): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x425e5a10
,D/dalvikvm( 2086): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x425e5a10
D/dalvikvm( 2086): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x425e5a10
,D/dalvikvm( 2086): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x425e5a10
,I/jxcore-log( 1996): JXcore Cordova bridge is ready!
I/jxcore-log( 1996): 
,W/jxcore-log( 1996): JXcore engine is started
,D/dalvikvm( 2086): GC_CONCURRENT freed 195K, 2% free 17415K/17656K, paused 2ms+1ms, total 11ms
,E/jxcore-log( 1996): >> LGE-Nexus 5
E/jxcore-log( 1996): 
,I/ProviderInstaller( 2086): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 1996): Total memory 1945137152
I/jxcore-log( 1996): 
I/jxcore-log( 1996): Free memory 906174464
I/jxcore-log( 1996): 
I/jxcore-log( 1996): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1996): 
,I/jxcore-log( 1996): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1996): 
,I/jxcore-log( 1996): userPath [ 'www' ]
I/jxcore-log( 1996): 
,I/jxcore-log( 1996): Size 1080 1776
I/jxcore-log( 1996): 
,I/jxcore-log( 1996): Screen Brightness 1
I/jxcore-log( 1996): 
,E/jxcore-log( 1996): Dummy Error Log.
E/jxcore-log( 1996): 
,E/YouTube MDX( 2086): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 2086): GC_CONCURRENT freed 319K, 2% free 17603K/17900K, paused 3ms+2ms, total 18ms
I/dalvikvm( 2086): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2086): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2086): VFY: replacing opcode 0x71 at 0x0046
,I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 2086): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2086): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 2086): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0220
,D/dalvikvm( 2086): DexOpt: --- BEGIN 'ads-131876442.jar' (bootstrap=0) ---
,D/dalvikvm( 2086): GC_CONCURRENT freed 306K, 2% free 17799K/18132K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 2130): DexOpt: load 3ms, verify+opt 5ms, 188892 bytes
,D/dalvikvm( 2086): DexOpt: --- END 'ads-131876442.jar' (success) ---
,D/dalvikvm( 2086): DEX prep '/data/data/com.google.android.youtube/cache/ads-131876442.jar': unzip in 4ms, rewrite 43ms
,D/dalvikvm( 2086): GC_CONCURRENT freed 298K, 2% free 18013K/18340K, paused 3ms+3ms, total 23ms
,D/dalvikvm( 2086): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2086): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2807: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2808: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2815: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2816: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method aex.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2832: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method aex.getPackageInstaller
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method aex.getUserBadgedDrawableForDensity
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2852: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method aex.getUserBadgedIcon
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2086): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method aex.getUserBadgedLabel
W/dalvikvm( 2086): VFY: unable to resolve virtual method 2854: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2086): VFY: replacing opcode 0x6e at 0x0002
W/InstanceID/Rpc( 2086): Found 10007
I/ActivityManager(  760): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,D/dalvikvm( 2086): GC_CONCURRENT freed 254K, 2% free 18257K/18460K, paused 3ms+4ms, total 33ms
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,W/BroadcastQueue(  760): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.apps.plus/com.google.android.libraries.social.notifications.impl.BootCompletedReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  760): Killing 1629:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,D/WearableService(  984): callingUid 10007, callindPid: 984
,E/MDM     (  984): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  760): Killing 1217:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/LocationInitializer( 1302): Restart initialization of location
I/ActivityManager(  760): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/dalvikvm( 1138): GC_EXPLICIT freed 320K, 4% free 18090K/18732K, paused 2ms+3ms, total 23ms
,W/GCoreFlp(  984): No location to return for getLastLocation()
,W/FusedLocationProvider( 1138): location=null
,I/ActivityManager(  760): Resuming delayed broadcast
D/GCM     ( 1138): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1138): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1138): Proximity feature is not enabled.
,V/GLSActivity( 1138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  760): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,V/GmsCoreStatsServiceLauncher( 1302): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  760): Resuming delayed broadcast
,E/MDM     (  984): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  760): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1302): Restart initialization of location
,W/GCoreFlp(  984): No location to return for getLastLocation()
,W/FusedLocationProvider( 1138): location=null
,I/ActivityManager(  760): Resuming delayed broadcast
D/GCM     ( 1138): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1138): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1138): Proximity feature is not enabled.
,V/GLSActivity( 1138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  760): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,D/dalvikvm( 1138): GC_FOR_ALLOC freed 216K, 4% free 18060K/18732K, paused 15ms, total 15ms
,V/GmsCoreStatsServiceLauncher( 1302): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  760): Resuming delayed broadcast
,I/jxcore-log( 1996): getBuffer is called!!!!
I/jxcore-log( 1996): 
,I/ActivityManager(  760): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2189 uid=10058 gids={50058, 3003, 1028, 1015}
,I/MultiDex( 2189): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 2189): install
,I/MultiDex( 2189): MultiDexExtractor.load(/data/app/com.google.android.music-1.apk, false)
,I/MultiDex( 2189): loading existing secondary dex files
,I/MultiDex( 2189): load found 1 secondary dex files
,I/MultiDex( 2189): install done
,D/dalvikvm( 1996): GC_CONCURRENT freed 652K, 5% free 17080K/17884K, paused 2ms+2ms, total 12ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 234K, 2% free 16901K/17168K, paused 2ms+3ms, total 17ms
,D/dalvikvm( 1996): GC_CONCURRENT freed 387K, 5% free 17126K/17884K, paused 1ms+2ms, total 11ms
,I/BaseStore( 2189): Store database version: 123
,I/dalvikvm( 2189): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
W/dalvikvm( 2189): VFY: unable to resolve virtual method 613: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2189): VFY: replacing opcode 0x6e at 0x00c2
I/dalvikvm( 2189): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzk
W/dalvikvm( 2189): VFY: unable to resolve virtual method 981: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2189): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 1996): GC_CONCURRENT freed 414K, 4% free 17183K/17884K, paused 2ms+1ms, total 12ms
,D/dalvikvm(  760): GC_EXPLICIT freed 670K, 9% free 25421K/27796K, paused 1ms+3ms, total 47ms
,D/dalvikvm( 1996): GC_CONCURRENT freed 350K, 4% free 17267K/17884K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 1996): WAIT_FOR_CONCURRENT_GC blocked 2ms
,I/dalvikvm-heap( 1996): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 1996): GC_FOR_ALLOC freed 85K, 4% free 17309K/18012K, paused 9ms, total 9ms
,D/dalvikvm( 1996): GC_FOR_ALLOC freed <1K, 4% free 17309K/18012K, paused 8ms, total 8ms
,I/dalvikvm-heap( 1996): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 1996): GC_FOR_ALLOC freed 127K, 5% free 17373K/18204K, paused 9ms, total 9ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 329K, 3% free 17055K/17416K, paused 2ms+9ms, total 22ms
,D/dalvikvm( 1996): GC_FOR_ALLOC freed 441K, 7% free 17078K/18204K, paused 9ms, total 9ms
,D/MusicLifecycle( 2189): com.google.android.music.MusicApplication generated event: Application created
,D/dalvikvm( 2189): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2189): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2189): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2189): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2189): VFY: unable to resolve instance field 46
,D/dalvikvm( 2189): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2189): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2189): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2189): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2189): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2189): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2189): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4260b740
D/dalvikvm( 2189): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4260b740
,D/dalvikvm( 2189): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4260b740, skipping init
,D/dalvikvm( 2189): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4260b740
D/dalvikvm( 2189): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4260b740
,V/JNIHelp ( 2189): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 2189): GC_CONCURRENT freed 359K, 3% free 17183K/17572K, paused 1ms+2ms, total 12ms
,D/dalvikvm( 2189): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4260b740
,D/dalvikvm( 2189): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4260b740
D/dalvikvm( 2189): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4260b740
,D/dalvikvm( 2189): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4260b740
,I/ProviderInstaller( 2189): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2189): GMSCore installation verified
,D/dalvikvm( 2189): GC_CONCURRENT freed 215K, 2% free 17392K/17692K, paused 2ms+2ms, total 14ms
,I/BaseStore( 2189): ConfigStore database version: 1
,I/GAV2    ( 1196): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1302): Google Analytics 8.3.01 is starting up.
,D/dalvikvm( 1302): GC_CONCURRENT freed 414K, 3% free 18341K/18788K, paused 3ms+3ms, total 25ms
,I/MediaRouter( 2189): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42663050 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2189): com.google.android.music.net.NetworkMonitor generated event: Service created
I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/MusicLifecycle( 2189): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,D/MusicLifecycle( 2189): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,D/MusicLifecycle( 2189): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,D/MusicLifecycle( 2189): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,I/ActivityManager(  760): Resuming delayed broadcast
I/GHttpClientFactory( 2189): Using our fixed implementation of GMSCore's GoogleHttpClient
W/dalvikvm( 2189): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2189): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2189): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
W/dalvikvm( 2189): VFY: unable to resolve virtual method 1704: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2189): VFY: replacing opcode 0x6e at 0x00a0
I/GoogleURLConnFactory( 2189): Using platform SSLCertificateSocketFactory
,D/MusicLifecycle( 2189): com.google.android.music.download.cache.ArtCacheService generated event: Service created
,D/MusicLifecycle( 2189): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42663050 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42663050 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService generated event: Service created
,D/dalvikvm( 2189): GC_CONCURRENT freed 319K, 2% free 17498K/17848K, paused 2ms+2ms, total 18ms
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42663050 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,I/ActivityManager(  760): Resuming delayed broadcast
D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService generated event: Service created
,I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/dalvikvm( 2189): GC_FOR_ALLOC freed 130K, 3% free 17662K/18024K, paused 12ms, total 13ms
,I/MediaStoreImporter( 2189): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/MusicLifecycle( 2189): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
,D/AlertReceiver( 1701): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1701): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/GAV2    ( 1789): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 1789): GC_CONCURRENT freed 296K, 2% free 17267K/17596K, paused 3ms+4ms, total 42ms
,I/ActivityManager(  760): Killing 1196:com.google.android.googlequicksearchbox:search/u0a19 (adj 15): empty #17
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  760): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  760): Message: 2
,I/jxcore-log( 1996): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 1996): 
,I/jxcore-log( 1996): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1996): 
D/WifiService(  760): setWifiEnabled: false pid=1996, uid=10115
,D/AndroidRuntime( 2236): 
D/AndroidRuntime( 2236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2236): CheckJNI is OFF
,D/dalvikvm( 2236): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2236): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2236): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2236): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2236): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2236): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,I/ActivityManager(  760): Killing 1657:com.android.vending/u0a14 (adj 15): empty #17
,D/AndroidRuntime( 2236): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 1996:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  760): Force removing ActivityRecord{42701ab0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  760): WIN DEATH: Window{42baf458 u0 com.example.hello/com.example.hello.MainActivity}
,D/dalvikvm( 2056): GC_CONCURRENT freed 247K, 2% free 17560K/17848K, paused 2ms+1ms, total 15ms
W/PackageSettings(  760): Skipping PackageSetting{426db818 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  760): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine(  984): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  760): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService: pid=2267 uid=10019 gids={50019, 3003, 1028, 3002, 1015}
,W/Binder  (  970): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  970): java.lang.NullPointerException
W/Binder  (  970): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  970): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  970): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  970): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 1996 uid 10115
,I/LatinIME:LogUtils(  970): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,D/Launcher.Workspace( 1055): 11683562 - stripEmptyScreens()
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  760): removePackageParticipantsLocked: uid=10115 #1
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
,D/Launcher.Workspace( 1055): 11683562 - stripEmptyScreens()
,D/dalvikvm(  970): GC_CONCURRENT freed 302K, 2% free 17009K/17336K, paused 5ms+1ms, total 17ms
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  760): GC_EXPLICIT freed 1578K, 12% free 24655K/27720K, paused 1ms+9ms, total 97ms
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 2236): Shutting down VM
,D/dalvikvm( 2236): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
,D/dalvikvm( 1055): GC_EXPLICIT freed 1525K, 6% free 26256K/27808K, paused 2ms+3ms, total 29ms
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2287 uid=10011 gids={50011, 3003}
,D/dalvikvm( 2267): GC_CONCURRENT freed 247K, 2% free 16964K/17240K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 2267): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2267): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2267): GC_CONCURRENT freed 270K, 2% free 17156K/17456K, paused 1ms+2ms, total 11ms
,W/Sidekick_LocationOracleImpl( 2267): Best location was null
,I/ActivityManager(  760): Killing 1566:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/dalvikvm( 2267): GC_CONCURRENT freed 252K, 2% free 17413K/17696K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 2267): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/GCoreFlp(  984): No location to return for getLastLocation()
,D/dalvikvm( 2267): GC_FOR_ALLOC freed 233K, 3% free 17428K/17948K, paused 10ms, total 10ms
,I/dalvikvm-heap( 2267): Grow heap (frag case) to 17.538MB for 516112-byte allocation
,D/dalvikvm( 2267): GC_FOR_ALLOC freed 248K, 5% free 17683K/18456K, paused 13ms, total 13ms
,W/GCoreFlp(  984): No location to return for getLastLocation()
,W/GCoreFlp(  984): No location to return for getLastLocation()
,I/Velvet.VelvetNetworkClient( 2267): Network connection not availble
D/dalvikvm( 2267): GC_CONCURRENT freed 39K, 4% free 17723K/18456K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 2267): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/dalvikvm-heap( 2267): Grow heap (frag case) to 17.594MB for 273040-byte allocation
,W/GCoreFlp(  984): No location to return for getLastLocation()
,D/dalvikvm( 2267): GC_FOR_ALLOC freed 20K, 5% free 17968K/18724K, paused 13ms, total 13ms
,I/VS.Container( 2267): create_speech_recognizer
,D/dalvikvm(  984): GC_CONCURRENT freed 382K, 3% free 17896K/18372K, paused 2ms+1ms, total 27ms
,D/dalvikvm( 2267): No JNI_OnLoad found in /system/lib/libgoogle_hotword_jni.so 0x425f85d0, skipping init
,D/dalvikvm( 2267): GC_FOR_ALLOC freed 595K, 7% free 17509K/18724K, paused 14ms, total 14ms
,I/dalvikvm-heap( 2267): Grow heap (frag case) to 17.736MB for 640016-byte allocation
,D/dalvikvm( 2267): GC_FOR_ALLOC freed <1K, 4% free 18134K/18724K, paused 11ms, total 11ms
,I/MicroHotwordRecognitionRunner( 2267): Starting hotword detection.
,D/dalvikvm( 2267): GC_CONCURRENT freed 6K, 4% free 18140K/18724K, paused 3ms+1ms, total 12ms
,D/audio_hw_primary(  185): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  185): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
,I/iu.UploadsManager( 1302): End new media; added: 0, uploading: 0, time: 37 ms
,I/SearchController( 2267): #onHotwordDetectorStarted
,E/qdhwcomposer(  182): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  182): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=16 dpy=0 numHwLayers=5
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  182): MdpData failed to play
E/qdoverlay(  182): == Dump MdpData start ==
E/qdoverlay(  182): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  182): mOvData msmfb_overlay_data id=64
E/qdoverlay(  182): data msmfb_data offset=0 memid=52 id=0 flags=0x0 priv=0
E/qdoverlay(  182): == Dump MdpData end ==
E/qdhwcomposer(  182): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  182): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  182): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  182): hwc_set_primary: display commit fail!
,E/qdhwcomposer(  182): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  182): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=16 dpy=0 numHwLayers=5
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  182): MdpData failed to play
E/qdoverlay(  182): == Dump MdpData start ==
E/qdoverlay(  182): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  182): mOvData msmfb_overlay_data id=64
E/qdoverlay(  182): data msmfb_data offset=0 memid=52 id=0 flags=0x0 priv=0
E/qdoverlay(  182): == Dump MdpData end ==
E/qdhwcomposer(  182): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  182): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  182): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  182): hwc_set_primary: display commit fail!

```
