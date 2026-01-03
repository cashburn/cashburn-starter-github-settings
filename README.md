# Cashburn Starter GitHub Settings
A minimal starter repo with instructions for storing GitHub Repository Settings/PR policies in a `settings.yml` file, using the [GitHub Settings App](https://github.com/apps/settings).

Rulesets can be imported using the json files provided in `/rulesets`. Rulesets are NOT currently working in the `/.github/settings.yml` file.

# Setup Steps
1. Install the [GitHub Settings App](https://github.com/apps/settings) for your Repository. This is created/supported by [Probot](https://probot.github.io/), a reputable open-source framework for GitHub automation using GitHub Apps.
   1. Select your specific repository
2. Copy `/.github/settings.yml` into your repository at `/.github/settings.yml`
3. Push to the default branch. This should trigger the Repository Settings to be updated by the Settings App.
4. Go to your Repository Settings in GitHub
   1. Under `Code and automation`, select `Rules -> Rulesets`, then `New ruleset -> Import a ruleset`
   2. Upload the ruleset json file