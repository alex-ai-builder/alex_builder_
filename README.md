# Hi, I'm Alex (The Infra Nerd) 🦦

**Building AI agents & fighting insane cloud bills. I test GPU infra so you don't have to.**

I spend my days spinning up instances, running benchmarks, and figuring out where to get the most TFLOPS for the least dollars. Here's my current stack and where I go for compute.

---

### 🖥️ My Go-To Compute Providers (Tested & Benchmarked)

*These are the platforms I actively use and monitor. (Yes, some are affiliate links, but I only list what I actually deploy on.)*

*   👉 **[RunPod](https://runpod.io?ref=fiaxk503)** - **Best for Serverless & Fast GPU Pods.** 
    *   *Why I use it:* When I need to deploy an LLM endpoint or a Stable Diffusion API fast. Their serverless cold starts are getting insanely good. I currently run my production inference jobs here.
*   👉 **[Vast.ai](https://cloud.vast.ai/?ref_id=407123)** - **Best for dirt-cheap raw compute.** 
    *   *Why I use it:* The absolute cheapest place to rent an RTX 4090 or A100. It's a peer-to-peer market, so I use this strictly for fine-tuning, training scripts, or temporary workloads where price matters more than 99.99% uptime. 
*   👉 **[Vultr](https://www.vultr.com/?ref=9868089)** - **Best for general Cloud & API Backends.** 
    *   *Why I use it:* When I just need a reliable Ubuntu instance in 30 seconds without the AWS IAM nightmares. Great global edge network for deploying the backend logic of my agents.

---

### 🛠️ The Tech Stack (What I use daily)

*   **Domains & DNS:** Cloudflare (Strictly for DNS routing) 
*   **Terminal / SSH:** Warp or plain old iTerm2.
*   **Current Fixation:** Optimizing vLLM batch sizes to squeeze out an extra 5% throughput.

---

### 📊 Latest Benchmark Highlights

*(I update this based on my X posts)*
*   **2026-03:** Pushing 70B models into production—comparing inference latency between serverless pods and dedicated instances.
*   **2026-02:** Saved 60% on monthly bills by migrating experimental training jobs to unverified hosts.

📫 **Catch my real-time rants and logs on X:** [@alex_builder_](https://x.com/alex_builder_)
