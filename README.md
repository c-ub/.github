# Creating a default community health file

You can add default community health files to a public repository called .github, in the root of the repository or in the docs or .github folders.

GitHub will use and display default files for any repository owned by the account that does not have its own file of that type in any of the following places:

+ the root of the repository
+ the `.github` folder
+ the `docs` folder

For example, anyone who creates an issue or pull request in a repository that does not have its own CONTRIBUTING file will see a link to the default CONTRIBUTING file. If a repository has any files in its own `.github/ISSUE_TEMPLATE` folder, including issue templates or a *config.yml* file, none of the contents of the default `.github/ISSUE_TEMPLATE` folder will be used.

Default files are not included in clones, packages, or downloads of individual repositories because they are stored only in the `.github` repository.

## Supported file types

You can create defaults in your organization or personal account for the following community health files:

| Community health file                             | Description                                                  |
| :------------------------------------------------ | :----------------------------------------------------------- |
| *CODE_OF_CONDUCT.md*                              | A CODE_OF_CONDUCT file defines standards for how to engage in a community. For more information, see "[Adding a code of conduct to your project](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)." |
| *CONTRIBUTING.md*                                 | A CONTRIBUTING file communicates how people should contribute to your project. For more information, see "[Setting guidelines for repository contributors](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)." |
| Discussion category forms                         | Discussion category forms customize the templates that are available for community members to use when they open new discussions in your repository. For more information, see "[Creating discussion category forms](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms)." |
| *FUNDING.yml*                                     | A FUNDING file displays a sponsor button in your repository to increase the visibility of funding options for your open source project. For more information, see "[Displaying a sponsor button in your repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/displaying-a-sponsor-button-in-your-repository)." |
| *GOVERNANCE.md*                                   | A GOVERNANCE file lets people know about how your project is governed. For example, it might discuss project roles and how decisions are made. |
| Issue and pull request templates and *config.yml* | Issue and pull request templates customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository. For more information, see "[About issue and pull request templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)." |
| *SECURITY.md*                                     | A SECURITY file gives instructions for how to report a security vulnerability in your project. For more information, see "[Adding a security policy to your repository](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)." |
| *SUPPORT.md*                                      | A SUPPORT file lets people know about ways to get help with your project. For more information, see "[Adding support resources to your project](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-support-resources-to-your-project)." |

You cannot create a default license file. License files must be added to individual repositories so the file will be included when a project is cloned, packaged, or downloaded.

## Creating a repository for default files

1. In the upper-right corner of any page, use the drop-down menu, and select **New repository**.

   ![asd](http://sm.nsddd.top/sm202306031951593.png)

2. Use the **Owner** drop-down menu, and select the organization or personal account you want to create default files for.![asdfaf](http://sm.nsddd.top/sm202306031951715.png)

3. In the "Repository name" field, type **.github**.

4. Optionally, in the "Description" field, type a description.

5. Make sure the repository status is set to **Public**. A repository for default files cannot be private.

6. Select **Initialize this repository with a README**.

7. Click **Create repository**.

8. In the repository, create one of the supported community health files. Issue templates and their configuration file must be in a folder called `.github/ISSUE_TEMPLATE`. All other supported files may be in the root of the repository, the `.github` folder, or the `docs` folder. For more information, see "[Creating new files](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)."

## Product Feedback

| **Feedback Category**                                        | **About the Product**                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 👍 [Accessibility](https://github.com/orgs/community/discussions/categories/accessibility) | [About Accessibility](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-personal-account-settings/managing-accessibility-settings#about-accessibility-settings) |
| 🚢 [Actions](https://github.com/orgs/community/discussions/categories/actions) | [GitHub Actions](https://github.com/features/actions)        |
| 🔁 [API and Webhooks](https://github.com/orgs/community/discussions/categories/api-and-webhooks) | [GitHub API](https://docs.github.com/en/rest) and [GitHub Webhooks](https://docs.github.com/en/developers/webhooks-and-events/webhooks/about-webhook) |
| 🔎 [Code Search & Navigation](https://github.com/orgs/community/discussions/categories/code-search-and-navigation) | [Code Search & Navigation](https://cs.github.com/about)      |
| 💻 [Codespaces](https://github.com/orgs/community/discussions/categories/codespaces) | [GitHub Codespaces](https://github.com/features/codespaces)  |
| 👩‍✈️ [Copilot](https://github.com/orgs/community/discussions/categories/copilot) | [GitHub Copilot](https://copilot.github.com/) (Technical Preview) |
| 🤖 [Code Security](https://github.com/orgs/community/discussions/categories/code-security) | [GitHub Code Security](https://github.com/features/security) |
| 🗣️ [Discussions](https://github.com/orgs/community/discussions/categories/discussions) | [GitHub Discussions](https://docs.github.com/en/discussions) |
| 🌐 [Feed](https://github.com/orgs/community/discussions/categories/feed) | [GitHub Feed](https://github.blog/2022-03-22-improving-your-github-feed/) |
| 🎒 [GitHub Education](https://github.com/orgs/community/discussions/categories/github-education) | [GitHub Education](https://education.github.com/)            |
| 🐙 [Issues](https://github.com/orgs/community/discussions/categories/issues) | [GitHub Issues](https://github.com/features/issues)          |
| ⭐ [Lists](https://github.com/orgs/community/discussions/categories/lists) | [GitHub Lists](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars#organizing-starred-repositories-with-lists) (Public Beta) |
| 📱 [Mobile](https://github.com/orgs/community/discussions/categories/mobile) | [GitHub Mobile](https://github.com/mobile)                   |
| 📦 [Packages](https://github.com/orgs/community/discussions/categories/packages) | [GitHub Packages](https://github.com/features/packages)      |
| 🗒️ [Pages](https://github.com/orgs/community/discussions/categories/pages) | [GitHub Pages](https://docs.github.com/en/pages)             |
| 🖼️ [Profile](https://github.com/orgs/community/discussions/categories/profile) | [GitHub Profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile) |
| ✔️ [Pull Requests](https://github.com/orgs/community/discussions/categories/pull-requests) | [GitHub Pull Requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) |
| 🗳️ [Repositories](https://github.com/orgs/community/discussions/categories/repositories?type=source) | [GitHub Repositories](https://docs.github.com/en/repositories) |
| 💖 [Sponsors](https://github.com/orgs/community/discussions/categories/sponsors) | [GitHub Sponsors](https://github.com/sponsors)               |
| ![:octocat:](https://github.githubassets.com/images/icons/emoji/octocat.png) [General Feedback](https://github.com/orgs/community/discussions/categories/general) | [GitHub Docs](https://docs.github.com/en)                    |

These discussions are where you can share suggestions for how the products should be improved and discuss those improvements with the community, including members of the GitHub product team. Check out [Making suggestions](https://github.com/community/community#making-suggestions) to learn how to provide feedback.


## Link

+ https://github.com/community/community
