A java agent to generate /tmp/perf-<pid>.map files for JITted methods for use with `perf`

## Build

    cmake .
    make

## Use

Add `-agentpath:<dir>/libperfmap.so` to the java command line.
