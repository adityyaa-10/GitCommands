<!DOCTYPE html>
<html>
    <meta charset = "utf8">
    <head>
        <title>Basic Git Commands</title>
        <h2 align="center">Commands in Git</Command></h2>
        <p align="center">Hey Folks here are the git commands you need to get started with git basics</p>
    </head>

        <body>
        <table align="center">
            <thead>
                <tr>
                    <th> Command </th>
                    <th></th>
                    <th> Working of Command</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                <td> git config --global user.name “[firstname lastname]”</td>
                <td>   ➡️   </td>
                <td> set a name that is identifiable for credit when review version history</td>
                </tr>
                <tr>
                    <td> git config --global user.email “[valid-email]”</td>
                    <td>   ➡️   </td>
                    <td> set an email address that will be associated with each history marker</td>
                </tr>
                <tr>
                    <td> git config --global color.ui auto</td>
                    <td>   ➡️   </td>
                    <td> set automatic command line coloring for Git for easy reviewing</td>
                </tr>
                <tr> 
                    <td> git init</td>
                    <td>   ➡️   </td>
                    <td> initialize an existing directory as a Git repository</td>
                </tr>
                <tr>
                    <td> git clone [url]</td>
                    <td>   ➡️   </td>
                    <td> retrieve an entire repository from a hosted location via URL</td>
                </tr>
                <tr>
                    <td>git status</td>
                    <td>   ➡️   </td>
                    <td>show modified files in working directory, staged for your next commit</td>
                </tr>
                <tr>
                    <td> git add [file]</td>
                    <td>   ➡️   </td>
                    <td> add a file as it looks now to your next commit (stage)</td>
                <tr>
                    <td> git reset [file]</td>
                    <td>   ➡️   </td>
                    <td> unstage a file while retaining the changes in working directory</td>
                </tr>    
                <tr>
                    <td> git diff </td>
                    <td>   ➡️   </td>
                    <td> diff of what is changed but not staged</td>
                </tr>
                <tr>
                    <td> git diff --staged </td>
                    <td>   ➡️   </td>
                    <td> diff of what is staged but not yet commited</td>
                </tr>
                <tr>
                    <td> git commit -m “[descriptive message]”</td>
                    <td>   ➡️   </td>
                    <td> commit your staged content as a new commit snapshot </td>
                </tr>         
                <tr>
                    <td>git branch </td>
                    <td>   ➡️   </td>
                    <td>list your branches. a * will appear next to the currently active branch</td>
                </tr>
                <tr>
                    <td>git branch [branch-name]</td>
                    <td>   ➡️   </td>
                    <td>create a new branch at the current commit</td>
                </tr>
                <tr>
                    <td>git checkout</td>
                    <td>   ➡️   </td>
                    <td>switch to another branch and check it out into your working directory</td>
                </tr>
                <tr>
                    <td>git merge [branch]</td>
                    <td>   ➡️   </td>
                    <td>merge the specified branch's history into the current one</td>
                </tr>
                <tr>
                    <td>git log</td>
                    <td>   ➡️   </td>
                    <td>show all commits in the current branch's history</td>
                </tr>
                <tr>
                    <td>git log branchB..branchA</td>
                    <td>   ➡️   </td>
                    <td>show the commits on branchA that are not on branchB</td>
                </tr>
                <tr>
                    <td>git log --follow [file]</td>
                    <td>   ➡️   </td>
                    <td>show the commits that changed file, even across renames</td>
                </tr>
                <tr>
                    <td>git diff branchB...branchA</td>
                    <td>   ➡️   </td>
                    <td>show the diff of what is in branchA that is not in branchB</td>
                </tr>
                <tr>
                    <td>git show [SHA]</td>
                    <td>   ➡️   </td>
                    <td>show any object in Git in human-readable format</td>
                </tr>
                <tr>
                    <td>git rm [file]</td>
                    <td>   ➡️   </td>
                    <td>delete the file from project and stage the removal for commit</td>
                </tr>
                <tr>
                    <td>git mv [existing-path] [new-path]</td>
                    <td>   ➡️   </td>
                    <td>change an existing file path and stage the move</td>
                </tr>
                <tr>
                    <td>git log --stat -M</td>
                    <td>   ➡️   </td>
                    <td>show all commit logs with indication of any paths that moved</td>
                </tr>
                <tr>
                    <td>git config --global core.excludesfile [file]</td>
                    <td>   ➡️   </td>
                    <td>system wide ignore patern for all local repositories</td>
                </tr>
                <tr>
                    <td>git remote add [alias] [url]</td>
                    <td>   ➡️   </td>
                    <td>add a git URL as an alias</td>
                </tr>
                <tr>
                    <td>git fetch [alias]</td>
                    <td>   ➡️   </td>
                    <td>fetch down all the branches from that Git remote</td>
                </tr>
                <tr>
                    <td>git merge [alias]/[branch]</td>
                    <td>   ➡️   </td>
                    <td>merge a remote branch into your current branch to bring it up to date</td>
                </tr>
                <tr>
                    <td>git push [alias] [branch]</td>
                    <td>   ➡️   </td>
                    <td>Transmit local branch commits to the remote repository branch</td>
                </tr>
                <tr>
                    <td>git pull</td>
                    <td>   ➡️   </td>
                    <td>fetch and merge any commits from the tracking remote branch</td>
                </tr>
                <tr>
                    <td>git rebase [branch]</td>
                    <td>   ➡️   </td>
                    <td>apply any commits of current branch ahead of specified one</td>
                </tr>
                <tr>
                    <td>git reset --hard [commit]</td>
                    <td>   ➡️   </td>
                    <td>clear staging area, rewrite working tree from specified commit</td>
                </tr>
                <tr>
                    <td>git stash</td>
                    <td>   ➡️   </td>
                    <td>Save modified and staged changes </td>
                </tr>
                <tr>
                    <td>git stash list</td>
                    <td>   ➡️   </td>
                    <td>list stack-order of stashed file changes</td>
                </tr>
                <tr>
                    <td>git stash pop</td>
                    <td>   ➡️   </td>
                    <td>write working from top of stash stack</td>
                </tr>
                <tr>
                    <td>git stash drop</td>
                    <td>   ➡️   </td>
                    <td>discard the changes from top of stash stack</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
