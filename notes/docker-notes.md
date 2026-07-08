# Docker Notes
If an interviewer asked:

**Why Docker?**
Docker eliminates configuration drift by packaging the application together with its runtime and dependencies. Instead of manually installing software on every server, we build a versioned Docker image once and deploy that same immutable image across development, testing, and production environments. This makes deployments repeatable, simplifies rollbacks, and reduces environment-specific issues.

## What is Docker?

what i wrote initially:
Docker is an installable linux program which basically provides containers for images which are basically compilation of different tech stacks like particalr java version , mysql etc depending on the requirement of the application. 

Reviewed Answer:
Docker is a container platform that packages an application together with its runtime, libraries, and dependencies so it runs consistently across different environments.



## What is an Image?

what i wrote initially:
An image is basically a summarized snapshot of the requirements for the application that which version and what all different programs needed.

Reviewed Answer:
A Docker image is a read-only **template** containing everything needed to run an application, including the application itself, its runtime, libraries, configuration, and dependencies.

The important word is:

Template

Because **many** containers can be created from one image.

## What is a Container?

what i wrote initially:
A container is a running compilation of tech bundles pulled from an image

Reviewed Answer:
A container is a running instance of tech bundles pulled from an image

## Why do companies use Docker?
what i wrote initially:
Compnaies use docker because it bundles the requirements and makes it independent of operating systems etc , simply install docker and then plug and play . It makes the development independent of the server .

Reviewed Answer:
This answer is really good.

I especially liked:

independent of the server

That tells me you've already connected it with your own production experience.

I'd only add:

Consistent deployments
Easy scaling
Fast rollback

## Image vs Container - Java Analogy
what i wrote initially:
As per Java Analogy we can say a .jar file is the image if it is run like by 2 different services then those 2 running things can be understood as containers.

Reviewed Answer:
Excellent.

I would only make it even more accurate.
app.jar instead of .jar

