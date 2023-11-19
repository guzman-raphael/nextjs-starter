# nextjs-starter

Starter web app project for a frontend app based in Next.js that is setup for a distributed team.

## :rocket: Launch Environment

Included with the codebase is the recommended development environment configured using [DevContainer](https://containers.dev/).

Here are some options that provide a great developer experience:

- **Cloud-based IDE**: (_recommended_)
  - Launch the environment using [GitHub Codespaces](https://github.com/features/codespaces) on your fork with the default options by selecting the green `Code` button, then the `Codespaces` tab, and then the green `Create codespace on main` button. For more control, under the `Codespaces` tab select the `...` button where you may create `New with options....`.
  - Start time for a 2-Core codespace is within minutes.
  - Once you are done, see the options in the menu in the bottom-left corner. In Codespaces, you can `Stop Current Codespace`. By default, GitHub will also automatically stop the Codespaces after 30 minutes of inactivity.
  - _Tip_: Each month, GitHub renews a [free-tier](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#monthly-included-storage-and-core-hours-for-personal-accounts) quota of computing and storage. Typically we run into the storage limits before anything else since Codespaces consume storage while stopped. It is best to delete [Codespaces](https://github.com/codespaces) when not actively in use and recreate them when needed. Once any portion of your quota is reached, you will need to wait for it to be reset at the end of your cycle or add billing info to your GitHub account to handle overages.
  - _Tip_: GitHub auto names the Codespaces, but you can rename the Codespace so that it is easier to identify later.
  - _Tip_: All the edits you make are **_not persistent_**. Edits will be reset to the original content every time you restart the server. However, you can easily commit the changes to your fork.
- **Local IDE**:
  - Ensure you have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - Ensure you have [Docker](https://docs.docker.com/get-docker/)
  - Ensure you have [VSCode](https://code.visualstudio.com/)
  - Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  - `git clone` the codebase repository and open it in VSCode
  - Use the `Dev Containers extension` to `Reopen in Container` (More info in the `Getting started` included with the extension)

## :fire: Start a hot reload session

Run the following command in a terminal (see `TERMINAL` tab within the IDE):

```bash
(cd frontend && npm install && npm run dev)
```

Navigate to the port that becomes active (see `PORTS` tab inthin IDE and click on <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/globe.svg" width="20" height="20">).

## Create a Live Share session

- Click the `Live Share` tab on the left within the IDE
- Click `Share` if you are hosting a session
- Login using GitHub and click `Allow`
- Once redirected to browser, click on `Open Visual Studio - URL Handler`
- Click `Open`
- Once session has started, the link will be copied to your clipboard
- Send this to anyone you wish to join in your session
- Learn more in [docs](https://code.visualstudio.com/learn/collaboration/live-share)

## Initialize a fresh Next.js project

```bash
npx create-next-app@latest frontend
```
