# Stress tests

- Download jmeter 5.0
- Run the following
```
mkdir /tmp/webreports
bin/jmeter -n -t ~/workspace/stress-tests/partial-login-teachers-boclips.jmx -l my-results -e -o /tmp/webreports/
```
