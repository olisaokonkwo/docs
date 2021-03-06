# sh


Runs a shell command




> Allows running an arbitrary shell command.
Be aware of a specific behavior of 'sh' action with regard to the working directory. For details refer to Advanced.md


sh |
-----|----
Supported platforms | ios, android, mac
Author | @KrauseFx
Returns | Outputs the string and executes it. When running in tests, it returns the actual command instead of executing it



**2 Examples**

```ruby
sh("ls")
```

```ruby
sh("git commit -m 'My message'")
```





**Parameters**

Key | Description
----|------------
  `command` | Shell command to be executed
  `log` | Determines whether fastlane should print out the executed command itself and output of the executed command. If command line option --troubleshoot is used, then it overrides this option to true
  `error_callback` | A callback invoked with the command output if there is a non-zero exit status




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action sh
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/sh.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>
