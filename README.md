# JENKINS FILE

A Jenkinsfile is a text file that contains the definition of a Jenkins Pipeline and is checked into source control. Jenkinsfile can be defined by using a domain specific language (DSL). It is written based on two syntax’s, namely:

1. Declarative
2. Scripted

### Declarative:

Declarative pipelines are a more recent approach to the “pipeline-as-code” principle. They are quite easy to write and understand. The structure may seem to be a bit complex, but overall, it contains only a couple of basic sections. The “pipeline” block is the main block that contains the entire declaration of a pipeline. 

- pipeline – contains the whole pipeline
- agent – defines the machine that will handle this pipeline
- stages – declares the stages of the pipeline
- steps – small operations inside a particular stage

### Scripted:

Scripted pipelines were the first version of the “pipeline-as-code” principle. They were designed as a DSL build with Groovy and provide an outstanding level of power and flexibility. However, this also requires some basic knowledge of Groovy, which sometimes isn't desirable.

These kinds of pipelines have fewer restrictions on the structure. Also, they have only two basic blocks: “node” and “stage”. A “node” block specifies the machine that executes a particular pipeline, whereas the “stage” blocks are used to group steps that, when taken together, represent a separate operation. The lack of additional rules and blocks makes these pipelines quite simple to understand
