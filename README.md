# Typora 图床设置
> {
  "picBed": {
    "uploader": "aliyun",
    "aliyun": {
    "accessKeyId": "LTAI4FzW8kiZQbWVtCLEBw2e",
    "accessKeySecret": "vNh7LiITKHjUHhRzR1uNxuYPDALCvT",
    "bucket": "shaowen4515", // 存储空间名
    "area": "oss-cn-beijing", // 存储区域代号
    "path": "img/", // 自定义存储路径
     "customUrl": "https://shaowen4515.oss-cn-beijing.aliyuncs.com", // 自定义域名，注意要加 http://或者 https://
     "options": "" // 针对图片的一些后缀处理参数 PicGo 2.2.0+ PicGo-Core 1.4.0+
    }
  },
  "picgoPlugins": {}
  "picBed": {
    "current": "gitee",
    "uploader": "gitee",
    "githubPlus": {
      "branch": "master",
      "customUrl": "https://cdn.jsdelivr.net/gh/用户名/项目名",
      "path": "img/",
      "repo": "github用户名/github仓库名",
      "token": "自己的token"
    },
    "gitee": {
      "branch": "master",
      "customPath": "yearMonth",
      "customUrl": "",
      "path": "img/",
      "repo": "gitee用户名/gitee仓库名",
      "token": "自己的token"
    },
    "smms-user": {
      "Authorization": "替换成你自己的token"
    },
    "transformer": "path"
  },
  "picgoPlugins": {
    "picgo-plugin-gitee-uploader": true,
    "picgo-plugin-smms-user": true,
    "picgo-plugin-github-plus": true
  },
  "picgo-plugin-gitee-uploader": {
    "lastSync": "2020-04-07 11:04:58"
  },
  "picgo-plugin-github-plus": {
    "lastSync": "2020-04-07 11:09:08"
  }
}
