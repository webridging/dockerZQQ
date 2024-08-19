# hammal

Hammal 是运行于 cloudflare workers 上的 Docker 镜像加速工具，用于解决获取 Docker 官方镜像无法正常访问的问题。

文档： https://singee.atlassian.net/wiki/spaces/MAIN/pages/5079084/Cloudflare+Workers+Docker 
# 方法步骤
```
git clone https://github.com/webridging/dockerZQQ.git
pwd
ls
cd dockerZQQ/
ls
mv wrangler.toml.sample wrangler.toml
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.nvm/nvm.sh
nvm install 17
nvm use 17
node -v
npm -v
npx -v
curl -fsSL https://get.pnpm.io/install.sh | sh -
npx wrangler whoami
npx wrangler login
```
![image](https://github.com/user-attachments/assets/a51d232e-638a-4454-9513-3a1e1997f3bf)
![image](https://github.com/user-attachments/assets/b7a5448c-1801-42b3-9da6-fa0057e55535)
![image](https://github.com/user-attachments/assets/67cc6453-ef2e-4808-a317-03c8e36ff2a3)
![image](https://github.com/user-attachments/assets/cb4fe917-348b-4128-8a92-a6fb7c86db81)
![image](https://github.com/user-attachments/assets/bc172e08-8f6f-432c-a7cc-bb94d53841af)
![image](https://github.com/user-attachments/assets/b4493368-245b-4dd2-8d06-519ab51485ff)
注册cloudflare账户：https://dash.cloudflare.com/sign-up
注册完了命令行登录验证npx wrangler login
