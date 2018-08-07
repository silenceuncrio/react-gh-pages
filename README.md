


# Deploying a React App* to GitHub Pages

參考 https://github.com/gitname/react-gh-pages



# 如何利用這個 repository

```
git clone https://github.com/gitname/react-gh-pages.git
cd react-gh-pages
```

先確認目前的 branch 是 master

若不是的話記得切過去
```
git checkout master
```

安裝所需套件
```
npm install
```



# 在 local 作開發可用
```
npm start
```

這會讓您在 local 用 web browser 觀察自己所作的修改



# Deploy

```
npm run deploy
```

# Commit source code to the "master" branch

```
git add .
git commit -m "your commit message"
git push origin master
```



# Published Site

Our site is published at https://silenceuncrio.github.io/react-gh-pages/


