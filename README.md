# jre-repo
Repo JRE  
Download zip/tar package from https://adoptium.net/ into `download/`.

## Extract

```bash
./extract download/OpenJDK25U-jre_x64_linux_hotspot_25.0.5.1_2.tar.gz
```

Platform/version are taken from the filename. Output:

| archive contains | destination |
|---|---|
| `linux` | `dist/linux/vN/newjre` |
| `mac` | `dist/macos/vN/newjre` |
| `windows` | `dist/window/vN/newjre` |

Promote when ready: replace `jre` with `newjre`.

# Change log
202406 Update JRE to 17.0.11_9

202601 Add JRE 21.0.9

202611
JRE17 --> 17.0.21
JRE21 --> 21.0.13
JRE25 --> 25.0.5

