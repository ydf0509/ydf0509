<html lang="ch">
    <table style="margin-left: auto; margin-right: auto;">
<tr>
            <td>
                <a href="https://github.com/ydf0509/nb_time">nb_time</a>
            </td>
            <td>
                pip install nb_time <br>
               面向对象封装的NbTime 时间类，方便时间转化和时区支持，支持无限链式操作，用法暴击亲自使用 datetime 和 三方 arrow 包 <br>
               比面向过程工程师在time_utils.py写几百个孤立的时间转换函数用法方便太多。<br>
               NbTime 能把任意格式的时间字符串转成时间对象，无需精确的提前写yyyy-mm-dd这样的字符串模板。
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/db_libs">db_libs</a>
            </td>
            <td>
                 pip install db_libs <br>
                各种数据库的封装。只封装生成连接，很少添加新的方法调用原生方法这种写法。
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/async_pool_executor">async_pool_executor</a>
            </td>
            <td>
                pip install async_pool_executor <br>
                its api like the concurrent.futures.使asyncio并发编程简化10倍
            </td>
        </tr>
         <tr>
            <td>
                <a href="https://github.com/ydf0509/flexible_thread_pool">flexible_thread_pool</a>
            </td>
            <td>
                pip install flexible_thread_pool <br>
                flexible_thread_pool 支持同步函数和 acync def 的 异步函数并发执行。
                可扩大和自动缩小的线程池，比 threadpool_executor_shrink_able 实现更简单的线程池，性能超过 concurrent.futures.ThreadpoolExecutor 200%
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/sync2asyncio">sync2asyncio</a>
            </td>
            <td>
                pip install sync2asyncio <br>
                python 快速万能同步转异步语法
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/object_pool_proj">object_pool_proj</a>
            </td>
            <td>
            pip install universal_object_pool <br>
            通用对象池，可以池化任意自定义类型的对象，用于快速实现任意池(线程池除外)。
                        </td>
       </tr>
          <tr>
            <td>
                <a href="https://github.com/ydf0509/nb_http_client">nb_http_client</a>
            </td>
            <td>
                pip install nb_http_client    <br>
                powred by object_pool_proj    <br>
                nb_http_client 是 python 史上性能最强的http客户端，比任意请求包快很多倍
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/celery_demo">celery_demo</a>
            </td>
            <td>
                演示复杂深层路径，完全不按照一般套路的目录格式的celery使用
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/funboost_support_celery_demo">funboost_support_celery_demo</a>
            </td>
            <td>
                演示复杂深层路径，完全不按照一般套路的目录格式,使用funboost来自动化配置和操作celery,代码极其简化
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/nb_filelock">nb_filelock</a>
            </td>
            <td>
                pip install nb_filelock <br>
                使用磁盘文件作为介质，实现基于单台机器的跨进程跨解释器的分布式锁。
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/tps_threadpool_executor">tps_threadpool_executor</a>
            </td>
            <td>
                pip install tps_threadpool_executor <br>
                控频线程池，能够指定精确每秒运行多少次函数，而不是精确指定程序线程池中同时多少个线程在并发
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/auto_run_on_remote">auto_run_on_remote</a>
            </td>
            <td>
                pip install auto_run_on_remote <br>
                在本机点击运行一个python脚本，但自动使该脚本自动在远程linux机器上运行。<br>
                方便程度暴击pycahrm 专业版调用远程linux解释器
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/auto_restart">auto_restart</a>
            </td>
            <td>
                pip install auto_restart <br>
                自动重启冷部署工具。当检测到git内容发生变化时候，会自动重启服务，无需手动重启发版。
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/base_decorator">base_decorator</a>
            </td>
            <td>
                pip install base_decorator <br>
                通用的装饰器基类，使写装饰器变得更简单。
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/decorator_libs">decorator_libs</a>
            </td>
            <td>
                pip install decorator_libs <br>
                常用的日常通用装饰器大全
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/fastapi_use_funboost">fastapi_use_funboost</a>
            </td>
            <td>
                fastapi 使用分布式函数调度框架 fastapi_use_funboost 作为后台消费的 demo
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/ydf0509/uwsgi_flask_funboost">uwsgi_flask_funboost</a>
            </td>
            <td>
                  uwsgi部署flask + funboost 作为后台消费的 demo
            </td>
        </tr>
<tr>
            <td>
                <a href="https://github.com/ydf0509/django_use_funboost">django_use_funboost</a>
            </td>
            <td>
                  dajngo + funboost 作为后台消费的 demo
            </td>
        </tr>
<tr>
            <td>
                <a href="https://github.com/ydf0509/funboost_django_orm_demo">funboost_django_orm_demo</a>
            </td>
            <td>
                  dajngo + funboost + 函数中操作了orm ,作为后台消费的 demo
            </td>
        </tr>
         <tr>
            <td>
                <a href="https://github.com/ydf0509/distrubuted_framework_vs_celery_benchmark">funboost_vs_celery_benchmark</a>
            </td>
            <td>
                使用严谨精确的控制变量法，测试分布式函数调度框架 funboost 和celery的性能对比
            </td>
        </tr>
  <tr>
            <td>
                <a href="https://github.com/ydf0509/pysnooper_click_able">pysnooper_click_able</a>
            </td>
            <td>
                pip install pysnooper_click_able   神级别黑科技装饰器，实现难度5颗星。不用打断点不用到处加print的deubg工具，可以精确显示代码运行率轨迹并点击。
                可以精确动态统计调用一个函数背后，python到底解释执行了多少行代码，让你对函数消耗的cpu资源了如指掌。
            </td>
        </tr>

 <tr>
            <td>
                <a href="https://github.com/ydf0509/kuai_log">kuai_log</a>
            </td>
            <td>
                pip install kuai_log
                速度最快的python日志,比nb_log更简单简化,没有三方包依赖和无需配置文件
            </td>
        </tr>
 <tr>
            <td>
                <a href="https://github.com/ydf0509/realtime_web_logs">realtime_web_logs</a>
            </td>
            <td>
                pip install realtime_web_logs
                文件日志实时显示到web页面。附带全系统硬盘的文件浏览下载功能。支持日志显示自动滚动和暂停。
            </td>
        </tr>
         <tr>
            <td>
                <a href="https://github.com/ydf0509/pythonpathdemo">pythonpathdemo</a>
            </td>
            <td>
                用专门的项目说明掌握python的 PYTHONPATH的重要性；说明窗口会话临时环境变量和永久性环境变量区别；说明pythonpath的好处；说明pythonpath的妙用。学了PYTHONPATH 写几十个项目复用公共代码如虎添翼
            </td>
        </tr>
 <tr>
            <td>
                <a href="https://github.com/ydf0509/pyhton-oop-4step">pyhton-oop-4step</a>
            </td>
            <td>
                python 万能通用 oop面向对象编程四步转化公式，面向过程转面向对象的万能可具体落地非抽象的4步转化公式。
            </td>
        </tr>
    </table>
</html>










