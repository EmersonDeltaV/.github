For Emerson employees, more details on using GitHub can be found [here](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github), in Azure DevOps.

This document outlines the responsibilities and processes regarding the **Emerson DeltaV GitHub** org account.

# Responsibilities

## Contributors
Contributors play a crucial role in maintaining the project. The contributor role, as of this moment, is currently limited to Emerson employees. We’ll let you know once it is open to developers outside Emerson.

Here are their responsibilities:

   * **Code of Conduct:** For Emerson employees, the code of conduct can be found [here](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github?path=/code-of-conduct.md&_a=preview) in Azure DevOps.
   * **Avoid Sensitive Information:** Never commit sensitive information. If you accidentally do so, promptly notify the owners via email at [opensource.deltav@emerson.com](mailto:opensource.deltav@emerson.com?subject=Concern).
   * **Coverity Check:** Contributors should execute the Coverity check before committing any changes to any repository.

## Owners

For owner responsibilities, please read our Emerson internal document [here](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github?path=/how-to-contribute.md&_a=preview&anchor=owners). 

# Processes

## Requesting a new Repository

### Contributor Responsibilities
Contributors need to follow these steps when requesting a new repository:

1. **Answer our Emerson internal document [licensing-questionnaire](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github?path=/licensing-questionnaire.md&_a=preview).** This ensures that the owners and legal team understand which license is appropriate for the new repo.
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

### Owner Responsibilities

When a request to create a new repository is received, please follow our Emerson internal document [here](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github?path=/how-to-contribute.md&_a=preview&anchor=owner-responsibilities).

## Mitigating Committed Sensitive Data

It is the responsibility of all contributors to avoid committing any sensitive data. However, if sensitive data is accidentally committed, contributors must send an email to [opensource.deltav@emerson.com](mailto:opensource.deltav@emerson.com?subject=Concern) as soon as possible.

For owners, please read the instruction from [this](https://dev.azure.com/EmersonPSS/PSS/_git/Amber_Github?path=/how-to-contribute.md&_a=preview&anchor=mitigating-committed-sensitive-data) section of our Emerson internal document.

# Feedback

Any concerns in mind or if you want to share any suggestions, don't hesitate to contact us by sending an email to [opensource.deltav@emerson.com](mailto:opensource.deltav@emerson.com?subject=Feedback)
