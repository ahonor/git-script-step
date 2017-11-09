Example script plugin demonstrating how to run a script stored in a git repository.
Given a repository and a script, this plugin will run it along with specified arguments to the script.

Authentication
* Assumes oauth2 token for authentication to the repository.
* Token should be stored in the Rundeck key store.

Use the Dryrun mode to print out the commands without actually running them.

Example
Import the resources/example-job.yaml to test out the plugin. It calls the resourcs/sample-script by default.

Building

    zip -x *.git* -r git-script-step.zip git-script-step

    