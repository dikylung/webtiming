# Latency Measurement for Content Download

This is a simple script to measure Time to First Byte (TTFB) and Time to Content Download (TTCD) using curl and bc. The script is tested on MacOS Ventura
 13.4

## Usage:

### Single Run
```
ttcd https://example.com
```
### Run it 10 times
```
seq 10 | xargs -n 1 ttcd https://example.com
```
