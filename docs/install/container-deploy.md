# 容器部署模式

docker run -d --name kubez-ansible --net host -v /root/.ssh/:/root/.ssh/ -v /etc:/etc -w /root --restart=always pixiuio/kubez-ansible:v2.0.0 sleep infinity
