# FindData Docker install
## 1. install docker (CentOS core > 3.10) [How to install docker?](https://docs.docker.com/get-started/)
```
sudo curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun
```
## 2. install docker-compose
```
sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

## 3. github get docker-compose.yml
```
git clone https://github.com/finddataio/finddata_docker.git
cd finddata_docker
sudo systemctl start docker 
sudo  docker-compose up -d --build
```

## 4. Visit Web URL: http://IP:8089
`See: hello word`   

`Request: open port on service`
## Well Done!





### Docker info (eg: CentOS Linux 7)
` 
 Data Space Used: 2 GB ;  Memory Space Used: 5 MB
`

### Lincese
