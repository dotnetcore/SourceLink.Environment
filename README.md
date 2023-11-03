# SourceLink.Environment

[![Member project of .NET Core Community](https://img.shields.io/badge/member%20project%20of-NCC-9e20c9.svg)](https://github.com/dotnetcore)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/dotnetcore/CAP/master/LICENSE.txt)

为 SourceLink 功能提供可继承性的 Nuget 包

## 使用方法

1、项目作者引用该包  

2、项目作者在发布 NUGET 包时需要指定源码的 GITHUB 地址 `<PackageProjectUrl>https://github.com/dotnetcore/Natasha</PackageProjectUrl>`

3、用户引用上述 NUGET 包，并对 VS 做出如下设置：  

   - 选项 - 调试 - 启用源链接支持。  
   - 选项 - 调试 - 去掉 启用”仅我的代码“ 前面的钩。  
    
4、用户在调试时，F11 进入封装好的函数内  
