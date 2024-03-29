{
  "install-npm": {
    "verifying": "verifying that npm is installed...",
    "missing": "It looks like npm is not installed.",
    "npm-problem": "Uh oh!  npm had a problem!",
    "version-verified": "You have version {{version}} installed.  Great!\nNow let's see what the latest version is... wait for it...",
    "latest-version": "The latest npm is: {{version}}",
    "upgrade": "You have version {{version}}, but the latest is {{latest}}\nRun `npm install npm -g` to upgrade it\n(You can also just skip this if you want)",
    "success": "Congratulations!\nYou have a recent version of npm installed!"
  },
  "dev-environment": {
    "err_workshopper": "It looks like you are in the root of the workshopper.",
    "err_home": "It looks like you are in your home directory.",
    "hint": "That is not wise.  Please make a new dir, and use that.",
    "no_package": "Seems like the `package.json` is missing. Did you run `npm init`?"
  },
  "login": {
    "whoami_err": "Uh oh!\nIt looks like something went wrong",
    "logged_out": "Hm... I don't see a login here\nDid you run `npm adduser` to create the account?",
    "success": "Congratulations, {{user}}!\nYou are the proud owner of an imaginary new npm account!\nUse it wisely.  Never in anger.  Always for the Good.\n\nWith this sweet power comes much responsibility, which is\nsufficiently different from Spiderman's thing that Marvel\nhopefully won't sue us.\n\nExcelsior!"
  },
  "start-a-project": {
    "no_package": "No package.json found.\nPlease run `npm init` in your working directory.",
    "success": "Congratulations!\nYou created a project!  View the package.json file to see it.",
    "extra_credit": "EXTRA CREDIT!  Nicely done."
  },
  "install-a-module": {
    "error": "Uh oh!  Looks like it didn't install right.\nThe error I got was: \n{{{error}}}\nMake sure you use the `npm install @linclark/pkg` command\nto install the `@linclark/pkg` module.",
    "success": "Congratulations! You installed it."
  },
  "listing-dependencies": {
    "usage": "Please run:\n`how-to-npm verify OK` if everything is ok,\nor:\n`how-to-npm verify NOT OK` otherwise.",
    "ok_not": "Sorry, no.  Everything is not ok!\nTry running `npm ls` and viewing the error.",
    "not_ok_not": "Hmm...\nWell, there may indeed be a lot wrong with the world,\nbut your package.json and node_modules folder are fine.",
    "success": "Looks like you fixed the problem.  Fantastic!\nNote that `npm ls` is a lot calmer now."
  },
  "npm-test": {
    "section_missing": "Oops!  You don't have a `scripts.test` section in your\npackage.json file.  Edit it, and try again.",
    "running": "Running your test script...",
    "running_done": "...done!",
    "error": "Uh oh!  The test failed!\nTry creating a test that actually works.",
    "success": "Congratulations!  You wrote a test that passes!\nWriting a test that is actually GOOD is left for another time."
  },
  "package-niceties": {
    "problem": "Not quite!\nThere's still a problem to fix.",
    "error": "Uh oh!\nIt looks like something went wrong",
    "success": "Looking sharp!\nA package without a readme and some metadata is like a\nbunch of JavaScript without instructions or git repo links."
  },
  "publish": {
    "error": "Uh oh!\nIt looks like you didn't successfully publish the\n  {{name}}\npackage.  Try again!"
  },
  "version": {
    "invalid_semver": "Looks like your package.json has an invalid version!\nUse `npm help semver` to learn more about version numbers\nYour current version number is: {{version}}\n",
    "old_version": "Uh oh!\nThe version is still {{version}}\nCheck `npm help version` for a handy util to do this.",
    "success": "Great job!\nRun `how-to-npm` for the next exciting challenge!"
  },
  "publish-again": {
    "not_republished": "Whoops!\nLooks like you did not publish the package again\nTry running `npm publish` and then verifying again.",
    "current_missing": "Hmm... I see that you published more than once, but\nthe current version ({{version}}) is not in the set.\nHere's what I see in there:\n{{{found}}}\nTry publishing again!",
    "success": "Wow!  You are well on your way to becoming a regular\nTJames \"Substack\" Halidaychuk!  There's no stopping you!\nRun `how-to-npm` to go to the next step."
  },
  "dist-tag": {
    "success": "Uh oh, looks like you still only have a single dist-tag.\nUse `npm help dist-tag` to learn how to add another one."
  },
  "dist-tag-removal": {
    "too_many": "Uh oh, looks like you have some extra dist-tags there.\nUse `npm help dist-tag` to learn how to remove them.",
    "version_mismatch": "Oops!  Your \"latest\" tag still points at the most recent\nrelease, {{version}}.\nPoint that somewhere else, and re-run `how-to-npm verify`\n\nUse `npm help dist-tag` to learn more about how to do it."
  },
  "outdated": {
    "no_package": "Run `how-to-npm verify PKG` but replace `PKG` with the name\nof the package that is outdated",
    "wrong_package": "Nope, it's not {{{pkg}}}.  Try again!"
  },
  "update": {
    "outdated": "Oops!  You are still using the outdated version!",
    "success": "Awesome!  You're up to date!\nRun `how-to-npm` to move on to the next exercise"
  },
  "rm": {
    "dependencies_left": "Looks like there are some deps still hanging around",
    "package_json_left": "You removed the files, but not the entries in package.json"
  },
  "finale": {
    "todo": "It looks like you still have more work to do. Finish\nthe following exercises before you can start this:"
  },
  "error": {
    "not_setup": "Looks like you are not ready for this one yet!\nGo back to the `01 Dev Environment` lesson to set up\nyour working directory.",
    "wrong_folder": "Uh oh!\nIt looks like you are in the wrong folder.\nPlease cd into {{cwd}}\nand then try again'"
  },
  "exercise": {
    "00 Install npm": "00 Install npm",
    "01 Dev Environment": "01 Dev Environment",
    "02 Login": "02 Login",
    "03 Start A Project": "03 Start A Project",
    "04 Install A Module": "04 Install A Module",
    "05 Listing Dependencies": "05 Listing Dependencies",
    "06 npm Test": "06 npm Test",
    "07 Package Niceties": "07 Package Niceties",
    "08 Publish": "08 Publish",
    "09 Version": "09 Version",
    "10 Publish Again": "10 Publish Again",
    "11 Dist Tag": "11 Dist Tag",
    "12 Dist Tag Removal": "12 Dist Tag Removal",
    "13 Outdated": "13 Outdated",
    "14 Update": "14 Update",
    "15 Rm": "15 Rm",
    "16 Finale": "16 Finale"
  },
  "menu": {
    "reset-registry": "RESET REGISTRY"
  },
  "reset": "Successfully reset registry"
}