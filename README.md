# Racaty-DL
CLI Racaty downloader written in Python. JS execution and BSoup-**FREE**. 

# Usage
Download two files to default directory:
```bash
python3 racaty-dl.py -u https://racaty.io/xxxxxxxxxxxx
```

Download from text file to "/home/user/Racaty_downloads":   
```bash
python3 racaty-dl.py /home/user/links.txt -o /home/user/Racaty_downloads
```

```bash
██████╗  █████╗  ██████╗ █████╗ ████████╗██╗   ██╗     ██████╗ ██╗     
██╔══██╗██╔══██╗██╔════╝██╔══██╗╚══██╔══╝╚██╗ ██╔╝     ██╔══██╗██║     
██████╔╝███████║██║     ███████║   ██║    ╚████╔╝█████╗██║  ██║██║     
██╔══██╗██╔══██║██║     ██╔══██║   ██║     ╚██╔╝ ╚════╝██║  ██║██║     
██║  ██║██║  ██║╚██████╗██║  ██║   ██║      ██║        ██████╔╝███████╗
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝   ╚═╝      ╚═╝        ╚═════╝ ╚══════╝

usage: racaty-dl.py [-h] -u URLS [URLS ...] [-o OUTPUT_PATH] [-ov]

optional arguments:
  -h, --help            show this help message and exit
  -u URLS [URLS ...], --urls URLS [URLS ...]
                        URLs separated by a space or an abs path to a txt
                        file.
  -o OUTPUT_PATH, --output-path OUTPUT_PATH
                        Abs output directory.
  -ov, --overwrite      Overwrite file if already exists.
```
