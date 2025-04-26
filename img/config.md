```javascript
const config = {
  //网页元数据
  metaData:{
    title: '你还是那么漂亮没变的个人主页🎉',
    description: '欢迎来到小强的奇妙世界！',
    keywords: 'LVOE,你还是那么漂亮没变,个人主页,个人网站',
    icon: '/favicon.ico'  //网页图标，支持外链
  },

  avatar: "/img/avatar.jpg", // 头像
  welcometitle: Hi, 欢迎大家来到你还是那么漂亮没变的博客网站", // 标题

  // 颜色配置
  color: {
    themecolor: "#FFFFFF", // 主题颜色，推荐趋于亮白可带有轻微色调，例： #D1FFEC
    welcometitlecolor: "#FFFFFF", // 标题颜色 例： #7BFFC9
  },
  
  brightness: 85, // 背景亮度 --%
  blur: 5, // 毛玻璃模糊效果

  // 我的标签
  tags : ['乐观开朗','温柔体贴','随和亲切','冷静沉着','才思敏捷','风趣幽默','刚正不阿','善解人意'],

  // 默认背景壁纸
  background: {
    "pc":{   //pc端
      "type":"pic",   //"pic":静态壁纸;"video":动态壁纸
      "datainfo":{
        "title":"海洋女孩", 
        "preview":"/img/wallpaper/static/海洋女孩/image-pre.webp",
        "url":"/img/wallpaper/static/海洋女孩/image.png",     //当然，也可填写网络地址或壁纸api，如随机PC壁纸api："url":"https://t.mwm.moe/pc"
      },
    },
    "mobile":{   //移动端
      "type":"pic",
      "datainfo":{
        "title":"0001", 
        "preview":"/img/wallpaper/static-mobile/0001/image-pre.webp",
        "url":"/img/wallpaper/static-mobile/0001/image.png"  //同理，随机移动端壁纸："url":"https://t.mwm.moe/mp"
      }
    }
      
  },

  //极坐标图数据
  polarChart:{
    skills: ['Node', 'Vue.js', 'React', 'JavaScript', 'Java', 'Python', 'linux', 'Docker', 'MySQL', 'MongoDB', 'AWS'],
    skillPoints: [90, 85, 78, 88, 80, 78, 85, 65, 82, 78, 65],
  },

  //社交按钮，图标使用mdi图标（https://pictogrammers.com/library/mdi/），复制图标名称即可
  socialPlatformIcons: [
    {icon:"mdi-github",link:"https://www.github.com"},
    {icon:"mdi-email",link:"mailto:1473226481@qq.com"},
    {icon:"mdi-qqchat",link:"https://im.qq.com/"},
    {icon:"mdi-wechat",link:"https://wx.qq.com/"},
    {icon:"mdi-youtube",link:"https://www.youtube.com"},
    {icon:"mdi-facebook",link:"https://www.facebook.com"}
  ],

  //打字机
  typeWriterStrings: [
    "如果你看到了这行字，说明我已经成功吸引到了你的注意力。",
    "顶峰的少年，给了你所有细节，你却说我不是迪迦，给不了你想要的光。",
    "心简单，世界就简单，幸福才会生长；心自由，生活就自由，到哪都有快乐。",
    "生命太短，没有时间留给遗憾，若不是终点，请微笑一直向前。"
  ],

  //音乐播放配置，采用MetingJS Api(https://github.com/metowolf/MetingJS)
  musicPlayer:{
    server: 'netease',  //服务提供商 --网易云音乐
    type: 'playlist',   //歌单类型
    id: '2028178887'  //歌单id ---> music.163.com/#/playlist?id=2028178887
  },

  //壁纸数据 -----可以将壁纸文件上传到uhsea.com获取网络直链。若想调用api，请前往脚本自行修改逻辑
  wallpaper:{
    pic:[
      {"title":"海洋女孩","preview":"/img/wallpaper/static/海洋女孩/image-pre.webp","url":"/img/wallpaper/static/海洋女孩/image.png"},
      {"title":"书房夜晚","preview":"/img/wallpaper/static/书房夜晚/image-pre.webp","url":"/img/wallpaper/static/书房夜晚/image.png"},
      {"title":"安逸舒适","preview":"/img/wallpaper/static/安逸舒适/image-pre.webp","url":"/img/wallpaper/static/安逸舒适/image.png"},
      {"title":"jswcMaMj","preview":"https://file.uhsea.com/2503/76a4f03e8654d6e66bbbc7e8149c2fe33M.png","url":"https://file.uhsea.com/2503/5b8a20a5f2b269659911c9485d0d0c3f0F.png"},
      {"title":"pgtTqoqq","preview":"https://file.uhsea.com/2503/caeae6b4fc1aba41bff4ad4ec59d6d8aA5.png","url":"https://file.uhsea.com/2503/45aa0a5a31a0ae95f7cc660e3ab4148eUT.png"},
      {"title":"cvKMKhue","preview":"https://file.uhsea.com/2503/7a693bf725b501e0907ce40f18d2edc49P.png","url":"https://file.uhsea.com/2503/55e7191130d160a8e4421497308ffb67DT.png"},
      {"title":"XpxvQVoP","preview":"https://file.uhsea.com/2503/f4b6804c7189357d3252aa0f981b59c4EF.png","url":"https://file.uhsea.com/2503/66359907715d46e0a4523da0142a6f63EU.png"},
	  {"title":"纪姿含1","preview":"/img/wallpaper/static/纪姿含1/image-pre.webp","url":"/img/wallpaper/static/纪姿含1/image.png"},
      {"title":"纪姿含2","preview":"/img/wallpaper/static/纪姿含2/image-pre.webp","url":"/img/wallpaper/static/纪姿含2/image.png"},
      {"title":"纪姿含3","preview":"/img/wallpaper/static/纪姿含3/image-pre.webp","url":"/img/wallpaper/static/纪姿含3/image.png"},
      {"title":"纪姿含4","preview":"/img/wallpaper/static/纪姿含4/image-pre.webp","url":"/img/wallpaper/static/纪姿含4/image.png"},
      {"title":"纪姿含5","preview":"/img/wallpaper/static/纪姿含5/image-pre.webp","url":"/img/wallpaper/static/纪姿含5/image.png"},
	  {"title":"纪姿含6","preview":"/img/wallpaper/static/纪姿含6/image-pre.webp","url":"/img/wallpaper/static/纪姿含6/image.png"},
      {"title":"纪姿含7","preview":"/img/wallpaper/static/纪姿含7/image-pre.webp","url":"/img/wallpaper/static/纪姿含7/image.png"},
      {"title":"纪姿含8","preview":"/img/wallpaper/static/纪姿含8/image-pre.webp","url":"/img/wallpaper/static/纪姿含8/image.png"},
      {"title":"纪姿含9","preview":"/img/wallpaper/static/纪姿含9/image-pre.webp","url":"/img/wallpaper/static/纪姿含9/image.png"},
      {"title":"纪姿含10","preview":"/img/wallpaper/static/纪姿含10/image-pre.webp","url":"/img/wallpaper/static/纪姿含10/image.png"},
      {"title":"纪姿含11","preview":"/img/wallpaper/static/纪姿含11/image-pre.webp","url":"/img/wallpaper/static/纪姿含11/image.png"},
	  {"title":"xiaoqiang","preview":"/img/wallpaper/static/xiaoqiang/image-pre.webp","url":"/img/wallpaper/static/xiaoqiang/image.png"},
    ],
    picMobile:[
	  {"title":"0001","preview":"/img/wallpaper/static-mobile/0001/image-pre.webp","url":"/img/wallpaper/static-mobile/0001/image.png"},
      {"title":"0002","preview":"/img/wallpaper/static-mobile/0002/image-pre.webp","url":"/img/wallpaper/static-mobile/0002/image.png"},
      {"title":"0003","preview":"/img/wallpaper/static-mobile/0003/image-pre.webp","url":"/img/wallpaper/static-mobile/0003/image.png"},
      {"title":"0004","preview":"/img/wallpaper/static-mobile/0004/image-pre.webp","url":"/img/wallpaper/static-mobile/0004/image.png"},
	  {"title":"DfNHPPcc","preview":"https://file.uhsea.com/2503/e3510f4d0286e37b828f74494230f0efM2.png","url":"https://file.uhsea.com/2503/97b50adb3d4cd6f1a4132f6d3e8c98483T.png"},
      {"title":"WIOlrGSy","preview":"https://file.uhsea.com/2503/99162abfe07e18cfe6182ca3458561ef3A.png","url":"https://file.uhsea.com/2503/609532b992163117db9b341dde87b78f3C.png"},
      {"title":"cZZwzhis","preview":"https://file.uhsea.com/2503/cf558fa1989c07726778c60be47b9928K8.png","url":"https://file.uhsea.com/2503/e27b91f1604f73d0444c807024ef7c9fI3.png"},
      {"title":"aANKZHPX","preview":"https://file.uhsea.com/2503/0aa1cb875c8c7c20afd1aa72530294350K.png","url":"https://file.uhsea.com/2503/b09b65e20e176cb0d22dbc319981b5b45L.png"},
      {"title":"纪姿含0005","preview":"/img/wallpaper/static-mobile/纪姿含0005/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0005/image.png"},
      {"title":"纪姿含0006","preview":"/img/wallpaper/static-mobile/纪姿含0006/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0006/image.png"},
      {"title":"纪姿含0007","preview":"/img/wallpaper/static-mobile/纪姿含0007/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0007/image.png"},
      {"title":"纪姿含0008","preview":"/img/wallpaper/static-mobile/纪姿含0008/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0008/image.png"},
	  {"title":"纪姿含0009","preview":"/img/wallpaper/static-mobile/纪姿含0009/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0009/image.png"},
      {"title":"纪姿含0010","preview":"/img/wallpaper/static-mobile/纪姿含0010/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0010/image.png"},
      {"title":"纪姿含0011","preview":"/img/wallpaper/static-mobile/纪姿含0011/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0011/image.png"},
      {"title":"纪姿含0012","preview":"/img/wallpaper/static-mobile/纪姿含0012/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0012/image.png"},
	  {"title":"纪姿含0013","preview":"/img/wallpaper/static-mobile/纪姿含0013/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0013/image.png"},
      {"title":"纪姿含0014","preview":"/img/wallpaper/static-mobile/纪姿含0014/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0014/image.png"},
	  {"title":"纪姿含0015","preview":"/img/wallpaper/static-mobile/纪姿含0015/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0015/image.png"},
      {"title":"纪姿含0016","preview":"/img/wallpaper/static-mobile/纪姿含0016/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0016/image.png"},
      {"title":"纪姿含0017","preview":"/img/wallpaper/static-mobile/纪姿含0017/image-pre.webp","url":"/img/wallpaper/static-mobile/纪姿含0017/image.png"},
      {"title":"dwzeijlrarg","preview":"/img/wallpaper/static-mobile/dwzeijlrarg/dwzeijlrarg-pre.webp","url":"/img/wallpaper/static-mobile/dwzeijlrarg/dwzeijlrarg.png"},
    ],
    video:[
      {
        "title":"尼尔：机械纪元 团队",
        "preview":"/img/wallpaper/dynamic/尼尔：机械纪元 团队/Nier-Automata-Team-pre.webm",
        "url":"/img/wallpaper/dynamic/尼尔：机械纪元 团队/Nier-Automata-Team.webm"
	  },
      {
        "title":"向往航天的女孩",
        "preview":"/img/wallpaper/dynamic/向往航天的女孩/Toy-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/向往航天的女孩/Toy-Aeroplane.webm"
	  },
      {
        "title":"纪姿含的视频1",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频1/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频1/jizihan520-Aeroplane.webm"
      },
      {
        "title":"纪姿含的视频2",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频2/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频2/jizihan520-Aeroplane.webm"
	  },
      {
        "title":"纪姿含的视频3",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频3/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频3/jizihan520-Aeroplane.webm"
      },
      {
        "title":"纪姿含的视频4",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频4/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频4/jizihan520-Aeroplane.webm"
	  },
      {
        "title":"纪姿含的视频5",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频5/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频5/jizihan520-Aeroplane.webm"
      },
      {
        "title":"纪姿含的视频6",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频6/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频6/jizihan520-Aeroplane.webm"
	  },
      {
        "title":"纪姿含的视频7",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频7/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频7/jizihan520-Aeroplane.webm"
	  },
      {
        "title":"纪姿含的视频8",
        "preview":"/img/wallpaper/dynamic/纪姿含的视频8/jizihan520-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/纪姿含的视频8/jizihan520-Aeroplane.webm"		
      },
    ],
    videoMobile:[
      {
        "title":"幻觉镇-gaako_illust",
        "preview":"/img/wallpaper/dynamic-mobile/幻觉镇-gaako_illust/Hallucination_town-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/幻觉镇-gaako_illust/Hallucination_town.mp4"
      },
      {
        "title":"chuva",
        "preview":"/img/wallpaper/dynamic-mobile/chuva/chuva-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/chuva/chuva.mp4"
      },
      {
        "title":"Doodle-小猫女仆降临",
        "preview":"/img/wallpaper/dynamic-mobile/Doodle-小猫女仆降临/d12-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/Doodle-小猫女仆降临/d12.mp4"
      },
      {
        "title":"纪姿含jizihan1",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan1/jizihan1-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan1/jizihan1.mp4"
      },
      {
        "title":"纪姿含jizihan2",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan2/jizihan2-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan2/jizihan2.mp4"
      },
      {
        "title":"纪姿含jizihan3",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan3/jizihan3-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan3/jizihan3.mp4"
      },
      {
        "title":"纪姿含jizihan4",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan4/jizihan4-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan4/jizihan4.mp4"
      },
      {
        "title":"纪姿含jizihan5",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan5/jizihan5-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan5/jizihan5.mp4"
      },
      {
        "title":"纪姿含jizihan6",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan6/jizihan6-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan6/jizihan6.mp4"
      },
      {
        "title":"纪姿含jizihan7",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan7/jizihan7-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan7/jizihan7.mp4"
      },
      {
        "title":"纪姿含jizihan8",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan8/jizihan8-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan8/jizihan8.mp4"
      },
      {
        "title":"纪姿含jizihan9",
       "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan9//jizihan9-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan9/jizihan9.mp4"
      },
      {
        "title":"纪姿含jizihan10",
        "preview":"/img/wallpaper/dynamic-mobile/纪姿含jizihan10/jizihan10-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/纪姿含jizihan10/jizihan10.mp4
      },
    ],
  },

  //项目卡片 其中 字段"show"控制初始卡片的text是否展开
  projectcards:[ 
    {go:"🚀 前往",img:"/img/jizihan1.jpg",title:"纪姿含1,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"🔍️ 前往",img:"/img/jizihan2.jpg",title:"纪姿含2,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"📝 前往",img:"/img/jizihan3.jpg",title:"纪姿含3,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"👍 前往",img:"/img/jizihan4.jpg",title:"纪姿含4,ubtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"🔍 前往",img:"/img/jizihan5.jpg",title:"纪姿含5,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"🎨 前往",img:"/img/jizihan6.jpg",title:"纪姿含6,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"💍 前往",img:"/img/jizihan7.jpg",title:"纪姿含7,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
    {go:"🔍 前往",img:"/img/jizihan8.jpg",title:"纪姿含8,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
	{go:"🚀 前往",img:"/img/sunshine9.jpg",title:"纪姿含9,subtitle:"纪姿含照片", text:"If you see this line, I've managed to get your attention.",url:"https://ai.xiaoqiangboke.top",show:false},
  ],
  
  statement: ["备案号：小强ICP备XIAOQAING号","Copyright © 2025 小强"],
}

export default config
```