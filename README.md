#### 内容介绍

- 记录一下跟着油管主net NinJa学习`SvelteKit`的过程
- 该demo是多个页面调转和重定向已经获取api数据的项目
- 将构建的demo通过`vercel`免费部署到网站上

------

#### demo最终实现效果

- 首页

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h1wr8ttaspj21c00u03zs.jpg" style="zoom:50%;" />

- About页面

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h1wr8ufqwoj21c00u0dh7.jpg" style="zoom:50%;" />

- Guide页面

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h1wr8x8mujj21c00u0abl.jpg" style="zoom:50%;" />

- Guide/id页面

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h1wr8w1mxnj21c00u075q.jpg" style="zoom:50%;" />

- 预览效果：[sveltekit-stidy](https://sveltekit-study-34krh80w2-ddy-ddy.vercel.app/)

#### Svelte学习资源

-  官方文档：[https://www.sveltejs.cn/](https://www.sveltejs.cn/)

-  net NinJa学习视频：[youtube](https://www.youtube.com/watch?v=9OlLxkaeVvw&list=PL4cUxeGkcC9hpM9ARM59Ve3jqcb54dqiP)
-  本demo代码：[https://github.com/ddy-ddy/sveltekit-study](https://github.com/ddy-ddy/sveltekit-study)

------

#### dem构建过程

1、使用脚手架工具`degit` setting up a svelte app

```bash
'''
#-g means installing this package globally on my compute so we can use it anywhere in any directory
'''
npm install -g degit    #install degit with npm
degit sveltejs/template svelte-demo-ddypoll   #create a project by degit
npm install #install dependency package with npm
npm run dev  #spin up a local development server to preview our project
```

2、跟着YouTube的视频不断添加新功能，每一个版本在我的github都有存档，这里就简单罗列每个版本添加的功能

v1：[Know something about pages and routes](https://github.com/ddy-ddy/sveltekit-study/tree/v1)

v2：[Add Reusable Component, Layout Component and Rset layout Component](https://github.com/ddy-ddy/sveltekit-study/tree/v2)

v3: [Learning loading data $ SSR & client-side vs server-side](https://github.com/ddy-ddy/sveltekit-study/tree/v3)

V4: [Dynamic Routes & Redirects](https://github.com/ddy-ddy/sveltekit-study/tree/v4)

v5: [Perfecting Data & Error page](https://github.com/ddy-ddy/sveltekit-study/tree/v5)

V6: [API routes](https://github.com/ddy-ddy/sveltekit-study/tree/v6)

------

3、将app部署到surge上

```shell
#安装surge
npm install --global surge
#build project
npm run build
#deploy to website
surge public my-project-name.surge.sh
```

4、将app部署到vercel上

```shell
直接到vercel官网链接自己的github库即可部署到网站上
```

