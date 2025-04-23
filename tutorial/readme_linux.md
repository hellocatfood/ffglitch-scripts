Set up FFglitch on Linux
========================

- Either run this one magic command:
```
wget https://ffglitch.org/pub/bin/linux64/ffglitch-0.10.2-linux-x86_64.zip && \
unzip ffglitch-0.10.2-linux-x86_64.zip && \
mv ffglitch-0.10.2-linux-x86_64/* /usr/bin/ && \
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
unzip ffglitch-0.10.2-linux-x86_64.zip
```
- Move its contents to a directory named `/usr/bin`:
```
mv ffglitch-0.10.2-linux-x86_64/* /usr/bin/
```
- Cleanup
```
rm -rf ffglitch-0.10.2-linux-x86_64
rm ffglitch-0.10.2-linux-x86_64.zip
```
