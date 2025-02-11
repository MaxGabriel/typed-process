## 0.2.4.1

* Fix a `Handle` leak in `withProcessInterleave` and its derivatives.

## 0.2.4.0

* Add `readProcessInterleaved` and `readProcessInterleaved_` to support
  capturing output from stdout and stderr in a single ByteString value.

## 0.2.3.0

* Add support for the single-threaded runtime via polling

## 0.2.2.0

* Add inherit versions of setter functions

## 0.2.1.0

* Add `readProcessStdout`, `readProcessStdout_`, `readProcessStderr`, and `readProcessStderr_`
* Do not show modified environment information in exceptions

## 0.2.0.0

* Remove dependency on `conduit` and `conduit-extra`. Relevant code added to
  `Data.Conduit.Process.Typed` in `conduit-extra-1.2.1`.

## 0.1.1

* Introduce 'unsafeProcessHandle' function

## 0.1.0.1

* Fix bug in `waitForProcess` that caused exit code to be lost
* Minor doc improvements

## 0.1.0.0

* Initial commit
