---
layout: default
---


<!-- ---- -->
<!-- Card -->
<!-- ---- -->


<p align="center">
	<a href="https://github.com/afkT">
		<img src="https://github-readme-stats.vercel.app/api?username=afkT&count_private=true&show_icons=true&hide=contribs&include_all_commits=true&theme=vue" />
	</a>
</p>


<!-- ------------ -->
<!-- Repositories -->
<!-- ------------ -->


<!-- -------- -->
<!-- DevUtils -->
<!-- -------- -->


<h1 align="center">
	<a href="https://github.com/afkT/DevUtils">DevUtils</a>
</h1>


<p align="center">
	<a href="https://github.com/afkT">
		<img alt="Profile" src="https://img.shields.io/badge/GitHub-afkT-orange.svg" />
	</a>
	<a href="https://github.com/afkT/DevUtils/blob/master/LICENSE">
		<img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" />
	</a>
	<a href="https://search.maven.org/search?q=io.github.afkt">
		<img alt="Version" src="https://img.shields.io/badge/Maven-Dev-5776E0.svg" />
	</a>
	<a href="https://android-arsenal.com/api?level=14">
		<img alt="API" src="https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat" />
	</a>
	<a href="https://search.maven.org/search?q=io.github.afkt">
		<img alt="Version" src="https://img.shields.io/badge/DevUtils-2.4.2-yellow.svg" />
	</a>
	<a href="https://github.com/afkT/DevUtils/blob/master/lib/DevApp/README.md">
		<img alt="Utils" src="https://img.shields.io/badge/Utils-300+-critical.svg" />
	</a>
</p>


<p align="center">
	🔥 ( 持续更新，目前含 300+ 工具类 ) <a href="https://github.com/afkT/DevUtils/projects/1">Roadmap</a>
	<br>
	DevUtils 是一个 Android 工具库，主要根据不同功能模块，封装快捷使用的工具类及 API 方法调用。
	<br>
	该项目尽可能的便于开发人员，快捷、高效开发安全可靠的项目。
</p>


<p align="center">
	<b>
		<a href="https://github.com/afkT/DevUtils/blob/master/README/android_standard.md">Android 规范</a>
	</b>、
	<b>
		<a href="https://github.com/afkT/DevUtils/blob/master/README/java_standard.md">Java 规范</a>
	</b>、
	<b>
		<a href="https://github.com/afkT/DevUtils/blob/master/README/git_standard.md">Git 规范</a>
	</b>
</p>


![module][module]


## Dev 系列开发库全部 Lib Gradle

```gradle
// DevApp - Android 工具类库
implementation 'io.github.afkt:DevAppX:2.4.2'

// DevAssist - 封装逻辑代码, 实现多个快捷功能辅助类、以及 Engine 兼容框架等
implementation 'io.github.afkt:DevAssist:1.3.8'

// DevBase - Base ( Activity、Fragment )、MVP、ViewBinding、ContentLayout 基类库
implementation 'io.github.afkt:DevBase:1.1.4'

// DevBaseMVVM - MVVM ( ViewDataBinding + ViewModel ) 基类库
implementation 'io.github.afkt:DevBaseMVVM:1.1.2'

// DevEngine - 第三方框架解耦、一键替换第三方库、同类库多 Engine 组件化混合使用
implementation 'io.github.afkt:DevEngine:1.1.0'

// DevHttpCapture - OkHttp 抓包工具库
implementation 'io.github.afkt:DevHttpCapture:1.1.3'

// DevHttpCaptureCompiler - OkHttp 抓包工具库 ( 可视化功能 )
debugImplementation 'io.github.afkt:DevHttpCaptureCompiler:1.1.3'
releaseImplementation 'io.github.afkt:DevHttpCaptureCompilerRelease:1.1.3'

// DevHttpManager - OkHttp 管理库 ( Retrofit 多 BaseUrl 管理、Progress 监听 )
implementation 'io.github.afkt:DevHttpManager:1.0.3'

// DevRetrofit - Retrofit + Kotlin Coroutines 封装
implementation 'io.github.afkt:DevRetrofit:1.0.2'

// DevWidget - 自定义 View UI 库
implementation 'io.github.afkt:DevWidgetX:1.2.0'

// DevEnvironment - Android 环境配置切换库
implementation 'io.github.afkt:DevEnvironment:1.1.2'
debugAnnotationProcessor 'io.github.afkt:DevEnvironmentCompiler:1.1.2' // kaptDebug
releaseAnnotationProcessor 'io.github.afkt:DevEnvironmentCompilerRelease:1.1.2' // kaptRelease
//annotationProcessor 'io.github.afkt:DevEnvironmentCompiler:1.1.2' // kapt

// DevJava - Java 工具类库 ( 不依赖 android api )
implementation 'io.github.afkt:DevJava:1.4.8' // 用于纯 Java 开发，如果依赖了 DevApp 则不需要依赖 DevJava
```


## License

    Copyright 2018 afkT

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



<!-- ------------ -->
<!-- DevComponent -->
<!-- ------------ -->


<h1 align="center">
	<a href="https://github.com/afkT/DevComponent">DevComponent</a>
</h1>


<p align="center">
	<a href="https://github.com/afkT">
		<img alt="Profile" src="https://img.shields.io/badge/GitHub-afkT-orange.svg" />
	</a>
	<a href="https://github.com/afkT/DevComponent/blob/master/LICENSE">
		<img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" />
	</a>
	<a href="https://search.maven.org/search?q=io.github.afkt">
		<img alt="Version" src="https://img.shields.io/badge/Maven-Dev-5776E0.svg" />
	</a>
	<a href="https://android-arsenal.com/api?level=14">
		<img alt="API" src="https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat" />
	</a>
</p>


<p align="center">
	🍋 这是一个 Android 组件化模板项目，通过在此基础上开发项目，使其拥有组件化能力。
</p>


<p align="center">
	<b>
		<a href="https://github.com/afkT/DevComponent/blob/main/USE_GUIDE.md">使用说明</a>
	</b>、
	<b>
		<a href="https://github.com/afkT/DevComponent/blob/main/USE_CHANNEL.md">多渠道打包</a>
	</b>
</p>


> Android 组件化就是利用多个 Module 来表示应用的多个模块实现代码和资源的隔离，并且每个 Module 都有单独运行和组合的能力。

该 Android 项目组件化示例代码 [100% Kotlin][100% Kotlin] 实现，使用 [ARouter][ARouter] 方案实现组件化，
整个项目基于 [Android JetPack][Android JetPack] 组件库 + [Kotlin][Kotlin] 等最新技术栈进行开发，
使用 MVVM 架构 ( [DataBinding][DataBinding] + [ViewModel][ViewModel] + [Lifecycle][Lifecycle] )



<!-- ------------- -->
<!-- DevUtils-repo -->
<!-- ------------- -->


<h1 align="center">
	<a href="https://github.com/afkT/DevUtils-repo">DevUtils-repo</a>
</h1>


<p align="center">
	<a href="https://github.com/afkT">
		<img alt="Profile" src="https://img.shields.io/badge/GitHub-afkT-orange.svg" />
	</a>
	<a href="https://github.com/afkT/DevUtils-repo/blob/master/LICENSE">
		<img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" />
	</a>
	<a href="https://search.maven.org/search?q=io.github.afkt">
		<img alt="Version" src="https://img.shields.io/badge/Maven-Dev-5776E0.svg" />
	</a>
	<a href="https://android-arsenal.com/api?level=14">
		<img alt="API" src="https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat" />
	</a>
</p>


<p align="center">
	🐝 该项目是针对 <a href="https://github.com/afkT/DevUtils">DevUtils</a> 第三方库封装扩展、新技术 Demo 编写、大文件资源等迁移存储仓库。
</p>


减少 `DevUtils` 仓库大小方便快速 clone，并让 `DevUtils` 项目**更加纯粹**只保留 Dev 系列开发库相关代码。

移除多余的第三方库、插件依赖配置，避免过多无关且繁杂配置影响快速理解项目，降低第三方库下载数量、编译运行 `DevUtils 演示 Demo App` 难度，使项目可更加快捷运行。


## 仓库优化前后对比

| before | after |
|:-:|:-:|
| ![][repositories_before] | ![][repositories_after] |

优化后仓库大小为 **12.7MB**，相较之前减少了 **56.4MB**。



<!-- ------- -->
<!-- JavaDoc -->
<!-- ------- -->


<h1 align="center">
	<a href="https://github.com/afkT/JavaDoc">JavaDoc</a>
</h1>


<p align="center">
	<a href="https://github.com/afkT">
		<img alt="Profile" src="https://img.shields.io/badge/GitHub-afkT-orange.svg" />
	</a>
	<a href="https://github.com/afkT/JavaDoc/blob/master/LICENSE">
		<img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" />
	</a>
	<a href="https://search.maven.org/search?q=io.github.afkt">
		<img alt="Version" src="https://img.shields.io/badge/Maven-Dev-5776E0.svg" />
	</a>
</p>


<p align="center">
	🍧 该项目通过 JavaDoc API 读取 class 中的信息 (注释、方法名、参数、返回值等)
</p>


方便大家通过了解 JavaDoc API 并能够实现节省时间、提高效率的工具。

编写该项目主要是提高效率，方便 Dev 系列开发库生成 API 以及检测代码规范、中英字符间距、@param、@return 等容易遗漏且复杂耗时的操作


### 代码排版

> 代码、注释间距规范检测通过第三方类 pangu.java 进行检测

- [Github - vinta/pangu.java][Github - vinta/pangu.java]

- [中文文案排版指北 - 简书][中文文案排版指北 - 简书]


### 生成效果

- [DevApp API][DevApp API] Android 工具类库

- [DevAssist API][DevAssist API] 封装逻辑代码, 实现多个快捷功能辅助类、以及 Engine 兼容框架等

- [DevBase API][DevBase API] Base ( Activity、Fragment )、MVP、ViewBinding、ContentLayout 基类库

- [DevBaseMVVM API][DevBaseMVVM API] MVVM ( ViewDataBinding + ViewModel ) 基类库

- [DevEngine API][DevEngine API] 第三方框架解耦、一键替换第三方库、同类库多 Engine 组件化混合使用

- [DevHttpCapture API][DevHttpCapture API] OkHttp 抓包工具库

- [DevHttpCaptureCompiler API][DevHttpCaptureCompiler API] OkHttp 抓包工具库 ( 可视化功能 )

- [DevHttpManager API][DevHttpManager API] OkHttp 管理库 ( Retrofit 多 BaseUrl 管理、Progress 监听 )

- [DevRetrofit API][DevRetrofit API] Retrofit + Kotlin Coroutines 封装

- [DevWidget API][DevWidget API] 自定义 View UI 库

- [DevEnvironment API][DevEnvironment API] Android 环境配置切换库

- [DevJava API][DevJava API] Java 工具类库 ( 不依赖 android api )

- [DevOther API][DevOther API] 功能、工具类二次封装, 直接 copy 使用【 大部分迁移至 DevUtils-repo 】



<!-- --- -->
<!-- End -->
<!-- --- -->


<!-- ---- -->
<!-- Link -->
<!-- ---- -->


[100% Kotlin]: http://www.kotlincn.net/docs/reference
[ARouter]: https://github.com/alibaba/ARouter
[Android JetPack]: https://developer.android.com/jetpack
[Kotlin]: http://www.kotlincn.net/docs/reference
[DataBinding]: https://developer.android.com/topic/libraries/data-binding
[ViewModel]: https://developer.android.com/topic/libraries/architecture/viewmodel
[Lifecycle]: https://developer.android.com/topic/libraries/architecture/lifecycle
[module]: https://github.com/afkT/DevUtils/raw/master/art/module.png
[repositories_before]: https://github.com/afkT/DevUtils-repo/raw/main/art/git_delete/repositories_before.png
[repositories_after]: https://github.com/afkT/DevUtils-repo/raw/main/art/git_delete/repositories_after.png
[Github - vinta/pangu.java]: https://github.com/vinta/pangu.java
[中文文案排版指北 - 简书]: https://www.jianshu.com/p/a05ecfe0fea5#%E4%B8%AD%E8%8B%B1%E6%96%87%E4%B9%8B%E9%97%B4%E9%9C%80%E8%A6%81%E5%A2%9E%E5%8A%A0%E7%A9%BA%E6%A0%BC
[DevApp API]: https://github.com/afkT/DevUtils/blob/master/lib/DevApp/README.md
[DevAssist API]: https://github.com/afkT/DevUtils/blob/master/lib/DevAssist/README.md
[DevBase API]: https://github.com/afkT/DevUtils/blob/master/lib/DevBase/README.md
[DevBaseMVVM API]: https://github.com/afkT/DevUtils/blob/master/lib/DevBaseMVVM/README.md
[DevEngine API]: https://github.com/afkT/DevUtils/blob/master/lib/DevEngine/README.md
[DevHttpCapture API]: https://github.com/afkT/DevUtils/blob/master/lib/DevHttpCapture/README.md
[DevHttpCaptureCompiler API]: https://github.com/afkT/DevUtils/blob/master/lib/HttpCapture/README.md
[DevHttpManager API]: https://github.com/afkT/DevUtils/blob/master/lib/DevHttpManager/README.md
[DevRetrofit API]: https://github.com/afkT/DevUtils/blob/master/lib/DevRetrofit/README.md
[DevWidget API]: https://github.com/afkT/DevUtils/blob/master/lib/DevWidget/README.md
[DevEnvironment API]: https://github.com/afkT/DevUtils/blob/master/lib/Environment
[DevJava API]: https://github.com/afkT/DevUtils/blob/master/lib/DevJava/README.md
[DevOther API]: https://github.com/afkT/DevUtils-repo/blob/main/lib/LocalModules/DevOther
