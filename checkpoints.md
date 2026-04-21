# Checkpoints

###### 2026-04-15

- Creating the readme.md file with the project's briefing and first ideas

###### 2026-04-16

- Creating basic structure with HTML only for holding blog posts

###### 2026-04-21

I'm not a fan of prototyping user interfaces, neither i am good of doing those, I tried to come up with a good and simple design that could fit into the brand identity that I have previously bought. I even tried to use some AI tools like Google Stitch to get a idea on how to do things. Based on the few hours that I have used it, it is far from usable in real-world projects, i feel that it is really good to give you ideas or brainstorm things, but to create a solid UI definetively not....

The truth is, I really suck at CSS and creating UI's, I have always recurred to things like Bootstrap or any other CSS component libraries. But when the matter is creating it from scratch I have no IDEA even where to begin.

Based on that I have decided, that I'll take a course or something like that to get the foundations of UI building to solve this deficiency and become a better Developer. Thus I also decided that I'll go to the next step of deploying the blog, and later I'll come back on how to create a nice looking UI for it, based on the new things that I'm gonna learn throughout this course.

To deploy the site at cloudflare workers at first, I browsed the documentation at https://gohugo.io/host-and-deploy/host-on-cloudflare/ At the time of writing it was updated recently, in this documentation it recomends to use Cloudflare workers. But in the Cloudflare docs https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/ I found that you could do the same thing using Cloudflare Pages. Then it sparked in my mind, what is the difference between Cloudflare Workers and Cloudflare pages, and why could I use the two to do the same thing.

Side fact: this is what always bothered me in the AWS ecosystem, that you could deploy a app in 12873647683 different ways, each one more complex to understand than the other. It is never clear what are the caveats or why should you choose A over B. As a simple example: why do AWS have two services like Elasticbeanstalk and lightsail? If you compare the containers deployment of each one do the same thing, why can't they simply join these two products in a decent competitor of heroku for example?

Basically Pages is optimized for static content, it seems the equivalent of serving a static page out of s3 bucket, and workers are optimized towards computing, being the equivalent of lambda functions. Nowdays those two are kinda merged together, but for my case the framework will generate a bunch of HTML pages, so I'll stick with Cloudflare pages.
