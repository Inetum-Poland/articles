# DevSecOps

## What is DevSecOps?

<!-- DevSecOps, which stands for development, security, and operations, is a approach that integrates security into all phases of the software development lifecycle. Organizations adopt this framework to reduce the risk of releasing code with security vulnerabilities. Through collaboration, automation, and clear processes, teams share responsibility for security, rather than leaving it to the end when issues can be much more difficult and costly to address. -->

In the realm of modern craft, there arose a practice known among the learned as DevSecOps, a union of three great disciplines: development, security, and operations. It was not unlike the forging of a mighty alliance, wherein each realm must contribute its strength, lest their endeavors fall prey to the shadows of vulnerability.

In days past, many would wait until the final hour, when the code was near release, before calling upon the wardens of security. Yet this path was fraught with peril, for to uncover weaknesses so late would often cost dear in time, gold, and effort. But the wisest of realms soon saw another way.

By weaving security into every phase of the craft—whether in the laying of the first line of code or the final shaping of the product—teams could safeguard their work from the outset. Through deep collaboration and the magic of automation, they crafted a system where all shared the burden of protection. Thus, no longer was security the task of the few, but of all who toiled together, forging a shield that would hold fast even in the face of the darkest threats.

In this way, DevSecOps was not merely a method, but a way of ensuring that no creation would leave the forges unguarded against the unseen dangers lurking in the shadows.

## DevOps vs DevSecOps

<!-- In traditional software development, projects are split into distinct phases for planning, design, development, integration, and testing, which happen sequentially over several months or even years. Although this approach is very methodical, many organizations have found it to be too slow, making it difficult to meet customers expectations for continuous product improvements. Additionally, security typically gets bolted on at the very end, which puts companies at risk of a breach.

To remain competitive, many companies have adopted a DevOps model that prioritizes delivery of smaller packets of high-quality code rather than feature-rich projects that take longer. In this framework, software development and operations teams collaborate to incorporate testing and integration throughout the process. Automation, standardized processes, and collaboration help teams move quickly without sacrificing quality.

DevSecOps is an enhancement to DevOps that builds security into all aspects of the process. The goal is to address security issues from the very start of the project. In this framework, not only does the entire team take responsibility for quality assurance and code integration but also security. In practice, this means teams discuss security implications during planning and begin testing for security issues in development environments, rather than waiting until the end. Another name for this approach is shift left security. -->


In the lands of traditional software craft, the crafting of great projects was long governed by the old ways, where the work was divided into phases—like the seasons of the year—each flowing one after the other. There would come a time for planning, then design, and only after would the labor of development begin, followed by the testing and binding of all parts into a whole. Yet, this process, while orderly, was as slow as the march of the seasons themselves. In an age where the winds of change blow swift and customers' desires are ever-shifting, such a pace no longer sufficed.

Worse still, the guardians of security were oft called upon at the very end, when the work was near complete, to cast their protections over the product. Alas, this lateness was fraught with danger, for vulnerabilities uncovered at such a time could unravel much of the work that had come before.

Thus, many of the great guilds of craft turned to a new way: the DevOps model. Here, rather than waiting for the long seasons to pass, the teams delivered smaller, yet finely crafted parcels of work—each one polished and ready—rather than undertaking vast projects that stretched on for years. In this way, the teams of development and operations joined forces, testing and refining their work as they went. By using the tools of automation and forging standardized processes, they moved with great speed, yet kept the quality of their craft intact.

But in time, the guilds realized there was a further step to be taken. They sought not just swiftness, but security woven into every step of their journey. And so was born DevSecOps, where security was not an afterthought but a companion to every stage of the craft. From the very first whispers of planning, security was present, and in the fires of development, it was tested and shaped alongside the code. The burden of protection no longer lay on the shoulders of a few, but on the entire fellowship of creators. This new way became known to some as ‘shift left security,' for it brought the guardians of protection to the forefront of the process, ensuring that no ill would befall their work from the very start of the journey to its end.

## Importance of DevSecOps

<!-- There are many methods that attackers use to gain access to an organizations data and assets, but a common tactic is to exploit software vulnerabilities. These types of breaches are costly, time consuming, and depending on the severity, damaging to a companys reputation. The DevSecOps framework reduces the risk of deploying software with misconfigurations and other vulnerabilities that bad actors can take advantage of. -->

In the ever-shifting shadows beyond the borders of an organization's walls, there lurk many foes, seeking to gain entry and plunder its most valuable treasures—its data and assets. Among the many dark arts these foes employ, one of the most common is the exploitation of weaknesses, hidden deep within the folds of the organization's own software. These vulnerabilities, if left unchecked, are like cracks in the foundation of a mighty fortress, and through them, adversaries can slip in unnoticed, wreaking havoc from within.

Such breaches can be devastating. They consume both time and treasure to mend, and in their wake, they leave scars upon a company's name, causing trust to wither among clients and allies alike.

But there is hope within the craft of DevSecOps. By following this path, the guilds of development, security, and operations stand together, ever watchful. The framework is like a vigilant sentry, reducing the risk of sending forth software riddled with flaws, misconfigurations, or vulnerabilities. Through constant vigilance and the weaving of security into every phase of creation, they close the gates through which bad actors might pass, fortifying their code so that it may stand strong against the onslaught of those who would seek to exploit it. Thus, the company stands firm, its reputation unshaken, its defenses prepared for the battles yet to come.

### Continuous integration

<!-- With continuous integration developers commit their code to a central repository multiple times a day. Then the code is automatically integrated and tested. This approach enables teams to catch integration issues and bugs early in the process rather than waiting until the end when there could be several issues that need to be resolved. -->

In the world of software craft, there once was a time when the labor of many artisans was brought together only at the final hour, when all the pieces were near completion. But it was often in those moments, at the very end, that flaws were revealed, and the seams of their work would unravel, leaving them with a tangle of issues too great to swiftly resolve.

But a new method arose, known as Continuous Integration, a practice where the builders of code did not wait for the end to unite their works. Instead, they would commit their efforts to a central repository many times throughout the day, like artisans returning to the hearth to meld their creations together piece by piece. Each time they did so, their work was automatically tested and integrated, ensuring that all parts fit together in harmony.

By catching integration issues and bugs early, long before the final forge was set aflame, this approach saved the guilds from the chaos of last-minute discoveries. Instead of waiting for a single moment, fraught with uncertainty, they ensured their work remained steady and true, addressing problems as they arose. Thus, they crafted their creations with foresight, and the path to completion became smoother and less perilous.

### Continuous delivery

<!-- Continuous delivery builds upon continuous integration to automate the process of moving code from the build environment to a staging environment. Once in staging, in addition to unit testing, the software is automatically tested to ensure the user interface is working, the code is successfully integrated, that APIs are reliable, and that the software can handle the expected traffic volumes. The goal of this approach is to consistently deliver production-ready code that provides value to customers. -->

Building upon the foundation of Continuous Integration, a further craft emerged, known as Continuous Delivery. Where the former ensured that code was swiftly integrated and tested, Continuous Delivery took this one step further, automating the journey from the builder's hands to a staging environment, where the true mettle of the code would be tested.

Once the code reached this staging ground, it did not rest. The system immediately set to work, not only with unit testing, but with a series of trials to ensure that all aspects of the creation were sound. The user interface was inspected to ensure it responded as intended, the seams of integration were examined for any weaknesses, and the APIs were tested to confirm they communicated faithfully between systems. The code was also tested under the weight of simulated traffic, to see if it could bear the burden of the many users it would one day serve.

Through this meticulous process, the guilds ensured that what emerged from staging was no half-finished creation, but code ready for the rigors of the real world. The aim of Continuous Delivery was simple but profound: to consistently deliver code that was not only complete, but of true value to those who would use it, ensuring that at any moment, the work could be sent to production, bringing swift and reliable benefits to all who depended on it.

### Continuous security

<!-- Building security into the entire software development lifecycle is a key component of DevSecOps. This includes threat modeling early in the process and automated security testing throughout the entire lifecycle, starting with developers own environments. By thoroughly testing the software for security issues early and frequently, organizations can efficiently deliver software with minimal issues. -->

In the crafting halls of DevSecOps, one of the most vital elements is the weaving of security into every step of the software's journey, from the first stroke of design to the final unveiling. No longer could security be treated as an afterthought, called upon only when the work was nearly complete. Instead, it became a core part of the process, guiding the work like an unseen but ever-present hand.

From the earliest stages, when the blueprints of the software were still taking shape, the guilds would engage in threat modeling, a process of foresight where they sought to uncover any potential dangers that might arise. They did not wait for the enemy to strike, but anticipated its moves, fortifying their code against unseen attacks before they could take root.

As the work progressed, security testing was woven into every stage of the craft. Automation played a key role, testing the code continuously, from the developers' own environments to the farthest reaches of the deployment pipeline. No phase was left unguarded; no section of code went untested.

Through this constant vigilance—testing early and testing often—the guilds were able to find and mend weaknesses swiftly. And so, they delivered their creations with confidence, knowing that each line of code was protected from the threats that lurked beyond. With DevSecOps, the road to production became one of fewer pitfalls and greater security, allowing organizations to deliver software swiftly and with minimal issues, their work as strong as the walls of a fortress built to endure the tests of time.

### Communication and collaboration

<!-- DevSecOps is highly dependent on individuals and teams working closely together. Continuous integration requires people to collaborate to address conflicts in code, and teams need to effectively communicate to unify around the same goals. -->

In the practice of DevSecOps, the strength of the craft does not lie solely in the tools or the processes but in the fellowship of those who undertake the journey together. It is a path that demands more than mere skill; it calls for deep collaboration and unity of purpose among individuals and teams.

When the artisans commit their work to the central repository in the practice of Continuous Integration, conflicts in code inevitably arise. But it is through collaboration—where minds come together, and voices are heard—that these challenges are resolved. Developers, security experts, and operations alike must work side by side, swiftly addressing these conflicts so the flow of progress is not hindered.

But beyond the technical work, there is a greater need—communication. Teams must speak openly and often, sharing their visions and aligning around the same goals. Without this shared understanding, the work would drift in many directions, and the efforts of one might undo the labors of another. In DevSecOps, every hand contributes to the same creation, and every voice is heard in the great chorus of the craft.

Only when individuals unite, not just in action but in purpose, can DevSecOps truly thrive. It is through this harmony of minds and hands that the work moves forward swiftly, safely, and in accordance with the goals they all share, bringing forth creations that stand the test of time.

## DevSecOps Practices (Shift security left)

### Planning and development

<!-- Introducing security early into development sprints not only helps reduce vulnerabilities later down the line, but it also saves time because its easier to address issues before code has been built and integrated. During planning and development, use threat modeling to identify and mitigate potential threats to the application. This will help you build security into the application right from the start. To uncover security issues before code is committed to the shared repository, implement automated checks, such as integrated development environment security plugs-ins, which give developers immediate feedback if theres a potential security risk in the code theyve written. During code review, have someone with security expertise provide recommendations for making improvements. -->

Introducing security early into the rhythm of development sprints is akin to fortifying the foundations of a great structure before the first stones are laid. By addressing vulnerabilities in the early stages, teams not only reduce the risk of future threats but also save valuable time, for it is far easier to mend potential flaws before the code has been built and woven into the greater tapestry of the project.

At the start of every sprint, during planning and development, threat modeling becomes a crucial tool, a map guiding the teams to uncover and mitigate potential dangers long before they can manifest. By identifying these threats early, security is no longer something that is added at the end, but something that is woven into the very fabric of the application from the outset.

To ensure no dangers slip through the cracks before the code is committed to the shared repository, automated checks are employed, acting as vigilant sentries. Integrated development environment (IDE) security plug-ins provide developers with immediate feedback, warning them if their code harbors a potential risk. These automated checks catch flaws early, empowering developers to address them before they can take root.

As the code continues its journey, passing from one set of hands to the next, the craft is further refined during the code review. Here, someone with the wisdom of security steps forward, offering their insight and making recommendations to bolster the work. This expertise ensures that, by the time the code is ready to move on, it is fortified against threats, and the path forward is more secure.

By embedding security into every stage, from the first lines of code to the final review, the team creates software that is not only functional and valuable but strong, resilient, and prepared for whatever challenges lie ahead.

### Code commit

<!-- One of the keys to a successful DevSecOps process is continuous integration. Developers typically commit their code to a central repository several times a day to ensure integration issues are caught early. Its important to add automated security checks to this phase. This can include scanning third-party libraries and dependencies, unit testing, and static application security testing. Its also important to deploy role-based access controls to protect your continuous integration and continuous delivery infrastructure from attackers seeking to run malicious code or steal credentials. -->


A cornerstone of the DevSecOps process lies in the practice of continuous integration, a discipline that ensures code is not simply created in isolation but is constantly woven into the central repository, allowing teams to catch issues before they can fester. Developers, like diligent artisans, commit their code several times a day, ensuring that each piece of work seamlessly fits into the greater whole. This frequent integration allows potential conflicts or errors to be discovered early, long before they can threaten the stability of the project.

However, to truly safeguard the craft, it is vital to introduce security into this phase. Automated security checks must stand guard alongside the integration process. These include scanning third-party libraries and dependencies—those external pieces of code that, while useful, may harbor unseen vulnerabilities. Unit testing ensures the smallest parts of the code function as they should, while static application security testing (SAST) reviews the code for weaknesses, searching for hidden threats that might otherwise go unnoticed.

But safeguarding the code itself is not enough. The continuous integration (CI) and continuous delivery (CD) infrastructure, which carries this code from creation to deployment, must also be protected. Role-based access controls (RBAC) play a crucial role in this defense, limiting access to the system based on the specific roles of individuals. By ensuring that only those with the right permissions can interact with the CI/CD infrastructure, teams protect it from attackers who might seek to run malicious code or steal credentials.

In this way, the continuous integration process becomes not only a means to unite code swiftly and efficiently but also a stronghold against external threats. Security is built into every layer, from the automated checks that scan the code to the protections guarding the very systems that bring the work to life.

### Building and testing

<!-- Running automated security scripts on the test environment helps uncover potential issues that werent previously detected. Some of the security tests you can run during this phase include dynamic application security testing, infrastructure scanning, container scanning, cloud configuration validation, and security acceptance testing. -->

In the realm of DevSecOps, where vigilance is paramount, the test environment serves as a proving ground for code before it ventures into production. Here, automated security scripts take up the role of sentinels, seeking out potential threats that may have slipped past earlier defenses. By running these tests in a controlled environment, teams can uncover hidden vulnerabilities and ensure their work remains strong and secure.

Among the many tests that can be employed during this phase is Dynamic Application Security Testing (DAST), which simulates real-world attacks against the running application. Unlike static tests, DAST operates while the application is live, identifying vulnerabilities such as cross-site scripting, SQL injection, and other dangerous flaws.

Infrastructure scanning follows, casting its gaze across the entire architecture, from servers to networks, searching for weaknesses in the foundational layers that might allow an attacker entry. For those employing containers as part of their deployment strategy, container scanning ensures that these lightweight units of software do not harbor vulnerabilities in their dependencies or configurations, fortifying them before they are deployed.

In the age of the cloud, where infrastructure is often abstracted and spread across vast digital realms, cloud configuration validation becomes crucial. By checking the configurations of cloud resources, teams can ensure that no misconfigurations—such as excessive permissions or insecure access points—expose their environments to unnecessary risk.

Lastly, security acceptance testing ensures that all necessary security requirements are met. This step serves as the final safeguard, confirming that the code and infrastructure are not only functional but fortified against known threats.

By running these automated security scripts in the test environment, organizations create a final layer of defense, ensuring that the code is ready to face the challenges of the real world. With each vulnerability caught and addressed before deployment, the risks are minimized, and the path forward is made more secure.

### Production

<!-- Once the application is deployed to production, some organizations engage in penetration testing to try to find weaknesses in the live environment. In penetration testing, people adopt the mindset of an attacker and search for ways to breach the application. -->

Once the application has been deployed to production and stands in the real world, some organizations take a proactive step to uncover any remaining weaknesses by engaging in penetration testing. This practice is more than just another test—it is a deliberate attempt to breach the application as an attacker might, with real-world tactics and determination.

In penetration testing, skilled individuals, often referred to as ethical hackers, adopt the mindset of a potential adversary. They probe the application for weaknesses, using the same strategies and tools a malicious actor might employ. These tests can range from exploiting known vulnerabilities in third-party components to crafting more sophisticated attacks aimed at bypassing the application's defenses.

The goal is simple: to expose any weaknesses that might have slipped through the earlier layers of security testing, those that could potentially be exploited in the wild. By simulating real-world attack scenarios, penetration testing reveals how the application holds up under direct assault, whether it's vulnerable to unauthorized access, data breaches, or other forms of compromise.

This phase is crucial for understanding not just theoretical vulnerabilities but how the system behaves in a live environment, where the stakes are highest. Penetration testing provides organizations with invaluable insights into the robustness of their defenses, allowing them to patch any remaining weaknesses before an actual attacker can exploit them. Thus, it becomes the final line of preparation, ensuring that the application is truly ready to stand firm against threats in the production environment.

### Operation

<!-- Even the best DevSecOps process wont catch everything, so its critical to continuously monitor applications for vulnerabilities and threats. Analytics data can help you evaluate if your security posture is improving and highlight areas for optimization. -->

Even with the most robust DevSecOps process, no system is entirely impervious to evolving threats. This is why continuous monitoring of applications becomes essential once they are deployed. As applications interact with the real world, new vulnerabilities and unforeseen threats can emerge. By maintaining constant vigilance, organizations can quickly detect, respond to, and mitigate these risks before they cause significant harm.

Monitoring tools scour the live environment for signs of irregularities, scanning for vulnerabilities, unauthorized access attempts, or other suspicious activities that might signal a breach or weakness. These tools provide real-time insights, alerting teams to potential issues the moment they arise, ensuring that no threat goes unnoticed for long.

To further strengthen this defense, analytics data plays a key role. By analyzing patterns and trends in security events, teams can evaluate the effectiveness of their security posture. This data offers valuable insights into how well current defenses are performing, allowing organizations to track whether they are improving over time or if new vulnerabilities are emerging. It also highlights areas that may require optimization, guiding future efforts in reinforcing the system.

In the world of security, the battle is never truly over. Even after an application is deployed and tested, constant monitoring and analysis ensure that defenses stay strong and evolve in step with the threats. By combining real-time monitoring with analytics, organizations can not only detect vulnerabilities but also continuously refine their security approach, ensuring that they stay one step ahead of potential attackers.

## Implementing DevSecOps and automating security practices

We bid you to consider these tools as you embark upon the journey of DevSecOps automation within your organization. Some are like fruit hanging low upon the bough, easily gathered and swiftly put to use, while others may lie deeper within the forest, requiring more effort to attain. Yet, though the path to them may be more difficult, the rewards they yield are well worth the quest.

### Trivvy

[Trivy](https://github.com/aquasecurity/trivy) has risen to prominence as a trusted sentinel among open-source security scanners, celebrated for its reliability, swiftness, and simplicity. It offers a far-reaching array of security checks, making it a vital companion for those seeking to fortify their DevSecOps practices. For teams looking to secure their realms of code and infrastructure, Trivy stands as a steadfast tool, ever vigilant and ready to ensure the safety of their creations.

Targets (what Trivy can scan):
- Container Image
- Filesystem
- Git Repository (remote)
- Virtual Machine Image
- Kubernetes
- AWS

Scanners (what Trivy can find there):
- OS packages and software dependencies in use (SBOM)
- Known vulnerabilities (CVEs)
- IaC issues and misconfigurations
- Sensitive information and secrets
- Software licenses

### Trufflehog

<!-- [TruffleHog](https://github.com/trufflesecurity/trufflehog)™ is a secrets scanning tool that digs deep into your code repositories to find secrets, passwords, and sensitive keys.

How TruffleHog works:
- Detect: Scan the version history of all platforms for hidden secrets. TruffleHog scans beyond code repositories to identify secrets hidden in comments, Docker images, and more.
- Analyze: TruffleHog Analyze automatically identifies the resources and permissions associated with API key and other secrets without requiring access to a providers UI.
- Prevent: Use pre-commit and pre-receive hooks so that developers can prevent leaked keys in the first place. Automatically run security scans before commits, and prevent accidental inclusion of sensitive data.
- Remediate: TruffleHog constantly tracks the status of different key types to verify their remediation. You can set up alert reminders on your preferred platform with links to guides on how to rotate and secure keys effectively.

Why TruffleHog?
- Comprehensive multi-branch analysis: By scanning all branches, not just the main or primary branch, TruffleHog ensures a consistent level of security across your entire project. This is particularly useful for larger projects with multiple branches being worked on concurrently.
- Credential verification: For every potential credential that is detected, we've painstakingly implemented programmatic verification using it's protocol or API. This verification removes false positives.
- Open-source community: Open-source software is transparent and available for inspection. Many developers volunteer their time to audit and improve it. This community verifies and checks each others work, so theres never a need to blindly trust one developer. -->

In the realm of software, where secrets lie hidden in the deep recesses of code repositories, there is a tool known as [TruffleHog](https://github.com/trufflesecurity/trufflehog), a masterful seeker of concealed passwords and keys. Like a skilled ranger, TruffleHog ventures where few dare to tread, unearthing the hidden secrets that, if left unchecked, could spell doom for the unwary.

How TruffleHog Wields Its Power:
- Detect: TruffleHog scours the history of all platforms, much like a wise lorekeeper sifting through ancient scrolls, seeking out long-forgotten secrets. Yet it looks not only in the obvious places but also in the whispers of comments, the hidden folds of Docker images, and other obscure corners.
- Analyze: With the keen eye of a strategist, TruffleHog Analyze reveals the true nature of the secrets it uncovers, discerning what resources and permissions are tied to API keys and other precious tokens. Remarkably, it achieves this without ever needing to peer into the provider's vault.
- Prevent: To stop the ill-fated inclusion of secrets from the very beginning, TruffleHog sets traps at key points, using pre-commit and pre-receive hooks. These safeguards ensure that no sensitive data is unintentionally leaked before it ever leaves the developer's hand.
- Remediate: Ever vigilant, TruffleHog continues to track the fate of discovered keys and secrets. It verifies that remediation is complete, sending reminders on preferred platforms and providing the wisdom to guide users on how to properly rotate and secure the keys that were once at risk.

Why TruffleHog Is a Worthy Ally:
- Comprehensive Multi-Branch Analysis: TruffleHog does not simply guard the main road but patrols every path. It scans all branches, not just the primary one, ensuring the same level of vigilance across the entire project. This is especially valuable in larger domains where many branches are being worked on in tandem.
- Credential Verification: For each secret it uncovers, TruffleHog employs programmatic verification, testing each credential using its own protocol or API. This removes the false trails, ensuring that only real threats are brought to light.
- Open-Source Fellowship: As with any great alliance, TruffleHog thrives through the support of an open-source community. Many dedicated hands join together to audit and improve the tool, ensuring that no single voice carries undue weight. The community checks and balances each other's work, so that trust is shared among all.

### Snyk

<!-- [Snyk](https://github.com/snyk/cli) is a developer security platform that enables application and cloud developers to secure their whole application — finding and fixing vulnerabilities from their first lines of code to their running cloud.

Snyk scans multiple content types for security issues:
- Snyk Open Source: Find and automatically fix open-source vulnerabilities
- Snyk Code: Find and fix vulnerabilities in your application code in real time
- Snyk Container: Find and fix vulnerabilities in container images and Kubernetes applications
- Snyk Infrastructure as Code: Find and fix insecure configurations in Terraform and Kubernetes code -->
-
In the wide lands of modern software craft, where both applications and cloud realms are wrought by skilled developers, there exists a powerful tool known as [Snyk](https://github.com/snyk/cli). This platform, much like a vigilant sentinel, guards the entirety of an application's journey—from the very first lines of code to its deployment in the vast expanse of the cloud. Through its guidance, developers may discover and mend vulnerabilities before they are ever loosed upon the world.

The Powers of Snyk:
- Snyk Open Source: With the wisdom of the ancients, Snyk scours open-source libraries and dependencies, seeking out vulnerabilities hidden within their folds. And when such flaws are found, it does not merely warn the developer but offers a swift means to mend them, restoring the strength of the code.
- Snyk Code: As code is written, Snyk watches in real-time, finding and fixing vulnerabilities within the very heart of the application. It is like a companion at the developer's side, ever watchful and ready to lend its aid as the work is crafted.
- Snyk Container: In the realms of containers and Kubernetes, where applications are housed, Snyk's gaze does not falter. It delves into container images, finding and repairing vulnerabilities that could otherwise bring harm to these vital vessels.
- Snyk Infrastructure as Code: With great foresight, Snyk peers into the blueprints of infrastructure itself, examining the configurations of Terraform and Kubernetes code. Should it find any insecurity in the very foundation, it offers swift guidance on how to rectify these flaws, ensuring that the structure remains strong and secure.

### Pre-commit

<!-- [Pre-commit](https://github.com/pre-commit/pre-commit) is a framework for managing and maintaining multi-language pre-commit hooks.

Git hook scripts are useful for identifying simple issues before submission to code review. We run our hooks on every commit to automatically point out issues in code such as missing semicolons, trailing whitespace, and debug statements. By pointing these issues out before code review, this allows a code reviewer to focus on the architecture of a change while not wasting time with trivial style nitpicks.

As we created more libraries and projects we recognized that sharing our pre-commit hooks across projects is painful. We copied and pasted unwieldy bash scripts from project to project and had to manually change the hooks to work for different project structures.

We believe that you should always use the best industry standard linters. Some of the best linters are written in languages that you do not use in your project or have installed on your machine. For example scss-lint is a linter for SCSS written in Ruby. If youre writing a project in node you should be able to use scss-lint as a pre-commit hook without adding a Gemfile to your project or understanding how to get scss-lint installed.

It is a multi-language package manager for pre-commit hooks. You specify a list of hooks you want and pre-commit manages the installation and execution of any hook written in any language before every commit. pre-commit is specifically designed to not require root access. If one of your developers doesnt have node installed but modifies a JavaScript file, pre-commit automatically handles downloading and building node to run eslint without root. -->

In the vast lands of software development, where many languages and tools converge, there exists a framework known as [Pre-commit](https://github.com/pre-commit/pre-commit) — a powerful system for managing and maintaining pre-commit hooks across many tongues of code. Like a watchful steward, Pre-commit ensures that no errant detail is left unchecked before the code is sent forth for review.

In the world of Git, hook scripts act as sentinels at the gate, catching simple errors before they reach the eyes of a reviewer. Whenever a developer commits their work, these hooks spring into action, pointing out issues such as missing semicolons, trailing whitespace, or forgotten debug statements. By addressing these small matters early, Pre-commit allows the reviewer to focus on the grand architecture of the changes, rather than wasting time on trivial style errors.

Yet as our libraries and projects grew in number, we found the task of sharing our pre-commit hooks between them to be burdensome. We were forced to copy and paste cumbersome bash scripts from one project to another, manually adjusting them for each new structure. The effort was like carrying a heavy burden across the lands, with each step weighed down by inefficiency.

We believe that the best tools should always be at your service, even if they hail from distant lands. Some of the finest linters are written in languages that may not even touch your own project. Take scss-lint, a linter for SCSS written in the language of Ruby—if you were crafting your project in Node, why should you be forced to burden your work with Ruby's Gemfile or wrestle with its arcane installation?

Pre-commit frees you from such toil. It is a package manager for pre-commit hooks across many languages, both familiar and foreign. You need only specify the hooks you desire, and Pre-commit will manage the installation and execution of any hook, no matter the language it was written in. It requires no root access, and if one of your comrades lacks the proper tools—such as Node for JavaScript—Pre-commit will summon the necessary tools, downloading and building them without the need for elevated privileges.

### Wazuh

<!-- [Wazuh](https://github.com/wazuh/wazuh) is a free and open source platform used for threat prevention, detection, and response. It is capable of protecting workloads across on-premises, virtualized, containerized, and cloud-based environments.

Wazuh solution consists of an endpoint security agent, deployed to the monitored systems, and a management server, which collects and analyzes data gathered by the agents. Besides, Wazuh has been fully integrated with the Elastic Stack, providing a search engine and data visualization tool that allows users to navigate through their security alerts.

Wazuh delivers robust security monitoring and protection for your IT assets using its Security Information and Event Management (SIEM) and Extended Detection and Response (XDR) capabilities. Wazuh use cases are designed to safeguard your digital assets and enhance your organization's cybersecurity posture. -->

In the ever-shifting landscapes of the digital realms, where threats lurk unseen and dangers arise without warning, there is a powerful ally known as [Wazuh](https://github.com/wazuh/wazuh). Free and open to all, Wazuh stands as a vigilant guardian, skilled in the arts of threat prevention, detection, and response. It is a protector capable of defending the realms of on-premises fortresses, virtualized strongholds, containerized ships, and vast cloud kingdoms alike.

The strength of Wazuh lies in two parts: its endpoint security agents, which are deployed like watchful sentinels to the systems they protect, and its management server, a wise and ever-alert overseer. The agents gather knowledge and data from the systems they monitor, and the management server collects, analyzes, and interprets this information, ever vigilant for signs of danger.

But Wazuh's might does not end there. It has been fully integrated with the famed Elastic Stack, a powerful search engine and tool for visualizing data. Through this integration, users may navigate through their security alerts with ease, as if wielding a crystal-clear map of their kingdom, revealing all the perils that threaten their borders.

Wazuh brings robust security to all IT assets, combining the powers of Security Information and Event Management (SIEM) and Extended Detection and Response (XDR). It watches over the domain with unblinking eyes, scanning for threats and delivering swift responses to protect what is most valuable. The use cases of Wazuh are many and varied, all designed to safeguard your digital treasures and strengthen the walls of your cybersecurity posture.

Use-cases:
- Configuration Assessment
- Malware Detection
- File Integrity Monitoring
- Threat Hunting
- Log Data Analysis
- Vulnerability Detection
- Incident Response
- Regulatory Compliance
- IT Hygiene
- Containers Security
- Posture Management
- Workload Protection

## DevOps and DevSecOps Integration

<!-- It should be a natural process, the integration that is organic and seamless. It is not a one-time thing, but a continuous process. Sometimes a culture shift is required, but it is a natural one (from the DevOps point of view). And as everything we build is tailored to our needs, the process and tooling should be adequately chosen to fit the needs of the organization. -->

The integration should be as natural as the turning of the seasons, an organic and seamless process that unfolds with time. It is not a single task to be completed and forgotten, but a continuous journey, like the flowing of a river that ever shapes the land it touches. Though at times it may call for a shift in the very culture of the organization, such change is not forced, but arises naturally, like the slow awakening of spring after the long winter—an inevitable transformation in the pursuit of a more harmonious craft.

And as in all great works of creation, what we forge must be shaped by the needs of our people and our lands. The processes we follow and the tools we wield must be chosen with wisdom, fitting the unique contours of our organization, much like a sword is balanced to the hand of the warrior who bears it. Only then can the integration thrive, as both DevOps and DevSecOps become not separate disciplines, but part of the same living tapestry, woven together in purpose and vision.
