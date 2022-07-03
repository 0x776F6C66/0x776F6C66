# Notes (tips&tricks) :)

# Python
## Python Modules
- elevate - elevate priviledges
- subprocess - execute commands e.g subprocess.run(command, shell=True, captureoutput=True)
- json, base64 - convert to respective encodings and back
- os - run shell commands
- pyautogui - keyboard and mouse e.g pressing a certain key (good for creating bots)
- keyboard - anything related to the keyboard e.g checking if a key is pressed, replaying keyboard presses
- pandas, numpy, matplotlib, opencv - Machine learning
- beautiful soup - web scraping
- urllib, requests - make web requests ans stuff

---
# GOLang
## Reducing go binaries size (shedding of extra weight) 
1. strip "unnecessary info" when building/compiling - go build -ldflags="-s -w" "/path/to/source/file"
2. Shed off extra weight from the compiled binary using upx - upx --brute "/path/to/compiled/binary" (can be applied to other binaries ??)

## Cross-Compiling
GOOS="linux" GOARCH="amd64" go build "/path/to/source/file" -- compile binary for linux amd64 machine

### Go Advantages
- cross compiling - you can compile code written in linux for a windows machine... vice-versa
- easy to learn (if you have some knowledge in programming )

---
# Osint
- whois lookups - find info about domains
- netcraft - whois except better and much more info
- google hacking - google dorking e.g
	~~~
	site:"domain name" - only info coming from the specific domain
	filetype:xml - search for files of type "xml"
	filename:users - search for files having the name "users" 
	inurl: "index of" - search for "index of" in the url
	~~~
	**MORE can be found at exploit db**
- website recon - e.g Frameworks like recon-ng
- gitrob & gitleaks - find sensitive info in git repositories
- shodan -- find devices connected to the internet e.g
	~~~
	in search bar: hostname:"domain name" -- find open ports and devices of the specified hostname
	~~~

---
# Cool Addons (firefox)
- Adblocker for Youtube - Removes all annoying ads and banners from Youtube :https://mybrowseraddon.com/adblocker-for-youtube.html
- Startpage Privacy Protection - provides private searching and online data protection
- ClearUrls - remove tracking info/elements from links
