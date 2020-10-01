# awesome-freemium-serverless-clouds
A curated list of true freemium serverless code execution cloud providers
- Provides subdomain based URL to invoke code.
- Http(s) support
- Support sending back the CORS headers to have cross domain calls.
- Outbound internet access from serverless execution environment to work with  datastores & APIs.
- May not have SLA and service may go down on reaching limits

# What is true freemium?
The freemium services don't require a credit card to start and operate for personal non-commercial uses.

| Name ⮫<br/>⮮Feature  | Heroku         |   Vercel   |  Netlify     | 
|:-                     | -              | -          | -            |
| NodeJS                | Yes            | Yes        | Yes          |
| Go                    |                |            | Yes          |
| Local development     |                |            | Yes          |
|                           **Features**                          ||||
| Http/2                |                | No         |              |
| WebSockets            |      Yes       | No         |              |
|                       **Deployment limits**                     ||||
| Function size         |                | 50MB       |              |
| Build Time            | 1 at a time    | 32/hour    |300 Mins/month|
| Deployments           |                | 100/day    |              |
|                      **Execution limits**                       ||||
| Band width            |                |            |100GB/month   | 
| Invocations           | 4500/hour      |            |125K/month    |          
| Request size limit    |                | 5 MB       |              |
| Response size limit   |                | 5 MB       |              |  
| Memory                | 512 MB         | 1024 MB    |              |
| Execution time        | 550 hrs/month  |            |              |
| Request timeout       | 30 secs        | 10 secs    | 10 secs      |
| Idle time             | 30 mins        |            |              |
# Sources
- [Heroku](https://devcenter.heroku.com/articles/limits)
  - [WebSockets](https://devcenter.heroku.com/articles/websockets)
- [Vercel](https://vercel.com/docs/platform/limits)
- [Netlify](https://www.netlify.com/pricing/), [FAQ](https://www.netlify.com/pricing/faq/),[terms](https://www.netlify.com/tos/)

# Other lists

Below are some list related but not filtered by true freemium. Some may require credit card also has more types of freemium services.

- [https://github.com/anaibol/awesome-serverless](https://github.com/anaibol/awesome-serverless)
- [https://github.com/agarrharr/awesome-static-website-services](https://github.com/agarrharr/awesome-static-website-services)