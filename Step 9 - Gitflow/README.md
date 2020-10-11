# Step 9 - Gitflow

Now we're almost done with all the basics of working with Git and Github. As the last point, I'd like to introduce you to workflows in Git.

### What is a workflow?
You can think of a workflow as a way to develop your application. It's a way to tackle the feature expansion and control the development to avoid bottlenecking your development flow. 
But workflows can differ greatly from project to project depending on how elaborate the workflow has to be for the desired functionally. 

One example might be a small student team working on a project for school. Here the team doesn't necessarily have to have a stable build running 100% of the time, therefore, they might decide that a less complex workflow is better for this specific project.

Another example might be a business that has clients depending on the software which is being developed, therefore they always have to have a stable version live and the new features needs to be smoothly added to the project. Thereby, forcing the business to choose a more complex workflow to have greater quality control.


### Examples on workflows
When we're working with Git the workflow is made possible by branching and pull requests.

Here in the first example the workflow we see two branches. In this scenario, the team would work on their updates on the development branch and then merge with the master branch when one feature is done.

![Git flow example 1](../Assets/Images/gitflow/Git%20flow%20example%201.png)

Here in example 2, we see a feature branch going off the development branch. Therefore, the development branch acts as a middle man which makes it possible to work on multiple features at once as we see in example 3.

![Git flow example 2](../Assets/Images/gitflow/Git%20flow%20example%202.png)

In example 3 we see that both features 1 and 2 can be developed simultaneously and therefore, the team could be working parallel which increases their effectiveness.

![Git flow example 3](../Assets/Images/gitflow/Git%20flow%20example%203.png)

In this last example we see the most complex workflow I'm going to show you. Here we see that a hotfix branch is being branched off of the master branch. This is normally done when an unexpected error is found in the production version (I.E the master branch). Here it's crucial that the hotfix is also merged with the development branch so the error doesn't appear later on.

![Git flow example 4](../Assets/Images/gitflow/Git%20flow%20example%204.png)


### If you'd like to see a more complex workflow or would like a different explanation then I'd recommend this video: [Git flow video](https://www.youtube.com/watch?v=aJnFGMclhU8)

Remember this is just a quick view of the possibilities made from working with Git and Github. To learn more start exploring the docs [https://docs.github.com/en](https://docs.github.com/en).