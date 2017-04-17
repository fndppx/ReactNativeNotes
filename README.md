# ReactNativeNotes

##Command

react-native init AwesomeProject

cd AwesomeProject

react-native run-ios

flex ：1 或者 0

1内部自动均等 

创建工程
>react-native init project
 
升级最新版本
>react-native upgrade

启动打包服务
>react-native start

在ios上运行debug程序
>react-native run-ios

打离线包
>react-native bundle
>react-native unbundle

为项目添加三方依赖
>react-native link

生成原生库
>react-native new-library

>##ReactNative生命周期

constructor(props)

componentWillMount()

componentDidMount()

componentReceiveProps()

componentWillUpdate

componentDidUpdate

componentWIllUnmount()

render()


>#导入与导出

1.如何导出一个组件，如何使用导出的组件？

2.如何导出一个变量或常量，如何使用导出的变量和常量？

3.如何导出一个方法，如何使用导出的方法？

onPress={()=>{}}>


>#React Native props

1.什么是props？

2.如何使用props？

3.什么是默认属性以及他的作用？

4.如何对props进行约束和检查？
static propTypes

5.props使用小技巧之延展操作符？
...params

6.props使用小技巧之解构赋值?

>#State

1.什么是state
2.如何使用state

>#原生代码混编

* Native Modules
* Native UI Components

>#CSS

  ```
  Valid style props: [
  "alignItems",

  "alignSelf",

  "backfaceVisibility",

  "backgroundColor",

  "borderBottomColor",

  "borderBottomLeftRadius",

  "borderBottomRightRadius",

  "borderBottomWidth",

  "borderColor",

  "borderLeftColor",

  "borderLeftWidth",

  "borderRadius",

  "borderRightColor",

  "borderRightWidth",

  "borderStyle",

  "borderTopColor",

  "borderTopLeftRadius",

  "borderTopRightRadius",

  "borderTopWidth",

  "borderWidth",

  "bottom",

  "color",

  "elevation",

  "flex",

  "flexDirection",

  "flexWrap",

  "fontFamily",

  "fontSize",

  "fontStyle",

  "fontWeight",

  "height",

  "justifyContent",

  "left",

  "letterSpacing",

  "lineHeight",

  "margin",

  "marginBottom",

  "marginHorizontal",

  "marginLeft",

  "marginRight",

  "marginTop",

  "marginVertical",

  "opacity",

  "overflow",

  "overlayColor",

  "padding",

  "paddingBottom",

  "paddingHorizontal",

  "paddingLeft",

  "paddingRight",

  "paddingTop",

  "paddingVertical",

  "position",

  "resizeMode",

  "right",

  "rotation",

  "scaleX",

  "scaleY",

  "shadowColor",

  "shadowOffset",

  "shadowOpacity",

  "shadowRadius",

  "textAlign",

  "textAlignVertical",

  "textDecorationColor",

  "textDecorationLine",

  "textDecorationStyle",

  "textShadowColor",

  "textShadowOffset",

  "textShadowRadius",

  "tintColor",

  "top",

  "transform",

  "transformMatrix",

  "translateX",

  "translateY",

  "width",

  "writingDirection"]
  ```


#相关博客

>[贾鹏辉博客](http://www.devio.org)

#github

https://github.com/crazycodeboy/RNStudyNotes/