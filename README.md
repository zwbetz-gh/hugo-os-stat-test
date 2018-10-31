# Hugo `os.Stat` test

A sample project for testing the Hugo function [`os.Stat`](https://gohugo.io/functions/os.stat/), inspired by these forum threads: [solved-os-fileinfo-modtime](https://discourse.gohugo.io/t/solved-os-fileinfo-modtime/14964) and [hugo-bitbucket-firebase](https://discourse.gohugo.io/t/hugo-bitbucket-firebase/14970). 

[Wercker CI](https://app.wercker.com/) builds this [Hugo](https://gohugo.io/) site, then deploys the generated static files to [Firebase](https://firebase.google.com/).

Demo: <https://hugo-os-stat-function.firebaseapp.com/>

## Run it locally

1. [Install Hugo](https://gohugo.io/getting-started/installing/)
1. Open a command line and run:
    1. `git clone https://github.com/zwbetz-gh/hugo-os-stat-test.git`
    1. `cd hugo-os-stat-test`
    1. `hugo server`
1. Navigate to `http://localhost:1313/` in your browser