
This document outlines the responsibilities and processes regarding the **Emerson DeltaV GitHub** org account.

## Contributing Guidelines

For Emerson employees, more details on using GitHub can be found [here](https://dev.azure.com/EmersonPSS/PSS/_wiki/wikis/PSS.wiki/1998/DeltaV-Github), in Azure DevOps.


---

## Responsibilities

### Contributors

Contributors play a crucial role in maintaining the project. The contributor role, as of this moment, is currently limited to Emerson employees. We’ll let you know once it is open to developers outside Emerson.

Contributors **must**:

- Follow the Emerson Code of Conduct  
- Ensure all submitted content meets security and compliance requirements  
- Execute required validation checks (e.g., Coverity) prior to committing  

---

## Sensitive Data and Security Requirements

Contributors **must not** commit, upload, or disclose sensitive or confidential information in any repository.

This includes, but is not limited to:

- Credentials (passwords, API keys, tokens, certificates)  
- Personal data (email addresses, phone numbers, identifiers)  
- Internal system details (IP addresses, hostnames, internal URLs, connection strings)  
- Customer or project data  
- Emerson confidential information  

---

### Required Practices

Contributors **must**:

- Use placeholders such as `<username>`, `<server_ip>`, `<REDACTED>`  
- Sanitize logs, outputs, and examples before committing  
- Sanitize or redact all screenshots and visual content  
- Supply credentials via environment variables or approved configuration methods  
- Ensure any initial credentials are temporary and changed on first use  

---

### Screenshots and Visual Content

Screenshots and images **must not** expose sensitive or environment-specific information.

All visual content **must be reviewed and redacted** prior to inclusion.

---

### If Sensitive Data Is Exposed

Contributors **must** immediately notify:  
opensource.deltav@emerson.com

---

## Repository Creation

Contributors need to follow these steps when requesting a new repository:

1. **Answer our Emerson internal document [licensing-questionnaire](https://dev.azure.com/EmersonPSS/PSS/_wiki/wikis/PSS.wiki/2004/Licensing-Questionnaire).** This ensures that the owners and legal team understand which license is appropriate for the new repo.
2. **Send an email** to [opensource.deltav@emerson.com](mailto:opensource.deltav@emerson.com) with the subject **[DeltaV GitHub] Request New Repo** and include the following information:
   * Proposed Name
   * Product
   * Description
   * GitIgnore to be used (refer to this link: [GitHub gitignore options](https://github.com/github/gitignore))
   * Proposed License (also, attach the answered licensing questionnaire)
3. **Update the readme file** to explain the purpose of the repo, what to expect, and how to run the app locally. Consider the following when creating the main readme file for your repository:
   * Descriptive information
   * Purpose of the repo
   * Instructions for running the app locally (including prerequisites and steps)
   * Optionally, include pipeline badges (e.g., build badge, SonarQube badge, NuGet version badge) if applicable.

---

## Full Policy

For detailed requirements, examples, and handling procedures, refer to:
[Sensitive Data Handling Standard](./sensitive-data-standard.md)
