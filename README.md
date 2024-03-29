# Gpxtools

Command line tools useful to manipulate GPX (GPS eXchange Format) files.

## gpx-rm-false-points

Command line utility to remove false points from gpx file.

### Usage

```
gpx-rm-false-points [-h] [-o OUTPUT] [-s SPEED_THRESHOLD] file
```

#### Positional arguments:
```
  file                  gpx file
```

#### Optional arguments:
```
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        output gpx filename (default: output.gpx)
  -s SPEED_THRESHOLD, --speed-threshold SPEED_THRESHOLD
                        speed threshold (km/h) (default: 100)
```

## Requirements

```bash
pip3 install -r requirements.txt
```
