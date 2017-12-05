FIrst I created a credentials file in `~/.sbt/lomaven.credentials`:

```
realm=Lo Pub Maven
host=learningobjects.jfrog.io
user=merlin
password=ABCD1234
```

Then I published scalactic and scalatest:

```
sbt
> ; scalactic/publish ; scalatest/publish
```
