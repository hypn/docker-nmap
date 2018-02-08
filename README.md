# Nmap Docker image
A Docker image of [Nmap](https://nmap.org/).

## Usage:

    docker run --rm hypnza/nmap <options> <target>

## Example:

    ~: docker run --rm hypnza/nmap -sS example.com
    Starting Nmap 7.40 ( https://nmap.org ) at 2018-02-08 06:41 UTC
    Nmap scan report for example.com (93.184.216.34)
    Host is up (0.21s latency).
    PORT     STATE  SERVICE
    80/tcp   open   http

    Nmap done: 1 IP address (1 host up) scanned in 22.23 seconds
