
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
