# scp


Transfer files via SCP







scp |
-----|----
Supported platforms | ios, android, mac
Author | @hjanuschka



**2 Examples**

```ruby
scp(
  host: "dev.januschka.com",
  username: "root",
  upload: {
    src: "/root/dir1",
    dst: "/tmp/new_dir"
  }
)
```

```ruby
scp(
  host: "dev.januschka.com",
  username: "root",
  download: {
    src: "/root/dir1",
    dst: "/tmp/new_dir"
  }
)
```





**Parameters**

Key | Description
----|------------
  `username` | Username
  `password` | Password
  `host` | Hostname
  `port` | Port
  `upload` | Upload
  `download` | Download




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action scp
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/scp.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>
