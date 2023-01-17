# DevOps-home-assignment-junior

 1. Fork the following repository https://github.com/pdurbin/maven-hello-world
 if you don’t know what fork is google it, apparently, they have a primitive yet quite an efficient device which could answer most of your questions, it’s called Google!
2. Understand this repository -
   a. Which programming language is this? </br>
   b. What is maven? </br>
   c. How does maven work? </br>
   d. What is this pom.xml everyone keeps mentioning? </br>
3. In order to build the above repository, use Azure Pipelines or GitHub Actions. 
   Hint: GitHub Actions is easier
4. Change the code:
   a.  Add your name to the "Hello World" message. </br>
   b. Set  Jar version to 1.0.0 </br>
5. Create a simple pipeline which would do the following actions:
   a. Increase the Patch part of the jar version ( 1.0.0 - > 1.0.1) automatically </br>
   b. Compile the code </br>
   c. Package it into an artifact </br>
   d. Create an artifact item for the build </br>
   e. Create a docker image  containing the artifact  - use Dockerfile: </br>
       i. Tag the Docker image as the the Jar version automatically. </br>
       ii. The  Docker image shouldn't run with root </br>
   f. Push the docker image that was created in the previous step to Docker Hub </br>
   g. Download and run the docker image. </br>
6. Once it’s running, we would come and pick you up immediately </br>

## Bonus – do as much as possible from the above using Multistage Docker 
If you encounter any issues with these primitive technologies, we highly recommend using Google, we believe you’ll be able to get most of the answers from this tool.
Good Luck!

See my submission [here](https://github.com/bennyrottenberg/maven-hello-world)
