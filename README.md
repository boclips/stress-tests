# Stress tests

- Download jmeter 5.0
- Run the following

(Make sure jmeter is in the PATH)

```
# For 100 concurrent users, delaying 1s between thread starts
./run-registered-user-journey 100 1
```

To see results

```
open /tmp/webreports/index.html
```

To edit a journey
```
jmeter -t partial-login-teachers-boclips.jmx
```