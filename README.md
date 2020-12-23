# Docker-Jenkins

### _General Description_
_Your Jenkins master is under too much load, as all jobs were being run on it. So, we decided to integrate two Jenkins workers with the Jenkins master, to assist in   distributing jobs to be executed on worker nodes. The two new Jenkins workers (`JenkinsWorker1` labeled `docker1`, and `JenkinsWorker2` labeled `docker2`) have been finally setup. We will break down a single job which used to spin up multiple containers to test parts of your application._
 - _The first part of your application to be tested fetches some JPG files._
 - _The second part watermarks them and all artifacts must be saved._

### _Learning Objective :-_
<p align="center">
  <img width="450" height="250" src="https://github.com/samblake30/Docker-Jenkins/blob/master/images/learnObjective.png">
</p>
