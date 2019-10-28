# Stress tests

Testing the limits of our systems.

## Prerequisits
- Download jmeter 5.0
- Make sure jmeter is on the PATH

## Run

Run the suite with 100 concurrent users, added with a 1s delay:
```
# For 100 concurrent users, delaying 1s between thread starts
./run-teacher-journeys 100 1
```

## Results

To see results:
```
open /tmp/webreports/index.html
```

## Development

To edit a journey:
```
jmeter -t partial-login-teachers-boclips.jmx
```
