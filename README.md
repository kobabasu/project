# project

## clone this repository
```
git clone github.com-kobabasu:kobabasu/project.git project

```

## run setup.sh
```
source ./setup.sh

enter project name.
```

## website setup
clone into [website repository](https://github.com/kobabasu/website) share directory

```
cd share/
git clone github.com-kobabasu:kobabasu/website.git www.example.com
```

```
+ share
  - www.example.com
  - doc.example.com
```

## vagrant up
```
cd coreos
vagrant up
vagrant ssh
```

## edit /etc/hosts
```
sudo /etc/hosts
```
add line below  
`127.0.0.1 www.example.dev`

## access by browser
https://www.example.com:3443/

## exit
```
vagrant halt
```
