# AI: Edge Is All You Need
Oct 28, 2025
[Jon Alexander](https://www.akamai.com/blog?author=jon-alexander)
![Jon Alexandar](https://www.akamai.com/site/en/images/blog/userpics/jon-alexander.jpeg)
Written by [Jon Alexander](https://www.akamai.com/blog?author=jon-alexander)
Jon Alexander is Senior Vice President of Product for the Cloud Technology Group at Akamai. He is responsible for the strategy, roadmap, and success of the cloud computing and delivery products. Jon joined Akamai in 2017 and led various product teams inside Akamai, starting within the media division. Previously, he worked in several roles focused on building large-scale internet infrastructure. Jon spent 10 years running the media business at one of the world’s largest telecommunications carriers and has led product teams at start-ups as they defined, launched, and grew new solutions. He is passionate about fostering innovation and building customer-centric product teams. He holds a Master of Arts degree and a Master of Engineering degree from Cambridge University.
Share

## Executive summary  

  * Akamai Inference Cloud is a full-stack cloud platform that enables organizations to build, protect, and optimize AI-powered applications at the edge.
  * The platform is designed to support agentic systems that adapt to users, communicate with other agents, and act in real time.
  * Key features include NVIDIA Blackwell GPUs, managed Kubernetes, vector databases, and AI-aware security.
  * The platform empowers three specific users: machine learning operations engineers, AI engineers, and agentic system architects.
  * Akamai Inference Cloud provides a reliable, secure, and scalable foundation for deploying advanced AI systems anywhere.


In 2017, a research paper quietly changed the course of technology. [Attention Is All You Need](https://arxiv.org/abs/1706.03762) introduced the Transformer architecture, a new kind of model for processing language and data that would soon underpin nearly every major advancement in artificial intelligence (AI). At the time, the breakthrough was confined mostly to academic and developer circles.
Five years later, in November 2022, OpenAI launched ChatGPT. For the first time, the broader public could interact firsthand with a system built on what this architecture made possible. It was a glimpse into a new kind of interface — not just with machines, but with knowledge itself. 
Now, just three years after that launch, OpenAI reports more than [700 million weekly active users](https://openai.com/index/how-people-are-using-chatgpt/). 
The [World Economic Forum](https://www.weforum.org/stories/2025/10/ai-s-new-dual-workforce-challenge-balancing-overcapacity-and-talent-shortages/) has noted: AI is introducing a dual disruption to the workforce. On one side, automation is generating overcapacity in established roles. On the other, demand for AI fluency is accelerating faster than education and hiring systems can adapt. The old models for work — and for how we prepare people to do it — are evolving quickly.
This is the end of the beginning.
## Looking backward to move forward  

Twenty-seven years ago, the world stood at a similar inflection point. The internet was expanding rapidly, and questions of scale, reliability, and security were unresolved. In that context, a group of researchers at MIT [founded Akamai](https://www.akamai.com/company/company-history) with a clear mission: to solve the “World Wide Wait.” 
They did it by bringing compute, storage, and networking closer to the points of creation and consumption in a model that has since been frequently imitated.
The rise of the agentic web has brought us full circle, reintroducing new scale and proximity challenges unique to AI and the inference required to realize its potential. 
Akamai Inference Cloud, which we [announced today](https://www.akamai.com/newsroom/press-release/akamai-inference-cloud-transforms-ai-from-core-to-edge-with-nvidia), builds on the distributed architecture work we pioneered nearly three decades ago to expand AI inference from core data centers to the edge and, once again, to remove the bottlenecks and move past the limits of centralized infrastructure.
## The agentic web  

This new generation of intelligent systems no longer waits for human commands or input; they observe, reason, and act on behalf of users who express their intent in natural language. These systems take initiative, coordinate with other systems, and deliver outcomes without step-by-step instructions. This is the agentic web.
The agentic web is changing how people and machines interact with digital services. Experiences are becoming conversational, multimodal, and personalized. Interfaces adapt to the user’s intent, not the other way around. A person might ask for a recommendation and receive it as a narrated summary, a visual comparison, or a written breakdown depending on their preferences, context, and device. The system selects the format and tone that fits best.
### Agent-driven interactions need new ways to support them  

As these agent-driven interactions become pervasive, enterprises need new ways to support them. Inference must move closer to users. Response times need to be predictable and low. Tools and memory must be available in real time. The entire stack must support agents working on behalf of users and systems, not just handling one-off requests.
This shift is already underway, but today’s centralized cloud platforms were not designed to support it. Companies are forced to choose between raw infrastructure or narrow solutions. What is missing is a platform built specifically for [agentic AI](https://www.akamai.com/blog/security/edge-of-agency-defending-against-risks-agentic-ai), one that reduces complexity, accelerates development, and delivers intelligent behavior at global scale.
## Akamai Inference Cloud makes the future possible  

Akamai Inference Cloud makes this future possible. Its approach to cloud and AI is centered on the needs of agentic systems and applications that adapt to users, communicate with other agents, and act in real time. 
Its unique distributed architecture is specifically designed to support these patterns, bringing the high-performance compute, storage, and orchestration needed for complex inference workloads and applying routing, control, and responsiveness closer to the user. 
Our customers are facing four critical missions:
  1. Power the AI-enabled application
  2. Manage AI as a new traffic channel
  3. Resource AI agents for enterprise workloads
  4. Enable responsible AI consumption by employees


### Power the AI-enabled application  

Every enterprise will embed intelligence into their applications. This represents the next stage of application architecture — from responsive design to multicloud and now to AI-integrated, real-time systems. Akamai remains the trusted backbone that enables and secures each evolution.
### Manage AI as a new traffic channel  

Users are reaching brands through AI platforms just as they once did through search, social, or mobile. Every brand, app, and API will need to define its desired versus undesired AI interactions and manage that traffic intelligently to turn AI traffic from risk to opportunity.
### Resource AI agents for enterprise workloads  

Our customers are using AI agents to operate parts of their business — from infrastructure management to data analysis. Agents need access to first-class resources associated with f internal and external systems but with appropriate guardrails — trust, identity, observability, and safety — so that enterprises can scale their AI-operated environments with confidence and efficiency.
### Enable responsible AI consumption by employees  

Employees across every enterprise are consuming AI services — Copilot, Cursor, ChatGPT, Claude, and others. Enterprises must manage the responsible use, cost, and data protection of this consumption.
**Akamai Inference Cloud is how inference scales**.
## What is Akamai Inference Cloud?  

Akamai Inference Cloud is a full-stack cloud platform designed to build, protect, and optimize the next generation of intelligent applications that are empowered by AI. It offers compute, storage, networking, orchestration, security, and developer tooling that is aligned to the unique requirements of real-time inference, agentic systems, and intelligence that lives closer to the user (Table).
|  Build |  Protect |  Optimize  
---|---|---|---  
The problems | 
  * APIs are expensive to host
  * Centralized inference is slow
  * Hosting your own model is difficult

| 
  * AI bots are scraping content
  * AI endpoints are leaking sensitive data
  * AI endpoints are being abused
  * Threat actors are using DDoS and resource exhaustion attacks

| 
  * Traditional web is invisible to AI search
  * AI interfaces are slow
  * Costs can escalate
  * Agents need a framework for discovery, auth, identity, trust, etc.

  
The solution(s) |  Distributed intelligent infrastructure with a developer platform  |  AI-aware bot management and API security (app, API, and AI protections, working in concert with AI-aware bot management) |  AI connectivity mesh for humans and agents   
The products | 
  * NVIDIA Blackwell GPUs
  * NVIDIA BlueField DPUs
  * Managed K8s
  * K8s developer platform 
  * Vector database
  * Object/block Storage
  * Backups and Snapshots
  * VPC
  * Functions

| 
  * [Akamai Guardicore Segmentation](https://www.akamai.com/products/akamai-guardicore-segmentation)
  * [Akamai App & API Protector](https://www.akamai.com/products/app-and-api-protector)
  * [Akamai API Security](https://www.akamai.com/products/api-security)
  * [Akamai Firewall for AI](https://www.akamai.com/products/firewall-for-ai)
  * [Akamai bot & abuse protection](https://www.akamai.com/solutions/bot-and-abuse-protection)

| 
  * AEO/GEO
  * Semantic caching
  * LLM rate limits and quotas
  * MCP server
  * CDN acceleration
  * Functions
  * Observability

  
Akamai Inference Cloud is a full-stack cloud platform designed to build, protect, and optimize the next generation of intelligent applications that are empowered by AI
### Who we’re building for  

Akamai Inference Cloud is a modular platform that meets customers where they are. Whether you are consuming hosted API endpoints from OpenAI and Gemini in your apps or building an agentic workflow around your own fine-tuned, distilled models, Akamai Inference Cloud allows you to build, protect, and optimize at the edge. 
Specifically, we are empowering three specific users:
  1. **Machine learning operations engineers (MLOps)** : Engineers who automate the entire machine learning lifecycle to ensure models are continuously retrained, deployed, and monitored for performance in production
  2. **AI engineers** : Data scientists or software engineers who build end-to-end agentic applications, often using pre-trained models, and bridge the gap between data science research and production software
  3. **Agentic system architects** : An architect who has evolved from the traditional system — one who designs, builds, and manages complex, autonomous agentic systems that can independently reason, plan, act, and adapt to achieve high-level business goals


With Akamai Inference Cloud, we are not locking users into a specific paradigm or solution but providing customers with flexibility to rent infrastructure, develop on a serverless platform, and seamlessly combine complex systems based on their preferences. 
## Putting NVIDIA’s AI stack closer to where decisions are made  

On October 28, 2025, we announced the Akamai Inference Cloud and our goal to bring intelligent, agentic AI inference to the edge where personalized experiences, real-time decisions, and smart agents require it. 
Customers now have access to the latest generation of NVIDIA Blackwell GPUs, coupled with NVIDIA BlueField networking; tiered memory across GDDR7, DRAM, and NVMe; high-performance, scalable block and object storage; managed vector databases; and virtual private cloud networking. 
An MLOps engineer can rent a single GPU by the hour or build a high-performance inference cluster with up to 8 NVIDIA RTX PRO™ 6000 Blackwell Server Edition GPUs, NVIDIA BlueField-3Ⓡ DPUs, 128 vCPUs, 1,472 GB of DRAM and 8,192 GB of NVMe (Figure 1).
[ ![An MLOps engineer can rent a single GPU by the hour or build a high-performance inference cluster with up to 8 NVIDIA RTX PRO™ 6000 Blackwell Server Edition GPUs, NVIDIA BlueField-3Ⓡ DPUs, 128 vCPUs, 1,472 GB of DRAM and 8,192 GB of NVMe \(Figure 1\).](https://www.akamai.com/site/en/images/blog/2025/ai-edge-all-you-need-one.jpg) ](javascript:void\(0\);) Fig. 1: Screenshot from Akamai Cloud Manager of server SKUs
Akamai Inference Cloud is optimized for time to first token (TTFT) and tokens per second (TPS). When combined with the Akamai distributed edge infrastructure, Akamai Inference Cloud can reduce latency for real-time and interactive intelligent applications. 
NVIDIA Blackwell GPUs deliver incredible performance, as described in our [benchmarking analysis](https://www.akamai.com/blog/cloud/benchmarking-nvidia-rtx-pro-6000-blackwell-akamai-cloud).
## Deploy and monitor agentic applications with App Platform  

To further help platform engineers, we go beyond just providing infrastructure. Platform engineers can easily deploy and monitor agentic applications with our [pre-engineered](https://techdocs.akamai.com/app-platform/docs/welcome) cloud native platform that makes it simple to deploy large language models (LLMs), agents, and knowledge bases at scale. 
The platform is highly customizable, yet opinionated — it accelerates deployment, reduces operational overhead, and includes pre-integrated AI-ready components like vector databases, LLM frameworks, and OpenAI-compatible APIs into a single self-service portal. [App Platform](https://www.akamai.com/blog/developers/introducing-the-akamai-app-platform) is optimized to run on LKE, Akamai’s managed Kubernetes engine, and is portable to any [conformant Kubernetes cluster](https://www.cncf.io/training/certification/software-conformance/). 
[App Platform for LKE](https://www.akamai.com/blog/developers/getting-started-with-akamai-app-platform) integrates a suite of more than 30 trusted Cloud Native Computing Foundation (CNCF) open source tools including KServe, a Kubernetes-native framework for serving and scaling machine learning models in production, and Kubeflow Pipelines, a platform for building, deploying, and managing ML workflows on Kubernetes. 
App Platform provides both the Kubernetes framework and the AI components needed for engineers to build their own AI platform. This helps avoid DIY approaches that demand heavy integration when building and maintaining your own Kubernetes-based platform or bespoke stack (Figure 2).
[ ![This helps avoid DIY approaches that demand heavy integration when building and maintaining your own Kubernetes-based platform or bespoke stack \(Figure 2\).](https://www.akamai.com/site/en/images/blog/2025/ai-edge-all-you-need-two.jpg) ](javascript:void\(0\);) Fig. 2: Screenshot from Akamai App Platform showing the AI apps 
## Akamai Inference Cloud — Designed for NVIDIA AI Enterprise Integrations  

[NVIDIA AI Enterprise](https://www.nvidia.com/en-us/data-center/products/ai-enterprise/) is the software platform built to streamline your journey from AI development to production. This cloud native suite accelerates and simplifies how you build, deploy, and scale AI applications. Using powerful tools like NVIDIA inference microservices (NIM) and neural modules (NeMo) microservices, it helps you cut infrastructure costs and significantly speed up your time to market (Figure 3). 
[ ![Using powerful tools like NVIDIA inference microservices \(NIM\) and neural modules \(NeMo\) microservices, it helps you cut infrastructure costs and significantly speed up your time to market \(Figure 3\). ](https://www.akamai.com/site/en/images/blog/2025/ai-edge-all-you-need-three.jpg) ](javascript:void\(0\);) Fig. 3: Screenshot of NVIDIA NIMs 
Akamai Inference Cloud is evolving with native functionality to accommodate the entire suite of NVIDIA AI Enterprise software. The platform provides a reliable, secure, and scalable foundation for organizations of all sizes to deploy advanced AI systems anywhere — in the cloud, in the data center, or at the edge — all backed by an extensive partner ecosystem.
## Find out more  

Akamai Inference Cloud is evolving rapidly with many new product launches planned through 2026. Follow the [Akamai blog](https://www.akamai.com/blog/cloud) or go to [our website](https://www.akamai.com/products/akamai-inference-cloud-platform) for more information on Akamai Inference Cloud.
[ Learn more ](https://www.akamai.com/products/akamai-inference-cloud-platform)
![Jon Alexandar](https://www.akamai.com/site/en/images/blog/userpics/jon-alexander.jpeg)
Oct 28, 2025
[Jon Alexander](https://www.akamai.com/blog?author=jon-alexander)
![Jon Alexandar](https://www.akamai.com/site/en/images/blog/userpics/jon-alexander.jpeg)
Written by
[Jon Alexander](https://www.akamai.com/blog?author=jon-alexander)
Jon Alexander is Senior Vice President of Product for the Cloud Technology Group at Akamai. He is responsible for the strategy, roadmap, and success of the cloud computing and delivery products. Jon joined Akamai in 2017 and led various product teams inside Akamai, starting within the media division. Previously, he worked in several roles focused on building large-scale internet infrastructure. Jon spent 10 years running the media business at one of the world’s largest telecommunications carriers and has led product teams at start-ups as they defined, launched, and grew new solutions. He is passionate about fostering innovation and building customer-centric product teams. He holds a Master of Arts degree and a Master of Engineering degree from Cambridge University.
Tags
  * [Cloud](https://www.akamai.com/blog?filter=blogs/cloud)
  * [App & API Protector](https://www.akamai.com/blog?filter=products/app-and-api-protector)
  * [Akamai Guardicore Segmentation](https://www.akamai.com/blog?filter=products/segmentation)
  * [API Security](https://www.akamai.com/blog?filter=products/api-security)
  * [Firewall for AI](https://www.akamai.com/blog?filter=products/firewall-for-ai)


Share
## Related Blog Posts
[ ![In an era in which customer experience determines market winners, reliability is not negotiable.](https://www.akamai.com/site/en/images/blog/2025/thumbnail-image-varition-ten.png) In an era in which customer experience determines market winners, reliability is not negotiable. ](https://www.akamai.com/blog/cloud/reliability-isnt-a-feature-its-a-commitment)
Cloud
Reliability Isn't a Feature. It's a Commitment.
December 05, 2025
[Adam Karon](https://www.akamai.com/blog?author=adam_karon)
Akamai is committed to reliability and resilience. Our platform helps business-critical operations stay online, even during peak traffic and cyberattacks.
[ Read blog ](https://www.akamai.com/blog/cloud/reliability-isnt-a-feature-its-a-commitment)
[ ![Starting today, if you're building distributed applications, you have a new option.](https://www.akamai.com/site/en/images/blog/2025/thumbnail-image-varition-ten.png) Starting today, if you're building distributed applications, you have a new option. ](https://www.akamai.com/blog/cloud/building-distributed-apps-akamai-fermyon-changing-game)
Cloud
Building Distributed Apps? Akamai and Fermyon Are Changing the Game.
December 01, 2025
[Ari Weil](https://www.akamai.com/blog?author=ari_weil)
Fermyon built the engine. Akamai provides the global infrastructure. Together, we're making edge native applications as easy to deploy as pushing to GitHub.
[ Read blog ](https://www.akamai.com/blog/cloud/building-distributed-apps-akamai-fermyon-changing-game)
[ ![By running inference on the edge, we can cut the cost and reduce the delay of transmitting data long distances for processing.](https://www.akamai.com/site/en/images/blog/2025/thumbnail-image-varition-five.png) By running inference on the edge, we can cut the cost and reduce the delay of transmitting data long distances for processing. ](https://www.akamai.com/blog/cloud/full-circle-akamais-evolution-set-stage-ai-inference-era)
Cloud
Full Circle: How Akamai’s Evolution Set the Stage for the AI Inference Era
November 26, 2025
[Mike Maney](https://www.akamai.com/blog?author=michael-maney)
Read how Akamai, a pioneer in CDNs, is undergoing a profound strategic transformation into a diversified cloud and cybersecurity provider in the AI era.
[ Read blog ](https://www.akamai.com/blog/cloud/full-circle-akamais-evolution-set-stage-ai-inference-era)
### PRODUCTS
  * [ Cloud Computing  ](https://www.akamai.com/solutions/cloud-computing)
  * [ Security  ](https://www.akamai.com/security)
  * [ Content Delivery  ](https://www.akamai.com/solutions/content-delivery-network)
  * [ All Products and Trials  ](https://www.akamai.com/products)
  * [ Global Services  ](https://www.akamai.com/global-services)


### COMPANY
  * [ About Us  ](https://www.akamai.com/company)
  * [ History  ](https://www.akamai.com/company/company-history)
  * [ Leadership  ](https://www.akamai.com/company/leadership)
  * [ Facts and Figures  ](https://www.akamai.com/company/facts-figures)
  * [ Awards  ](https://www.akamai.com/company/our-awards)
  * [ Board of Directors  ](https://www.akamai.com/company/leadership/board-of-directors)
  * [ Investor Relations  ](https://www.ir.akamai.com)
  * [ Corporate Responsibility  ](https://www.akamai.com/company/corporate-responsibility)
  * [ Ethics  ](https://www.akamai.com/company/ethics-and-compliance)
  * [ Locations  ](https://www.akamai.com/company/locations)
  * [ Vulnerability Reporting  ](https://www.akamai.com/global-services/support/vulnerability-reporting)
  * [ Accessibility Statement  ](https://www.akamai.com/accessibility-statement)


### CAREERS
  * [ Careers  ](https://www.akamai.com/careers)
  * [ Working at Akamai  ](https://www.akamai.com/careers/working-at-akamai)
  * [ Students and Recent Grads  ](https://www.akamai.com/careers/students-and-recent-graduates)
  * [ Workplace Diversity  ](https://www.akamai.com/careers/workplace-diversity)
  * [ Search Jobs  ](https://akamaicareers.inflightcloud.com/search?searchable=%5B%5D&section=aka_ext)
  * [ Culture Blog  ](https://www.akamai.com/blog/culture)


### NEWSROOM
  * [ Newsroom  ](https://www.akamai.com/newsroom)
  * [ Press Releases  ](https://www.akamai.com/newsroom/press-release)
  * [ In the News  ](https://www.akamai.com/newsroom/in-the-news)
  * [ Media Resources  ](https://www.akamai.com/newsroom/media-resources)


### LEGAL & COMPLIANCE
  * [ Legal  ](https://www.akamai.com/legal)
  * [ Information Security Compliance  ](https://www.akamai.com/legal/compliance)
  * [ Privacy Trust Center  ](https://www.akamai.com/legal/compliance/privacy-trust-center)
  * [ Cookie Settings  ](https://www.akamai.com/legal/manage-cookie-preferences)
  * [ EU Digital Services Act (DSA)  ](https://www.akamai.com/legal/eu-digital-services-act)


### GLOSSARY
  * [ What Is API Security?  ](https://www.akamai.com/glossary/what-is-api-security)
  * [ What Is a CDN?  ](https://www.akamai.com/glossary/what-is-a-cdn)
  * [ What Is Cloud Computing?  ](https://www.akamai.com/glossary/what-is-cloud-computing)
  * [ What Is Cybersecurity?  ](https://www.akamai.com/glossary/what-is-cybersecurity)
  * [ What Is a DDoS attack?  ](https://www.akamai.com/glossary/what-is-ddos)
  * [ What Is Microsegmentation?  ](https://www.akamai.com/glossary/what-is-microsegmentation)
  * [ What Is WAAP?  ](https://www.akamai.com/glossary/what-is-waap)
  * [ What Is Zero Trust?  ](https://www.akamai.com/glossary/what-is-zero-trust)
  * [ See all  ](https://www.akamai.com/glossary)


  * [ ](https://twitter.com/Akamai)
  * [ ](https://www.facebook.com/AkamaiTechnologies/)
  * [ ](https://www.youtube.com/user/akamaitechnologies)
  * [ ](https://www.linkedin.com/company/akamai-technologies)


[ ![Akamai logo](https://www.akamai.com/site/en/images/logo/akamai-logo4.svg) ](https://www.akamai.com/)
* * *
  * [ EMEA Legal Notice  ](https://www.akamai.com/legal/emea-legal-notices)
  * [ Service Status  ](https://www.akamaistatus.com/)
  * [ Contact Us  ](https://www.akamai.com/why-akamai/contact-us)


  * en
    * [English](https://www.akamai.com/blog/cloud/ai-edge-all-you-need "English")
    * [Deutsch](https://www.akamai.com/de/blog/cloud/ai-edge-all-you-need "Deutsch")
    * [Español](https://www.akamai.com/es/blog/cloud/ai-edge-all-you-need "Español")
    * [Français](https://www.akamai.com/fr/blog/cloud/ai-edge-all-you-need "Français")
    * [Italiano](https://www.akamai.com/it/blog/cloud/ai-edge-all-you-need "Italiano")
    * [Português](https://www.akamai.com/pt/blog/cloud/ai-edge-all-you-need "Português")
    * [中文](https://www.akamai.com/zh/blog/cloud/ai-edge-all-you-need "中文")
    * [日本語](https://www.akamai.com/ja/blog/cloud/ai-edge-all-you-need "日本語")
    * [한국어](https://www.akamai.com/ko/blog/cloud/ai-edge-all-you-need "한국어")


©2025 Akamai Technologies
## Your cookie choices for this website
We use cookies to ensure the fast reliable and secure operation of this website, to improve your website experience, to enable certain social media interactions and to manage your cookie choices. Some cookies process personal data or personal information. By agreeing to the placement of the cookies you also agree to the related processing activities, where applicable. Click “Accept Cookies” to agree to the placement of all cookies except for strictly necessary cookies and to the related processing activities or click “Manage Preferences” to make individual choices and get details on the cookies in use and the processing activities in the Cookie Details section. You can access the Cookie Management Page and withdraw the consent at any time via the Cookie Settings link in the footer. For additional information relating to your privacy take a look at our[Privacy Statement](https://www.akamai.com/legal/privacy-and-policies/privacy-statement)
Accept All CookiesManage Preferences
![](https://atiprod.112.2o7.net/b/ss/atiprod/1?AQB=1&pageName=AI:%20Edge%20Is%20All%20You%20Need&g=https://www.akamai.com/blog/cloud/ai-edge-all-you-need&r=&ch=blog&server=www.akamai.com&v0=&v1=www.akamai.com/blog/cloud/ai-edge-all-you-need&v2=https://www.akamai.com/blog/cloud/ai-edge-all-you-need&v3=blog:cloud:2025:oct:ai-edge-all-you-need&v4=/blog/cloud/ai-edge-all-you-need&v5=en:jp&v22=Jon%20Alexander&v24=2025-10-28&v31=blog:cloud:2025:oct:ai-edge-all-you-need&v32=&v33=&v61=&v62=&v63=&v64=api-security,app-and-api-protector,segmentation,firewall-for-ai,api-security,app-and-api-protector,segmentation,firewall-for-ai&v65=&v66=&v67=&v68=cloud,cloud&v69=&v70=&v25=opted%20out&s=1080x600&cl=none&AQE=1)

