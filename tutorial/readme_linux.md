Set up FFglitch on Linux
========================

- Either run this one magic command:
```
wget https://ffglitch.org/pub/bin/linux64/ffglitch-0.10.2-linux-x86_64.zip && \
unzip x ffglitch-0.10.2-linux-x86_64.zip && \
mkdir -p bin && \
mv ffglitch-0.10.2-linux-x86_64/* bin/ && \
rm -rf ffglitch-0.10.2-linux-x86_64 && \
rm ffglitch-0.10.2-linux-x86_64.zip
```

Or run the commands separately:
- Download FFglitch:
```
wget https://ffglitch.org/pub/bin/linux64/ffglitch-0.10.2-linux-x86_64.zip
```
- Unpack it:
```
unzip x ffglitch-0.10.2-linux-x86_64.zip
```
- Move its contents to a directory named `bin`:
```
mkdir -p bin
mv ffglitch-0.10.2-linux-x86_64/* bin/
```
- Cleanup
```
rm -rf ffglitch-0.10.2-linux-x86_64
rm ffglitch-0.10.2-linux-x86_64.zip
```
