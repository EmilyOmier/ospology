# Risks and Challenges 

Business stakeholders who have heard of open source software but aren't well-educated about what open source is or what it can do for businesses (which is most business stakeholders) tend to **underestimate** the risks from using open source software while **overestimating** the risks from contributing to and/or publishing and maintaining open source projects. When talking with business stakeholders, it's important to be honest about the potential risks from open source software -- both from using OSS anonymously as part of the software stack and from contributing to and creating projects. Business stakeholders aren't stupid; if you don't address these risks head-on you'll lose credibility. It's also important to address the risks open source software can create because you need to find ways to mitigate those risks and protect your organization. For many OSPOs, risk mitigate is a core part of the mission.

It's also important to think critically about risks from your engagement with open source software because there will be times when the risks and downsides outweigh the benefits. In fact, one of the key elements of a mature open source strategy is having a framework for evaluating when it makes sense to use, contribute to and create open source projects, so that risk/benefit calculations aren't based just on gut instinct. 


## Risks and challenges from using open source software

Open source software is everywhere, from programming languages to libraries to end-user applications. Particularly because open source is so critical at the infrastructure layer, it's nearly impossible to find an organization that doesn't have open source software as part of its software stack. From a superficial business perspective, this can seem like a no-brainer -- someone puts code on the internet, you take it and integrate it into your stack. Your engineers are able to work much more effectively, you deliver more features more quickly. Everyone is happy. 

In many organizations, stakeholders outside the engineering organization aren't even aware that open source software is being used at all -- and in some cases, even engineering leadership isn't aware. That's because most engineers will assume that it's ok to use open source components unless they are told otherwise -- it's such an accepted software development practice. They won't necessarily ask for permission to do so, nor will they report on the fact that there are open source components in the stack. To many software engineers, open source components are just the water they swim in; they assume that everyone else assumes they are using them. 

In addition, many software engineers don't actually know what open source means. 

However, there are three main categories of risk that can come from simply using open source. One is security; there can be vulnerabilies or even backdoors in the open source components that render the entire application vulnerable. The second is around legal compliance; just because a project is available on GitHub does not mean the code can be used for abosolutely all purposes, and not all uses are allowed under all open source licenses. The third category of risk from open source components comes from abandoned projects. Like all software, open source projects, whether they are full-fledged end-user applications or niche libraries, require some kind of mainenance. All software can be abandoned, but open source projects can live on GitHub for years without being maintained. It's a myth that all open source projects are maintained by volunteers, but nonetheless many projects are created and maintained by a single person doing the project in their spare time. Therefore, the risk of abandonment is always there, and evaluating project health before using the project is a key way to minimize this risk. 

### Security

Whether or not open source software is inherently more secure than closed-source software is debatable. Some people will say that because open source software is visible to all, the transperancy means more eyes on the code and a greater likelihood that security vulnerabilities will be uncovered before they go into production. Others argue that closed source software is closed; therefore it's harder for malicious actors to see the code and figure out how to exploit it. Regardless of which camp you're in, it would be naive to think that there are never security issues with open source software. 

There have been a couple of high-profile security vulnerabilities related to open source software in the past several years. The [Log4shell vulnerability](https://www.ncsc.gov.uk/information/log4j-vulnerability-what-everyone-needs-to-know) is one of the more well-known [vulnerabilities in open source software](https://en.wikipedia.org/wiki/Log4Shell), and even though a patch was released there are undoubtedly still many devices that are vulnerable, even years after the vulnerability was disclosed. 

There was also the the XZ Utils backdoor [https://en.wikipedia.org/wiki/XZ_Utils_backdoor](https://en.wikipedia.org/wiki/XZ_Utils_backdoor), a backdoor that was injected into a popular Linux library. The backdoor was discovered before the update was put into production widely, but its discovery was largely thanks to chance and a particularly observant software engineer who noticed and investigated strange behavior from the utility in question. Had it gone into production, it would have given complete remote access to million of machines. In the case of the XZ Utils backdoor, the exploit was a direct result of some of the dynamics that can make open source software vulnerable: A malicious actor spent years gaining the trust of an overwhelmed, unpaid maintainer, who then agreed to give them maintainer access to the repository. That allowed the malicious actor to accept code that contained the backdoor, almost certainly both the malicious maintainer and the code author were sock puppet accounts. 

There are also security problems in closed-source software. 

### Legal Compliance

### Abandonware / technical debt

## Risks and challenges from contributing to open source software

## Risks and challenges from publishing and maintaining open source software

### Cyber Resilience Act (CRA) when publishing software

## Legislative risks related to open source software

## How to properly budget or allocate resources for OSPOs?

## Strategies for minimizing the risks and downsides from open source
