

> https://chat-gpt-next-web.vercel.app/


> https://blog.laoda.de/archives/docker-compose-install-chatgpt-next-web



bash <(curl -Ls https://cpp.li/openai




#### docker-compose部署

docker-compose.yaml 文件，熟悉 docker 环境的小伙伴可以直接拷贝搭建


```yaml

version: '3.3'
services:
    chatgpt-next-web:
        ports:
            - '8090:3000'
        environment:
            - OPENAI_API_KEY=sk-xxxx    # 填写你的API KEY
            - CODE=your-password    # 填一个密码，不然你的额度很快就会被刷完
        image: yidadaa/chatgpt-next-web

```