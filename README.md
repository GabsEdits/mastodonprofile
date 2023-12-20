<div align="center">
<h1>Mastodon Profile Card</h1>
<p>A website to list your Mastodon and GitHub profile to the world</p>
</div>

![image](https://github.com/hellofaizan/xprofile/assets/84437051/5b463c7d-4488-4743-8e56-f0cf31c6ba3d)


## Credits
Fork of [XProfile](https://github.com/hellofaizan/xprofile), ❤️ for making this project. This fork just changes the code to link to your Mastodon Server.

## Languages/Tools

    <img src="https://skillicons.dev/icons?i=next,js,react,firebase" />

## 👩🏽‍💻 Demo

Check out the website: [Mastodon Profiles](https://mastodon.gxbs.me)

## 👇🏽 File Format
```json
    ,{
        "server": "fosstodon.org",
        "username": "gabs",
        "name": "Gabriel Cozma",
        "github": "GabsEdits",
        "banner_color": "#fff",
        "about": "Human | gabs.eu.org"
    }
```

| Key  | Value                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| server | This value should be your Mastodon server that you are apart of.|
| username | This value should be your Mastodon username.|
| name | This value should be your real name. |
| github | The value should be your Github username                   |
| banner_color | The value should contain any hex code for background just like Twitter eg: #fff, #000   |
| about | Short simple `max 2 lines` about yourself, You can also include links which are clickable   |
    

## 🛠️ Installation Steps

### 🔥 Add your profile using

1. Fork the project:

- [Fork](https://github.com/hellofaizan/mastodonprofile/fork) the project. Click on the <a href="https://github.com/hellofaizan/xprofile/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="15" width="15"></a> icon in the top right to get started.

2. Create a New Branch:

- On your new repository's page, click the gray `main` button in the upper left to reveal a dropdown menu.
- Enter the name of your new branch in the text box. (Branch names usually make a reference to what is being changed. Example: `profileAdd`).
- Click on `Create branch <new branch name>` and this will automatically take you to your new branch. You can make edits on the main branch, but this may cause issues down the line. Best practice is to create a new branch for each separate issue you work on. That way, your `main` branch remains in sync with `xprofile` `main` branch.

3. Navigate to file:

- Navigate to the `data/users.json` file.

4. Edit:

- On the top right of the JSON file, click on the pencil icon to edit the file by adding your image, name and username.
- You can add JSON object wherever you want in the file, it will automatically arrange according to alphabetical order.
- After editing the JSON file, add a commit message and click on the green button saying "Commit Changes". Make sure you have selected the branch you have created.

5. Raise a Pull Request:

- And finally, create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!
- Great job! You did it!
- Remember to PR in ```addProfile branch of repository```


## 🚀 Running locally
To run locally, just `cd` into the project and run the following commands to run node modules and serve the website locally.
```bash
yarn
```

```bash
yarn run dev
```

## 💪🏽 Contributors

Thank you all so much for spending your time to improve Mastodon Profile.

<a href="https://github.com/hellofaizan/xprofile/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gabsedits/mastodonprofile" />
</a>

## Drop a ⭐ if you like this project
