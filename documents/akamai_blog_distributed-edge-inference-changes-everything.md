# Distributed Edge Inference Changes Everything
Nov 21, 2025
Written by [Ari Weil](https://www.akamai.com/blog?author=ari_weil)
Ari Weil is Vice President of Cloud Computing and Delivery Product Marketing at Akamai.

![Ari Weil is Vice President of Cloud Computing and Delivery Product Marketing at Akamai.](https://www.akamai.com/site/en/images/blog/userpics/ari-weil.jpg)

Share
We're witnessing the third great scaling wave in AI, and it demands a fundamental rethinking of critical infrastructure. While the industry has been mesmerized by the race to build ever-larger frontier models, and businesses are making early efforts to identify killer apps and ROI, the real battleground for enterprise AI value creation has shifted to the edge.
## The evolution of AI scaling waves  

Why discuss these as scaling waves? Because waves are forces that build, crest, and transform the landscape — with the momentum, inevitability, and cascading effects that trigger the next wave. The three waves, which are unstoppable forces that are reshaping entire industries, include:
  * First wave: Pre-training at massive scale
  * Second wave: Post-training and fine-tuning
  * Third wave: Multistep inference and reasoning


Let me explain why these matter for every business leader who is making AI infrastructure decisions today.
### The first wave  

The first wave — pre-training at massive scale — gave us GPT-4, Claude, and the frontier models that introduced enterprises to AI's transformative potential. These models became our productivity copilots, our brainstorming partners, our first glimpse into what artificial general intelligence might enable. 
They also, however, came with a few catches: astronomical compute costs, significant latency for global users, and the inherent limitations of centralized processing. 
**As an industry, we ignore the latency because streaming tokens are a fresh way to engage — Oh, look, the AI is thinking**.
### The second wave  

The second wave — post-training and fine-tuning — brought AI closer to business reality. Enterprises learned to adapt foundation models to their specific domains by using proprietary data and institutional knowledge. 
This wave delivered the first real ROI stories: customer service automation that actually understood context, code generation that followed company standards, and conversational interfaces that felt native to existing applications. 
Yet even these specialized models remain tethered to centralized clouds. As use cases develop, this centralization will create bottlenecks for real-time, latency-sensitive use cases, such as personalized recommendations, autonomous vehicles and manufacturing, and physical AI and robotics that will require responses in milliseconds not seconds or minutes. 
**A lack of distribution hasn’t become a bottleneck because the use cases that will require it aren’t being used at scale … yet**.
### The third wave  

Now we're entering the third wave, which requires models to reason through complex workflows, maintain context across extended interactions, and deliver responses in real time at global scale. 
This isn't just about making models bigger — it's about making them work harder, think longer, and operate everywhere your users are. To make AI useful at scale, it needs to be fast, secure, accurate, and engaging. 
**Distributed inference will enable us to bring these various factors together at the edge, and it will change everything about how we engage, monetize, and grow our businesses**.
## The infrastructure challenge no one talks about … yet  

Here's what most infrastructure providers won't tell you: The economics of centralized AI inference break down catastrophically for real time use cases at scale. When every inference request requires a round trip to a distant data center, you're not just dealing with latency, you're facing compounding costs from bandwidth, queuing delays, and the sheer physics of distance.
Consider what happens when an AI agent needs to perform multistep reasoning. Each step might require multiple model calls, vector database lookups, and API integrations. In a centralized architecture, you're looking at hundreds of milliseconds per step, which quickly add up to unacceptable response times for real-world applications. 
Now, multiply that by thousands of concurrent users across different geographies, and you understand why the hyperscalers' centralized approach hits a wall.
## Akamai Inference Cloud: Built for real-time distributed AI  

This is precisely why we built [Akamai Inference Cloud](https://www.akamai.com/products/akamai-inference-cloud-platform). We're not trying to compete with hyperscalers to determine who can build the biggest cluster in any small region. We're solving the actual problem enterprises face: How to deliver AI inference at planetary scale with local performance.
Our approach leverages three critical advantages that only Akamai can deliver:
  1. Infrastructure at the edge
  2. Platform-native AI operations
  3. Security that understands AI


### Infrastructure at the edge  

We're deploying NVIDIA Blackwell RTX PRO 6000 Server Edition GPUs across our global network — not in a handful of mega data centers, but distributed where your users actually are. This isn't experimental; it's production-ready infrastructure built on the same network that already delivers approximately 30% of web traffic.
### Platform-native AI operations  

Through NVIDIA Inference Microservices (NIM) running on our [Linode Kubernetes Engine (LKE)](https://www.akamai.com/blog/cloud/linode-kubernetes-engine-optimization), we're making it simple to deploy, scale, and manage AI workloads. Your teams get access to integrated vector databases for retrieval-augmented generation (RAG) implementations, object storage for model artifacts, and global load balancing that automatically routes inference requests to the optimal location. 
This isn't bolted-on AI — it's AI-native platform design.
### Security that understands AI   

Here's where it gets especially interesting. Traditional security wasn't built for AI workloads. We've developed purpose-built protections across every layer, including:
  * **Application security** that discovers AI-augmented apps and APIs, continuously assesses their security posture, and applies intelligent controls
  * **AI firewall** capabilities specifically designed to protect prompts from injection attacks and models from extraction attempts
  * **Workload security** that uses AI itself to analyze east-west traffic patterns, automatically generate optimal segmentation policies, and continuously adapt to emerging threats
  * **Access security** through our Secure Enterprise Browser that controls employee interactions with LLM interfaces and prevents data exfiltration, combined with [Zero Trust Network Access](https://www.akamai.com/glossary/what-is-ztna) and [multi-factor authentication](https://www.akamai.com/glossary/what-is-multifactor-authentication) for infrastructure access
  * **Infrastructure security** that provides real-time DNS and network posture assessment with AI-driven policy recommendations
  * **Generative SIEM interfaces** that transform security operations by making vast amounts of telemetry data conversationally accessible to teams in the security operations center


When you move inference from centralized clouds to the edge, latency drops (making real-time AI interactions actually feel real time), bandwidth costs decrease (by processing data where it's generated), and compliance becomes manageable (because you can guarantee data processing happens within specific geographic boundaries). Furthermore, reliability improves dramatically through true redundancy — not just via multiple availability zones in one region, but through genuinely distributed processing.
But the real transformation happens at the application level. Suddenly, use cases that were impossible become trivial. Multi-agent workflows that previously required complex orchestration become simple. Real-time personalization at scale becomes economically viable.
## What this means for your AI strategy  

**If you're still thinking about AI infrastructure in terms of training clusters and model hosting, then you're solving yesterday's problem**. The enterprises that win in this third wave will be those that recognize inference — not training — as the critical bottleneck, and distributed edge infrastructure as the solution to that problem.
The question isn't whether you need distributed inference infrastructure. The question is whether you'll build it yourself (good luck with that), wait for the hyperscalers to eventually offer it (while your competitors move ahead), or use the platform that's already operating at planetary scale.
At Akamai, we've spent 25 years solving the hard problems of distributed computing, security, and global scale. Akamai Inference Cloud is the natural evolution of the infrastructure that already powers the internet.
The third wave of AI is here. The infrastructure to support it is here. The only question is: Are you ready to ride the wave?
## Learn more  

To learn more about how Akamai Inference Cloud can transform your AI infrastructure strategy, visit our [website ](https://www.akamai.com/products/akamai-inference-cloud-platform)or connect with me on[ LinkedIn](https://www.linkedin.com/in/ariweil/).
[ Learn more ](https://www.akamai.com/products/akamai-inference-cloud-platform)
![Ari Weil is Vice President of Cloud Computing and Delivery Product Marketing at Akamai.](https://www.akamai.com/site/en/images/blog/userpics/ari-weil.jpg)
Nov 21, 2025
[Ari Weil](https://www.akamai.com/blog?author=ari_weil)
![Ari Weil is Vice President of Cloud Computing and Delivery Product Marketing at Akamai.](https://www.akamai.com/site/en/images/blog/userpics/ari-weil.jpg)
Written by
[Ari Weil](https://www.akamai.com/blog?author=ari_weil)
Ari Weil is Vice President of Cloud Computing and Delivery Product Marketing at Akamai.
Tags
  * [Cloud](https://www.akamai.com/blog?filter=blogs/cloud)
  * [Akamai Inference Cloud](https://www.akamai.com/blog?filter=products/akamai-inference-cloud)


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
    * [English](https://www.akamai.com/blog/cloud/distributed-edge-inference-changes-everything "English")
    * [Deutsch](https://www.akamai.com/de "Deutsch")
    * [Español](https://www.akamai.com/es "Español")
    * [Français](https://www.akamai.com/fr "Français")
    * [Italiano](https://www.akamai.com/it "Italiano")
    * [Português](https://www.akamai.com/pt "Português")
    * [中文](https://www.akamai.com/zh "中文")
    * [日本語](https://www.akamai.com/ja "日本語")
    * [한국어](https://www.akamai.com/ko "한국어")


©2025 Akamai Technologies
## Your cookie choices for this website
We use cookies to ensure the fast reliable and secure operation of this website, to improve your website experience, to enable certain social media interactions and to manage your cookie choices. Some cookies process personal data or personal information. By agreeing to the placement of the cookies you also agree to the related processing activities, where applicable. Click “Accept Cookies” to agree to the placement of all cookies except for strictly necessary cookies and to the related processing activities or click “Manage Preferences” to make individual choices and get details on the cookies in use and the processing activities in the Cookie Details section. You can access the Cookie Management Page and withdraw the consent at any time via the Cookie Settings link in the footer. For additional information relating to your privacy take a look at our[Privacy Statement](https://www.akamai.com/legal/privacy-and-policies/privacy-statement)
Accept All CookiesManage Preferences
![](https://atiprod.112.2o7.net/b/ss/atiprod/1?AQB=1&pageName=Distributed%20Edge%20Inference%20Changes%20Everything&g=https://www.akamai.com/blog/cloud/distributed-edge-inference-changes-everything&r=&ch=blog&server=www.akamai.com&v0=&v1=www.akamai.com/blog/cloud/distributed-edge-inference-changes-everything&v2=https://www.akamai.com/blog/cloud/distributed-edge-inference-changes-everything&v3=blog:cloud:2025:nov:distributed-edge-inference-changes-everything&v4=/blog/cloud/distributed-edge-inference-changes-everything&v5=en:jp&v22=Ari%20Weil&v24=2025-11-21&v31=blog:cloud:2025:nov:distributed-edge-inference-changes-everything&v32=&v33=&v61=&v62=&v63=&v64=akamai-inference-cloud,akamai-inference-cloud&v65=&v66=&v67=&v68=cloud,cloud&v69=&v70=&v25=opted%20out&s=1080x600&cl=none&AQE=1)

