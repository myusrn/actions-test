# actions-test
github actions test using hosted and self-hosted runners  
<br>

overviews used . . .  
- [what is devsecops? devsecops explained in 8 mins](https://youtu.be/nrhxNNH5lt0)  
- [github actions tutorial - basic concepts and ci/cd pipeline with docker](https://youtu.be/R8_veQiYBjI)
- [communication between self-hosted runners and github](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners#communication-requirements)   

The self-hosted runner connects to GitHub to receive job assignments and to download new versions of the runner application. The self-hosted runner uses an HTTPS long poll that opens a connection to GitHub for 50 seconds, and if no response is received, it then times out and creates a new long poll. The application must be running on the machine to accept and run GitHub Actions jobs.

Since the self-hosted runner opens a connection to GitHub.com, you do not need to allow GitHub to make inbound connections to your self-hosted runner.

You must ensure that the machine has the appropriate network access to communicate with the GitHub hosts listed below. Some hosts are required for essential runner operations, while other hosts are only required for certain functionality.  

- [github flow to collaborate on projects](https://docs.github.com/en/get-started/quickstart/github-flow)  
- [github actions hosted runners images](https://github.com/actions/runner-images)  
<br>

walkthroughs used . . .  
- [installing a self-hosted github runner](https://ideasawakened.com/post/radauthenticator-part-4-build-automation-with-delphi-and-github-by-installing-a-self-hosted-runner)
- [getting started with github actions](https://ideasawakened.com/post/radauthenticator-part-5-implement-a-hello-world-github-action-on-your-self-hosted-runner)    

