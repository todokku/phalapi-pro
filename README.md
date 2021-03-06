# PhalApi Pro
PHP开放平台，搭建云平台的最佳选择。基于开源的PhalApi框架打造的商业软件，官方出品。

> PhalApi专业版官网：http://pro.phalapi.net/   （可购买商业授权和源代码）  
  
> 在线演示：http://open.phalapi.net/  （管理员账号密码：admin / 123456）  

# 整体架构及业务流程

PhalApi Pro，是一套专注搭建云平台的系统软件，企业可以基于PhalApi Pro快速搭建自主的云平台、BaaS、SaaS、PaaS等平台，也可以使用PhalApi Pro开发接口给内部产品或外部客户调用。  

开放平台的整体架构及业务流程如下：  
![](http://cdn7.okayapi.com/yesyesapi_20200415115806_ea773ef9474aaf016e04cc02e6e0933e.png)  

## 整体架构

开放平台，主要由三个子系统构成，分别是：  
 - Platform开放平台
 - API开放接口
 - Admin管理后台
 
这三部分由PhalApi Pro提供，可进行二次开发。   

开发者在接入开放平台后，根据自己的需要，开发自己的客户端应用。  
此外，开放平台可以接入或需要依赖于企业已有的系统，包括但不限于企业已有的业务系统、数据库、信息库，此部分不属于PhalApi Pro提供。  

### Platform开放平台
Platform开放平台，是提供给开发者使用的平台，开发者可以是内部或外部开发者、合作伙伴、供应商、分销销等。可以进行开发者注册、创建应用、查看接口权限等操作。  

> Platform开放平台地址：http://你的域名/platform/  

### API开放接口
API开放接口，是提供给应用/客户端使用的接口服务，应用可以是自主研发的产品、项目、客户端、第三方应用或第三方系统。归根到底，API的使用对象是由开发者研发和维护的应用、程序或系统。  

> API开放接口在线文档地址：http://你的域名/docs.php 

### Admin管理后台

综上所述，Platform开放平台是提供给开发者使用的，API开放接口是提供给程序使用的。这两个子系统都是对外的，而Admin管理后台与此不同，Admin管理后台是对内的，是提供给内部管理员使用的，可以对开发者和API接口进行管理，以及其他管理操作，例如应用审核、权限分配等。   

> Admin管理后台地址：http://你的域名/admin/  


## 业务流程

业务流程，可以分别从外部开发者和内部管理员两个维度进行划分。  

### 对外的主要业务流程 
对于外部而言，即对于开发者而言，其主要业务流程是：
 
 + **第1步、注册开放平台**  
 + **第2步、创建应用并等待平台审核**  
 + **第3步、调用已经分配权限的开放接口API**
 + **第4步、开发应用**    
 
> 默认情况下，每个开发者最多可创建的应用数量为10个，可修改配置。   
 
### 对内的主要业务流程
对于内部而言，即对于平台而言，其主要业务流程是：
 
 + **第1步、审核开发者应用**  
 + **第2步、提供新的开放API接口**  
 + **第3步、分配接口权限**
 + **第4步、进行日常管理和维护**    

> 默认情况下，未分配权限的接口，开发者无权限调用。  

## 技术架构

![](http://cdn7.okayapi.com/yesyesapi_20200414112347_3ea28c8662dd5c7cad988bcf3f5b5e12.png)  

