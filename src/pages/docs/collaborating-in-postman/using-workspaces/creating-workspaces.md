---
title: "Creating workspaces"
order: 76
page_id: "creating_workspaces"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Working with your team"
    url: "/docs/collaborating-in-postman/collaboration-intro/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Related Blog Posts"
  - type: link
    name: "Workspaces! What are they good for?"
    url: "https://blog.postman.com/2018/04/07/workspaces-the-biggest-thing-to-hit-postman-this-month/"
  - type: subtitle
    name: "Case Studies"
  - type: link
    name: "Movember Foundation"
    url: "https://www.postman.com/resources/case-studies/movember-foundation/"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Team collaboration with Postman"
    url: "https://www.youtube.com/watch?v=8tLvvQ-3Nx0"
  - type: section
    name: "Next Steps"
  - type: link
    name: "Using and managing workspaces"
    url: "/docs/collaborating-in-postman/using-workspaces/managing-workspaces/"

warning: false

---

Workspaces allow you to organize your Postman work and collaborate with teammates. You can group your projects together, with workspace acting as the single source of truth for related APIs, collections, environments, mocks, monitors, and other linked entities. By collaborating in a workspace, your edits are synced with your team in realtime.

[![WS-mainScreen-teamMenu](https://assets.postman.com/postman-docs/Workspaces_Mainscreen3.png)](https://assets.postman.com/postman-docs/Workspaces_Mainscreen3.png)

Personal workspaces are visible only to you—with a [Postman account](/docs/getting-started/postman-account/) you can create unlimited workspaces. With team workspaces, you can share and manage access to project components with collaborators.

By sharing a component such as a collection to a workspace, collaborators with access to the workspace can also access it—by default with readonly permissions. You can [configure access settings](/docs/collaborating-in-postman/roles-and-permissions/) for the workspace on an individual basis to provide permissions depending on your account.

Workspaces can also create visibility for the projects within a team, since collections in the workspace are visible to all members sharing it. Request history is also saved to a workspace, which can aid collaborative debugging efforts.

> For Postman Business and Enterprise teams, a private workspace is a team workspace that is only visible to the user who created it, plus team members who have been invited to join it. Private workspaces allow teams to restrict access to collections, environments, mocks, and monitors that are relevant only to a particular group.

## Creating a new workspace

To create a new workspace, select the workspace dropdown menu at the top and center of Postman, and choose **Create New**.

<img alt="Default Workspace" src="https://assets.postman.com/postman-docs/default-workspace-dropdown.jpg" width="500px"/>

Use the switch to choose a __Team__ or __Personal__ workspace. Note that you can share elements to a different workspace at a later date if you aren't sure which type to create.

To create a personal workspace, enter the workspace enter the name and summary. For a team workspace, you can also invite collaborators and set access levels depending on your Postman plan and account permissions.

[![New workspace](https://assets.postman.com/postman-docs/new-team-workspace-details.jpg)](https://assets.postman.com/postman-docs/new-team-workspace-details.jpg)

If you are an Admin user and add any email addresses not associated with current team members, they will be invited to join the team.

> Postman Business and Enterprise users can check the box to limit visibility of this workspace to invited members, making a [private workspace](/docs/collaborating-in-postman/using-workspaces/managing-workspaces/).

Click **Create Workspace** and Postman will open your new workspace. You can add elements to the workspace and invite new members using the __Invite__ button at the top at any time.

You can also create a new workspace in the [Workspaces dashboard](https://app.getpostman.com/dashboard). Click **Create a new workspace** and follow the same steps.

[![create new workspace dashboard](https://assets.postman.com/postman-docs/createnewworkspacedashboard.png)](https://assets.postman.com/postman-docs/createnewworkspacedashboard.png)

## Next steps

Check out some tips on how to [use and manage your workspaces](/docs/collaborating-in-postman/using-workspaces/managing-workspaces/). You can also use your workspace [activity feed](/docs/collaborating-in-postman/using-workspaces/changelog-and-restoring-collections/) to keep up to date with progress on the projects within it.
