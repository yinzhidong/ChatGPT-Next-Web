

> https://chat-gpt-next-web.vercel.app/

> https://blog.laoda.de/archives/docker-compose-install-chatgpt-next-web

> https://yinzhidong-fictional-yodel-xrrwvj4g64w265v5.github.dev/?editSessionId=46c7a4ed-4f6a-4ca0-8708-80bc4924533e&continueOn=1



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









#### Awesome List

> https://github.com/moeakwak/chatgpt-web-share
> https://github.com/Ice-Hazymoon/openai-scf-proxy
> https://yidadaa-chatgptnextweb-l3x6l0vxvaf.ws-us93.gitpod.io/