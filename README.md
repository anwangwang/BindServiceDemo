# BindServiceDemo
service练习。Bind(绑定)方式开启一个service


* 当activity销毁的时候服务也销毁。不求同时，但求同死

* 使用bind开启service的目的，就是为了调用service里面的方法。（四大组件的运行需要上下文环境，不能直接用new 关键字创建，创建出来的就是一个普通的对象，不具备上下文环境）


