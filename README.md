# asset
Easy way to find subdomain.

This tool created by Bash script , you need Download these two tools before :

https://github.com/tomnomnom/assetfinder

https://github.com/projectdiscovery/httpx <br>

<h1> How to download it </h1>

git clone https://github.com/viking2022/asset.git<br>
chmod 755 asset.sh<br>

this tool is for fast doing of finding subdomain , it look like you writing this : <br>
assetfinder --subs-only YOURDOMAIN.com | httpx -nc -title --content-length -status-code -silent >> YOURDOMAIN.com.txt<br>

<h1>Tool usage </h1>
./asset.sh YOURDOMAIN.com<br>
______________________________<br>

created by Viking2022
