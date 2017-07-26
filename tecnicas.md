Técnicas e boas práticas
========================


Adotar
------

### Pipeline como código

Teams are pushing for automation across their environments, including their development infrastructure. Pipelines as code is defining the deployment pipeline through code instead of configuring a running CI/CD tool. LambdaCD, Drone, GoCD and Concourse are examples that allow usage of this technique. Also, configuration automation tools for CI/CD systems like GoMatic can be used to treat the deployment pipeline as code—versioned and tested.


Experimentar
------------

### Legado na caixa

Working with legacy code, especially large monoliths, is one of the most unsatisfying, high-friction experiences for developers. Although we caution against extending and actively maintaining legacy monoliths, they continue to be dependencies in our environments, and developers often underestimate the cost and time required to develop against these dependencies. To help reduce the friction, developers have used virtualized machine images or container images with Docker containers to create immutable images of legacy systems and their configurations. The intent is to contain the legacy in a box for developers to run locally and remove the need for rebuilding, reconfiguring or sharing environments. In an ideal scenario, teams that own legacy systems generate the corresponding boxed legacy images through their build pipelines, and developers can then run and orchestrate these images in their allocated sandbox more reliably. Although this approach has reduced the overall time spent by each developer, it has had limited success when the teams owning the downstream dependencies have been reluctant to create container images for others to use.


### Aplicações web progressivas 

The increase in Progressive Web Applications (PWAs) is the latest attempt to bring back the mobile web in response to users' "app fatigue". Originally proposed by Google in 2015, PWAs are web applications that take advantage of the latest technologies to combine the best of web and native mobile applications. Using a set of open standard technologies such as, service workers, the app manifest, and cache and push APIs, we can create applications that are platform independent and deliver app-like user experiences. This brings parity to web and native applications and helps mobile developers reach users beyond the walled garden of the app stores. Think of PWAs as websites that act and feel like native apps.


### API como produto

Companies have wholeheartedly embraced APIs as a way to expose business capabilities to both external and internal developers. APIs promise the ability to experiment quickly with new business ideas by recombining core capabilities. But what differentiates an API from an ordinary enterprise integration service? One difference lies in treating APIs as a product, even when the consumer is an internal system or fellow developer. Teams that build APIs should understand the needs of their customers and make the product compelling to them. Usability testing and UX research can lead to a better design and understanding of the API usage patterns and help bring a product mindset to APIs. APIs, like products, should be actively maintained and supported, and, easy to use. They should have an owner who advocates for the customer and strives for continual improvement. In our experience, product orientation is the missing ingredient that makes the difference between ordinary enterprise integration and an agile business built on a platform of APIs.


Testar
------


Estudar
-------

Em suspenso
-----------

Evitar
------
