# Harshavardhan Gowda
Cloud Devops Engineer 2 at Amazon Web Services (AWS) with 6+ years of experience. 

## Stuff I am good at:
- Linux system administration (I can exit vim without having to restart the server)
- Troubleshoot issues with complex distributed systems without blaming others
- Somewhat of an expert in Elasticache (Redis & Valkey) and Systems Manager
- In the process of mastering IaC (terraform), CI/CD (Github actions, Gitlab), Containers and Container Orchestration (Docker & Kubernetes) and Observability (Prometheus & Grafana)
- Use ChatGPT, Gemini and Claude to get things done and also untangle the mess they create

## Open Source Contributions

### HashiCorp - [terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws)

| PR | Description | Released In |
|----|-------------|-------------|
| [#48254](https://github.com/hashicorp/terraform-provider-aws/pull/48254) | Adding durability attribute to `aws_elasticache_replication_group` | v6.51.0 |
| [#48380](https://github.com/hashicorp/terraform-provider-aws/pull/48380) | Adding `network_type` argument for Serverless Caches | v6.51.0 |
| [#48897](https://github.com/hashicorp/terraform-provider-aws/pull/48897) | Scaffolding for new Lambda Microvms service | N/A |
| [#48950](https://github.com/hashicorp/terraform-provider-aws/pull/48950) | New Resrouce: Lambda MicroVMs Image | Pending Review |
| [#48984](https://github.com/hashicorp/terraform-provider-aws/pull/48984) | New Resource: `aws_lambdamicrovms_microvm` | Pending Review |

## Certifications

### AWS
<div>
  <img src="/assets/aws-certified-ai-practitioner.png" height=150 width=150> 
  <img src="/assets/aws-certified-cloud-practitioner.png" height=150 width=150>
  <img src="/assets/aws-certified-solutions-architect-associate.png" height=150 width=150>
  <img src="/assets/aws-certified-developer-associate.png" height=150 width=150>
  <img src="/assets/aws-certified-cloudops-engineer-associate.png" height=150 width=150>
  <img src="/assets/aws-certified-devops-engineer-professional.png" height=150 width=150>
</div>

### AWS Subject Matter Expert

<div>
  <img src="/assets/systems-manager-subject-matter-expert.png" height=150 width=150> 
  <img src="/assets/elasticache-subject-matter-expert.png" height=150 width=150>
</div>

### Kubernetes

<div>
  <img src="/assets/kcna-kubernetes-and-cloud-native-associate.png" height=150 width=150> 
  <img src="/assets/kcsa-kubernetes-and-cloud-native-security-associate.png" height=150 width=150>
</div>

## Peer Feedbacks

### Director, Software Engineering, AWS Elasticache CC

I want to take a moment to recognize @Gowda, Harshavardhan.
 
Harshavardhan has been an active SME for ElastiCache. More so, he has been very active in the internal ⬛︎⬛︎⬛︎redacted⬛︎⬛︎⬛︎ slack channel where he is constantly responding to queries from the TAM / Sas / Account Managers who are asking questions on behalf of their customers.
 
There are two key advantages to this: 
1. It reduces the burden on the engineering team to answer the questions
2. More importantly, I have seen at least on more than 6 occasions that responses from Harshavardhan have been accurate and spot-on which have averted an unnecessary support ticket or a service side ticket.
 
As an example, here is the latest issue: ⬛︎⬛︎⬛︎redacted⬛︎⬛︎⬛︎. The analysis of multiplexing and the fact at the results are actually being processes faster by the main thread is spot on! This definitely averted a service side ticket. In the process he has also helped educate a few of his own colleagues as well.
 
Thank you @Gowda, Harshavardhan for continuing to monitor this channel and provide the right feedback.

---

### Sr. Product Manager Technical - Elasticache
I wanted to share some positive feedback on Harshavardhan Gowda's recent contributions to the AWS Terraform provider for ElastiCache.

Harshavardhan proactively identified a gap in Terraform support following our [ElastiCache Durability launch](aws.amazon.com/about-aws/whats-new/2026/06/durability-amazon-elasticache) — the new durability attribute on `aws_elasticache_replication_group` was not yet available in the Terraform provider. Without being asked, he opened a PR [#48254](github.com/hashicorp/terraform-provider-aws/pull/48254), worked through HashiCorp's review feedback, and got it merged within days.

He then asked if there were other gaps he could help with. I pointed him to a missing `network_type parameter` on `aws_elasticache_serverless_cache` — a feature we launched in April that still had no Terraform support. He opened the GitHub issue, submitted the PR [#48380](https://github.com/hashicorp/terraform-provider-aws/pull/48380), and had it merged within a week. Both features shipped in terraform-provider-aws `v6.51.0`.

What stood out to me:
- **Proactive ownership**: He noticed the Terraform gap on his own and reached out to offer help rather than waiting to be assigned work.
- **Speed and quality**: Both PRs included acceptance tests, documentation updates, and regression testing. HashiCorp maintainers approved with minimal revision.
- **Follow-through**: He kept me updated at each stage and drove both contributions to completion independently.

**These contributions directly benefit ElastiCache customers who manage infrastructure with Terraform.**
