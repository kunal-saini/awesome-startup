# App hosting

- [App hosting](#app-hosting)
  - [AWS EC2](#aws-ec2)
  - [Azure App Service](#azure-app-service)
  - [Heroku](#heroku)
  - [OpeNode](#openode)
  - [OpenShift](#openshift)
  - [Vercel](#vercel)

## AWS EC2

[Product page](https://aws.amazon.com/free/)

* *Free tier*: 750 hours/month of t2.micro instances
* *Limitations*: expires 12 months after sign-up

## Azure App Service

[Pricing page](https://azure.microsoft.com/en-us/pricing/details/app-service/)

* *Free tier*: 10 applications, 1 shared core, 1GB RAM and 1GB storage per application
* *Pros*: supports .NET, easy publishing directly from Git/GitHub/Bitbucket
* *Limitations*: cumulative limit for CPU (60 minutes allowed every 24 hours), no SLA, no custom domain, no SSL

## Heroku

[Pricing page](https://www.heroku.com/pricing)

* *Free tier*: one "dyno" (512MB memory), custom domains
* *Pros*: supports multiple languages (Node.js, Ruby, Java, PHP, Python, Go, Scala or Clojure)
* *Limitations*: instance will sleep after 30 mins of inactivity

## OpeNode

[Pricing page](https://www.openode.io/pricing)
* *Free tier*: 100MB RAM, 1GB Storage, 100GB Bandwidth / Month
* *Limitations*: Your code will be open-sourced unless you declare your project is educational (for students)

## OpenShift

[Pricing page](https://www.openshift.com/pricing/index.html)

* *Free tier*: 1 project, 2GB memory, 2GB storage, no custom domain
* *Pros*: gears can be used to deploy apps in a lot of languages and/or databases, many deployment templates are provided
* *Limitations*: deployment requires installation of OpenShift app, 'idle' apps take longer to load (>30s)

[Pricing page](https://vercel.com/pricing)

* *Free tier*: 100GB bandwidth per month, 100 deployments per day, 12 serverless functions written in Node.js, Go, Python and Ruby
* *Pros*:  Next.js API endpoints are converted to serverless functions automatically. [Also see](static-app-hosting.md#vercel) for static hosting.
* *Limitations*: Free tier doesn't include commercial usage