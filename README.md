# DarkSide
DarkSide is a Python 3 app for SECURITY TESTING PURPOSES ONLY!

DarkSide is an HTTP DoS Test Tool.

Attack Vector exploited: HTTP Keep Alive + NoCache

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


