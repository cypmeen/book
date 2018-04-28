# RxLifeCycler


> 此库主要是为了防止RxJava中subscription导致内存泄露而诞生的，核心思想是通过监听Activity、
Fragment的生命周期，来自动断开subscription以防止内存泄露,现结合到项目中正好可以解决之前网络回调的空指针以及内存泄露问题。

GitHub地址: https://github.com/trello/RxLifecycle


