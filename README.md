![diagrams logo](assets/img/diagrams.png)

# Diagrams

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
[![pypi version](https://badge.fury.io/py/diagrams.svg)](https://badge.fury.io/py/diagrams)
![python version](https://img.shields.io/badge/python-%3E%3D%203.6-blue?logo=python)
![Run tests](https://github.com/mingrammer/diagrams/workflows/Run%20tests/badge.svg?branch=master)
[![todos](https://badgen.net/https/api.tickgit.com/badgen/github.com/mingrammer/diagrams?label=todos)](https://www.tickgit.com/browse?repo=github.com/mingrammer/diagrams)
![contributors](https://img.shields.io/github/contributors/mingrammer/diagrams)

<a href="https://www.buymeacoffee.com/mingrammer" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

**Diagram as Code**.

Diagrams lets you draw the cloud system architecture **in Python code**. It was born for **prototyping** a new system architecture design without any design tools. You can also describe or visualize the existing system architecture as well. Diagrams currently supports main major providers including: `AWS`, `Azure`, `GCP`, `Kubernetes`, `Alibaba Cloud`, `Oracle Cloud` etc... It also supports `On-Premises` nodes, `SaaS` and major `Programming` frameworks and languages.

**Diagram as Code** also allows you to **track** the architecture diagram changes in any **version control** system.

>  NOTE: It does not control any actual cloud resources nor does it generate cloud formation or terraform code. It is just for drawing the cloud system architecture diagrams.

## Providers

![aws provider](https://img.shields.io/badge/AWS-orange?logo=amazon-aws&color=ff9900)
![azure provider](https://img.shields.io/badge/Azure-orange?logo=microsoft-azure&color=0089d6)
![gcp provider](https://img.shields.io/badge/GCP-orange?logo=google-cloud&color=4285f4)
![ibm provider](https://img.shields.io/badge/IBM-orange?logo=ibm&color=052FAD)
![kubernetes provider](https://img.shields.io/badge/Kubernetes-orange?logo=kubernetes&color=326ce5)
![alibaba cloud provider](https://img.shields.io/badge/AlibabaCloud-orange?logo=alibaba-cloud&color=ff6a00)
![oracle cloud provider](https://img.shields.io/badge/OracleCloud-orange?logo=oracle&color=f80000)
![openstack provider](https://img.shields.io/badge/OpenStack-orange?logo=openstack&color=da1a32)
![firebase provider](https://img.shields.io/badge/Firebase-orange?logo=firebase&color=FFCA28)
![digital ocean provider](https://img.shields.io/badge/DigitalOcean-0080ff?logo=digitalocean&color=0080ff)
![elastic provider](https://img.shields.io/badge/Elastic-orange?logo=elastic&color=005571)
![outscale provider](https://img.shields.io/badge/OutScale-orange?color=5f87bf)
![on premises provider](https://img.shields.io/badge/OnPremises-orange?color=5f87bf)
![generic provider](https://img.shields.io/badge/Generic-orange?color=5f87bf)
![programming provider](https://img.shields.io/badge/Programming-orange?color=5f87bf)
![saas provider](https://img.shields.io/badge/SaaS-orange?color=5f87bf)
![c4 provider](https://img.shields.io/badge/C4-orange?color=5f87bf)

## Getting Started

It requires **Python 3.7** or higher, check your Python version first.

It uses [Graphviz](https://www.graphviz.org/) to render the diagram, so you need to [install Graphviz](https://graphviz.gitlab.io/download/) to use **diagrams**. After installing graphviz (or already have it), install the **diagrams**.

> macOS users can download the Graphviz via `brew install graphviz` if you're using [Homebrew](https://brew.sh).

```shell
# using pip (pip3)
$ pip install diagrams

# using pipenv
$ pipenv install diagrams

# using poetry
$ poetry add diagrams
```

You can start with [quick start](https://diagrams.mingrammer.com/docs/getting-started/installation#quick-start). Check out [guides](https://diagrams.mingrammer.com/docs/guides/diagram) for more details, and you can find all available nodes list in [here](https://diagrams.mingrammer.com/docs/nodes/aws).

## Examples

| Event Processing                                             | Stateful Architecture                                        | Advanced Web Service                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![event processing](https://diagrams.mingrammer.com/img/event_processing_diagram.png) | ![stateful architecture](https://diagrams.mingrammer.com/img/stateful_architecture_diagram.png) | ![advanced web service with on-premises](https://diagrams.mingrammer.com/img/advanced_web_service_with_on-premises.png) |

You can find all the examples on the [examples](https://diagrams.mingrammer.com/docs/getting-started/examples) page.

## Contributing

To contribute to diagram, check out [contribution guidelines](CONTRIBUTING.md).

> Let me know if you are using diagrams! I'll add you in showcase page. (I'm working on it!) :)

## Who uses it?

[Apache Airflow](https://github.com/apache/airflow) is the most popular data workflow Orchestrator. Airflow uses Diagrams to generate architecture diagrams in their documentation.

[Cloudiscovery](https://github.com/Cloud-Architects/cloudiscovery) helps you to analyze resources in your cloud (AWS/GCP/Azure/Alibaba/IBM) account. It allows you to create a diagram of analyzed cloud resource map based on this Diagrams library, so you can draw your existing cloud infrastructure with Cloudiscovery.

[Airflow Diagrams](https://github.com/feluelle/airflow-diagrams) is an Airflow plugin that aims to easily visualise your Airflow DAGs on service level from providers like AWS, GCP, Azure, etc. via diagrams.

## Other languages

- If you are familiar with Go, you can use [go-diagrams](https://github.com/blushft/go-diagrams) as well.

## License

[MIT](LICENSE)

```
diagrams
├─ .git
│  ├─ config
│  ├─ description
│  ├─ HEAD
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  ├─ sendemail-validate.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ master
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-2b76d6c7674b20c05308dc3f3c459e940d756308.idx
│  │     ├─ pack-2b76d6c7674b20c05308dc3f3c459e940d756308.pack
│  │     └─ pack-2b76d6c7674b20c05308dc3f3c459e940d756308.rev
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ master
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .github
│  ├─ dependabot.yml
│  └─ workflows
│     ├─ codeql-analysis.yml
│     └─ test.yml
├─ .gitignore
├─ assets
│  └─ img
│     └─ diagrams.png
├─ autogen.sh
├─ CHANGELOG.md
├─ config.py
├─ CONTRIBUTING.md
├─ DEVELOPMENT.md
├─ diagrams
│  ├─ alibabacloud
│  │  ├─ analytics.py
│  │  ├─ application.py
│  │  ├─ communication.py
│  │  ├─ compute.py
│  │  ├─ database.py
│  │  ├─ iot.py
│  │  ├─ network.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  ├─ web.py
│  │  └─ __init__.py
│  ├─ aws
│  │  ├─ analytics.py
│  │  ├─ ar.py
│  │  ├─ blockchain.py
│  │  ├─ business.py
│  │  ├─ compute.py
│  │  ├─ cost.py
│  │  ├─ database.py
│  │  ├─ devtools.py
│  │  ├─ enablement.py
│  │  ├─ enduser.py
│  │  ├─ engagement.py
│  │  ├─ game.py
│  │  ├─ general.py
│  │  ├─ integration.py
│  │  ├─ iot.py
│  │  ├─ management.py
│  │  ├─ media.py
│  │  ├─ migration.py
│  │  ├─ ml.py
│  │  ├─ mobile.py
│  │  ├─ network.py
│  │  ├─ quantum.py
│  │  ├─ robotics.py
│  │  ├─ satellite.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ azure
│  │  ├─ analytics.py
│  │  ├─ compute.py
│  │  ├─ database.py
│  │  ├─ devops.py
│  │  ├─ general.py
│  │  ├─ identity.py
│  │  ├─ integration.py
│  │  ├─ iot.py
│  │  ├─ migration.py
│  │  ├─ ml.py
│  │  ├─ mobile.py
│  │  ├─ monitor.py
│  │  ├─ network.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  ├─ web.py
│  │  └─ __init__.py
│  ├─ base
│  │  └─ __init__.py
│  ├─ c4
│  │  └─ __init__.py
│  ├─ custom
│  │  └─ __init__.py
│  ├─ digitalocean
│  │  ├─ compute.py
│  │  ├─ database.py
│  │  ├─ network.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ elastic
│  │  ├─ agent.py
│  │  ├─ beats.py
│  │  ├─ elasticsearch.py
│  │  ├─ enterprisesearch.py
│  │  ├─ observability.py
│  │  ├─ orchestration.py
│  │  ├─ saas.py
│  │  ├─ security.py
│  │  └─ __init__.py
│  ├─ firebase
│  │  ├─ base.py
│  │  ├─ develop.py
│  │  ├─ extentions.py
│  │  ├─ grow.py
│  │  ├─ quality.py
│  │  └─ __init__.py
│  ├─ gcp
│  │  ├─ analytics.py
│  │  ├─ api.py
│  │  ├─ compute.py
│  │  ├─ database.py
│  │  ├─ devtools.py
│  │  ├─ iot.py
│  │  ├─ migration.py
│  │  ├─ ml.py
│  │  ├─ network.py
│  │  ├─ operations.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ generic
│  │  ├─ blank.py
│  │  ├─ compute.py
│  │  ├─ database.py
│  │  ├─ device.py
│  │  ├─ network.py
│  │  ├─ os.py
│  │  ├─ place.py
│  │  ├─ storage.py
│  │  ├─ virtualization.py
│  │  └─ __init__.py
│  ├─ ibm
│  │  ├─ analytics.py
│  │  ├─ applications.py
│  │  ├─ blockchain.py
│  │  ├─ compute.py
│  │  ├─ data.py
│  │  ├─ devops.py
│  │  ├─ general.py
│  │  ├─ infrastructure.py
│  │  ├─ management.py
│  │  ├─ network.py
│  │  ├─ security.py
│  │  ├─ social.py
│  │  ├─ storage.py
│  │  ├─ user.py
│  │  └─ __init__.py
│  ├─ k8s
│  │  ├─ chaos.py
│  │  ├─ clusterconfig.py
│  │  ├─ compute.py
│  │  ├─ controlplane.py
│  │  ├─ ecosystem.py
│  │  ├─ group.py
│  │  ├─ infra.py
│  │  ├─ network.py
│  │  ├─ others.py
│  │  ├─ podconfig.py
│  │  ├─ rbac.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ oci
│  │  ├─ compute.py
│  │  ├─ connectivity.py
│  │  ├─ database.py
│  │  ├─ devops.py
│  │  ├─ governance.py
│  │  ├─ monitoring.py
│  │  ├─ network.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ onprem
│  │  ├─ aggregator.py
│  │  ├─ analytics.py
│  │  ├─ auth.py
│  │  ├─ cd.py
│  │  ├─ certificates.py
│  │  ├─ ci.py
│  │  ├─ client.py
│  │  ├─ compute.py
│  │  ├─ container.py
│  │  ├─ database.py
│  │  ├─ dns.py
│  │  ├─ etl.py
│  │  ├─ gitops.py
│  │  ├─ groupware.py
│  │  ├─ iac.py
│  │  ├─ identity.py
│  │  ├─ inmemory.py
│  │  ├─ logging.py
│  │  ├─ messaging.py
│  │  ├─ mlops.py
│  │  ├─ monitoring.py
│  │  ├─ network.py
│  │  ├─ proxmox.py
│  │  ├─ queue.py
│  │  ├─ registry.py
│  │  ├─ search.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  ├─ tracing.py
│  │  ├─ vcs.py
│  │  ├─ workflow.py
│  │  └─ __init__.py
│  ├─ openstack
│  │  ├─ adjacentenablers.py
│  │  ├─ apiproxies.py
│  │  ├─ applicationlifecycle.py
│  │  ├─ baremetal.py
│  │  ├─ billing.py
│  │  ├─ compute.py
│  │  ├─ containerservices.py
│  │  ├─ deployment.py
│  │  ├─ frontend.py
│  │  ├─ lifecyclemanagement.py
│  │  ├─ monitoring.py
│  │  ├─ multiregion.py
│  │  ├─ networking.py
│  │  ├─ nfv.py
│  │  ├─ operations.py
│  │  ├─ optimization.py
│  │  ├─ orchestration.py
│  │  ├─ packaging.py
│  │  ├─ sharedservices.py
│  │  ├─ storage.py
│  │  ├─ user.py
│  │  ├─ workloadprovisioning.py
│  │  └─ __init__.py
│  ├─ outscale
│  │  ├─ compute.py
│  │  ├─ network.py
│  │  ├─ security.py
│  │  ├─ storage.py
│  │  └─ __init__.py
│  ├─ programming
│  │  ├─ flowchart.py
│  │  ├─ framework.py
│  │  ├─ language.py
│  │  ├─ runtime.py
│  │  └─ __init__.py
│  ├─ saas
│  │  ├─ alerting.py
│  │  ├─ analytics.py
│  │  ├─ cdn.py
│  │  ├─ chat.py
│  │  ├─ communication.py
│  │  ├─ filesharing.py
│  │  ├─ identity.py
│  │  ├─ logging.py
│  │  ├─ media.py
│  │  ├─ recommendation.py
│  │  ├─ social.py
│  │  └─ __init__.py
│  └─ __init__.py
├─ docker
│  └─ dev
│     └─ Dockerfile
├─ docs
│  ├─ getting-started
│  │  ├─ examples.md
│  │  └─ installation.md
│  ├─ guides
│  │  ├─ cluster.md
│  │  ├─ diagram.md
│  │  ├─ edge.md
│  │  └─ node.md
│  └─ nodes
│     ├─ alibabacloud.md
│     ├─ aws.md
│     ├─ azure.md
│     ├─ c4.md
│     ├─ custom.md
│     ├─ digitalocean.md
│     ├─ elastic.md
│     ├─ firebase.md
│     ├─ gcp.md
│     ├─ generic.md
│     ├─ ibm.md
│     ├─ k8s.md
│     ├─ oci.md
│     ├─ onprem.md
│     ├─ openstack.md
│     ├─ outscale.md
│     ├─ programming.md
│     └─ saas.md
├─ graphviz
│  ├─ backend
│  │  ├─ dot_command.py
│  │  ├─ execute.py
│  │  ├─ mixins.py
│  │  ├─ piping.py
│  │  ├─ rendering.py
│  │  ├─ unflattening.py
│  │  ├─ upstream_version.py
│  │  ├─ viewing.py
│  │  └─ __init__.py
│  ├─ base.py
│  ├─ copying.py
│  ├─ dot.py
│  ├─ encoding.py
│  ├─ exceptions.py
│  ├─ graphs.py
│  ├─ jupyter_integration.py
│  ├─ parameters
│  │  ├─ base.py
│  │  ├─ engines.py
│  │  ├─ formats.py
│  │  ├─ formatters.py
│  │  ├─ mixins.py
│  │  ├─ renderers.py
│  │  └─ __init__.py
│  ├─ piping.py
│  ├─ quoting.py
│  ├─ rendering.py
│  ├─ saving.py
│  ├─ sources.py
│  ├─ unflattening.py
│  ├─ _compat.py
│  ├─ _defaults.py
│  ├─ _tools.py
│  └─ __init__.py
├─ jinja2
│  ├─ async_utils.py
│  ├─ bccache.py
│  ├─ compiler.py
│  ├─ constants.py
│  ├─ debug.py
│  ├─ defaults.py
│  ├─ environment.py
│  ├─ exceptions.py
│  ├─ ext.py
│  ├─ filters.py
│  ├─ idtracking.py
│  ├─ lexer.py
│  ├─ loaders.py
│  ├─ meta.py
│  ├─ nativetypes.py
│  ├─ nodes.py
│  ├─ optimizer.py
│  ├─ parser.py
│  ├─ py.typed
│  ├─ runtime.py
│  ├─ sandbox.py
│  ├─ tests.py
│  ├─ utils.py
│  ├─ visitor.py
│  ├─ _identifier.py
│  └─ __init__.py
├─ LICENSE
├─ markupsafe
│  ├─ py.typed
│  ├─ _native.py
│  ├─ _speedups.c
│  ├─ _speedups.cp311-win_amd64.pyd
│  ├─ _speedups.pyi
│  └─ __init__.py
├─ poetry.lock
├─ pyproject.toml
├─ README.md
├─ resources
│  ├─ alibabacloud
│  │  ├─ analytics
│  │  │  ├─ analytic-db.png
│  │  │  ├─ click-house.png
│  │  │  ├─ data-lake-analytics.png
│  │  │  ├─ elatic-map-reduce.png
│  │  │  └─ open-search.png
│  │  ├─ application
│  │  │  ├─ api-gateway.png
│  │  │  ├─ bee-bot.png
│  │  │  ├─ blockchain-as-a-service.png
│  │  │  ├─ cloud-call-center.png
│  │  │  ├─ code-pipeline.png
│  │  │  ├─ direct-mail.png
│  │  │  ├─ log-service.png
│  │  │  ├─ message-notification-service.png
│  │  │  ├─ node-js-performance-platform.png
│  │  │  ├─ open-search.png
│  │  │  ├─ performance-testing-service.png
│  │  │  ├─ rd-cloud.png
│  │  │  ├─ smart-conversation-analysis.png
│  │  │  └─ yida.png
│  │  ├─ communication
│  │  │  ├─ direct-mail.png
│  │  │  └─ mobile-push.png
│  │  ├─ compute
│  │  │  ├─ auto-scaling.png
│  │  │  ├─ batch-compute.png
│  │  │  ├─ container-registry.png
│  │  │  ├─ container-service.png
│  │  │  ├─ elastic-compute-service.png
│  │  │  ├─ elastic-container-instance.png
│  │  │  ├─ elastic-high-performance-computing.png
│  │  │  ├─ elastic-search.png
│  │  │  ├─ function-compute.png
│  │  │  ├─ operation-orchestration-service.png
│  │  │  ├─ resource-orchestration-service.png
│  │  │  ├─ server-load-balancer.png
│  │  │  ├─ serverless-app-engine.png
│  │  │  ├─ simple-application-server.png
│  │  │  └─ web-app-service.png
│  │  ├─ database
│  │  │  ├─ apsaradb-cassandra.png
│  │  │  ├─ apsaradb-hbase.png
│  │  │  ├─ apsaradb-memcache.png
│  │  │  ├─ apsaradb-mongodb.png
│  │  │  ├─ apsaradb-oceanbase.png
│  │  │  ├─ apsaradb-polardb.png
│  │  │  ├─ apsaradb-postgresql.png
│  │  │  ├─ apsaradb-ppas.png
│  │  │  ├─ apsaradb-redis.png
│  │  │  ├─ apsaradb-sqlserver.png
│  │  │  ├─ data-management-service.png
│  │  │  ├─ data-transmission-service.png
│  │  │  ├─ database-backup-service.png
│  │  │  ├─ disribute-relational-database-service.png
│  │  │  ├─ graph-database-service.png
│  │  │  ├─ hybriddb-for-mysql.png
│  │  │  └─ relational-database-service.png
│  │  ├─ iot
│  │  │  ├─ iot-internet-device-id.png
│  │  │  ├─ iot-link-wan.png
│  │  │  ├─ iot-mobile-connection-package.png
│  │  │  └─ iot-platform.png
│  │  ├─ network
│  │  │  ├─ cdn.png
│  │  │  ├─ cloud-enterprise-network.png
│  │  │  ├─ elastic-ip-address.png
│  │  │  ├─ express-connect.png
│  │  │  ├─ nat-gateway.png
│  │  │  ├─ server-load-balancer.png
│  │  │  ├─ smart-access-gateway.png
│  │  │  ├─ virtual-private-cloud.png
│  │  │  └─ vpn-gateway.png
│  │  ├─ security
│  │  │  ├─ anti-bot-service.png
│  │  │  ├─ anti-ddos-basic.png
│  │  │  ├─ anti-ddos-pro.png
│  │  │  ├─ antifraud-service.png
│  │  │  ├─ bastion-host.png
│  │  │  ├─ cloud-firewall.png
│  │  │  ├─ cloud-security-scanner.png
│  │  │  ├─ content-moderation.png
│  │  │  ├─ crowdsourced-security-testing.png
│  │  │  ├─ data-encryption-service.png
│  │  │  ├─ db-audit.png
│  │  │  ├─ game-shield.png
│  │  │  ├─ id-verification.png
│  │  │  ├─ managed-security-service.png
│  │  │  ├─ security-center.png
│  │  │  ├─ server-guard.png
│  │  │  ├─ ssl-certificates.png
│  │  │  └─ web-application-firewall.png
│  │  ├─ storage
│  │  │  ├─ cloud-storage-gateway.png
│  │  │  ├─ file-storage-hdfs.png
│  │  │  ├─ file-storage-nas.png
│  │  │  ├─ hybrid-backup-recovery.png
│  │  │  ├─ hybrid-cloud-disaster-recovery.png
│  │  │  ├─ imm.png
│  │  │  ├─ object-storage-service.png
│  │  │  └─ object-table-store.png
│  │  └─ web
│  │     ├─ dns.png
│  │     └─ domain.png
│  ├─ aws
│  │  ├─ analytics
│  │  │  ├─ amazon-opensearch-service.png
│  │  │  ├─ analytics.png
│  │  │  ├─ athena.png
│  │  │  ├─ cloudsearch-search-documents.png
│  │  │  ├─ cloudsearch.png
│  │  │  ├─ data-lake-resource.png
│  │  │  ├─ data-pipeline.png
│  │  │  ├─ elasticsearch-service.png
│  │  │  ├─ emr-cluster.png
│  │  │  ├─ emr-engine-mapr-m3.png
│  │  │  ├─ emr-engine-mapr-m5.png
│  │  │  ├─ emr-engine-mapr-m7.png
│  │  │  ├─ emr-engine.png
│  │  │  ├─ emr-hdfs-cluster.png
│  │  │  ├─ emr.png
│  │  │  ├─ glue-crawlers.png
│  │  │  ├─ glue-data-catalog.png
│  │  │  ├─ glue.png
│  │  │  ├─ kinesis-data-analytics.png
│  │  │  ├─ kinesis-data-firehose.png
│  │  │  ├─ kinesis-data-streams.png
│  │  │  ├─ kinesis-video-streams.png
│  │  │  ├─ kinesis.png
│  │  │  ├─ lake-formation.png
│  │  │  ├─ managed-streaming-for-kafka.png
│  │  │  ├─ quicksight.png
│  │  │  ├─ redshift-dense-compute-node.png
│  │  │  ├─ redshift-dense-storage-node.png
│  │  │  └─ redshift.png
│  │  ├─ ar
│  │  │  ├─ ar-vr.png
│  │  │  └─ sumerian.png
│  │  ├─ blockchain
│  │  │  ├─ blockchain-resource.png
│  │  │  ├─ blockchain.png
│  │  │  ├─ managed-blockchain.png
│  │  │  └─ quantum-ledger-database-qldb.png
│  │  ├─ business
│  │  │  ├─ alexa-for-business.png
│  │  │  ├─ business-applications.png
│  │  │  ├─ chime.png
│  │  │  └─ workmail.png
│  │  ├─ compute
│  │  │  ├─ app-runner.png
│  │  │  ├─ application-auto-scaling-rounded.png
│  │  │  ├─ application-auto-scaling.png
│  │  │  ├─ batch-rounded.png
│  │  │  ├─ batch.png
│  │  │  ├─ compute-optimizer.png
│  │  │  ├─ compute-rounded.png
│  │  │  ├─ compute.png
│  │  │  ├─ ec2-ami.png
│  │  │  ├─ ec2-auto-scaling.png
│  │  │  ├─ ec2-container-registry-image.png
│  │  │  ├─ ec2-container-registry-registry.png
│  │  │  ├─ ec2-container-registry-rounded.png
│  │  │  ├─ ec2-container-registry.png
│  │  │  ├─ ec2-elastic-ip-address.png
│  │  │  ├─ ec2-image-builder.png
│  │  │  ├─ ec2-instance.png
│  │  │  ├─ ec2-instances.png
│  │  │  ├─ ec2-rescue.png
│  │  │  ├─ ec2-rounded.png
│  │  │  ├─ ec2-spot-instance.png
│  │  │  ├─ ec2.png
│  │  │  ├─ elastic-beanstalk-application.png
│  │  │  ├─ elastic-beanstalk-deployment.png
│  │  │  ├─ elastic-beanstalk-rounded.png
│  │  │  ├─ elastic-beanstalk.png
│  │  │  ├─ elastic-container-service-container.png
│  │  │  ├─ elastic-container-service-rounded.png
│  │  │  ├─ elastic-container-service-service.png
│  │  │  ├─ elastic-container-service.png
│  │  │  ├─ elastic-kubernetes-service-rounded.png
│  │  │  ├─ elastic-kubernetes-service.png
│  │  │  ├─ fargate-rounded.png
│  │  │  ├─ fargate.png
│  │  │  ├─ lambda-function.png
│  │  │  ├─ lambda-rounded.png
│  │  │  ├─ lambda.png
│  │  │  ├─ lightsail-rounded.png
│  │  │  ├─ lightsail.png
│  │  │  ├─ local-zones.png
│  │  │  ├─ outposts-rounded.png
│  │  │  ├─ outposts.png
│  │  │  ├─ serverless-application-repository-rounded.png
│  │  │  ├─ serverless-application-repository.png
│  │  │  ├─ thinkbox-deadline-rounded.png
│  │  │  ├─ thinkbox-deadline.png
│  │  │  ├─ thinkbox-draft-rounded.png
│  │  │  ├─ thinkbox-draft.png
│  │  │  ├─ thinkbox-frost-rounded.png
│  │  │  ├─ thinkbox-frost.png
│  │  │  ├─ thinkbox-krakatoa-rounded.png
│  │  │  ├─ thinkbox-krakatoa.png
│  │  │  ├─ thinkbox-sequoia-rounded.png
│  │  │  ├─ thinkbox-sequoia.png
│  │  │  ├─ thinkbox-stoke-rounded.png
│  │  │  ├─ thinkbox-stoke.png
│  │  │  ├─ thinkbox-xmesh-rounded.png
│  │  │  ├─ thinkbox-xmesh.png
│  │  │  ├─ vmware-cloud-on-aws-rounded.png
│  │  │  ├─ vmware-cloud-on-aws.png
│  │  │  └─ wavelength.png
│  │  ├─ cost
│  │  │  ├─ budgets.png
│  │  │  ├─ cost-and-usage-report.png
│  │  │  ├─ cost-explorer.png
│  │  │  ├─ cost-management.png
│  │  │  ├─ reserved-instance-reporting.png
│  │  │  └─ savings-plans.png
│  │  ├─ database
│  │  │  ├─ aurora-instance.png
│  │  │  ├─ aurora.png
│  │  │  ├─ database-migration-service-database-migration-workflow.png
│  │  │  ├─ database-migration-service.png
│  │  │  ├─ database.png
│  │  │  ├─ documentdb-mongodb-compatibility.png
│  │  │  ├─ dynamodb-attribute.png
│  │  │  ├─ dynamodb-attributes.png
│  │  │  ├─ dynamodb-dax.png
│  │  │  ├─ dynamodb-global-secondary-index.png
│  │  │  ├─ dynamodb-item.png
│  │  │  ├─ dynamodb-items.png
│  │  │  ├─ dynamodb-table.png
│  │  │  ├─ dynamodb.png
│  │  │  ├─ elasticache-cache-node.png
│  │  │  ├─ elasticache-for-memcached.png
│  │  │  ├─ elasticache-for-redis.png
│  │  │  ├─ elasticache.png
│  │  │  ├─ keyspaces-managed-apache-cassandra-service.png
│  │  │  ├─ neptune.png
│  │  │  ├─ quantum-ledger-database-qldb.png
│  │  │  ├─ rds-instance.png
│  │  │  ├─ rds-mariadb-instance.png
│  │  │  ├─ rds-mysql-instance.png
│  │  │  ├─ rds-on-vmware.png
│  │  │  ├─ rds-oracle-instance.png
│  │  │  ├─ rds-postgresql-instance.png
│  │  │  ├─ rds-sql-server-instance.png
│  │  │  ├─ rds.png
│  │  │  ├─ redshift-dense-compute-node.png
│  │  │  ├─ redshift-dense-storage-node.png
│  │  │  ├─ redshift.png
│  │  │  └─ timestream.png
│  │  ├─ devtools
│  │  │  ├─ cloud-development-kit.png
│  │  │  ├─ cloud9-resource.png
│  │  │  ├─ cloud9.png
│  │  │  ├─ codeartifact.png
│  │  │  ├─ codebuild.png
│  │  │  ├─ codecommit.png
│  │  │  ├─ codedeploy.png
│  │  │  ├─ codepipeline.png
│  │  │  ├─ codestar.png
│  │  │  ├─ command-line-interface.png
│  │  │  ├─ developer-tools.png
│  │  │  ├─ tools-and-sdks.png
│  │  │  └─ x-ray.png
│  │  ├─ enablement
│  │  │  ├─ customer-enablement.png
│  │  │  ├─ iq.png
│  │  │  ├─ managed-services.png
│  │  │  ├─ professional-services.png
│  │  │  └─ support.png
│  │  ├─ enduser
│  │  │  ├─ appstream-2-0.png
│  │  │  ├─ desktop-and-app-streaming.png
│  │  │  ├─ workdocs.png
│  │  │  ├─ worklink.png
│  │  │  └─ workspaces.png
│  │  ├─ engagement
│  │  │  ├─ connect.png
│  │  │  ├─ customer-engagement.png
│  │  │  ├─ pinpoint.png
│  │  │  ├─ simple-email-service-ses-email.png
│  │  │  └─ simple-email-service-ses.png
│  │  ├─ game
│  │  │  ├─ game-tech.png
│  │  │  └─ gamelift.png
│  │  ├─ general
│  │  │  ├─ client.png
│  │  │  ├─ disk.png
│  │  │  ├─ forums.png
│  │  │  ├─ general.png
│  │  │  ├─ generic-database.png
│  │  │  ├─ generic-firewall.png
│  │  │  ├─ generic-office-building.png
│  │  │  ├─ generic-saml-token.png
│  │  │  ├─ generic-sdk.png
│  │  │  ├─ internet-alt1.png
│  │  │  ├─ internet-alt2.png
│  │  │  ├─ internet-gateway.png
│  │  │  ├─ marketplace.png
│  │  │  ├─ mobile-client.png
│  │  │  ├─ multimedia.png
│  │  │  ├─ office-building.png
│  │  │  ├─ saml-token.png
│  │  │  ├─ sdk.png
│  │  │  ├─ ssl-padlock.png
│  │  │  ├─ tape-storage.png
│  │  │  ├─ toolkit.png
│  │  │  ├─ traditional-server.png
│  │  │  ├─ user.png
│  │  │  └─ users.png
│  │  ├─ integration
│  │  │  ├─ application-integration.png
│  │  │  ├─ appsync.png
│  │  │  ├─ console-mobile-application.png
│  │  │  ├─ event-resource.png
│  │  │  ├─ eventbridge-custom-event-bus-resource.png
│  │  │  ├─ eventbridge-default-event-bus-resource.png
│  │  │  ├─ eventbridge-saas-partner-event-bus-resource.png
│  │  │  ├─ eventbridge.png
│  │  │  ├─ express-workflows.png
│  │  │  ├─ mq.png
│  │  │  ├─ simple-notification-service-sns-email-notification.png
│  │  │  ├─ simple-notification-service-sns-http-notification.png
│  │  │  ├─ simple-notification-service-sns-topic.png
│  │  │  ├─ simple-notification-service-sns.png
│  │  │  ├─ simple-queue-service-sqs-message.png
│  │  │  ├─ simple-queue-service-sqs-queue.png
│  │  │  ├─ simple-queue-service-sqs.png
│  │  │  └─ step-functions.png
│  │  ├─ iot
│  │  │  ├─ freertos.png
│  │  │  ├─ internet-of-things.png
│  │  │  ├─ iot-1-click.png
│  │  │  ├─ iot-action.png
│  │  │  ├─ iot-actuator.png
│  │  │  ├─ iot-alexa-echo.png
│  │  │  ├─ iot-alexa-enabled-device.png
│  │  │  ├─ iot-alexa-skill.png
│  │  │  ├─ iot-alexa-voice-service.png
│  │  │  ├─ iot-analytics-channel.png
│  │  │  ├─ iot-analytics-data-set.png
│  │  │  ├─ iot-analytics-data-store.png
│  │  │  ├─ iot-analytics-notebook.png
│  │  │  ├─ iot-analytics-pipeline.png
│  │  │  ├─ iot-analytics.png
│  │  │  ├─ iot-bank.png
│  │  │  ├─ iot-bicycle.png
│  │  │  ├─ iot-button.png
│  │  │  ├─ iot-camera.png
│  │  │  ├─ iot-car.png
│  │  │  ├─ iot-cart.png
│  │  │  ├─ iot-certificate.png
│  │  │  ├─ iot-coffee-pot.png
│  │  │  ├─ iot-core.png
│  │  │  ├─ iot-desired-state.png
│  │  │  ├─ iot-device-defender.png
│  │  │  ├─ iot-device-gateway.png
│  │  │  ├─ iot-device-management.png
│  │  │  ├─ iot-door-lock.png
│  │  │  ├─ iot-events.png
│  │  │  ├─ iot-factory.png
│  │  │  ├─ iot-fire-tv-stick.png
│  │  │  ├─ iot-fire-tv.png
│  │  │  ├─ iot-generic.png
│  │  │  ├─ iot-greengrass-connector.png
│  │  │  ├─ iot-greengrass.png
│  │  │  ├─ iot-hardware-board.png
│  │  │  ├─ iot-house.png
│  │  │  ├─ iot-http.png
│  │  │  ├─ iot-http2.png
│  │  │  ├─ iot-jobs.png
│  │  │  ├─ iot-lambda.png
│  │  │  ├─ iot-lightbulb.png
│  │  │  ├─ iot-medical-emergency.png
│  │  │  ├─ iot-mqtt.png
│  │  │  ├─ iot-over-the-air-update.png
│  │  │  ├─ iot-policy-emergency.png
│  │  │  ├─ iot-policy.png
│  │  │  ├─ iot-reported-state.png
│  │  │  ├─ iot-rule.png
│  │  │  ├─ iot-sensor.png
│  │  │  ├─ iot-servo.png
│  │  │  ├─ iot-shadow.png
│  │  │  ├─ iot-simulator.png
│  │  │  ├─ iot-sitewise.png
│  │  │  ├─ iot-thermostat.png
│  │  │  ├─ iot-things-graph.png
│  │  │  ├─ iot-topic.png
│  │  │  ├─ iot-travel.png
│  │  │  ├─ iot-utility.png
│  │  │  └─ iot-windfarm.png
│  │  ├─ management
│  │  │  ├─ amazon-devops-guru.png
│  │  │  ├─ amazon-managed-grafana.png
│  │  │  ├─ amazon-managed-prometheus.png
│  │  │  ├─ amazon-managed-workflows-apache-airflow.png
│  │  │  ├─ auto-scaling.png
│  │  │  ├─ chatbot.png
│  │  │  ├─ cloudformation-change-set.png
│  │  │  ├─ cloudformation-stack.png
│  │  │  ├─ cloudformation-template.png
│  │  │  ├─ cloudformation.png
│  │  │  ├─ cloudtrail.png
│  │  │  ├─ cloudwatch-alarm.png
│  │  │  ├─ cloudwatch-event-event-based.png
│  │  │  ├─ cloudwatch-event-time-based.png
│  │  │  ├─ cloudwatch-rule.png
│  │  │  ├─ cloudwatch.png
│  │  │  ├─ codeguru.png
│  │  │  ├─ command-line-interface.png
│  │  │  ├─ config.png
│  │  │  ├─ control-tower.png
│  │  │  ├─ license-manager.png
│  │  │  ├─ managed-services.png
│  │  │  ├─ management-and-governance.png
│  │  │  ├─ management-console.png
│  │  │  ├─ opsworks-apps.png
│  │  │  ├─ opsworks-deployments.png
│  │  │  ├─ opsworks-instances.png
│  │  │  ├─ opsworks-layers.png
│  │  │  ├─ opsworks-monitoring.png
│  │  │  ├─ opsworks-permissions.png
│  │  │  ├─ opsworks-resources.png
│  │  │  ├─ opsworks-stack.png
│  │  │  ├─ opsworks.png
│  │  │  ├─ organizations-account.png
│  │  │  ├─ organizations-organizational-unit.png
│  │  │  ├─ organizations.png
│  │  │  ├─ personal-health-dashboard.png
│  │  │  ├─ proton.png
│  │  │  ├─ service-catalog.png
│  │  │  ├─ systems-manager-app-config.png
│  │  │  ├─ systems-manager-automation.png
│  │  │  ├─ systems-manager-documents.png
│  │  │  ├─ systems-manager-inventory.png
│  │  │  ├─ systems-manager-maintenance-windows.png
│  │  │  ├─ systems-manager-opscenter.png
│  │  │  ├─ systems-manager-parameter-store.png
│  │  │  ├─ systems-manager-patch-manager.png
│  │  │  ├─ systems-manager-run-command.png
│  │  │  ├─ systems-manager-state-manager.png
│  │  │  ├─ systems-manager.png
│  │  │  ├─ trusted-advisor-checklist-cost.png
│  │  │  ├─ trusted-advisor-checklist-fault-tolerant.png
│  │  │  ├─ trusted-advisor-checklist-performance.png
│  │  │  ├─ trusted-advisor-checklist-security.png
│  │  │  ├─ trusted-advisor-checklist.png
│  │  │  ├─ trusted-advisor.png
│  │  │  └─ well-architected-tool.png
│  │  ├─ media
│  │  │  ├─ elastic-transcoder.png
│  │  │  ├─ elemental-conductor.png
│  │  │  ├─ elemental-delta.png
│  │  │  ├─ elemental-live.png
│  │  │  ├─ elemental-mediaconnect.png
│  │  │  ├─ elemental-mediaconvert.png
│  │  │  ├─ elemental-medialive.png
│  │  │  ├─ elemental-mediapackage.png
│  │  │  ├─ elemental-mediastore.png
│  │  │  ├─ elemental-mediatailor.png
│  │  │  ├─ elemental-server.png
│  │  │  ├─ kinesis-video-streams.png
│  │  │  └─ media-services.png
│  │  ├─ migration
│  │  │  ├─ application-discovery-service.png
│  │  │  ├─ cloudendure-migration.png
│  │  │  ├─ database-migration-service.png
│  │  │  ├─ datasync-agent.png
│  │  │  ├─ datasync.png
│  │  │  ├─ migration-and-transfer.png
│  │  │  ├─ migration-hub.png
│  │  │  ├─ server-migration-service.png
│  │  │  ├─ snowball-edge.png
│  │  │  ├─ snowball.png
│  │  │  ├─ snowmobile.png
│  │  │  └─ transfer-for-sftp.png
│  │  ├─ ml
│  │  │  ├─ apache-mxnet-on-aws.png
│  │  │  ├─ augmented-ai.png
│  │  │  ├─ comprehend.png
│  │  │  ├─ deep-learning-amis.png
│  │  │  ├─ deep-learning-containers.png
│  │  │  ├─ deepcomposer.png
│  │  │  ├─ deeplens.png
│  │  │  ├─ deepracer.png
│  │  │  ├─ elastic-inference.png
│  │  │  ├─ forecast.png
│  │  │  ├─ fraud-detector.png
│  │  │  ├─ kendra.png
│  │  │  ├─ lex.png
│  │  │  ├─ machine-learning.png
│  │  │  ├─ personalize.png
│  │  │  ├─ polly.png
│  │  │  ├─ rekognition-image.png
│  │  │  ├─ rekognition-video.png
│  │  │  ├─ rekognition.png
│  │  │  ├─ sagemaker-ground-truth.png
│  │  │  ├─ sagemaker-model.png
│  │  │  ├─ sagemaker-notebook.png
│  │  │  ├─ sagemaker-training-job.png
│  │  │  ├─ sagemaker.png
│  │  │  ├─ tensorflow-on-aws.png
│  │  │  ├─ textract.png
│  │  │  ├─ transcribe.png
│  │  │  └─ translate.png
│  │  ├─ mobile
│  │  │  ├─ amplify.png
│  │  │  ├─ api-gateway-endpoint.png
│  │  │  ├─ api-gateway.png
│  │  │  ├─ appsync.png
│  │  │  ├─ device-farm.png
│  │  │  ├─ mobile.png
│  │  │  └─ pinpoint.png
│  │  ├─ network
│  │  │  ├─ api-gateway-endpoint.png
│  │  │  ├─ api-gateway.png
│  │  │  ├─ app-mesh.png
│  │  │  ├─ client-vpn.png
│  │  │  ├─ cloud-map.png
│  │  │  ├─ cloudfront-edge-location.png
│  │  │  ├─ cloudfront.png
│  │  │  ├─ direct-connect.png
│  │  │  ├─ elastic-load-balancing.png
│  │  │  ├─ elb-application-load-balancer.png
│  │  │  ├─ elb-classic-load-balancer.png
│  │  │  ├─ elb-network-load-balancer.png
│  │  │  ├─ endpoint.png
│  │  │  ├─ global-accelerator.png
│  │  │  ├─ internet-gateway.png
│  │  │  ├─ nacl.png
│  │  │  ├─ nat-gateway.png
│  │  │  ├─ network-firewall.png
│  │  │  ├─ networking-and-content-delivery.png
│  │  │  ├─ private-subnet.png
│  │  │  ├─ privatelink.png
│  │  │  ├─ public-subnet.png
│  │  │  ├─ route-53-hosted-zone.png
│  │  │  ├─ route-53.png
│  │  │  ├─ route-table.png
│  │  │  ├─ site-to-site-vpn.png
│  │  │  ├─ transit-gateway.png
│  │  │  ├─ vpc-customer-gateway.png
│  │  │  ├─ vpc-elastic-network-adapter.png
│  │  │  ├─ vpc-elastic-network-interface.png
│  │  │  ├─ vpc-flow-logs.png
│  │  │  ├─ vpc-peering.png
│  │  │  ├─ vpc-router.png
│  │  │  ├─ vpc-traffic-mirroring.png
│  │  │  ├─ vpc.png
│  │  │  ├─ vpn-connection.png
│  │  │  └─ vpn-gateway.png
│  │  ├─ quantum
│  │  │  ├─ braket.png
│  │  │  └─ quantum-technologies.png
│  │  ├─ robotics
│  │  │  ├─ robomaker-cloud-extension-ros.png
│  │  │  ├─ robomaker-development-environment.png
│  │  │  ├─ robomaker-fleet-management.png
│  │  │  ├─ robomaker-simulator.png
│  │  │  ├─ robomaker.png
│  │  │  └─ robotics.png
│  │  ├─ satellite
│  │  │  ├─ ground-station.png
│  │  │  └─ satellite.png
│  │  ├─ security
│  │  │  ├─ ad-connector.png
│  │  │  ├─ artifact.png
│  │  │  ├─ certificate-authority.png
│  │  │  ├─ certificate-manager.png
│  │  │  ├─ cloud-directory.png
│  │  │  ├─ cloudhsm.png
│  │  │  ├─ cognito.png
│  │  │  ├─ detective.png
│  │  │  ├─ directory-service.png
│  │  │  ├─ firewall-manager.png
│  │  │  ├─ guardduty.png
│  │  │  ├─ identity-and-access-management-iam-access-analyzer.png
│  │  │  ├─ identity-and-access-management-iam-add-on.png
│  │  │  ├─ identity-and-access-management-iam-aws-sts-alternate.png
│  │  │  ├─ identity-and-access-management-iam-aws-sts.png
│  │  │  ├─ identity-and-access-management-iam-data-encryption-key.png
│  │  │  ├─ identity-and-access-management-iam-encrypted-data.png
│  │  │  ├─ identity-and-access-management-iam-long-term-security-credential.png
│  │  │  ├─ identity-and-access-management-iam-mfa-token.png
│  │  │  ├─ identity-and-access-management-iam-permissions.png
│  │  │  ├─ identity-and-access-management-iam-role.png
│  │  │  ├─ identity-and-access-management-iam-temporary-security-credential.png
│  │  │  ├─ identity-and-access-management-iam.png
│  │  │  ├─ inspector-agent.png
│  │  │  ├─ inspector.png
│  │  │  ├─ key-management-service.png
│  │  │  ├─ macie.png
│  │  │  ├─ managed-microsoft-ad.png
│  │  │  ├─ resource-access-manager.png
│  │  │  ├─ secrets-manager.png
│  │  │  ├─ security-hub-finding.png
│  │  │  ├─ security-hub.png
│  │  │  ├─ security-identity-and-compliance.png
│  │  │  ├─ shield-advanced.png
│  │  │  ├─ shield.png
│  │  │  ├─ simple-ad.png
│  │  │  ├─ single-sign-on.png
│  │  │  ├─ waf-filtering-rule.png
│  │  │  └─ waf.png
│  │  └─ storage
│  │     ├─ backup.png
│  │     ├─ cloudendure-disaster-recovery.png
│  │     ├─ efs-infrequentaccess-primary-bg.png
│  │     ├─ efs-standard-primary-bg.png
│  │     ├─ elastic-block-store-ebs-snapshot.png
│  │     ├─ elastic-block-store-ebs-volume.png
│  │     ├─ elastic-block-store-ebs.png
│  │     ├─ elastic-file-system-efs-file-system.png
│  │     ├─ elastic-file-system-efs.png
│  │     ├─ fsx-for-lustre.png
│  │     ├─ fsx-for-windows-file-server.png
│  │     ├─ fsx.png
│  │     ├─ multiple-volumes-resource.png
│  │     ├─ s3-glacier-archive.png
│  │     ├─ s3-glacier-vault.png
│  │     ├─ s3-glacier.png
│  │     ├─ simple-storage-service-s3-bucket-with-objects.png
│  │     ├─ simple-storage-service-s3-bucket.png
│  │     ├─ simple-storage-service-s3-object.png
│  │     ├─ simple-storage-service-s3.png
│  │     ├─ snow-family-snowball-import-export.png
│  │     ├─ snowball-edge.png
│  │     ├─ snowball.png
│  │     ├─ snowmobile.png
│  │     ├─ storage-gateway-cached-volume.png
│  │     ├─ storage-gateway-non-cached-volume.png
│  │     ├─ storage-gateway-virtual-tape-library.png
│  │     ├─ storage-gateway.png
│  │     └─ storage.png
│  ├─ azure
│  │  ├─ analytics
│  │  │  ├─ analysis-services.png
│  │  │  ├─ data-explorer-clusters.png
│  │  │  ├─ data-factories.png
│  │  │  ├─ data-lake-analytics.png
│  │  │  ├─ data-lake-store-gen1.png
│  │  │  ├─ databricks.png
│  │  │  ├─ event-hub-clusters.png
│  │  │  ├─ event-hubs.png
│  │  │  ├─ hdinsightclusters.png
│  │  │  ├─ log-analytics-workspaces.png
│  │  │  ├─ stream-analytics-jobs.png
│  │  │  └─ synapse-analytics.png
│  │  ├─ compute
│  │  │  ├─ app-services.png
│  │  │  ├─ automanaged-vm.png
│  │  │  ├─ availability-sets.png
│  │  │  ├─ batch-accounts.png
│  │  │  ├─ citrix-virtual-desktops-essentials.png
│  │  │  ├─ cloud-services-classic.png
│  │  │  ├─ cloud-services.png
│  │  │  ├─ cloudsimple-virtual-machines.png
│  │  │  ├─ container-apps.png
│  │  │  ├─ container-instances.png
│  │  │  ├─ container-registries.png
│  │  │  ├─ disk-encryption-sets.png
│  │  │  ├─ disk-snapshots.png
│  │  │  ├─ disks.png
│  │  │  ├─ function-apps.png
│  │  │  ├─ image-definitions.png
│  │  │  ├─ image-versions.png
│  │  │  ├─ kubernetes-services.png
│  │  │  ├─ mesh-applications.png
│  │  │  ├─ os-images.png
│  │  │  ├─ sap-hana-on-azure.png
│  │  │  ├─ service-fabric-clusters.png
│  │  │  ├─ shared-image-galleries.png
│  │  │  ├─ spring-cloud.png
│  │  │  ├─ vm-classic.png
│  │  │  ├─ vm-images.png
│  │  │  ├─ vm-linux.png
│  │  │  ├─ vm-scale-set.png
│  │  │  ├─ vm-windows.png
│  │  │  ├─ vm.png
│  │  │  └─ workspaces.png
│  │  ├─ database
│  │  │  ├─ blob-storage.png
│  │  │  ├─ cache-for-redis.png
│  │  │  ├─ cosmos-db.png
│  │  │  ├─ data-explorer-clusters.png
│  │  │  ├─ data-factory.png
│  │  │  ├─ data-lake.png
│  │  │  ├─ database-for-mariadb-servers.png
│  │  │  ├─ database-for-mysql-servers.png
│  │  │  ├─ database-for-postgresql-servers.png
│  │  │  ├─ elastic-database-pools.png
│  │  │  ├─ elastic-job-agents.png
│  │  │  ├─ instance-pools.png
│  │  │  ├─ managed-databases.png
│  │  │  ├─ sql-databases.png
│  │  │  ├─ sql-datawarehouse.png
│  │  │  ├─ sql-managed-instances.png
│  │  │  ├─ sql-server-stretch-databases.png
│  │  │  ├─ sql-servers.png
│  │  │  ├─ sql-vm.png
│  │  │  ├─ sql.png
│  │  │  ├─ ssis-lift-and-shift-ir.png
│  │  │  ├─ synapse-analytics.png
│  │  │  ├─ virtual-clusters.png
│  │  │  └─ virtual-datacenter.png
│  │  ├─ devops
│  │  │  ├─ application-insights.png
│  │  │  ├─ artifacts.png
│  │  │  ├─ boards.png
│  │  │  ├─ devops.png
│  │  │  ├─ devtest-labs.png
│  │  │  ├─ lab-services.png
│  │  │  ├─ pipelines.png
│  │  │  ├─ repos.png
│  │  │  └─ test-plans.png
│  │  ├─ general
│  │  │  ├─ allresources.png
│  │  │  ├─ azurehome.png
│  │  │  ├─ developertools.png
│  │  │  ├─ helpsupport.png
│  │  │  ├─ information.png
│  │  │  ├─ managementgroups.png
│  │  │  ├─ marketplace.png
│  │  │  ├─ quickstartcenter.png
│  │  │  ├─ recent.png
│  │  │  ├─ reservations.png
│  │  │  ├─ resource.png
│  │  │  ├─ resourcegroups.png
│  │  │  ├─ servicehealth.png
│  │  │  ├─ shareddashboard.png
│  │  │  ├─ subscriptions.png
│  │  │  ├─ support.png
│  │  │  ├─ supportrequests.png
│  │  │  ├─ tag.png
│  │  │  ├─ tags.png
│  │  │  ├─ templates.png
│  │  │  ├─ twousericon.png
│  │  │  ├─ userhealthicon.png
│  │  │  ├─ usericon.png
│  │  │  ├─ userprivacy.png
│  │  │  ├─ userresource.png
│  │  │  └─ whatsnew.png
│  │  ├─ identity
│  │  │  ├─ access-review.png
│  │  │  ├─ active-directory-connect-health.png
│  │  │  ├─ active-directory.png
│  │  │  ├─ ad-b2c.png
│  │  │  ├─ ad-domain-services.png
│  │  │  ├─ ad-identity-protection.png
│  │  │  ├─ ad-privileged-identity-management.png
│  │  │  ├─ app-registrations.png
│  │  │  ├─ conditional-access.png
│  │  │  ├─ enterprise-applications.png
│  │  │  ├─ groups.png
│  │  │  ├─ identity-governance.png
│  │  │  ├─ information-protection.png
│  │  │  ├─ managed-identities.png
│  │  │  └─ users.png
│  │  ├─ integration
│  │  │  ├─ api-for-fhir.png
│  │  │  ├─ api-management.png
│  │  │  ├─ app-configuration.png
│  │  │  ├─ data-catalog.png
│  │  │  ├─ event-grid-domains.png
│  │  │  ├─ event-grid-subscriptions.png
│  │  │  ├─ event-grid-topics.png
│  │  │  ├─ integration-accounts.png
│  │  │  ├─ integration-service-environments.png
│  │  │  ├─ logic-apps-custom-connector.png
│  │  │  ├─ logic-apps.png
│  │  │  ├─ partner-topic.png
│  │  │  ├─ sendgrid-accounts.png
│  │  │  ├─ service-bus-relays.png
│  │  │  ├─ service-bus.png
│  │  │  ├─ service-catalog-managed-application-definitions.png
│  │  │  ├─ software-as-a-service.png
│  │  │  ├─ storsimple-device-managers.png
│  │  │  └─ system-topic.png
│  │  ├─ iot
│  │  │  ├─ device-provisioning-services.png
│  │  │  ├─ digital-twins.png
│  │  │  ├─ iot-central-applications.png
│  │  │  ├─ iot-hub-security.png
│  │  │  ├─ iot-hub.png
│  │  │  ├─ maps.png
│  │  │  ├─ sphere.png
│  │  │  ├─ time-series-insights-environments.png
│  │  │  ├─ time-series-insights-events-sources.png
│  │  │  └─ windows-10-iot-core-services.png
│  │  ├─ migration
│  │  │  ├─ data-box-edge.png
│  │  │  ├─ data-box.png
│  │  │  ├─ database-migration-services.png
│  │  │  ├─ migration-projects.png
│  │  │  └─ recovery-services-vaults.png
│  │  ├─ ml
│  │  │  ├─ batch-ai.png
│  │  │  ├─ bot-services.png
│  │  │  ├─ cognitive-services.png
│  │  │  ├─ genomics-accounts.png
│  │  │  ├─ machine-learning-service-workspaces.png
│  │  │  ├─ machine-learning-studio-web-service-plans.png
│  │  │  ├─ machine-learning-studio-web-services.png
│  │  │  └─ machine-learning-studio-workspaces.png
│  │  ├─ mobile
│  │  │  ├─ app-service-mobile.png
│  │  │  ├─ mobile-engagement.png
│  │  │  └─ notification-hubs.png
│  │  ├─ monitor
│  │  │  ├─ change-analysis.png
│  │  │  ├─ logs.png
│  │  │  ├─ metrics.png
│  │  │  └─ monitor.png
│  │  ├─ network
│  │  │  ├─ application-gateway.png
│  │  │  ├─ application-security-groups.png
│  │  │  ├─ cdn-profiles.png
│  │  │  ├─ connections.png
│  │  │  ├─ ddos-protection-plans.png
│  │  │  ├─ dns-private-zones.png
│  │  │  ├─ dns-zones.png
│  │  │  ├─ expressroute-circuits.png
│  │  │  ├─ firewall.png
│  │  │  ├─ front-doors.png
│  │  │  ├─ load-balancers.png
│  │  │  ├─ local-network-gateways.png
│  │  │  ├─ network-interfaces.png
│  │  │  ├─ network-security-groups-classic.png
│  │  │  ├─ network-watcher.png
│  │  │  ├─ on-premises-data-gateways.png
│  │  │  ├─ private-endpoint.png
│  │  │  ├─ public-ip-addresses.png
│  │  │  ├─ reserved-ip-addresses-classic.png
│  │  │  ├─ route-filters.png
│  │  │  ├─ route-tables.png
│  │  │  ├─ service-endpoint-policies.png
│  │  │  ├─ subnets.png
│  │  │  ├─ traffic-manager-profiles.png
│  │  │  ├─ virtual-network-classic.png
│  │  │  ├─ virtual-network-gateways.png
│  │  │  ├─ virtual-networks.png
│  │  │  └─ virtual-wans.png
│  │  ├─ security
│  │  │  ├─ application-security-groups.png
│  │  │  ├─ conditional-access.png
│  │  │  ├─ defender.png
│  │  │  ├─ extended-security-updates.png
│  │  │  ├─ key-vaults.png
│  │  │  ├─ security-center.png
│  │  │  └─ sentinel.png
│  │  ├─ storage
│  │  │  ├─ archive-storage.png
│  │  │  ├─ azurefxtedgefiler.png
│  │  │  ├─ blob-storage.png
│  │  │  ├─ data-box-edge-data-box-gateway.png
│  │  │  ├─ data-box.png
│  │  │  ├─ data-lake-storage.png
│  │  │  ├─ general-storage.png
│  │  │  ├─ netapp-files.png
│  │  │  ├─ queues-storage.png
│  │  │  ├─ storage-accounts-classic.png
│  │  │  ├─ storage-accounts.png
│  │  │  ├─ storage-explorer.png
│  │  │  ├─ storage-sync-services.png
│  │  │  ├─ storsimple-data-managers.png
│  │  │  ├─ storsimple-device-managers.png
│  │  │  └─ table-storage.png
│  │  └─ web
│  │     ├─ api-connections.png
│  │     ├─ app-service-certificates.png
│  │     ├─ app-service-domains.png
│  │     ├─ app-service-environments.png
│  │     ├─ app-service-plans.png
│  │     ├─ app-services.png
│  │     ├─ media-services.png
│  │     ├─ notification-hub-namespaces.png
│  │     ├─ search.png
│  │     └─ signalr.png
│  ├─ digitalocean
│  │  ├─ compute
│  │  │  ├─ containers.png
│  │  │  ├─ docker.png
│  │  │  ├─ droplet-connect.png
│  │  │  ├─ droplet-snapshot.png
│  │  │  ├─ droplet.png
│  │  │  ├─ k8s-cluster.png
│  │  │  ├─ k8s-node-pool.png
│  │  │  └─ k8s-node.png
│  │  ├─ database
│  │  │  ├─ dbaas-primary-standby-more.png
│  │  │  ├─ dbaas-primary.png
│  │  │  ├─ dbaas-read-only.png
│  │  │  └─ dbaas-standby.png
│  │  ├─ network
│  │  │  ├─ certificate.png
│  │  │  ├─ domain-registration.png
│  │  │  ├─ domain.png
│  │  │  ├─ firewall.png
│  │  │  ├─ floating-ip.png
│  │  │  ├─ internet-gateway.png
│  │  │  ├─ load-balancer.png
│  │  │  ├─ managed-vpn.png
│  │  │  └─ vpc.png
│  │  └─ storage
│  │     ├─ folder.png
│  │     ├─ space.png
│  │     ├─ volume-snapshot.png
│  │     └─ volume.png
│  ├─ elastic
│  │  ├─ agent
│  │  │  ├─ agent.png
│  │  │  ├─ endpoint.png
│  │  │  ├─ fleet.png
│  │  │  └─ integrations.png
│  │  ├─ beats
│  │  │  ├─ apm.png
│  │  │  ├─ auditbeat.png
│  │  │  ├─ filebeat.png
│  │  │  ├─ functionbeat.png
│  │  │  ├─ heartbeat.png
│  │  │  ├─ metricbeat.png
│  │  │  ├─ packetbeat.png
│  │  │  └─ winlogbeat.png
│  │  ├─ elasticsearch
│  │  │  ├─ alerting.png
│  │  │  ├─ beats.png
│  │  │  ├─ elasticsearch.png
│  │  │  ├─ kibana.png
│  │  │  ├─ logstash-pipeline.png
│  │  │  ├─ logstash.png
│  │  │  ├─ machine-learning.png
│  │  │  ├─ map-services.png
│  │  │  ├─ maps.png
│  │  │  ├─ monitoring.png
│  │  │  ├─ searchable-snapshots.png
│  │  │  ├─ security-settings.png
│  │  │  ├─ sql.png
│  │  │  └─ stack.png
│  │  ├─ enterprisesearch
│  │  │  ├─ app-search.png
│  │  │  ├─ crawler.png
│  │  │  ├─ enterprise-search.png
│  │  │  ├─ site-search.png
│  │  │  └─ workplace-search.png
│  │  ├─ observability
│  │  │  ├─ apm.png
│  │  │  ├─ logs.png
│  │  │  ├─ metrics.png
│  │  │  ├─ observability.png
│  │  │  └─ uptime.png
│  │  ├─ orchestration
│  │  │  ├─ ece.png
│  │  │  └─ eck.png
│  │  ├─ saas
│  │  │  ├─ cloud.png
│  │  │  └─ elastic.png
│  │  └─ security
│  │     ├─ endpoint.png
│  │     ├─ security.png
│  │     ├─ siem.png
│  │     └─ xdr.png
│  ├─ firebase
│  │  ├─ base
│  │  │  └─ firebase.png
│  │  ├─ develop
│  │  │  ├─ authentication.png
│  │  │  ├─ firestore.png
│  │  │  ├─ functions.png
│  │  │  ├─ hosting.png
│  │  │  ├─ ml-kit.png
│  │  │  ├─ realtime-database.png
│  │  │  └─ storage.png
│  │  ├─ extentions
│  │  │  └─ extensions.png
│  │  ├─ grow
│  │  │  ├─ ab-testing.png
│  │  │  ├─ app-indexing.png
│  │  │  ├─ dynamic-links.png
│  │  │  ├─ in-app-messaging.png
│  │  │  ├─ invites.png
│  │  │  ├─ messaging.png
│  │  │  ├─ predictions.png
│  │  │  └─ remote-config.png
│  │  └─ quality
│  │     ├─ crash-reporting.png
│  │     ├─ crashlytics.png
│  │     ├─ performance-monitoring.png
│  │     └─ test-lab.png
│  ├─ gcp
│  │  ├─ analytics
│  │  │  ├─ bigquery.png
│  │  │  ├─ composer.png
│  │  │  ├─ data-catalog.png
│  │  │  ├─ data-fusion.png
│  │  │  ├─ dataflow.png
│  │  │  ├─ datalab.png
│  │  │  ├─ dataprep.png
│  │  │  ├─ dataproc.png
│  │  │  ├─ genomics.png
│  │  │  └─ pubsub.png
│  │  ├─ api
│  │  │  ├─ api-gateway.png
│  │  │  ├─ apigee.png
│  │  │  └─ endpoints.png
│  │  ├─ compute
│  │  │  ├─ app-engine.png
│  │  │  ├─ compute-engine.png
│  │  │  ├─ container-optimized-os.png
│  │  │  ├─ functions.png
│  │  │  ├─ gke-on-prem.png
│  │  │  ├─ gpu.png
│  │  │  ├─ kubernetes-engine.png
│  │  │  └─ run.png
│  │  ├─ database
│  │  │  ├─ bigtable.png
│  │  │  ├─ datastore.png
│  │  │  ├─ firestore.png
│  │  │  ├─ memorystore.png
│  │  │  ├─ spanner.png
│  │  │  └─ sql.png
│  │  ├─ devtools
│  │  │  ├─ build.png
│  │  │  ├─ code-for-intellij.png
│  │  │  ├─ code.png
│  │  │  ├─ container-registry.png
│  │  │  ├─ gradle-app-engine-plugin.png
│  │  │  ├─ ide-plugins.png
│  │  │  ├─ maven-app-engine-plugin.png
│  │  │  ├─ scheduler.png
│  │  │  ├─ sdk.png
│  │  │  ├─ source-repositories.png
│  │  │  ├─ tasks.png
│  │  │  ├─ test-lab.png
│  │  │  ├─ tools-for-eclipse.png
│  │  │  ├─ tools-for-powershell.png
│  │  │  └─ tools-for-visual-studio.png
│  │  ├─ iot
│  │  │  └─ iot-core.png
│  │  ├─ migration
│  │  │  └─ transfer-appliance.png
│  │  ├─ ml
│  │  │  ├─ advanced-solutions-lab.png
│  │  │  ├─ ai-hub.png
│  │  │  ├─ ai-platform-data-labeling-service.png
│  │  │  ├─ ai-platform.png
│  │  │  ├─ automl-natural-language.png
│  │  │  ├─ automl-tables.png
│  │  │  ├─ automl-translation.png
│  │  │  ├─ automl-video-intelligence.png
│  │  │  ├─ automl-vision.png
│  │  │  ├─ automl.png
│  │  │  ├─ dialog-flow-enterprise-edition.png
│  │  │  ├─ inference-api.png
│  │  │  ├─ jobs-api.png
│  │  │  ├─ natural-language-api.png
│  │  │  ├─ recommendations-ai.png
│  │  │  ├─ speech-to-text.png
│  │  │  ├─ text-to-speech.png
│  │  │  ├─ tpu.png
│  │  │  ├─ translation-api.png
│  │  │  ├─ video-intelligence-api.png
│  │  │  └─ vision-api.png
│  │  ├─ network
│  │  │  ├─ armor.png
│  │  │  ├─ cdn.png
│  │  │  ├─ dedicated-interconnect.png
│  │  │  ├─ dns.png
│  │  │  ├─ external-ip-addresses.png
│  │  │  ├─ firewall-rules.png
│  │  │  ├─ load-balancing.png
│  │  │  ├─ nat.png
│  │  │  ├─ network.png
│  │  │  ├─ partner-interconnect.png
│  │  │  ├─ premium-network-tier.png
│  │  │  ├─ router.png
│  │  │  ├─ routes.png
│  │  │  ├─ standard-network-tier.png
│  │  │  ├─ traffic-director.png
│  │  │  ├─ virtual-private-cloud.png
│  │  │  └─ vpn.png
│  │  ├─ operations
│  │  │  ├─ logging.png
│  │  │  └─ monitoring.png
│  │  ├─ security
│  │  │  ├─ iam.png
│  │  │  ├─ iap.png
│  │  │  ├─ key-management-service.png
│  │  │  ├─ resource-manager.png
│  │  │  ├─ security-command-center.png
│  │  │  └─ security-scanner.png
│  │  └─ storage
│  │     ├─ filestore.png
│  │     ├─ persistent-disk.png
│  │     └─ storage.png
│  ├─ generic
│  │  ├─ blank
│  │  │  └─ blank.png
│  │  ├─ compute
│  │  │  └─ rack.png
│  │  ├─ database
│  │  │  └─ sql.png
│  │  ├─ device
│  │  │  ├─ mobile.png
│  │  │  └─ tablet.png
│  │  ├─ network
│  │  │  ├─ firewall.png
│  │  │  ├─ router.png
│  │  │  ├─ subnet.png
│  │  │  ├─ switch.png
│  │  │  └─ vpn.png
│  │  ├─ os
│  │  │  ├─ android.png
│  │  │  ├─ centos.png
│  │  │  ├─ debian.png
│  │  │  ├─ ios.png
│  │  │  ├─ linux-general.png
│  │  │  ├─ raspbian.png
│  │  │  ├─ red-hat.png
│  │  │  ├─ suse.png
│  │  │  ├─ ubuntu.png
│  │  │  └─ windows.png
│  │  ├─ place
│  │  │  └─ datacenter.png
│  │  ├─ storage
│  │  │  └─ storage.png
│  │  └─ virtualization
│  │     ├─ qemu.png
│  │     ├─ virtualbox.png
│  │     ├─ vmware.png
│  │     └─ xen.png
│  ├─ ibm
│  │  ├─ analytics
│  │  │  ├─ analytics.png
│  │  │  ├─ data-integration.png
│  │  │  ├─ data-repositories.png
│  │  │  ├─ device-analytics.png
│  │  │  └─ streaming-computing.png
│  │  ├─ applications
│  │  │  ├─ actionable-insight.png
│  │  │  ├─ annotate.png
│  │  │  ├─ api-developer-portal.png
│  │  │  ├─ api-polyglot-runtimes.png
│  │  │  ├─ app-server.png
│  │  │  ├─ application-logic.png
│  │  │  ├─ enterprise-applications.png
│  │  │  ├─ index.png
│  │  │  ├─ iot-application.png
│  │  │  ├─ microservice.png
│  │  │  ├─ mobile-app.png
│  │  │  ├─ ontology.png
│  │  │  ├─ open-source-tools.png
│  │  │  ├─ runtime-services.png
│  │  │  ├─ saas-applications.png
│  │  │  ├─ service-broker.png
│  │  │  ├─ speech-to-text.png
│  │  │  ├─ visual-recognition.png
│  │  │  └─ visualization.png
│  │  ├─ blockchain
│  │  │  ├─ blockchain-developer.png
│  │  │  ├─ blockchain.png
│  │  │  ├─ certificate-authority.png
│  │  │  ├─ client-application.png
│  │  │  ├─ communication.png
│  │  │  ├─ consensus.png
│  │  │  ├─ event-listener.png
│  │  │  ├─ event.png
│  │  │  ├─ existing-enterprise-systems.png
│  │  │  ├─ hyperledger-fabric.png
│  │  │  ├─ key-management.png
│  │  │  ├─ ledger.png
│  │  │  ├─ membership-services-provider-api.png
│  │  │  ├─ membership.png
│  │  │  ├─ message-bus.png
│  │  │  ├─ node.png
│  │  │  ├─ services.png
│  │  │  ├─ smart-contract.png
│  │  │  ├─ transaction-manager.png
│  │  │  └─ wallet.png
│  │  ├─ compute
│  │  │  ├─ bare-metal-server.png
│  │  │  ├─ image-service.png
│  │  │  ├─ instance.png
│  │  │  ├─ key.png
│  │  │  └─ power-instance.png
│  │  ├─ data
│  │  │  ├─ caches.png
│  │  │  ├─ cloud.png
│  │  │  ├─ conversation-trained-deployed.png
│  │  │  ├─ data-services.png
│  │  │  ├─ data-sources.png
│  │  │  ├─ device-identity-service.png
│  │  │  ├─ device-registry.png
│  │  │  ├─ enterprise-data.png
│  │  │  ├─ enterprise-user-directory.png
│  │  │  ├─ file-repository.png
│  │  │  ├─ ground-truth.png
│  │  │  ├─ model.png
│  │  │  └─ tms-data-interface.png
│  │  ├─ devops
│  │  │  ├─ artifact-management.png
│  │  │  ├─ build-test.png
│  │  │  ├─ code-editor.png
│  │  │  ├─ collaborative-development.png
│  │  │  ├─ configuration-management.png
│  │  │  ├─ continuous-deploy.png
│  │  │  ├─ continuous-testing.png
│  │  │  ├─ devops.png
│  │  │  ├─ provision.png
│  │  │  └─ release-management.png
│  │  ├─ general
│  │  │  ├─ cloud-messaging.png
│  │  │  ├─ cloud-services.png
│  │  │  ├─ cloudant.png
│  │  │  ├─ cognitive-services.png
│  │  │  ├─ data-security.png
│  │  │  ├─ enterprise.png
│  │  │  ├─ governance-risk-compliance.png
│  │  │  ├─ ibm-containers.png
│  │  │  ├─ ibm-public-cloud.png
│  │  │  ├─ identity-access-management.png
│  │  │  ├─ identity-provider.png
│  │  │  ├─ infrastructure-security.png
│  │  │  ├─ internet.png
│  │  │  ├─ iot-cloud.png
│  │  │  ├─ microservices-application.png
│  │  │  ├─ microservices-mesh.png
│  │  │  ├─ monitoring-logging.png
│  │  │  ├─ monitoring.png
│  │  │  ├─ object-storage.png
│  │  │  ├─ offline-capabilities.png
│  │  │  ├─ openwhisk.png
│  │  │  ├─ peer-cloud.png
│  │  │  ├─ retrieve-rank.png
│  │  │  ├─ scalable.png
│  │  │  ├─ service-discovery-configuration.png
│  │  │  ├─ text-to-speech.png
│  │  │  └─ transformation-connectivity.png
│  │  ├─ infrastructure
│  │  │  ├─ channels.png
│  │  │  ├─ cloud-messaging.png
│  │  │  ├─ dashboard.png
│  │  │  ├─ diagnostics.png
│  │  │  ├─ edge-services.png
│  │  │  ├─ enterprise-messaging.png
│  │  │  ├─ event-feed.png
│  │  │  ├─ infrastructure-services.png
│  │  │  ├─ interservice-communication.png
│  │  │  ├─ load-balancing-routing.png
│  │  │  ├─ microservices-mesh.png
│  │  │  ├─ mobile-backend.png
│  │  │  ├─ mobile-provider-network.png
│  │  │  ├─ monitoring-logging.png
│  │  │  ├─ monitoring.png
│  │  │  ├─ peer-services.png
│  │  │  ├─ service-discovery-configuration.png
│  │  │  └─ transformation-connectivity.png
│  │  ├─ management
│  │  │  ├─ alert-notification.png
│  │  │  ├─ api-management.png
│  │  │  ├─ cloud-management.png
│  │  │  ├─ cluster-management.png
│  │  │  ├─ content-management.png
│  │  │  ├─ data-services.png
│  │  │  ├─ device-management.png
│  │  │  ├─ information-governance.png
│  │  │  ├─ it-service-management.png
│  │  │  ├─ management.png
│  │  │  ├─ monitoring-metrics.png
│  │  │  ├─ process-management.png
│  │  │  ├─ provider-cloud-portal-service.png
│  │  │  ├─ push-notifications.png
│  │  │  └─ service-management-tools.png
│  │  ├─ network
│  │  │  ├─ bridge.png
│  │  │  ├─ direct-link.png
│  │  │  ├─ enterprise.png
│  │  │  ├─ firewall.png
│  │  │  ├─ floating-ip.png
│  │  │  ├─ gateway.png
│  │  │  ├─ internet-services.png
│  │  │  ├─ load-balancer-listener.png
│  │  │  ├─ load-balancer-pool.png
│  │  │  ├─ load-balancer.png
│  │  │  ├─ load-balancing-routing.png
│  │  │  ├─ public-gateway.png
│  │  │  ├─ region.png
│  │  │  ├─ router.png
│  │  │  ├─ rules.png
│  │  │  ├─ subnet.png
│  │  │  ├─ transit-gateway.png
│  │  │  ├─ vpc.png
│  │  │  ├─ vpn-connection.png
│  │  │  ├─ vpn-gateway.png
│  │  │  └─ vpn-policy.png
│  │  ├─ security
│  │  │  ├─ api-security.png
│  │  │  ├─ blockchain-security-service.png
│  │  │  ├─ data-security.png
│  │  │  ├─ firewall.png
│  │  │  ├─ gateway.png
│  │  │  ├─ governance-risk-compliance.png
│  │  │  ├─ identity-access-management.png
│  │  │  ├─ identity-provider.png
│  │  │  ├─ infrastructure-security.png
│  │  │  ├─ physical-security.png
│  │  │  ├─ security-monitoring-intelligence.png
│  │  │  ├─ security-services.png
│  │  │  ├─ trustend-computing.png
│  │  │  └─ vpn.png
│  │  ├─ social
│  │  │  ├─ communities.png
│  │  │  ├─ file-sync.png
│  │  │  ├─ live-collaboration.png
│  │  │  ├─ messaging.png
│  │  │  └─ networking.png
│  │  ├─ storage
│  │  │  ├─ block-storage.png
│  │  │  └─ object-storage.png
│  │  └─ user
│  │     ├─ browser.png
│  │     ├─ device.png
│  │     ├─ integrated-digital-experiences.png
│  │     ├─ physical-entity.png
│  │     ├─ sensor.png
│  │     └─ user.png
│  ├─ k8s
│  │  ├─ chaos
│  │  │  ├─ chaos-mesh.png
│  │  │  └─ litmus-chaos.png
│  │  ├─ clusterconfig
│  │  │  ├─ hpa.png
│  │  │  ├─ limits.png
│  │  │  └─ quota.png
│  │  ├─ compute
│  │  │  ├─ cronjob.png
│  │  │  ├─ deploy.png
│  │  │  ├─ ds.png
│  │  │  ├─ job.png
│  │  │  ├─ pod.png
│  │  │  ├─ rs.png
│  │  │  └─ sts.png
│  │  ├─ controlplane
│  │  │  ├─ api.png
│  │  │  ├─ c-c-m.png
│  │  │  ├─ c-m.png
│  │  │  ├─ k-proxy.png
│  │  │  ├─ kubelet.png
│  │  │  └─ sched.png
│  │  ├─ ecosystem
│  │  │  ├─ external-dns.png
│  │  │  ├─ helm.png
│  │  │  ├─ krew.png
│  │  │  └─ kustomize.png
│  │  ├─ group
│  │  │  └─ ns.png
│  │  ├─ infra
│  │  │  ├─ etcd.png
│  │  │  ├─ master.png
│  │  │  └─ node.png
│  │  ├─ network
│  │  │  ├─ ep.png
│  │  │  ├─ ing.png
│  │  │  ├─ netpol.png
│  │  │  └─ svc.png
│  │  ├─ others
│  │  │  ├─ crd.png
│  │  │  └─ psp.png
│  │  ├─ podconfig
│  │  │  ├─ cm.png
│  │  │  └─ secret.png
│  │  ├─ rbac
│  │  │  ├─ c-role.png
│  │  │  ├─ crb.png
│  │  │  ├─ group.png
│  │  │  ├─ rb.png
│  │  │  ├─ role.png
│  │  │  ├─ sa.png
│  │  │  └─ user.png
│  │  └─ storage
│  │     ├─ pv.png
│  │     ├─ pvc.png
│  │     ├─ sc.png
│  │     └─ vol.png
│  ├─ oci
│  │  ├─ compute
│  │  │  ├─ autoscale-white.png
│  │  │  ├─ autoscale.png
│  │  │  ├─ bm-white.png
│  │  │  ├─ bm.png
│  │  │  ├─ container-white.png
│  │  │  ├─ container.png
│  │  │  ├─ functions-white.png
│  │  │  ├─ functions.png
│  │  │  ├─ instance-pools-white.png
│  │  │  ├─ instance-pools.png
│  │  │  ├─ ocir-white.png
│  │  │  ├─ ocir.png
│  │  │  ├─ oke-white.png
│  │  │  ├─ oke.png
│  │  │  ├─ vm-white.png
│  │  │  └─ vm.png
│  │  ├─ connectivity
│  │  │  ├─ backbone-white.png
│  │  │  ├─ backbone.png
│  │  │  ├─ cdn-white.png
│  │  │  ├─ cdn.png
│  │  │  ├─ customer-datacenter.png
│  │  │  ├─ customer-datacntr-white.png
│  │  │  ├─ customer-premises-white.png
│  │  │  ├─ customer-premises.png
│  │  │  ├─ disconnected-regions-white.png
│  │  │  ├─ disconnected-regions.png
│  │  │  ├─ dns-white.png
│  │  │  ├─ dns.png
│  │  │  ├─ fast-connect-white.png
│  │  │  ├─ fast-connect.png
│  │  │  ├─ nat-gateway-white.png
│  │  │  ├─ nat-gateway.png
│  │  │  ├─ vpn-white.png
│  │  │  └─ vpn.png
│  │  ├─ database
│  │  │  ├─ autonomous-white.png
│  │  │  ├─ autonomous.png
│  │  │  ├─ bigdata-service-white.png
│  │  │  ├─ bigdata-service.png
│  │  │  ├─ database-service-white.png
│  │  │  ├─ database-service.png
│  │  │  ├─ dataflow-apache-white.png
│  │  │  ├─ dataflow-apache.png
│  │  │  ├─ dcat-white.png
│  │  │  ├─ dcat.png
│  │  │  ├─ dis-white.png
│  │  │  ├─ dis.png
│  │  │  ├─ dms-white.png
│  │  │  ├─ dms.png
│  │  │  ├─ science-white.png
│  │  │  ├─ science.png
│  │  │  ├─ stream-white.png
│  │  │  └─ stream.png
│  │  ├─ devops
│  │  │  ├─ api-gateway-white.png
│  │  │  ├─ api-gateway.png
│  │  │  ├─ api-service-white.png
│  │  │  ├─ api-service.png
│  │  │  ├─ resource-mgmt-white.png
│  │  │  └─ resource-mgmt.png
│  │  ├─ governance
│  │  │  ├─ audit-white.png
│  │  │  ├─ audit.png
│  │  │  ├─ compartments-white.png
│  │  │  ├─ compartments.png
│  │  │  ├─ groups-white.png
│  │  │  ├─ groups.png
│  │  │  ├─ logging-white.png
│  │  │  ├─ logging.png
│  │  │  ├─ ocid-white.png
│  │  │  ├─ ocid.png
│  │  │  ├─ policies-white.png
│  │  │  ├─ policies.png
│  │  │  ├─ tagging-white.png
│  │  │  └─ tagging.png
│  │  ├─ monitoring
│  │  │  ├─ alarm-white.png
│  │  │  ├─ alarm.png
│  │  │  ├─ email-white.png
│  │  │  ├─ email.png
│  │  │  ├─ events-white.png
│  │  │  ├─ events.png
│  │  │  ├─ health-check-white.png
│  │  │  ├─ health-check.png
│  │  │  ├─ notifications-white.png
│  │  │  ├─ notifications.png
│  │  │  ├─ queue-white.png
│  │  │  ├─ queue.png
│  │  │  ├─ search-white.png
│  │  │  ├─ search.png
│  │  │  ├─ telemetry-white.png
│  │  │  ├─ telemetry.png
│  │  │  ├─ workflow-white.png
│  │  │  └─ workflow.png
│  │  ├─ network
│  │  │  ├─ drg-white.png
│  │  │  ├─ drg.png
│  │  │  ├─ firewall-white.png
│  │  │  ├─ firewall.png
│  │  │  ├─ internet-gateway-white.png
│  │  │  ├─ internet-gateway.png
│  │  │  ├─ load-balancer-white.png
│  │  │  ├─ load-balancer.png
│  │  │  ├─ route-table-white.png
│  │  │  ├─ route-table.png
│  │  │  ├─ security-lists-white.png
│  │  │  ├─ security-lists.png
│  │  │  ├─ service-gateway-white.png
│  │  │  ├─ service-gateway.png
│  │  │  ├─ vcn-white.png
│  │  │  └─ vcn.png
│  │  ├─ security
│  │  │  ├─ cloud-guard-white.png
│  │  │  ├─ cloud-guard.png
│  │  │  ├─ ddos-white.png
│  │  │  ├─ ddos.png
│  │  │  ├─ encryption-white.png
│  │  │  ├─ encryption.png
│  │  │  ├─ id-access-white.png
│  │  │  ├─ id-access.png
│  │  │  ├─ key-management-white.png
│  │  │  ├─ key-management.png
│  │  │  ├─ max-security-zone-white.png
│  │  │  ├─ max-security-zone.png
│  │  │  ├─ vault-white.png
│  │  │  ├─ vault.png
│  │  │  ├─ waf-white.png
│  │  │  └─ waf.png
│  │  └─ storage
│  │     ├─ backup-restore-white.png
│  │     ├─ backup-restore.png
│  │     ├─ block-storage-clone-white.png
│  │     ├─ block-storage-clone.png
│  │     ├─ block-storage-white.png
│  │     ├─ block-storage.png
│  │     ├─ buckets-white.png
│  │     ├─ buckets.png
│  │     ├─ data-transfer-white.png
│  │     ├─ data-transfer.png
│  │     ├─ elastic-performance-white.png
│  │     ├─ elastic-performance.png
│  │     ├─ file-storage-white.png
│  │     ├─ file-storage.png
│  │     ├─ object-storage-white.png
│  │     ├─ object-storage.png
│  │     ├─ storage-gateway-white.png
│  │     └─ storage-gateway.png
│  ├─ onprem
│  │  ├─ aggregator
│  │  │  ├─ fluentd.png
│  │  │  └─ vector.png
│  │  ├─ analytics
│  │  │  ├─ beam.png
│  │  │  ├─ databricks.png
│  │  │  ├─ dbt.png
│  │  │  ├─ dremio.png
│  │  │  ├─ flink.png
│  │  │  ├─ hadoop.png
│  │  │  ├─ hive.png
│  │  │  ├─ metabase.png
│  │  │  ├─ norikra.png
│  │  │  ├─ powerbi.png
│  │  │  ├─ presto.png
│  │  │  ├─ singer.png
│  │  │  ├─ spark.png
│  │  │  ├─ storm.png
│  │  │  ├─ superset.png
│  │  │  ├─ tableau.png
│  │  │  └─ trino.png
│  │  ├─ auth
│  │  │  ├─ boundary.png
│  │  │  ├─ buzzfeed-sso.png
│  │  │  └─ oauth2-proxy.png
│  │  ├─ cd
│  │  │  ├─ spinnaker.png
│  │  │  ├─ tekton-cli.png
│  │  │  └─ tekton.png
│  │  ├─ certificates
│  │  │  ├─ cert-manager.png
│  │  │  └─ lets-encrypt.png
│  │  ├─ ci
│  │  │  ├─ circleci.png
│  │  │  ├─ concourseci.png
│  │  │  ├─ droneci.png
│  │  │  ├─ github-actions.png
│  │  │  ├─ gitlabci.png
│  │  │  ├─ jenkins.png
│  │  │  ├─ teamcity.png
│  │  │  ├─ travisci.png
│  │  │  └─ zuulci.png
│  │  ├─ client
│  │  │  ├─ client.png
│  │  │  ├─ user.png
│  │  │  └─ users.png
│  │  ├─ compute
│  │  │  ├─ nomad.png
│  │  │  └─ server.png
│  │  ├─ container
│  │  │  ├─ containerd.png
│  │  │  ├─ crio.png
│  │  │  ├─ docker.png
│  │  │  ├─ firecracker.png
│  │  │  ├─ gvisor.png
│  │  │  ├─ k3s.png
│  │  │  ├─ lxc.png
│  │  │  └─ rkt.png
│  │  ├─ database
│  │  │  ├─ cassandra.png
│  │  │  ├─ clickhouse.png
│  │  │  ├─ cockroachdb.png
│  │  │  ├─ couchbase.png
│  │  │  ├─ couchdb.png
│  │  │  ├─ dgraph.png
│  │  │  ├─ druid.png
│  │  │  ├─ hbase.png
│  │  │  ├─ influxdb.png
│  │  │  ├─ janusgraph.png
│  │  │  ├─ mariadb.png
│  │  │  ├─ mongodb.png
│  │  │  ├─ mssql.png
│  │  │  ├─ mysql.png
│  │  │  ├─ neo4j.png
│  │  │  ├─ oracle.png
│  │  │  ├─ postgresql.png
│  │  │  └─ scylla.png
│  │  ├─ dns
│  │  │  ├─ coredns.png
│  │  │  └─ powerdns.png
│  │  ├─ etl
│  │  │  └─ embulk.png
│  │  ├─ gitops
│  │  │  ├─ argocd.png
│  │  │  ├─ flagger.png
│  │  │  └─ flux.png
│  │  ├─ groupware
│  │  │  └─ nextcloud.png
│  │  ├─ iac
│  │  │  ├─ ansible.png
│  │  │  ├─ atlantis.png
│  │  │  ├─ awx.png
│  │  │  ├─ puppet.png
│  │  │  └─ terraform.png
│  │  ├─ identity
│  │  │  └─ dex.png
│  │  ├─ inmemory
│  │  │  ├─ aerospike.png
│  │  │  ├─ hazelcast.png
│  │  │  ├─ memcached.png
│  │  │  └─ redis.png
│  │  ├─ logging
│  │  │  ├─ fluentbit.png
│  │  │  ├─ graylog.png
│  │  │  ├─ loki.png
│  │  │  ├─ rsyslog.png
│  │  │  └─ syslog-ng.png
│  │  ├─ messaging
│  │  │  └─ centrifugo.png
│  │  ├─ mlops
│  │  │  ├─ mlflow.png
│  │  │  └─ polyaxon.png
│  │  ├─ monitoring
│  │  │  ├─ cortex.png
│  │  │  ├─ datadog.png
│  │  │  ├─ dynatrace.png
│  │  │  ├─ grafana.png
│  │  │  ├─ humio.png
│  │  │  ├─ mimir.png
│  │  │  ├─ nagios.png
│  │  │  ├─ newrelic.png
│  │  │  ├─ prometheus-operator.png
│  │  │  ├─ prometheus.png
│  │  │  ├─ sentry.png
│  │  │  ├─ splunk.png
│  │  │  ├─ thanos.png
│  │  │  └─ zabbix.png
│  │  ├─ network
│  │  │  ├─ ambassador.png
│  │  │  ├─ apache.png
│  │  │  ├─ bind-9.png
│  │  │  ├─ caddy.png
│  │  │  ├─ consul.png
│  │  │  ├─ envoy.png
│  │  │  ├─ etcd.png
│  │  │  ├─ glassfish.png
│  │  │  ├─ gunicorn.png
│  │  │  ├─ haproxy.png
│  │  │  ├─ internet.png
│  │  │  ├─ istio.png
│  │  │  ├─ jbossas.png
│  │  │  ├─ jetty.png
│  │  │  ├─ kong.png
│  │  │  ├─ linkerd.png
│  │  │  ├─ nginx.png
│  │  │  ├─ ocelot.png
│  │  │  ├─ open-service-mesh.png
│  │  │  ├─ opnsense.png
│  │  │  ├─ pfsense.png
│  │  │  ├─ pomerium.png
│  │  │  ├─ powerdns.png
│  │  │  ├─ tomcat.png
│  │  │  ├─ traefik.png
│  │  │  ├─ tyk.png
│  │  │  ├─ vyos.png
│  │  │  ├─ wildfly.png
│  │  │  ├─ yarp.png
│  │  │  └─ zookeeper.png
│  │  ├─ proxmox
│  │  │  └─ pve.png
│  │  ├─ queue
│  │  │  ├─ activemq.png
│  │  │  ├─ celery.png
│  │  │  ├─ emqx.png
│  │  │  ├─ kafka.png
│  │  │  ├─ nats.png
│  │  │  ├─ rabbitmq.png
│  │  │  └─ zeromq.png
│  │  ├─ registry
│  │  │  ├─ harbor.png
│  │  │  └─ jfrog.png
│  │  ├─ search
│  │  │  └─ solr.png
│  │  ├─ security
│  │  │  ├─ bitwarden.png
│  │  │  ├─ trivy.png
│  │  │  └─ vault.png
│  │  ├─ storage
│  │  │  ├─ ceph-osd.png
│  │  │  ├─ ceph.png
│  │  │  ├─ glusterfs.png
│  │  │  └─ portworx.png
│  │  ├─ tracing
│  │  │  ├─ jaeger.png
│  │  │  └─ tempo.png
│  │  ├─ vcs
│  │  │  ├─ git.png
│  │  │  ├─ gitea.png
│  │  │  ├─ github.png
│  │  │  ├─ gitlab.png
│  │  │  └─ svn.png
│  │  └─ workflow
│  │     ├─ airflow.png
│  │     ├─ digdag.png
│  │     ├─ kubeflow.png
│  │     └─ nifi.png
│  ├─ openstack
│  │  ├─ apiproxies
│  │  │  └─ ec2api.png
│  │  ├─ applicationlifecycle
│  │  │  ├─ freezer.png
│  │  │  ├─ masakari.png
│  │  │  ├─ murano.png
│  │  │  └─ solum.png
│  │  ├─ baremetal
│  │  │  ├─ cyborg.png
│  │  │  └─ ironic.png
│  │  ├─ billing
│  │  │  └─ cloudkitty.png
│  │  ├─ compute
│  │  │  ├─ nova.png
│  │  │  ├─ qinling.png
│  │  │  └─ zun.png
│  │  ├─ containerservices
│  │  │  └─ kuryr.png
│  │  ├─ deployment
│  │  │  ├─ ansible.png
│  │  │  ├─ charms.png
│  │  │  ├─ chef.png
│  │  │  ├─ helm.png
│  │  │  ├─ kolla.png
│  │  │  └─ tripleo.png
│  │  ├─ frontend
│  │  │  └─ horizon.png
│  │  ├─ monitoring
│  │  │  ├─ monasca.png
│  │  │  └─ telemetry.png
│  │  ├─ multiregion
│  │  │  └─ tricircle.png
│  │  ├─ networking
│  │  │  ├─ designate.png
│  │  │  ├─ neutron.png
│  │  │  └─ octavia.png
│  │  ├─ nfv
│  │  │  └─ tacker.png
│  │  ├─ openstack.png
│  │  ├─ optimization
│  │  │  ├─ congress.png
│  │  │  ├─ rally.png
│  │  │  ├─ vitrage.png
│  │  │  └─ watcher.png
│  │  ├─ orchestration
│  │  │  ├─ blazar.png
│  │  │  ├─ heat.png
│  │  │  ├─ mistral.png
│  │  │  ├─ senlin.png
│  │  │  └─ zaqar.png
│  │  ├─ packaging
│  │  │  ├─ loci.png
│  │  │  ├─ puppet.png
│  │  │  └─ rpm.png
│  │  ├─ sharedservices
│  │  │  ├─ barbican.png
│  │  │  ├─ glance.png
│  │  │  ├─ karbor.png
│  │  │  ├─ keystone.png
│  │  │  └─ searchlight.png
│  │  ├─ storage
│  │  │  ├─ cinder.png
│  │  │  ├─ manila.png
│  │  │  └─ swift.png
│  │  ├─ user
│  │  │  └─ openstackclient.png
│  │  └─ workloadprovisioning
│  │     ├─ magnum.png
│  │     ├─ sahara.png
│  │     └─ trove.png
│  ├─ outscale
│  │  ├─ compute
│  │  │  ├─ compute.png
│  │  │  └─ direct-connect.png
│  │  ├─ network
│  │  │  ├─ client-vpn.png
│  │  │  ├─ internet-service.png
│  │  │  ├─ load-balancer.png
│  │  │  ├─ nat-service.png
│  │  │  ├─ net.png
│  │  │  └─ site-to-site-vpng.png
│  │  ├─ security
│  │  │  ├─ firewall.png
│  │  │  └─ identity-and-access-management.png
│  │  └─ storage
│  │     ├─ simple-storage-service.png
│  │     └─ storage.png
│  ├─ programming
│  │  ├─ flowchart
│  │  │  ├─ action.png
│  │  │  ├─ collate.png
│  │  │  ├─ database.png
│  │  │  ├─ decision.png
│  │  │  ├─ delay.png
│  │  │  ├─ display.png
│  │  │  ├─ document.png
│  │  │  ├─ input-output.png
│  │  │  ├─ inspection.png
│  │  │  ├─ internal-storage.png
│  │  │  ├─ loop-limit.png
│  │  │  ├─ manual-input.png
│  │  │  ├─ manual-loop.png
│  │  │  ├─ merge.png
│  │  │  ├─ multiple-documents.png
│  │  │  ├─ off-page-connector-left.png
│  │  │  ├─ off-page-connector-right.png
│  │  │  ├─ or.png
│  │  │  ├─ predefined-process.png
│  │  │  ├─ preparation.png
│  │  │  ├─ sort.png
│  │  │  ├─ start-end.png
│  │  │  ├─ stored-data.png
│  │  │  └─ summing-junction.png
│  │  ├─ framework
│  │  │  ├─ angular.png
│  │  │  ├─ backbone.png
│  │  │  ├─ camel.png
│  │  │  ├─ django.png
│  │  │  ├─ ember.png
│  │  │  ├─ fastapi.png
│  │  │  ├─ flask.png
│  │  │  ├─ flutter.png
│  │  │  ├─ graphql.png
│  │  │  ├─ hibernate.png
│  │  │  ├─ jhipster.png
│  │  │  ├─ laravel.png
│  │  │  ├─ micronaut.png
│  │  │  ├─ quarkus.png
│  │  │  ├─ rails.png
│  │  │  ├─ react.png
│  │  │  ├─ spring.png
│  │  │  ├─ starlette.png
│  │  │  ├─ svelte.png
│  │  │  └─ vue.png
│  │  ├─ language
│  │  │  ├─ bash.png
│  │  │  ├─ c.png
│  │  │  ├─ cpp.png
│  │  │  ├─ csharp.png
│  │  │  ├─ dart.png
│  │  │  ├─ elixir.png
│  │  │  ├─ erlang.png
│  │  │  ├─ go.png
│  │  │  ├─ java.png
│  │  │  ├─ javascript.png
│  │  │  ├─ kotlin.png
│  │  │  ├─ latex.png
│  │  │  ├─ matlab.png
│  │  │  ├─ nodejs.png
│  │  │  ├─ php.png
│  │  │  ├─ python.png
│  │  │  ├─ r.png
│  │  │  ├─ ruby.png
│  │  │  ├─ rust.png
│  │  │  ├─ scala.png
│  │  │  ├─ swift.png
│  │  │  └─ typescript.png
│  │  └─ runtime
│  │     └─ dapr.png
│  └─ saas
│     ├─ alerting
│     │  ├─ newrelic.png
│     │  ├─ opsgenie.png
│     │  ├─ pagerduty.png
│     │  ├─ pushover.png
│     │  └─ xmatters.png
│     ├─ analytics
│     │  ├─ dataform.png
│     │  ├─ snowflake.png
│     │  └─ stitch.png
│     ├─ cdn
│     │  ├─ akamai.png
│     │  ├─ cloudflare.png
│     │  └─ fastly.png
│     ├─ chat
│     │  ├─ discord.png
│     │  ├─ line.png
│     │  ├─ mattermost.png
│     │  ├─ messenger.png
│     │  ├─ rocket-chat.png
│     │  ├─ slack.png
│     │  ├─ teams.png
│     │  └─ telegram.png
│     ├─ communication
│     │  └─ twilio.png
│     ├─ filesharing
│     │  └─ nextcloud.png
│     ├─ identity
│     │  ├─ auth0.png
│     │  └─ okta.png
│     ├─ logging
│     │  ├─ datadog.png
│     │  ├─ newrelic.png
│     │  └─ papertrail.png
│     ├─ media
│     │  └─ cloudinary.png
│     ├─ recommendation
│     │  └─ recombee.png
│     └─ social
│        ├─ facebook.png
│        └─ twitter.png
├─ scripts
│  ├─ generate.py
│  ├─ resource.py
│  └─ __init__.py
├─ templates
│  ├─ apidoc.tmpl
│  ├─ apidoc_custom.tmpl
│  └─ module.tmpl
├─ tests
│  ├─ test_c4.py
│  ├─ test_diagram.py
│  └─ __init__.py
├─ typed_ast
│  ├─ ast27.py
│  ├─ ast3.py
│  ├─ conversions.py
│  ├─ tests
│  │  └─ test_basics.py
│  ├─ _ast27.cp311-win_amd64.pyd
│  ├─ _ast3.cp311-win_amd64.pyd
│  └─ __init__.py
├─ website
│  ├─ core
│  │  └─ Footer.js
│  ├─ i18n
│  │  └─ en.json
│  ├─ package.json
│  ├─ pages
│  │  └─ en
│  │     └─ index.js
│  ├─ publish.sh
│  ├─ sidebars.json
│  ├─ siteConfig.js
│  ├─ static
│  │  ├─ css
│  │  │  └─ custom.css
│  │  └─ img
│  │     ├─ advanced_web_service_with_on-premises.png
│  │     ├─ advanced_web_service_with_on-premises_colored.png
│  │     ├─ c4.png
│  │     ├─ clustered_web_services_diagram.png
│  │     ├─ custom_local.png
│  │     ├─ custom_remote.png
│  │     ├─ diagrams.ico
│  │     ├─ diagrams.png
│  │     ├─ event_processing_code.png
│  │     ├─ event_processing_diagram.png
│  │     ├─ exposed_pod_with_3_replicas_diagram.png
│  │     ├─ grouped_workers_diagram.png
│  │     ├─ message_collecting_code.png
│  │     ├─ message_collecting_diagram.png
│  │     ├─ rabbitmq_consumers_diagram.png
│  │     ├─ resources
│  │     │  ├─ alibabacloud
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ analytic-db.png
│  │     │  │  │  ├─ click-house.png
│  │     │  │  │  ├─ data-lake-analytics.png
│  │     │  │  │  ├─ elatic-map-reduce.png
│  │     │  │  │  └─ open-search.png
│  │     │  │  ├─ application
│  │     │  │  │  ├─ api-gateway.png
│  │     │  │  │  ├─ bee-bot.png
│  │     │  │  │  ├─ blockchain-as-a-service.png
│  │     │  │  │  ├─ cloud-call-center.png
│  │     │  │  │  ├─ code-pipeline.png
│  │     │  │  │  ├─ direct-mail.png
│  │     │  │  │  ├─ log-service.png
│  │     │  │  │  ├─ message-notification-service.png
│  │     │  │  │  ├─ node-js-performance-platform.png
│  │     │  │  │  ├─ open-search.png
│  │     │  │  │  ├─ performance-testing-service.png
│  │     │  │  │  ├─ rd-cloud.png
│  │     │  │  │  ├─ smart-conversation-analysis.png
│  │     │  │  │  └─ yida.png
│  │     │  │  ├─ communication
│  │     │  │  │  ├─ direct-mail.png
│  │     │  │  │  └─ mobile-push.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ auto-scaling.png
│  │     │  │  │  ├─ batch-compute.png
│  │     │  │  │  ├─ container-registry.png
│  │     │  │  │  ├─ container-service.png
│  │     │  │  │  ├─ elastic-compute-service.png
│  │     │  │  │  ├─ elastic-container-instance.png
│  │     │  │  │  ├─ elastic-high-performance-computing.png
│  │     │  │  │  ├─ elastic-search.png
│  │     │  │  │  ├─ function-compute.png
│  │     │  │  │  ├─ operation-orchestration-service.png
│  │     │  │  │  ├─ resource-orchestration-service.png
│  │     │  │  │  ├─ server-load-balancer.png
│  │     │  │  │  ├─ serverless-app-engine.png
│  │     │  │  │  ├─ simple-application-server.png
│  │     │  │  │  └─ web-app-service.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ apsaradb-cassandra.png
│  │     │  │  │  ├─ apsaradb-hbase.png
│  │     │  │  │  ├─ apsaradb-memcache.png
│  │     │  │  │  ├─ apsaradb-mongodb.png
│  │     │  │  │  ├─ apsaradb-oceanbase.png
│  │     │  │  │  ├─ apsaradb-polardb.png
│  │     │  │  │  ├─ apsaradb-postgresql.png
│  │     │  │  │  ├─ apsaradb-ppas.png
│  │     │  │  │  ├─ apsaradb-redis.png
│  │     │  │  │  ├─ apsaradb-sqlserver.png
│  │     │  │  │  ├─ data-management-service.png
│  │     │  │  │  ├─ data-transmission-service.png
│  │     │  │  │  ├─ database-backup-service.png
│  │     │  │  │  ├─ disribute-relational-database-service.png
│  │     │  │  │  ├─ graph-database-service.png
│  │     │  │  │  ├─ hybriddb-for-mysql.png
│  │     │  │  │  └─ relational-database-service.png
│  │     │  │  ├─ iot
│  │     │  │  │  ├─ iot-internet-device-id.png
│  │     │  │  │  ├─ iot-link-wan.png
│  │     │  │  │  ├─ iot-mobile-connection-package.png
│  │     │  │  │  └─ iot-platform.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ cdn.png
│  │     │  │  │  ├─ cloud-enterprise-network.png
│  │     │  │  │  ├─ elastic-ip-address.png
│  │     │  │  │  ├─ express-connect.png
│  │     │  │  │  ├─ nat-gateway.png
│  │     │  │  │  ├─ server-load-balancer.png
│  │     │  │  │  ├─ smart-access-gateway.png
│  │     │  │  │  ├─ virtual-private-cloud.png
│  │     │  │  │  └─ vpn-gateway.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ anti-bot-service.png
│  │     │  │  │  ├─ anti-ddos-basic.png
│  │     │  │  │  ├─ anti-ddos-pro.png
│  │     │  │  │  ├─ antifraud-service.png
│  │     │  │  │  ├─ bastion-host.png
│  │     │  │  │  ├─ cloud-firewall.png
│  │     │  │  │  ├─ cloud-security-scanner.png
│  │     │  │  │  ├─ content-moderation.png
│  │     │  │  │  ├─ crowdsourced-security-testing.png
│  │     │  │  │  ├─ data-encryption-service.png
│  │     │  │  │  ├─ db-audit.png
│  │     │  │  │  ├─ game-shield.png
│  │     │  │  │  ├─ id-verification.png
│  │     │  │  │  ├─ managed-security-service.png
│  │     │  │  │  ├─ security-center.png
│  │     │  │  │  ├─ server-guard.png
│  │     │  │  │  ├─ ssl-certificates.png
│  │     │  │  │  └─ web-application-firewall.png
│  │     │  │  ├─ storage
│  │     │  │  │  ├─ cloud-storage-gateway.png
│  │     │  │  │  ├─ file-storage-hdfs.png
│  │     │  │  │  ├─ file-storage-nas.png
│  │     │  │  │  ├─ hybrid-backup-recovery.png
│  │     │  │  │  ├─ hybrid-cloud-disaster-recovery.png
│  │     │  │  │  ├─ imm.png
│  │     │  │  │  ├─ object-storage-service.png
│  │     │  │  │  └─ object-table-store.png
│  │     │  │  └─ web
│  │     │  │     ├─ dns.png
│  │     │  │     └─ domain.png
│  │     │  ├─ aws
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ amazon-opensearch-service.png
│  │     │  │  │  ├─ analytics.png
│  │     │  │  │  ├─ athena.png
│  │     │  │  │  ├─ cloudsearch-search-documents.png
│  │     │  │  │  ├─ cloudsearch.png
│  │     │  │  │  ├─ data-lake-resource.png
│  │     │  │  │  ├─ data-pipeline.png
│  │     │  │  │  ├─ elasticsearch-service.png
│  │     │  │  │  ├─ emr-cluster.png
│  │     │  │  │  ├─ emr-engine-mapr-m3.png
│  │     │  │  │  ├─ emr-engine-mapr-m5.png
│  │     │  │  │  ├─ emr-engine-mapr-m7.png
│  │     │  │  │  ├─ emr-engine.png
│  │     │  │  │  ├─ emr-hdfs-cluster.png
│  │     │  │  │  ├─ emr.png
│  │     │  │  │  ├─ glue-crawlers.png
│  │     │  │  │  ├─ glue-data-catalog.png
│  │     │  │  │  ├─ glue.png
│  │     │  │  │  ├─ kinesis-data-analytics.png
│  │     │  │  │  ├─ kinesis-data-firehose.png
│  │     │  │  │  ├─ kinesis-data-streams.png
│  │     │  │  │  ├─ kinesis-video-streams.png
│  │     │  │  │  ├─ kinesis.png
│  │     │  │  │  ├─ lake-formation.png
│  │     │  │  │  ├─ managed-streaming-for-kafka.png
│  │     │  │  │  ├─ opensearch.png
│  │     │  │  │  ├─ quicksight.png
│  │     │  │  │  ├─ redshift-dense-compute-node.png
│  │     │  │  │  ├─ redshift-dense-storage-node.png
│  │     │  │  │  └─ redshift.png
│  │     │  │  ├─ ar
│  │     │  │  │  ├─ ar-vr.png
│  │     │  │  │  └─ sumerian.png
│  │     │  │  ├─ blockchain
│  │     │  │  │  ├─ blockchain-resource.png
│  │     │  │  │  ├─ blockchain.png
│  │     │  │  │  ├─ managed-blockchain.png
│  │     │  │  │  └─ quantum-ledger-database-qldb.png
│  │     │  │  ├─ business
│  │     │  │  │  ├─ alexa-for-business.png
│  │     │  │  │  ├─ business-applications.png
│  │     │  │  │  ├─ chime.png
│  │     │  │  │  └─ workmail.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ app-runner.png
│  │     │  │  │  ├─ application-auto-scaling-rounded.png
│  │     │  │  │  ├─ application-auto-scaling.png
│  │     │  │  │  ├─ batch-rounded.png
│  │     │  │  │  ├─ batch.png
│  │     │  │  │  ├─ compute-optimizer.png
│  │     │  │  │  ├─ compute-rounded.png
│  │     │  │  │  ├─ compute.png
│  │     │  │  │  ├─ ec2-ami.png
│  │     │  │  │  ├─ ec2-auto-scaling.png
│  │     │  │  │  ├─ ec2-container-registry-image.png
│  │     │  │  │  ├─ ec2-container-registry-registry.png
│  │     │  │  │  ├─ ec2-container-registry-rounded.png
│  │     │  │  │  ├─ ec2-container-registry.png
│  │     │  │  │  ├─ ec2-elastic-ip-address.png
│  │     │  │  │  ├─ ec2-image-builder.png
│  │     │  │  │  ├─ ec2-instance.png
│  │     │  │  │  ├─ ec2-instances.png
│  │     │  │  │  ├─ ec2-rescue.png
│  │     │  │  │  ├─ ec2-rounded.png
│  │     │  │  │  ├─ ec2-spot-instance.png
│  │     │  │  │  ├─ ec2.png
│  │     │  │  │  ├─ elastic-beanstalk-application.png
│  │     │  │  │  ├─ elastic-beanstalk-deployment.png
│  │     │  │  │  ├─ elastic-beanstalk-rounded.png
│  │     │  │  │  ├─ elastic-beanstalk.png
│  │     │  │  │  ├─ elastic-container-service-container.png
│  │     │  │  │  ├─ elastic-container-service-rounded.png
│  │     │  │  │  ├─ elastic-container-service-service.png
│  │     │  │  │  ├─ elastic-container-service.png
│  │     │  │  │  ├─ elastic-kubernetes-service-rounded.png
│  │     │  │  │  ├─ elastic-kubernetes-service.png
│  │     │  │  │  ├─ fargate-rounded.png
│  │     │  │  │  ├─ fargate.png
│  │     │  │  │  ├─ lambda-function.png
│  │     │  │  │  ├─ lambda-rounded.png
│  │     │  │  │  ├─ lambda.png
│  │     │  │  │  ├─ lightsail-rounded.png
│  │     │  │  │  ├─ lightsail.png
│  │     │  │  │  ├─ local-zones.png
│  │     │  │  │  ├─ outposts-rounded.png
│  │     │  │  │  ├─ outposts.png
│  │     │  │  │  ├─ serverless-application-repository-rounded.png
│  │     │  │  │  ├─ serverless-application-repository.png
│  │     │  │  │  ├─ thinkbox-deadline-rounded.png
│  │     │  │  │  ├─ thinkbox-deadline.png
│  │     │  │  │  ├─ thinkbox-draft-rounded.png
│  │     │  │  │  ├─ thinkbox-draft.png
│  │     │  │  │  ├─ thinkbox-frost-rounded.png
│  │     │  │  │  ├─ thinkbox-frost.png
│  │     │  │  │  ├─ thinkbox-krakatoa-rounded.png
│  │     │  │  │  ├─ thinkbox-krakatoa.png
│  │     │  │  │  ├─ thinkbox-sequoia-rounded.png
│  │     │  │  │  ├─ thinkbox-sequoia.png
│  │     │  │  │  ├─ thinkbox-stoke-rounded.png
│  │     │  │  │  ├─ thinkbox-stoke.png
│  │     │  │  │  ├─ thinkbox-xmesh-rounded.png
│  │     │  │  │  ├─ thinkbox-xmesh.png
│  │     │  │  │  ├─ vmware-cloud-on-aws-rounded.png
│  │     │  │  │  ├─ vmware-cloud-on-aws.png
│  │     │  │  │  └─ wavelength.png
│  │     │  │  ├─ cost
│  │     │  │  │  ├─ budgets.png
│  │     │  │  │  ├─ cost-and-usage-report.png
│  │     │  │  │  ├─ cost-explorer.png
│  │     │  │  │  ├─ cost-management.png
│  │     │  │  │  ├─ reserved-instance-reporting.png
│  │     │  │  │  └─ savings-plans.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ aurora-instance.png
│  │     │  │  │  ├─ aurora.png
│  │     │  │  │  ├─ database-migration-service-database-migration-workflow.png
│  │     │  │  │  ├─ database-migration-service.png
│  │     │  │  │  ├─ database.png
│  │     │  │  │  ├─ documentdb-mongodb-compatibility.png
│  │     │  │  │  ├─ dynamodb-attribute.png
│  │     │  │  │  ├─ dynamodb-attributes.png
│  │     │  │  │  ├─ dynamodb-dax.png
│  │     │  │  │  ├─ dynamodb-global-secondary-index.png
│  │     │  │  │  ├─ dynamodb-item.png
│  │     │  │  │  ├─ dynamodb-items.png
│  │     │  │  │  ├─ dynamodb-table.png
│  │     │  │  │  ├─ dynamodb.png
│  │     │  │  │  ├─ elasticache-cache-node.png
│  │     │  │  │  ├─ elasticache-for-memcached.png
│  │     │  │  │  ├─ elasticache-for-redis.png
│  │     │  │  │  ├─ elasticache.png
│  │     │  │  │  ├─ keyspaces-managed-apache-cassandra-service.png
│  │     │  │  │  ├─ neptune.png
│  │     │  │  │  ├─ quantum-ledger-database-qldb.png
│  │     │  │  │  ├─ rds-instance.png
│  │     │  │  │  ├─ rds-mariadb-instance.png
│  │     │  │  │  ├─ rds-mysql-instance.png
│  │     │  │  │  ├─ rds-on-vmware.png
│  │     │  │  │  ├─ rds-oracle-instance.png
│  │     │  │  │  ├─ rds-postgresql-instance.png
│  │     │  │  │  ├─ rds-sql-server-instance.png
│  │     │  │  │  ├─ rds.png
│  │     │  │  │  ├─ redshift-dense-compute-node.png
│  │     │  │  │  ├─ redshift-dense-storage-node.png
│  │     │  │  │  ├─ redshift.png
│  │     │  │  │  └─ timestream.png
│  │     │  │  ├─ devtools
│  │     │  │  │  ├─ cloud-development-kit.png
│  │     │  │  │  ├─ cloud9-resource.png
│  │     │  │  │  ├─ cloud9.png
│  │     │  │  │  ├─ codeartifact.png
│  │     │  │  │  ├─ codebuild.png
│  │     │  │  │  ├─ codecommit.png
│  │     │  │  │  ├─ codedeploy.png
│  │     │  │  │  ├─ codepipeline.png
│  │     │  │  │  ├─ codestar.png
│  │     │  │  │  ├─ command-line-interface.png
│  │     │  │  │  ├─ developer-tools.png
│  │     │  │  │  ├─ tools-and-sdks.png
│  │     │  │  │  └─ x-ray.png
│  │     │  │  ├─ enablement
│  │     │  │  │  ├─ customer-enablement.png
│  │     │  │  │  ├─ iq.png
│  │     │  │  │  ├─ managed-services.png
│  │     │  │  │  ├─ professional-services.png
│  │     │  │  │  └─ support.png
│  │     │  │  ├─ enduser
│  │     │  │  │  ├─ appstream-2-0.png
│  │     │  │  │  ├─ desktop-and-app-streaming.png
│  │     │  │  │  ├─ workdocs.png
│  │     │  │  │  ├─ worklink.png
│  │     │  │  │  └─ workspaces.png
│  │     │  │  ├─ engagement
│  │     │  │  │  ├─ connect.png
│  │     │  │  │  ├─ customer-engagement.png
│  │     │  │  │  ├─ pinpoint.png
│  │     │  │  │  ├─ simple-email-service-ses-email.png
│  │     │  │  │  └─ simple-email-service-ses.png
│  │     │  │  ├─ game
│  │     │  │  │  ├─ game-tech.png
│  │     │  │  │  └─ gamelift.png
│  │     │  │  ├─ general
│  │     │  │  │  ├─ client.png
│  │     │  │  │  ├─ disk.png
│  │     │  │  │  ├─ forums.png
│  │     │  │  │  ├─ general.png
│  │     │  │  │  ├─ generic-database.png
│  │     │  │  │  ├─ generic-firewall.png
│  │     │  │  │  ├─ generic-office-building.png
│  │     │  │  │  ├─ generic-saml-token.png
│  │     │  │  │  ├─ generic-sdk.png
│  │     │  │  │  ├─ internet-alt1.png
│  │     │  │  │  ├─ internet-alt2.png
│  │     │  │  │  ├─ internet-gateway.png
│  │     │  │  │  ├─ marketplace.png
│  │     │  │  │  ├─ mobile-client.png
│  │     │  │  │  ├─ multimedia.png
│  │     │  │  │  ├─ office-building.png
│  │     │  │  │  ├─ saml-token.png
│  │     │  │  │  ├─ sdk.png
│  │     │  │  │  ├─ ssl-padlock.png
│  │     │  │  │  ├─ tape-storage.png
│  │     │  │  │  ├─ toolkit.png
│  │     │  │  │  ├─ traditional-server.png
│  │     │  │  │  ├─ user.png
│  │     │  │  │  └─ users.png
│  │     │  │  ├─ integration
│  │     │  │  │  ├─ application-integration.png
│  │     │  │  │  ├─ appsync.png
│  │     │  │  │  ├─ console-mobile-application.png
│  │     │  │  │  ├─ event-resource.png
│  │     │  │  │  ├─ eventbridge-custom-event-bus-resource.png
│  │     │  │  │  ├─ eventbridge-default-event-bus-resource.png
│  │     │  │  │  ├─ eventbridge-saas-partner-event-bus-resource.png
│  │     │  │  │  ├─ eventbridge.png
│  │     │  │  │  ├─ express-workflows.png
│  │     │  │  │  ├─ mq.png
│  │     │  │  │  ├─ simple-notification-service-sns-email-notification.png
│  │     │  │  │  ├─ simple-notification-service-sns-http-notification.png
│  │     │  │  │  ├─ simple-notification-service-sns-topic.png
│  │     │  │  │  ├─ simple-notification-service-sns.png
│  │     │  │  │  ├─ simple-queue-service-sqs-message.png
│  │     │  │  │  ├─ simple-queue-service-sqs-queue.png
│  │     │  │  │  ├─ simple-queue-service-sqs.png
│  │     │  │  │  └─ step-functions.png
│  │     │  │  ├─ iot
│  │     │  │  │  ├─ freertos.png
│  │     │  │  │  ├─ internet-of-things.png
│  │     │  │  │  ├─ iot-1-click.png
│  │     │  │  │  ├─ iot-action.png
│  │     │  │  │  ├─ iot-actuator.png
│  │     │  │  │  ├─ iot-alexa-echo.png
│  │     │  │  │  ├─ iot-alexa-enabled-device.png
│  │     │  │  │  ├─ iot-alexa-skill.png
│  │     │  │  │  ├─ iot-alexa-voice-service.png
│  │     │  │  │  ├─ iot-analytics-channel.png
│  │     │  │  │  ├─ iot-analytics-data-set.png
│  │     │  │  │  ├─ iot-analytics-data-store.png
│  │     │  │  │  ├─ iot-analytics-notebook.png
│  │     │  │  │  ├─ iot-analytics-pipeline.png
│  │     │  │  │  ├─ iot-analytics.png
│  │     │  │  │  ├─ iot-bank.png
│  │     │  │  │  ├─ iot-bicycle.png
│  │     │  │  │  ├─ iot-button.png
│  │     │  │  │  ├─ iot-camera.png
│  │     │  │  │  ├─ iot-car.png
│  │     │  │  │  ├─ iot-cart.png
│  │     │  │  │  ├─ iot-certificate.png
│  │     │  │  │  ├─ iot-coffee-pot.png
│  │     │  │  │  ├─ iot-core.png
│  │     │  │  │  ├─ iot-desired-state.png
│  │     │  │  │  ├─ iot-device-defender.png
│  │     │  │  │  ├─ iot-device-gateway.png
│  │     │  │  │  ├─ iot-device-management.png
│  │     │  │  │  ├─ iot-door-lock.png
│  │     │  │  │  ├─ iot-events.png
│  │     │  │  │  ├─ iot-factory.png
│  │     │  │  │  ├─ iot-fire-tv-stick.png
│  │     │  │  │  ├─ iot-fire-tv.png
│  │     │  │  │  ├─ iot-generic.png
│  │     │  │  │  ├─ iot-greengrass-connector.png
│  │     │  │  │  ├─ iot-greengrass.png
│  │     │  │  │  ├─ iot-hardware-board.png
│  │     │  │  │  ├─ iot-house.png
│  │     │  │  │  ├─ iot-http.png
│  │     │  │  │  ├─ iot-http2.png
│  │     │  │  │  ├─ iot-jobs.png
│  │     │  │  │  ├─ iot-lambda.png
│  │     │  │  │  ├─ iot-lightbulb.png
│  │     │  │  │  ├─ iot-medical-emergency.png
│  │     │  │  │  ├─ iot-mqtt.png
│  │     │  │  │  ├─ iot-over-the-air-update.png
│  │     │  │  │  ├─ iot-policy-emergency.png
│  │     │  │  │  ├─ iot-policy.png
│  │     │  │  │  ├─ iot-reported-state.png
│  │     │  │  │  ├─ iot-rule.png
│  │     │  │  │  ├─ iot-sensor.png
│  │     │  │  │  ├─ iot-servo.png
│  │     │  │  │  ├─ iot-shadow.png
│  │     │  │  │  ├─ iot-simulator.png
│  │     │  │  │  ├─ iot-sitewise.png
│  │     │  │  │  ├─ iot-thermostat.png
│  │     │  │  │  ├─ iot-things-graph.png
│  │     │  │  │  ├─ iot-topic.png
│  │     │  │  │  ├─ iot-travel.png
│  │     │  │  │  ├─ iot-utility.png
│  │     │  │  │  └─ iot-windfarm.png
│  │     │  │  ├─ management
│  │     │  │  │  ├─ amazon-devops-guru.png
│  │     │  │  │  ├─ amazon-managed-grafana.png
│  │     │  │  │  ├─ amazon-managed-prometheus.png
│  │     │  │  │  ├─ amazon-managed-workflows-apache-airflow.png
│  │     │  │  │  ├─ auto-scaling.png
│  │     │  │  │  ├─ chatbot.png
│  │     │  │  │  ├─ cloudformation-change-set.png
│  │     │  │  │  ├─ cloudformation-stack.png
│  │     │  │  │  ├─ cloudformation-template.png
│  │     │  │  │  ├─ cloudformation.png
│  │     │  │  │  ├─ cloudtrail.png
│  │     │  │  │  ├─ cloudwatch-alarm.png
│  │     │  │  │  ├─ cloudwatch-event-event-based.png
│  │     │  │  │  ├─ cloudwatch-event-time-based.png
│  │     │  │  │  ├─ cloudwatch-rule.png
│  │     │  │  │  ├─ cloudwatch.png
│  │     │  │  │  ├─ codeguru.png
│  │     │  │  │  ├─ command-line-interface.png
│  │     │  │  │  ├─ config.png
│  │     │  │  │  ├─ control-tower.png
│  │     │  │  │  ├─ devops-guru.png
│  │     │  │  │  ├─ license-manager.png
│  │     │  │  │  ├─ managed-services.png
│  │     │  │  │  ├─ management-and-governance.png
│  │     │  │  │  ├─ management-console.png
│  │     │  │  │  ├─ opsworks-apps.png
│  │     │  │  │  ├─ opsworks-deployments.png
│  │     │  │  │  ├─ opsworks-instances.png
│  │     │  │  │  ├─ opsworks-layers.png
│  │     │  │  │  ├─ opsworks-monitoring.png
│  │     │  │  │  ├─ opsworks-permissions.png
│  │     │  │  │  ├─ opsworks-resources.png
│  │     │  │  │  ├─ opsworks-stack.png
│  │     │  │  │  ├─ opsworks.png
│  │     │  │  │  ├─ organizations-account.png
│  │     │  │  │  ├─ organizations-organizational-unit.png
│  │     │  │  │  ├─ organizations.png
│  │     │  │  │  ├─ personal-health-dashboard.png
│  │     │  │  │  ├─ proton.png
│  │     │  │  │  ├─ service-catalog.png
│  │     │  │  │  ├─ systems-manager-app-config.png
│  │     │  │  │  ├─ systems-manager-automation.png
│  │     │  │  │  ├─ systems-manager-documents.png
│  │     │  │  │  ├─ systems-manager-inventory.png
│  │     │  │  │  ├─ systems-manager-maintenance-windows.png
│  │     │  │  │  ├─ systems-manager-opscenter.png
│  │     │  │  │  ├─ systems-manager-parameter-store.png
│  │     │  │  │  ├─ systems-manager-patch-manager.png
│  │     │  │  │  ├─ systems-manager-run-command.png
│  │     │  │  │  ├─ systems-manager-state-manager.png
│  │     │  │  │  ├─ systems-manager.png
│  │     │  │  │  ├─ trusted-advisor-checklist-cost.png
│  │     │  │  │  ├─ trusted-advisor-checklist-fault-tolerant.png
│  │     │  │  │  ├─ trusted-advisor-checklist-performance.png
│  │     │  │  │  ├─ trusted-advisor-checklist-security.png
│  │     │  │  │  ├─ trusted-advisor-checklist.png
│  │     │  │  │  ├─ trusted-advisor.png
│  │     │  │  │  └─ well-architected-tool.png
│  │     │  │  ├─ media
│  │     │  │  │  ├─ elastic-transcoder.png
│  │     │  │  │  ├─ elemental-conductor.png
│  │     │  │  │  ├─ elemental-delta.png
│  │     │  │  │  ├─ elemental-live.png
│  │     │  │  │  ├─ elemental-mediaconnect.png
│  │     │  │  │  ├─ elemental-mediaconvert.png
│  │     │  │  │  ├─ elemental-medialive.png
│  │     │  │  │  ├─ elemental-mediapackage.png
│  │     │  │  │  ├─ elemental-mediastore.png
│  │     │  │  │  ├─ elemental-mediatailor.png
│  │     │  │  │  ├─ elemental-server.png
│  │     │  │  │  ├─ kinesis-video-streams.png
│  │     │  │  │  └─ media-services.png
│  │     │  │  ├─ migration
│  │     │  │  │  ├─ application-discovery-service.png
│  │     │  │  │  ├─ cloudendure-migration.png
│  │     │  │  │  ├─ database-migration-service.png
│  │     │  │  │  ├─ datasync-agent.png
│  │     │  │  │  ├─ datasync.png
│  │     │  │  │  ├─ migration-and-transfer.png
│  │     │  │  │  ├─ migration-hub.png
│  │     │  │  │  ├─ server-migration-service.png
│  │     │  │  │  ├─ snowball-edge.png
│  │     │  │  │  ├─ snowball.png
│  │     │  │  │  ├─ snowmobile.png
│  │     │  │  │  └─ transfer-for-sftp.png
│  │     │  │  ├─ ml
│  │     │  │  │  ├─ apache-mxnet-on-aws.png
│  │     │  │  │  ├─ augmented-ai.png
│  │     │  │  │  ├─ comprehend.png
│  │     │  │  │  ├─ deep-learning-amis.png
│  │     │  │  │  ├─ deep-learning-containers.png
│  │     │  │  │  ├─ deepcomposer.png
│  │     │  │  │  ├─ deeplens.png
│  │     │  │  │  ├─ deepracer.png
│  │     │  │  │  ├─ elastic-inference.png
│  │     │  │  │  ├─ forecast.png
│  │     │  │  │  ├─ fraud-detector.png
│  │     │  │  │  ├─ kendra.png
│  │     │  │  │  ├─ lex.png
│  │     │  │  │  ├─ machine-learning.png
│  │     │  │  │  ├─ personalize.png
│  │     │  │  │  ├─ polly.png
│  │     │  │  │  ├─ rekognition-image.png
│  │     │  │  │  ├─ rekognition-video.png
│  │     │  │  │  ├─ rekognition.png
│  │     │  │  │  ├─ sagemaker-ground-truth.png
│  │     │  │  │  ├─ sagemaker-model.png
│  │     │  │  │  ├─ sagemaker-notebook.png
│  │     │  │  │  ├─ sagemaker-training-job.png
│  │     │  │  │  ├─ sagemaker.png
│  │     │  │  │  ├─ tensorflow-on-aws.png
│  │     │  │  │  ├─ textract.png
│  │     │  │  │  ├─ transcribe.png
│  │     │  │  │  └─ translate.png
│  │     │  │  ├─ mobile
│  │     │  │  │  ├─ amplify.png
│  │     │  │  │  ├─ api-gateway-endpoint.png
│  │     │  │  │  ├─ api-gateway.png
│  │     │  │  │  ├─ appsync.png
│  │     │  │  │  ├─ device-farm.png
│  │     │  │  │  ├─ mobile.png
│  │     │  │  │  └─ pinpoint.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ api-gateway-endpoint.png
│  │     │  │  │  ├─ api-gateway.png
│  │     │  │  │  ├─ app-mesh.png
│  │     │  │  │  ├─ client-vpn.png
│  │     │  │  │  ├─ cloud-map.png
│  │     │  │  │  ├─ cloudfront-edge-location.png
│  │     │  │  │  ├─ cloudfront.png
│  │     │  │  │  ├─ direct-connect.png
│  │     │  │  │  ├─ elastic-load-balancing.png
│  │     │  │  │  ├─ elb-application-load-balancer.png
│  │     │  │  │  ├─ elb-classic-load-balancer.png
│  │     │  │  │  ├─ elb-network-load-balancer.png
│  │     │  │  │  ├─ endpoint.png
│  │     │  │  │  ├─ global-accelerator.png
│  │     │  │  │  ├─ internet-gateway.png
│  │     │  │  │  ├─ nacl.png
│  │     │  │  │  ├─ nat-gateway.png
│  │     │  │  │  ├─ network-firewall.png
│  │     │  │  │  ├─ networking-and-content-delivery.png
│  │     │  │  │  ├─ private-subnet.png
│  │     │  │  │  ├─ privatelink.png
│  │     │  │  │  ├─ public-subnet.png
│  │     │  │  │  ├─ route-53-hosted-zone.png
│  │     │  │  │  ├─ route-53.png
│  │     │  │  │  ├─ route-table.png
│  │     │  │  │  ├─ site-to-site-vpn.png
│  │     │  │  │  ├─ transit-gateway.png
│  │     │  │  │  ├─ vpc-customer-gateway.png
│  │     │  │  │  ├─ vpc-elastic-network-adapter.png
│  │     │  │  │  ├─ vpc-elastic-network-interface.png
│  │     │  │  │  ├─ vpc-flow-logs.png
│  │     │  │  │  ├─ vpc-peering.png
│  │     │  │  │  ├─ vpc-router.png
│  │     │  │  │  ├─ vpc-traffic-mirroring.png
│  │     │  │  │  ├─ vpc.png
│  │     │  │  │  ├─ vpn-connection.png
│  │     │  │  │  └─ vpn-gateway.png
│  │     │  │  ├─ quantum
│  │     │  │  │  ├─ braket.png
│  │     │  │  │  └─ quantum-technologies.png
│  │     │  │  ├─ robotics
│  │     │  │  │  ├─ robomaker-cloud-extension-ros.png
│  │     │  │  │  ├─ robomaker-development-environment.png
│  │     │  │  │  ├─ robomaker-fleet-management.png
│  │     │  │  │  ├─ robomaker-simulator.png
│  │     │  │  │  ├─ robomaker.png
│  │     │  │  │  └─ robotics.png
│  │     │  │  ├─ satellite
│  │     │  │  │  ├─ ground-station.png
│  │     │  │  │  └─ satellite.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ ad-connector.png
│  │     │  │  │  ├─ artifact.png
│  │     │  │  │  ├─ certificate-authority.png
│  │     │  │  │  ├─ certificate-manager.png
│  │     │  │  │  ├─ cloud-directory.png
│  │     │  │  │  ├─ cloudhsm.png
│  │     │  │  │  ├─ cognito.png
│  │     │  │  │  ├─ detective.png
│  │     │  │  │  ├─ directory-service.png
│  │     │  │  │  ├─ firewall-manager.png
│  │     │  │  │  ├─ guardduty.png
│  │     │  │  │  ├─ identity-and-access-management-iam-access-analyzer.png
│  │     │  │  │  ├─ identity-and-access-management-iam-add-on.png
│  │     │  │  │  ├─ identity-and-access-management-iam-aws-sts-alternate.png
│  │     │  │  │  ├─ identity-and-access-management-iam-aws-sts.png
│  │     │  │  │  ├─ identity-and-access-management-iam-data-encryption-key.png
│  │     │  │  │  ├─ identity-and-access-management-iam-encrypted-data.png
│  │     │  │  │  ├─ identity-and-access-management-iam-long-term-security-credential.png
│  │     │  │  │  ├─ identity-and-access-management-iam-mfa-token.png
│  │     │  │  │  ├─ identity-and-access-management-iam-permissions.png
│  │     │  │  │  ├─ identity-and-access-management-iam-role.png
│  │     │  │  │  ├─ identity-and-access-management-iam-temporary-security-credential.png
│  │     │  │  │  ├─ identity-and-access-management-iam.png
│  │     │  │  │  ├─ inspector-agent.png
│  │     │  │  │  ├─ inspector.png
│  │     │  │  │  ├─ key-management-service.png
│  │     │  │  │  ├─ macie.png
│  │     │  │  │  ├─ managed-microsoft-ad.png
│  │     │  │  │  ├─ resource-access-manager.png
│  │     │  │  │  ├─ secrets-manager.png
│  │     │  │  │  ├─ security-hub-finding.png
│  │     │  │  │  ├─ security-hub.png
│  │     │  │  │  ├─ security-identity-and-compliance.png
│  │     │  │  │  ├─ shield-advanced.png
│  │     │  │  │  ├─ shield.png
│  │     │  │  │  ├─ simple-ad.png
│  │     │  │  │  ├─ single-sign-on.png
│  │     │  │  │  ├─ waf-filtering-rule.png
│  │     │  │  │  └─ waf.png
│  │     │  │  └─ storage
│  │     │  │     ├─ backup.png
│  │     │  │     ├─ cloudendure-disaster-recovery.png
│  │     │  │     ├─ efs-infrequentaccess-primary-bg.png
│  │     │  │     ├─ efs-standard-primary-bg.png
│  │     │  │     ├─ elastic-block-store-ebs-snapshot.png
│  │     │  │     ├─ elastic-block-store-ebs-volume.png
│  │     │  │     ├─ elastic-block-store-ebs.png
│  │     │  │     ├─ elastic-file-system-efs-file-system.png
│  │     │  │     ├─ elastic-file-system-efs.png
│  │     │  │     ├─ fsx-for-lustre.png
│  │     │  │     ├─ fsx-for-windows-file-server.png
│  │     │  │     ├─ fsx.png
│  │     │  │     ├─ multiple-volumes-resource.png
│  │     │  │     ├─ s3-glacier-archive.png
│  │     │  │     ├─ s3-glacier-vault.png
│  │     │  │     ├─ s3-glacier.png
│  │     │  │     ├─ simple-storage-service-s3-bucket-with-objects.png
│  │     │  │     ├─ simple-storage-service-s3-bucket.png
│  │     │  │     ├─ simple-storage-service-s3-object.png
│  │     │  │     ├─ simple-storage-service-s3.png
│  │     │  │     ├─ snow-family-snowball-import-export.png
│  │     │  │     ├─ snowball-edge.png
│  │     │  │     ├─ snowball.png
│  │     │  │     ├─ snowmobile.png
│  │     │  │     ├─ storage-gateway-cached-volume.png
│  │     │  │     ├─ storage-gateway-non-cached-volume.png
│  │     │  │     ├─ storage-gateway-virtual-tape-library.png
│  │     │  │     ├─ storage-gateway.png
│  │     │  │     └─ storage.png
│  │     │  ├─ azure
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ analysis-services.png
│  │     │  │  │  ├─ data-explorer-clusters.png
│  │     │  │  │  ├─ data-factories.png
│  │     │  │  │  ├─ data-lake-analytics.png
│  │     │  │  │  ├─ data-lake-store-gen1.png
│  │     │  │  │  ├─ databricks.png
│  │     │  │  │  ├─ event-hub-clusters.png
│  │     │  │  │  ├─ event-hubs.png
│  │     │  │  │  ├─ hdinsightclusters.png
│  │     │  │  │  ├─ log-analytics-workspaces.png
│  │     │  │  │  ├─ stream-analytics-jobs.png
│  │     │  │  │  └─ synapse-analytics.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ app-services.png
│  │     │  │  │  ├─ automanaged-vm.png
│  │     │  │  │  ├─ availability-sets.png
│  │     │  │  │  ├─ batch-accounts.png
│  │     │  │  │  ├─ citrix-virtual-desktops-essentials.png
│  │     │  │  │  ├─ cloud-services-classic.png
│  │     │  │  │  ├─ cloud-services.png
│  │     │  │  │  ├─ cloudsimple-virtual-machines.png
│  │     │  │  │  ├─ container-apps.png
│  │     │  │  │  ├─ container-instances.png
│  │     │  │  │  ├─ container-registries.png
│  │     │  │  │  ├─ disk-encryption-sets.png
│  │     │  │  │  ├─ disk-snapshots.png
│  │     │  │  │  ├─ disks.png
│  │     │  │  │  ├─ function-apps.png
│  │     │  │  │  ├─ image-definitions.png
│  │     │  │  │  ├─ image-versions.png
│  │     │  │  │  ├─ kubernetes-services.png
│  │     │  │  │  ├─ mesh-applications.png
│  │     │  │  │  ├─ os-images.png
│  │     │  │  │  ├─ sap-hana-on-azure.png
│  │     │  │  │  ├─ service-fabric-clusters.png
│  │     │  │  │  ├─ shared-image-galleries.png
│  │     │  │  │  ├─ spring-cloud.png
│  │     │  │  │  ├─ vm-classic.png
│  │     │  │  │  ├─ vm-images.png
│  │     │  │  │  ├─ vm-linux.png
│  │     │  │  │  ├─ vm-scale-set.png
│  │     │  │  │  ├─ vm-windows.png
│  │     │  │  │  ├─ vm.png
│  │     │  │  │  └─ workspaces.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ blob-storage.png
│  │     │  │  │  ├─ cache-for-redis.png
│  │     │  │  │  ├─ cosmos-db.png
│  │     │  │  │  ├─ data-explorer-clusters.png
│  │     │  │  │  ├─ data-factory.png
│  │     │  │  │  ├─ data-lake.png
│  │     │  │  │  ├─ database-for-mariadb-servers.png
│  │     │  │  │  ├─ database-for-mysql-servers.png
│  │     │  │  │  ├─ database-for-postgresql-servers.png
│  │     │  │  │  ├─ elastic-database-pools.png
│  │     │  │  │  ├─ elastic-job-agents.png
│  │     │  │  │  ├─ instance-pools.png
│  │     │  │  │  ├─ managed-databases.png
│  │     │  │  │  ├─ sql-databases.png
│  │     │  │  │  ├─ sql-datawarehouse.png
│  │     │  │  │  ├─ sql-managed-instances.png
│  │     │  │  │  ├─ sql-server-stretch-databases.png
│  │     │  │  │  ├─ sql-servers.png
│  │     │  │  │  ├─ sql-vm.png
│  │     │  │  │  ├─ sql.png
│  │     │  │  │  ├─ ssis-lift-and-shift-ir.png
│  │     │  │  │  ├─ synapse-analytics.png
│  │     │  │  │  ├─ virtual-clusters.png
│  │     │  │  │  └─ virtual-datacenter.png
│  │     │  │  ├─ devops
│  │     │  │  │  ├─ application-insights.png
│  │     │  │  │  ├─ artifacts.png
│  │     │  │  │  ├─ boards.png
│  │     │  │  │  ├─ devops.png
│  │     │  │  │  ├─ devtest-labs.png
│  │     │  │  │  ├─ lab-services.png
│  │     │  │  │  ├─ pipelines.png
│  │     │  │  │  ├─ repos.png
│  │     │  │  │  └─ test-plans.png
│  │     │  │  ├─ general
│  │     │  │  │  ├─ allresources.png
│  │     │  │  │  ├─ azurehome.png
│  │     │  │  │  ├─ developertools.png
│  │     │  │  │  ├─ helpsupport.png
│  │     │  │  │  ├─ information.png
│  │     │  │  │  ├─ managementgroups.png
│  │     │  │  │  ├─ marketplace.png
│  │     │  │  │  ├─ quickstartcenter.png
│  │     │  │  │  ├─ recent.png
│  │     │  │  │  ├─ reservations.png
│  │     │  │  │  ├─ resource.png
│  │     │  │  │  ├─ resourcegroups.png
│  │     │  │  │  ├─ servicehealth.png
│  │     │  │  │  ├─ shareddashboard.png
│  │     │  │  │  ├─ subscriptions.png
│  │     │  │  │  ├─ support.png
│  │     │  │  │  ├─ supportrequests.png
│  │     │  │  │  ├─ tag.png
│  │     │  │  │  ├─ tags.png
│  │     │  │  │  ├─ templates.png
│  │     │  │  │  ├─ twousericon.png
│  │     │  │  │  ├─ userhealthicon.png
│  │     │  │  │  ├─ usericon.png
│  │     │  │  │  ├─ userprivacy.png
│  │     │  │  │  ├─ userresource.png
│  │     │  │  │  └─ whatsnew.png
│  │     │  │  ├─ identity
│  │     │  │  │  ├─ access-review.png
│  │     │  │  │  ├─ active-directory-connect-health.png
│  │     │  │  │  ├─ active-directory.png
│  │     │  │  │  ├─ ad-b2c.png
│  │     │  │  │  ├─ ad-domain-services.png
│  │     │  │  │  ├─ ad-identity-protection.png
│  │     │  │  │  ├─ ad-privileged-identity-management.png
│  │     │  │  │  ├─ app-registrations.png
│  │     │  │  │  ├─ conditional-access.png
│  │     │  │  │  ├─ enterprise-applications.png
│  │     │  │  │  ├─ groups.png
│  │     │  │  │  ├─ identity-governance.png
│  │     │  │  │  ├─ information-protection.png
│  │     │  │  │  ├─ managed-identities.png
│  │     │  │  │  └─ users.png
│  │     │  │  ├─ integration
│  │     │  │  │  ├─ api-for-fhir.png
│  │     │  │  │  ├─ api-management.png
│  │     │  │  │  ├─ app-configuration.png
│  │     │  │  │  ├─ data-catalog.png
│  │     │  │  │  ├─ event-grid-domains.png
│  │     │  │  │  ├─ event-grid-subscriptions.png
│  │     │  │  │  ├─ event-grid-topics.png
│  │     │  │  │  ├─ integration-accounts.png
│  │     │  │  │  ├─ integration-service-environments.png
│  │     │  │  │  ├─ logic-apps-custom-connector.png
│  │     │  │  │  ├─ logic-apps.png
│  │     │  │  │  ├─ partner-topic.png
│  │     │  │  │  ├─ sendgrid-accounts.png
│  │     │  │  │  ├─ service-bus-relays.png
│  │     │  │  │  ├─ service-bus.png
│  │     │  │  │  ├─ service-catalog-managed-application-definitions.png
│  │     │  │  │  ├─ software-as-a-service.png
│  │     │  │  │  ├─ storsimple-device-managers.png
│  │     │  │  │  └─ system-topic.png
│  │     │  │  ├─ iot
│  │     │  │  │  ├─ device-provisioning-services.png
│  │     │  │  │  ├─ digital-twins.png
│  │     │  │  │  ├─ iot-central-applications.png
│  │     │  │  │  ├─ iot-hub-security.png
│  │     │  │  │  ├─ iot-hub.png
│  │     │  │  │  ├─ maps.png
│  │     │  │  │  ├─ sphere.png
│  │     │  │  │  ├─ time-series-insights-environments.png
│  │     │  │  │  ├─ time-series-insights-events-sources.png
│  │     │  │  │  └─ windows-10-iot-core-services.png
│  │     │  │  ├─ migration
│  │     │  │  │  ├─ data-box-edge.png
│  │     │  │  │  ├─ data-box.png
│  │     │  │  │  ├─ database-migration-services.png
│  │     │  │  │  ├─ migration-projects.png
│  │     │  │  │  └─ recovery-services-vaults.png
│  │     │  │  ├─ ml
│  │     │  │  │  ├─ batch-ai.png
│  │     │  │  │  ├─ bot-services.png
│  │     │  │  │  ├─ cognitive-services.png
│  │     │  │  │  ├─ genomics-accounts.png
│  │     │  │  │  ├─ machine-learning-service-workspaces.png
│  │     │  │  │  ├─ machine-learning-studio-web-service-plans.png
│  │     │  │  │  ├─ machine-learning-studio-web-services.png
│  │     │  │  │  └─ machine-learning-studio-workspaces.png
│  │     │  │  ├─ mobile
│  │     │  │  │  ├─ app-service-mobile.png
│  │     │  │  │  ├─ mobile-engagement.png
│  │     │  │  │  └─ notification-hubs.png
│  │     │  │  ├─ monitor
│  │     │  │  │  ├─ change-analysis.png
│  │     │  │  │  ├─ logs.png
│  │     │  │  │  ├─ metrics.png
│  │     │  │  │  └─ monitor.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ application-gateway.png
│  │     │  │  │  ├─ application-security-groups.png
│  │     │  │  │  ├─ cdn-profiles.png
│  │     │  │  │  ├─ connections.png
│  │     │  │  │  ├─ ddos-protection-plans.png
│  │     │  │  │  ├─ dns-private-zones.png
│  │     │  │  │  ├─ dns-zones.png
│  │     │  │  │  ├─ expressroute-circuits.png
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ front-doors.png
│  │     │  │  │  ├─ load-balancers.png
│  │     │  │  │  ├─ local-network-gateways.png
│  │     │  │  │  ├─ network-interfaces.png
│  │     │  │  │  ├─ network-security-groups-classic.png
│  │     │  │  │  ├─ network-watcher.png
│  │     │  │  │  ├─ on-premises-data-gateways.png
│  │     │  │  │  ├─ private-endpoint.png
│  │     │  │  │  ├─ public-ip-addresses.png
│  │     │  │  │  ├─ reserved-ip-addresses-classic.png
│  │     │  │  │  ├─ route-filters.png
│  │     │  │  │  ├─ route-tables.png
│  │     │  │  │  ├─ service-endpoint-policies.png
│  │     │  │  │  ├─ subnets.png
│  │     │  │  │  ├─ traffic-manager-profiles.png
│  │     │  │  │  ├─ virtual-network-classic.png
│  │     │  │  │  ├─ virtual-network-gateways.png
│  │     │  │  │  ├─ virtual-networks.png
│  │     │  │  │  └─ virtual-wans.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ application-security-groups.png
│  │     │  │  │  ├─ conditional-access.png
│  │     │  │  │  ├─ defender.png
│  │     │  │  │  ├─ extended-security-updates.png
│  │     │  │  │  ├─ key-vaults.png
│  │     │  │  │  ├─ security-center.png
│  │     │  │  │  └─ sentinel.png
│  │     │  │  ├─ storage
│  │     │  │  │  ├─ archive-storage.png
│  │     │  │  │  ├─ azurefxtedgefiler.png
│  │     │  │  │  ├─ blob-storage.png
│  │     │  │  │  ├─ data-box-edge-data-box-gateway.png
│  │     │  │  │  ├─ data-box.png
│  │     │  │  │  ├─ data-lake-storage.png
│  │     │  │  │  ├─ general-storage.png
│  │     │  │  │  ├─ netapp-files.png
│  │     │  │  │  ├─ queues-storage.png
│  │     │  │  │  ├─ storage-accounts-classic.png
│  │     │  │  │  ├─ storage-accounts.png
│  │     │  │  │  ├─ storage-explorer.png
│  │     │  │  │  ├─ storage-sync-services.png
│  │     │  │  │  ├─ storsimple-data-managers.png
│  │     │  │  │  ├─ storsimple-device-managers.png
│  │     │  │  │  └─ table-storage.png
│  │     │  │  └─ web
│  │     │  │     ├─ api-connections.png
│  │     │  │     ├─ app-service-certificates.png
│  │     │  │     ├─ app-service-domains.png
│  │     │  │     ├─ app-service-environments.png
│  │     │  │     ├─ app-service-plans.png
│  │     │  │     ├─ app-services.png
│  │     │  │     ├─ media-services.png
│  │     │  │     ├─ notification-hub-namespaces.png
│  │     │  │     ├─ search.png
│  │     │  │     └─ signalr.png
│  │     │  ├─ digitalocean
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ containers.png
│  │     │  │  │  ├─ docker.png
│  │     │  │  │  ├─ droplet-connect.png
│  │     │  │  │  ├─ droplet-snapshot.png
│  │     │  │  │  ├─ droplet.png
│  │     │  │  │  ├─ k8s-cluster.png
│  │     │  │  │  ├─ k8s-node-pool.png
│  │     │  │  │  └─ k8s-node.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ dbaas-primary-standby-more.png
│  │     │  │  │  ├─ dbaas-primary.png
│  │     │  │  │  ├─ dbaas-read-only.png
│  │     │  │  │  └─ dbaas-standby.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ certificate.png
│  │     │  │  │  ├─ domain-registration.png
│  │     │  │  │  ├─ domain.png
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ floating-ip.png
│  │     │  │  │  ├─ internet-gateway.png
│  │     │  │  │  ├─ load-balancer.png
│  │     │  │  │  ├─ managed-vpn.png
│  │     │  │  │  └─ vpc.png
│  │     │  │  └─ storage
│  │     │  │     ├─ folder.png
│  │     │  │     ├─ space.png
│  │     │  │     ├─ volume-snapshot.png
│  │     │  │     └─ volume.png
│  │     │  ├─ elastic
│  │     │  │  ├─ agent
│  │     │  │  │  ├─ agent.png
│  │     │  │  │  ├─ endpoint.png
│  │     │  │  │  ├─ fleet.png
│  │     │  │  │  └─ integrations.png
│  │     │  │  ├─ beats
│  │     │  │  │  ├─ apm.png
│  │     │  │  │  ├─ auditbeat.png
│  │     │  │  │  ├─ filebeat.png
│  │     │  │  │  ├─ functionbeat.png
│  │     │  │  │  ├─ heartbeat.png
│  │     │  │  │  ├─ metricbeat.png
│  │     │  │  │  ├─ packetbeat.png
│  │     │  │  │  └─ winlogbeat.png
│  │     │  │  ├─ elasticsearch
│  │     │  │  │  ├─ alerting.png
│  │     │  │  │  ├─ beats.png
│  │     │  │  │  ├─ elasticsearch.png
│  │     │  │  │  ├─ kibana.png
│  │     │  │  │  ├─ logstash-pipeline.png
│  │     │  │  │  ├─ logstash.png
│  │     │  │  │  ├─ machine-learning.png
│  │     │  │  │  ├─ map-services.png
│  │     │  │  │  ├─ maps.png
│  │     │  │  │  ├─ monitoring.png
│  │     │  │  │  ├─ searchable-snapshots.png
│  │     │  │  │  ├─ security-settings.png
│  │     │  │  │  ├─ sql.png
│  │     │  │  │  └─ stack.png
│  │     │  │  ├─ enterprisesearch
│  │     │  │  │  ├─ app-search.png
│  │     │  │  │  ├─ crawler.png
│  │     │  │  │  ├─ enterprise-search.png
│  │     │  │  │  ├─ site-search.png
│  │     │  │  │  └─ workplace-search.png
│  │     │  │  ├─ observability
│  │     │  │  │  ├─ apm.png
│  │     │  │  │  ├─ logs.png
│  │     │  │  │  ├─ metrics.png
│  │     │  │  │  ├─ observability.png
│  │     │  │  │  └─ uptime.png
│  │     │  │  ├─ orchestration
│  │     │  │  │  ├─ ece.png
│  │     │  │  │  └─ eck.png
│  │     │  │  ├─ saas
│  │     │  │  │  ├─ cloud.png
│  │     │  │  │  └─ elastic.png
│  │     │  │  └─ security
│  │     │  │     ├─ endpoint.png
│  │     │  │     ├─ security.png
│  │     │  │     ├─ siem.png
│  │     │  │     └─ xdr.png
│  │     │  ├─ firebase
│  │     │  │  ├─ base
│  │     │  │  │  └─ firebase.png
│  │     │  │  ├─ develop
│  │     │  │  │  ├─ authentication.png
│  │     │  │  │  ├─ firestore.png
│  │     │  │  │  ├─ functions.png
│  │     │  │  │  ├─ hosting.png
│  │     │  │  │  ├─ ml-kit.png
│  │     │  │  │  ├─ realtime-database.png
│  │     │  │  │  └─ storage.png
│  │     │  │  ├─ extentions
│  │     │  │  │  └─ extensions.png
│  │     │  │  ├─ grow
│  │     │  │  │  ├─ ab-testing.png
│  │     │  │  │  ├─ app-indexing.png
│  │     │  │  │  ├─ dynamic-links.png
│  │     │  │  │  ├─ in-app-messaging.png
│  │     │  │  │  ├─ invites.png
│  │     │  │  │  ├─ messaging.png
│  │     │  │  │  ├─ predictions.png
│  │     │  │  │  └─ remote-config.png
│  │     │  │  └─ quality
│  │     │  │     ├─ crash-reporting.png
│  │     │  │     ├─ crashlytics.png
│  │     │  │     ├─ performance-monitoring.png
│  │     │  │     └─ test-lab.png
│  │     │  ├─ gcp
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ bigquery.png
│  │     │  │  │  ├─ composer.png
│  │     │  │  │  ├─ data-catalog.png
│  │     │  │  │  ├─ data-fusion.png
│  │     │  │  │  ├─ dataflow.png
│  │     │  │  │  ├─ datalab.png
│  │     │  │  │  ├─ dataprep.png
│  │     │  │  │  ├─ dataproc.png
│  │     │  │  │  ├─ genomics.png
│  │     │  │  │  └─ pubsub.png
│  │     │  │  ├─ api
│  │     │  │  │  ├─ api-gateway.png
│  │     │  │  │  ├─ apigee.png
│  │     │  │  │  └─ endpoints.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ app-engine.png
│  │     │  │  │  ├─ compute-engine.png
│  │     │  │  │  ├─ container-optimized-os.png
│  │     │  │  │  ├─ functions.png
│  │     │  │  │  ├─ gke-on-prem.png
│  │     │  │  │  ├─ gpu.png
│  │     │  │  │  ├─ kubernetes-engine.png
│  │     │  │  │  └─ run.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ bigtable.png
│  │     │  │  │  ├─ datastore.png
│  │     │  │  │  ├─ firestore.png
│  │     │  │  │  ├─ memorystore.png
│  │     │  │  │  ├─ spanner.png
│  │     │  │  │  └─ sql.png
│  │     │  │  ├─ devtools
│  │     │  │  │  ├─ build.png
│  │     │  │  │  ├─ code-for-intellij.png
│  │     │  │  │  ├─ code.png
│  │     │  │  │  ├─ container-registry.png
│  │     │  │  │  ├─ gradle-app-engine-plugin.png
│  │     │  │  │  ├─ ide-plugins.png
│  │     │  │  │  ├─ maven-app-engine-plugin.png
│  │     │  │  │  ├─ scheduler.png
│  │     │  │  │  ├─ sdk.png
│  │     │  │  │  ├─ source-repositories.png
│  │     │  │  │  ├─ tasks.png
│  │     │  │  │  ├─ test-lab.png
│  │     │  │  │  ├─ tools-for-eclipse.png
│  │     │  │  │  ├─ tools-for-powershell.png
│  │     │  │  │  └─ tools-for-visual-studio.png
│  │     │  │  ├─ iot
│  │     │  │  │  └─ iot-core.png
│  │     │  │  ├─ migration
│  │     │  │  │  └─ transfer-appliance.png
│  │     │  │  ├─ ml
│  │     │  │  │  ├─ advanced-solutions-lab.png
│  │     │  │  │  ├─ ai-hub.png
│  │     │  │  │  ├─ ai-platform-data-labeling-service.png
│  │     │  │  │  ├─ ai-platform.png
│  │     │  │  │  ├─ automl-natural-language.png
│  │     │  │  │  ├─ automl-tables.png
│  │     │  │  │  ├─ automl-translation.png
│  │     │  │  │  ├─ automl-video-intelligence.png
│  │     │  │  │  ├─ automl-vision.png
│  │     │  │  │  ├─ automl.png
│  │     │  │  │  ├─ dialog-flow-enterprise-edition.png
│  │     │  │  │  ├─ inference-api.png
│  │     │  │  │  ├─ jobs-api.png
│  │     │  │  │  ├─ natural-language-api.png
│  │     │  │  │  ├─ recommendations-ai.png
│  │     │  │  │  ├─ speech-to-text.png
│  │     │  │  │  ├─ text-to-speech.png
│  │     │  │  │  ├─ tpu.png
│  │     │  │  │  ├─ translation-api.png
│  │     │  │  │  ├─ video-intelligence-api.png
│  │     │  │  │  └─ vision-api.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ armor.png
│  │     │  │  │  ├─ cdn.png
│  │     │  │  │  ├─ dedicated-interconnect.png
│  │     │  │  │  ├─ dns.png
│  │     │  │  │  ├─ external-ip-addresses.png
│  │     │  │  │  ├─ firewall-rules.png
│  │     │  │  │  ├─ load-balancing.png
│  │     │  │  │  ├─ nat.png
│  │     │  │  │  ├─ network.png
│  │     │  │  │  ├─ partner-interconnect.png
│  │     │  │  │  ├─ premium-network-tier.png
│  │     │  │  │  ├─ router.png
│  │     │  │  │  ├─ routes.png
│  │     │  │  │  ├─ standard-network-tier.png
│  │     │  │  │  ├─ traffic-director.png
│  │     │  │  │  ├─ virtual-private-cloud.png
│  │     │  │  │  └─ vpn.png
│  │     │  │  ├─ operations
│  │     │  │  │  ├─ logging.png
│  │     │  │  │  └─ monitoring.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ iam.png
│  │     │  │  │  ├─ iap.png
│  │     │  │  │  ├─ key-management-service.png
│  │     │  │  │  ├─ resource-manager.png
│  │     │  │  │  ├─ security-command-center.png
│  │     │  │  │  └─ security-scanner.png
│  │     │  │  └─ storage
│  │     │  │     ├─ filestore.png
│  │     │  │     ├─ persistent-disk.png
│  │     │  │     └─ storage.png
│  │     │  ├─ generic
│  │     │  │  ├─ blank
│  │     │  │  │  └─ blank.png
│  │     │  │  ├─ compute
│  │     │  │  │  └─ rack.png
│  │     │  │  ├─ database
│  │     │  │  │  └─ sql.png
│  │     │  │  ├─ device
│  │     │  │  │  ├─ mobile.png
│  │     │  │  │  └─ tablet.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ router.png
│  │     │  │  │  ├─ subnet.png
│  │     │  │  │  ├─ switch.png
│  │     │  │  │  └─ vpn.png
│  │     │  │  ├─ os
│  │     │  │  │  ├─ android.png
│  │     │  │  │  ├─ centos.png
│  │     │  │  │  ├─ debian.png
│  │     │  │  │  ├─ ios.png
│  │     │  │  │  ├─ linux-general.png
│  │     │  │  │  ├─ raspbian.png
│  │     │  │  │  ├─ red-hat.png
│  │     │  │  │  ├─ suse.png
│  │     │  │  │  ├─ ubuntu.png
│  │     │  │  │  └─ windows.png
│  │     │  │  ├─ place
│  │     │  │  │  └─ datacenter.png
│  │     │  │  ├─ storage
│  │     │  │  │  └─ storage.png
│  │     │  │  └─ virtualization
│  │     │  │     ├─ qemu.png
│  │     │  │     ├─ virtualbox.png
│  │     │  │     ├─ vmware.png
│  │     │  │     └─ xen.png
│  │     │  ├─ ibm
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ analytics.png
│  │     │  │  │  ├─ data-integration.png
│  │     │  │  │  ├─ data-repositories.png
│  │     │  │  │  ├─ device-analytics.png
│  │     │  │  │  └─ streaming-computing.png
│  │     │  │  ├─ applications
│  │     │  │  │  ├─ actionable-insight.png
│  │     │  │  │  ├─ annotate.png
│  │     │  │  │  ├─ api-developer-portal.png
│  │     │  │  │  ├─ api-polyglot-runtimes.png
│  │     │  │  │  ├─ app-server.png
│  │     │  │  │  ├─ application-logic.png
│  │     │  │  │  ├─ enterprise-applications.png
│  │     │  │  │  ├─ index.png
│  │     │  │  │  ├─ iot-application.png
│  │     │  │  │  ├─ microservice.png
│  │     │  │  │  ├─ mobile-app.png
│  │     │  │  │  ├─ ontology.png
│  │     │  │  │  ├─ open-source-tools.png
│  │     │  │  │  ├─ runtime-services.png
│  │     │  │  │  ├─ saas-applications.png
│  │     │  │  │  ├─ service-broker.png
│  │     │  │  │  ├─ speech-to-text.png
│  │     │  │  │  ├─ visual-recognition.png
│  │     │  │  │  └─ visualization.png
│  │     │  │  ├─ blockchain
│  │     │  │  │  ├─ blockchain-developer.png
│  │     │  │  │  ├─ blockchain.png
│  │     │  │  │  ├─ certificate-authority.png
│  │     │  │  │  ├─ client-application.png
│  │     │  │  │  ├─ communication.png
│  │     │  │  │  ├─ consensus.png
│  │     │  │  │  ├─ event-listener.png
│  │     │  │  │  ├─ event.png
│  │     │  │  │  ├─ existing-enterprise-systems.png
│  │     │  │  │  ├─ hyperledger-fabric.png
│  │     │  │  │  ├─ key-management.png
│  │     │  │  │  ├─ ledger.png
│  │     │  │  │  ├─ membership-services-provider-api.png
│  │     │  │  │  ├─ membership.png
│  │     │  │  │  ├─ message-bus.png
│  │     │  │  │  ├─ node.png
│  │     │  │  │  ├─ services.png
│  │     │  │  │  ├─ smart-contract.png
│  │     │  │  │  ├─ transaction-manager.png
│  │     │  │  │  └─ wallet.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ bare-metal-server.png
│  │     │  │  │  ├─ image-service.png
│  │     │  │  │  ├─ instance.png
│  │     │  │  │  ├─ key.png
│  │     │  │  │  └─ power-instance.png
│  │     │  │  ├─ data
│  │     │  │  │  ├─ caches.png
│  │     │  │  │  ├─ cloud.png
│  │     │  │  │  ├─ conversation-trained-deployed.png
│  │     │  │  │  ├─ data-services.png
│  │     │  │  │  ├─ data-sources.png
│  │     │  │  │  ├─ device-identity-service.png
│  │     │  │  │  ├─ device-registry.png
│  │     │  │  │  ├─ enterprise-data.png
│  │     │  │  │  ├─ enterprise-user-directory.png
│  │     │  │  │  ├─ file-repository.png
│  │     │  │  │  ├─ ground-truth.png
│  │     │  │  │  ├─ model.png
│  │     │  │  │  └─ tms-data-interface.png
│  │     │  │  ├─ devops
│  │     │  │  │  ├─ artifact-management.png
│  │     │  │  │  ├─ build-test.png
│  │     │  │  │  ├─ code-editor.png
│  │     │  │  │  ├─ collaborative-development.png
│  │     │  │  │  ├─ configuration-management.png
│  │     │  │  │  ├─ continuous-deploy.png
│  │     │  │  │  ├─ continuous-testing.png
│  │     │  │  │  ├─ devops.png
│  │     │  │  │  ├─ provision.png
│  │     │  │  │  └─ release-management.png
│  │     │  │  ├─ general
│  │     │  │  │  ├─ cloud-messaging.png
│  │     │  │  │  ├─ cloud-services.png
│  │     │  │  │  ├─ cloudant.png
│  │     │  │  │  ├─ cognitive-services.png
│  │     │  │  │  ├─ data-security.png
│  │     │  │  │  ├─ enterprise.png
│  │     │  │  │  ├─ governance-risk-compliance.png
│  │     │  │  │  ├─ ibm-containers.png
│  │     │  │  │  ├─ ibm-public-cloud.png
│  │     │  │  │  ├─ identity-access-management.png
│  │     │  │  │  ├─ identity-provider.png
│  │     │  │  │  ├─ infrastructure-security.png
│  │     │  │  │  ├─ internet.png
│  │     │  │  │  ├─ iot-cloud.png
│  │     │  │  │  ├─ microservices-application.png
│  │     │  │  │  ├─ microservices-mesh.png
│  │     │  │  │  ├─ monitoring-logging.png
│  │     │  │  │  ├─ monitoring.png
│  │     │  │  │  ├─ object-storage.png
│  │     │  │  │  ├─ offline-capabilities.png
│  │     │  │  │  ├─ openwhisk.png
│  │     │  │  │  ├─ peer-cloud.png
│  │     │  │  │  ├─ retrieve-rank.png
│  │     │  │  │  ├─ scalable.png
│  │     │  │  │  ├─ service-discovery-configuration.png
│  │     │  │  │  ├─ text-to-speech.png
│  │     │  │  │  └─ transformation-connectivity.png
│  │     │  │  ├─ infrastructure
│  │     │  │  │  ├─ channels.png
│  │     │  │  │  ├─ cloud-messaging.png
│  │     │  │  │  ├─ dashboard.png
│  │     │  │  │  ├─ diagnostics.png
│  │     │  │  │  ├─ edge-services.png
│  │     │  │  │  ├─ enterprise-messaging.png
│  │     │  │  │  ├─ event-feed.png
│  │     │  │  │  ├─ infrastructure-services.png
│  │     │  │  │  ├─ interservice-communication.png
│  │     │  │  │  ├─ load-balancing-routing.png
│  │     │  │  │  ├─ microservices-mesh.png
│  │     │  │  │  ├─ mobile-backend.png
│  │     │  │  │  ├─ mobile-provider-network.png
│  │     │  │  │  ├─ monitoring-logging.png
│  │     │  │  │  ├─ monitoring.png
│  │     │  │  │  ├─ peer-services.png
│  │     │  │  │  ├─ service-discovery-configuration.png
│  │     │  │  │  └─ transformation-connectivity.png
│  │     │  │  ├─ management
│  │     │  │  │  ├─ alert-notification.png
│  │     │  │  │  ├─ api-management.png
│  │     │  │  │  ├─ cloud-management.png
│  │     │  │  │  ├─ cluster-management.png
│  │     │  │  │  ├─ content-management.png
│  │     │  │  │  ├─ data-services.png
│  │     │  │  │  ├─ device-management.png
│  │     │  │  │  ├─ information-governance.png
│  │     │  │  │  ├─ it-service-management.png
│  │     │  │  │  ├─ management.png
│  │     │  │  │  ├─ monitoring-metrics.png
│  │     │  │  │  ├─ process-management.png
│  │     │  │  │  ├─ provider-cloud-portal-service.png
│  │     │  │  │  ├─ push-notifications.png
│  │     │  │  │  └─ service-management-tools.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ bridge.png
│  │     │  │  │  ├─ direct-link.png
│  │     │  │  │  ├─ enterprise.png
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ floating-ip.png
│  │     │  │  │  ├─ gateway.png
│  │     │  │  │  ├─ internet-services.png
│  │     │  │  │  ├─ load-balancer-listener.png
│  │     │  │  │  ├─ load-balancer-pool.png
│  │     │  │  │  ├─ load-balancer.png
│  │     │  │  │  ├─ load-balancing-routing.png
│  │     │  │  │  ├─ public-gateway.png
│  │     │  │  │  ├─ region.png
│  │     │  │  │  ├─ router.png
│  │     │  │  │  ├─ rules.png
│  │     │  │  │  ├─ subnet.png
│  │     │  │  │  ├─ transit-gateway.png
│  │     │  │  │  ├─ vpc.png
│  │     │  │  │  ├─ vpn-connection.png
│  │     │  │  │  ├─ vpn-gateway.png
│  │     │  │  │  └─ vpn-policy.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ api-security.png
│  │     │  │  │  ├─ blockchain-security-service.png
│  │     │  │  │  ├─ data-security.png
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ gateway.png
│  │     │  │  │  ├─ governance-risk-compliance.png
│  │     │  │  │  ├─ identity-access-management.png
│  │     │  │  │  ├─ identity-provider.png
│  │     │  │  │  ├─ infrastructure-security.png
│  │     │  │  │  ├─ physical-security.png
│  │     │  │  │  ├─ security-monitoring-intelligence.png
│  │     │  │  │  ├─ security-services.png
│  │     │  │  │  ├─ trustend-computing.png
│  │     │  │  │  └─ vpn.png
│  │     │  │  ├─ social
│  │     │  │  │  ├─ communities.png
│  │     │  │  │  ├─ file-sync.png
│  │     │  │  │  ├─ live-collaboration.png
│  │     │  │  │  ├─ messaging.png
│  │     │  │  │  └─ networking.png
│  │     │  │  ├─ storage
│  │     │  │  │  ├─ block-storage.png
│  │     │  │  │  └─ object-storage.png
│  │     │  │  └─ user
│  │     │  │     ├─ browser.png
│  │     │  │     ├─ device.png
│  │     │  │     ├─ integrated-digital-experiences.png
│  │     │  │     ├─ physical-entity.png
│  │     │  │     ├─ sensor.png
│  │     │  │     └─ user.png
│  │     │  ├─ k8s
│  │     │  │  ├─ chaos
│  │     │  │  │  ├─ chaos-mesh.png
│  │     │  │  │  └─ litmus-chaos.png
│  │     │  │  ├─ clusterconfig
│  │     │  │  │  ├─ hpa.png
│  │     │  │  │  ├─ limits.png
│  │     │  │  │  └─ quota.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ cronjob.png
│  │     │  │  │  ├─ deploy.png
│  │     │  │  │  ├─ ds.png
│  │     │  │  │  ├─ job.png
│  │     │  │  │  ├─ pod.png
│  │     │  │  │  ├─ rs.png
│  │     │  │  │  └─ sts.png
│  │     │  │  ├─ controlplane
│  │     │  │  │  ├─ api.png
│  │     │  │  │  ├─ c-c-m.png
│  │     │  │  │  ├─ c-m.png
│  │     │  │  │  ├─ k-proxy.png
│  │     │  │  │  ├─ kubelet.png
│  │     │  │  │  └─ sched.png
│  │     │  │  ├─ ecosystem
│  │     │  │  │  ├─ external-dns.png
│  │     │  │  │  ├─ helm.png
│  │     │  │  │  ├─ krew.png
│  │     │  │  │  └─ kustomize.png
│  │     │  │  ├─ group
│  │     │  │  │  └─ ns.png
│  │     │  │  ├─ infra
│  │     │  │  │  ├─ etcd.png
│  │     │  │  │  ├─ master.png
│  │     │  │  │  └─ node.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ ep.png
│  │     │  │  │  ├─ ing.png
│  │     │  │  │  ├─ netpol.png
│  │     │  │  │  └─ svc.png
│  │     │  │  ├─ others
│  │     │  │  │  ├─ crd.png
│  │     │  │  │  └─ psp.png
│  │     │  │  ├─ podconfig
│  │     │  │  │  ├─ cm.png
│  │     │  │  │  └─ secret.png
│  │     │  │  ├─ rbac
│  │     │  │  │  ├─ c-role.png
│  │     │  │  │  ├─ crb.png
│  │     │  │  │  ├─ group.png
│  │     │  │  │  ├─ rb.png
│  │     │  │  │  ├─ role.png
│  │     │  │  │  ├─ sa.png
│  │     │  │  │  └─ user.png
│  │     │  │  └─ storage
│  │     │  │     ├─ pv.png
│  │     │  │     ├─ pvc.png
│  │     │  │     ├─ sc.png
│  │     │  │     └─ vol.png
│  │     │  ├─ oci
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ autoscale-white.png
│  │     │  │  │  ├─ autoscale.png
│  │     │  │  │  ├─ bm-white.png
│  │     │  │  │  ├─ bm.png
│  │     │  │  │  ├─ container-white.png
│  │     │  │  │  ├─ container.png
│  │     │  │  │  ├─ functions-white.png
│  │     │  │  │  ├─ functions.png
│  │     │  │  │  ├─ instance-pools-white.png
│  │     │  │  │  ├─ instance-pools.png
│  │     │  │  │  ├─ ocir-white.png
│  │     │  │  │  ├─ ocir.png
│  │     │  │  │  ├─ oke-white.png
│  │     │  │  │  ├─ oke.png
│  │     │  │  │  ├─ vm-white.png
│  │     │  │  │  └─ vm.png
│  │     │  │  ├─ connectivity
│  │     │  │  │  ├─ backbone-white.png
│  │     │  │  │  ├─ backbone.png
│  │     │  │  │  ├─ cdn-white.png
│  │     │  │  │  ├─ cdn.png
│  │     │  │  │  ├─ customer-datacenter.png
│  │     │  │  │  ├─ customer-datacntr-white.png
│  │     │  │  │  ├─ customer-premise-white.png
│  │     │  │  │  ├─ customer-premise.png
│  │     │  │  │  ├─ disconnected-regions-white.png
│  │     │  │  │  ├─ disconnected-regions.png
│  │     │  │  │  ├─ dns-white.png
│  │     │  │  │  ├─ dns.png
│  │     │  │  │  ├─ fast-connect-white.png
│  │     │  │  │  ├─ fast-connect.png
│  │     │  │  │  ├─ nat-gateway-white.png
│  │     │  │  │  ├─ nat-gateway.png
│  │     │  │  │  ├─ vpn-white.png
│  │     │  │  │  └─ vpn.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ autonomous-white.png
│  │     │  │  │  ├─ autonomous.png
│  │     │  │  │  ├─ bigdata-service-white.png
│  │     │  │  │  ├─ bigdata-service.png
│  │     │  │  │  ├─ database-service-white.png
│  │     │  │  │  ├─ database-service.png
│  │     │  │  │  ├─ dataflow-apache-white.png
│  │     │  │  │  ├─ dataflow-apache.png
│  │     │  │  │  ├─ dcat-white.png
│  │     │  │  │  ├─ dcat.png
│  │     │  │  │  ├─ dis-white.png
│  │     │  │  │  ├─ dis.png
│  │     │  │  │  ├─ dms-white.png
│  │     │  │  │  ├─ dms.png
│  │     │  │  │  ├─ science-white.png
│  │     │  │  │  ├─ science.png
│  │     │  │  │  ├─ stream-white.png
│  │     │  │  │  └─ stream.png
│  │     │  │  ├─ devops
│  │     │  │  │  ├─ api-gateway-white.png
│  │     │  │  │  ├─ api-gateway.png
│  │     │  │  │  ├─ api-service-white.png
│  │     │  │  │  ├─ api-service.png
│  │     │  │  │  ├─ resource-mgmt-white.png
│  │     │  │  │  └─ resource-mgmt.png
│  │     │  │  ├─ governance
│  │     │  │  │  ├─ audit-white.png
│  │     │  │  │  ├─ audit.png
│  │     │  │  │  ├─ compartments-white.png
│  │     │  │  │  ├─ compartments.png
│  │     │  │  │  ├─ groups-white.png
│  │     │  │  │  ├─ groups.png
│  │     │  │  │  ├─ logging-white.png
│  │     │  │  │  ├─ logging.png
│  │     │  │  │  ├─ ocid-white.png
│  │     │  │  │  ├─ ocid.png
│  │     │  │  │  ├─ policies-white.png
│  │     │  │  │  ├─ policies.png
│  │     │  │  │  ├─ tagging-white.png
│  │     │  │  │  └─ tagging.png
│  │     │  │  ├─ monitoring
│  │     │  │  │  ├─ alarm-white.png
│  │     │  │  │  ├─ alarm.png
│  │     │  │  │  ├─ email-white.png
│  │     │  │  │  ├─ email.png
│  │     │  │  │  ├─ events-white.png
│  │     │  │  │  ├─ events.png
│  │     │  │  │  ├─ health-check-white.png
│  │     │  │  │  ├─ health-check.png
│  │     │  │  │  ├─ notifications-white.png
│  │     │  │  │  ├─ notifications.png
│  │     │  │  │  ├─ queue-white.png
│  │     │  │  │  ├─ queue.png
│  │     │  │  │  ├─ search-white.png
│  │     │  │  │  ├─ search.png
│  │     │  │  │  ├─ telemetry-white.png
│  │     │  │  │  ├─ telemetry.png
│  │     │  │  │  ├─ workflow-white.png
│  │     │  │  │  └─ workflow.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ drg-white.png
│  │     │  │  │  ├─ drg.png
│  │     │  │  │  ├─ firewall-white.png
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  ├─ internet-gateway-white.png
│  │     │  │  │  ├─ internet-gateway.png
│  │     │  │  │  ├─ load-balancer-white.png
│  │     │  │  │  ├─ load-balancer.png
│  │     │  │  │  ├─ route-table-white.png
│  │     │  │  │  ├─ route-table.png
│  │     │  │  │  ├─ security-lists-white.png
│  │     │  │  │  ├─ security-lists.png
│  │     │  │  │  ├─ service-gateway-white.png
│  │     │  │  │  ├─ service-gateway.png
│  │     │  │  │  ├─ vcn-white.png
│  │     │  │  │  └─ vcn.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ cloud-guard-white.png
│  │     │  │  │  ├─ cloud-guard.png
│  │     │  │  │  ├─ ddos-white.png
│  │     │  │  │  ├─ ddos.png
│  │     │  │  │  ├─ encryption-white.png
│  │     │  │  │  ├─ encryption.png
│  │     │  │  │  ├─ id-access-white.png
│  │     │  │  │  ├─ id-access.png
│  │     │  │  │  ├─ key-management-white.png
│  │     │  │  │  ├─ key-management.png
│  │     │  │  │  ├─ max-security-zone-white.png
│  │     │  │  │  ├─ max-security-zone.png
│  │     │  │  │  ├─ vault-white.png
│  │     │  │  │  ├─ vault.png
│  │     │  │  │  ├─ waf-white.png
│  │     │  │  │  └─ waf.png
│  │     │  │  └─ storage
│  │     │  │     ├─ backup-restore-white.png
│  │     │  │     ├─ backup-restore.png
│  │     │  │     ├─ block-storage-clone-white.png
│  │     │  │     ├─ block-storage-clone.png
│  │     │  │     ├─ block-storage-white.png
│  │     │  │     ├─ block-storage.png
│  │     │  │     ├─ buckets-white.png
│  │     │  │     ├─ buckets.png
│  │     │  │     ├─ data-transfer-white.png
│  │     │  │     ├─ data-transfer.png
│  │     │  │     ├─ elastic-performance-white.png
│  │     │  │     ├─ elastic-performance.png
│  │     │  │     ├─ file-storage-white.png
│  │     │  │     ├─ file-storage.png
│  │     │  │     ├─ object-storage-white.png
│  │     │  │     ├─ object-storage.png
│  │     │  │     ├─ storage-gateway-white.png
│  │     │  │     └─ storage-gateway.png
│  │     │  ├─ onprem
│  │     │  │  ├─ aggregator
│  │     │  │  │  ├─ fluentd.png
│  │     │  │  │  └─ vector.png
│  │     │  │  ├─ analytics
│  │     │  │  │  ├─ beam.png
│  │     │  │  │  ├─ databricks.png
│  │     │  │  │  ├─ dbt.png
│  │     │  │  │  ├─ dremio.png
│  │     │  │  │  ├─ flink.png
│  │     │  │  │  ├─ hadoop.png
│  │     │  │  │  ├─ hive.png
│  │     │  │  │  ├─ metabase.png
│  │     │  │  │  ├─ norikra.png
│  │     │  │  │  ├─ powerbi.png
│  │     │  │  │  ├─ presto.png
│  │     │  │  │  ├─ singer.png
│  │     │  │  │  ├─ spark.png
│  │     │  │  │  ├─ storm.png
│  │     │  │  │  ├─ superset.png
│  │     │  │  │  ├─ tableau.png
│  │     │  │  │  └─ trino.png
│  │     │  │  ├─ auth
│  │     │  │  │  ├─ boundary.png
│  │     │  │  │  ├─ buzzfeed-sso.png
│  │     │  │  │  └─ oauth2-proxy.png
│  │     │  │  ├─ cd
│  │     │  │  │  ├─ spinnaker.png
│  │     │  │  │  ├─ tekton-cli.png
│  │     │  │  │  └─ tekton.png
│  │     │  │  ├─ certificates
│  │     │  │  │  ├─ cert-manager.png
│  │     │  │  │  └─ lets-encrypt.png
│  │     │  │  ├─ ci
│  │     │  │  │  ├─ circleci.png
│  │     │  │  │  ├─ concourseci.png
│  │     │  │  │  ├─ droneci.png
│  │     │  │  │  ├─ github-actions.png
│  │     │  │  │  ├─ gitlabci.png
│  │     │  │  │  ├─ jenkins.png
│  │     │  │  │  ├─ teamcity.png
│  │     │  │  │  ├─ travisci.png
│  │     │  │  │  └─ zuulci.png
│  │     │  │  ├─ client
│  │     │  │  │  ├─ client.png
│  │     │  │  │  ├─ user.png
│  │     │  │  │  └─ users.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ nomad.png
│  │     │  │  │  └─ server.png
│  │     │  │  ├─ container
│  │     │  │  │  ├─ containerd.png
│  │     │  │  │  ├─ crio.png
│  │     │  │  │  ├─ docker.png
│  │     │  │  │  ├─ firecracker.png
│  │     │  │  │  ├─ gvisor.png
│  │     │  │  │  ├─ k3s.png
│  │     │  │  │  ├─ lxc.png
│  │     │  │  │  └─ rkt.png
│  │     │  │  ├─ database
│  │     │  │  │  ├─ cassandra.png
│  │     │  │  │  ├─ clickhouse.png
│  │     │  │  │  ├─ cockroachdb.png
│  │     │  │  │  ├─ couchbase.png
│  │     │  │  │  ├─ couchdb.png
│  │     │  │  │  ├─ dgraph.png
│  │     │  │  │  ├─ druid.png
│  │     │  │  │  ├─ hbase.png
│  │     │  │  │  ├─ influxdb.png
│  │     │  │  │  ├─ janusgraph.png
│  │     │  │  │  ├─ mariadb.png
│  │     │  │  │  ├─ mongodb.png
│  │     │  │  │  ├─ mssql.png
│  │     │  │  │  ├─ mysql.png
│  │     │  │  │  ├─ neo4j.png
│  │     │  │  │  ├─ oracle.png
│  │     │  │  │  ├─ postgresql.png
│  │     │  │  │  └─ scylla.png
│  │     │  │  ├─ dns
│  │     │  │  │  ├─ coredns.png
│  │     │  │  │  └─ powerdns.png
│  │     │  │  ├─ etl
│  │     │  │  │  └─ embulk.png
│  │     │  │  ├─ gitops
│  │     │  │  │  ├─ argocd.png
│  │     │  │  │  ├─ flagger.png
│  │     │  │  │  └─ flux.png
│  │     │  │  ├─ groupware
│  │     │  │  │  └─ nextcloud.png
│  │     │  │  ├─ iac
│  │     │  │  │  ├─ ansible.png
│  │     │  │  │  ├─ atlantis.png
│  │     │  │  │  ├─ awx.png
│  │     │  │  │  ├─ puppet.png
│  │     │  │  │  └─ terraform.png
│  │     │  │  ├─ identity
│  │     │  │  │  └─ dex.png
│  │     │  │  ├─ inmemory
│  │     │  │  │  ├─ aerospike.png
│  │     │  │  │  ├─ hazelcast.png
│  │     │  │  │  ├─ memcached.png
│  │     │  │  │  └─ redis.png
│  │     │  │  ├─ logging
│  │     │  │  │  ├─ fluentbit.png
│  │     │  │  │  ├─ graylog.png
│  │     │  │  │  ├─ loki.png
│  │     │  │  │  ├─ rsyslog.png
│  │     │  │  │  └─ syslog-ng.png
│  │     │  │  ├─ messaging
│  │     │  │  │  └─ centrifugo.png
│  │     │  │  ├─ mlops
│  │     │  │  │  ├─ mlflow.png
│  │     │  │  │  └─ polyaxon.png
│  │     │  │  ├─ monitoring
│  │     │  │  │  ├─ cortex.png
│  │     │  │  │  ├─ datadog.png
│  │     │  │  │  ├─ dynatrace.png
│  │     │  │  │  ├─ grafana.png
│  │     │  │  │  ├─ humio.png
│  │     │  │  │  ├─ mimir.png
│  │     │  │  │  ├─ nagios.png
│  │     │  │  │  ├─ newrelic.png
│  │     │  │  │  ├─ prometheus-operator.png
│  │     │  │  │  ├─ prometheus.png
│  │     │  │  │  ├─ sentry.png
│  │     │  │  │  ├─ splunk.png
│  │     │  │  │  ├─ thanos.png
│  │     │  │  │  └─ zabbix.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ ambassador.png
│  │     │  │  │  ├─ apache.png
│  │     │  │  │  ├─ bind-9.png
│  │     │  │  │  ├─ caddy.png
│  │     │  │  │  ├─ consul.png
│  │     │  │  │  ├─ envoy.png
│  │     │  │  │  ├─ etcd.png
│  │     │  │  │  ├─ glassfish.png
│  │     │  │  │  ├─ gunicorn.png
│  │     │  │  │  ├─ haproxy.png
│  │     │  │  │  ├─ internet.png
│  │     │  │  │  ├─ istio.png
│  │     │  │  │  ├─ jbossas.png
│  │     │  │  │  ├─ jetty.png
│  │     │  │  │  ├─ kong.png
│  │     │  │  │  ├─ linkerd.png
│  │     │  │  │  ├─ nginx.png
│  │     │  │  │  ├─ ocelot.png
│  │     │  │  │  ├─ open-service-mesh.png
│  │     │  │  │  ├─ opnsense.png
│  │     │  │  │  ├─ pfsense.png
│  │     │  │  │  ├─ pomerium.png
│  │     │  │  │  ├─ powerdns.png
│  │     │  │  │  ├─ tomcat.png
│  │     │  │  │  ├─ traefik.png
│  │     │  │  │  ├─ tyk.png
│  │     │  │  │  ├─ vyos.png
│  │     │  │  │  ├─ wildfly.png
│  │     │  │  │  ├─ yarp.png
│  │     │  │  │  └─ zookeeper.png
│  │     │  │  ├─ proxmox
│  │     │  │  │  └─ pve.png
│  │     │  │  ├─ queue
│  │     │  │  │  ├─ activemq.png
│  │     │  │  │  ├─ celery.png
│  │     │  │  │  ├─ emqx.png
│  │     │  │  │  ├─ kafka.png
│  │     │  │  │  ├─ nats.png
│  │     │  │  │  ├─ rabbitmq.png
│  │     │  │  │  └─ zeromq.png
│  │     │  │  ├─ registry
│  │     │  │  │  ├─ harbor.png
│  │     │  │  │  └─ jfrog.png
│  │     │  │  ├─ search
│  │     │  │  │  └─ solr.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ bitwarden.png
│  │     │  │  │  ├─ trivy.png
│  │     │  │  │  └─ vault.png
│  │     │  │  ├─ storage
│  │     │  │  │  ├─ ceph-osd.png
│  │     │  │  │  ├─ ceph.png
│  │     │  │  │  ├─ glusterfs.png
│  │     │  │  │  └─ portworx.png
│  │     │  │  ├─ tracing
│  │     │  │  │  ├─ jaeger.png
│  │     │  │  │  └─ tempo.png
│  │     │  │  ├─ vcs
│  │     │  │  │  ├─ git.png
│  │     │  │  │  ├─ gitea.png
│  │     │  │  │  ├─ github.png
│  │     │  │  │  ├─ gitlab.png
│  │     │  │  │  └─ svn.png
│  │     │  │  └─ workflow
│  │     │  │     ├─ airflow.png
│  │     │  │     ├─ digdag.png
│  │     │  │     ├─ kubeflow.png
│  │     │  │     └─ nifi.png
│  │     │  ├─ openstack
│  │     │  │  ├─ apiproxies
│  │     │  │  │  └─ ec2api.png
│  │     │  │  ├─ applicationlifecycle
│  │     │  │  │  ├─ freezer.png
│  │     │  │  │  ├─ masakari.png
│  │     │  │  │  ├─ murano.png
│  │     │  │  │  └─ solum.png
│  │     │  │  ├─ baremetal
│  │     │  │  │  ├─ cyborg.png
│  │     │  │  │  └─ ironic.png
│  │     │  │  ├─ billing
│  │     │  │  │  └─ cloudkitty.png
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ nova.png
│  │     │  │  │  ├─ qinling.png
│  │     │  │  │  └─ zun.png
│  │     │  │  ├─ containerservices
│  │     │  │  │  └─ kuryr.png
│  │     │  │  ├─ deployment
│  │     │  │  │  ├─ ansible.png
│  │     │  │  │  ├─ charms.png
│  │     │  │  │  ├─ chef.png
│  │     │  │  │  ├─ helm.png
│  │     │  │  │  ├─ kolla.png
│  │     │  │  │  └─ tripleo.png
│  │     │  │  ├─ frontend
│  │     │  │  │  └─ horizon.png
│  │     │  │  ├─ monitoring
│  │     │  │  │  ├─ monasca.png
│  │     │  │  │  └─ telemetry.png
│  │     │  │  ├─ multiregion
│  │     │  │  │  └─ tricircle.png
│  │     │  │  ├─ networking
│  │     │  │  │  ├─ designate.png
│  │     │  │  │  ├─ neutron.png
│  │     │  │  │  └─ octavia.png
│  │     │  │  ├─ nfv
│  │     │  │  │  └─ tacker.png
│  │     │  │  ├─ openstack.png
│  │     │  │  ├─ optimization
│  │     │  │  │  ├─ congress.png
│  │     │  │  │  ├─ rally.png
│  │     │  │  │  ├─ vitrage.png
│  │     │  │  │  └─ watcher.png
│  │     │  │  ├─ orchestration
│  │     │  │  │  ├─ blazar.png
│  │     │  │  │  ├─ heat.png
│  │     │  │  │  ├─ mistral.png
│  │     │  │  │  ├─ senlin.png
│  │     │  │  │  └─ zaqar.png
│  │     │  │  ├─ packaging
│  │     │  │  │  ├─ loci.png
│  │     │  │  │  ├─ puppet.png
│  │     │  │  │  └─ rpm.png
│  │     │  │  ├─ sharedservices
│  │     │  │  │  ├─ barbican.png
│  │     │  │  │  ├─ glance.png
│  │     │  │  │  ├─ karbor.png
│  │     │  │  │  ├─ keystone.png
│  │     │  │  │  └─ searchlight.png
│  │     │  │  ├─ storage
│  │     │  │  │  ├─ cinder.png
│  │     │  │  │  ├─ manila.png
│  │     │  │  │  └─ swift.png
│  │     │  │  ├─ user
│  │     │  │  │  └─ openstackclient.png
│  │     │  │  └─ workloadprovisioning
│  │     │  │     ├─ magnum.png
│  │     │  │     ├─ sahara.png
│  │     │  │     └─ trove.png
│  │     │  ├─ outscale
│  │     │  │  ├─ compute
│  │     │  │  │  ├─ compute.png
│  │     │  │  │  └─ direct-connect.png
│  │     │  │  ├─ network
│  │     │  │  │  ├─ client-vpn.png
│  │     │  │  │  ├─ internet-service.png
│  │     │  │  │  ├─ load-balancer.png
│  │     │  │  │  ├─ nat-service.png
│  │     │  │  │  ├─ net.png
│  │     │  │  │  └─ site-to-site-vpng.png
│  │     │  │  ├─ security
│  │     │  │  │  ├─ firewall.png
│  │     │  │  │  └─ identity-and-access-management.png
│  │     │  │  └─ storage
│  │     │  │     ├─ simple-storage-service.png
│  │     │  │     └─ storage.png
│  │     │  ├─ programming
│  │     │  │  ├─ flowchart
│  │     │  │  │  ├─ action.png
│  │     │  │  │  ├─ collate.png
│  │     │  │  │  ├─ database.png
│  │     │  │  │  ├─ decision.png
│  │     │  │  │  ├─ delay.png
│  │     │  │  │  ├─ display.png
│  │     │  │  │  ├─ document.png
│  │     │  │  │  ├─ input-output.png
│  │     │  │  │  ├─ inspection.png
│  │     │  │  │  ├─ internal-storage.png
│  │     │  │  │  ├─ loop-limit.png
│  │     │  │  │  ├─ manual-input.png
│  │     │  │  │  ├─ manual-loop.png
│  │     │  │  │  ├─ merge.png
│  │     │  │  │  ├─ multiple-documents.png
│  │     │  │  │  ├─ off-page-connector-left.png
│  │     │  │  │  ├─ off-page-connector-right.png
│  │     │  │  │  ├─ or.png
│  │     │  │  │  ├─ predefined-process.png
│  │     │  │  │  ├─ preparation.png
│  │     │  │  │  ├─ sort.png
│  │     │  │  │  ├─ start-end.png
│  │     │  │  │  ├─ stored-data.png
│  │     │  │  │  └─ summing-junction.png
│  │     │  │  ├─ framework
│  │     │  │  │  ├─ angular.png
│  │     │  │  │  ├─ backbone.png
│  │     │  │  │  ├─ camel.png
│  │     │  │  │  ├─ django.png
│  │     │  │  │  ├─ ember.png
│  │     │  │  │  ├─ fastapi.png
│  │     │  │  │  ├─ flask.png
│  │     │  │  │  ├─ flutter.png
│  │     │  │  │  ├─ graphql.png
│  │     │  │  │  ├─ hibernate.png
│  │     │  │  │  ├─ jhipster.png
│  │     │  │  │  ├─ laravel.png
│  │     │  │  │  ├─ micronaut.png
│  │     │  │  │  ├─ quarkus.png
│  │     │  │  │  ├─ rails.png
│  │     │  │  │  ├─ react.png
│  │     │  │  │  ├─ spring.png
│  │     │  │  │  ├─ starlette.png
│  │     │  │  │  ├─ svelte.png
│  │     │  │  │  └─ vue.png
│  │     │  │  ├─ language
│  │     │  │  │  ├─ bash.png
│  │     │  │  │  ├─ c.png
│  │     │  │  │  ├─ cpp.png
│  │     │  │  │  ├─ csharp.png
│  │     │  │  │  ├─ dart.png
│  │     │  │  │  ├─ elixir.png
│  │     │  │  │  ├─ erlang.png
│  │     │  │  │  ├─ go.png
│  │     │  │  │  ├─ java.png
│  │     │  │  │  ├─ javascript.png
│  │     │  │  │  ├─ kotlin.png
│  │     │  │  │  ├─ latex.png
│  │     │  │  │  ├─ matlab.png
│  │     │  │  │  ├─ nodejs.png
│  │     │  │  │  ├─ php.png
│  │     │  │  │  ├─ python.png
│  │     │  │  │  ├─ r.png
│  │     │  │  │  ├─ ruby.png
│  │     │  │  │  ├─ rust.png
│  │     │  │  │  ├─ scala.png
│  │     │  │  │  ├─ swift.png
│  │     │  │  │  └─ typescript.png
│  │     │  │  └─ runtime
│  │     │  │     └─ dapr.png
│  │     │  └─ saas
│  │     │     ├─ alerting
│  │     │     │  ├─ newrelic.png
│  │     │     │  ├─ opsgenie.png
│  │     │     │  ├─ pagerduty.png
│  │     │     │  ├─ pushover.png
│  │     │     │  └─ xmatters.png
│  │     │     ├─ analytics
│  │     │     │  ├─ dataform.png
│  │     │     │  ├─ snowflake.png
│  │     │     │  └─ stitch.png
│  │     │     ├─ cdn
│  │     │     │  ├─ akamai.png
│  │     │     │  ├─ cloudflare.png
│  │     │     │  └─ fastly.png
│  │     │     ├─ chat
│  │     │     │  ├─ discord.png
│  │     │     │  ├─ line.png
│  │     │     │  ├─ mattermost.png
│  │     │     │  ├─ messenger.png
│  │     │     │  ├─ rocket-chat.png
│  │     │     │  ├─ slack.png
│  │     │     │  ├─ teams.png
│  │     │     │  └─ telegram.png
│  │     │     ├─ communication
│  │     │     │  └─ twilio.png
│  │     │     ├─ filesharing
│  │     │     │  └─ nextcloud.png
│  │     │     ├─ identity
│  │     │     │  ├─ auth0.png
│  │     │     │  └─ okta.png
│  │     │     ├─ logging
│  │     │     │  ├─ datadog.png
│  │     │     │  ├─ newrelic.png
│  │     │     │  └─ papertrail.png
│  │     │     ├─ media
│  │     │     │  └─ cloudinary.png
│  │     │     ├─ recommendation
│  │     │     │  └─ recombee.png
│  │     │     └─ social
│  │     │        ├─ facebook.png
│  │     │        └─ twitter.png
│  │     ├─ simple_web_service_with_db_cluster_diagram.png
│  │     ├─ stateful_architecture_diagram.png
│  │     ├─ web_services_diagram.png
│  │     ├─ web_service_diagram.png
│  │     └─ workers_diagram.png
│  └─ yarn.lock
└─ web_service.png

```