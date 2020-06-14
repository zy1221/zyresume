<template>
  <div class="hello">
    <div class="header">
      <div class="header-left">
          <div class="header-img">
            <img src="../assets/zy.jpg"/>
          </div>
      </div>
      <div class="header-middle">
          <div class="personal-info">
            <P><label for="zy-name">姓名：</label><span>张媛</span></p>
            <P><label for="zy-want">就职意向：</label><span>web开发工程师</span></p>
            <p><label for="zy-now">当前职业：</label><span>webGIS开发工程师</span></p>
            <p><label for="zy-now">现居：</label><span>杭州</span></p>
          </div>  
      </div>
      <div class="header-right">
          <div class="personal-info">
            <p><label for="zy-now">出生日期：</label><span>1992.12</span></p>
            <p><label for="zy-name">电话：</label><span>13260651221</span></p>
            <p><label for="zy-want">邮箱：</label><span>1083060476@qq.com</span></p>
            <p><label for="zy-want">github：</label><span>github.com/zy1221</span></p>
          </div> 
      </div>
    </div>
    <div class="content" style="font-size: 0.7rem;">
        <div class="content-left">
          <p class="education" align="right"> 
             教育背景
          </p>
           <p class="time" style="top:-5px" align="right"> 
             2011-2015
          </p>
           <p class="time" style="top:-8px" align="right"> 
             2015-2018
          </p>
          <p class="practice" style="top:-15px" align="right">
            实习实践
          </p>
           <p class="time" style="top:-20px" align="right"> 
             2016-2017(科研)
          </p>
           <p class="time" style="top:-10px" align="right"> 
             2017.06-2017.08(实习)
          </p>
           <p class="time" style="top:2px" align="right"> 
             2018.01-2018.04(科研)
          </p>
          <p class="working" style="top:15px" align="right">
            工作经历
          </p>
          <p class="time" style="top:130px" align="right"> 
             2018.07-至今(浙江大华)
          </p>
          <p class="skill" style="top:442px"  align="right">
            个人技能
          </p>
        </div>
        <div class="content-line">
          <div class="big-circle">
            <div class="small-circle"></div>
          </div>
          <div class="little-line little-line-3"></div>
          <div class="little-point">
            <img src="../assets/little_point.png"/>
          </div>
          <div class="little-line little-line-3"></div>
          <div class="little-point">
            <img src="../assets/little_point.png"/>
          </div>
          <div class="little-line little-line-3"></div>
          <div class="big-circle">
            <div class="small-circle"></div>
          </div>
          <div class="little-line little-line-3"></div>
          <div class="little-point">
            <img src="../assets/little_point.png"/>
          </div>
          <div class="little-line little-line-4"></div>
          <div class="little-point">
            <img src="../assets/little_point.png"/>
          </div>
          <div class="little-line little-line-4"></div>
           <div class="little-point">
            <img src="../assets/little_point.png"/>
          </div>
          <div class="little-line little-line-4"></div>
           <div class="big-circle">
            <div class="small-circle"></div>
          </div>
           <div class="little-line little-line-2"></div>
           <div class="big-circle">
            <div class="small-circle"></div>
          </div>
          <div class="little-line little-line-5"></div>
        
        </div>
        <div class="content-right">
          <div class="education-onfo">
            <p style="position:relative;top:10px"> 
              学士学位&nbsp;&nbsp;
              辽宁工大&nbsp;&nbsp;
              测绘学院&nbsp;&nbsp;
              测绘工程&nbsp;&nbsp;
            </p>
            <p style="position:relative;top:-5px"> 
              硕士学位&nbsp;&nbsp;
              武汉大学&nbsp;&nbsp;
              遥感信息工程学院&nbsp;&nbsp;
              摄影测量与遥感&nbsp;&nbsp;
            </p>
          </div>
            <div class="practice-onfo">
              <p style="position:relative;top:-5px"> 
                <span style="font-weight:bold">沉降信息管理系统</span>
                主要负责完成基于openLayer的地理数据展示和基于EChart对沉降数据进行统计展示。
                主要用到的前端库为jQuery、openLayer、Echarts。
              </p>
              <p style="position:relative;top:-10px"> 
              <span style="font-weight:bold">中国电建&nbsp;&nbsp;数据可视化</span>
              基于Cesium实现地理数据的三维展示，利用ECharts库对数据进行二维展示和统计。
              </p>
              <p style="position:relative;top:-15px"> 
              <span style="font-weight:bold">影响管理系统</span>
              后台服务在Node.js上基于express框架进行开发；前端基于react+Ant Design+openlayers技术栈实现；
              影像存储在文件中，影像的路径、时间、地点等信息存储在MySQL数据库中。
              </p>
            </div>
             <div class="working-info">
               <ul style="list-style:none;padding:0px">
                  <li> 
                  <div  class="list-item"></div>
                  <span style="font-weight:bold">负责公司多个产品地图模块开发</span>
                  主要负责了公司9系地图产品、多维产品、实战产品的开发；主要是采用了Vue+VueX+VueRooter+iView技术栈实现。
                  <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">9系地图产品：</span>9系地图产品是公司9系产品的一个分支，主要分为管理员端和客户端两个部分。
                  管理员端主要的负责地图配置、设备点位地理位置配置、热区配置、社会资源标记等功能。
                  客户端主要对设备点位用聚类图层进行展示，可以对重点区域进行标记并快速定位到管控区域，可以通过圈选、线选功能选择多个设备进行实时监控和录像回放。
                  <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">多维产品：</span>该产品更主要服务于公安部门。以公安机关的人口信息库为基准，设备出现报警之后，根据设备识别出的车牌号、手机mac、电动车RFID、人脸等多个维度出发对犯罪嫌疑人进行追踪。
                  其中设备出现报警之后地图上相应点位会进行闪烁警示并对报警信息进行展示，根据信息可以搜素嫌疑目标的运行轨迹并在地图上进行模拟展示。
                   <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">实战产品：</span>该产品主要用于公安机关案件信息管理和分析。地图主要负责展示案件发生的地点，以及与案件相关的具有地理信息的线索，
                  在添加案件信息时提供经纬度拾取功能。
                </li>
                 <li> 
                  <div class="list-item" ></div>
                  <span style="font-weight:bold">参与公司内部地图API的开发</span> 
                  利用模块化的思想，基于openLayers封装一套仅供公司内部使用的地图API。主要提供了打点、画线、画面、冒泡、绘制轨迹等接口。
                </li>
                <li> 
                  <div class="list-item" ></div>
                  <span style="font-weight:bold">负责Vue地图组件开发</span> 
                  针对安防行业地图的应用场景，利用公司内部的地图API，基于Vue框架开发了一套常用的地图组件库，主要包含图层组件、工具栏组件、冒泡组件等。
                  <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">图层组件：</span>主要包含常用的点位图层（包括卡口点位图层、视频点位图层）、热力图图层、聚类图层等；
                  <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">工具栏组件：</span>主要要是为地图添加操作按钮，组件中的按钮需要可配置便于地图上层的应用添加一些子菜单如地图全屏菜单。
                  工具栏中常用功能主要有图层展示、圈选、框选、线选、测量工具、清屏等功能。
                   <br/>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="font-weight:bold">冒泡组件：</span>主要用于展示地图上的设备点位的信息，包含名称及编码等信息。
                  同时在冒泡下方提供操作按钮配置入口，常用的操作按钮主要为视频播放和录像回放。
                </li>
                 <li> 
                  <div class="list-item" ></div>
                  <span style="font-weight:bold">负责公司大屏展示页面开发</span> 
                  基于three.js进行三维城市模型展示，行政区立体饼状展示，并提供实时报警功能，对报警信息进行冒泡展示。
                </li>
               </ul>
            </div>
            <div class="skill-info">
                <ul style='margin-top: 5px;'>
                  <li>
                     <div class="list-item" ></div>
                     熟练使用JavaScript、html、css语言
                  </li>
                   <li>
                     <div class="list-item" ></div>
                    熟练使用Vue+vuex+VueRooter+iView技术栈进行前端开发
                  </li>
                  <li>
                     <div class="list-item" ></div>
                    熟练基于openLayers的地图开发
                  </li>
                  <li>
                     <div class="list-item" ></div>
                    能够基于Cesium、Echarts、three.js进行三维场景开发。
                  </li>
                   <li>
                    <div class="list-item" ></div>
                    对基于react框架的前端开发和基于Node.js的后端开发有一定的了解。
                  </li>
                </ul>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  width: 100%;
  height:1020px;
  margin: 0;
  padding: 0;
}
.header{
  width: 100%;
  height: 20%;
  /* border: 2px solid grey; */
  display: flex;
  flex-direction: row;
  justify-content:space-evenly;
  flex-wrap: nowrap;
  align-items: center;
}

.header-left,.header-middle,.header-right{
  width: 30%;
  height: 100%;
  /* border: 1px solid #cbc1db; */
}
.header-left .header-img{
  width: 155px;
  height: 160px;
  /* border-radius: 50%; */
  overflow: hidden;
  position: relative;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
  border: 3px solid #cbc1db;
  border-radius: 10px;
  box-shadow: 1px 1px 0px 1px #cbc1db;
}
.header-left .header-img img{
  width: 100%;
  height: 100%;
  display: inline-block;
   border-radius: 50%;
}
.personal-info{
    width: 200px;
    height: 170x;
    font-size: 0.8rem;
    /* border-radius: 50%; */
    overflow: hidden;
    position: relative;
    left: 50%;
    top: 50%;
    transform: translate(-50%,-50%);
    border: 1px solid #cbc1db;
    border-radius: 20px;
    padding-left: 10px;
    box-shadow: 1px 1px 0px 1px #cbc1db;
}
.personal-info span{
  font-weight: bold;
}
.content{
  width: 100%;
  height: 80%;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.content-left{
  width:28%;
  height:100%;
  /* border:1px solid #cbc1db; */
}
.content-line{
  width:4%;
  height:100%;
  /* border:1px solid #cbc1db; */
}
.content-right{
  width:68%;
  height:90%;
  
  /* border:1px solid #cbc1db; */
}
.content-line{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.big-circle{
  width: 12px;
  height: 12px;
  border-radius: 12px;
  border:3px solid #cbc1db;
}
.big-circle .small-circle{
  width: 4px;
  height: 4px;
  border-radius: 4px;
  border:3px solid #cbc1db;
  position: relative;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
}
.little-line{
  width: 0px;
  border:1px solid #626262;
}
.little-line-1{
   height: 25px
}
.little-line-2{
   height: 550px;
}
.little-line-3{
   height: 13px;
}
.little-line-4{
   height: 28px;
}
.little-line-5{
   height: 100px;
}
.little-point{
    width: 12px;
    height: 12px;
    border-radius: 12px;
}
.little-point img{
    width: 100%;
    height: 100%;
    display: block;
    border-radius: 12px;  
}
.working,.education,.skill,.evaluation,.practice{
  width: 100%;
  height: 23px;
  position: relative;
  right:50px;
  margin: 0px;
  line-height: 23px;
  font-size: 1.2rem;
  font-weight: bold;
  margin-right:40px;
  color:#40464d;
}
.time{
  color: #5c6165;
  position: relative;
}
.education-onfo{
  width:100%;
  height: 11%;
  border-top: 5px solid #cbc1db;
  border-bottom: 5px solid #cbc1db;
}
.education-onfo p{ 
  height: 28px;
  line-height: 28px;
}
.working-info{
  width:100%;
  height: 14%;
  border-top: 5px solid #cbc1db;
  position: relative;
  top:-25px;
}
.list-item{
  display:inline-block;
  width:0px;
  height:0px;
  border-left:10px solid #cbc1db;
  border-right:5px solid transparent;
  border-bottom :5px solid transparent;
  border-top:5px solid transparent;
  margin-right:5px
}
.skill-info{
  width:100%;
  height: 14%;
  border-top: 5px solid #cbc1db;
  position: relative;
  top:355px;
}
ul{
  list-style:none;
  padding:0px;
}
</style>
