# DarkSide
DarkSide is a Python 3 app for SECURITY TESTING PURPOSES ONLY!

DarkSide is an HTTP DoS Test Tool.

Attack Vector exploited: HTTP Keep Alive + NoCache

# Downloading 
```
git clone https://github.com/Sn8ow/DarkSide.git (as ROOT)
cd DarkSide 
chmod 777 darkside.py
./darkside.py <url> [options] or  proxychains ./darkside.py  <url>
```

# Usage

     USAGE: ./darkside.py <url> [OPTIONS]

     OPTIONS:
        Flag           Description                     Default
        -u, --useragents   File with user-agents to use                     (default: randomly generated)
        -w, --workers      Number of concurrent workers                     (default: 50)
        -s, --sockets      Number of concurrent sockets                     (default: 30)
        -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get)
        -d, --debug        Enable Debug Mode [more verbose output]          (default: False)
        -n, --nosslcheck   Do not verify SSL Certificate                    (default: True)
        -h, --help         Shows this help

## Utilities
* util/getuas.py - Fetches user-agent lists from http://www.useragentstring.com/pages/useragentstring.php subpages (ex: ./getuas.py "http://www.useragentstring.com/pages/useragentstring.php?name=All") *REQUIRES BEAUTIFULSOUP4*
* res/lists/useragents - Text lists (one per line) of User-Agent strings (from http://www.useragentstring.com)


## License
This software is distributed under the GNU General Public License version 3 (GPLv3)



## LEGAL NOTICE
THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS.

