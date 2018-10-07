# goci

## Reqs
* microservice model
* coordinated, masterless model - it may use paxos or something to coordinate cluster nodes
* stateless - all state should be written as plain text and should have options to push them to s3, and some other medium
* 100% api coverage
* can we have this integrated to apps? - self ci/cd'able apps?
* support central pipelines
* support snowflake pipelines - maybe get file from application repo itself
* event driven model
  * basic model should consider event driven functions kind of model
* easy pipeline model - may be yaml based
* templating engine - easy way to template and make it programmatic
* separate task  logic and orchestrationn logic
  * Orchestration logic may be easy to handle using yaml
  * Task logic may be written in any language (may be conncourse model?)
  * Task logic:
    * May be written as separate functions somehow
    * May be written as separate scripts
    * May be written as a library
    * Maybe written in any language?
    * plugin model - to have a common library of tasks
    
* Reports 
* No master/worker model rather all of them are cluster nodes which may act as master as well as agents
* handle type of agents based on
  * operatingn system
  * Connectivity or environments
* Multi-datacenter/region
  * Global reports 
  * May be feature to deligate jobs to other regions?
* Integration models with other tools
