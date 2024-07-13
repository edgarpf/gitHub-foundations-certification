# GitHub Foundations Certification

* To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.
* You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).
* You can make an unordered list by preceding one or more lines of text with -, *, or +.
* To order your list, precede each line with a number.
* You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.
* Use ** ** or __ __ to rendered a line as bold in a Markdown.
* Anyone with admin permissions to a repository can make the repository a template.
* A Codespace's lifecycle begins when you create it and ends when you delete it. You can disconnect and reconnect to an active Codespace without affecting its running processes, and you can stop and restart a Codespace without losing any changes you've made to your project. Hence, the Codespace lifecycle can be broadly categorized into these four stages:
  1. Creating a Codespace
  2. Rebuilding a Codespace
  3. Closing or stopping a Codespace
  4. Deleting a Codespace
* The primary states for a file in a Git repository are:
  1. **Untracked**: An initial state of a file when it isn't yet part of the Git repository. Git is unaware of its existence.
  2. **Tracked**: A tracked file is one that Git is actively monitoring. It can be in one of the following substates:
     1. **Unmodified**: The file is tracked, but it hasn't been modified since the last commit.
     2. **Modified**: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.
     3. **Staged**: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.
     4. **Committed**: The file is in the repository's database. It represents the latest committed version of the file.
* You can use a saved reply to respond to an issue or pull request.
Saved replies allow you to create a reusable response to issues and pull requests. Saved replies are tied to your personal account. Once they're created, you'll be able to use them across repositories and organizations. You can create a maximum of 100 saved replies. If you've reached the maximum limit, you can delete saved replies that you no longer use or edit existing saved replies. You can also use the GitHub-provided "Duplicate issue" saved reply to mark an issue as a duplicate and track it with a similar issue.
* People with triage permission to a repository can create an issue from a discussion. When you create an issue from a discussion, the contents of the discussion post will be automatically included in the issue body, and any labels will be retained. Creating an issue from a discussion does not convert the discussion to an issue or delete the existing discussion.
* If you create a wiki in a private repository, only people with access to the repository can access the wiki.
* You can change name, VM, IDE and shell of a codespace.
* The github.dev editor opens instantly with a key-press and allows users to start editing code right away, without having to wait for additional configuration or installation. This makes it more convenient for quick edits or tasks compared to GitHub Codespaces.
* Workflows are defined in the **.github/workflows** directory in yaml files.
* To search for issues and pull requests in all repositories owned by a certain organization, you can use the "org" qualifier. To search for issues and pull requests in a specific repository, you can use the "repo" qualifier.
* When the CODEOWNERS file exceeds the size limit of 3 MB, GitHub won't load the file, and the code owner information won't be displayed. To address this issue, Peter should optimize the CODEOWNERS file size by consolidating multiple entries into a single entry using wildcard patterns
* Git is an example of a distributed version control system (DVCS). In DVCS, each user has a complete copy of the repository, enabling decentralized and flexible collaboration.
* To give people instructions for reporting security vulnerabilities in your project, you can add a SECURITY.md file to your repository's root, docs, or .github folder. When someone creates an issue in your repository, they will see a link to your project's security policy.
* Users can access all the repositories and topics they have starred on GitHub by visiting their stars page at https://github.com/stars. This page allows users to search, sort, and filter their starred content.
* Insights for Projects on GitHub allows users with write or admin access to a project to view, create, and customize charts based on the project's data.
* You can use the involves qualifier to find issues that in some way involve a certain user. The involves qualifier is a logical OR between the author, assignee, mentions, and commenter qualifiers for a single user.
* Use the git revert <SHA> command to undo the mistaken commit.
* If you create a new repository under your account in the future, do not reuse the original name of the renamed repository. If you do, redirects to the renamed repository will no longer work.
* If a repository contains more than one README file, then the file shown is chosen from locations in the following order: the .github directory, then the repository's root directory, and finally the docs directory.
* Peter should name his new public repository on GitHub as "username.github.io," where "username" is his actual GitHub username or organization name. If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.
* Users with write access to a repository can assign issues and pull requests.
* A repository admin can view insights for a repository in the "Insights" tab, located at the top of the repository's page on GitHub.
* GitHub maintains the visibility of topic names as public, regardless of whether they are created within private repositories.
* GitHub slash commands are shortcuts or commands that enable users to perform various actions directly from the comment box or issue description by using a forward slash ("/") followed by a keyword or action
* External collaborators cannot be team maintainers.
* 2FA -> SMS, Authentication App, Security Key and GitHub Mobile.
* Label
  * <img width="627" alt="Screenshot 2024-07-09 at 18 06 30" src="https://github.com/edgarpf/gitHub-foundations-certification/assets/15313093/5dcb47cd-9b48-42d4-97d2-aa033a50421d">
* To protect the CODEOWNERS file against unauthorized changes, you can define the repository owner as the owner of the CODEOWNERS file. 
* You can give organization members, outside collaborators, and teams of people different levels of access to repositories owned by an organization by assigning them to roles. Choose the role that best fits each person or team's function in your project without giving people more access to the project than they need. From least access to most access, the roles for an organization repository are:
  * Read: Recommended for non-code contributors who want to view or discuss your project
  * Triage: Recommended for contributors who need to proactively manage issues, discussions, and pull requests without write access
  * Write: Recommended for contributors who actively push to your project
  * Maintain: Recommended for project managers who need to manage the repository without access to sensitive or destructive actions
  * Admin: Recommended for people who need full access to the project, including sensitive and destructive actions like managing security or deleting a repository.
* With issue forms, you can optionally add Assignees and Labels.
* The github.dev is an online web-based editor that allows you to quickly open or create files within a repository.
* Secret gists aren't private. If you send the URL of a secret gist to a friend, they'll be able to see it. However, if someone you don't know discovers the URL, they'll also be able to see your gist. If you need to keep your code away from prying eyes, you may want to create a private repository instead.
* Issue templates are stored in a hidden directory named .github/ISSUE_TEMPLATE within the repository's default branch (usually the main branch).
* Internal repositories on GitHub are accessible to all members within an enterprise. This facilitates collaboration and sharing of code and projects among all authorized members of the organization.
* The new GitHub Projects provides a richer experience that enables you to keep track of your work, where you work.
  * Projects offers advanced customization options and built-in automation features, while Projects Classic provides basic customization capabilities.
  * Projects offers more views like Boards, Lists and Roadmaps.
  * Insights is available for the new Projects experience, you cannot use Insights with projects (classic).
* To make your project easier to find and engage with, you can add relevant topics that describe what your project is about. These topics act like labels. Also, consider adding a README file.
* Peter decides to publicize his private contributions on his GitHub profile. Now, when someone visits his profile, they can see that he made private contributions on certain days, but they won't be able to view the specific details of those contributions.
* The different statuses of a pull request: Draft, Open pull request, Closed pull request, Merged pull request.
* Pulse provides an overview of a repository's activity, including open and merged pull requests, open and closed issues, and a graph showing the commit activity for the top 15 users who committed to the default branch of the project in the selected time period.
* GitHub makes it convenient for you by automatically subscribing you to conversations when you actively participate.
* Layout options are available in GitHub Project: Table layout, Board layout and Roadmap layout.
* In Git repositories, settings from .gitignore files are inherited from parent directories to child directories.
* On GitHub, teams can be categorized as either visible or secret. Visible teams are accessible and can be mentioned by any member within the organization. In contrast, secret teams are only visible to the team members and individuals with owner permissions.
* Developers can create collapsible detail areas in GitHub comments or descriptions using the /details slash command.
* Glenn should archive the repository to make it read-only for all users and indicate that it's no longer actively maintained.
* You can assign multiple people to each issue or pull request, including yourself, anyone who has commented on the issue or pull request, anyone with write permissions to the repository, and organization members with read permissions to the repository.
* To stay updated on the activity in a specific repository on GitHub, You should watch the repository.
* If you add a README file to the root of a public repository with the same name as your username, it will appear on your profile page.
* Using the "git clone" command with the repository's URL followed by ".wiki.git" to clone a wiki from a GitHub repository.
* Your template repository cannot include files stored using Git LFS.
* Draft pull requests cannot be merged, and code owners are not automatically requested to review draft pull requests.
* GitHub provides the functionality to filter issues based on milestones.
* Deleting a branch in the GitHub flow signals that the work on the branch is completed.
* GitHub provides the option to create a permanent link to a specific line or range of lines of code in a file or pull request.
* GitHub accounts come in three types - Personal, Organization, and Enterprise.
* The code frequency graph displays the content additions and deletions for each week in a repository's history.
* Files added to a repository via a browser can be no larger than 25 MiB.
* You can exclude specified files from being used to inform code completion suggestions made by GitHub Copilot. However, this feature is only available in Copilot Business and Copilot Enterprise, not in Copilot Individual.
* When a PR targets a repository's default branch, special keywords in the PR description are interpreted to create links to relevant issues. However, if the PR's base is any other branch, the keywords are ignored, and no links are created.
* Anyone with push access to a repository can view its traffic, including full clones (not fetches), visitors from the past 14 days.
* After creating a gist, you cannot convert it from public to secret.. However, a secret gist can be made public by editing the gist and updating the visibility to public.
* By adding topics like "Literature" and "Book Reviews," Brian can classify his repository based on its intended purpose, making it easier for other users interested in literature to discover and contribute to his projects.
* Regardless of your local operating system, your codespace will run in a Linux environment.
* You can use the Dependency Graph feature on GitHub to identify all the project's dependencies.
* You should use a regular, non-incognito window in his browser to open github.dev, as incognito windows may not provide the necessary authentication.
* While it is available for use by anyone, access to Copilot is free for verified students, teachers, and maintainers of popular open source projects.
* GitHub Security Advisories enable repository maintainers to privately discuss and fix security vulnerabilities in a project before publicly disclosing them to the community.
* Secret teams cannot be nested under parent teams or have child teams.
* The actions/add-to-project workflow is designed to automate the process of adding issues and pull requests to projects.
* You can mark a comment as an answer to the discussion if it is within a category that accepts answers.
* With security keys, your enterprise can achieve a higher level of user security and protection.
* When your project initializes, two workflows are enabled by default: When issues or pull requests in your project are closed, their status is set to Done, and when pull requests in your project are merged, their status is set to Done.
* In GitHub discussions, you can mark a threaded comment (a comment in response to another comment) as the answer to a discussion if it provides a satisfactory solution or response.
* You should edit the .git/info/exclude file in the root of his repository to add rules that will not be checked in and will only ignore files for his local repository.
* Filters can be sorted to provide better information during a specific time period.
  * You can sort any filtered view by:
  * The newest created issues or pull requests
  * The oldest created issues or pull requests
  * The most commented issues or pull requests
  * The least commented issues or pull requests
  * The newest updated issues or pull requests
  * The oldest updated issues or pull requests
  * The most added reaction on issues or pull requests
* You should use git commit -a to automatically stage all tracked files for the next commit along with a descriptive commit message.
* To skip checks for a commit, type your commit message and a short, meaningful description of your changes. After your commit description, before the closing quotation, add two empty lines followed by skip-checks: true:
* The "Share a deep link" option allows you to configure more options for the codespace and build a custom URL, which can then be shared to facilitate codespace creation with specific configurations.
* When using the team synchronization feature, there are specific usage limits you need to know about. Exceeding these limits can lead to unexpected performance, and may cause synchronization failures.
  * Maximum number of members in a GitHub team: 5,000
  * Maximum number of members in a GitHub organization: 10,000
  * Maximum number of teams in a GitHub organization: 1,500
* The GitHub flow is a lightweight workflow that allows for safe experimentation with new ideas, features, and fixes. It involves creating branches, making changes, creating pull requests for feedback, reviewing and implementing feedback, getting approval, and finally, merging changes into the main branch.
* You can create an unlimited number of Codespaces per repository or branch, depending upon available space.
* GitHub Enterprise includes two deployment options: GitHub Enterprise Cloud (cloud-hosted) and GitHub Enterprise Server (self-hosted).
* You can open any GitHub repository in github.dev in either of the following ways:
* To open the repository in the same browser tab, press . while browsing any repository or pull request on GitHub.
  * To open the repository in a new browser tab, press >.
  * Change the URL from "github.com" to "github.dev".
  * When viewing a file, select the dropdown menu and click github.dev.
* While Personal Access Tokens (Classic) have broad access scopes and can live indefinitely, Fine-Grained Tokens have over 50 granular permissions and expire after a specified duration.
* Slash commands on GitHub are designed to make it easier to type complex Markdown, such as tables, tasklists, and code blocks, by reducing the amount of typing required.
* The referring sites and popular content sections of GitHub's traffic graph update on a daily basis. However, full clones and visitor information are updated hourly.
* In GitHub repositories, individuals with write access can pin up to three important issues above the list of issues.
* GitHub recommends repositories to remain small, ideally less than 1 GB, and less than 5 GB is strongly recommended for better performance and ease of maintenance.
* You should create an organization site for the centralized website of the organization. Organization sites are connected to a specific GitHub organization and must be created in a repository named <organization>.github.io.
* Once a vote has been cast in a poll on GitHub, voters cannot change their vote.
* GitHub Copilot is powered by OpenAI Codex.
* To mark an issue or pull request as a duplicate, type "Duplicate of" followed by an issue or pull request number in the body of a new comment. You can also use the GitHub-provided saved replies, "Duplicate issue" or "Duplicate pull request."
* SAML authentication is a process used to verify user identity and credentials against a known identity provider.
* To include the directory structure and files from all branches of the template repository, you should check the "Include all branches" option while creating the new repository.
* Each individual file must be smaller than 2 GiB.
* A project can span multiple repositories, but a workflow is specific to a repository.
* You can see all commits made to a repository in the past year (excluding merge commits) in the Commit graph.
* GitHub Apps are the preferred method for integrating with GitHub because they provide finer control over permissions for accessing data.
* 
