## GitHubAction1
 Introduction Into Continious Integration and Continious Deployment 


 # 1. initialize Git Repository

 ![](./img/1.%20created%20repo.png)


 ![](./img/1.%20clone%20repo.png) 

 # 2. Create a Simple node.js application
 2.1 

 initialize a Node.js project
 ![](./img/2.%20Npm%20init.png)

 2.2 
 create a simple express.js to serve a static web page 
 ![](./img/3.%20code%20server%20js.png)

2.3 

Add your code to the repository 
 ![](./img/3.%20code%20server%20jss.png)

Push to repository

![](./img/4.%20push%20to%20git.png)



# 3. Writing your first Github Action Workflow

`` ./github/worflows/node.js.yml`` 

![](./img/5.%20node%20js.png)


![](./img/6.%20node%20js%20input.png)

 

![](./img/7.%20package%20js%20lock%20push.png)


![](./img/7.%20package%20js%20lock.png)

# Build Result

![](./img/8.%20build%20result%201.png)


![](./img/8.%20build%20result%202.png)

# TESTING AND DEPLOYMENT 

##  1.  Automated Test file created

![](./img/9.%20Automated%20test%20added.png)

## 2. App file created 

![](./img/10.%20app%20js.png)

# 3. To test 

![](./img/11.%20to%20test.png)
 

![](./img/12.%20test%20passed.png)

## 4.  Git status to push to github repository 

![](./img/13.%20%20git%20status%20to%20push%20to%20git%20hub.png)

## 5. An error occured due to a higher version

![](./img/14.%20an%20error%20due%20to.png)

## 6. Downgrade version and testing, passed. 

![](./img/15.%20downgrade%20version%20and%20test%20passed.png)

## 7. Build for version 16x done 
![](./img/16.%20git%20add%20and%20push%20to%20repository.png)

## 8. Downgrade and push Successful

![](./img/17.%20downgrade%20and%20push%20successfully%20action%20passed.png)

## 9. Build for automated Test done 

![](./img/18.%20build%2016%20done.png)

## 10. Automated test done

![](./img/19.%20test%20passed%20on%20github%20actions.png)

## 11. Deployment to AWS

Created an EC2 INSTANCE for deployment. 
Ubuntu 

![](./img/20.%20AWS%20Instance.png)


# Deployment  workflow 1

![](./img/20.%20deployment%201.png)


# Deployment  workflow 2
![](./img/20.%20deployment%20workflow%201.png)


# Secret created to input;

EC2 HOST

SSH KEY

EC2 USER

![](./img/19.%20secret%20for%20AWS%20safe.png)


# Deployment To AWS Successful

![](./img/20.%20deployment%20successful.png)

# Successful deployment breakdown 

![](./img/21.%20deployment%20breakdown.png)


![](./img/22.%20deployment%20breakdown.png)

## Security Group set up to open port 3000

http://localhost:3000

![](./img/24.%20SG%20rule%20on%20port%203000.png)

# Aws deployment testing

![](./img/23.%20on%20AWS.png)

![](./img/23.%20on%20URL.png)







