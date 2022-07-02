# Let's Practice Git and Github Together

This Challenge contains a mission, should you choose to accept it, which is practising all the you acquired knowledge in order to get the job done.

## Step 1 : Fork the original remote repository to your own remote repository

This project represents a collaborative team project shared between GoMyCode Full Stack JS students, and as it represents the collaborator is your own instructor, he asked you to add specific fonctionnalities before checking them and adding them right away to the original project.

PS : Use proper manipulations to do so.

## Step 2 : Let's get to work locally

In order to start the work, you need to download all the initial files into you own machine. Don't heesitate to **clone** it up ! (Or pull it up, you know what suits you the most).

## Step 3 : Getting started isn't the easiest Part !

Before do any changes, let's make sure that you are linked to all necessary remote repository :

 - First, Check the current remote repositories linked to the local repository. Execute `git remote -v` and see the result.
 - If the original repository is not among them, add it by naming it **`up-stream`**

**Note :** Linking the original repository will allow you to pull all changes that have been made up in it. you can easily do that by executing `git fetch up-stream` in your command prompt.

## Step 4 : Change As you Wish

Now it is time to add the necessary Changes to the repository :

 - First, Add the following Code in the **HTML file** :

```
    <div>
        <h3 class="title">Yes, I'm a Change</h3>
        <p class="paragraph">And yes, i do have a description</p>
    </div>
```

Once finished, stage the changes and commit by using the message `html modification`

 - Next, Add the following Code in the **CSS file** :

```
.title {
    color: blue;
}

.paragraph {
    color: violet;
}
```

Once finished, stage the changes and commit by using the message `css modification`

 - Finally, Add the following Code in the **JS file** :

```
function sayHello() {
    console.log("Hello Guys !");
}
```

Once finished, stage the changes and commit by using the message `js modification`

 - Let's be a little bit crazy and add a branch to our local branches, (you know how to do it right ? :3). You can name it whatever you want.

Checkout out to this branch if it isn't already done, then create a `robots.txt` file in your repository. Stage the changes and commit by using the message `adding a robots.txt`

## Step 5 : Check with you instructor

Do a pause here and alert your instructor that everything is done correctly.

## Step 6 : Publish your work

Since you have finished all the modifications, now it is time to push your changes to your remote repository.

**Note :** before pushing, make sur that nothing has been changed yet in the **original remote repository**.

After verifying and pushing, verify again if all the files has been pushed in **your remote repository**.

## Step 7 : Ask fo validation

The last step is to show your instructor that you have done the work properly, this can be done simply by doing a pull request to the **original remote repository** and wait for the validation !