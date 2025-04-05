<header>

# Hello TT魔怔人

BATA 1.8.0 through 1.7.4 are dead

</header>

## 依旧是我 : 禁闭

_TT "我是禁闭"! :wave:_

*You should all be here for the old TT version I'm telling you the bad news that the old version is dead:

- TT  I'm telling you the bad news that the old version is dead
- TT If you have anything to say, you can send me a private message in the background

*If you're here for the old version, you're good to go


Good friend plus me `T/ROOMID 355007106`.

### :The beautification package also died

1.You're here for the old version, and you're good to go.

1. Navigate to the **Code** tab.
1. From the **main** branch dropdown, click on the **welcome-workflow** branch.
1. Navigate to the `.github/workflows/` folder, then select **Add file** and click on **Create new file**.
1. In the **Name your file** field, enter `welcome.yml`.
1. Add the following content to the `welcome.yml` file:

   ```yaml copy
   name: Post welcome comment
   on:
     pull_request:
       types: [opened]
   permissions:
     pull-requests: write
   ```

1. To commit your changes, click **Commit changes**.
1. Type a commit message, select **Commit directly to the welcome-workflow branch** and click **Commit changes**.
1. Wait about 20 seconds, then refresh this page (the one you're following instructions from). A separate Actions workflow in the repository (not the workflow you created) will run and will automatically replace the contents of this README file with instructions for the next step.

<footer>

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/hello-github-actions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
