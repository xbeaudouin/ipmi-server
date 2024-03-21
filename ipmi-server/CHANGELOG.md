## 1.2.7
- Merge from upstream:
- extract all sensors that are returned by `sdr list full` command because
the `sensor` command does not work with all servers.
- extract all sensors available on the server, including power and current sensors
- allow users to provide extra params in case they need them 
(for example one can provide "-C 17" to correctly connect to the ipmi server)
- ability to chose what interface type to use when connecting to the server
  (if not provided then it will try to auto select it)
- anonymize passwords in error messages

## 1.1.27
- Debug for finding where is error with iLo

## 1.1.26
- Update docker image to more recent one

## 1.0.0
- Initial release
