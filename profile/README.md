# Nodeox

GPUs available. A training job waiting. Getting the two together isn't always straightforward.

We're building the execution control plane for fragmented AI compute. Nodeox lets suitable training workloads use different GPU generations and vendors together. We measure where that helps—and where coordination adds overhead.

## Check the evidence

Our [E1-A benchmark](https://github.com/nodeoxai/e1-benchmark) contains 13 measurement extracts, methods and a Python calculation. You can check the October 2026 ViT-B/16 scaling and NVIDIA/AMD accuracy results without GPUs or a Nodeox account. The tests have different setups and keep their own baselines and limits.

## See the Workbench

![Accelerated Workbench replay of ViT-H/14 with LoRA on L40S and RTX 4090.](https://raw.githubusercontent.com/nodeoxai/e1-benchmark/main/assets/workbench-replay.gif)

A reconstructed 24-second replay of a measured 24:22 run on 2 November 2026: ViT-H/14 + LoRA on Oxford-IIIT Pet, using NVIDIA L40S and RTX 4090 GPUs. Final top-1 accuracy: 90.5% on 3,669 images. Accuracy after rounds 1–3 uses a 1,000-image subset; the final value uses all 3,669 test images. Phase proportions are reconstructed for display; identifiers and detailed execution and exchange logs are omitted. This is a separate product demonstration, outside the E1-A calculation package.

## Read more

- [How to benchmark mixed-GPU training without fooling yourself](https://nodeox.com/blog/benchmark-mixed-gpu-training)
- [What kept GPUs waiting: an E1 study of distributed training overhead](https://nodeox.com/blog/e1-distributed-training-overhead)

Have a training workload and GPUs you'd like to use together? Tell us what you need to run: [info@nodeox.com](mailto:info@nodeox.com).

[Website](https://nodeox.com) · [LinkedIn](https://www.linkedin.com/company/nodeox/) · [X](https://x.com/NodeoxAI)
