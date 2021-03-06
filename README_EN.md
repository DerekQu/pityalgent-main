[ä¸­æææ¡£](https://github.com/wuranxu/pity/blob/main/README.md)

![png](https://img.shields.io/badge/Python-3.5+-green)
![png](https://img.shields.io/badge/React-17+-blue)
![png](https://img.shields.io/badge/FastApi-green)
![png](https://img.shields.io/badge/contributors-3-green)


## ð Getting Started

1. clone code

```bash
$ git clone https://github.com/wuranxu/pity
$ cd pity
```

2. install dependencies

```bash
# å¯æ¢è±ç£æºæèæ¸åæºå®è£ä¾èµ
$ pip install -r requirements.txt
```

3. install and start redis

4. install and start mysql

5. edit config.py

  edit connection info about redis and mysql

6. start server

```bash
$ python main.py
```

7. registry

  Open your browser, enter url: `http://localhost:7777`, then you will see the page.

  First people will be `ADMIN`

![](https://gitee.com/woodywrx/picture/raw/master/2022-1-2/1641092636428-image.png)

  Sign in and enjoy `pity`ï¼

## ð Overview 

[Documents ð](http://pity.readthedocs.org/)

[Demo ð](http://121.5.2.74/)

### ð¢ About pity 

pity is an auto test tool based on `Python`+`FastApi`+`React` for api test. It's not an absolute production right now.

### â¤ï¸ Heart 

I hope pity can help someone still uses robotframework or writes script for apitest.pity can help you a lot.

### ð Features

+ [x] ð¥ absolute auth rule, support login with github

- [x] ð absolute project management

* [x] ð´ fast with FastApi

- [x] ð many options for data dependencies, you can make and use data so easy
- [x] ð¨ online http request like postman
- [x] ð· global variable for you
- [x] ð redis online
- [x] ð test plan
- [x] ð online database manager
- [x] ð° beautiful email notification
- [x] ð¹ cronjob for case
- [x] ð§ beautiful test report

## ð Coming soon 

- [ ] ð Micro Services
- [ ] ð DataFactory for developing data
- [ ] ð¸ support har/jmx to pity case
- [ ] ð CI/CDï¼like pipeline, provide openapi
- [ ] ð¼ notification
- [ ] ð support dubbo/grpc
- [ ] ð yapi
- [ ] ð½ and so on

  You can open issues to communicate with me, if you like the project, give a star will make me happy.

## ð¨ Wechat communicate group

  you can ask anything in my wechat group.

![](https://gitee.com/woodywrx/picture/raw/master/2022-1-2/1641097484952-ddff5bf23bdccaaf23fa227aa2e9957.jpg)