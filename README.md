cookiecutter 是一个通过项目模板创建项目的命令行工具。

安装 cookiecutter

sudo pip3 install -U cookiecutter
初始化项目



cd workspace
cookiecutter https://github.com/pyloong/cookiecutter-pythonic-project
运行命令后会出现下面的配置过程，如果你不清楚配置的具体用途，可以直接按回车使用默认配置，默认配置使用项目模板初始值。


生成项目的 src 目录下有一个项目模块，用来存放项目源代码， tests 目录用来编写模块的相关测试代码。

pyproject.toml 包含项目初始依赖，和项目的描述信息，tox.ini 定义了任务自动化执行逻辑。


