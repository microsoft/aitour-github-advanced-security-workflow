
# BRK422 - GitHub Advanced Security: Securing your workflow
If you will be delivering this session, consult the [session-delivery-resources](https://github.com/microsoft/aitour-github-advanced-security-workflow/tree/main/session-delivery-resources#readme) page for slides, demo scripts, and other resources.

## Session Description

GitHub Advanced Security features are built directly into the development workflow, making them easy to use and giving developers the ability to catch potential security issues as early in the software development lifecycle as possible.

Learn how to prevent common security issues from being merged into your codebase, how to find and fix vulnerabilities faster with AI, and how to keep your dependencies updated via GitHub Advanced Security.

## Learning Outcomes
- Learn how to enable Dependabot alerts and get notifications about vulnerable dependencies, including a link to the affected file in the project and information about a fixed version.
- See how to automatically update or generate a pull request to update vulnerable dependencies.
- Discover how to automatically update supported packages used by your repository on a schedule you configure.
- Learn how to enable Secret scanning and Push protection proactively prevents secret leaks by scanning code on commit and blocking a push if a secret is present.
- Find vulnerabilities before they are merged into the code base with automated CodeQL scans.
- Learn how to get suggested code fixes powered by AI in pull requests.


## Technology Used
- GitHub Advanced Security
   - Dependabot
   - Secret Scanning
   - CodeQL
   - Copilot Autofix
- GitHub Actions

## Additional Resources and Continued Learning

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Docs  | [Docs](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security) | About GitHub Advanced Security |
| Docs  | [Dependabot security updates Doc](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/about-dependabot-security-updates) | About Dependabot security updates |
| Docs  | [Copilot Autofix Doc](https://docs.github.com/en/code-security/code-scanning/managing-code-scanning-alerts/about-autofix-for-codeql-code-scanning#autofix-generation-process) | About Copilot Copilot Autofix for CodeQL code scanning |
| Certification  | [GitHub Advanced Security Certification Program](https://examregistration.github.com/) | Learn more about GitHub Certifications |

## Content Owners
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://developer.microsoft.com/en-us/advocates/media/profiles/joylynn-kirui.jpg" width="100px;" alt="Chris Testa-O'Neill
"/><br />
        <sub><b>Joylynn Kirui
</b></sub></a><br />
            <a href="[https://developer.microsoft.com/advocates/joylynn-kirui]" title="talk">📢</a> 
    </td>
</tr></table>
<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://developer.microsoft.com/en-us/advocates/media/profiles/Anthony-Bartolo.jpg" width="100px;" alt="Chris Testa-O'Neill
"/><br />
        <sub><b>Anthony Bartolo
</b></sub></a><br />
            <a href="[https://developer.microsoft.com/advocates/anthony-bartolo]" title="talk">📢</a> 
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI
Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at https://aka.ms/RAI. Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators.](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-metrics-built-in?tabs=warning)  You also have the ability to create and evaluate with [custom evaluators.](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators)

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK.](https://microsoft.github.io/promptflow/index.html) Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide.](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk) Once you execute an evaluation run, you can [visualize the results in Azure AI Studio.](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results)

