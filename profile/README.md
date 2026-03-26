<div align="center">
  <img src="https://raw.githubusercontent.com/Tandemn-Labs/.github/main/profile/githubBanner.png" alt="Tandemn" width="100%" />
</div>

# Welcome to Tandemn

> **Maximum performance. Minimum cost. On Your hardware.**
> Tandem is the inference optimization platform that makes GPU infrastructure run on autoplilot. Deploy your model, set your SLO, and let Tandem handle the rest. 

[Website](https://tandemn.com) | [Docs](https://github.com/Tandemn-Labs/Tandemn-docs) | [Contact](https://tandemn.com/contact.html)

---

## What we're building

### Tandem: Inference Optimization for Online and Batch Workloads

Tandem is the orchestration layer that runs in your own VPC or on-prem cluster. You specify the model and your SLO. Tandem then selects the right GPUs, routes traffic intelligently, forecasts whether deadlines will be met, and rebalances resources automatically as the task progresses.

### Online Inference: Minimum Cost, Maximum Availability

For production APIs, Tandem routes traffic across a hybrid of spot and serverless GPUs, giving you spot economics without spot reliability risk. Cold starts are eliminated, traffic spikes are absorbed automatically, and you get full cost transparency on every request. Up to 80% cheaper than always-on deployments. 

### Batch Inference: Maximum Throughput, Guaranteed Deadlines

For large workloads such as offline evals, dataset scoring, synthetic data generation, Tandem maximizes GPU utilization through continuous batching and prefill/decode optimization. It forecasts job completion before you submit, proactively scales if a deadline is at risk, and supports heterogeneous resources.

### Open Source

The inference engines powering Tandem are fully open source. This means no black boxes, no vendor lock-in, andtransparent benchmarks. [tandemn-vllm](https://github.com/Tandemn-Labs/tandemn-vllm) brings heterogeneous inference to mixed GPU fleets. Contributions welcome.

### Built for Your Infrastructure

Tandem installs once in your VPC or on-prem cluster. Works with heterogeneous GPU fleets, integrates with GCP, AWS, and Azure via SkyPilot, and requires zero changes to your existing model code.

---

## Get in touch

Follow us on [LinkedIn](https://www.linkedin.com/company/tandemn) for announcements and posts as we build out the product.
