# appdemo
题目：创建一个Istio服务网格，要求如下：
至少有2个服务，彼此有调用关系（如 A -> B）
创建一个ingressgateway，基于不同的host路由到不同的Service
某一个服务有2个版本，配置一个基于权重的流量切分
限定A（出流量）只能访问B
网格（当前namespace）启用mtls
添加一个授权策略，使得网格内某服务无法访问其他服务
产生一些流量，用kiali观察网格情况

