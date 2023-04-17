# Empire Expansion Tracker

Built for No Stars, a Sci-Fi Nation Roleplay (SFNRP) guild on Discord, this utility lets you track your assets and calculates how they expand over time.

## Instructions

DO NOT ENTER HYPHENS AS CONSTRUCTION NAMES

1. Open time_input.py. Run it, and follow instructions.
2. Go to items_control.py. Open it in your preferred IDE, and run it. Follow the instructions given. 
3. Open main.py. Run it, and look at the list of running items. You will have to manually go into items.py and items_list.py to remove any excess items, so be careful when inputting.
4. You are now all set to start tracking your nation-expansion. 

## Logs

Logs are in the items.py file. Time needed means time from start.

## Development Environment Setup

To contribute to this codebase, you need to have the right tools. 
You have three options for setup, ordered by difficulty from easiest to hardest:

### Option 1: GitHub Codespace

You need:
- A browser, preferably Firefox or Chrome.
- A GitHub account.

Setup:
1. In your browser, sign into GitHub.
2. Navigate to [the GitHub repo for this project](https://github.com/LawTest4085/NoStars-ExpansionTracker).
3. Click the green Code button -> Codespaces tab -> "Create codespace on main".

> #### Notice:
> Make sure you stop or delete your codespace when you're done. You have 60 hours per month of free codespace up-time, after which you'll need to pay GitHub for more. You can manage your codespaces in the Codespace tab in the green Code button's dropdown.

### Option 2: Dev Container

You need:
- VS Code
- Docker

Setup:
1. In VS Code, install the Remote Development extension pack.
2. Copy the URL of this repo (found in the dropdown of the green Code button in [the GitHub repo for this project](https://github.com/LawTest4085/NoStars-ExpansionTracker)).
3. Open the VS Code command palette. Invoke the "Dev Containers: Clone Repository in Container Volume" command. Paste the repo's URL, and press `Enter`.

### Option 3: Manual Setup

You need:
- VS Code
- Git
- (Optional, but preferred) The same operating system as used by container in the `image` section of the [Dev Container definition](.devcontainer/devcontainer.json)

Setup:
1. Install onto your machine every application, service, and utility listed in the `features` section of the [Dev Container definition](.devcontainer/devcontainer.json).
2. Install into VS Code every extension listed in the `customizations` section of the [Dev Container definition](.devcontainer/devcontainer.json).
3. `git clone` this repo.