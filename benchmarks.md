
### Sbt 1.2.8 - Scala 2.12.8

`code ~/.sbt/1.0/plugins/build.sbt`

```scala
resolvers += Resolver.url("Triplequote Plugins Releases",
        url("https://repo.triplequote.com/artifactory/sbt-plugins-release/"))(Resolver.ivyStylePatterns)
addSbtPlugin("com.triplequote" % "sbt-hydra" % "2.1.3")
addSbtPlugin("com.softwaremill.clippy" % "plugin-sbt" % "0.6.1")
addSbtPlugin("org.duhemm" % "sbt-errors-summary" % "0.6.3")
```

```bash
$ java -version
java version "1.8.0_201"
Java(TM) SE Runtime Environment (build 1.8.0_201-b09)
Java HotSpot(TM) 64-Bit Server VM (build 25.201-b09, mixed mode)
```


```shell
[success] Total time: 111 s, completed Apr 18, 2019 8:40:05 PM
sbt clean compile  922.64s user 15.22s system 594% cpu 2:37.65 total
```

`$ jabba use adopt-openj9@1.8.202-08`

```shell
[success] Total time: 135 s, completed Apr 18, 2019 8:46:57 PM
sbt clean compile  1061.69s user 28.36s system 591% cpu 3:04.20 total
```



### Sbt 1.2.8 - Scala 2.12.8

`code ~/.sbt/1.0/plugins/build.sbt`

```scala
resolvers += Resolver.url("Triplequote Plugins Releases",
        url("https://repo.triplequote.com/artifactory/sbt-plugins-release/"))(Resolver.ivyStylePatterns)
addSbtPlugin("com.triplequote" % "sbt-hydra" % "2.1.3")
```

`time sbt clean compile`

```shell
[success] Total time: 138 s, completed Apr 18, 2019 8:51:50 PM
sbt clean compile  1062.61s user 31.29s system 498% cpu 3:39.62 total
```
`

```
[success] Total time: 20 s, completed Apr 18, 2019 8:54:26 PM
sbt compile  56.81s user 3.98s system 141% cpu 43.072 total
```

```bash
$ java -version
java version "1.8.0_201"
Java(TM) SE Runtime Environment (build 1.8.0_201-b09)
Java HotSpot(TM) 64-Bit Server VM (build 25.201-b09, mixed mode)
```

`time sbt clean compile`

```
[success] Total time: 118 s, completed Apr 18, 2019 8:58:23 PM
sbt clean compile  944.18s user 16.00s system 524% cpu 3:02.97 total
```

`time sbt compile`

```
[success] Total time: 18 s, completed Apr 18, 2019 9:15:18 PM
sbt compile  70.49s user 3.06s system 169% cpu 43.280 total
```


Oracle JDK *appears* faster on my mac while other stuff is running.
