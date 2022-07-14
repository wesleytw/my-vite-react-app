1.yarn create vite my-vite-react-app --template react  
2.cd my-vite-react-app  
  yarn  
  yarn dev  
      
git init  
  
git add . 
git commit -m "first-commit"   
git push   

Go to your vite.config.js file. And add your base url to it(#repo name).  
defineConfig({  
base: '/my-vite-react-app/' , 
  
yarn build  (npm rum build)  
git add dist -f (-f is required, as your .gitignore will not consider your /dist folder. Hence, it is required for git to consider it as well.)  
git commit -m "Adding dist"  
git subtree push --prefix dist origin gh-pages    
#git subtree push --prefix client/dist origin gh-pages#!!!!  

https://gitbook.tw/chapters/github/fail-to-push   
https://dev.to/shashannkbawa/deploying-vite-app-to-github-pages-3ane  

https://fullstackcode.dev/2022/01/30/creating-react-js-app-using-vite-2-0/
  


dwdwdw