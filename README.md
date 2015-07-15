# github-project-touchers
Small script that generates a CSV dump of users who have touched a project.

## Usage

1. Clone the repository
2. Generate a GitHub access token at https://github.com/settings/tokens and export it for the script: `export GITHUB_ACCESS_TOKEN=asdf1234`
3. Install dependencies: `cd github-project-touchers && bundle install`
4. Run the script. For example, to get commenters of the project `deis/deis`: `./commenters deis/deis`
5. Inspect the generated CSV
6. Enjoy!
