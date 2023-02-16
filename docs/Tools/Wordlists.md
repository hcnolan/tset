- [SecLists](https://github.com/danielmiessler/SecLists)  
- [wordlistctl](https://github.com/BlackArch/wordlistctl)   
- https://inventory.raw.pm/tools.html#title-tools-cracking

# Generating Wordlists  
- [Mentalist](https://github.com/sc0tfree/mentalist) - given a list, creates variations of it (i.e. hello -> h3ll0)  
- [CeWL](https://github.com/digininja/CeWL) - grab words from a URL  
    - e.g. download all words from example.org with a depth of 2: `cewl -d 2 -w $(pwd)/example.txt https://example.org`  
- [TTPassGen](https://github.com/tp7309/TTPassGen)  
    - e.g. create wordlist containing all combinations of 4 digits `ttpassgen --rule '[?d]{4:4:*}' out.txt`  
    - all lowercase character combinations of length 1 - 3 `ttpassgen --rule '[?l]{1:3:*}' out.txt`  
    - combination of the above: `ttpassgen --dictlist 'pin.txt,abc.txt' --rule '$0[-]{1}$1' combination.txt`