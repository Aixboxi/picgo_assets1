# picgo_assets1


# 将更改提交
git add .
git commit -m "npm publish"
# 更新package版本号
npm version patch
# 推送至github触发action
git push


每次提交记得更新package版本号  npm version patch



国内能用的npm cdn
https://npm.onmicrosoft.cn/,
https://jsd.onmicrosoft.cn/npm/,
https://cdn.jsdelivr.net/npm/,
https://jsd.cdn.zzko.cn/npm/


例子
https://cdn.jsdelivr.net/npm/picgo-plugin-upload-gitee@1.0.0/dist/index.js