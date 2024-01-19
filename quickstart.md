
1. python3.10 安装
2. 执行python依赖包安装
可以上网的环境
FastAPI-vue3--master\kinit-api> pip3 install -r requirements.md -i https://mirrors.aliyun.com/pypi/simple/

不能上网的环境
FastAPI-vue3--master\kinit-api> pip3 install -r requirements.md -i https://替换成内部私网镜像地址.com/xxx/ --trusted-host https://替换成内部私网镜像地址.com

3. 修改数据库配置信息
   在 `application/config` 目录中
   - development.py：开发环境
   - production.py：生产环境

4. 手工执行数据库创建
   库名称：kinit

5. 初始化数据库指令执行
FastAPI-vue3--master\kinit-api> python main.py init --env dev

6. 后端程序运行指令执行
FastAPI-vue3--master\kinit-api> python main.py run

INFO:     Started server process [52568]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Uvicorn running on http://0.0.0.0:9000 (Press CTRL+C to quit)

swagger接口访问地址：http://127.0.0.1:9000/docs

#前端 
淘宝镜像设置 npm config set registry https://registry.npm.taobao.org 
1. 执行脚本

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> npm install -g yarn

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> yarn add vite-plugin-svg-icons -D

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> yarn add fast-glob -D

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> npm install -g pnpm

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> pnpm install

FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> pnpm run dev 

PS D:\pyProject\FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin> pnpm run dev

> vue-element-plus-admin@2.3.0 dev D:\pyProject\FastAPI-vue3--master\FastAPI-vue3--master\kinit-admin
> vite --mode dev
  VITE v4.4.9  ready in 15060 ms
  ➜  Local:   http://localhost:5000/
  ➜  Network: http://192.168.103.22:5000/ 
  ➜  Network: http://172.19.96.1:5000/
  ➜  press h to show help
