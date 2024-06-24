# 安装监控中间件
如果你需要开启监控功能请安装kube-prometheus-stack组件
helm install im-kube-prometheus-stack infra/kube-prometheus-stack/ -f prometheus-config.yaml
说明：开启监控功能你需要一个域名用于grafana网页的访问,请修改prometheus-config.yaml成你真实的域名和tls名称

