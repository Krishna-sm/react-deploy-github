# install package
```bash
            npm i gh-pages

```


# add script upper section

```json

"homepage":"krishna-sm.github.io/react-deploy-github

```


# add two more script in scripts section


```json
{
    
 "predeploy":"npm run build",
    "deploy":"gh-pages -d build"

}
```


# go to repositry on github then > setting then pages then select gh-pages branch

![Alt text](image.png)