```
sudo add-apt-repository "deb https://repo.sovrin.org/deb bionic stable"

sudo apt-get update -y
```
show error message after ^ this command
```
[sudo] password for rana: 
Hit:1 http://security.ubuntu.com/ubuntu bionic-security InRelease              
Hit:2 http://us.archive.ubuntu.com/ubuntu bionic InRelease                     
Hit:3 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease             
Hit:4 https://deb.nodesource.com/node_16.x bionic InRelease                    
Hit:5 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease           
Hit:6 https://repo.sovrin.org/sdk/deb bionic InRelease                   
Hit:7 https://repo.sovrin.org/deb bionic InRelease 
Reading package lists... Done                      
W: Skipping acquire of configured file 'stable/binary-amd64/Packages' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/binary-i386/Packages' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/i18n/Translation-en' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/i18n/Translation-en_US' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/dep11/Components-amd64.yml' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/dep11/icons-48x48.tar' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/dep11/icons-64x64.tar' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)
W: Skipping acquire of configured file 'stable/cnf/Commands-amd64' as repository 'https://repo.sovrin.org/deb bionic InRelease' doesn't have the component 'stable' (component misspelt in sources.list?)

```