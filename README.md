# Stress tests

- Download jmeter 5.0
- Run the following
```
mkdir -p /tmp/webreports
rm -rf /tmp/webreports/*
jmeter -n -t ~/workspace/stress-tests/partial-login-teachers-boclips.jmx -e -o /tmp/webreports/
```
