Кто перешел по ссылке в майле молодец.
Вот ошибка:
Executing Gradle task: setupDecompWorkspace --refresh-dependencies

Build info: MCreator 2020.2.14217, 1.12.2, 64-bit, 4007 MB, Windows 8.1, JVM 1.8.0_232, JAVA_HOME: C:\Program Files\Pylo\MCreator\jdk

org.gradle.tooling.GradleConnectionException: Could not install Gradle distribution from 'https://services.gradle.org/distributions/gradle-4.4-bin.zip'.


   at org.gradle.tooling.internal.consumer.DistributionFactory$ZippedDistribution.getToolingImplementationClasspath(DistributionFactory.java:139)

   at org.gradle.tooling.internal.consumer.loader.CachingToolingImplementationLoader.create(CachingToolingImplementationLoader.java:41)

   at org.gradle.tooling.internal.consumer.loader.SynchronizedToolingImplementationLoader.create(SynchronizedToolingImplementationLoader.java:44)

   at org.gradle.tooling.internal.consumer.connection.LazyConsumerActionExecutor.onStartAction(LazyConsumerActionExecutor.java:104)

   at org.gradle.tooling.internal.consumer.connection.LazyConsumerActionExecutor.run(LazyConsumerActionExecutor.java:86)

   at org.gradle.tooling.internal.consumer.connection.CancellableConsumerActionExecutor.run(CancellableConsumerActionExecutor.java:45)

   at org.gradle.tooling.internal.consumer.connection.ProgressLoggingConsumerActionExecutor.run(ProgressLoggingConsumerActionExecutor.java:61)

   at org.gradle.tooling.internal.consumer.connection.RethrowingErrorsConsumerActionExecutor.run(RethrowingErrorsConsumerActionExecutor.java:38)

   at org.gradle.tooling.internal.consumer.async.DefaultAsyncConsumerActionExecutor.lambda$run$0(DefaultAsyncConsumerActionExecutor.java:55)

   at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)

   at org.gradle.internal.concurrent.ManagedExecutorImpl$1.run(ManagedExecutorImpl.java:48)

   at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)

   at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)

   at org.gradle.internal.concurrent.ThreadFactoryImpl$ManagedThreadRunnable.run(ThreadFactoryImpl.java:56)

   at java.lang.Thread.run(Thread.java:748)

Caused by: java.net.SocketException: Permission denied: connect


   at java.net.DualStackPlainSocketImpl.connect0(Native Method)


   at java.net.DualStackPlainSocketImpl.socketConnect(DualStackPlainSocketImpl.java:79)

   at java.net.AbstractPlainSocketImpl.doConnect(AbstractPlainSocketImpl.java:350)

   at java.net.AbstractPlainSocketImpl.connectToAddress(AbstractPlainSocketImpl.java:206)

   at java.net.AbstractPlainSocketImpl.connect(AbstractPlainSocketImpl.java:188)

   at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)

   at java.net.SocksSocketImpl.connect(SocksSocketImpl.java:392)

   at java.net.Socket.connect(Socket.java:607)

   at sun.security.ssl.SSLSocketImpl.connect(SSLSocketImpl.java:666)

   at sun.security.ssl.BaseSSLSocketImpl.connect(BaseSSLSocketImpl.java:173)

   at sun.net.NetworkClient.doConnect(NetworkClient.java:180)

   at sun.net.www.http.HttpClient.openServer(HttpClient.java:463)

   at sun.net.www.http.HttpClient.openServer(HttpClient.java:558)

   at sun.net.www.protocol.https.HttpsClient.<init>(HttpsClient.java:264)

   at sun.net.www.protocol.https.HttpsClient.New(HttpsClient.java:367)

   at sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.getNewHttpClient(AbstractDelegateHttpsURLConnection.java:191)

   at sun.net.www.protocol.http.HttpURLConnection.plainConnect0(HttpURLConnection.java:1162)

   at sun.net.www.protocol.http.HttpURLConnection.plainConnect(HttpURLConnection.java:1056)

   at sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.connect(AbstractDelegateHttpsURLConnection.java:177)

   at sun.net.www.protocol.http.HttpURLConnection.getInputStream0(HttpURLConnection.java:1570)

   at sun.net.www.protocol.http.HttpURLConnection.getInputStream(HttpURLConnection.java:1498)

   at sun.net.www.protocol.https.HttpsURLConnectionImpl.getInputStream(HttpsURLConnectionImpl.java:268)

   at org.gradle.wrapper.Download.downloadInternal(Download.java:78)

   at org.gradle.wrapper.Download.download(Download.java:63)

   at org.gradle.tooling.internal.consumer.DistributionInstaller$1.run(DistributionInstaller.java:128)

TASK EXECUTION FAILED

Task completed in 47 milliseconds
