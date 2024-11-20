# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## LLMs accelerated with eGPU on a Raspberry Pi 5
 - [https://www.jeffgeerling.com/blog/2024/llms-accelerated-egpu-on-raspberry-pi-5](https://www.jeffgeerling.com/blog/2024/llms-accelerated-egpu-on-raspberry-pi-5)
 - RSS feed: $source
 - date published: 2024-11-19T21:26:55+00:00

<span class="field field--name-title field--type-string field--label-hidden">LLMs accelerated with eGPU on a Raspberry Pi 5</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>After a long journey <a href="https://www.jeffgeerling.com/tags/gpu">getting AMD graphics cards working on the Raspberry Pi 5</a>, we finally have a stable patch for the <code>amdgpu</code> Linux kernel driver, and it works on AMD RX 400, 500, 6000, and (current-generation) 7000-series GPUs.</p>

<p>With that, we also have stable Vulkan graphics and compute API support.</p>

<p>When I wrote about <a href="https://www.jeffgeerling.com/blog/2024/amd-radeon-pro-w7700-running-on-raspberry-pi">getting a Radeon Pro W7700 running on the Pi</a>, I also mentioned <a href="https://github.com/ROCm/ROCm/issues/3960">AMD is not planning on supporting Arm</a> with their ROCm GPU acceleration framework. At least not anytime soon.</p>


