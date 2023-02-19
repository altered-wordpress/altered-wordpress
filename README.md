# Altered Wordpress (Creating an Alternative to Wordpress)

![altered-wordpress-github-banner-min](https://user-images.githubusercontent.com/44144724/219922313-9c68f3dc-c036-4fbb-aeb6-7c7b9d818274.png)

## Cons of using Wordpress

- It's slow.
- Too much bloat.
- Ugly UI and bad UX.
- It uses SVN for version controlling which is awful and isn't as good as Git.
- Breaking changes in themes and plugins can cause a lot of issues for website owners.
- Some Wordpress themes and plugins are also slow, have ugly UI and bad UX, and have too much bloat.
- Security: Installing a lousy plugin may explode your whole website.
- Website owners need to install plugins for basic needs and at the same time, there are features and options that some people may never use.

## Pros of using Wordpress

- Open-source.
- Community and resources:
- Communities to ask for help.
- Many free & paid tutorials.
- Many free & paid themes and plugins.
- Easy to get started.
- People can contribute to translating a theme or plugin.

## What we are going to build

- Open-source.
- Easy and fully featured API support for building themes and plugins.
- A great documentation.
- Stay up to date with Wordpress itself.
- Design a beautiful UI WOrdpress Administration.
- Remove bloat and unused code.
- Maybe use VueJS for some Frontend stuff, or maybe use something like AlpineJS.
- Create a free and paid marketplace at the feature and integrate it with Github.
- Lock updating a theme or plugin if it isn't compatible with other installed plugins.
- Build and provide premade UI components for building theme and plugin settings that are shown in the Wordpress administration panel.
- Somehow scope the themes and plugins variables, functions and etc, to prevent name collision
- Add a security system, for example, the theme or plugin can't access X data from the database if that access is not explicitly given. Have a strong and fully featured system like this, so if a plugin doesn't need to do anything with the database (or that access or functionality) to do what it sposed to do, then it doesn't need to have that access. We can already see how our phone and computer apps are trying to have access to everything even if they literally don't need that access. So, any theme and plugin need to ask for permission for adding, editing, deleting and etc from the database.
- Provide basic and neat widely used features so website owners don't need to install a plugin for every single thing.
- Allow users to be able to disable and completely hide a feature that they don't need. for example, a user may like to not have the post post-type, so make it possible to get rid of it.
- Allow shit ton of customization options for administration UI.
- Create a community on Telegram and Discord and maybe slack.

## Attention

Altered Wordpress is not [Wordpress](http://wordpress.org).
