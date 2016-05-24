```sh
stack build
sudo -u www-data stack exec --verbose stack-exec-bug-exe
  Version 1.1.2 x86_64 hpack-0.14.0
  2016-05-24 12:09:59.384192: [debug] Checking for project config at: .../stack-exec-bug/stack.yaml @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Config src/Stack/Config.hs:811:9)
  2016-05-24 12:09:59.384390: [debug] Loading project config file stack.yaml @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Config src/Stack/Config.hs:829:13)
  2016-05-24 12:09:59.385361: [debug] Checking whether stack was built with libgmp4 @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Config src/Stack/Config.hs:326:5)
  2016-05-24 12:09:59.385442: [debug] Run process: ldd .../.local/bin/stack @(stack_IZ6kIIshaMC0uV4dtbkAts:System.Process.Read src/System/Process/Read.hs:283:3)
  2016-05-24 12:09:59.391749: [debug] Stack was not built with libgmp4 @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Config src/Stack/Config.hs:330:14)
  2016-05-24 12:09:59.391865: [debug] Trying to decode .../.stack/build-plan-cache/x86_64-linux/lts-5.18.cache @(stack_IZ6kIIshaMC0uV4dtbkAts:Data.Binary.VersionTagged src/Data/Binary/VersionTagged.hs:55:5)
  2016-05-24 12:09:59.398234: [debug] Success decoding .../.stack/build-plan-cache/x86_64-linux/lts-5.18.cache @(stack_IZ6kIIshaMC0uV4dtbkAts:Data.Binary.VersionTagged src/Data/Binary/VersionTagged.hs:64:13)
  2016-05-24 12:09:59.398336: [debug] Getting system compiler version @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Setup src/Stack/Setup.hs:341:17)
  2016-05-24 12:09:59.398435: [debug] Run process: ghc --info @(stack_IZ6kIIshaMC0uV4dtbkAts:System.Process.Read src/System/Process/Read.hs:283:3)
  2016-05-24 12:09:59.411434: [debug] Asking GHC for its version @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Setup.Installed src/Stack/Setup/Installed.hs:94:13)
  2016-05-24 12:09:59.411577: [debug] Run process: ghc --numeric-version @(stack_IZ6kIIshaMC0uV4dtbkAts:System.Process.Read src/System/Process/Read.hs:283:3)
  2016-05-24 12:09:59.430591: [debug] Getting Cabal package version @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.GhcPkg src/Stack/GhcPkg.hs:165:5)
  2016-05-24 12:09:59.430725: [debug] Run process: ghc-pkg --no-user-package-db field --simple-output Cabal version @(stack_IZ6kIIshaMC0uV4dtbkAts:System.Process.Read src/System/Process/Read.hs:283:3)
  2016-05-24 12:09:59.443145: [debug] Resolving package entries @(stack_IZ6kIIshaMC0uV4dtbkAts:Stack.Setup src/Stack/Setup.hs:221:5)
  2016-05-24 12:09:59.443769: [debug] Run process: git reset --hard 153a9efe1c66d3cb73a0e307165f8006ebb41362 -- @(stack_IZ6kIIshaMC0uV4dtbkAts:System.Process.Read src/System/Process/Read.hs:283:3)
  .../stack-exec-bug/.stack-work/downloaded/RmaIptTMKNnf/Setup.lhs: removeDirectoryRecursive: permission denied (Permission denied)

```
