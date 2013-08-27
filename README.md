Golgi
=====

Deploys and tests platform apps so that they can be safely deployed


Deploy.sh
Test.sh


How to use (MVP)
==========
0. Add deploy.sh to your project and write out the command that is needed to push it to your testing app
1. Add github webhook for golgi
2. Let golgi run (CLI for status, or Web interface, or just let github display it)
3. Golgi will report back to github telling you if the build is good
4. Tell golgi to deploy your branch (CLI/Web interface?) 

Whats won't be in the MVP
=========================
* Any sort of interface
* actual deployment tools, it will just run direwolfs on a project and for now just codon
Incase you were wondering about the name...
http://en.wikipedia.org/wiki/Golgi_apparatus
